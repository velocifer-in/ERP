   AssetTransferJourPost_ES?tg5    ?  AssetList_ES?tg5?    AssetTransferJourTrans_ES?tg5?  ?  AssetSite_ES?tg5?#  ?  AssetLocation_ES?tg5?&  ?  ? ?@public class AssetTransferJourPost_ES extends common
{



}   ?
AutoReport??
AutoLookup?? AutoIdentification??AutoSummary??
AutoBrowse?   ?	TransDate	TransDate??AssetLocType_ESTo Location type	ToLocType??	AssetLocId_ESTo locationToAssetLocId??	AssetLocId_ESFromAssetLocId??AssetLocType_ESFrom Location TypeFromLocType??DimensionDefaultDefaultDimension??  	ProjActivityNumberActivityNumber??	AssetListId_ESAssetListId??LedgerJournalTypeJournalType??    	AssetTransJourId_ESAssetTransJourID??AssetTransType_ESAssetTransactionType??	ProjIdFrom ProjectFromProjectId??	ProjId
To ProjectToProjectId??QtyStatisticalQty??    NoYes	JournalPostedPosted??    	TransDateEnd dateEndDate??	AssetId
From assetFromAssetId??    	LedgerJournalId 
JournalNum??	Description
@SYS105215Txt??	AssetId@ESS:ToAsset	ToAssetId??HcmWorkerRecIdAssetEmployee??JournalPostedDateTimePostedDateTime??	UserNamePostedBy??RefRecId	TransLine??AssetLocationType_ESTypeFromAssetLocationType??AssetLocationType_ESTypeToAssetLocationType?   ? 	
exists   ? _assetListId AssetListId_ES??  boolean? ?? 	
	findTrans   ? _assetlistId AssetListId_ES?? 	startDate 	TransDate?? endDate 	TransDate?? false
_forUpdate boolean?? ConcurrencyModel::Auto_concurrencyModel ConcurrencyModel??  AssetTransferJourPost_ES? ?? 	

existTrans   ? assetListId AssetListId_ES?? 	startDate 	TransDate?? endDate 	TransDate??  boolean? ?? 	
findPreviousLine   ? _assetlistId AssetListId_ES?? 
_transdate 	TransDate?? endDate 	TransDate?? false
_forUpdate boolean?? ConcurrencyModel::Auto_concurrencyModel ConcurrencyModel??  AssetTransferJourPost_ES? ?? 	
findNextLine   ? _assetListId AssetListId_ES?? _assetTransferJourPost AssetTransferJourPost_ES?? endDate 	TransDate?? transJourPost  ?? false
_forUpdate boolean?? ConcurrencyModel::Auto_concurrencyModel ConcurrencyModel??  AssetTransferJourPost_ES? ?!AssetTransferJourPost_ES9  ??? ? 0public class AssetList_ES extends common
{

}   ?
AutoReport??
AutoLookup?? AutoIdentification??AutoSummary??
AutoBrowse??   ?AcquisitionDate??UnitCost??Quantity??UOM??	totalCost?AcquisitionAcquisition??   ?AssetId?Fixed asset numberAssetId??   ?Name?DescriptionDescription??IdentificationIdentification??   ?BarCode?	Inventory	Inventory??   ?Make??Model??Serial??	ModelYear??TechnicalInfo?ModelModel??   ?ListId??AssetId??Name??AcquisitionDate??ProjId??LocId??UnitCost??Quantity??Stopped??LocType??	totalCost?OverviewOverview??   ?PODate??PaymentDate??	PaymentId?PurchasePurchase??   ?Comments?	Reference	Reference?#   ?AssetLocType_ESLocType??    	AssetListId_ES ListId??  	AssetId AssetId??AssetAdditionCostPriceUnitCost??	AssetId	ToAssetId??    NoYesStopped??    AssetStatus_ESStatus??		AssetName!Enter a description for the assetName??	LedgerJournalIdMovementRef??    	AssetLocId_ESLocationLocId??AssetAcquisitionDateAcquisitionDate??AssetAdditionQty Quantity??NoYes
Allocation??	AssetLocId_ESDefault locationDefaultLocation??	Name	@SYS67389Make??	Name@SYS9923Model??	NumSerial numberSerial??	AssetModelYear	ModelYear??	AssetTechInfoTechnicalInfo??DimensionDefaultDefaultDimension??NoYes	SuspendedAssetSuspended??	UserGroupId
User groupAssetUserGroup??	AssetBarcodeBar code of the additional itemBarCode??	AssetAdditionCommentsComments??AssetTransDate
Posting DateDatePostingDate??HcmWorkerRecIdEmployee responsibleEmployeeResponsible??	LedgerJournalIdMovement journal numberFATransferJournal??	TransDateMovement dateFATransferFate??	PaymId	PaymentId??AssetTransDate
Date of paymentPayment datePaymentDate??AssetTransDate
"Any date related to purchase orderPO datePODate??    	ProjIdProjId??	ReasonCommentTransfer reasonTransferReason??RefRecId	ReferenceTransferRefId??	UnitOfMeasureSymbol'the common unit of measure for the itemUnit of measureUOM?   ?   ?ListId?	AssetListIdx?
Asset List   ? 	
findByAssetList   ? _assetListId AssetListId_ES?? false
_ForUpdate boolean??  AssetList_ES? ?? 
	totalCost?  AssetAdditionTotalCost? ?? 	
assetListExists   ? _assetId AssetId??  boolean? ?? 
getNextListId   ? ''_assetId AssetId??  AssetListId_ES? ?? 
getNextListIdName   ? ''_assetId AssetId??  AssetListId_ES? ?? 
createAssetList   ? _assetTable 
AssetTable?? 1_cnt Counter?? 0_assetPrice AssetAdditionCostPrice??  ? ?? 	
mergeDimension   ? firstDim DimensionDefault?? 	secondDim DimensionDefault??  DimensionDefault? ?? 
	initValue?  ? ?? 
insert?  ? ?? 	

checkExist   ? _assetId AssetId?? _additionNumber AssetAdditionNum??  boolean? ?? 	
exist   ? _assetId AssetId?? _additionNumber AssetAdditionNum??  boolean? ?? 	
find   ? _assetId AssetId?? _additionalNumber AssetListId_ES?? false
_forupdate boolean?? ConcurrencyModel::Auto_concurrencyModel ConcurrencyModel??  AssetList_ES? ?? 	
totalAssetListValue   ? _assetId AssetId??  AssetAdditionTotalCost? ?!AssetList_ES%   ?    ?AssetIdAssetIdAssetId? 
AssetTable
AssetTable  ??   ?ListIdListIdAssetListId?AssetTransferJourPostAssetTransferJourPost_ES??    ?UOMUOMSymbol?UnitofMeasureUnitOfMeasure  ??    ?EmployeeResponsibleEmployeeResponsibleRecId?EmployeeResponsible	HcmWorker  ?9  ?0 4Name?? ?Bpublic class AssetTransferJourTrans_ES extends common
{
   

}@ESS:AssetTransJourTrans_ES   ?   ?
JournalNum??AssetListId?
AutoReport??
AutoLookup?? AutoIdentification??AutoSummary??
AutoBrowse??   ?
JournalNum??LineNum??	TransDate??AssetTransType??AssetListId??FromAssetId??FromLocType??FromAssetLocId??	ToLocType??	ToAssetId??ToAssetLocId??AccountValue??ActivityNumber??AssetEmployee??TransJourId??DefaultDimension??EndDate??Posted??Qty??Reversed??Site??Txt?	@SYS57714General?   ?	String15	@SYS41043AccountValue??	ProjActivityNumberActivityNumber??HcmWorkerRecIdAssetEmployee??  	AssetListId_ES AssetListId??AssetTransType_ESAssetTransType??    AssetLocType_ESFrom Location TypeFromLocType??AssetLocType_ESTo Location Type	ToLocType??	AssetTransJourId_ESTransJourId??DimensionDefaultDefaultDimension??EndDateEndDate??	AssetId@ESS:FromAssetFromAssetId??	AssetId@ESS:ToAsset	ToAssetId??    	AssetLocId_ES@ESS:FrmAssetLocFromAssetLocId??	AssetLocId_ES@ESS:ToAssetLocToAssetLocId??    	LedgerJournalId 
JournalNum??    LineNumLineNum??    NoYes	PostedPosted??QtyQty??NoYes	NoYesId	@SYS22850Reversed??	String15Site??	TransDate	@SYS34422	TransDate??	Description
@SYS105215Txt??	ProjIdFrom projectFromProjectId??	ProjId
To projectToProjectId??AssetLocationType_ESTypeFromAssetLocationType??AssetLocationType_ESTypeToAssetLocationType??NoYesIs it a transfer?TransferTransfer??NoYes
TransferedTransferred??	UserIdTransferred ByTransferredBy??	TransDateTransferred onTransferredOn??    	LedgerJournalIdTransferred to journalTransferredTo?   ?    ?
JournalNum??AssetListId?	JournalNumIdx?	@SYS30149   ? 
	initValue?  ? ?? 	
find   ? _recId RecId?? 
_forupdate boolean??  AssetTransferJourTrans_ES? ?? 	
lastLineNum   ? _journalNum LedgerJournalId??  LineNum? ?? 
ledgerJournalTable?  LedgerJournalTable? ?? 
insert?  ? ?? 
modifiedField   ? _fieldId FieldId??  ? ?!AssetTransferJourTrans_ES$JournalNumIdx%   ?    ?AssetEmployeeAssetEmployeeRecId?RecId		HcmWorker 	HcmWorker  ??    ?DefaultDimensionDefaultDimensionRecId?RecId	DimensionAttributeValueSet DimensionAttributeValueSet  ??    ?AssetListIdAssetListIdListId?AssetList_ESAssetList_ES  ??    ?SiteSiteSite?AssetSite_ES
 AssetSite_ES  ??    ?
JournalNum
JournalNum
JournalNum?LedgerJournalTableLedgerJournalTable  ??    ?ActivityNumberActivityNumberActivityNumber?smmActivitiessmmActivities  ??    ?FromAssetIdFromAssetIdAssetIdAssetId?AssetTable_From
AssetTable  ??    ?	ToAssetId	ToAssetIdAssetIdAssetId?AssetTable_To
AssetTable  ?3
JournalNum4AssetListId?? ? SiteIdx.public class AssetSite_ES extends common
{
}   ?
AutoReport??
AutoLookup?? AutoIdentification??AutoSummary??
AutoBrowse??   ?Name?DescriptionDescription??   ?Site?IdentificationIdentification?   ?LogisticsLocationRecIdLogisticsLocation  ??	AssetLocationName	Site nameName??	AssetSiteId_ESSite?   ?   ?Site?	SiteIdx?Fixed assets locations   ? 	
find   ? _siteId AssetSiteId_ES?? false
_forupdate boolean?? ConcurrencyModel::Auto_concurrencyModel ConcurrencyModel??  AssetSite_ES? ?!AssetSite_ES$SiteIdx%   ?    ?LogisticsLocationLogisticsLocationRecId?LogisticsLocationLogisticsLocation  ?9  ?/ 0 3Site4Name?? ?4public class AssetLocation_ES extends common
{

}   ?   ?
AssetLocId??Description?
AutoReport??
AutoLookup?? AutoIdentification??AutoSummary??
AutoBrowse?   ?	ProjActivityNumberActivityNumber??  	AssetLocId_ES 
AssetLocId??	DescriptionDescription??DimensionDefaultDimensionDefault??AssetLocType_ESLocation TypeLocationType??Valued   ?   ?   ?
AssetLocId?	AssetLocIdx?Asset location   ? 	
find   ? 	_location AssetLocId_ES?? 
_forUpdate boolean??  AssetLocation_ES? ?? 	
lookupAssetLocationId   ? _Ctrl FormControl?? _buffer Common??  ? ?!AssetLocation_ES9  ?0 3
AssetLocId4Description?