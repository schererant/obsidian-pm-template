[[+Home]] %% tags:: #MOC %% 

# Milestone MOC
...

**Template:** [[meeting_template]]


## Meeting Notes

```dataview
TABLE file.cday as Created, summary
FROM "meetings" and -#MOC
SORT file.cday DESC
```