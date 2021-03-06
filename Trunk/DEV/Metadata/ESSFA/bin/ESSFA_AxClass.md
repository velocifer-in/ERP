   !AssetProposalDepreciationSplit_ES?tg5    ?  ESS_AssetMove?tg5?    CommonMethods_ES?tg5?  ?  ESS_AssetParameters?tg5\  e  ESS_AssetStockJournalCheckPost?tg5?   ?  $SMAServiceObjectRelationEvtHdlrClass?tg5?'  ?  "ESS_AssetProposalDepreciationSplit?tg5~*    .SMAServiceObjectRelationFormExtensionOverrides?tg5?8  6  AssetBookTbl_Extension?tg5?9  ?   !ESS_AssetTransferJournalCheckPost?tg5?:  ?  clearDimensionCache?tg5?A  v   LedgerJournalTablefrm_Extension?tg5B  (  LedgerJournalTable_EventHandler?tg5/C  n  AssetMgmt_ExtensionES?tg5?H  V  ? ! ?/// <summary>
///    The <c>AssetProposalDepreciationSplit_ES</c> class provides functionality for depreciation split.
/// </summary>
public class AssetProposalDepreciationSplit_ES extends RunBase
{
    AssetTable              getAssetTable;
    QueryRun                queryRun;
    AssetTransDate          assetTransDate;
    AssetTransDate          deprecPostDate;

    DialogField             dialogDepDate;
    DialogField             dialogPostDate;

    DimensionDisplayValue   journalNum;
    JournalNameId           journalNameId;
    JournalNameId           JournalName;
    Voucher                 voucher;
    LedgerJournalId         ledgerJournalId;
    ProjId                  projectId;
    
    #define.CurrentVersion(1)
    #define.version(1)

    #localmacro.CurrentList
        assetTransDate,
        deprecPostDate
    #endmacro

}RunBase   " getAssetTable 
AssetTable?" queryRun QueryRun?" assetTransDate AssetTransDate?" deprecPostDate AssetTransDate?" dialogDepDate DialogField?" dialogPostDate DialogField?" 
journalNum DimensionDisplayValue?" journalNameId JournalNameId?" JournalName JournalNameId?" voucher Voucher?" ledgerJournalId LedgerJournalId?" 	projectId ProjId?   ? 

adjustment?  ? ?? 
createJounalLines   ? _assetTrans 
AssetTrans?? 
_AsserList AssetList_ES?? _AssetTransferJourPost AssetTransferJourPost_ES?? _voucher Voucher?? _accountType LedgerJournalACType?? 
_ledgerAcc LedgerDimensionDefaultAccount?? 
_amountCur Amount?? isDebit boolean?? 
_dimension DimensionDefault?? 
_transDate 	TransDate?? ''_txt LedgerJournalTransTxt?? ""activityNumber ProjActivityNumber?? 0defaultDimension DimensionDefault??  ? ?? 
createJournal?  ? ?? 
dialog?  Object? ?? 
getFromDialog?  boolean? ?? 
getJournalName?  JournalNameId? ?? 
getLedgerAcc   ? 
assetTrans 
AssetTrans?? assetTransferJourPost AssetTransferJourPost_ES??  LedgerDimensionDefaultAccount? ?? 
parmJournalNameId   ? journalNameId_journalNameId JournalNameId??  JournalNameId? ?? 
parmJournalNum   ? 
journalNum_journalNum DimensionDisplayValue??  DimensionDisplayValue? ?? 

parmProjId   ? 	projectId_projId ProjId??  ProjId? ?? 
getLedgerAcc_Default   ? _assetTrans 
AssetTrans?? _locType AssetLocType_ES?? _locId AssetLocId_ES??  LedgerDimensionDefaultAccount? ?? 
getLedgerType   ? assetTransferJourPost AssetTransferJourPost_ES??  LedgerJournalACType? ?? 
getOffsetAcc   ? 
assetTrans 
AssetTrans??  LedgerDimensionDefaultAccount? ?? 
	getProjId   ? assetTransferJourTrans AssetTransferJourTrans_ES??  ProjId? ?? 
gettingLedgerDimensionAll   ? _ledgerJournalId LedgerDimensionDefaultAccount?? _assetId AssetId?? _assetListId AssetListId_ES?? defaultDimension DimensionDefault??  LedgerDimensionDefaultAccount??? 
gettingMainAccount   ? _defaultAccount LedgerDimensionDefaultAccount??  DimensionValue??? 
initInstance   ? _ledgerJournalTrans LedgerJournalTrans??  ? ?? 
initParmDefault?  ? ?? 
pack?   ? ?? 
parmVoucher   ? voucher_voucher Voucher??  Voucher? ?? 
queryRun?  QueryRun? ?? 

setVoucher?  ? ?? 
showQueryValues?  boolean? ?? 
unpack   ? _packedClass  ??  boolean? ?? 
updateAssetTrans   ? 
assetTrans 
AssetTrans??  ??? 
run?  ? ?? 	
main   ? _args Args??  ? ?? 
canRunInNewSession?  boolean? ?!AssetProposalDepreciationSplit_ES?? ! ?class  ESS_AssetMove extends AssetSplit
{
    AssetId         assetIdMove;
    TransDate       assetDate;
    ReasonComment   assetComment;

    DialogField     dialogAssetId;
    DialogField     dialogAssetDate;
    DialogField     dialogAssetReason;

    boolean         promptAssetId;

    AssetTable      assetTable;
    AssetTable      assetTableNew;

    FormDataSource  assetListSource;
    AssetList_ES       assetList;
    Amount          selectedAmt;


}
AssetSplit   " assetIdMove AssetId?" 	assetDate 	TransDate?" assetComment ReasonComment?" dialogAssetId DialogField?" dialogAssetDate DialogField?" dialogAssetReason DialogField?" promptAssetId boolean?" 
assetTable 
AssetTable?" assetTableNew 
AssetTable?" assetListSource FormDataSource?" 	assetList AssetList_ES?" selectedAmt Amount?   ? 
assetTableNew?  
AssetTable? ?? 
dialog?  Object? ?? 
getFromDialog?  boolean? ?? 
pack?   ? ?? 
parmAssetList   ? 	assetList
_assetList AssetList_ES??  AssetList_ES? ?? 
parmAssetListSource   ? _assetListSource FormDataSource??  FormDataSource? ?? 
parmAssetTable   ? 
assetTable_assetTable 
AssetTable??  
AssetTable? ?? 
run?  ? ?? 
unpack   ? packedClass  ??  boolean? ?? 
validate   ? null_calledFrom Object??  boolean? ?? 	
description?  ClassDescription? ?? 	
main   ? args Args??  ? ?ESS_AssetMove?? ! ?/// <summary>
///    The <c>CommonMethods_ES</c> class provides common static methods for asset management functionality.
/// </summary>
public class CommonMethods_ES
{
   
}   ? 	
replaceDefaultDimensions   ? _defaultDimension DimensionDefault?? _backEntityType TableId?? _key RecId?? _value  ?? ''_dimName  ??  DimensionDefault? ?? 	
serviceReplaceAttributeValue   ? _target DimensionDefault?? _source DimensionDefault?? _dimensionAttributeId RecId??  DimensionDefault? ?? 	
serverReplaceAttributeValue   ? _target DimensionDefault?? _source DimensionDefault?? _dimensionAttributeId RecId??  DimensionDefault??? 	
replaceAttributeValue   ? _parms  ??   ??? 	
findByAssetId   ? _assetId AssetId?? false
_forupdate boolean??  	AssetBook? ?CommonMethods_ES?? ! /public static class ESS_AssetParameters
{

}   ?     FormDataFieldEventHandler        AssetParameters? AssetParameters? AssetOffSource_ES? formDataFieldStr?     Modified?	 FormDataFieldEventType??	
AssetOffsetAcct_ES_OnModified   ? sender FormDataObject?? e FormDataFieldEventArgs??  ? ??     FormDataFieldEventHandler        AssetParameters? AssetParameters? AssetLedgerSource_ES? formDataFieldStr?     Modified?	 FormDataFieldEventType??	
AssetLedgerSource_ES_OnModified   ? sender FormDataObject?? e FormDataFieldEventArgs??  ? ??     FormDataSourceEventHandler        AssetParameters? AssetParameters? ? formDataSourceStr?     	Activated?	 FormDataSourceEventType??	
AssetParameters_OnActivated   ? sender FormDataSource?? e FormDataSourceEventArgs??  ? ??     FormControlEventHandler        AssetParameters? %AssetParameters_AssetTransJourName_ES? ? formControlStr?     Lookup?	 FormControlEventType??	
.AssetParameters_AssetTransJourName_ES_OnLookup   ? sender FormControl?? e FormControlEventArgs??  ? ??     FormControlEventHandler        AssetParameters? %AssetParameters_AssetAllocJourName_ES? ? formControlStr?     Lookup?	 FormControlEventType??	
.AssetParameters_AssetAllocJourName_ES_OnLookup   ? sender FormControl?? e FormControlEventArgs??  ? ??     FormControlEventHandler        AssetParameters? 'AssetParameters_AssetMoveJournalName_ES? ? formControlStr?     Lookup?	 FormControlEventType??	
0AssetParameters_AssetMoveJournalName_ES_OnLookup   ? sender FormControl?? e FormControlEventArgs??  ? ??     FormControlEventHandler        AssetParameters? %AssetParameters_AssetMgmtProjExpCatId? ? formControlStr?     Lookup?	 FormControlEventType??	
.AssetParameters_AssetMgmtProjExpCatId_OnLookup   ? sender FormControl?? e FormControlEventArgs??  ? ?ESS_AssetParameters?? ! ?class ESS_AssetStockJournalCheckPost extends RunBase
{
    LedgerJournalTable                ledgerJournalTable;
    AssetTransferJourTrans_ES            assetTransferJourTrans;
    FormDataSource                    formDataSource;
    TableId                           journalTableId;
    Common                            record;
    JournalCheckPostType              journalCheckPostType;
    Counter                           progressCounter;






}RunBase   " ledgerJournalTable LedgerJournalTable?" assetTransferJourTrans AssetTransferJourTrans_ES?" formDataSource FormDataSource?" journalTableId TableId?" record Common?" journalCheckPostType JournalCheckPostType?" progressCounter Counter?   ? 
checkJournal   ? 
_journalId 	JournalId??  boolean? ?? 
checkStockJournal   ? 
_journalId 	JournalId?? falseisPost Boolean??  boolean? ?? 
createTransferJournal?  ? ?? 

numOfLines?   ? ?? 
parmJournalCheckPostType   ? journalCheckPostType_journalCheckPostType JournalCheckPostType??  JournalCheckPostType? ?? 
parmJournalDataSource   ? formDataSource_formDataSource FormDataSource??  FormDataSource? ?? 
parmJournalRecord   ? record_record Common??  common? ?? 
parmJournalTableId   ? journalTableId_tableId TableId??  TableId? ?? 
postJournal?  boolean? ?? 
progressUpdate   ? _text  ??  ? ?? 
run?  ? ?? 
updateSystemBlock   ? _ledgerJournalTable LedgerJournalTable?? trueset boolean??  ? ?? 
validate   ? null_calledFrom Object??  boolean? ?? 	
main   ? _args Args??  ? ?ESS_AssetStockJournalCheckPost?? ! 0class SMAServiceObjectRelationEvtHdlrClass
{
}   ?     FormDataFieldEventHandler        SMAServiceObjectRelation? SMAServiceObjectRelation? ESS_AssetListId? formDataFieldStr?     Modified?	 FormDataFieldEventType??	
ESS_AssetListId_OnModified   ? sender FormDataObject?? e FormDataFieldEventArgs??  ? ??     FormDataSourceEventHandler        SMAServiceObjectRelation? SMAServiceObjectRelation? ? formDataSourceStr?     Initialized?	 FormDataSourceEventType??	
&SMAServiceObjectRelation_OnInitialized   ? sender FormDataSource?? e FormDataSourceEventArgs??  ? ?$SMAServiceObjectRelationEvtHdlrClass?? ! ?public class ESS_AssetProposalDepreciationSplit extends RunBase
{
    AssetTable              getAssetTable;
    QueryRun                queryRun;
    AssetTransDate          assetTransDate;
    AssetTransDate          deprecPostDate;

    DialogField             dialogDepDate;
    DialogField             dialogPostDate;

    DimensionDisplayValue   journalNum;
    JournalNameId           journalNameId;
    JournalNameId           JournalName;
    Voucher                 voucher;
    LedgerJournalId         ledgerJournalId;
    ProjId                  projectId;

    #define.CurrentVersion(1)
    #define.version(1)

    #localmacro.CurrentList
        assetTransDate,
        deprecPostDate
    #endmacro




   

}RunBase   " getAssetTable 
AssetTable?" queryRun QueryRun?" assetTransDate AssetTransDate?" deprecPostDate AssetTransDate?" dialogDepDate DialogField?" dialogPostDate DialogField?" 
journalNum DimensionDisplayValue?" journalNameId JournalNameId?" JournalName JournalNameId?" voucher Voucher?" ledgerJournalId LedgerJournalId?" 	projectId ProjId?   ? 

adjestment?  ? ?? 
createJounalLines   ? _assetTrans 
AssetTrans?? 
_AssetList AssetList_ES?? _AssetTransferJourPost Assettransferjourpost_ES?? _voucher Voucher?? _accountType LedgerJournalACType?? 
_ledgerAcc LedgerDimensionDefaultAccount?? 
_amountCur Amount?? isDebit boolean?? 
_dimension DimensionDefault?? 
_TransDate 	TransDate?? ''_txt LedgerJournalTransTxt?? ""_activityNumber ProjActivityNumber?? 0_defaultDimension DimensionDefault??  ? ?? 
createJournal?  ? ?? 
dialog?  Object? ?? 
getFromDialog?  boolean? ?? 
getJournalName?  JournalNameId? ?? 
getLedgerAcc   ? 
assetTrans 
AssetTrans?? assetTransferJourPost AssetTransferJourPost_ES??  LedgerDimensionDefaultAccount? ?? 
getLedgerAcc_Default   ? _assetTrans 
AssetTrans?? _locType AssetLocType_ES?? _locId AssetLocId_ES??  LedgerDimensionDefaultAccount? ?? 
getLedgerType   ? assetTransferJourPost AssetTransferJourPost_ES??  LedgerJournalACType? ?? 
getOffsetAcc   ? 
assetTrans 
AssetTrans??  LedgerDimensionDefaultAccount? ?? 
	getProjId   ? assetTransferJourTrans AssetTransferJourTrans_ES??  ProjId? ?? 
gettingLedgerDimensionAll   ? _ledgerJournalId LedgerDimensionDefaultAccount?? _assetId AssetId?? _assetListId AssetListId_ES?? _defaultDimension DimensionDefault??  LedgerDimensionDefaultAccount??? 
gettingMainAccount   ? _ledgerJournalId LedgerDimensionDefaultAccount??  DimensionValue??? 
initInstance   ? _ledgerJournalTrans LedgerJournalTrans??  ? ?? 
initParmDefault?  ? ?? 
pack?   ? ?? 
parmJournalNameId   ? journalNameId_journalNameId JournalNameId??  JournalNameId? ?? 
parmJournalNum   ? 
journalNum_journalNum DimensionDisplayValue??  DimensionDisplayValue? ?? 

parmProjId   ? 	projectId_projId ProjId??  ProjId? ?? 
parmVoucher   ? voucher_voucher Voucher??  Voucher? ?? 
queryRun?  QueryRun? ?? 
run?  ? ?? 

setVoucher?  ? ?? 
showQueryValues?  boolean? ?? 
unpack   ? _packedClass  ??  boolean? ?? 
updateAssetTrans   ? 
assetTrans 
AssetTrans??  ??? 	
main   ? _args Args??  ? ?"ESS_AssetProposalDepreciationSplit?? ! Hpublic class SMAServiceObjectRelationFormExtensionOverrides
{
   

}   ? 
new?  ? ?? 	
	construct?  .SMAServiceObjectRelationFormExtensionOverrides? ?? 
ESS_AssetListId_OnLookup   ? _callingControl FormStringControl??  ? ?.SMAServiceObjectRelationFormExtensionOverrides?? ! )static class AssetBookTbl_Extension
{
}   ? 	
findByAssetId   ? _assetId AssetId?? false
_forupdate boolean?? ConcurrencyModel::Auto_concurrencyModel ConcurrencyModel??  	AssetBook? ?AssetBookTbl_Extension?? ! ?class ESS_AssetTransferJournalCheckPost extends RunBase
{

    LedgerJournalTable                ledgerJournalTable;
    AssetTransferJourTrans_ES         assetTransferJourTrans;
    FormDataSource                    formDataSource;
    TableId                           journalTableId;
    Common                            record;
    JournalCheckPostType              journalCheckPostType;
    Counter                           progressCounter;

}RunBase   " ledgerJournalTable LedgerJournalTable?" assetTransferJourTrans AssetTransferJourTrans_ES?" formDataSource FormDataSource?" journalTableId TableId?" record Common?" journalCheckPostType JournalCheckPostType?" progressCounter Counter?   ? 
checkJournal   ? 
_journalId 	JournalId??  boolean? ?? 
missedJournalLines   ? assetTransferJourTransIns AssetTransferJourTrans_ES??  ? ?? 

numOfLines?   ? ?? 
parmJournalCheckPostType   ? journalCheckPostType_journalCheckPostType JournalCheckPostType??  JournalCheckPostType? ?? 
parmJournalDataSource   ? formDataSource_formDataSource FormDataSource??  FormDataSource? ?? 
parmJournalRecord   ? record_record Common??  common? ?? 
parmJournalTableId   ? journalTableId_tableId TableId??  TableId? ?? 
postJournal?  boolean? ?? 
progressUpdate   ? _text  ??  ? ?? 
run?  ? ?? 
updateSystemBlock   ? _ledgerJournalTable LedgerJournalTable?? trueset boolean??  ? ?? 
validate   ? null_calledFrom Object??  boolean? ?? 	
main   ? _args Args??  ? ?!ESS_AssetTransferJournalCheckPost?? ! 'class clearDimensionCache
{        
}   ? 	
main   ? _args Args??  ? ?clearDimensionCache?? !     extensionof        LedgerJournalTable? ? ? formStr??d[extensionof(formStr(LedgerJournalTable))]
final class LedgerJournalTablefrm_Extension
{
     
}   ? 
AssetLocationTypeModified?  ? ?? 
enableButtonsActive?  ? ?LedgerJournalTablefrm_Extension?? ! 1class LedgerJournalTable_EventHandler
{
    
}   ?     DataEventHandler        LedgerJournalTable? ? ? tableStr?     Updated?	 DataEventType??	
LedgerJournalTable_onUpdated   ? sender Common?? e DataEventArgs??  ? ??     PostHandlerFor        LedgerJournalTable? ? ? formStr?     LedgerJournalTable? init? ? formMethodStr??	
LedgerJournalTable_Post_init   ? args XppPrePostArgs??  ? ??     FormDataFieldEventHandler        LedgerJournalTable? LedgerJournalTable? AssetLocType_ES? formDataFieldStr?     Modified?	 FormDataFieldEventType??	
AssetLocType_ES_OnModified   ? sender FormDataObject?? e FormDataFieldEventArgs??  ? ??     FormDataSourceEventHandler        LedgerJournalTable? LedgerJournalTable? ? formDataSourceStr?     	InitValue?	 FormDataSourceEventType??	
LedgerJournalTable_OnInitValue   ? sender FormDataSource?? e FormDataSourceEventArgs??  ? ??     FormControlEventHandler        LedgerJournalTable? Asset_Defaults_ESS_AssetLocId? ? formControlStr?     Lookup?	 FormControlEventType??	
&Asset_Defaults_ESS_AssetLocId_OnLookup   ? sender FormControl?? e FormControlEventArgs??  ? ?LedgerJournalTable_EventHandler?? ! ?/// <summary>
/// The extensions for the <c>AssetMgmt_ES</c> module.
/// </summary>
public static class AssetMgmt_ExtensionES
{

}   ?     PostHandlerFor        LedgerJournalTable? ? ? formStr?     LedgerJournalTable? init? ? formMethodStr??	
LedgerJournalTable_Post_init   ? args XppPrePostArgs??  ? ??     FormDataSourceEventHandler        LedgerJournalTable? LedgerJournalTable? ? formDataSourceStr?     	Activated?	 FormDataSourceEventType??	
LedgerJournalTable_OnActivated   ? sender FormDataSource?? e FormDataSourceEventArgs??  ? ??     DataEventHandler        
AssetTrans? ? ? tableStr?     Inserted?	 DataEventType??	
AssetTrans_onInserted   ? sender Common?? e DataEventArgs??  ? ?? 	
acquisitionValue   ? _this 
AssetTable??  AssetAcquisitionValue? ?? 	
assetSumCalc   ? _this 
AssetTable??  AssetSumCalc? ?? 	
depreciationValue   ? _this 
AssetTable??  AssetDepreciation? ??     PostHandlerFor        LedgerJournalStatic? ? ? classStr?     LedgerJournalStatic? menuItemStrLines? ? 	methodStr??	
)LedgerJournalStatic_Post_menuItemStrLines   ? args XppPrePostArgs??  ? ??     PostHandlerFor        LedgerJournalFormTable? ? ? classStr?     LedgerJournalFormTable? datasourceCreatePost? ? 	methodStr??	
0LedgerJournalFormTable_Post_datasourceCreatePost   ? args XppPrePostArgs??  ? ?? 	
numRefAssetTransferJourSequence?  NumberSequenceReference? ??     PostHandlerFor        AssetParameters? ? ? formStr?     AssetParameters? numberSeqPreInit? ? formMethodStr??	
%AssetParameters_Post_numberSeqPreInit   ? args XppPrePostArgs??  ? ??     DataEventHandler        LedgerJournalTrans? ? ? tableStr?     Deleted?	 DataEventType??	
LedgerJournalTrans_onDeleted   ? sender Common?? e DataEventArgs??  ? ?AssetMgmt_ExtensionES?