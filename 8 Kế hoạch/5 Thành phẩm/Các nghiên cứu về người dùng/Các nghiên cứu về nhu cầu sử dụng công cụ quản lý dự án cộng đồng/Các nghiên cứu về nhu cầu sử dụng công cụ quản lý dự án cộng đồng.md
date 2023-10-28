%%
#file/thành-phẩm
%%

Phục vụ cho thành quả:
```dataview
LIST
FROM #file/thành-quả 
WHERE contains(thành-phẩm,[[]])
```
Các giả thuyết cần kiểm tra:
```dataview
LIST giả-thuyết
FROM #file/thành-quả 
WHERE contains(thành-phẩm,[[]])
```
Người chơi::
Đối tượng thụ hưởng: `=this.file.inlinks.đối-tượng-thụ-hưởng`
Thành quả cần có:: [[1 người tham gia phỏng vấn mỗi tuần]]
Thành quả hỗ trợ:: [[3 người có 10 năm kinh nghiệm trong lĩnh vực phi lợi nhuận nhận phỏng vấn]]
Thành quả hỗ trợ:: [[3 người có 1 năm kinh nghiệm trong lĩnh vực phi lợi nhuận nhận phỏng vấn]]

- [x] [[Bài đăng kêu gọi phỏng vấn]] ✅ 2023-03-15
- [ ] Hoàn thành [[Mục tiêu, câu hỏi nghiên cứu. Câu hỏi phỏng vấn, khảo sát]]
- [ ] [[Email mời phỏng vấn]]
	- [ ] SNPO
	- [ ] VOGE
	- [ ] 
- [x] Phỏng vấn anh Minh ✅ 2023-03-14
- [ ] Khảo sát

Thành phẩm nhỏ hơn:
```dataview
List 
Where contains(file.folder,this.file.folder) and file.name!=this.file.name
```


[[Mục tiêu, câu hỏi nghiên cứu. Câu hỏi phỏng vấn, khảo sát]]