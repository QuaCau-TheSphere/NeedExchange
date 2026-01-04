---
share: true
created: 2026-01-03T15:44
updated: 2026-01-03T16:43
---
```dataview
LIST rows.file.link
FROM "1 Nhu cầu/Chiến lược đáp ứng/Sứ mạng"
GROUP BY split(file.folder, "/")[3]
WHERE file.name != this.file.name
```