### Basic Tags

> 這個章節介紹幾個常見的tag。

### 語法查詢

> 在介紹Tags之前，先介紹兩個Web開發的語法查詢網站，分別是  
> [MDN](https://developer.mozilla.org/zh-TW/)以及[W3School](https://www.w3schools.com)，在上面你可以得到非常詳細的資訊，也可以在上面學習到一些語法的使用慣例。


* ### h1 to h6 Tag

```html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>
```

h1 到 h6 分別代表不同等級的標題，h1最高，h6最小，下圖為顯示結果。

![](/assets/螢幕快照 2017-06-05 上午1.56.42.png)

使用習慣

1. 通常作為一段文章的標題，盡量從h1 -&gt; h2 -&gt; h3 -&gt; h4 -&gt; h5 -&gt; h6 這個順序去使用他，如果你用h1 - &gt; h3 或是h2 -&gt; h5，那麼這種標題的落差感會比較大，看起來比較奇怪。
2. 標題階級只是一種比例，沒有絕對的大小，不同的瀏覽器有不同的size，如果你需要微調標題大小，請你使用[ CSS font-size](https://developer.mozilla.org/en-US/docs/Web/CSS/font-size) （在CSS章節會提到）。

3. "align" 這個屬性在HTML 5 已經被淘汰了，所以不要在標題\(h1~h6\)中使用align 屬性\(之後會討論更多關於屬性attribute的議題\)。
---
* ### p Tag

```html
<p>運動競技對身體健康非常有幫助。</p>
<p>體育運動是對於所有有組織或無組織參與，通過使用、維持或改進體能，為參與者提供娛樂的競技性身體運動的總稱。</p>
```
p Tag 代表的是文字的段落，下圖為顯示結果。
![](/assets/螢幕快照 2017-06-05 上午2.50.29.png)

你可以發現，段落之間會用換行隔開。


也是一種Block level element(塊級元素)，通常





