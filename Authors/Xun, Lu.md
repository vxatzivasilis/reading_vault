---
type: author
aliases: ["Lu Xun"]
born: 
died: 
language: Chinese
roles: []
priority: 
status: not-started
wikipedia: ""
influenced_by: []
works_raw: "Diary of a Madman and Other Stories"
---

## Why read them


## Must-read works
```dataview
TABLE year, form, status FROM "Works"
WHERE author = this.file.link
SORT year ASC
```

## Influenced (computed automatically)
```dataview
LIST FROM "Authors"
WHERE contains(influenced_by, this.file.link)
```

## Notes
