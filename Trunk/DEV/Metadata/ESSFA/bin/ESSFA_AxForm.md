   ESS_FAssetTransferHistory?tg5    ?  AssetJourTransLocTransfer_ES?tg5?  ?  ESS_AssetLocationTable?tg5  
  AssetTransferJourTrans_ES?tg5)  '
  AssetJourTransStock_ES?tg5P(  ?  ESS_FAssetStockHistory?tg55  ?  ES_AssetLocationTableLookUp?tg5?=    ESS_AssetList?tg5A  ?  ? ?    ?          ? ActivityNumber?? AssetListId?? AssetTransactionType?? AssetTransJourID?? 
DataAreaId?? DefaultDimension?? EndDate?? FromAssetLocId?? FromLocType?? FromProjectId?? JournalType?? 	Partition?? Posted?? Qty?? RecId?? TableId?? ToAssetLocId?? 	ToLocType?? ToProjectId?? 	TransDate?       ? 
active?   ? ?? 
executeQuery?  ? ?AssetTransferJourPost_ESAssetTransferJourPost_ES?? 
 ?Asset transfer history   ? )FormActionPaneControl1?? 
 ?   ?   
 ?Overview   ?  ? ?   ?   ?  ?	TransDateAssetTransferJourPost_ES, ?5Transfer date; ?K"AssetTransferJourPost_ES_TransDate??  ?AssetTransJourIDAssetTransferJourPost_ES' ?0Asset journal id6 ?G)AssetTransferJourPost_ES_AssetTransJourID??  ?AssetListIdAssetTransferJourPost_ES' ?0Asset list Id6 ?G$AssetTransferJourPost_ES_AssetListId??  ?AssetTransactionTypeAssetTransferJourPost_ES% ?/From Location Type5 ?@-AssetTransferJourPost_ES_AssetTransactionType??   ?FromProjectIdAssetTransferJourPost_ES' ?0From project Id6 ?G&AssetTransferJourPost_ES_FromProjectId??  ?FromAssetLocIdAssetTransferJourPost_ES' ?0From Location6 ?G'AssetTransferJourPost_ES_FromAssetLocId??   ?ToProjectIdAssetTransferJourPost_ES' ?0
To Project6 ?G$AssetTransferJourPost_ES_ToProjectId??   ?ToAssetLocIdAssetTransferJourPost_ES' ?0To Location6 ?G%AssetTransferJourPost_ES_ToAssetLocId?? 	 ?QtyAssetTransferJourPost_ES+ ?5Quantity; ?LAssetTransferJourPost_ES_Qty??  ?PostedAssetTransferJourPost_ES ?' ?2AssetTransferJourPost_ES_Posted??  ?EndDateAssetTransferJourPost_ES, ?; ?K AssetTransferJourPost_ES_EndDate]  ?AssetTransferJourPost_ES2  3FormGridControl1;  = K ?AssetTransferJourPost_ES0FormTabPageControl1??  
 ?Financial dimensions'  0TabFinancialDiemensions5DimensionEntryControl61.1J ?AssetTransferJourPost_ES0FormTabControl1< ?0Custom: <AssetTransferJourPost_ES?   " 	projTable 	ProjTable?" qbds QueryBuildDataSource?" qbr QueryBuildRange?
   ? 
classDeclaration? ??? 
enableFields?  ? ?ESS_FAssetTransferHistory?? ?    ?    ? AccountValue?? ActivityNumber   ? 
lookup   ? _formControl FormControl?? 
_filterStr  ??  ? ??? AssetEmployee?? AssetListId   ? 
lookup   ? _formControl FormControl?? 
_filterStr  ??  ? ?? 
modified?  ? ??? AssetTransType?? 
DataAreaId?? DefaultDimension?? EndDate?? FromAssetId?? FromAssetLocationType?? FromAssetLocId   ? 
lookup   ? _formControl FormControl?? 
_filterStr  ??  ? ??? FromLocType?? FromProjectId?? 
JournalNum?? LineNum?? 	Partition?? Posted?? Qty?? RecId?? Reversed?? Site?? TableId?? 	ToAssetId?? ToAssetLocationType?? ToAssetLocId   ? 
modified?  ? ?? 
lookup   ? _formControl FormControl?? 
_filterStr  ??  ? ??? 	ToLocType   ? 
modified?  ? ??? ToProjectId?? 	TransDate?? TransJourId?? Txt?   ? 
	initValue?  ? ?? 
active?   ? ?AssetTransferJourTrans_ESAssetTransferJourTrans_ES?? 
 ?Asset transfer journal trans   ?    ? 	@SYS10340   ?  
 ?@SalesAndMarketing:Maintain   ?  ?AssetTransferJourTrans_ES# ?0AssetTransferJourCheck_ES1 4AssetTransferJourCheck_ESGValidate??  ?AssetTransferJourTrans_ES# ?0AssetTransferJourPost_ES1 2   ? 
clicked?  ? ?4AssetTransferJourPost_ESGPost?AssetTransferJourTrans_ES5FunctionsBtnGroup?AssetTransferJourTrans_ES,ActionPaneTab?)FormActionPane??  
 ?   ? ?    ? targetControlName ?? placeholderText ?? defaultColumnName ?QuickFilterControl?QuickFilterControlListStyleGridGrid& ?* <	FormGroup@CustomAndQuickFiltersA1.1F P S ??  ? ? ?   ?  ?	TransDateAssetTransferJourTrans_ES, ?; ?K#AssetTransferJourTrans_ES_TransDate??  ?AssetListIdAssetTransferJourTrans_ES' ?6 ?G%AssetTransferJourTrans_ES_AssetListId??  ?FromAssetLocationTypeAssetTransferJourTrans_ES% ?5 ?@/AssetTransferJourTrans_ES_FromAssetLocationTypeP  ??  ?FromAssetIdAssetTransferJourTrans_ES' ?0
From Asset6 ?G%AssetTransferJourTrans_ES_FromAssetId??  ?FromProjectIdAssetTransferJourTrans_ES' ?0From Project6 ?GFromProjectId^  ??  ?FromLocTypeAssetTransferJourTrans_ES% ?/From Location type5 ?@%AssetTransferJourTrans_ES_FromLocType??  ?FromAssetLocIdAssetTransferJourTrans_ES' ?0From Asset Loc Id6 ?G(AssetTransferJourTrans_ES_FromAssetLocId?? 	 ?QtyAssetTransferJourTrans_ES+ ?5Quantity; ?LAssetTransferJourTrans_ES_Qty??  ?TxtAssetTransferJourTrans_ES' ?0Text6 ?GAssetTransferJourTrans_ES_Txt??  ?ToAssetLocationTypeAssetTransferJourTrans_ES% ?5 ?@-AssetTransferJourTrans_ES_ToAssetLocationTypeP  ??  ?	ToAssetIdAssetTransferJourTrans_ES' ?0To Asset Id6 ?G#AssetTransferJourTrans_ES_ToAssetId^  ??  ?	ToLocTypeAssetTransferJourTrans_ES% ?/To Location Type5 ?@#AssetTransferJourTrans_ES_ToLocType??  ?ToAssetLocIdAssetTransferJourTrans_ES' ?0To Asset Loc Id6 ?G&AssetTransferJourTrans_ES_ToAssetLocId??  ?ToProjectIdAssetTransferJourTrans_ES' ?0To Project Id6 ?GToProjectId^  ??   ?ActivityNumberAssetTransferJourTrans_ES' ?0Activity Number6 ?G(AssetTransferJourTrans_ES_ActivityNumber??  ?AssetTransferJourTrans_ES( ?3Employee9 ?G'AssetTransferJourTrans_ES_AssetEmployeeMAssetEmployee??  ?ReversedAssetTransferJourTrans_ES ?!Reversed' ?2"AssetTransferJourTrans_ES_Reversed?AssetTransferJourTrans_ES3Gridoverview= ?AssetTransferJourTrans_ES0
SimpleList11.1: <AssetTransferJourTrans_ES?   " ledgerJournalTable LedgerJournalTable?" ledgerJournalEngine LedgerJournalEngine?
   ? 
classDeclaration? ??? 
init?  ? ?? 
checkJournal?  ? ?? 
assetFromLookup   ? _formControl FormControl?? _assetTransferJourTrans AssetTransferJourTrans_ES??  ??? 
assetToLookup   ? _formControl FormControl?? _assetTransferJourTrans AssetTransferJourTrans_ES??  ??AssetJourTransLocTransfer_ES?? ?    ? 
   ? ActivityNumber   ? 
lookup   ? _formControl FormControl?? 
_filterStr  ??  ? ??? 
AssetLocId?? 
DataAreaId?? Description?? DimensionDefault?? LocationType   ? 
modified?  ? ??? 	Partition?? RecId?? TableId?? Value   ? 
lookup   ? _formControl FormControl?? 
_filterStr  ??  ? ?? 
modified?  ? ?? 
validate?  boolean? ??     ? 
active?   ? ?AssetLocation_ESAssetLocation_ES?? 
 ?   ? )FormActionPaneControl1?? 
 ?   ? ?    ? targetControlName ?? placeholderText ?? defaultColumnName ?QuickFilterControl?QuickFilterControlListStyleGridGrid& ??  ? ?   ?2  3FormGridControl1;  = K ?* , <
TitleGroupF Q  ?? 
 ?  * <FilterGroup@FieldsFieldGroupsA1.1Q  S ?? 
 ?   ? 
 ?Overview     ?  ? ? ?   ?  ?LocationTypeAssetLocation_ES% ?5 ?@AssetLocation_ES_LocationType??  ?ValueAssetLocation_ES' ?6 ?GAssetLocation_ES_Value??  ?
AssetLocIdAssetLocation_ES' ?6 ?GAssetLocation_ES_AssetLocId??  ?DescriptionAssetLocation_ES' ?6 ?GAssetLocation_ES_Description??  ?ActivityNumberAssetLocation_ES' ?6 ?GAssetLocation_ES_ActivityNumber?AssetLocation_ES2  3FormGridControl2?0FormTabPageControl15Custom??  
 ?Financial Dimensions0TabFinancialDimensions?AssetLocation_ES0FormTabControl1< ?0SimpleListDetails11.3: ?
   ? 
classDeclaration? ??? 
lookupMethod   ? _formControl FormControl??  ? ?ESS_AssetLocationTable?? ?    ?    ? AccountValue?? ActivityNumber   ? 
lookup   ? _formControl FormControl?? 
_filterStr  ??  ? ??? AssetEmployee?? AssetListId   ? 
lookup   ? _formControl FormControl?? 
_filterStr  ??  ? ??? AssetTransType?? 
DataAreaId?? DefaultDimension?? EndDate?? FromAssetId?? FromAssetLocId   ? 
lookup   ? _formControl FormControl?? 
_filterStr  ??  ? ??? FromLocType?? 
FromProjId?? 
JournalNum?? LineNum?? 	Partition?? Posted?? Qty?? RecId?? Reversed?? Site?? TableId?? 	ToAssetId?? ToAssetLocId   ? 
modified?  ? ?? 
lookup   ? _formControl FormControl?? 
_filterStr  ??  ? ??? 	ToLocType   ? 
modified?  ? ??? ToProjId?? 	TransDate?? TransJourId?? Txt?   ? 
	initValue?  ? ?? 
active?   ? ?AssetTransferJourTrans_ESAssetTransferJourTrans_ES?? 
 ?@SYS4081079   ?    ? 	@SYS10340   ?  
 ?@SalesAndMarketing:Maintain   ?  ?AssetTransferJourTrans_ES# ?0AssetTransferJourCheck_ES1 3  4AssetTransferJourCheck_ES??  ?AssetTransferJourTrans_ES# ?0AssetTransferJourPost_ES1 3  4AssetTransferJourPost_ES?AssetTransferJourTrans_ES5FunctionsBtnGroup?AssetTransferJourTrans_ES,ActionPaneTab?)FormActionPane??  
 ?   ? ?    ? targetControlName ?? placeholderText ?? defaultColumnName ?QuickFilterControl?QuickFilterControlListStyleGridGrid& ?* <	FormGroup@CustomAndQuickFiltersA1.1F P S ??  ? ? ?   ?  ?	TransDateAssetTransferJourTrans_ES, ?; ?K#AssetTransferJourTrans_ES_TransDate??  ?AssetListIdAssetTransferJourTrans_ES' ?6 ?G%AssetTransferJourTrans_ES_AssetListId??  ?FromLocTypeAssetTransferJourTrans_ES% ?5 ?@%AssetTransferJourTrans_ES_FromLocType??  ?FromAssetLocIdAssetTransferJourTrans_ES' ?6 ?G(AssetTransferJourTrans_ES_FromAssetLocId??  ?TxtAssetTransferJourTrans_ES' ?6 ?GAssetTransferJourTrans_ES_Txt??  ?	ToLocTypeAssetTransferJourTrans_ES% ?5 ?@#AssetTransferJourTrans_ES_ToLocType??  ?ToAssetLocIdAssetTransferJourTrans_ES' ?6 ?G&AssetTransferJourTrans_ES_ToAssetLocId??  ?ActivityNumberAssetTransferJourTrans_ES' ?6 ?G(AssetTransferJourTrans_ES_ActivityNumber?AssetTransferJourTrans_ES3FormGridControl1= ?AssetTransferJourTrans_ES0
SimpleList11.1: <AssetTransferJourTrans_ES?   " ledgerJournalTable LedgerJournalTable?" ledgerJournalEngine LedgerJournalEngine?
   ? 
classDeclaration? ??? 
init?  ? ?? 
checkJournal?  ? ?AssetTransferJourTrans_ES?? ?    ?    ? AccountValue?? ActivityNumber?? AssetEmployee?? AssetListId   ? 
lookup   ? _formControl FormControl?? 
_filterStr  ??  ? ?? 
modified?  ? ??? AssetTransType?? 
DataAreaId?? DefaultDimension?? EndDate?? FromAssetId?? FromAssetLocationType?? FromAssetLocId   ? 
lookup   ? _formControl FormControl?? 
_filterStr  ??  ? ??? FromLocType?? FromProjectId?? 
JournalNum?? LineNum?? 	Partition?? Posted?? Qty?? RecId?? Reversed?? Site?? TableId?? 	ToAssetId?? ToAssetLocationType?? ToAssetLocId   ? 
lookup   ? _formControl FormControl?? 
_filterStr  ??  ? ??? 	ToLocType?? ToProjectId?? 	TransDate?? TransJourId?? Txt?   ? 
	initValue?  ? ?? 
active?   ? ?? 
executeQuery?  ? ?AssetTransferJourTrans_ESAssetTransferJourTrans_ES?? 
 ?Physical stock for assets   ?    ? 	@SYS10340   ?  
 ?   ?  ?AssetTransferJourTrans_ES# ?0AssetStockJourCheck_ES1 3  4AssetStockJourCheck_ES??  ?AssetTransferJourTrans_ES# ?0AssetStockJourPost_ES1 3  4AssetStockJourPost_ES?AssetTransferJourTrans_ES5FunctionsBtnGroup?AssetTransferJourTrans_ES,ActionPaneTab?)FormActionPane??  
 ?   ? ?    ? targetControlName ?? placeholderText ?? defaultColumnName ?QuickFilterControl?QuickFilterControlListStyleGridGrid& ?* <	FormGroup@CustomAndQuickFiltersA1.1F P S ??  ? ? ?   ?  ?	TransDateAssetTransferJourTrans_ES, ?5
Stock Date; ?K#AssetTransferJourTrans_ES_TransDate??  ?AssetListIdAssetTransferJourTrans_ES' ?6 ?G%AssetTransferJourTrans_ES_AssetListId??  ?FromAssetLocationTypeAssetTransferJourTrans_ES% ?5 ?@/AssetTransferJourTrans_ES_FromAssetLocationTypeP  ??  ?FromProjectIdAssetTransferJourTrans_ES' ?6 ?G'AssetTransferJourTrans_ES_FromProjectId^  ??  ?FromLocTypeAssetTransferJourTrans_ES% ?5 ?@%AssetTransferJourTrans_ES_FromLocTypeP  ??  ?FromAssetLocIdAssetTransferJourTrans_ES' ?6 ?G(AssetTransferJourTrans_ES_FromAssetLocId^  ??  ?TxtAssetTransferJourTrans_ES' ?6 ?GAssetTransferJourTrans_ES_Txt??  ?ToAssetLocationTypeAssetTransferJourTrans_ES% ?5 ?@-AssetTransferJourTrans_ES_ToAssetLocationTypeP  ??  ?ToProjectIdAssetTransferJourTrans_ES' ?6 ?G%AssetTransferJourTrans_ES_ToProjectId^  ??  ?	ToLocTypeAssetTransferJourTrans_ES% ?/Location type5 ?@#AssetTransferJourTrans_ES_ToLocType??  ?ToAssetLocIdAssetTransferJourTrans_ES' ?0Location6 ?G&AssetTransferJourTrans_ES_ToAssetLocId??  ?AssetTransferJourTrans_ES( ?9 ?G'AssetTransferJourTrans_ES_AssetEmployeeMAssetEmployee?AssetTransferJourTrans_ES3Overview= ?AssetTransferJourTrans_ES0
SimpleList11.1: ?   " ledgerJournalTable LedgerJournalTable?" ledgerJournalEngine LedgerJournalEngine?
   ? 
classDeclaration? ??? 
init?  ? ?? 
checkJournal?  ? ?? 
validate?  ? ?? 
assetFromLookup   ? _formControl FormControl?? _assetTransferJourTrans AssetTransferJourTrans_ES??  ??? 
assetToLookup   ? _formControl FormControl?? _assetTransferJourTrans AssetTransferJourTrans_ES??  ??? 
	RefreshDS?  ? ?AssetJourTransStock_ES?? ?    ?    ? AccountValue?? ActivityNumber?? AssetEmployee?? AssetListId?? AssetTransType?? 
DataAreaId?? DefaultDimension?? EndDate?? FromAssetId?? FromAssetLocId?? FromLocType?? FromProjectId?? 
JournalNum?? LineNum?? 	Partition?? Posted?? Qty?? RecId?? Reversed?? Site?? TableId?? 	ToAssetId?? ToAssetLocId?? 	ToLocType?? ToProjectId?? 	TransDate?? TransJourId?? Txt?   ? 
active?   ? ?? 
executeQuery?  ? ?AssetTransferJourTrans_ESAssetTransferJourTrans_ES?? 
 ?@SYS4081079   ?    ? 	@SYS10340AssetTransferJourTrans_ES,ActionPaneTab?)FormActionPane??  
 ?   ? ?    ? targetControlName ?? placeholderText ?? defaultColumnName ?QuickFilterControl?QuickFilterControlListStyleGridGrid& ?* <	FormGroup@CustomAndQuickFiltersA1.1F P S ??  ? ? ?   ?  ?TransJourIdAssetTransferJourTrans_ES' ?0Transfer Jour Id6 ?G%AssetTransferJourTrans_ES_TransJourId??  ?AssetListIdAssetTransferJourTrans_ES' ?0Asset List Id6 ?G%AssetTransferJourTrans_ES_AssetListId??  ?	TransDateAssetTransferJourTrans_ES, ?5
Stock Date; ?K#AssetTransferJourTrans_ES_TransDate??  ?AssetTransTypeAssetTransferJourTrans_ES% ?/Location Type5 ?@(AssetTransferJourTrans_ES_AssetTransType??  ?AssetTransferJourTrans_ES' ?0Text6 ?Gtext??  ?FromProjectIdAssetTransferJourTrans_ES' ?0From Project6 ?G'AssetTransferJourTrans_ES_FromProjectId^  ??  ?FromAssetLocIdAssetTransferJourTrans_ES' ?0From Location6 ?G(AssetTransferJourTrans_ES_FromAssetLocId^  ??   ?ToProjectIdAssetTransferJourTrans_ES' ?0
To Project6 ?G%AssetTransferJourTrans_ES_ToProjectId??   ?	ToLocTypeAssetTransferJourTrans_ES% ?/Location5 ?@#AssetTransferJourTrans_ES_ToLocType??   ?ToAssetLocIdAssetTransferJourTrans_ES' ?0To Location6 ?G&AssetTransferJourTrans_ES_ToAssetLocId??  ?PostedAssetTransferJourTrans_ES ?' ?2 AssetTransferJourTrans_ES_Posted??  ?EndDateAssetTransferJourTrans_ES, ?; ?K!AssetTransferJourTrans_ES_EndDate?AssetTransferJourTrans_ES3Overview= ?AssetTransferJourTrans_ES0
SimpleList11.1: <AssetTransferJourTrans_ES?
   ? 
classDeclaration? ??? 
enableFields?  ??ESS_FAssetStockHistory?? ?    ?       
   ? ActivityNumber?? 
AssetLocId?? 
DataAreaId?? Description?? DimensionDefault?? LocationType?? 	Partition?? RecId?? TableId?? Value?    AssetLocation_ESAssetLocation_ES?? 
 ?   ? )FormActionPaneControl1??  
 ?   ? ?    ? targetControlName ?? defaultColumnName ?? placeholderText ?QuickFilterControl?QuickFilterControl&  ?* <FormGroupControl1@CustomAndQuickFiltersA1.1F P S ??  ? ?	  ?   ?   ?
AssetLocIdAssetLocation_ES' ?6 ?GAssetLocation_ES_AssetLocId??  ?DescriptionAssetLocation_ES' ?6 ?GAssetLocation_ES_Description?AssetLocation_ES3Grid;  = ?0
SimpleList11.1: ?
   ? 
classDeclaration? ??? 
init?  ? ?? 
run?  ? ?ES_AssetLocationTableLookUp?? ?    ? '   ? AcquisitionDate?? 
Allocation?? AssetId?? AssetSuspended?? AssetUserGroup?? BarCode?? Comments?? 
DataAreaId?? DefaultDimension?? DefaultLocation?? EmployeeResponsible?? FATransferFate?? FATransferJournal?? ListId?? LocId?? LocType?? Make?? Model?? 	ModelYear?? MovementRef?? Name?? 	Partition?? PaymentDate?? 	PaymentId?? PODate?? PostingDate?? ProjId?? Quantity?? RecId?? Serial?? Status?? Stopped?? TableId?? TechnicalInfo?? 	ToAssetId?? TransferReason?? TransferRefId?? UnitCost?? UOM?     ? 
remainingQty?  AssetAdditionQty? ?? 
totalAssetQty?  AssetAdditionQty? ?? 
totalListQty?  AssetAdditionQty? ?? 
validateWrite?  boolean? ?? 
active?   ? ?? 
remainingBalance?  	AmountMST? ?? 
totalAssetValue?  	AmountMST? ?? 
totalAcquisitionValue?  	AmountMST? ?? 
init?  ? ?? 
	initValue?  ? ?? 
write?  ? ?? 
create   ? false_append boolean??  ? ?? 
delete?  ? ?AssetList_ESAssetList_ES?? 
 ?   ?    ? Fixed asset list   ? 
 ?Maintain   ?   ?v" ?&"Edit the Selected fixed asset list0EditRecordButton2 AEdit??   ? # ?% (!Eit the selected fixed asset list4EditDetailsButton: N  ??  ?" ?&$Delete the selected fixed asset list/ 0DeleteButton2 ;  ADelete?5MaintainGroup?? 
 ?New   ?  ?" ?.   ? 
clicked?  ? ?0	NewButtonANew?AssetList_ES5NewGroup?? 
 ?	Functions   ?  ?" ?/  0GenerateAssetList@Populate Asset Lit??   ?# ?0ESS_AssetMove1 3 4	AssetMoveG
Move asset??  ?   ?  ?" ?0	AssetCopy@Asset??  ?" ?0AssetListCopy@
Asset list?$ ?2  3CopyDCopy??  ?" ?/  0CreateResource@Create resourceI  ??  ?" ?/  0TransferLocation@Transfer location??  ?AssetList_ES# ?0ESS_FAssetStockHistory3 4FAssetStockHistoryGPhysical stock??  ?AssetList_ES# ?0ESS_FAssetTransferHistory3  4FAssetTransferHistory?5FunctionsGroup??  
 ?List   ?  ?;" ?&Refresh0FormCommandButtonControl1??  ?T" ?0ExportToExcelButton?5	ListGroup?? 
 ?Attachments   ?  ?%" ?0AttachmentsButtonAAttachments?5AttachementGroup?,ActionPaneHeader?)FormActionPaneControl1?? 
 ?   ? ?    ? targetControlName ?? placeholderText ?? defaultColumnName ?QuickFilterControl?QuickFilterControlListStyleGridGrid& ??  ? ?   ?2  3FormGridControl1;  = K ?AssetList_ES* , <FormcontrolgrouptestF Q  ??   
 ?     ?   
 ?  Total   ?   	 ?totalAcquisitionValueAssetList_ES+ ?5Acquisition value; ?LTotalAcqCost??   	 ?totalAssetValueAssetList_ES+ ?5Asset value; ?L	ListTotal??   	 ?remainingBalanceAssetList_ES+ ?5Balance; ?L
BalanceAmt?AssetList_ES<TotalBalancesGroup??   
 ?  Balances   ?   	 ?totalAssetQtyAssetList_ES+ ?5Total Asset Qty; ?LTotalAssetQty??   	 ?totalListQtyAssetList_ES+ ?5	Asset Qty; ?LListTotalQty??   	 ?remainingQtyAssetList_ES+ ?5Balance; ?L
BalanceQty?AssetList_ES<TotalQtyBalances?AssetList_ES* <Balances@FieldsFieldGroupsA1.1S ?? 
 ?   ?  
 ?   ? 
 ?   ?  ?' ?6 ?GHeaderTitleS ?<HeadderInfoF Q  ?? 
 ?   ? 
 ?OverView   ?  ? ? ?   ?  ?ListIdAssetList_ES' ?6 ?GAssetList_ES_ListId??  ?AssetIdAssetList_ES' ?6 ?GAssetList_ES_AssetId??  ?NameAssetList_ES' ?6 ?GAssetList_ES_Name??  ?AcquisitionDateAssetList_ES, ?; ?KAssetList_ES_AcquisitionDate??  ?LocTypeAssetList_ES% ?5 ?@AssetList_ES_LocType??  ?ProjIdAssetList_ES' ?6 ?GAssetList_ES_ProjId??  ?LocIdAssetList_ES' ?6 ?GAssetList_ES_LocId?? 	 ?UnitCostAssetList_ES+ ?; ?LAssetList_ES_UnitCost?? 	 ?QuantityAssetList_ES+ ?; ?LAssetList_ES_Quantity?? 	 ?	totalCostAssetList_ES+ ?; ?LGrid_M_TotalCost??  ?StoppedAssetList_ES ?' ?2AssetList_ES_Stopped?AssetList_ES3Grid_ESS?AssetList_ES0TabOverview?? 
 ?General      ? 
 ?   ?  ?NameAssetList_ES' ?6 ?GDescription_Name?DescriptionAssetList_ES<Description?? 
 ?   ?  ?AcquisitionDateAssetList_ES, ?; ?KAcquisition_AcquisitionDate?? 	 ?UnitCostAssetList_ES+ ?; ?LAcquisition_UnitCost?? 	 ?QuantityAssetList_ES+ ?; ?LAcquisition_Quantity??  ?UOMAssetList_ES' ?6 ?GAcquisition_UOM?? 	 ?	totalCostAssetList_ES+ ?; ?LAcquisition_totalCost?AcquisitionAssetList_ES<Acquisition?? 
 ?   ?  ?CommentsAssetList_ES' ?6 ?GReference_Comments?	ReferenceAssetList_ES<	Reference?? 
 ?   ?  ?BarCodeAssetList_ES' ?6 ?GInventory_BarCode?	InventoryAssetList_ES<	Inventory?? 
 ?   ?  ?MakeAssetList_ES' ?6 ?G
Model_Make??  ?ModelAssetList_ES' ?6 ?GModel_Model??  ?SerialAssetList_ES' ?6 ?GModel_Serial??  ?	ModelYearAssetList_ES' ?6 ?GModel_ModelYear??  ?TechnicalInfoAssetList_ES' ?6 ?GModel_TechnicalInfo?ModelAssetList_ES<Model?0
TabGeneral?? 
 ?ClosureAssetList_ES0
TabClosureH  ??  
 ?Financial Dimensions0TabFinancialDimensions?0HeaderDetailsTab?0ESS_TabPageDetails5Custom< ?0ESS_Tab< ?0SimpleListDetails11.3: ?   " 
assetTable 
AssetTable?" 	isWritten boolean?" newAdditionNumber AssetAdditionNum?" assetTableSelect 
AssetTable?
   ? 
classDeclaration? ??? 
canClose?  boolean? ?? 
init?  ? ?? 
parmAssetTable   ? 
assetTable_assetTable 
AssetTable??  
AssetTable? ?? 
parmIsWritten   ? 	isWritten
_isWritten boolean??  boolean? ?? 
parmNewAdditionNumber   ? newAdditionNumber_newAdditionNumber AssetAdditionNum??  AssetAdditionNum? ?? 
populateAssetLists?  ? ?? 
UpdateDelJournalId?  ??ESS_AssetList?