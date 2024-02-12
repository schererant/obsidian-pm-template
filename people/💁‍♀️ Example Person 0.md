---
stakeholder: "[[🏛️ Example Stakeholder 0]]"
location: Berlin
position: CEO
role: Management
email: example@foo.de
website: foo.de
aliases:
  - staky0
expertise: 
projects: 
teams:
---
tags:: [[People MOC]]

# 💁‍♀️ Example Person 0


---
## To Discuss
- 

---
## Notes
- 

---
## Tasks
```dataview
TABLE file.cday as Created, summary AS "Summary"
FROM "tasks" where contains(file.outlinks, [[TKTK]])
SORT file.cday DESC
```
## Meetings
```dataview
TABLE file.cday as Created, summary AS "Summary"
FROM "meetings" where contains(file.outlinks, [[TKTK]])
SORT file.cday DESC
```
