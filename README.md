objc.io issue #2
===

This is an example project for the article [Common Background Practices](http://www.objc.io/issue-2/common-background-practices.html) published in [objc.io issue #2](http://www.objc.io/issue-2/index.html).

##### 裡面講到
1. 初始化匯入大量資料 (一萬兩千多筆 柏林 車站座標 )
2. 如何在背景載入 並且 控制批次寫入 Core Data 筆數，盡量避免寫入時 讓 UI 停住
3. 如何使用 NSFetchedResultsController 將一萬多筆資料載入 TableView 不會閃退 而且捲動不會延遲
