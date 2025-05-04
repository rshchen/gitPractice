# html
超文本標記語言（英語：HyperText Markup Language，簡稱：HTML）是一種用於建立網頁的標準標記語言。HTML是一種基礎技術，常與CSS、JavaScript一起被眾多網站用於設計網頁、網頁應用程式以及行動應用程式的使用者介面。網頁瀏覽器可以讀取HTML檔案，並將其彩現成視覺化網頁。HTML描述了一個網站的結構語意隨著線索的呈現，使之成為一種標記語言而非程式語言。
## Easy Example
```html
<!DOCTYPE html>
<html lang="zh-tw">
    <head>
        <meta charset="utf-8" />
        <title>哈囉你好嗎</title>
      </head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```
## Elements元素
常用元素
|標籤|形容|
|-|-|
|`<p>`|paragraph|
|`<h1>`to`<h6>`|heading|
|`<br>`|line break|

## Attributes屬性
範例：
```html
<!DOCTYPE html>
<html lang="en-US">
<body>
    
<a href="https://www.w3schools.com">Visit W3Schools</a>
<img src="img_girl.jpg">
<img src="img_girl.jpg" width="500" height="600">
<img src="img_girl.jpg" alt="Girl with a jacket">
<p style="color:red;">This is a red paragraph.</p>
<p title="I'm a tooltip">This is a paragraph.</p>

</body>
</html>
```

常用屬性

| **HTML 屬性**       | **功能描述**                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **href 屬性**       | `<a>` 的 `href` 屬性指定了連結到的網頁 URL(用相對URL比較好)。                                |
| **src 屬性**        | `<img>` 的 `src` 屬性指定了顯示圖片的路徑。                                 |
| **width 和 height 屬性** | `<img>` 的 `width` 和 `height` 屬性為圖片提供大小資訊。                     |
| **alt 屬性**        | `<img>` 的 `alt` 屬性為圖片提供替代文字。                                   |
| **style 屬性**      | `style` 屬性用於為元素添加樣式，例如顏色、字體、大小等。                     |
| **lang 屬性**       | `<html>` 標籤的 `lang` 屬性聲明網頁的語言。                                |
| **title 屬性**      | `title` 屬性定義了元素的一些額外資訊。                                      |

* title屬性：`<p title="I'm a tooltip">This is a paragraph.</p>`
當游標移到元素的時候會用小方框顯示出額外資訊。