# Basic Tags 3

> 這個章節介紹 &lt; form &gt;、&lt; input &gt;、&lt; label &gt;。這些是構成一個表格所需的元素，網頁設計中，常會用到這些元素。

在還沒有網路的時代，其實人們就已經開始使用表格了，我們用固定格式的表格來填入所需的資訊，不過以前的表格都是用紙印出來的。在網頁中，我們也需要表格來幫助我們設計網頁，以下是一些常見的表格。

![](/assets/螢幕快照 2017-06-17 下午11.20.14.png)![](/assets/螢幕快照 2017-06-17 下午11.22.23.png)![](/assets/螢幕快照 2017-06-17 下午11.20.27.png)

我們在許多地方都有用到表格，對於網頁開發來說，表格是將使用者的資訊，傳達到server端，之後由server端回傳相對應的資訊。

* ### &lt; form &gt;Tag

```html
<form action="" method="">

</form>
```

這是一個標準的&lt; form &gt; tag的寫法，上面的程式碼，並不會顯現任何東西，其實它是一個容器。

在&lt; form &gt; 這個tag裡面，我們會加入&lt; input &gt; 這個元素，這個元素就是填入表格，填入表格有許多種類，你可以在[MDN InputTypes](https://developer.mozilla.org/zh-TW/docs/Web/HTML/Element/input#Form_<input>_types)  
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



