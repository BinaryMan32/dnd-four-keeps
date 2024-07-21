```dataview
TABLE WITHOUT ID
	file.link AS "Name",
	owner AS "Owner",
	race AS "Race",
	class AS "Class",
	status AS "Status"
FROM "Characters"
WHERE file.name != "Characters"
SORT status, file.name 
```
