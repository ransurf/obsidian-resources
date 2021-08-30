tags:
Index: [[000 Index|Index]], [[My Inputs|Ideas]]
___
# ~ Projects
## Yearly Projects
> [[Yearly Reviews]]
```dataview
list
FROM #projects/yearly
WHERE file.name != "Project Template"
WHERE completed = null
SORT deadline desc
```
## Quarterly Projects
> [[Quarterly Reviews]]
```dataview
list
FROM #projects/quarterly
WHERE file.name != "Project Template"
WHERE completed = null
SORT deadline desc
```
## Monthly Projects
 > [[Monthly Reviews]]
```dataview
list
FROM #projects/monthly
WHERE file.name != "Project Template"
WHERE completed = null
SORT deadline desc
```
## Weekly Projects
> [[Weekly Reviews]]
```dataview
list
FROM #projects/weekly
WHERE file.name != "Project Template"
WHERE completed = null
SORT deadline desc
```
### Kanban Boards
- [[Youtube Kanban]]
## Dusty Projects
*These projects may have already bit the dust. I'm just keeping track of them here.*
```dataview
table completed
FROM #projects
WHERE file.name != "Project Template" AND completed != null
SORT completed desc
```
- [[Robotics 30 Capstone Project Proposal]]
___
# Backlinks
```dataview
list from [[~ Projects]] AND !outgoing([[~ Projects]]) AND !#projects
```
___