### Line Graph

Files location:[http://192.168.18.60/Chelsea/GraphingTesting/tree/master/LineGraph](http://192.168.18.60/Chelsea/GraphingTesting/tree/master/LineGraph)

TestCase 1:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | line width,color | 1 | Try different line width | Fill row numbers | Plot correct |
|  |  | 2 | Try different color | Fill row numbers | Plot correct |

TestCase 2:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 2 | Connect type | 1 | Bezier | Fill row numbers | Plot correct |
|  |  | 2 | Modified Bezier | Fill row numbers | Plot correct |
|  |  | 3 | Akima | Fill row numbers | Plot correct |
|  |  | 4 | B-Spline | Fill row numbers | Plot correct |
|  |  | 5 | Spline | Fill row numbers | Plot correct |

TestCase 3:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 3 | Connect type | 1 | Color: Set as Increment | Fill row numbers | Plot correct |
|  |  | 2 | color mapping | Fill row numbers | Plot correct |
|  |  | 3 | color indexing | Fill row numbers | Plot correct |
|  |  | 4 | Set as Custom and right click to set Custom color | Fill row numbers | Plot correct |

TestCase 6:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 6 | Fill Area Under Curve: Check diff settings | 1 | Span Vertically broken by missing values | Fill row numbers | Plot correct |
|  |  | 2 | Fill to next data plot - One Color/Above below colors | Fill row numbers | Plot correct |
|  |  | 3 | Try to fill to next plot draws when there is missing values or axis break | Fill row numbers | Plot correct |
|  |  | 4 | Try missing value case for normal, slideline only, slideline and base case, etc. \(and also change line color to increment or colormap to test\) | Fill row numbers | Plot correct |



