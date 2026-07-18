```dataview
TABLE
id,
title,
element,
category,
sub,
parent,
source,
status,
date,
tags
FROM "docs/07-general-log/trading"
WHERE file.name != "Trading Index"
SORT id ASC
```