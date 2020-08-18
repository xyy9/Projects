### 聊天室(server 可視)

###### xyy9/Projects/Socket

> clinet部分：

>> 功能說明 ：

```
名字是這個 client 的名字，通過這個跟別的 client 聊天 
IP 是要填 server 的 IP 
PORT 填 server 的 port 
INPUT_IP+HOST 的 button 是一鍵填寫默認
當名字，ip，port 填寫完之後點擊 connect，跳轉到下一頁 
Back 按鈕是回到前一頁的，並且不斷開連接！
Disconnect 按鈕是斷開與 server 的連接並顯示 
上面的 editview(To:)是要填你（client2）想交流的 client 的名字（client1） 
下面的 editview(輸入訊息)是要填你對上面的 client 想說的話 
然後點擊送出按鈕 
如果上面的 client 也連接在相同的 server 中，則信息發送，並且會在那個 client 中顯示誰說了什麼 
如果上面的 client 跟 server 並沒有連線，則 server 回傳
```

> server部分：

>> 功能說明 ：

```
點擊開啟按鈕，抓取 server 所在網路的 ip  
Port 初始設定為 9999
界面顯示 server 連接的 client 個數 
Users 按鈕可以查看連接這個 server 的 client 都有哪些 
並且會顯示哪個 client 給哪個 client 傳了什麼 
同時連接的所有 client 會顯示
```
