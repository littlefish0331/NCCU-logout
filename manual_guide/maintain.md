---
title: maintain
tags: NCCU-logout
disqus: hackmd
lang: zh-tw
---

{%hackmd @NCCU-logout/styles%}

###### tags: `maintain` `連動機制` `md差異`

# 維護注意事項

- [GitHub repository](https://github.com/littlefish0331/NCCU-logout)
- [本手冊的網址]

## github和HackMD連動機制

基本上不要造成版本混亂的方法，就是修改後，都與master同步。  
如此一來，本機端執行pull的動作，就可以解決衝突的問題。

- 舊的HackMD，新增內容: pull
- 建立新的HackMD，記得新增 Github 連動的檔案，檔名設定一樣即可。
- 網址記得改成和md檔名一樣
- 瀏覽模式
- 可閱讀: 所有人
- 可編輯: 擁有者。
- 更多設定: 留言權限: 啟用，所有人

---

## md 開頭模板

```
---
title: md檔名(即網址連結名稱)
tags: NCCU-logout, 資料分類
disqus: hackmd
lang: zh-tw
---

{%hackmd @NCCU-logout/styles%}

###### tags: `md檔名` `文章大標`
```

---

## HackMD和GitHub的markdown差異

| 效果語法                   | HackMD | Gitlab .md        |
|----------------------------|--------|-------------------|
| Enter換行(軟換行)           | O      | X，需要句尾空兩格，<br>或是加上反斜線`\` |
| :::<br>的標註區塊<br>::: | O      | X                 |

## 文章標題與md檔名對應

| 文章標題                     | md檔名      | Link |
|------------------------------|-------------|------|
| 內嵌風格                     | styles      |      |
| 維護注意事項                 | maintain    |      |
| 政大碩士 - 畢業+離校教戰手則 | manual      |      |

**政大碩士 - 畢業+離校教戰手則 manual_guide:**

| 文章標題                     | md檔名      | Link |
|------------------------------|-------------|------|
| 計畫說明                     | README      |      |
| 重要時程                     | deadline    |      |
| 常見問題                     | FAQ         |      |
| 感謝貢獻                     | contributor |      |
| 與作者聯繫                   | contact     |      |

**論文格式 thesis_format:**

**調查口試時間、邀請老師 schedule_invite:**

**口試餐點 oral_meal:**

**裝訂論文 binding_thesis:**

**離校RPG logout_RPG:**
