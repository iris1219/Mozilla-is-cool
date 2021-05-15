# 作業 4 說明：

請修改 [What_will_your_website_look_like.html](https://github.com/iris1219/Mozilla-is-cool/blob/main/Getting_started_with_the_web/What_will_your_website_look_like.html) 檔案，
要加上下列調整：

1. 基本的 Html 架構包括 `html`、`head`、`body`、`title`
2. 「標題：你的網站看起來會是什麼樣子？」要用大標題的樣式。「首要：規劃」、「從頭設計」...等，要用章節標題樣式。
3. 「`#Firefox OS Guidelines 連結: http:......`」表示上個段落有個「`Firefox OS Guidelines`」要寫成超連結，請加上超連結的元素，並用「新開分頁」的方式。
4. 「`圖: https://mdn.mozillademos.org/files/9239/website-drawing-scan.png`」 表示這邊要插入圖片。
5. 所有 1, 2, 3... 這些步驟，要用 html 的列表元素表示。
6. 「注意：......」整個有藍色區塊的，請用 `<div class="note notecard"></div>` 包起來，粗體用 `<strong></strong>`。
7. 要呈現藍色區塊樣式，請把下列 Style 複製貼到 `<head></head>` 之間。

```html
<style>
.notecard.note {
    background-color: #dcf4ff;
}
.notecard {
    border-left: 6px solid #1e7f9d;
    margin: 0 0 24px;
    padding: 12px;
}
</style>
```

結果參考：[你的網站看起來會是什麼樣子？ - 學習該如何開發 Web | MDN](https://developer.mozilla.org/zh-TW/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)

完成修改並 Commit 後可到這邊看成果：
https://iris1219.github.io/Mozilla-is-cool/Getting_started_with_the_web/What_will_your_website_look_like.html
