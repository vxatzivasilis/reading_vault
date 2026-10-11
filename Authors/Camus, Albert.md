---
type: author
aliases: ["Albert Camus"]
born: 1913
died: 1960
language: French
roles: ["dramatist", "journalist", "philosopher", "writer"]
priority: 6
status: not-started
wikipedia: ""
influenced_by:
  - "[[Dostoevsky, Fyodor]]"
  - "[[Nietzsche, Friedrich]]"
  - "[[Kafka, Franz]]"
works_raw: "The Stranger"
---

## Why read them
The absurd, revolt and moral clarity in plain prose.

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
