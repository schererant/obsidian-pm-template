[[+Home]] %% tags:: #MOC %% 

# Meetings MOC
Meetings are timestamped events with other people, where information is exchanged and collected. Meeting notes are intrinsically ephemeral. They're stored in a separate Space than other Umami notes (`meetings`) and rarely reviewed. If there's information in a meeting that needs to be accessed later, it should be moved into a more evergreen note in the Umami folder. 

**Template:** [[meeting_template]]

```meta-bind-button
label: New Meeting
hidden: false
class: ""
tooltip: ""
id: ""
style: default
actions:
  - type: templaterCreateNote
    templateFile: obsidian_helper/templates/meeting_template.md
    folderPath: meetings
    fileName: TKTK
    openNote: true

```
## Meeting Notes

```dataview
TABLE file.cday as Created, summary
FROM "meetings" and -#MOC
SORT file.cday DESC
``