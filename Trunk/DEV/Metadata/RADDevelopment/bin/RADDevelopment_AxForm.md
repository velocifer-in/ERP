   SIGTSTimesheetEntry?tg5    FS  ? ?    ?          ? ApprovalStatus?? 	CreatedBy?? CreatedDateTime?? CreatedTransactionId?? 
DataAreaId?? IsWorkflowToBeResubmitted?? 
ModifiedBy?? ModifiedDateTime?? ModifiedTransactionId?? 	Partition?? 
PeriodFrom?? PeriodTo?? 
PostStatus?? ProjPeriodId?? ProjPeriodTimesheetWeek?? RecId?? Resource   ? 
modified?  ? ??? SIGParentResource?? SIGParentWorker?? SourceDocumentHeader?? TableId?? TimesheetNbr?? Worker?    	   ? 
active?   ? ?? 
markChanged?  ? ?? 
init?  ? ?? 
create   ? false_append boolean??  ? ?? 
executeQuery?  ? ?? 
timesheetTotalHours?  TSHoursTotal? ?? 
write?  ? ?? 
delete?  ? ?? 
validateWrite?  boolean? ?TSTimesheetTableTSTimesheetTable??         "   ? ActivityComplete?? ActivityNumber   ? 
lookupExtensionActive?  boolean? ?? 
lookup   ? _formControl FormControl?? 
_filterStr  ??  ? ?? 
modified?  ? ??? ActivityRemaining?? ApplyAction?? ApprovalStatus?? ApproverList?? 
CategoryId   ? 
modified?  ? ??? 	CreatedBy?? CreatedDateTime?? CreatedTransactionId?? CurrencyCode?? 
DataAreaId?? DefaultDimension?? LineNum?? LinePropertyId?? 
ModifiedBy?? ModifiedDateTime?? ModifiedTransactionId?? PackedExtensions?? 	Partition?? ProjCompanySalesCurrency?? ProjectDataAreaId?? ProjId   ? 
modified?  ? ??? ProjPeriodTimesheetWeek?? RecId?? Resource?? TableId?? 
TaxGroupId?? TaxItemGroup?? TimesheetNbr?? TSFavorites?? WebTransaction?? Worker?? WrkCtrId?       ? 
init?  ? ?? 
validateDelete?  boolean? ?? 
changeReason   ? _set boolean?? _tsTimesheetLine TSTimesheetLine?? ''_value Notes??  Notes? ?? 
validateWrite?  boolean? ?? 
delete   ? null_timesheetLine TSTimesheetLine??  ? ?? 
!initializeTimesheetLineWeekBuffer   ? _tsTimesheetLineWeek TSTimesheetLineWeek??  TSTimesheetLineWeek? ?? 
write?  ? ?? 
active?   ? ?? 
create   ? false_append boolean??  ? ?? 
	initValue?  ? ?? 
workflowIcon   ? _line TSTimesheetLine??   ? ?? 
customerName   ? _line TSTimesheetLine??  CustName? ?TSTimesheetLineTSTimesheetLine??       '   ? 
dataAreaId?? DayFrom?? DayTo?? ExternalComments[1]?? ExternalComments[2]?? ExternalComments[3]?? ExternalComments[4]?? ExternalComments[5]?? ExternalComments[6]?? ExternalComments[7]?? Hours[1]?? Hours[2]?? Hours[3]?? Hours[4]?? Hours[5]?? Hours[6]?? Hours[7]?? InternalComments[1]?? InternalComments[2]?? InternalComments[3]?? InternalComments[4]?? InternalComments[5]?? InternalComments[6]?? InternalComments[7]?? 	JournalId?? LineNum?? 	Partition?? 
PeriodDate?? 
PostStatus?? ProjPeriodId?? ProjTransDate?? RecId?? 
SalesPrice?? TableId?? TimesheetNbr?? 	TransDate?? TransId?? TSTimesheetLine?? Voucher?    TSTimesheetLine    ? 
delete?  ? ?? 
validateWrite?  boolean? ?? 
write   ? false_doWork boolean??  ? ?? 
	initValue?  ? ?TSTimesheetLineWeekTSTimesheetLineWeek??          ? Commissionarate?? Division?? 	ECCNumber?? ExciseLTUCode?? GSTIN?? GSTTransNumSeqGroup_IN?? IECRegistrationNumberTable?? 	IsPrimary?? ManECCRegistrationNumberTable?? Name?? 	Partition?? Range?? RecId?? RegistrationLocation?? SalesTaxRegistrationNumber?? STCRegistrationNumberTable?? TableId?? TAN?? TaxID?? TIN??  TraderECCRegistrationNumberTable?TSTimesheetLineTaxExtensionIN TaxInformation_INTaxInformation_IN??          ? CompanyLocation   ? 
jumpRef?  ? ?? 
lookupReference   ? _formReferenceControl FormReferenceControl??  Common? ?? 
modified?  ? ??? CustomerLocation?? CustomerTaxInformation?? 
dataAreaId?? Exempt?? HSNCodeTable?? ITCCategory?? 	Partition?? RecId?? ServiceAccountingCodeTable?? ServiceCategory?? TableId?? TaxInformation   ? 
jumpRef?  ? ?? 
lookupReference   ? _formReferenceControl FormReferenceControl??  Common? ?? 
modified?  ? ??? TSTimesheetLine?TSTimesheetLine     ? 
isNeeded?  boolean? ?? 
init?  ? ?TSTimesheetLineTaxExtensionINTSTimesheetLineTaxExtensionIN??  
 ?
@SYS190484   ?         ?      @SYS716   ?  
 ?@SYS2055   ?    ?TSTimesheetTable# ?0TSTimesheet_Copy1 2   ? 
clicked?  ? ?3  4CopyTimesheet7 N  ?)  5NewGroupL  ??  
 ?
@SYS316703   ?  ??m?6%1# ?% '  0TSTimesheetMyDelegates2   ? 
clicked?  ? ?4	Delegates: ? C  G
@SYS184032L????P  ??   ?H?$I%1# ?'  0TSTimesheetMyFavorites2   ? 
clicked?  ? ?4	Favorites? @  C  G	@SYS95713L????P  ????/!%1)  0    5MaintainGroupH????L  ??  
 ?
@SYS323065   ?   ?	 TSTimesheetTableTUUU%1# ?'  0ProjTransEmpl4HourTransactions7 C  G	@SYS75774L????P  ?????!%1)  0    5RelatedInfoGroupH????L  ??  
 ?
@SYS314071   ?   ?	 TSTimesheetTable???*%1# ?'  0ProjLedgerTransVoucher4ProjLedgerTransVoucher7 ? G
@SYS116039L????N  P  ??   ?	  TSTimesheetTable????%1# ?'  0#AccountingDistributionsDocumentView4#AccountingDistributionsDocumentView7 C  L????N  P  ??   ?	 TSTimesheetTable???_%1# ?'  0TSTimesheetPostSourceDocument1 2   ? 
clicked?  ? ?? 
isPostingMultipleTimesheets?  boolean??3 4TSTimesheetPostSourceDocument7 L????N  P  ????O!%1)  0    5
AccountingH????L  ??  
 ?
@SYS302689   ?   ?	 TSTimesheetTableTUUU%1# ?'  0TSTableVersion4VersionList7 ? C  G@SYS4005390L????P  ??$IR!%1)  0    5ButtonGroupManageI L  ??  
 ?	@SYS91576   ?  ?	 TUUU%1# ?'  0TSTimesheetSignOff1 3 4MenuItemButton7 C  L????P  ????o!%1)  0    5PrintReportH????L  ??  
 ?@Timesheet:Policy_Group_Caption   ?   ?# ?0TSEvaluatePolicies1 3  4EvaluatePolicies7 G'@Timesheet:EvaluatePolicies_Button_Text?)  5PoliciesGroupL  ?TSTimesheetTableTUUU%1   ,ActionPaneTab<????@  ?? 
 ?   ?   ?	 ?  TSTimesheetTable% ?2TSTimesheetWorkflowDropDialog5"TSTimesheetTableWorkflowDropDialog8 9Workflow?TSTimesheetTable5+TimesheetTableWorkflowDropDialogButtonGroup????%1  )
ActionPane:????=    ?? 
 ?   ? ?    ? targetControlName NavigationListGrid?? defaultColumnName TSTimesheetTable_TimesheetNbr?? placeholderText ?QuickFilterControl?QuickFilterControl& ??  ? ?   ?   ?  ?TimesheetNbrTSTimesheetTable' ?6 ?GTSTimesheetTable_TimesheetNbr??  ?TSTimesheetTable( ?9 ?F   ? 
jumpRef?  ? ?GTSTimesheetTable_ResourceMResourceN
AutoLookup??  ?displayTimesheetPeriodTSTimesheetTable' ?6 ?GTSTimesheetTable_Period??  	 ?
totalHoursTSTimesheetTable+ ?; ?LTSTimesheetTable_TotalHours?TSTimesheetTable2  3NavigationListGrid;  = K ?* , <NavigationListF Q  ??      
 ?   ?  
 ?   ?  
 ?   ?     ?
  ????"%1%   & ' ?0	@SYS153786 ?GHeaderTitleR  S T [????] ` ?* <TitleF S ?? 
 ?   ? 
 ?   ? 
 ?   ? 
 ?	@SYS15311     ?  
 ?   ? 	  ?   ?  ?Worker.DirPerson_FK"%1' ?*  6 ?G!WorkerName_DirPerson_FK_NameCopy1[????`  ?TSTimesheetTableTUUU#%1( ?9 ?F   ? 
lookupReference?  Common? ?? 
jumpRef?  ? ?GResource_LineViewHeaderMResourceN
AutoLookup[?????2333#%1* <LineViewHeaderGeneralN?????? 
 ?   ?     ?????TSTimesheetPeriod"%1' ?6 ?E   ? 
lookup?  ? ?GPeriodDateRange_LineViewHeader[??????   ????_TSTimesheetWeekPeriod"%1' ?6 ?B C E   ? 
lookup?  ? ?GTimesheetWeek_LineViewHeader[????] ?<LineViewHeaderDates?? 
 ?   ?  ?ApprovalStatusTSTimesheetTable % ?5 ?@.TSTimesheetTable_ApprovalStatus_LineViewHeaderO ??  	 ?timesheetTotalHoursTSTimesheetTable   + ?5
@SYS333677; ?LtotalHours_LineViewHeader?<LineViewHeaderSummary?0LineViewHeaderDetailsTabPage5FieldsFieldGroups61.1?? 
 ?
@SYS339037   ?          ?         ? 
 ?	   ?   ? cV%1" ?%  .   ? 
clicked?  ? ?0NewLine2 4Add@	@SYS59247G????K  ??    ? TSTimesheetLinenW?$%1# ?'  0TSDeleteCurrentRecordAction1 2   ? 
clicked?  ? ?3 4
DeleteLine6 7 8Delete@  G
@SYS311855L????P  ??   ? ?Kh/%1" ?%  .   ? 
clicked?  ? ?/  0DeleteLineButton2 4Delete:  @
@SYS311855G????K  ??    ? )O  %1" ?%  .   ? 
clicked?  ? ?/  0StartStopTime3 4Timer@
@SYS333672G????K  ??   ?    ?  ? TSTimesheetTable2333%1# ?'  0TSTimesheetEntryCopy2   ? 
clicked?  ? ?4CopyFromTimesheetG	@SYS15311L????P  ??   ? TSTimesheetTable???L%1# ?'  0#TSTimesheetCreateLinesFromFavorites1 2   ? 
clicked?  ? ?4MyFavoritesL????P  ??   ? TSTimesheetTabledfff%1# ?'  0$TSTimesheetCreateLinesFromActivities1 2   ? 
clicked?  ? ?4AssignedActivitiesG	@SYS80292L????P  ??Z.\  %1$ ?'  3CopyFrom7CopyD	@SYS68297J????N  ??   ? TSTimesheetLine?Yi%1# ?'  0TSTimesheetAddFavorites1 3 4TSTimesheetAddFavorites7 8SaveL????P  ??    ? ???v  %1" ?%  .   ? 
clicked?  ? ?/ 0SaveToFavorites4Save@
@SYS333668G????I  K  ??   ?	 ? TSTimesheetLine% ?2TSTimesheetWorkflowDropDialog5!TSTimesheetLineWorkflowDropDialog8 9Workflow??   ?TSTimesheetLine# ?0TransTaxInformation4TransTaxInformation7 N  ?TSTimesheetLineTUUU!%10    5LineWorkflowButtonGroupH?????TSTimesheetLineTUUU%1   ,ActionPaneTab_LineView<????@  ?TSTimesheetLine????%1)ActionStrip3 :??????  ? ?	  ?   ? 
 ?   ?   ?workflowIconTSTimesheetLine ?    $@Proj:WorkflowIcon* ?6LineGridWorkflowImage<  ??   ? ProjectDataAreaIdTSTimesheetLine    ???
"%1' ?*  6 ?E   ? 
lookup?  ? ?? 
modified?  boolean? ?G!TSTimesheetLine_ProjectDataAreaId[????`  ??   ?custAccountTSTimesheetLine
    a?M"%1' ?*  0@SYS3026 ?E   ? 
lookup?  ? ?? 
jumpRef?  ? ?? 
resolveAmbiguousReference?   ? ?? 
modified?  boolean? ?GCustAccount[????_    `  ??   ?customerNameTSTimesheetLine' ?6 ?GCustName??   ?ProjIdTSTimesheetLine
    ' ?6 ?E   ? 
lookup?  ? ?? 
modified?  boolean? ?? 
jumpRef?  ? ?GProjId`  ??  ?projNameTSTimesheetLine    ' ?6 ?GProjName??   ?ActivityNumberTSTimesheetLine
    ' ?6 ?E   ? 
jumpRef?  ? ?? 
modified?  boolean? ?GActivityNumber`  ??  ?activityTxtTSTimesheetLine    ' ?0	@SYS383816 ?GActivityTxt??   ?
CategoryIdTSTimesheetLine
    ' ?6 ?E   ? 
lookup?  ? ?? 
modified?  boolean? ?? 
jumpRef?  ? ?GCatergoryName`  ??    	 ?Hours[1]TSTimesheetLineWeek    ?[1&%1+ ?/  ; ?I   ? 
gotFocus?  ? ?? 

textChange?  ? ?? 
modified?  boolean? ?LTSTimesheetLineWeek_Hours_1N????b????fF   g ??    	 ?Hours[2]TSTimesheetLineWeek    
?)9&%1+ ?/  ; ?I   ? 
gotFocus?  ? ?? 

textChange?  ? ?? 
modified?  boolean? ?LTSTimesheetLineWeek_Hours_2N????b????fF   g ??    	 ?Hours[3]TSTimesheetLineWeek    >?@&%1+ ?/  ; ?I   ? 
gotFocus?  ? ?? 

textChange?  ? ?? 
modified?  boolean? ?LTSTimesheetLineWeek_Hours_3N????b????fF   g ??    	 ?Hours[4]TSTimesheetLineWeek    ??H&%1+ ?/  ; ?I   ? 
gotFocus?  ? ?? 

textChange?  ? ?? 
modified?  boolean? ?LTSTimesheetLineWeek_Hours_4N????b????fF   g ??    	 ?Hours[5]TSTimesheetLineWeek    ???P&%1+ ?/  ; ?I   ? 
gotFocus?  ? ?? 

textChange?  ? ?? 
modified?  boolean? ?LTSTimesheetLineWeek_Hours_5N????b????fF   g ??    	 ?Hours[6]TSTimesheetLineWeek    ?KcX&%1+ ?/  ; ?I   ? 
gotFocus?  ? ?? 

textChange?  ? ?? 
modified?  boolean? ?LTSTimesheetLineWeek_Hours_6N????b????fF   g ??    	 ?Hours[7]TSTimesheetLineWeek    ??1`&%1+ ?/  ; ?I   ? 
gotFocus?  ? ?? 

textChange?  ? ?? 
modified?  boolean? ?LTSTimesheetLineWeek_Hours_7N????b????fF   g ??  	 ?
totalHoursTSTimesheetLineWeek    ???g&%1+ ?/  5	@SYS58659; ?L	LineTotalN????b????f2   g ??  ?LinePropertyIdTSTimesheetLine???o"%1' ?*  6 ?E   ? 
lookup?  ? ?? 
jumpRef?  ? ?? 
modified?  boolean? ?GTSTimesheetLine_LinePropertyId[????_F   `  ??   ?ApprovalStatusTSTimesheetLineMUUu %1% ?(  5 ?@TSTimesheetLine_ApprovalStatusM?????,  <lineGridGroupS  ?TSTimesheetLine???_!%13LineGrid= C????H   I ?TSTimesheetLine % 0LineViewLines?? 
 ?	@SYS23823   ?      
 ?   ?  
 ?@SYS5343     ? 
 ?   ?   ?2333 %1% ?/@SYS45695 ??   ? 
selectionChange?   ? ?@CommentsDayComboBoxM????O ?<LineViewDetailsCommentsDate?? 
 ?   ?   ?InternalComments[1]TSTimesheetLineWeekTUUU"%1' ?6 ?G$TSTimesheetLineWeek_InternalComments[?????<LineViewDetailsCommentsInternal?? 
 ?   ?   ?ExternalComments[1]TSTimesheetLineWeekTUUU"%1' ?6 ?G$TSTimesheetLineWeek_ExternalComments[?????<LineViewDetailsCommentsExternal?TSTimesheetLine???*!%1%  '  0CommentsTabPage5FieldsFieldGroups61.1:c E????J ?? 
 ?
@SYS114913     ? 
 ?
@SYS333675   ?  	 ?
SalesPriceTSTimesheetLineWeek???&%1+ ?; ?LTSTimesheetLineWeek_SalesPriceN????b??????   ?CurrencyCodeTSTimesheetLine???/"%1' ?6 ?GTSTimesheetLine_CurrencyCode[??????   ?editTaxGroupTSTimesheetLine???J"%1' ?6 ?E   ? 
jumpRef?  ? ?? 
lookup?  ? ?GTSTimesheetLine_TaxGroupId[??????   ?editTaxItemGroupTSTimesheetLineSUUe"%1' ?6 ?E   ? 
jumpRef?  ? ?? 
lookup?  ? ?GTSTimesheetLine_TaxItemGroup[?????TUUU#%1<BillingN?????????!%1%  0General5FieldsFieldGroups61.1:c E????J ??  
 ?
@SYS138491   ?  ?    ? parmControllerClassName 	ClassName?? parmControlLabelText 
@SYS138487?? parmEnumerationName ?? parmDataSourceName TSTimesheetLine?? parmValueSetReferenceField DefaultDimension?? parmEnumValueSetReferenceField ?DimensionEntryControl?'DimensionEntryControl: ?TUUU !%1'  0
Dimensions5DimensionEntryControl61.1:c E????J ??  
 ?@SYS4006054     ?   ?ChangeReasonTSTimesheetLineTUUU"%1' ?0@SYS40060546 ?E   ? 
	lostFocus?  ? ?GTSTimesheetLineLog_ChangeReason[?????TSTimesheetLineTUUU!%1%  0ChangeReasonTabPage5FieldsFieldGroups61.1:c E????J ?TUUU!%10LineDetailsTabJ?????TSTimesheetLine 0LineViewLineDetails?0LineViewTab< ?0LinesPanelTabPage3 ?? 
 ?   ? 
 ?   ? 
 ?	@SYS15311     ?  
 ?   ? 	  ?   ?  ?Worker.DirPerson_FK"%1' ?*  6 ?GWorkerName_DirPerson_FK_Name[????`  ?TSTimesheetTableTUUU#%1( ?9 ?F   ? 
lookupReference?  Common? ?? 
jumpRef?  ? ?GResource_HeaderDetailsMResourceN
AutoLookup[?????2333#%1* <HeaderDetailsGeneralN?????? 
 ?   ?     ?????TSTimesheetPeriod"%1' ?6 ?E   ? 
lookup?  ? ?GPeriodDateRange_HeaderDetails[??????   ????_TSTimesheetWeekPeriod"%1' ?6 ?B C E   ? 
lookup?  ? ?GTimesheetWeek_HeaderDetails[????] ?dfff#%1<HeaderDetailsDatesN?????? 
 ?   ?  ?ApprovalStatusTSTimesheetTable% ?5 ?@-TSTimesheetTable_ApprovalStatus_HeaderDetailsO ??  	 ?timesheetTotalHoursTSTimesheetTable   + ?5
@SYS333677; ?LtotalHours_HeaderDetails?<HeaderDetailsSummary?0HeaderDetailsTabPage5FieldsFieldGroups61.1?0HeaderDetailsTab< ?0HeaderPanelTabPage3 ?0HeaderAndLinePanels:  ????*!%1%  0DetailsPanel3 :c < E????J  ?? 
 ?   ?  
 ?   ? ?    ? targetControlName GridView?? defaultColumnName &TSTimesheetTable_TimesheetNbr_GridView?? placeholderText ?QuickFilterControl?CustomFilterQuickFilter??   ?TUUUTSTimesheetListPageFilter %1% ?5 ??   ? 
executeFilterQuery?  ? ?? 
selectionChange?   ? ?@MyTimesheetFilterM????P  ?* <CustomFilterGroup@CustomAndQuickFiltersA1.1F P S ??  ? ? ?   ?  ?TimesheetNbrTSTimesheetTable' ?6 ?G&TSTimesheetTable_TimesheetNbr_GridView] _?   ` ??  ?TSTimesheetTable( ?9 ?F   ? 
jumpRef?  ? ?G"TSTimesheetTable_Resource_GridViewMResourceN
AutoLookup] _?   ` ??  ?TSTimesheetTable( ?3
Supervisor9 ?F   ? 
jumpRef?  ? ?G TSTimesheetTable_Resource_ParentMSIGParentResourceN
AutoLookup] _?   ` ??  ?
PeriodFromTSTimesheetTable, ?5@SYS428; ?K$TSTimesheetTable_PeriodFrom_GridView\ ^?   _ ??  ?PeriodToTSTimesheetTable, ?5	@SYS50115; ?K"TSTimesheetTable_PeriodTo_GridView\ ^?   _ ??  ?ApprovalStatusTSTimesheetTable% ?5 ?@(TSTimesheetTable_ApprovalStatus_GridViewO Q?   R ?? 	 ?
totalHoursTSTimesheetTablep?q&%1+ ?5
@SYS333677; ?L$TSTimesheetTabke_TotalHours_GridViewN????b????f?   g ?TSTimesheetTableMainDefaultActionView Details3GridView??  ?$" ?0MainDefaultActionJ  ?0	GridPanel3 < ?????!%10PanelTab:  J?????TSTimesheetTable     0DetailsTransaction11.47  8  :	 <TSTimesheetTableB C E    F ?   " projPeriodTimesheetWeek ProjPeriodTimesheetWeek?" projPeriodLine ProjPeriodLine?" projParameters ProjParameters?" timesheetRecId RecId?" requireStartStopTime NoYes?" skipValidateWrite boolean?" isDeletingLine boolean?" createdFromEss boolean?" cdsLockingOptionTimesheets boolean?" listFormParts List?" mapCommentsDayComboboxIndex Map?" changeReasonsCollection !TSTimesheetChangeReasonCollection?" firstDayIndex  ?" 	dayLabels LabelString?" childDialogClosedOk boolean?" tsTimesheetEntryQuery TSTimesheetEntryQuery?" tsTimesheetEntryGridView TSTimesheetEntryGridView?" myTimesheetFilterSelection TSTimesheetListPageFilter?" currentResourceRecId ResourceRecId?" isOwnerOrDelegate boolean?" workflowIconObservableLink FormObservableLink?" isTaxParametersMarked_IN boolean?" customerNameMap Map?
6   ? 
classDeclaration? ??? 
refreshWorkflowIcon?  ? ?? 
%updateWorkflowButtonForLineVisibility?  ??? 
enableWorkflowButton?  ??? 
activateTimesheetTable?  ? ?? 
initDetailsViewOnly?  ??? 
allowHeaderFieldEdit   ? true_enable boolean??  ? ?? 
canSubmitToWorkflow?  boolean? ?? 
$canAddDeleteHeaderLineFromEntryPoint?  boolean? ?? 
&canCopySelectedTimesheetFromEntryPoint?  boolean? ?? 
formInitPost?  ? ?? 
init?  ? ?? 
(getTSTimesheetEntryGridViewAllTimesheets   ? _args xArgs??  TSTimesheetEntryGridView? ?? 
openedFromEssMyTimesheets?  ??? 
callerTSTimesheetTable?  TSTimesheetTable? ?? 
setPeriodRangeDateFormControls   ? 	_fromDate 
PeriodDate?? _toDate 
PeriodDate??  ? ?? 
setTimesheetWeekDates   ? 	_fromDate 
PeriodDate?? _toDate 
PeriodDate??  ? ?? 
setProjPeriodLine?  ? ?? 
selectProjPeriodTimesheetWeek?  ? ?? 

initFields?  ? ?? 
isOwnerOrDelegate?  boolean? ?? 
loadTimesheetTable   ? _tsTimesheetTable TSTimesheetTable??  ? ?? 
isChangeReasonRequired?  boolean? ?? 
refreshFactBox?  ? ?? 
refreshTimesheetGrid?  ? ?? 
register   ? _object Object??  boolean? ?? 
setButtonVisibility?  ? ?? 
setCommentDays   ? 	_periodId ProjPeriodId?? _periodFrom ProjPeriodFrom?? 	_periodTo ProjPeriodTo??  ? ?? 
setDates?  ? ?? 
setFocusOnDayIndex   ? _index  ??  ? ?? 
isLineEditable?  boolean? ?? 
setActionStripEnabled   ? _actionStrip FormActionPaneControl?? _tsTimesheetTable TSTimesheetTable??  ? ?? 
setHeaderObjects?  ? ?? 
setLineGridDays   ? 	_periodId ProjPeriodId?? _periodFrom ProjPeriodFrom?? 	_periodTo ProjPeriodTo??  ? ?? 
canDeleteLine?  boolean??? 
isLineNotSavedInReadOnly?  boolean??? 
setLineObjects   ? true_enable boolean??  ? ?? 
setHeaderTitleText?  ? ?? 
setNewTimesheetNbr   ? _tsTimesheetNbr TSTimesheetNbr??  TSTimesheetTable? ?? 
$isTimesheetRetrievedByDataSouceQuery   ? 
_timesheet TSTimesheetTable??  boolean??? 
workflowActionCompleted?  ? ?? 
setChildDialogClosedOk   ? _childDialogClosedOk boolean??  ? ?? 
getChildDialogClosedOk?  boolean? ?? 
task   ? _taskId  ??   ? ?? 
refreshData?  ? ?? 
performPeriodDateLookup   ? _formControl FormStringControl??  ? ?? 
performTimesheetLineWeekLookup   ? _formControl FormStringControl??  ? ?? 
viewDetailsJumpRef   ? 	_menuItem  ?? _record Common??  ??? 
runDisplayMenuItem   ? 	_menuItem  ??  ??? 
enableComments   ? _index  ?? _changedValue  ??  ? ?? 
run?  ? ?? 
close?  ? ?? 
 validateProjectExternallyManaged   ? _projId ProjId??  boolean??? 
applyRecordContext   ? _recordContext  ??  boolean? ?SIGTSTimesheetEntry   ? TSTimesheetTable???? TSTimesheetEntryTotalsPartTSTimesheetEntryTotalsPart??