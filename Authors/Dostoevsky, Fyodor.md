---
type: author
aliases: ["Fyodor Dostoevsky"]
born: 1821
died: 1881
language: Russian
roles: ["essayist", "journalist", "novelist", "short story writer"]
priority: 1
status: not-started
wikipedia: ""
influenced_by:
  - "[[Balzac, Honoré de]]"
  - "[[Hugo, Victor]]"
  - "[[Dickens, Charles]]"
---

## Why read them
Psychological and moral extremity; the template for the novel of ideas.

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
