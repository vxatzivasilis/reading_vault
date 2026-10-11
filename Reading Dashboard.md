## Top of the queue (priority 1-2, first 10)
```dataview
TABLE author, author.priority AS "Pri", year, form
FROM "Works"
WHERE must_read = true AND status = "unread" AND author.priority <= 2
SORT author.priority ASC, year ASC
LIMIT 10
```

## Full queue
```dataview
TABLE author, author.priority AS "Pri", year, form
FROM "Works"
WHERE must_read = true AND status = "unread"
SORT author.priority ASC, author ASC, year ASC
```

## Currently reading
```dataview
TABLE author, year
FROM "Works"
WHERE status = "reading"
```

## Finished
```dataview
TABLE author, date_finished, rating
FROM "Works"
WHERE status = "done"
SORT date_finished DESC
```