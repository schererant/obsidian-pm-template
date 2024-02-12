---
stakeholder: 
location: 
position: 
role: 
email: 
website: 
aliases: 
expertise: 
projects: 
teams:
---
Peotags:: [[People MOC]]

# <% tp.file.title %>
<% await tp.file.move("/people/" + tp.file.title) %>

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
FROM "tasks" where contains(file.outlinks, [[<% tp.file.title %>]])
SORT file.cday DESC
```
## Meetings
```dataview
TABLE file.cday as Created, summary AS "Summary"
FROM "meetings" where contains(file.outlinks, [[<% tp.file.title %>]])
SORT file.cday DESC
```
