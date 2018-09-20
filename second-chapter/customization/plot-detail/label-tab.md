### Label Tab

Files location:[http://192.168.18.60/Chelsea/GraphingTesting/tree/master/PlotDetail](http://192.168.18.60/Chelsea/GraphingTesting/tree/master/PlotDetail)

TestCase 1:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Show at Specified Indices Only | 1 | Indices from dataset | Fill row numbers | Plot correct |
|  |  | 2 | Indices from space separated numbers. 0=last | Fill row numbers | Plot correct |
|  |  | 3 | Indices... editbox is empty, then no label should show | Fill row numbers | Plot correct |
|  |  |  | In Indices from dataset or space separated numbers edit box, you can also enter the syntax: \[book\]sheet!column like \[Multiple Peaks.dat\]Peak\_Centers1!A . If the index dataset is from same workbook, enter syntax like sheet!column like Peak\_Centers1!A, if in same sheet, just enter column, like A. | Fill row numbers | Plot correct |

TestCase 2:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
|  | Label From | 1 | Label From,select col\(B\) | Fill row numbers | Plot correct |

TestCase 3:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
|  |  | 1 | Numeric Display Format: .4 | Fill row numbers | Plot correct |



