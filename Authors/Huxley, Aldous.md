---
type: author
aliases: ["Aldous Huxley"]
born: 1894
died: 1963
language: English
roles: ["philosopher", "writer"]
priority: 4
status: not-started
wikipedia: ""
influenced_by: []
---

## Why read them
Dystopia built on pleasure rather than terror; essays on mind and society.

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
