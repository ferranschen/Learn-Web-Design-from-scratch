### Basic Tags

> 這個章節介紹幾個常見的tag。

### 語法查詢

> 在介紹 tags 之前，先介紹兩個 Web 開發的語法查詢網站，分別是  
> [MDN](https://developer.mozilla.org/zh-TW/) 以及 [W3School](https://www.w3schools.com)，在上面你可以得到非常詳細的資訊，也可以在上面學習到一些語法的使用慣例。


* ### &lt; h1 &gt; to &lt; h6 &gt; Tag

```html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>
```

&lt; h1 &gt; 到 &lt; h6 &gt; 分別代表不同等級的標題，&lt; h1 &gt;最高，&lt; h6 &gt;最小，下圖為顯示結果。

![](/assets/螢幕快照 2017-06-05 上午3.11.16.png)

使用習慣

1. 通常作為一段文章的標題，盡量從h1 -&gt; h2 -&gt; h3 -&gt; h4 -&gt; h5 -&gt; h6 這個順序去使用，如果你用h1 - &gt; h3 或是h2 -&gt; h5，那麼這種標題的落差感會太大。
2. 標題階級只是一種比例，沒有絕對的大小，不同的瀏覽器有不同的size，如果你需要微調標題大小，請你使用[ CSS font-size](https://developer.mozilla.org/en-US/docs/Web/CSS/font-size) （在CSS章節會提到）。

3. "align" 這個屬性在HTML 5 已經被淘汰了，所以不要在標題\(h1~h6\)中使用align 屬性\(之後會討論更多關於屬性attribute的議題\)。
---
* ### &lt; p &gt; Tag

```html
<p>運動競技對身體健康非常有幫助。</p>
<p>體育運動是對於所有有組織或無組織參與，通過使用、維持或改進體能，為參與者提供娛樂的競技性身體運動的總稱。</p>
```
&lt; p &gt;  Tag 代表的是文字的段落，下圖為顯示結果。
![](/assets/螢幕快照 2017-06-05 上午2.50.29.png)

你可以發現，瀏覽器遇到段落會加上一個換行，而不會直接接到下一個段落。另外，如同 &lt; h1 &gt;，不要在&lt; p &gt; 中使用“align”屬性

---
* ### &lt; ol &gt; 與 &lt; ul &gt; Tag

```html
<ul>
  <li>first item</li>
  <li>second item</li>
  <li>third item</li>
</ul>
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```
unordered list (ul) 無序列表，以及 ordered list (ol) 有序列表，會搭配 &lt; li &gt; 來呈現，下圖為顯示結果。 
![](/assets/螢幕快照 2017-06-05 下午2.52.51.png)

使用習慣

1. 通常作為一段文章的標題，盡量從h1 -&gt; h2 -&gt; h3 -&gt; h4 -&gt; h5 -&gt; h6 這個順序去使用，如果你用h1 - &gt; h3 或是h2 -&gt; h5，那麼這種標題的落差感會太大。
2. 標題階級只是一種比例，沒有絕對的大小，不同的瀏覽器有不同的size，如果你需要微調標題大小，請你使用[ CSS font-size](https://developer.mozilla.org/en-US/docs/Web/CSS/font-size) （在CSS章節會提到）。

3. "align" 這個屬性在HTML 5 已經被淘汰了，所以不要在標題\(h1~h6\)中使用align 屬性\(之後會討論更多關於屬性attribute的議題\)。

 





