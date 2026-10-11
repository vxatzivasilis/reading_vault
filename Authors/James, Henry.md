---
type: author
aliases: ["Henry James"]
born: 
died: 
language: English
roles: []
priority: 6
status: not-started
wikipedia: ""
influenced_by:
  - "[[Balzac, Honoré de]]"
  - "[[Flaubert, Gustave]]"
works_raw: "The Turn of the Screw"
---

## Why read them
Psychological realism; consciousness as the real subject of the novel.

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
