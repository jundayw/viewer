## 简介

viewer 是一款 jQuery 插件，主要用于图像浏览插件。

## 演示
[DEMO](https://jundayw.github.io/viewer/viewer.html)

## 开发理念

简单、快速。

## 开使用方法

加载依赖库
```javascript
<script src="jQuery.js"></script>
```
加载本插件
```html
<link rel="stylesheet" href="jquery.viewer.min.css">
<script src="jquery.viewer.min.js"></script>
```
调用
```javascript
<script type="text/javascript">
$(function(){
	$("[rel-action=viewer]").each(function(){
		$(this).viewer($(this).data());
	});
});
</script>
```
HTML代码img标签的父元素添加 rel-action="viewer"
