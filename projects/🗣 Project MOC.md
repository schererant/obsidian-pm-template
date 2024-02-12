[[+Home]] %% tags:: #MOC %% 

# Project MOC
Ipse Lorum

**Template:** [[meeting_template]]

```meta-bind-button
label: New Project
hidden: false
class: ""
tooltip: ""
id: ""
style: default
actions:
  - type: templaterCreateNote
    templateFile: obsidian_helper/project_template.md
    folderPath: projects
    fileName: ""
    openNote: true

```
## Projects

```dataview
TABLE file.cday as Created, summary
FROM "projects" and -#MOC
SORT file.cday DESC
```

