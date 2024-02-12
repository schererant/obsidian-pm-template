---
location: 
website: 
email:
---
tags:: [[📝 Stakeholder MOC]]

# <% tp.file.title %>
<% await tp.file.move("/stakeholders/" + tp.file.title) %>

---
## Description

---
## People
```dataview
TABLE file.cday as Created, summary AS "Summary"
FROM "stakeholders" where contains(file.outlinks, [[<% tp.file.title %>]])
SORT file.cday DESC
```