[[+Home]] %% tags:: #MOC %% 

# Task MOC
Tasks are ...

**Template:** [[task_template]]

```meta-bind-button
label: New Task
hidden: false
class: ""
tooltip: ""
id: ""
style: default
actions:
  - type: templaterCreateNote
    templateFile: obsidian_helper/templates/task_template.md
    folderPath: tasks
    fileName: TKTK
    openNote: true

```
## Tasks

**Ready**

```dataview
TABLE file.cday, status as status
FROM "tasks" and -#MOC
SORT file.cday DESC
WHERE status = "Ready"
```

**In Progress**

```dataview
TABLE file.cday, status as status
FROM "tasks" and -#MOC
SORT file.cday DESC
WHERE status = "In Progress"
```

**Done**

```dataview
TABLE file.cday, status as status
FROM "tasks" and -#MOC
SORT file.cday DESC
WHERE status = "Done"
```

**Due Date**

```dataview
TABLE due_date as Due_Date
FROM "tasks" and -#MOC
SORT due_date DESC
WHERE status != "Done"
```
