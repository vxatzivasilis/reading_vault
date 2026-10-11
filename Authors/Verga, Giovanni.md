---
type: author
aliases: ["Giovanni Verga"]
born: 1840
died: 1922
language: Italian
roles: ["writer"]
priority: 5
status: not-started
wikipedia: ""
influenced_by:
  - "[[Balzac, Honoré de]]"
  - "[[Flaubert, Gustave]]"
---

## Why read them
Founder of Italian verismo: Sicilian poverty told without sentiment.

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
