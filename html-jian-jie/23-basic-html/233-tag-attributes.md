# Basic Tags 5

> 這個章節介紹 &lt; form &gt;。這是輸入表所需的元素，&lt; form &gt;可以讓使用者輸入資訊並傳遞到server端，網頁設計中，常會用到這個元素。

在還沒有網路的時代，其實人們就已經開始使用填入表了，我們用固定格式的表格來填入所需的資訊。在網頁中，我們也需要填入表來幫助我們設計網頁，以下是一些常見的填入表。

![](/assets/螢幕快照 2017-06-17 下午11.20.14.png)![](/assets/螢幕快照 2017-06-17 下午11.22.23.png)![](/assets/螢幕快照 2017-06-17 下午11.20.27.png)

我們在許多地方都有用到填入表，對於網頁開發來說，填入表是將使用者的資訊，傳達到server端，之後由server端回傳相對應的資訊。

* ### &lt; form &gt;Tag

```html
<form action="" method="">

</form>
```

這是一個標準的&lt; form &gt; tag的寫法，上面的程式碼，並不會顯現任何東西，其實它是一個容器。

在&lt; form &gt; 這個 tag 裡面，我們會加入&lt; input &gt; 這個元素，這個元素就是填入格，填入格有許多種類，你可以在[MDN InputTypes](https://developer.mozilla.org/zh-TW/docs/Web/HTML/Element/input#Form_<input>_types)  
這邊看到有許多種類，我們常用的其實佔少數，所以也不用全部都背起來，下面是一個加入&lt; input &gt; 元素的例子。

```html
<form action="" method="">
        <input type="text" >
        <input type="password">
        <input type="date" >
        <input type="color">
        <input type="file">
        <input type="checkbox">
        <input type="radio">
        <input type="submit">
</form>
```

以下為對應的網頁顯示畫面。  
![](/assets/螢幕快照 2017-06-18 上午12.09.31.png)


* ### placeholder

```html
<form action="" method="">
        <input type="text" placeholder="使用者名稱">
        <input type="password" placeholder="密碼">
</form>
```

placeholder 是一個很常用的屬性，這個屬性可以產生一串提示字串，讓使用者可以明白這個格子需要填入哪些資訊。

以下為對應的網頁顯示畫面。  
![](/assets/螢幕快照 2017-06-18 上午12.37.34.png)

* ### action and method 屬性

這兩個屬性在前端開發中比較感受不到它們的存在，action 是把資料送到某個地方，method 則是指我們要使用哪一種方法去送。  
以下是一個例子：

```html
<form action="https://www.google.com" method="GET">
        <input type="text">
        <input type="submit">
</form>
```

你可以在文字編輯器中打入程式碼試試看，在 action 中我們通常把資料送到網頁的伺服器，網頁伺服器收到資訊之後，再回傳一些訊息，不過這個部分比較偏向後端，在後端教學中會有更詳細的介紹，這邊只是一個範例。

* ### name 屬性
name 屬性是將你的資料，取一個變數的名字，你可以用下面這個例子觀察變數的傳遞。

```html
<form action="http://www.wikipedia.com" action="GET">
		<input type="text" name="username">
		<input type="password" name="password">
		<input type="submit">
</form>
```
以下為對應的網頁顯示畫面：
![](/assets/1.png)
我們對這個表格輸入資訊：
![](/assets/2.png)
然後按提交：
![](/assets/3.png)

你可以發現瀏覽器的欄位裡面發生了一些變化，這代表我們確實有傳遞參數username 以及 password，這種格式為前面加上一個 ? 後面接變數名稱並且用＆隔開。

* ### &lt; label &gt;


* ### 小試身手

1.把上面的例子打在文字編輯器上面。  
2.用瀏覽器開啟來看\(建議使用google chrome\)。  
3.輸入一些資訊試試看。




### 單元總結

>



