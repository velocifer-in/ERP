7   !SIGProjPostedTransTable_Extension?tg5    X  !CustAgingReportControllerCopyCopy?tg5X  ?  RADCustAgingReportControllerV1?tg5  ?  RADPayChequeContract?tg5?  ?  SIGTrvExpTrans_Extension?tg5C  ?   !SIGProjInvoiceProposalCreateLines?tg5.  ?  RADPSAProjInvoiceDP_Extension?tg5  %  SIGChequeControllerExt?tg5<  ?   RunnableClassdefalutdim?tg5  v   RADPayChequeWeeklyUIBuilder?tg5?  ?  ProjRepContract?tg5R  ?  SIGProjGroupUpdation?tg5?  ?  -SIGCustVendChequeSlipTextCalculator_Extension?tg5?   U  SIGDimensionHelper?tg5%  ?  RADTimesheetValidation?tg5*  |   SIGProjInvoiceTable_Extension?tg5?*  ?  SIGTmpChequePrintout_Extension?tg5e-  ?    SIGTSTimesheetLineWeek_Extension?tg5Y.    SIGTimeSheetTableUpdationBatch?tg5d/  ?   SIGProjInvoiceJour_Extension?tg5V0  ;  SIGTSTimesheetTable_Extension?tg5?1  ?  RADPrintMgtDocTypeHandlersExt?tg5<5  q  RunnableClass1?tg5?6  d   RADCustInvAmountYearContract?tg57  ?  SIGPostedProjTransUpdationBatch?tg5?;  ?   SIGProjProposalJour_Extension?tg5?<  ?  SIGProjProposalJourUpdation?tg5&?  _  )RADPsaProjAndContractInvoiceControllerExt?tg5?@  ?  SIGTSTimeSheetEntry_Extension?tg5rB  ?   #RADEmployeeTSAndUtilizationContract?tg5`C  x  SIGCustVendCheque_Extension?tg5?I  n  RADPayrollChequeDP?tg5FK    RADCustAgingReportDPV2?tg5`N  ?  SIGProjTable_Extension?tg5?b  ?  SIGProjInvoiceControl_Extension?tg5?d  a  SIGTimeSheetTable_Extension?tg54f  ?   SIGPSAProjInvoiceTmp_Extension?tg5!g  B  SIGChequeDP_Extension?tg5ch  ?   SIGCreditCardTransDeleteBatch?tg5<i  _  $RADEmployeeTSAndUtilizationUIBuilder?tg5?k  ?  RADPayChequeUIBuilder?tg5?p  ?  SIGProjPostTransView_Extension?tg5Hu  x  SIGEmployeeTimesheet?tg5?v  p   RADEmployeeTSAndUtilizationDP?tg50w  ?  RADPayChequeWeeklyContract?tg5?{  ?  RADCustAgingReportDPV1?tg5f?  ?  SIGChequeTmp_Extension?tg5?  ?   RADCustInvAmountYearDP?tg5֘    ProjreportDP?tg5ٞ  ?  RADPayrollChequeWeeklyDP?tg5Р  2  CustAgingReportDPCopy?tg5?  ?  SIGProjectBudgetApproval?tg5??  x   RADCustAgingReportControllerV2?tg5?  ?  SIGProjectBudgetApprovalBatch?tg5ƻ  ?    SIGPSAProjProposalProj_Extension?tg5??  ?   ? !     ExtensionOf        ProjPostedTransTable? ? ? tableStr??i[ExtensionOf(tableStr(ProjPostedTransTable))]
final public class SIGProjPostedTransTable_Extension
{
}   ? 
displayIntComment?  	TSComment? ?? 
displayExtComment?  	TSComment? ?? 
insert?  ? ?!SIGProjPostedTransTable_Extension?? ! ?/// <summary>
///    The <c>CustAgingReportController</c> class is the controller class for the <c>CustAgingReport</c>
///    SRS report.
/// </summary>
public class CustAgingReportControllerCopyCopy extends SrsReportRunController
{
}SrsReportRunController   ? 
getReportName   ? 	_contract CustAgingReportContract??   ? ?? 
prePromptModifyContract?  ? ?? 
preRunModifyContract?  ? ?? 
preRunValidate?   ? ?? 
queryChanged   ? _key  ?? _query Query??  ? ?? 
	setRanges   ? _query Query?? 	_contract CustAgingReportContract??  ? ?? 	
main   ? _args Args??  ? ?!CustAgingReportControllerCopyCopy?? ! ?/// <summary>
///    The <c>CustAgingReportController</c> class is the controller class for the <c>CustAgingReport</c>
///    SRS report.
/// </summary>
public class RADCustAgingReportControllerV1 extends SrsReportRunController
{
}SrsReportRunController   ? 
getReportName   ? 	_contract CustAgingReportContract??   ? ?? 
prePromptModifyContract?  ? ?? 
preRunModifyContract?  ? ?? 
preRunValidate?   ? ?? 
queryChanged   ? _key  ?? _query Query??  ? ?? 
	setRanges   ? _query Query?? 	_contract CustAgingReportContract??  ? ?? 	
main   ? _args Args??  ? ?RADCustAgingReportControllerV1?? !     DataContractAttribute? 'SysOperationContractProcessingAttribute        RADPayChequeUIBuilder? ? ? classStr?     &CreateSeparateUIBuilderForEachContract?	 &SysOperationDataContractProcessingMode???/// <summary>
///    The <c>PayrollPayStatementReportContract</c> class is the Data Contract class for the <c>PayrollPayStatementReport</c>
///    SSRS report.
/// </summary>
/// <remarks>
///    This is the Data Contract class for the the <c>PayrollPayStatementReport</c> SSRS Report.
/// </remarks>

[
    DataContractAttribute,
    SysOperationContractProcessingAttribute(classStr(RADPayChequeUIBuilder), SysOperationDataContractProcessingMode::CreateSeparateUIBuilderForEachContract)
]
public class RADPayChequeContract
{
    #DEFINE.PayCycle("PayCycle")
    #DEFINE.PayPeriod("PayPeriod")

    RADPayrollPayCycleRecId            payrollPayCycleRecId;
    PayrollPayPeriodRecId           payrollPayPeriodRecId;
    
}   " payrollPayCycleRecId RADPayrollPayCycleRecId?" payrollPayPeriodRecId PayrollPayPeriodRecId?   ?     DataMemberAttribute    
"PayCycle"?? SysOperationLabelAttribute        @Payroll:PayCycle1? ? ? 
literalStr?? SysOperationHelpTextAttribute        @SYS4090106? ? ? 
literalStr?? !SysOperationDisplayOrderAttribute    "0"??
parmPayCycle   ? payrollPayCycleRecId_payrollPayCycleRecId RADPayrollPayCycleRecId??  RADPayrollPayCycleRecId? ??     DataMemberAttribute    "PayPeriod"?? SysOperationLabelAttribute        @Payroll:PayPeriod? ? ? 
literalStr?? SysOperationHelpTextAttribute        @SYS4090107? ? ? 
literalStr?? !SysOperationDisplayOrderAttribute    "1"??
parmPayPeriod   ? payrollPayPeriodRecId_payrollPayPeriodRecId PayrollPayPeriodRecId??  PayrollPayPeriodRecId? ?RADPayChequeContract?? !     ExtensionOf        TrvExpTrans? ? ? tableStr??W[ExtensionOf(tableStr(TrvExpTrans))]
public final class SIGTrvExpTrans_Extension
{
}   ? 
validateWrite?  boolean? ?SIGTrvExpTrans_Extension?? ! ?//[ExtensionOf(formControlStr(ProjInvoiceProposalCreateLines, SIGCreateProposal))]
public  class SIGProjInvoiceProposalCreateLines//_Extension
{
    
    
}   ?     FormControlEventHandler        ProjInvoiceProposalCreateLines? SIGCreateProposal? ? formControlStr?     GotFocus?	 FormControlEventType??	
SIGCreateProposal_OnGotFocus   ? sender FormControl?? e FormControlEventArgs??  ? ?!SIGProjInvoiceProposalCreateLines?? !     ExtensionOf        PSAProjInvoiceDP? ? ? classStr??g[ExtensionOf(classStr(PSAProjInvoiceDP))]
final public class RADPSAProjInvoiceDP_Extension
{
    
}   ? 
initFromProjProposalOnAcc   ? _projProposalOnAcc ProjProposalOnAcc??  ? ?? 
initFromProjProposalEmpl   ? _projProposalEmpl ProjProposalEmpl??  ? ?? 
initFromProjInvoiceEmpl   ? _projInvoiceEmpl ProjInvoiceEmpl??  ? ?? 
initFromProjInvoiceOnAcc   ? _projInvoiceOnAcc ProjInvoiceOnAcc??  ? ?? 
initFromProjInvoiceItem   ? _projInvoiceItem ProjInvoiceItem??  ? ?? 
initFromProjInvoiceRevenue   ? _projInvoiceRevenue ProjInvoiceRevenue??  ? ?? 
initFromProjProposalItem   ? _projProposalItem ProjProposalItem??  ? ?? 
initFromProjProposalRevenue   ? _projProposalRevenue ProjProposalRevenue??  ? ?? 
populatePSAProjInvoiceHeaderTmp?  ? ?? 
calcTotalBudgetLine   ? _projId ProjId??  ProjBudgetLine? ?? 	
cfbs_formatAddress   ? _address LogisticsPostalAddress??  LogisticsAddressing? ?? 
initFromProjInvoiceCost   ? _projInvoiceCost ProjInvoiceCost??  ? ?? 
initFromProjProposalCost   ? _projProposalCost ProjProposalCost??  ? ?RADPSAProjInvoiceDP_Extension?? ! ;class SIGChequeControllerExt extends ChequeController
{
}ChequeController   ? 	
	construct?  SIGChequeControllerExt? ?? 	
main   ? _args Args??  ? ?SIGChequeControllerExt?? ! #class RunnableClassdefalutdim
{
}   ? 	
main   ? _args Args??  ? ?RunnableClassdefalutdim?? ! ?class RADPayChequeWeeklyUIBuilder extends SrsReportDataContractUIBuilder
{
    RADPayChequeWeeklyContract   rdpContract;
   // PayrollPayStatementReportController ctrl;
    FormBuildComboBoxControl            cmbBuildPayPeriod;
    FormComboBoxControl                 cmbPayPeriod;
    DialogField                         dlgFldPayCycle;
    DialogField                         dlgFldPayPeriod;
  //  DialogField                         dlgFldDisbursement;
    container                           payPeriodList;

    #DEFINE.PayPeriodListControl('PayPeriodListControl')
    /// <summary>
    ///     Add customizations for controls created for contract parameter in report dialog.
    /// </summary>

}SrsReportDataContractUIBuilder   " rdpContract RADPayChequeWeeklyContract?" cmbBuildPayPeriod FormBuildComboBoxControl?" cmbPayPeriod FormComboBoxControl?" dlgFldPayCycle DialogField?" dlgFldPayPeriod DialogField?" payPeriodList  ?   ? 
build?  ? ?? 
getFromDialog?  ? ?? 
initPayPeriods?  ??? 
modified   ? _control FormReferenceGroupControl??  boolean? ?? 
postRun?  ? ?? 
setLastPayPeriod?  ??RADPayChequeWeeklyUIBuilder?? !     DataContractAttribute?b[DataContractAttribute]
class ProjRepContract
{
    date FromDate,ToDate;
    
   


  
}   " FromDate  ?" ToDate  ?   ?     DataMemberAttribute    
'FromDate'??
parmfromDate   ? FromDate	_fromdate  ??   ? ??     DataMemberAttribute    'ToDate'??

parmToDate   ? ToDate_ToDate  ??   ? ?ProjRepContract?? ! ?class SIGProjGroupUpdation  extends RunBaseBatch
{
    DialogField             fieldDisplayMessage;
    DialogField             dlgProjGroupId,dlgProjLedgerStatusOnAcc;
    ProjGroupId             projGroupId;
    ProjLedgerStatusOnAcc   projLedgerStatusOnAcc;

}RunBaseBatch   " fieldDisplayMessage DialogField?" dlgProjGroupId DialogField?" dlgProjLedgerStatusOnAcc DialogField?" projGroupId ProjGroupId?" projLedgerStatusOnAcc ProjLedgerStatusOnAcc?   ? 	
	construct?  SIGProjGroupUpdation? ?? 
dialog?  Object? ?? 
getFromDialog?  boolean? ?? 
run?  ? ?? 	
main   ? _args Args??  ? ?SIGProjGroupUpdation?? !     ExtensionOf         CustVendChequeSlipTextCalculator? ? ? classStr???[ExtensionOf(classStr(CustVendChequeSlipTextCalculator))]
public final class SIGCustVendChequeSlipTextCalculator_Extension
{

}   ? 
;determineSlipTextTitleAndEndLinesAdjustmentForColumnHeaders   ? _bankChequeTable BankChequeTable?? _chequeFormType ChequeFormType??   ? ?? 
<determineSlipTextTitleAndEndLinesAdjustmentForChequeFormType   ? _bankChequeTable BankChequeTable?? _chequeFormType ChequeFormType??   ? ?? 
AdetermineSlipTextTitleAndEndLinesAdjustmentForChequeRecipientType   ? _bankChequeTable BankChequeTable?? _chequeFormType ChequeFormType??   ? ?? 
3determineSlipTextTitleAndEndLinesForSubTotalOrTotal   ? _args <CustVendChequeSlipTextCalcDeterminSlipTextForTotalParameters??  8CustVendChequeSlipTextCalcDeterminSlipTextForTotalReturn? ?? 
<determineSlipTextAndEndLinesAdjustmentForBankChequePaymTrans   ? bankChequePaymTrans BankChequePaymTrans??   ? ?-SIGCustVendChequeSlipTextCalculator_Extension?? ! ?class SIGDimensionHelper
{
    //put the default value here

    static protected Name businessUnit   = 'BusinessUnit';
    static protected Name department     = 'Department';
    static protected Name costCenter     = 'CostCenter';

}   " businessUnit Name?" 
department Name?" 
costCenter Name?	   ? 	
BusinessUnit?  Name? ?? 	

Department?  Name? ?? 	

CostCenter?  Name? ?? 	
TypeNew?  ? ?? 	
getValueByDefaultDimension   ? _dimensionDefault DimensionDefault?? _dimensionName Name??  DimensionValue? ?? 	
getValueByLedgerDimension   ? _dimensionDefault LedgerDimensionAccount?? _dimensionName Name??  DimensionValue? ?? 	
setValueToDefaultDimension   ? _dimensionDefault DimensionDefault?? _dimensionName Name?? _newDimensionValue DimensionValue??  DimensionDefault? ?? 	
setValueToDefaultDimensionCon   ? _dimensionDefault DimensionDefault?? _dimensionNameValueCon  ??  DimensionDefault? ?? 	
setDefaultDimensionRecId   ? _dimensionDefault DimensionDefault?? _dimensionAttributeRecId RefRecId?? _newDimensionValue DimensionValue??  DimensionDefault? ?SIGDimensionHelper?? ! *class RADTimesheetValidation
{        
}   ? 	
main   ? _args Args??  ? ?RADTimesheetValidation?? !     ExtensionOf        ProjInvoiceTable? ProjFundingSource? ? formDataSourceStr???[ExtensionOf(formDataSourceStr(ProjInvoiceTable,ProjFundingSource))]
Public final class SIGProjInvoiceTable_Extension
{
    
}   ?     FormControlEventHandler        ProjInvoiceTable? &SIGProjFundingSource_PSAInvoiceFormats? ? formControlStr?     Enter?	 FormControlEventType??	
.SIGProjFundingSource_PSAInvoiceFormats_OnEnter   ? sender FormControl?? e FormControlEventArgs??  ? ?? 
editInvoiceFormatSIG   ? _set boolean?? _projFundingSource ProjFundingSource?? 	_newValue PSAInvoiceFormat??  PSAInvoiceFormat? ?SIGProjInvoiceTable_Extension?? !     ExtensionOf        TmpChequePrintout? ? ? tablestr??e[ExtensionOf(tablestr(TmpChequePrintout))]
public final class SIGTmpChequePrintout_Extension
{

}   ? 
insert?  ? ?SIGTmpChequePrintout_Extension?? !     ExtensionOf        TSTimesheetLineWeek? ? ? tablestr??g[ExtensionOf(tablestr(TSTimesheetLineWeek))]
public final class SIGTSTimesheetLineWeek_Extension
{
}   ? 
validateWrite?  boolean? ? SIGTSTimesheetLineWeek_Extension?? ! ?class SIGTimeSheetTableUpdationBatch extends RunBaseBatch
{
}RunBaseBatch   ? 	
	construct?  SIGTimeSheetTableUpdationBatch? ?? 
run?  ? ?? 	
main   ? _args Args??  ? ?SIGTimeSheetTableUpdationBatch?? !     ExtensionOf        ProjInvoiceJour? ? ? tableStr??_[ExtensionOf(tableStr(ProjInvoiceJour))]
public final class SIGProjInvoiceJour_Extension
{
}   ? 
insert?  ? ?? 
initFromProjProposal   ? projProposalJour ProjProposalJour??  ? ?SIGProjInvoiceJour_Extension?? !     ExtensionOf        TSTimesheetTable? ? ? tableStr??a[ExtensionOf(tableStr(TSTimesheetTable))]
public final class SIGTSTimesheetTable_Extension
{
}   ?     !SysClientCacheDataMethodAttribute     True??
displayHours1?  HoursPerDay? ??     !SysClientCacheDataMethodAttribute     True??
displayHours2?  HoursPerDay? ??     !SysClientCacheDataMethodAttribute     True??
displayHours3?  HoursPerDay? ??     !SysClientCacheDataMethodAttribute     True??
displayHours4?  HoursPerDay? ??     !SysClientCacheDataMethodAttribute     True??
displayHours5?  HoursPerDay? ??     !SysClientCacheDataMethodAttribute     True??
displayHours6?  HoursPerDay? ??     !SysClientCacheDataMethodAttribute     True??
displayHours7?  HoursPerDay? ?SIGTSTimesheetTable_Extension?? ! )class RADPrintMgtDocTypeHandlersExt
{
}   ?     SubscribesTo        PrintMgmtDocType? ? ? classstr?     PrintMgmtDocType? getDefaultReportFormatDelegate? ? delegatestr??	
getDefaultReportFormatDelegate   ? _docType PrintMgmtDocumentType?? _result EventHandlerResult??  ? ?RADPrintMgtDocTypeHandlersExt?? ! class RunnableClass1
{
}   ? 	
main   ? _args Args??  ? ?RunnableClass1?? !     DataContractAttribute??/// <summary>
/// Data Contract class for <c>RADCustInvAmountYear</c> SSRS report
/// </summary>
/// <remarks>
/// This is the Data Contract class for the <c>RADCustInvAmountYear</c> SSRS Report.
/// </remarks>
[DataContractAttribute]
public class RADCustInvAmountYearContract
{
    CustAccount     custaccount;
    FromDate        fromDate;
    ToDate          toDate;
    AmountMST       minimumAmount;

}   " custaccount CustAccount?" fromDate FromDate?" toDate ToDate?" minimumAmount 	AmountMST?   ?     DataMemberAttribute    
'FromDate'?? SysOperationLabelAttribute        @SYS5209? ? ? 
literalstr?? SysOperationHelpTextAttribute        @SYS4083? ? ? 
literalstr??
parmFromDate   ? fromDate	_fromDate FromDate??  FromDate? ??     DataMemberAttribute    'ToDate'?? SysOperationLabelAttribute        	@SYS14656? ? ? 
literalstr?? SysOperationHelpTextAttribute        	@SYS53942? ? ? 
literalstr??

parmToDate   ? toDate_toDate ToDate??  ToDate? ?RADCustInvAmountYearContract?? ! @class SIGPostedProjTransUpdationBatch extends RunBaseBatch
{
}RunBaseBatch   ? 	
	construct?  SIGPostedProjTransUpdationBatch? ?? 
run?  ? ?? 	
main   ? _args Args??  ? ?SIGPostedProjTransUpdationBatch?? !     ExtensionOf        ProjProposalJour? ? ? tableStr??a[ExtensionOf(tableStr(ProjProposalJour))]
public final class SIGProjProposalJour_Extension
{
}   ? 
insert?  ? ??     !SysClientCacheDataMethodAttribute     True??
displayProjId?  ProjId? ??     !SysClientCacheDataMethodAttribute     True??
displayProjController?  Name? ??     !SysClientCacheDataMethodAttribute     True??
displayProjManager?  Name? ??     !SysClientCacheDataMethodAttribute     True??
displayProjName?  ProjectName? ?SIGProjProposalJour_Extension?? ! <class SIGProjProposalJourUpdation extends RunBaseBatch
{
}RunBaseBatch   ? 	
	construct?  SIGProjProposalJourUpdation? ?? 
run?  ? ?? 
getDisplayName   ? _dimensionDefault DimensionDefault?? _dimensionName Name??  Description? ?? 	
main   ? _args Args??  ? ?SIGProjProposalJourUpdation?? ! aclass RADPsaProjAndContractInvoiceControllerExt extends PSAProjAndContractInvoiceController
{
}#PSAProjAndContractInvoiceController   ? 	
	construct?  )RADPsaProjAndContractInvoiceControllerExt? ?? 	
main   ? _args Args??  ? ?? 
getReportTitle   ? _menuItemName MenuItemName?? _isProforma boolean??  PrintCopyOriginal::OriginalPrint_printCopyOriginal PrintCopyOriginal??  ReportTitle? ?)RADPsaProjAndContractInvoiceControllerExt?? !     ExtensionOf        TSTimeSheetEntry? ? ? formStr??`[ExtensionOf(formStr(TSTimeSheetEntry))]
public final class SIGTSTimeSheetEntry_Extension
{
}   ? 
setDates?  ? ?SIGTSTimeSheetEntry_Extension?? !     DataContractAttribute? 'SysOperationContractProcessingAttribute        $RADEmployeeTSAndUtilizationUIBuilder? ? ? classStr?     &CreateSeparateUIBuilderForEachContract?	 &SysOperationDataContractProcessingMode???[
    DataContractAttribute,
    SysOperationContractProcessingAttribute(classStr(RADEmployeeTSAndUtilizationUIBuilder), SysOperationDataContractProcessingMode::CreateSeparateUIBuilderForEachContract)
]
class RADEmployeeTSAndUtilizationContract
{
    #DEFINE.PayCycle("PayCycle")
    #DEFINE.PayPeriod("PayPeriod")

    PayrollPayCycleRecId            payrollPayCycleRecId;
    PayrollPayPeriodRecId           payrollPayPeriodRecId;
    
}   " payrollPayCycleRecId PayrollPayCycleRecId?" payrollPayPeriodRecId PayrollPayPeriodRecId?   ?     DataMemberAttribute    
"PayCycle"?? SysOperationLabelAttribute        @Payroll:PayCycle1? ? ? 
literalStr?? SysOperationHelpTextAttribute        @SYS4090106? ? ? 
literalStr?? !SysOperationDisplayOrderAttribute    "0"??
parmPayCycle   ? payrollPayCycleRecId_payrollPayCycleRecId PayrollPayCycleRecId??  PayrollPayCycleRecId? ??     DataMemberAttribute    "PayPeriod"?? SysOperationLabelAttribute        @Payroll:PayPeriod? ? ? 
literalStr?? SysOperationHelpTextAttribute        @SYS4090107? ? ? 
literalStr?? !SysOperationDisplayOrderAttribute    "1"??
parmPayPeriod   ? payrollPayPeriodRecId_payrollPayPeriodRecId PayrollPayPeriodRecId??  PayrollPayPeriodRecId? ?#RADEmployeeTSAndUtilizationContract?? !     ExtensionOf        CustVendCheque? ? ? classStr??][ExtensionOf(classStr(CustVendCheque))]
public final class SIGCustVendCheque_Extension
{
}   ? 
formatSlipText   ? _ledgerJournalTrans LedgerJournalTrans??  ChequeSlipTxt? ?? 
output   ? _custVendPaym CustVendPaym??  ? ?SIGCustVendCheque_Extension?? !     SrsReportParameterAttribute        RADPayChequeContract? ? ? classstr???[SrsReportParameterAttribute(classstr(RADPayChequeContract))]
class RADPayrollChequeDP extends SRSReportDataProviderBase
{
    RADPayCheckTmp  payCheckTmp,payCheckTmpDetails;
    StartDate           startDate,periodStartDate;
    EndDate             endDate,periodEndDate;

}SRSReportDataProviderBase   " payCheckTmp RADPayCheckTmp?" payCheckTmpDetails RADPayCheckTmp?" 	startDate 	StartDate?" periodStartDate 	StartDate?" endDate EndDate?" periodEndDate EndDate?   ?     SrsReportDataSetAttribute        RADPayCheckTmp? ? ? tableStr??
getPayCheckTmp?  RADPayCheckTmp? ?? 
processReport?  ? ?RADPayrollChequeDP?? !     SRSReportQueryAttribute        CustAgingReport? ? ? queryStr?? SRSReportParameterAttribute        CustAgingReportContract? ? ? classStr???/// <summary>
/// The <c>CustAgingReportDP</c> class declares the variables, tables, enumeration types, and so on
/// that are used in the <c>CustAgingReport</c> report.
/// </summary>
/// <remarks>
/// In Microsoft Dynamics AX 2012 R2 this class was changed to derive from the
/// <c>SRSReportDataProviderPreProcessTempDB</c> class instead of the <c>SRSReportDataProviderPreProcess</c>
/// class to improve performance. See <see cref="http://go.microsoft.com/fwlink/?LinkId=335910" />
/// for more information.
/// </remarks>
[
    SRSReportQueryAttribute(queryStr(CustAgingReport)),
    SRSReportParameterAttribute(classStr(CustAgingReportContract))
]
public class RADCustAgingReportDPV2 extends SRSReportDataProviderPreProcessTempDB
{
    CustAgingReportTmp custAgingReportTmp;
    CustTmpAccountSum tmpAccountSum;

    CustTable                       CustTable;
    DimensionAttributeValueSet      DimensionAttributeValueSet;
    DimensionAttributeValueSetItem  DimensionAttributeValueSetItem;
    DimensionAttributeValue         DimensionAttributeValue;
    DimensionAttribute              DimensionAttribute;
    OMOperatingUnit                 operatingUnit;
    DimensionFinancialTag           dimfintag;
    Name                            attributeName,attributeName2;

    CustVendBalanceList custVendBalanceList;
    CustAgingReportContract contract;

    ColumnTxt headingDate;
    TransDate heading011;
    TransDate heading02;
    TransDate heading021;
    TransDate heading03;
    TransDate heading031;
    TransDate heading04;
    TransDate heading041;
    TransDate heading05;
    TransDate heading051;
    TransDate heading06;
    TransDate heading061;
    TransDate heading07;
    TransDate heading071;

    TransTxt heading01;
    TransTxt heading02Text;
    TransTxt heading07Text;
    TransTxt headingAgingBucketDescription02;
    TransTxt headingAgingBucketDescription03;
    TransTxt headingAgingBucketDescription04;
    TransTxt headingAgingBucketDescription05;
    TransTxt headingAgingBucketDescription06;
    TransTxt headingAgingBucketDescription07;

    #define.emptyString(' ')
}
%SRSReportDataProviderPreProcessTempDB$   " custAgingReportTmp CustAgingReportTmp?" tmpAccountSum CustTmpAccountSum?" 	CustTable 	CustTable?" DimensionAttributeValueSet DimensionAttributeValueSet?" DimensionAttributeValueSetItem DimensionAttributeValueSetItem?" DimensionAttributeValue DimensionAttributeValue?" DimensionAttribute DimensionAttribute?" operatingUnit OMOperatingUnit?" 	dimfintag DimensionFinancialTag?" attributeName Name?" attributeName2 Name?" custVendBalanceList CustVendBalanceList?" contract CustAgingReportContract?" headingDate 	ColumnTxt?" 
heading011 	TransDate?" 	heading02 	TransDate?" 
heading021 	TransDate?" 	heading03 	TransDate?" 
heading031 	TransDate?" 	heading04 	TransDate?" 
heading041 	TransDate?" 	heading05 	TransDate?" 
heading051 	TransDate?" 	heading06 	TransDate?" 
heading061 	TransDate?" 	heading07 	TransDate?" 
heading071 	TransDate?" 	heading01 TransTxt?" heading02Text TransTxt?" heading07Text TransTxt?" headingAgingBucketDescription02 TransTxt?" headingAgingBucketDescription03 TransTxt?" headingAgingBucketDescription04 TransTxt?" headingAgingBucketDescription05 TransTxt?" headingAgingBucketDescription06 TransTxt?" headingAgingBucketDescription07 TransTxt?   ?     SRSReportDataSetAttribute    'CustAgingReportTmp'??
getCustAgingReportTmp?  CustAgingReportTmp? ?? 
getReverseAmountsAndHeadings   ? _agingBucket CustVendAgingBucketLookUp?? 
_direction ForwardBackwardPrinting??  boolean??? 
	heading01?  TransTxt??? 

heading011?  	TransDate??? 
	heading02?  	TransDate??? 

heading021?  	TransDate??? 
heading02Text?  TransTxt??? 
	heading03?  	TransDate??? 

heading031?  	TransDate??? 
	heading04?  	TransDate??? 

heading041?  	TransDate??? 
	heading05?  	TransDate??? 

heading051?  	TransDate??? 
	heading06?  	TransDate??? 

heading061?  	TransDate??? 
	heading07?  	TransDate??? 

heading071?  	TransDate??? 
heading07Text?  TransTxt??? 
headingAgingBucketDescription02?  TransTxt??? 
headingAgingBucketDescription03?  TransTxt??? 
headingAgingBucketDescription04?  TransTxt??? 
headingAgingBucketDescription05?  TransTxt??? 
headingAgingBucketDescription06?  TransTxt??? 
headingAgingBucketDescription07?  TransTxt??? 
headingDate?  	ColumnTxt??? 
initHeadingValues?  ??? 
insertCustAgingReportTmp   ? _reverseAmountsAndHeadings boolean??  CustAgingReportTmp? ?? 
parmUseDefaultTransactionOnly   ? useDefaultTransOnly_useDefaultTransOnly boolean??  boolean? ?? 
processReport?  ? ?? 
setCustAgingReportTmp?  ??? 
setCustAgingReportTmpInReverse?  ??RADCustAgingReportDPV2?? !     ExtensionOf        	ProjTable? ? ? tablestr??S[ExtensionOf(tablestr(ProjTable))]
public final class SIGProjTable_Extension
{
}   ? 
validateWrite   ? _calledFromStatus boolean??  boolean? ?? 
displayOriginalBudget?  Amount? ?? 
displayCommittedRevisionsTotal?  Amount? ?? 
 displayUncommittedRevisionsTotal?  Amount? ?? 
displayBudgetLineTotal?  Amount? ?SIGProjTable_Extension?? !     ExtensionOf        ProjInvoiceControl? General? ? formDataSourceStr??v[ExtensionOf(formDataSourceStr(ProjInvoiceControl,General))]
public final class SIGProjInvoiceControl_Extension
{
}   ? 
displayContractAmount?  Amount? ?? 
displayApprovedBudget?  Amount? ?SIGProjInvoiceControl_Extension?? !     ExtensionOf        TSTimesheetTable? ? ? tablestr??_[ExtensionOf(tablestr(TSTimesheetTable))]
Public final class SIGTimeSheetTable_Extension
{
}   ? 
	initValue?  ? ?SIGTimeSheetTable_Extension?? !     ExtensionOf        PSAProjInvoiceTmp? ? ? tableStr??e[ExtensionOf(tableStr(PSAProjInvoiceTmp))]
public final class SIGPSAProjInvoiceTmp_Extension
{

}   ? 
insert?  ? ?? 
calcTotalBudgetLine   ? _projId ProjId??  ProjBudgetLine? ?SIGPSAProjInvoiceTmp_Extension?? !     ExtensionOf        ChequeDP? ? ? classStr??Q[ExtensionOf(classStr(ChequeDP))]
public final class SIGChequeDP_Extension
{
}   ? 
populateChequeTmp?  ? ?SIGChequeDP_Extension?? ! ?class SIGCreditCardTransDeleteBatch extends RunBaseBatch
{
    DialogField     fieldDisplayMessage;
    DialogField     dlgFromDate,dlgToDate;
    FromDate        fromDate;
    ToDate          toDate;
}RunBaseBatch   " fieldDisplayMessage DialogField?" dlgFromDate DialogField?" 	dlgToDate DialogField?" fromDate FromDate?" toDate ToDate?   ? 	
	construct?  SIGCreditCardTransDeleteBatch? ?? 
dialog?  Object? ?? 
getFromDialog?  boolean? ?? 
run?  ? ?? 	
main   ? _args Args??  ? ?SIGCreditCardTransDeleteBatch?? ! ?class RADEmployeeTSAndUtilizationUIBuilder extends SrsReportDataContractUIBuilder
{
    RADEmployeeTSAndUtilizationContract   rdpContract;
    // PayrollPayStatementReportController ctrl;
    FormBuildComboBoxControl            cmbBuildPayPeriod;
    FormComboBoxControl                 cmbPayPeriod;
    DialogField                         dlgFldPayCycle;
    DialogField                         dlgFldPayPeriod;
    //  DialogField                         dlgFldDisbursement;
    container                           payPeriodList;

    #DEFINE.PayPeriodListControl('PayPeriodListControl')
    /// <summary>
    ///     Add customizations for controls created for contract parameter in report dialog.
    /// </summary>

}SrsReportDataContractUIBuilder   " rdpContract #RADEmployeeTSAndUtilizationContract?" cmbBuildPayPeriod FormBuildComboBoxControl?" cmbPayPeriod FormComboBoxControl?" dlgFldPayCycle DialogField?" dlgFldPayPeriod DialogField?" payPeriodList  ?   ? 
build?  ? ?? 
getFromDialog?  ? ?? 
initPayPeriods?  ??? 
modified   ? _control FormReferenceGroupControl??  boolean? ?? 
postRun?  ? ?? 
setLastPayPeriod?  ??$RADEmployeeTSAndUtilizationUIBuilder?? ! ?class RADPayChequeUIBuilder extends SrsReportDataContractUIBuilder
{
    RADPayChequeContract   rdpContract;
   // PayrollPayStatementReportController ctrl;
    FormBuildComboBoxControl            cmbBuildPayPeriod;
    FormComboBoxControl                 cmbPayPeriod;
    DialogField                         dlgFldPayCycle;
    DialogField                         dlgFldPayPeriod;
  //  DialogField                         dlgFldDisbursement;
    container                           payPeriodList;

    #DEFINE.PayPeriodListControl('PayPeriodListControl')
    /// <summary>
    ///     Add customizations for controls created for contract parameter in report dialog.
    /// </summary>

}SrsReportDataContractUIBuilder   " rdpContract RADPayChequeContract?" cmbBuildPayPeriod FormBuildComboBoxControl?" cmbPayPeriod FormComboBoxControl?" dlgFldPayCycle DialogField?" dlgFldPayPeriod DialogField?" payPeriodList  ?   ? 
build?  ? ?? 
getFromDialog?  ? ?? 
initPayPeriods?  ??? 
modified   ? _control FormReferenceGroupControl??  boolean? ?? 
postRun?  ? ?? 
setLastPayPeriod?  ??RADPayChequeUIBuilder?? !     ExtensionOf        ProjPostTransView? ? ? viewStr??b[ExtensionOf(viewStr(ProjPostTransView))]
final public class SIGProjPostTransView_Extension
{
}   ? 	

intComment?   ? ?? 	

extComment?   ? ?? 
acitivityText?   ? ?? 
businessUnitSIG?   ? ?? 
costCenterSIG?   ? ?SIGProjPostTransView_Extension?? !  class SIGEmployeeTimesheet
{
}   ? 	
main   ? _args Args??  ? ?SIGEmployeeTimesheet?? !     SrsReportParameterAttribute        #RADEmployeeTSAndUtilizationContract? ? ? classstr???[SrsReportParameterAttribute(classstr(RADEmployeeTSAndUtilizationContract))]
class RADEmployeeTSAndUtilizationDP extends SRSReportDataProviderBase
{

    //TableBuffer Decleration
    RADEmployeeTSAndUtilizationTmp      employeeTSAndUtilizationTmp;
    StartDate                           startDate,periodStartDate,parmStartDate;
    EndDate                             endDate,periodEndDate,parmEndDate;
    RADPayCheckUtilizationTmp           payCheckTmp;

}SRSReportDataProviderBase   " employeeTSAndUtilizationTmp RADEmployeeTSAndUtilizationTmp?" 	startDate 	StartDate?" periodStartDate 	StartDate?" parmStartDate 	StartDate?" endDate EndDate?" periodEndDate EndDate?" parmEndDate EndDate?" payCheckTmp RADPayCheckUtilizationTmp?   ?     SrsReportDataSetAttribute     'RADEmployeeTSAndUtilizationTmp'??
!getRADEmployeeTSAndUtilizationTmp?  RADEmployeeTSAndUtilizationTmp? ??     SysEntryPointAttribute?
processReport?  ? ?RADEmployeeTSAndUtilizationDP?? !     DataContractAttribute? 'SysOperationContractProcessingAttribute        RADPayChequeWeeklyUIBuilder? ? ? classStr?     &CreateSeparateUIBuilderForEachContract?	 &SysOperationDataContractProcessingMode???/// <summary>
///    The <c>PayrollPayStatementReportContract</c> class is the Data Contract class for the <c>PayrollPayStatementReport</c>
///    SSRS report.
/// </summary>
/// <remarks>
///    This is the Data Contract class for the the <c>PayrollPayStatementReport</c> SSRS Report.
/// </remarks>

[
    DataContractAttribute,
    SysOperationContractProcessingAttribute(classStr(RADPayChequeWeeklyUIBuilder), SysOperationDataContractProcessingMode::CreateSeparateUIBuilderForEachContract)
]
public class RADPayChequeWeeklyContract
{
    #DEFINE.PayCycle("PayCycle")
    #DEFINE.PayPeriod("PayPeriod")

    RADPayrollPayCycleWeeklyRecId   payrollPayCycleRecId;
    PayrollPayPeriodRecId           payrollPayPeriodRecId;
    
}   " payrollPayCycleRecId RADPayrollPayCycleWeeklyRecId?" payrollPayPeriodRecId PayrollPayPeriodRecId?   ?     DataMemberAttribute    
"PayCycle"?? SysOperationLabelAttribute        @Payroll:PayCycle1? ? ? 
literalStr?? SysOperationHelpTextAttribute        @SYS4090106? ? ? 
literalStr?? !SysOperationDisplayOrderAttribute    "0"??
parmPayCycle   ? payrollPayCycleRecId_payrollPayCycleRecId RADPayrollPayCycleWeeklyRecId??  RADPayrollPayCycleWeeklyRecId? ??     DataMemberAttribute    "PayPeriod"?? SysOperationLabelAttribute        @Payroll:PayPeriod? ? ? 
literalStr?? SysOperationHelpTextAttribute        @SYS4090107? ? ? 
literalStr?? !SysOperationDisplayOrderAttribute    "1"??
parmPayPeriod   ? payrollPayPeriodRecId_payrollPayPeriodRecId PayrollPayPeriodRecId??  PayrollPayPeriodRecId? ?RADPayChequeWeeklyContract?? !     SRSReportQueryAttribute        CustAgingReport? ? ? queryStr?? SRSReportParameterAttribute        CustAgingReportContract? ? ? classStr???/// <summary>
/// The <c>CustAgingReportDP</c> class declares the variables, tables, enumeration types, and so on
/// that are used in the <c>CustAgingReport</c> report.
/// </summary>
/// <remarks>
/// In Microsoft Dynamics AX 2012 R2 this class was changed to derive from the
/// <c>SRSReportDataProviderPreProcessTempDB</c> class instead of the <c>SRSReportDataProviderPreProcess</c>
/// class to improve performance. See <see cref="http://go.microsoft.com/fwlink/?LinkId=335910" />
/// for more information.
/// </remarks>
[
    SRSReportQueryAttribute(queryStr(CustAgingReport)),
    SRSReportParameterAttribute(classStr(CustAgingReportContract))
]
public class RADCustAgingReportDPV1 extends SRSReportDataProviderPreProcessTempDB
{
    CustAgingReportTmp custAgingReportTmp;
    CustTmpAccountSum tmpAccountSum;

    CustTable                       CustTable;
    DimensionAttributeValueSet      DimensionAttributeValueSet;
    DimensionAttributeValueSetItem  DimensionAttributeValueSetItem;
    DimensionAttributeValue         DimensionAttributeValue;
    DimensionAttribute              DimensionAttribute;
    OMOperatingUnit                 operatingUnit;
    DimensionFinancialTag           dimfintag;
    Name                            attributeName,attributeName2;

    CustVendBalanceList custVendBalanceList;
    CustAgingReportContract contract;

    ColumnTxt headingDate;
    TransDate heading011;
    TransDate heading02;
    TransDate heading021;
    TransDate heading03;
    TransDate heading031;
    TransDate heading04;
    TransDate heading041;
    TransDate heading05;
    TransDate heading051;
    TransDate heading06;
    TransDate heading061;
    TransDate heading07;
    TransDate heading071;

    TransTxt heading01;
    TransTxt heading02Text;
    TransTxt heading07Text;
    TransTxt headingAgingBucketDescription02;
    TransTxt headingAgingBucketDescription03;
    TransTxt headingAgingBucketDescription04;
    TransTxt headingAgingBucketDescription05;
    TransTxt headingAgingBucketDescription06;
    TransTxt headingAgingBucketDescription07;

    #define.emptyString(' ')
}
%SRSReportDataProviderPreProcessTempDB$   " custAgingReportTmp CustAgingReportTmp?" tmpAccountSum CustTmpAccountSum?" 	CustTable 	CustTable?" DimensionAttributeValueSet DimensionAttributeValueSet?" DimensionAttributeValueSetItem DimensionAttributeValueSetItem?" DimensionAttributeValue DimensionAttributeValue?" DimensionAttribute DimensionAttribute?" operatingUnit OMOperatingUnit?" 	dimfintag DimensionFinancialTag?" attributeName Name?" attributeName2 Name?" custVendBalanceList CustVendBalanceList?" contract CustAgingReportContract?" headingDate 	ColumnTxt?" 
heading011 	TransDate?" 	heading02 	TransDate?" 
heading021 	TransDate?" 	heading03 	TransDate?" 
heading031 	TransDate?" 	heading04 	TransDate?" 
heading041 	TransDate?" 	heading05 	TransDate?" 
heading051 	TransDate?" 	heading06 	TransDate?" 
heading061 	TransDate?" 	heading07 	TransDate?" 
heading071 	TransDate?" 	heading01 TransTxt?" heading02Text TransTxt?" heading07Text TransTxt?" headingAgingBucketDescription02 TransTxt?" headingAgingBucketDescription03 TransTxt?" headingAgingBucketDescription04 TransTxt?" headingAgingBucketDescription05 TransTxt?" headingAgingBucketDescription06 TransTxt?" headingAgingBucketDescription07 TransTxt?   ?     SRSReportDataSetAttribute    'CustAgingReportTmp'??
getCustAgingReportTmp?  CustAgingReportTmp? ?? 
getReverseAmountsAndHeadings   ? _agingBucket CustVendAgingBucketLookUp?? 
_direction ForwardBackwardPrinting??  boolean??? 
	heading01?  TransTxt??? 

heading011?  	TransDate??? 
	heading02?  	TransDate??? 

heading021?  	TransDate??? 
heading02Text?  TransTxt??? 
	heading03?  	TransDate??? 

heading031?  	TransDate??? 
	heading04?  	TransDate??? 

heading041?  	TransDate??? 
	heading05?  	TransDate??? 

heading051?  	TransDate??? 
	heading06?  	TransDate??? 

heading061?  	TransDate??? 
	heading07?  	TransDate??? 

heading071?  	TransDate??? 
heading07Text?  TransTxt??? 
headingAgingBucketDescription02?  TransTxt??? 
headingAgingBucketDescription03?  TransTxt??? 
headingAgingBucketDescription04?  TransTxt??? 
headingAgingBucketDescription05?  TransTxt??? 
headingAgingBucketDescription06?  TransTxt??? 
headingAgingBucketDescription07?  TransTxt??? 
headingDate?  	ColumnTxt??? 
initHeadingValues?  ??? 
insertCustAgingReportTmp   ? _reverseAmountsAndHeadings boolean??  CustAgingReportTmp? ?? 
parmUseDefaultTransactionOnly   ? useDefaultTransOnly_useDefaultTransOnly boolean??  boolean? ?? 
processReport?  ? ?? 
setCustAgingReportTmp?  ??? 
setCustAgingReportTmpInReverse?  ??RADCustAgingReportDPV1?? !     ExtensionOf        	ChequeTmp? ? ? tablestr??U[ExtensionOf(tablestr(ChequeTmp))]
public final class SIGChequeTmp_Extension
{

}   ? 
insert?  ? ?SIGChequeTmp_Extension?? !     SRSReportParameterAttribute        RADCustInvAmountYearContract? ? ? classStr?? SRSReportQueryAttribute    'SIGInvoiceAmountByYear'???/// <summary>
/// The <c>CustInvoiceVolumeDP</c> class supports the <c>RADCustInvAmountYear</c>Microsoft SQL Server
/// Reporting Services report.
/// </summary>
/// <remarks>
/// Declares the variables, tables, enumeration values, macros, and so on that can be used for the
/// <c>RADCustInvAmountYear</c>Reporting Services report.
/// </remarks>
[
    SRSReportParameterAttribute(classStr(RADCustInvAmountYearContract)),
    SRSReportQueryAttribute('SIGInvoiceAmountByYear')

]
public class RADCustInvAmountYearDP extends SRSReportDataProviderBase
{

    CustTable                   custTable;
    RADCustInvAmountYearTmp     custInvAmountYearTmp;
    
    TransDate   fromDate;
    TransDate   toDate;
    AmountMST   minAmount;
    String30    businessUnit,costCenter;
}SRSReportDataProviderBase   " 	custTable 	CustTable?" custInvAmountYearTmp RADCustInvAmountYearTmp?" fromDate 	TransDate?" toDate 	TransDate?" 	minAmount 	AmountMST?" businessUnit String30?" 
costCenter String30?   ? 
	dateRange?   ? ??     SRSReportDataSetAttribute        RADCustInvAmountYearTmp? ? ? tablestr??
getRADCustInvAmountYearTmp?  RADCustInvAmountYearTmp? ?? 
processReport?  ? ?? 
getDimensionDisplayValue   ? defaultDimension RecId??  ? ?RADCustInvAmountYearDP?? !     SrsReportParameterAttribute        ProjRepContract? ? ? classStr???[SrsReportParameterAttribute(classStr(ProjRepContract))]
class ProjreportDP extends SRSReportDataProviderBase
{
    ProjRepTmpTable  ProjReptmp;


}SRSReportDataProviderBase   " 
ProjReptmp ProjRepTmpTable?   ?     SrsReportDataSetAttribute        ProjRepTmpTable? ? ? tableStr??
getprojReptmpTable?  ProjRepTmpTable? ?? 
processReport?  ? ?ProjreportDP?? !     SrsReportParameterAttribute        RADPayChequeWeeklyContract? ? ? classstr???[SrsReportParameterAttribute(classstr(RADPayChequeWeeklyContract))]
class RADPayrollChequeWeeklyDP extends SRSReportDataProviderBase
{
    RADPayCheckTmp  payCheckTmp,payCheckTmpDetails;
    StartDate           startDate,periodStartDate;
    EndDate             endDate,periodEndDate;

}SRSReportDataProviderBase   " payCheckTmp RADPayCheckTmp?" payCheckTmpDetails RADPayCheckTmp?" 	startDate 	StartDate?" periodStartDate 	StartDate?" endDate EndDate?" periodEndDate EndDate?   ?     SrsReportDataSetAttribute        RADPayCheckTmp? ? ? tableStr??
getPayCheckTmp?  RADPayCheckTmp? ?? 
processReport?  ? ?RADPayrollChequeWeeklyDP?? !     SRSReportQueryAttribute        CustAgingReport? ? ? queryStr?? SRSReportParameterAttribute        CustAgingReportContract? ? ? classStr???/// <summary>
/// The <c>CustAgingReportDP</c> class declares the variables, tables, enumeration types, and so on
/// that are used in the <c>CustAgingReport</c> report.
/// </summary>
/// <remarks>
/// In Microsoft Dynamics AX 2012 R2 this class was changed to derive from the
/// <c>SRSReportDataProviderPreProcessTempDB</c> class instead of the <c>SRSReportDataProviderPreProcess</c>
/// class to improve performance. See <see cref="http://go.microsoft.com/fwlink/?LinkId=335910" />
/// for more information.
/// </remarks>
[
    SRSReportQueryAttribute(queryStr(CustAgingReport)),
    SRSReportParameterAttribute(classStr(CustAgingReportContract))
]
public class CustAgingReportDPCopy extends SRSReportDataProviderPreProcessTempDB
{
    CustAgingReportTmp custAgingReportTmp;
    CustTmpAccountSum tmpAccountSum;
    
    CustTable                       CustTable;
    DimensionAttributeValueSet      DimensionAttributeValueSet;
    DimensionAttributeValueSetItem  DimensionAttributeValueSetItem;
    DimensionAttributeValue         DimensionAttributeValue;
    DimensionAttribute              DimensionAttribute;
    OMOperatingUnit                 operatingUnit;
    DimensionFinancialTag           dimfintag;
    Name                            attributeName,attributeName2;

    CustVendBalanceList custVendBalanceList;
    CustAgingReportContract contract;

    ColumnTxt headingDate;
    TransDate heading011;
    TransDate heading02;
    TransDate heading021;
    TransDate heading03;
    TransDate heading031;
    TransDate heading04;
    TransDate heading041;
    TransDate heading05;
    TransDate heading051;
    TransDate heading06;
    TransDate heading061;
    TransDate heading07;
    TransDate heading071;

    TransTxt heading01;
    TransTxt heading02Text;
    TransTxt heading07Text;
    TransTxt headingAgingBucketDescription02;
    TransTxt headingAgingBucketDescription03;
    TransTxt headingAgingBucketDescription04;
    TransTxt headingAgingBucketDescription05;
    TransTxt headingAgingBucketDescription06;
    TransTxt headingAgingBucketDescription07;

    #define.emptyString(' ')
}%SRSReportDataProviderPreProcessTempDB$   " custAgingReportTmp CustAgingReportTmp?" tmpAccountSum CustTmpAccountSum?" 	CustTable 	CustTable?" DimensionAttributeValueSet DimensionAttributeValueSet?" DimensionAttributeValueSetItem DimensionAttributeValueSetItem?" DimensionAttributeValue DimensionAttributeValue?" DimensionAttribute DimensionAttribute?" operatingUnit OMOperatingUnit?" 	dimfintag DimensionFinancialTag?" attributeName Name?" attributeName2 Name?" custVendBalanceList CustVendBalanceList?" contract CustAgingReportContract?" headingDate 	ColumnTxt?" 
heading011 	TransDate?" 	heading02 	TransDate?" 
heading021 	TransDate?" 	heading03 	TransDate?" 
heading031 	TransDate?" 	heading04 	TransDate?" 
heading041 	TransDate?" 	heading05 	TransDate?" 
heading051 	TransDate?" 	heading06 	TransDate?" 
heading061 	TransDate?" 	heading07 	TransDate?" 
heading071 	TransDate?" 	heading01 TransTxt?" heading02Text TransTxt?" heading07Text TransTxt?" headingAgingBucketDescription02 TransTxt?" headingAgingBucketDescription03 TransTxt?" headingAgingBucketDescription04 TransTxt?" headingAgingBucketDescription05 TransTxt?" headingAgingBucketDescription06 TransTxt?" headingAgingBucketDescription07 TransTxt?   ?     SRSReportDataSetAttribute    'CustAgingReportTmp'??
getCustAgingReportTmp?  CustAgingReportTmp? ?? 
getReverseAmountsAndHeadings   ? _agingBucket CustVendAgingBucketLookUp?? 
_direction ForwardBackwardPrinting??  boolean??? 
	heading01?  TransTxt??? 

heading011?  	TransDate??? 
	heading02?  	TransDate??? 

heading021?  	TransDate??? 
heading02Text?  TransTxt??? 
	heading03?  	TransDate??? 

heading031?  	TransDate??? 
	heading04?  	TransDate??? 

heading041?  	TransDate??? 
	heading05?  	TransDate??? 

heading051?  	TransDate??? 
	heading06?  	TransDate??? 

heading061?  	TransDate??? 
	heading07?  	TransDate??? 

heading071?  	TransDate??? 
heading07Text?  TransTxt??? 
headingAgingBucketDescription02?  TransTxt??? 
headingAgingBucketDescription03?  TransTxt??? 
headingAgingBucketDescription04?  TransTxt??? 
headingAgingBucketDescription05?  TransTxt??? 
headingAgingBucketDescription06?  TransTxt??? 
headingAgingBucketDescription07?  TransTxt??? 
headingDate?  	ColumnTxt??? 
initHeadingValues?  ??? 
insertCustAgingReportTmp   ? _reverseAmountsAndHeadings boolean??  CustAgingReportTmp? ?? 
parmUseDefaultTransactionOnly   ? useDefaultTransOnly_useDefaultTransOnly boolean??  boolean? ?? 
processReport?  ? ?? 
setCustAgingReportTmp?  ??? 
setCustAgingReportTmpInReverse?  ??CustAgingReportDPCopy?? ! $class SIGProjectBudgetApproval
{
}   ? 	
main   ? _args Args??  ? ?SIGProjectBudgetApproval?? ! ?/// <summary>
///    The <c>CustAgingReportController</c> class is the controller class for the <c>CustAgingReport</c>
///    SRS report.
/// </summary>
public class RADCustAgingReportControllerV2 extends SrsReportRunController
{
}SrsReportRunController   ? 
getReportName   ? 	_contract CustAgingReportContract??   ? ?? 
prePromptModifyContract?  ? ?? 
preRunModifyContract?  ? ?? 
preRunValidate?   ? ?? 
queryChanged   ? _key  ?? _query Query??  ? ?? 
	setRanges   ? _query Query?? 	_contract CustAgingReportContract??  ? ?? 	
main   ? _args Args??  ? ?RADCustAgingReportControllerV2?? ! >class SIGProjectBudgetApprovalBatch extends RunBaseBatch
{
}RunBaseBatch   ? 	
	construct?  SIGProjectBudgetApprovalBatch? ?? 
run?  ? ?? 	
main   ? _args Args??  ? ?SIGProjectBudgetApprovalBatch?? !     ExtensionOf        PSAProjProposalProj? ? ? tablestr??g[ExtensionOf(tablestr(PSAProjProposalProj))]
public final class SIGPSAProjProposalProj_Extension
{
}   ? 
insert?  ? ? SIGPSAProjProposalProj_Extension?