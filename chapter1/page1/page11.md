### Plot Range

Files location:[http://192.168.18.60/Chelsea/GraphingTesting/tree/master/PlotRange](http://192.168.18.60/Chelsea/GraphingTesting/tree/master/PlotRange)

TestCase 1:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Select combination | 1 | One column | Fill row numbers | Plot correct |
|  |  | 2 | multiple columns | Fill row numbers | Plot correct |
|  |  | 3 | adjacent | Fill row numbers | Plot correct |
|  |  | 4 | non-adjacent | Fill row numbers | Plot correct |

TestCase 2:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 2 | Select combination | 1 | ranges in same columns | Fill row numbers | Plot disable |
|  |  | 2 | ranges in differnet columns | Fill row numbers | Plot Correct |
|  |  | 3 | ranges in diff worksheet of the same workbook | Fill row numbers | Plot disable |

TestCase 3:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 3 |  | 1 | Y with sampling intervals | Fill row numbers | Plot Correct |

TestCase 4:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 4 |  | 1 | Diff column headers with user defined parameters | Fill row numbers | Plot Correct |

TestCase 5:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 5 | try different kinds of column combinations | 1 | XYXY data | Fill row numbers | Plot Correct |
|  |  | 2 | XYYYY | Fill row numbers | Plot Correct |
|  |  | 3 | XYZXYZ | Fill row numbers | Plot Correct |

TestCase 6:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 6 |  | 1 | Error bar | Fill row numbers | Plot Correct |

TestCase 7:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 7 | For some special plot,we should use specific plot range | 1 | box chart | Fill row numbers | Plot correct |
|  |  | 2 | radar chart | Fill row numbers | Plot correct |
|  |  | 3 | polar plot | Fill row numbers | Plot correct |
|  |  | 4 | windrose plot | Fill row numbers | Plot correct |
|  |  | 5 | Pie chart | Fill row numbers | Plot correct |

TestCase 8:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 8 | Ignore hidden columns/rows | 1 | XYXY data | Fill row numbers | Plot Correct |
|  |  | 2 | XYYYY | Fill row numbers | Plot Correct |
|  |  |  |  |  |  |





