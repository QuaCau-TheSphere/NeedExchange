---
share: true
created: 2026-01-03T16:46
updated: 2026-01-03T16:46
---
 ```dataview
LIST rows.file.link
FROM "1 Nhu cầu/Chiến lược đáp ứng/Cấp độ dự án"
GROUP BY split(file.folder, "/")[3]
WHERE file.name != this.file.name
```