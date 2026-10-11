---
type: author
aliases: ["Harold Bloom"]
born: 1930
died: 2019
language: English
roles: ["critic", "professor"]
priority: 6
status: not-started
wikipedia: ""
influenced_by:
  - "[[Shakespeare, William]]"
  - "[[Milton, John]]"
  - "[[Nietzsche, Friedrich]]"
---

## Why read them
Critic who made influence itself the subject; useful for this very vault.

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
