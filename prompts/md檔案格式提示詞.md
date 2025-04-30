請將以下英文新聞內容依照以下格式與規則，**轉換為 Jekyll 使用的 Markdown `.md` 檔案**，並給我一個可下載的檔案連結。

---

### 🗂 檔案命名規則
```
YYYY-MM-DD-類別 _ 標題.md
```
- `YYYY-MM-DD` 為新聞日期
- `-` 用來連接日期與議題類型（如 Technology、Politics、World News 等）
- `_` 前後加空格，用來分隔「議題類型」與「文章標題」

🟢 範例：
```
2025-04-29-Technology _ LG and MediaTek Unveil Next-Gen In-Car Infotainment System.md
```

---

### 🧾 YAML Front Matter 格式
```yaml
---
layout: post
title: "YYYY-MM-DD _ 類別 _ 標題"
---
```
- 使用底線 `_` 分隔 `日期 _ 類別 _ 標題`
- 不使用破折號 `–`，避免 YAML 解碼錯誤

---

### 📑 文章格式規則
請依照以下區塊順序整理文章，不改寫文字內容：

1. `### Article`  
2. `<!-- split -->`  
3. `### Vocabulary`（英文詞彙 + 英文定義，共 5 個）  
4. `<!-- split -->`  
5. `### Reading Comprehension`（選擇題 3 題，每題 4 個選項）  
6. `<!-- split -->`  
7. `### Answer Key`（直接列出 1. A / B / C... 格式）  
8. `<!-- split -->`  
9. `### Source`（統一使用 `[標題](網址)` 格式）

---

### 🔄 自動行為要求
- 自動讀取文章標題作為檔案名的一部分
- 自動將文章整理為 `.md` 並提供一鍵下載連結
- 所有破折號與底線使用，需嚴格區分並遵循上述規則

---
