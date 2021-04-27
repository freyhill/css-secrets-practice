# charpter 1
* 合理使用简写，比如background 而不是background-color，因为background-image可能会对background有影响
* :root 这个 CSS 伪类匹配文档树的根元素。对于 HTML 来说，:root 表示 <html> 元素，除了优先级更高之外，与 html 选择器相同。
```
:root{
    color: #333;
    --h5-fontsize: 30px;
    --theme-color: red;
}
.title{
    color: var(--theme-color);
}
.content{
    color: var(--theme-color);
}
```

# chapter2 
* background-clip属性初始值为border-box 意味着背景会侵入到border，若不希望背景侵入border则设置为 padding-box
