
```dataview
TABLE
	journal-date AS "Journal Date",
	author-date AS "Author Date",
	ratings.energy AS "⚡",
	ratings.focus AS "🤔",
	ratings.mental-capacity AS "🧠",
	ratings.productivity AS "🤖",
	file.inlinks AS "Mentions"
FROM
	"Daily Journals"
SORT
	journal-date ASC
```
