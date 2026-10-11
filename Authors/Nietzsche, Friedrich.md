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
influenced_by:
  - "[[Schopenhauer, Arthur]]"
  - "[[Ηράκλειτος]]"
  - "[[Goethe, Johann Wolfgang von]]"
---

## Why read them
The most provocative critic of morality, religion and culture in modern thought.

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
