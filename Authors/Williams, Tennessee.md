---
type: author
aliases: ["Tennessee Williams"]
born: 1911
died: 1983
language: English
roles: ["dramatist", "screenwriter"]
priority: 6
status: not-started
wikipedia: ""
influenced_by:
  - "[[Chekhov, Anton]]"
  - "[[Strindberg, August]]"
---

## Why read them
Southern Gothic psychology on the American stage.

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
