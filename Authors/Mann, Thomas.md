---
type: author
aliases: ["Thomas Mann"]
born: 1875
died: 1955
language: German
roles: ["critic", "essayist", "novelist", "short story writer"]
priority: 5
status: not-started
wikipedia: ""
influenced_by:
  - "[[Goethe, Johann Wolfgang von]]"
  - "[[Nietzsche, Friedrich]]"
  - "[[Schopenhauer, Arthur]]"
---

## Why read them
The great German novel of ideas: bourgeois decline, art and sickness.

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
