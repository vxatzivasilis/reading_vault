---
type: author
aliases: ["Lu Xun"]
born: 
died: 
language: Chinese
roles: []
priority: 6
status: not-started
wikipedia: ""
influenced_by:
  - "[[Nietzsche, Friedrich]]"
works_raw: "Diary of a Madman and Other Stories"
---

## Why read them
Founder of modern Chinese literature; savage social satire in short form.

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
