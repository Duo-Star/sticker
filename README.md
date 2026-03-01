# 你的QQ聊天里的常见表情

共计 6503 个，2 GB

收集这些干什么？

1. ~~我闲的~~
2. 有趣

# 分卷浏览

---

### 卷一

[浏览_01](src/_01/0.md)

---

### 卷二
[浏览_02](src/_02/0.md)

---

### 卷三

[浏览_03](src/_03/0.md)

---

### 卷四

[浏览_04](src/_04/0.md)

---

### 卷五

[浏览_05](src/_05/0.md)

---

### 卷六

[浏览_06](src/_06/0.md)

---

### 卷七

[浏览_07](src/_07/0.md)

---

### 涨知识环节

```ps
Get-ChildItem -Path . -File | Where-Object { $_.Extension -match "png|jpg|jpeg|gif" } | ForEach-Object { "![$($_.Name)]($($_.Name))" } | Out-File -FilePath "0.md" -Encoding utf8
```

用于将目录中的图片转为目标于同级目录输出 markdown 语法的图片链接，保存为 `0.md`
