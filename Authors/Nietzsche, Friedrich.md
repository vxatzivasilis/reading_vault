---
type: author
aliases: ["Friedrich Nietzsche"]
born: 1844
died: 1900
language: German
roles: ["critic", "philosopher"]
priority: 1
status: not-started
wikipedia: ""
influenced_by: []
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
