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

---

* ### &lt; span &gt;Tag

```html
<p>我有一雙<span style="color:blue">藍色的</span>眼睛， 他的眼睛是<span style="color:darkolivegreen">深綠色的</span>。</p>
```

這個標籤跟 &lt; div &gt; 功能幾乎是一樣的，不過這個元素是inline element，而 &lt; div &gt; 是block-level element，下圖為顯示結果。

![](/assets/螢幕快照 2017-06-06 上午1.06.27.png)

---

* ### Block vs Inline Elements

>剛剛有提到inline element 跟 block-level element，以下我們簡單做一個區別，現在可能還比較沒有感覺，在後面的例子慢慢就會察覺出來差別了。

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

瀏覽器遇到這種標籤並不會加入換行。另外，這種標籤的寬度只會取剛好所需。

常見的 Inline Elements 如下：

```html
<span> </span>
<a> </a>
<img>
```

#### 參考例子：


```html
		<p>Lorem ipsum dolor sit amet, <span style="color: green">consectetur adipisicing elit,</span> sed do eiusmod
	tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
	quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
	consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
	cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
	proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
	<p>Lorem ipsum dolor sit amet, <div style="color:red">consectetur adipisicing elit, sed do eiusmodtempor incididunt ut labore et dolore </div> magna aliqua. Ut enim ad minim veniam,
	quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
	consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
	cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
	proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
```















