```dataview
TABLE WITHOUT ID
	file.link AS "Name",
	description AS "Description",
	leader AS "Leader",
	location AS "Location"
FROM "Organizations"
WHERE file.name != "Organizations"
```
