---
share: true
created: 2024-02-29T23:53
updated: 2026-01-03T15:48
---
```dataview
LIST rows.file.link
FROM "📜Tài nguyên/Nhu cầu công nghệ" 
GROUP BY split(file.folder, "/")[2]
WHERE file.name != this.file.name
```

Lĩnh vực:: [[Lĩnh vực]]
Giải pháp kỹ thuật:: [[Giải pháp kỹ thuật]]
[Outline of computer science - Wikipedia](https://en.wikipedia.org/wiki/Outline_of_computer_science)
[There's an AI for that](https://theresanaiforthat.com/)
[[No code so với có code giống như so xe Lego so với ô tô thực sự]]
