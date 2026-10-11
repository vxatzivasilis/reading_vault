---
type: author
aliases: ["Johann Wolfgang von Goethe"]
born: 1749
died: 1832
language: 
roles: []
priority: 
status: not-started
wikipedia: "https://el.wikipedia.org/wiki/%CE%93%CE%B9%CF%8C%CF%87%CE%B1%CE%BD_%CE%92%CF%8C%CE%BB%CF%86%CE%B3%CE%BA%CE%B1%CE%BD%CE%B3%CE%BA_%CF%86%CE%BF%CE%BD_%CE%93%CE%BA%CE%B1%CE%AF%CF%84%CE%B5"
influenced_by: []
---

## Why read them


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
