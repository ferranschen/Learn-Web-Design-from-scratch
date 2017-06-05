# Basic Tags

> 這個章節介紹div以及span，它們可以將元素組合起來，有點像是一個容器。

* ### &lt; div &gt;Tag

```html
<div>
  <h3>This is a heading</h3>
  <p>This is a paragraph.</p>
</div>

<!--我們將下面的群體組合起來，然後賦予它一個顏色-->
<div style="color:#000FFF">
  <h3>This is a heading</h3>
  <p>This is a paragraph.</p>
</div>
```

可以把這個標籤想像成一個袋子，裡面裝了其他元素，這些元素組成的一個群體，通常用來改變一個群體的風格外觀，下圖為顯示結果。  
![](/assets/螢幕快照 2017-06-06 上午12.34.28.png)

---

* ### &lt; span &gt;Tag

```html
<p>我有一雙<span style="color:blue">藍色的</span>眼睛， 他的眼睛是<span style="color:darkolivegreen">深綠色的</span>。</p>
```

這個標籤跟 &lt; div &gt; 功能幾乎是一樣的，不過這個元素是inline element，而 &lt; div &gt; 是block-level element，下圖為顯示結果。

![](/assets/螢幕快照 2017-06-06 上午1.06.27.png)

---

* ### Block vs Inline Elements

> 剛剛有提到 inline element 跟 block-level element，以下我們簡單做一個區別，現在可能還比較沒有感覺，在後面的例子慢慢就會察覺出來差別了。

#### Block-level Elements

瀏覽器遇到這種標籤首先會在它前面加入一個換行。另外，這種標籤的寬度會盡可能往左右兩邊延伸到最大。

常見的 Block-level Elements 如下：

```html
<div> </div> 

<p> </p> 

<form> </form> 

<h1> - <h6>
```

#### Inline Elements

瀏覽器遇到這種標籤並不會加入換行，內容通常是文字或是連結。另外，這種標籤的寬度只會取剛好所需。

常見的 Inline Elements 如下：

```html
<span> </span>

<a> </a>

<img>
```

#### 參考例子：

```html
<p>工為而晚紙又；中建後，<span style="color: red">遠喜次南公蘭己人麗這生……媽裡童，</span>
來至資士縣和，時統全一主下股果取我把世；經位多心樣，<p style="color: green">學答斷！音產意旅花
。長劇是節李具</p>：止今寫作只年：臺制片我都機品是可運何文的……於勢心至國黃自人品星的本圖。表媽量遠時量，
風一以可海優看要安立隊德改前國為思玩歌造過員晚三檢讀面竟下無一。</p>
<!-- 以上為內容為無意義的隨機假文 -->
```

顯示結果如下：

![](/assets/螢幕快照 2017-06-06 上午2.16.50.png)

你可以發現，&lt; span &gt; 前面並沒有換行，而且寬度只取剛好。相反的，&lt; p &gt; 前面多了一個換行，而且寬度是取最左邊到最右邊。原因是因為 &lt; span &gt; 是一個 inline element，而&lt; p &gt; 則是 block-level element。 



### 單元總結

 > 這個章節我們介紹了兩個標籤，分別是&lt; div &gt; 跟 &lt; span &gt;。我們更進一步的瞭解 Block 跟 Inline Elements 的差別。不要被這些名詞嚇到，先有基本的概念就行了，以後的例子比較能感受到差別。



























