---
created: 2023-04-15T10:31
updated: 2026-01-02T16:37
---
Lý do:: 

Giải pháp cho yêu cầu này:
```dataview
List where contains(lý-do,[[]])
```

Vấn đề phát sinh::
```dataview
Table vấn-đề-phát-sinh as "Vấn đề phát sinh" 
where contains(lý-do,[[]])
```
