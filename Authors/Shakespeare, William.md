---
type: author
aliases: ["William Shakespeare"]
born: 1564
died: 1616
language: English
roles: ["dramatist", "poet"]
priority: 1
status: not-started
wikipedia: ""
influenced_by:
  - "[[Marlowe, Christopher]]"
works_raw: "Hamlet, King Lear"
---

## Why read them
The benchmark for character, language and dramatic structure in English.

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
