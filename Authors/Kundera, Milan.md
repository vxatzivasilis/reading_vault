---
type: author
aliases: ["Milan Kundera"]
born: 
died: 
language: French
roles: []
priority: 6
status: not-started
wikipedia: ""
influenced_by:
  - "[[Kafka, Franz]]"
  - "[[Cervantes, Miguel de]]"
works_raw: "The Unbearable Lightness of Being"
---

## Why read them
Philosophical novels on memory, politics and the lightness of existence.

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
