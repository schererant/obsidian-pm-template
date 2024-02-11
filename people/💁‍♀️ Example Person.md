---
company: foo_company
location: foo_town
title: foo_ceo
email: foo@mail.com
website: foo.org
aliases:
  - foogirl
expertise: software
projects: project_0
teams: software, embedded
---
tags:: [[People MOC]]

# Example Person


---
## To Discuss
- Please rename yourself

---
## Notes
- wikipedia
- drinks coffee loudly

---
## Tasks
```dataview
TABLE file.cday as Created, summary AS "Summary"
FROM "tasks" where contains(file.outlinks, [[💁‍♀️ Example Person]])
SORT file.cday DESC
```
## Meetings
```dataview
TABLE file.cday as Created, summary AS "Summary"
FROM "meetings" where contains(file.outlinks, [[TKTK]])
SORT file.cday DESC
```
