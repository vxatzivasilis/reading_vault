---
type: author
aliases: ["Milan Kundera"]
born: 
died: 
language: French
roles: []
priority: 
status: not-started
wikipedia: ""
influenced_by: []
works_raw: "The Unbearable Lightness of Being"
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
