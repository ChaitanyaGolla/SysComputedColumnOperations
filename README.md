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
