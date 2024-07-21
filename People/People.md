```dataview
TABLE WITHOUT ID
	file.link AS "Name",
	description AS "Description",
	location AS "Location",
	status AS "Status"
FROM "People"
WHERE file.name != "People"
```
