# Crawler
用python selenium搭配chromedriver + beautifulsoup爬蟲
## ig珍藏貼文連結+圖片標籤
Code: ig_saved_posts_desc.ipynb  
1. 有完整功能  
可以爬珍藏貼文的各貼文連結及圖片標籤  
並用pandas做表格呈現  
## fb社團最新貼文連結
Code: fb_group_straight_crawl.ipynb  
1. 半成品  
依最新時間排序爬fb社團清交二手大拍賣XD的前幾則(向下滾一次)貼文連結  
2. 問題  
現在fb貌似有防爬  
f12檢查頁面中看的到href連結  
爬出來卻無法顯示(href="#" or href="社團連結#")  
不過滑鼠點一下f12檢查頁面的href部分模擬人的操作就能顯示了  
3. 可能解決辦法  
點進去貼文  
爬貼文連結  
回到社團頁面  
重複  
4. 預期效果  
當社團有新貼文發布時  
如果此則貼文有關鍵字(免費、送...等等自行設定)  
就發通知(messenger bot or line bot)  
## ig珍藏複製
Code: ig_saved_posts_transfer.ipynb  
1. 半成品  
爬帳號A的所有珍藏貼文連結  
再用帳號B把每一則貼文都珍藏
2. 問題  
短時間開啟太多連結會吃HTTP ERROR 429 (Too Many Requests)  
3. 可能解決辦法  
還沒想到  
4. 預期效果  
將帳號A珍藏貼文複製到帳號B  
### 注意
* Code中需要換上用來登入的帳號密碼  
* 使用時要下載python、selenium、chromedriver、beautifulsoup、pandas
