---
type: author
aliases: ["George Ostrogorsky"]
born: 1902
died: 1976
language: 
roles: []
priority: 6
status: not-started
wikipedia: "https://el.wikipedia.org/wiki/%CE%93%CE%B5%CF%8E%CF%81%CE%B3%CE%B9%CE%BF%CF%82_%CE%9F%CF%83%CF%84%CF%81%CE%BF%CE%B3%CE%BA%CF%8C%CF%81%CF%83%CE%BA%CE%B9"
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
