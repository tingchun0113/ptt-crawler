# ptt-crawler

Demo: https://colab.research.google.com/drive/18wupYerwiNJ77syxBv8ZZmkkj9pGjblW?usp=sharing
<br>
<br>
原本是為了看/爬些房貸資料，結果就順手做了這個微專案。程式碼有部分參考此[專案](https://github.com/leVirve/CrawlerTutorial)。

## 專案功能
- 身為使用者，在 **Variables** 
  - 可以修改要爬哪個看板 `e.g. board = 'Loan'`
  - 可以修改要爬幾頁的資料 `e.g. num_pages = 10`
  - 可以指定要爬標題有哪些關鍵字的資料 `e.g. title_keywords = ['房貸', '房屋']`

- 身為使用者，在 **Preview crawled data**
  - 可以預覽爬下的資料
  <img src="/preview_crawled_data.png">

- 身為使用者，在 **Add columns**
  - 可以增加額外資料欄位 (從爬下資料的內文中，尋找房價/收入關鍵字擷取資料，然後增加 2 個新欄位房價及收入)

- 身為使用者，在 **Save to CSV**
  - 可以下載資料成 csv
