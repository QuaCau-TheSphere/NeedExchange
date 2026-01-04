---
share: true
created: 2024-02-29T23:53
updated: 2026-01-03T16:10
aliases:
  - Danh sách các nhu cầu công việc thường gặp
  - Kho tài nguyên cho các nhu cầu thường gặp trong công việc
  - Các nhu cầu liên quan đến nghiên cứu, vận hành
---
```dataview
LIST rows.file.link
FROM "1 Nhu cầu/Chiến lược đáp ứng/Cấp độ dự án/Nhu cầu công việc" 
WHERE file.name!=this.file.name
GROUP BY split(file.folder, "/")[4]
```
