# ICND Physical Layer
實體層（物理層）

實體層主要定義了傳輸媒體、連接方式、信號類別，並且規範出啟動、維護、停用終端系統間各類實體連接時，電子機械、傳送程序的需求。

實體層也掌握了 Voltage、Speed、MTU (Payload) 最大傳輸單位 、Max Distance、Flux Rate(throughput) 資料流通率。

* 線材與連接器

由該層標準定義之，例如 Ethernet 抑或是 IEEE 802.3 標準，定義了串連 bus 架構且速度達到 10M(10Mbps) 的 LAN。

其中三種線材的標準：

   -- 10Base2: 近乎200m（細的同軸電纜）
  
   -- 10Base5: 500m (粗的同軸電纜)
  
   -- 10BaseT: 100m (雙絞線), 大部分應用在集線器連結 hosts 的線材。
   
 * 信號碰撞
 
 因為 Ethernet 中同網段的各點是以同一條線材連接，因此在線路上傳算的任何信號均可為所有設備收到。這表示任兩點同時送出的信號，會發生碰撞，因此乙太網路架構上需要一套規範，確保了同一時間內僅有一個節點 node 會在線上發送信號 send signal，並且有一套機制能偵錯。
 
 * 廣播領域
 
 指一組網路上設備，彼此間可以收到對方廣播信息的範圍。
 
 * 網路設備
 
 指稱路由器或交換器，並不包含伺服器或是主機。

 
 
  




