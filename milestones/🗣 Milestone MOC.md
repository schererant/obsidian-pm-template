[[+Home]] %% tags:: #MOC %% 

# Milestone MOC
...

**Template:** [[milestone_template]]

```meta-bind-button
label: New Milestone
hidden: false
class: ""
tooltip: ""
id: ""
style: default
actions:
  - type: templaterCreateNote
    templateFile: obsidian_helper/templates/milestone_template.md
    folderPath: milestones
    fileName: TKTK
    openNote: true

```
## Milestones

```dataview
TABLE file.cday, due_date as Created, summary, Due_Date
FROM "milestones" and -#MOC
SORT file.cday DESC
```
