# Changelog
<!-- @author DHJT 2018-10-29 -->

-------------------------------------------------------------------------------------------------------------

### v2-1.0

#### 新特性
- `pdf.js`版本升级至`2.0.943`
    + 该版本中添加了左侧缩略图视图可以拉伸宽度进行多列查看
    + 对于语言设置，暂时还没有找到相应的方法
    + 更改在`viewer.js`中，在4500行:`userOptions['locale'] = 'zh-CN';`

-------------------------------------------------------------------------------------------------------------

### v1-1.1

#### 新特性
- 添加各种自定义方法
    + 页面初始化后方法：可以传入按钮数据来显示组件
    + 添加数据记录方法，将数据发送到后台
    + 更改pdf的文件源 实现动态刷新pdf而不更新pdfjs组件`changeSrc(url)`
    + 暂时IE无法打印`framePrint()`

-------------------------------------------------------------------------------------------------------------

### v1-1.0

#### 新特性
- 添加`pdf.js`web包<kbd>1.1.159</kbd>
- 添加本项目测试页面`viewer.jsp`
    + 添加中文设置`locale`
- 使用`pdf.js`的许可证：Apache-2.0
