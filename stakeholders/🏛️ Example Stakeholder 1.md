---
location: Munich
website: bar.de
email: example@bar.de
---
tags:: [[📝 Stakeholder MOC]]

# 🏛️ Example Stakeholder 1


---
## Description

---
## People
```dataview
TABLE file.cday as Created, summary AS "Summary"
FROM "stakeholders" where contains(file.outlinks, [[TKTK]])
SORT file.cday DESC
```