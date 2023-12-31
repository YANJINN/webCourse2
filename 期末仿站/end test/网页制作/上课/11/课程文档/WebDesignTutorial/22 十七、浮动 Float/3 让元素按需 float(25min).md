从 `main` 和 `sidebar` 这样的命名就不难看出，文字区和广告区应该是一页两栏的分栏效果，此例中，确实做了 `main` 靠左 `sidebar` 靠右的两栏设计。因为各位已经成功的为休闲吧网站设置了分栏。请运用之前学习的只是，为 Starbuzz 更上一层楼。

## 3.1 步骤提示

1. 为浮动元素指定名称（已经完成了，需确认是 id 还是 class）；
2. 设置浮动元素的宽度，建议让 sidebar 定宽（280像素）；
3. 为了让 sidebar 向右浮动，又能和 main 平齐，请确认向右浮动元素在 HTML 中的位置；
4. 设置 float，完成元素的浮动。

```css
.sidebar {
  为了防止各位复制代码，请自行完成后，我再来添加此处的内容。
}
```

>[!question]
> 步骤 2 中让 sidebar 定宽，main 自动缩放。如果反过来 main 自动缩放，sidebar 定宽，哪个更好？
___


## 3.2 测试 Starbuzz

用浏览器打开更新后的页面，你会发现结果并不令人满意：

* `main` 和 `sidebar` 确实分成了两栏，但是视觉效果上并不像是分栏；
* 背景图像全都混在了一起；
* 如果缩小浏览器窗口， `main` 文字区内容，会出现在 `sidebar` 的下方，影响美观；
* 如果扩大浏览器窗口， `main` 文字区会变得很宽，和 `footer` 之间留下很大的空隙，影响美观；

>[!tip]
> 所以说，我们确实完成了浮动，实现了对页面元素的定位，但只会 float 是远远不够，没法实现“美观”的。接下来的课程，我们需要对细节进行更多的讨论。