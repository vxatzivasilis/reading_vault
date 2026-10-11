---
type: author
aliases: ["John Milton"]
born: 1608
died: 1674
language: 
roles: []
priority: 6
status: not-started
wikipedia: "https://el.wikipedia.org/wiki/%CE%A4%CE%B6%CE%BF%CE%BD_%CE%9C%CE%AF%CE%BB%CF%84%CE%BF%CE%BD"
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
