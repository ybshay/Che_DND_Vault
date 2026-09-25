---
title: Unique Notes
tags:
date created: Sunday, 21st June 2026, 8:49:15 pm
date modified: Friday, 25th September 2026, 4:38:49 pm
---
# Unique Notes
```dataview
TABLE WITHOUT ID
link(file.aliases[1]) AS Time, link(file.link, file.aliases[0]) AS Note
FROM #uniqueNote 
SORT file.ctime DESC
LIMIT 8
```
