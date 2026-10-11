---
type: author
aliases: ["Eugene O'Neill"]
born: 1888
died: 1953
language: English
roles: ["dramatist"]
priority: 3
status: not-started
wikipedia: ""
influenced_by:
  - "[[Strindberg, August]]"
  - "[[Nietzsche, Friedrich]]"
  - "[[Ibsen, Henrik]]"
  - "[[Αισχύλος]]"
---

## Why read them
American tragedy with Greek and Strindbergian roots.

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
