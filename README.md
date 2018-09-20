# About GTA

It is an auto test system designed for graphing testing.

* Funcitonal test material design and make:

We pay close attention to "case point" , "classified type" , "case using data" and "expected results". Then make it into Ranorex scripts.

example:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
|  |  |  |  |  |  |

* Design graph:

![](/assets/gtade.png)

> * Base on : Go + Git + VMVare/PC

---

1. go url : [http://192.168.18.167:8153/go/pipelines\#!/](http://192.168.18.167:8153/go/pipelines#!/)
2. Material:[http://192.168.18.60/Chelsea/GraphingTesting/tree/master](http://192.168.18.60/Chelsea/GraphingTesting/tree/master)
3. Reference :[http://wikis/internal/index.php?title=Originlab%3AGraphing\_Testing](http://wikis/internal/index.php?title=Originlab%3AGraphing_Testing)
4. Control panel: [http://192.168.18.108/GTAControlPanel/](http://192.168.18.108/GTAControlPanel/)

Sqlite database design:

```
CREATE TABLE [report](
    [reportFile], 
    [caseName], 
    [caseTester], 
    [nodeName], 
    [shortNodeName], 
    [buildID], 
    [success], 
    [successPct], 
    [failedPct], 
    [failed], 
    [result], 
    [startTime] PRIMARY KEY, 
    [duration]);
```

Import sql:

process test data:

```
"INSERT INTO report (reportFile,caseName,caseTester,buildID,success,successPct,failed,result,startTime,duration) VALUES ('".$filestr."','".$str."','Chelsea','".$buildid."',".$success.",".$successPct.",".$failed.",'".$$result."','".$startTime."','".$duration."')"
UPDATE report set duration = strftime('%s',duration) - strftime('%s',startTime);
```

report presented:

```
 SELECT   * FROM report where buildID=(SELECT buildID FROM report ORDER BY buildID DESC LIMIT 1) GROUP BY caseName ORDER BY successPct DESC;
```



