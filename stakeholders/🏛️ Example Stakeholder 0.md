---
location: Berlin
website: foo.de
email: example@foo.de
---
tags:: [[📝 Stakeholder MOC]]

# 🏛️ Example Stakeholder 0


---
## Description

---
## People
```dataview
TABLE file.cday as Created, summary AS "Summary"
FROM "stakeholders" where contains(file.outlinks, [[TKTK]])
SORT file.cday DESC
```