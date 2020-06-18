---
title: maintain
tags: NCCU-logout
disqus: hackmd
lang: zh-tw
---

###### tags: `maintain` `連動機制` `md差異`

# 維護注意事項

- [GitHub repository](https://github.com/littlefish0331/NCCU-logout)
- [本手冊的網址]()

## github和HackMD連動機制

基本上不要造成版本混亂的方法，就是修改後，都與master同步。  
如此一來，本機端執行pull的動作，就可以解決衝突的問題。

## HackMD和GitHub的markdown差異

| 效果語法                   | HackMD | Gitlab .md        |
|----------------------------|--------|-------------------|
| Enter換行(軟換行)           | O      | X，需要句尾空兩格，<br>或是加上反斜線`\` |
| :::<br>的標註區塊<br>::: | O      | X                 |
