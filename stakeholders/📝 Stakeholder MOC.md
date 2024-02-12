[[+Home]] %% tags:: #MOC %% 

# Stakeholder MOC


**Template:** [[stakeholder_template]]

```meta-bind-button
label: New Stakeholder
hidden: false
class: ""
tooltip: ""
id: ""
style: default
actions:
  - type: templaterCreateNote
    templateFile: obsidian_helper/templates/stakeholder_template.md
    folderPath: stakeholders
    fileName: TKTK
    openNote: true

```
---
## Stakeholders

```dataview
TABLE file.cday as Created, summary
FROM "stakeholders" and -#MOC
SORT file.cday DESC
```