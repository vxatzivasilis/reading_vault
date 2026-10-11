---
type: author
aliases: ["Herta Müller"]
born: 
died: 
language: German
roles: []
priority: 6
status: not-started
wikipedia: ""
influenced_by: []
works_raw: "The Passport"
---

## Why read them
Life under dictatorship rendered in dense, poetic prose.

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
