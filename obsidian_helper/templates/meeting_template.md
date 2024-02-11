---
date: <% tp.file.creation_date() %>
type: meeting
company: 
summary: This is a summary
---
tags: [[🗣 Meetings MOC]]
Date: [[<% tp.date.now("YYYY-MM-DD-dddd") %>]]
<% await tp.file.move("/meetings/" + tp.date.now("YYYY-MM-DD") + " " + tp.file.title) %>
# [[<% tp.date.now("YYYY-MM-DD") + " " + tp.file.title %>]]
___
**Attendees**: 
- 
___
## Agenda/Questions
- 

## Notes
-