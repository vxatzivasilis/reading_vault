---
type: author
aliases: ["Bertolt Brecht"]
born: 1898
died: 1956
language: German
roles: []
priority: 6
status: not-started
wikipedia: "https://el.wikipedia.org/wiki/%CE%9C%CF%80%CE%AD%CF%81%CF%84%CE%BF%CE%BB%CF%84_%CE%9C%CF%80%CF%81%CE%B5%CF%87%CF%84"
influenced_by: []
works_raw: "The Caucasian Chalk Circle"
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
