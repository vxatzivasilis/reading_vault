---
type: author
aliases: ["Franz Kafka"]
born: 1883
died: 1924
language: German
roles: ["novelist", "writer"]
priority: 1
status: not-started
wikipedia: ""
influenced_by: []
works_raw: "The Trial"
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
