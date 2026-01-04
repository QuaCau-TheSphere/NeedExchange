---
share: true
created: 2026-01-03T16:47
updated: 2026-01-03T16:47
---
```dataview
LIST rows.file.link
FROM "1 Nhu cầu/Chiến lược đáp ứng/Cấp độ cá nhân"
GROUP BY split(file.folder, "/")[3]
WHERE file.name != this.file.name
```