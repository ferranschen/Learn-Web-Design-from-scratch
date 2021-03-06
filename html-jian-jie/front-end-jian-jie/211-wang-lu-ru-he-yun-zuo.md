

> ###### 我們每天都在使用網路，如果在瀏覽器上面輸入 www.youtube.com 然後按下確認鍵，這短短的幾秒鐘，電腦做了什麼事情呢？
>
> ![](/assets/螢幕快照 2017-06-02 下午9.55.52.png)

* ### 網路如何運作（請先收看以下連結）

#### [How the Internet Works in 5 Minutes](https://www.youtube.com/watch?v=7_LPdttKXPc)

<br />
Internet 並不是我們想像中的雲。  
![](/assets/螢幕快照 2017-06-02 下午7.13.56.png)  
<br />
事實上，網路只是一條線，這條線上有client端以及server端，由client端發出服務請求，server端回應。server端通常擁有大量資訊跟強大的運算能力。（例子 : 在youtube上打辛普森家庭，youtube server收到影片的請求，然後傳送辛普森家庭的影片給client，client的瀏覽器收到之後便開始播放。）  
![](/assets/螢幕快照 2017-06-02 下午9.12.04.png)  
<br />
在這條線上，每個連線裝置都有一個地址，就像是寄信的時候我們需要收件人的地址，我們稱這個地址叫做IP。IP是由數字跟點構成的。數字不好記，所以我們用“名稱.com”來取代地址。實際上電腦會去查詢“名稱.com”對應到的“地址”是多少，這種查詢需要借助DNS。  
![](/assets/螢幕快照 2017-06-02 下午9.12.42.png)
<br />
另外，網路連線通常藉由網際網路服務供應商ISP（例如:中華電信、台灣大哥大）所提供的服務來進行連線，所以資料會先經過ISP才會到server。  
![](/assets/螢幕快照 2017-06-02 下午9.14.10.png)
<br />
在網路上，所有的資料都會被切成小塊的單位進行傳送，我們稱這種資料格式叫做封包。
![](/assets/螢幕快照 2017-06-02 下午10.27.19.png)

<br />
傳送封包的過程中，封包可能會遇到許多路由器（router），這個角色有點像是郵局，路由器會接收封包，然後把封包交到另外一個路由器上，直到最後交到目的地。
![](/assets/螢幕快照 2017-06-02 下午10.30.39.png)
<br />


* ### 延伸閱讀



1.[什麼是DNS](http://dns-learning.twnic.net.tw/dns/01whatDNS.html)
<br />
2.[網路封包](https://zh.wikipedia.org/wiki/網路封包)
<br />









