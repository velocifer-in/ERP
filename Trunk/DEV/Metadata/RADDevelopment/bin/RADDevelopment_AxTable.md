
   ProjRepTmpTable?tg5    l  RADCustInvAmountYearTmp?tg5l    RADPayCheckUtilizationTmp?tg5?  -  RADPayCheckUtilizationTransTmp?tg5?  7   RADPayCheckUtilizationDetailsTmp?tg5?	  8  RADEmployeeTSAndUtilizationTmp?tg5!  ?  RADPayCheckWeeklyTmp?tg5  o  RADPayCheckDetailsWeeklyTmp?tg5u  }  RADPayCheckTmp?tg5?  n  RADPayCheckDetailsTmp?tg5`  |  ? ?3public class ProjRepTmpTable extends common
{
}
   ?
AutoReport??
AutoLookup?? AutoIdentification??AutoSummary??
AutoBrowse?
   ?	ProjectID??ProjectName   ??OriginalBudget??SalesManager   ??RevisionAmount??
Created_By   ??CreatedDate??
Dimensions2   ??TotalBudget??DimBU2   ?!ProjRepTmpTable9  ?1 ?? ?;public class RADCustInvAmountYearTmp extends common
{
}
   ?
AutoReport??
AutoLookup?? AutoIdentification??AutoSummary??
AutoBrowse?   ?  Customer Content 	CustAccount 
AccountNum??    "Customer ContentAmountMSTDebCredInvoiceAmount??    Customer Content	TransDate 	TransDate??Year??
Month name	MonthName??MonthMonthNum??		CompanyIdDataarea??BusinessUnit2   ??
CostCenter2   ??BitmapCompnayLogo??	CompanyNameCompanyName?!RADCustInvAmountYearTmp9  ?1 ?? ?=public class RADPayCheckUtilizationTmp extends common
{
}
   ?
AutoReport??
AutoLookup?? AutoIdentification??AutoSummary??
AutoBrowse?   ?	String10Dataarea??
ResourceIdResource??	String30
CategoryId??	ResourceNameResourceName??	HcmPersonnelNumberIdHcmPersonnelNumberId??	StartDate	StartDate??EndDateEndDate??
RADPayCalc
RADPayCalc??Customer Content	JmgProfileId 	@SYS38567 DefaultProfileId??RADEmployeeTypeRADEmployeeType??NoYes	NoYesIdLeave and absence projectRADLeaveAndAbsence??Customer Content 	ProjLinePropertyId LinePropertyId??  Customer Content 	TSTimesheetNbr TimesheetNbr??HoursHours??Hours
TotalHours??  Customer Content	ProjTransIdBaseTransId?!RADPayCheckUtilizationTmp8 (  9  ?1 ?? ?Bpublic class RADPayCheckUtilizationTransTmp extends common
{
}
   ?
AutoReport??
AutoLookup?? AutoIdentification??AutoSummary??
AutoBrowse?   ?	String10Dataarea??
ResourceIdResource??	String30
CategoryId??	ResourceNameResourceName??	HcmPersonnelNumberIdHcmPersonnelNumberId??	StartDate	StartDate??EndDateEndDate??
RADPayCalc
RADPayCalc??Customer Content	JmgProfileId 	@SYS38567 DefaultProfileId??RADEmployeeTypeRADEmployeeType??NoYes	NoYesIdLeave and absence projectRADLeaveAndAbsence??Customer Content 	ProjLinePropertyId LinePropertyId??  Customer Content 	TSTimesheetNbr TimesheetNbr??HoursHours??Hours
TotalHours??  Customer Content	ProjTransIdBaseTransId?!RADPayCheckUtilizationTransTmp8 (  9  ?1 ?? ?Dpublic class RADPayCheckUtilizationDetailsTmp extends common
{
}
   ?
AutoReport??
AutoLookup?? AutoIdentification??AutoSummary??
AutoBrowse?   ?	String10Dataarea??
ResourceIdResource??	String30
CategoryId??	ResourceNameResourceName??	HcmPersonnelNumberIdHcmPersonnelNumberId??	StartDate	StartDate??EndDateEndDate??
RADPayCalc
RADPayCalc??Customer Content	JmgProfileId 	@SYS38567 DefaultProfileId??RADEmployeeTypeRADEmployeeType??NoYes	NoYesIdLeave and absence projectRADLeaveAndAbsence??Customer Content 	ProjLinePropertyId LinePropertyId??  Customer Content 	TSTimesheetNbr TimesheetNbr??Hours
TotalHours??  Customer Content	ProjTransIdBaseTransId??HoursHours?! RADPayCheckUtilizationDetailsTmp8 (  9  ??? ?@public class RADEmployeeTSAndUtilizationTmp extends common
{
}   ?
AutoReport??
AutoLookup?? AutoIdentification??AutoSummary??
AutoBrowse?   ?	HcmPersonnelNumberIdHcmPersonnelNumberId??	StartDate	StartDate??EndDateEndDate??	Name
Supervisor??	ResourceNameResourceName??QtyUtilizationExlHolPL??QtyUtilizationAllHours??QtyTotal??QtyRegular??QtyOTHours??QtyOTNonBillableHours??QtyBillableHours??QtyBilledHours??QtyNonBillableHours??QtyPersonalLeave??QtyHoliday??Qty
WithoutPay??QtyUtilBaseExlHolPL??QtyUtilBaseAllHours??	String30HourlySalaried?&Employee Timesheet and Utilization tmp!RADEmployeeTSAndUtilizationTmp9  ?1 ?? ?8public class RADPayCheckWeeklyTmp extends common
{
}
   ?
AutoReport??
AutoLookup?? AutoIdentification??AutoSummary??
AutoBrowse?   ?	String10Dataarea??
ResourceIdResource?? Hours??	String30
CategoryId??	ResourceNameResourceName??
TotalHours??	HcmPersonnelNumberIdHcmPersonnelNumberId??	StartDate	StartDate??EndDateEndDate??
RADPayCalc
RADPayCalc??Customer Content	JmgProfileId 	@SYS38567 DefaultProfileId??RADEmployeeTypeRADEmployeeType??NoYes	NoYesIdLeave and absence projectRADLeaveAndAbsence?!RADPayCheckWeeklyTmp8 (  9  ?1 ?? ??public class RADPayCheckDetailsWeeklyTmp extends common
{
}
   ?
AutoReport??
AutoLookup?? AutoIdentification??AutoSummary??
AutoBrowse?   ?	String10Dataarea??
ResourceIdResource?? Hours??	String30
CategoryId??	ResourceNameResourceName??
TotalHours??	HcmPersonnelNumberIdHcmPersonnelNumberId??	StartDate	StartDate??EndDateEndDate??
RADPayCalc
RADPayCalc??Customer Content	JmgProfileId 	@SYS38567 DefaultProfileId??RADEmployeeTypeRADEmployeeType??NoYes	NoYesIdLeave and absence projectRADLeaveAndAbsence?!RADPayCheckDetailsWeeklyTmp8 (  9  ?1 ?? ?2public class RADPayCheckTmp extends common
{
}
   ?
AutoReport??
AutoLookup?? AutoIdentification??AutoSummary??
AutoBrowse?   ?	String10Dataarea??
ResourceIdResource??	String30
CategoryId??	ResourceNameResourceName??	HcmPersonnelNumberIdHcmPersonnelNumberId??	StartDate	StartDate??EndDateEndDate??
RADPayCalc
RADPayCalc??Customer Content	JmgProfileId 	@SYS38567 DefaultProfileId??RADEmployeeTypeRADEmployeeType??NoYes	NoYesIdLeave and absence projectRADLeaveAndAbsence??HoursHours??Hours
TotalHours?!RADPayCheckTmp8 (  9  ?1 ?? ?9public class RADPayCheckDetailsTmp extends common
{
}
   ?
AutoReport??
AutoLookup?? AutoIdentification??AutoSummary??
AutoBrowse?   ?	String10Dataarea??
ResourceIdResource??	String30
CategoryId??	ResourceNameResourceName??	HcmPersonnelNumberIdHcmPersonnelNumberId??	StartDate	StartDate??EndDateEndDate??
RADPayCalc
RADPayCalc??Customer Content	JmgProfileId 	@SYS38567 DefaultProfileId??RADEmployeeTypeRADEmployeeType??NoYes	NoYesIdLeave and absence projectRADLeaveAndAbsence??HoursHours??Hours
TotalHours?!RADPayCheckDetailsTmp8 (  9  ?1 ?