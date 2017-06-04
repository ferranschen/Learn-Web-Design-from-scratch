### Basic HTML

> 這個章節介紹基本HTML 語法，並實作完整的HTML網站。

### 首先，HTML的本質是什麼?

* 嚴格來說，HTML不算是程式語言，而是一種標記語言。

* HTML 是 Hyper Text Markup Language 的縮寫。

* HTML 的元素 （elements）是 HTML 網頁的基礎單位。

* HTML 的元素 （elements）由標籤（tag）與內容\(content\)組成。

* HTML 的標籤（tags）可以標示：文章、標題、表格...等。

* 瀏覽器不會直接把HTML程式碼印出來，而是經過解讀之後，再根據標籤的型態去顯現內容。

---

* ### HTML元素

一個元素是由標籤跟內容所構成的

```html
<標籤>內容</標籤>

ex:
<h1>自我介紹</h1>
<p>我的名字叫做王大明。</p>
```

前面的標籤是起始標籤，後面的標籤稱為結束標籤（多加一個斜線）。

---

* ### HTML 註解

```html
<!-- 註解是用來幫助讀者來瞭解程式的邏輯 -->
<!-- 註解並不會被執行 -->
```

---

* ### 一個標準的HTML檔案

```html
<!DOCTYPE html>
<html>
<head>
<title>網頁標題</title>
</head>
<body>
<h1>內文標題</h1>
<p>文章段落</p>

</body>
</html>
```

* 這是一個標準的格式，不用死記，因為以後常會看到。
* DOCTYPE 告訴瀏覽器，這個檔案是哪一種檔案，此例為：html。
* 除了 DOCTYPE 之外，所有的元素都是起始標籤＋結束標籤構成的。
* html 檔案中，有head及body，在head 裡面，我們會放metadada\(現在先不用瞭解\)。在body裡面，我們會放網站的內容。

---

* ### 小試身手

```html
<!DOCTYPE html>
<html>
<head>
<title>My first page</title>
</head>
<body>
<h1>My first heading</h1>
<p>Hello, This is my first page.</p>

</body>
</html>
```

* 將上述的程式碼打入你的文字編輯器。
* 以“first.html”的檔名存檔。
* 點擊兩下“first.html”開啟檔案，或是將檔案拖曳到瀏覽器打開。
* 更改h1, p 或是 title 等元素中的內容，存檔之後，再把它放到瀏覽器上，觀察有什麼變化。

---
<br/>
恭喜你！你已經會寫一個格式正確的HTML檔案了，你可以發現撰寫 HTML 其實不會很困難，下個章節裡，我們會詳細幾個介紹基本常見的標籤。



