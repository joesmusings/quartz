---

---
``` dataview
table (date(today) - file.cday).day as "Days alive"
from "notes/references"
where status = "To Process"
sort file.cday asc

```
