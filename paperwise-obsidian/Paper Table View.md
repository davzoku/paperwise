
```dataview
TABLE file.name as name, shortTitle, year, isCodeAvailable
WHERE contains(file.tags, "#paper")
SORT shortTitle asc
```
