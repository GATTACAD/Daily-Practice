# Repository for test
**本仓库主要测试一些文档内容，仅为练习之用。**

- 百度搜索联想功能
    + bug 1 显示返回数据时联想栏的位置
    + 代码如下
```javascript
javascript
                   $("#search_suggest").show().css({
                        position: 'absolute',
                        top: $('#search_text').offset().top,
                        left: $('#search_text').offset().left
                        //width: $('#search_text').width()
                   });
```
- 运用 css3 添加一个旋转小箭头
