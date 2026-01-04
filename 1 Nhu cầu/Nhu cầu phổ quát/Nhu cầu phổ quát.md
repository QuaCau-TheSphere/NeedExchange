---
share: true
created: 2026-01-03T11:48
updated: 2026-01-03T16:48
---
Bài chi tiết: [[Các nhóm nhu cầu của cá nhân]]
```dataview
LIST rows.file.link
FROM "1 Nhu cầu/Nhu cầu phổ quát"
GROUP BY split(file.folder, "/")[2]
WHERE file.name != this.file.name
```