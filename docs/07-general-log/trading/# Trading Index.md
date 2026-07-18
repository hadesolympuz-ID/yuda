```dataview
TABLE
id,
title,
status,
date
FROM "docs/07-general-log/trading"
WHERE file.name != "Trading Index"
SORT id ASC
```