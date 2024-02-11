[[+Home]] %% tags:: #MOC %% 

# Meetings MOC
Meetings are timestamped events with other people, where information is exchanged and collected. Meeting notes are intrinsically ephemeral. They're stored in a separate Space than other Umami notes (`people`) and rarely reviewed. If there's information in a meeting that needs to be accessed later, it should be moved into a more evergreen note in the Umami folder. 

**Template:** [[people_template]]

```meta-bind-button
label: New Person
hidden: false
class: ""
tooltip: ""
id: ""
style: default
actions:
  - type: templaterCreateNote
    templateFile: obsidian_helper/templates/people_template.md
    folderPath: people
    fileName: TKTK
    openNote: true

```
---
## People

```dataview
TABLE file.cday as Created, summary
FROM "people" and -#MOC
SORT file.cday DESC
```