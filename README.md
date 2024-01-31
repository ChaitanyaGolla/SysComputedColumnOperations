# SysComputedColumnOperations
This project contains X++ code to show the usage of SysComputedColumn class method in Dynamics 365 for Finance and Operations.
1) Using a simple SQL query on a view using SysComputedColumn - View: DAXPurchAgreementDetails and method: getPOAmount
2) Using a complex SQL query on a view using SysComputedColumn - View: DAXPurchAgreementDetails and method: getPOInvAmount
3) Show the usage of getDateAdd method of SysComputedColumn - DataEntity: DAXCustHistoryTransEntity and method: computePrior30Days
4) Show the usage of getDateDiffWithFallbackToZero method of SysComputedColumn to view the difference between two dates - DataEntity: DAXCustHistoryTransEntity and method: computeColumnDateDiffToZero
5) Show the usage of or2 condition of SysComputedColumn - DataEntity: DAXCustHistoryTransEntity and method: computeColumnDateDiff
6) Show the usage of SysColumnDatePart(Year) of SysComputedColumn - DataEntity: DAXCustHistoryTransEntity and method: computePriorYear
7) Show the usage of codeDependentRelation expression of SysComputedColumn - DataEntity: DAXCustHistoryTransEntity and method: customerNumberComputedColumnDefinition
8) Show the usage of "Null" expression of SysComputedColumn - DataEntity: DAXCustHistoryTransEntity and method: computeColumnDateDiffNull
9) Show the usage of comparison expression list of SysComputedColumn - View: DAXCustVendExternalItem and method: computeColumnModuleType
10) Show the usage of cast operation of SysComputedColumn - View: DAXPurchAgreementDetails and method: computeCreatedDate
11) Show the usage of count method of SysComputedColumn - View: DAXCustomerTransCount  and method: computedTransCountStr
12) Show the usage of getDateDiff method of SysComputedColumn - DataEntity: DAXCustHistoryTransEntity  and method: computeColumnDateDiff
13) Show the usage of getCurrentUtcDate and getCurrentUtcDate methods of SysComputedColumn - DataEntity: DAXCustHistoryTransEntity  and method: computedCurrentDate and method: computedCurrentUtcDate respectively.
14) Show the usage of not equal expression of SysComputedColumn - View: DAXPurchAgreementDetails and method: computeDeliveryDate
15) Show the usage of compare expression of SysComputedColumn - View: DAXPurchAgreementDetails and method: computeDateofDelivery
16) Show the usage of SysComputedColumn with a if loop - Entity: DAXCustHistoryTransEntity and method: computedAmountDueStr 
17) Show the usage of SysComputedColumn with a if loop & and condition - Entity: DAXCustHistoryTransEntity and method: computeSelectiveCust
18) Show the usage of addList method of SysComputedColumn - View: DAXSalesInvoiceHeaders and method: computeTotalDiscountAmount
19) Show the usage of switch method of SysComputedColumn - View: DAXCustomerTrans and method: computedTransType
20) Show the usage of if condition and cast method of SysComputedColumn - View: DAXCustomerTrans and method: computeTransAmount
21) Show the usage of max method of SysComputedColumn - View: DAXCustomerTrans and method: computeMaxAmount
22) Show the usage of absolute method of SysComputedColumn - View: DAXCustomerTransMeasures and method: computeAbsValue
23) Show the usage of aggregate method "Sum" of SysComputedColumn - View: DAXCustomerTransMeasures and method: computeBalance
24) Using SyscomputedColumn to compare dates and display the max value - View: DAXPurchAgreementDetails and method: getMaxDate
