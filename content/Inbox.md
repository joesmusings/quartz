---

---

```dataview 
table 

(date(today) - file.cday).day as "days alive" , (date(today) - file.mday).day as "since edited"
from "inbox"
sort file.mday desc
```
