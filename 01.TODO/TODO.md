
## TODOS
```dataview
LIST 
FROM ""
WHERE file.folder = "01.TODO"
SORT file.name DESC
```
----
## ISSUES

```dataview
table 
	dateformat(file.ctime, "DD HH:mm:ss") AS "Created"
FROM ""
WHERE file.folder = "01.TODO/ISSUE"
SORT file.ctime desc

```


