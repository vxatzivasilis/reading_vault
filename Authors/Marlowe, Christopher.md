---
type: author
aliases: ["Christopher Marlowe"]
born: 1564
died: 1593
language: English
roles: ["dramatist", "poet", "translator"]
priority: 4
status: not-started
wikipedia: ""
influenced_by: []
---

## Why read them
Shakespeare's most important predecessor; ambition and damnation in blank verse.

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
