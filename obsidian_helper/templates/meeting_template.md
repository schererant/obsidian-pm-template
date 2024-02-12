---
date: <% tp.file.creation_date() %>
type: meeting
company: 
summary: This is a summary
people: 
projects:
---
tags: [[🗣 Meetings MOC]]
Date: [[<% tp.date.now("YYYY-MM-DD-dddd") %>]]
 <%* let title = await tp.system.prompt("Meeting name: ") %>
<% 
await tp.file.move("/meetings/" + tp.file.creation_date("YYYY-MM-DD_HH.mm") + " " + title) %>
# [[<% title %>]]
___
## Agenda/Questions


## Notes
