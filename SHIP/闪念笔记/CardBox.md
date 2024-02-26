---
cssclasses:
  - zettelkasten
  - max
obsidianUIMode: preview
---
```dataviewjs 
dv.table(["卡片","简介"],
dv.pages("#zettelkasten")
	.map(p => [p.file.link, p.description]))
```
