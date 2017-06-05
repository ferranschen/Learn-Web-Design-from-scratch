# Basic Tags

> 這個章節介紹div以及span。

* ### &lt; div &gt;Tag

```html
<div>
  <h3>This is a heading</h3>
  <p>This is a paragraph.</p>
</div>

<div style="color:#000FFF">
  <h3>This is a heading</h3>
  <p>This is a paragraph.</p>
</div>
```

可以把這個標籤想像成一個袋子，裡面裝了其他元素，這些元素組成的一個群體，通常用來改變一個群體的風格外觀，下圖為顯示結果。  
![](/assets/螢幕快照 2017-06-06 上午12.34.28.png)

* ### &lt; span &gt;Tag

```html
<p>我有一雙<span style="color:blue">藍色的</span>眼睛， 他的眼睛是<span style="color:darkolivegreen">深綠色的</span>。</p>
```

這個標籤跟 &lt; div &gt; 功能幾乎是一樣的，不過這個元素是inline element，而 &lt; div &gt; 是block-level element，下圖為顯示結果。

![](/assets/螢幕快照 2017-06-06 上午1.06.27.png)

* ### Block vs Inline Elements

#### Block-level Elements

瀏覽器遇到這種標籤首先會在他前面加入一個換行。另外，這種標籤的寬度會盡可能往左右兩邊延伸到最大。

常見的 Block-level Element 如下：


```html
<div> </div> 

<p> </p> 

<form> </form> 

<h1> - <h6>
```

#### Inline Elements

















