[1. 规范目的](#1-规范目的)<br>[2. 基本原则](#2-基本原则)<br>&emsp;[2.1 结构、样式、行为分离 (A)](#21-结构样式行为分离-a)<br>&emsp;[2.2 缩进 (A)](#22-缩进-a)<br>&emsp;[2.3 文件编码 (A)](#23-文件编码-a)<br>&emsp;[2.4 一律使用小写字母 (A)](#24-一律使用小写字母-a)<br>&emsp;[2.5 省略外链资源 URL 协议部分 (A)](#25-省略外链资源-url-协议部分-a)<br>[3. HTML](#3-html)<br>&emsp;[3.1 通用约定](#31-通用约定)<br>&emsp;&emsp;[3.1.1 标签 (B)](#311-标签-b)<br>&emsp;&emsp;[3.1.2 Class 与 ID (A)](#312-class-与-id-a)<br>&emsp;&emsp;[3.1.3 属性顺序 (A)](#313-属性顺序-a)<br>&emsp;&emsp;[3.1.4 引号 (A)](#314-引号-a)<br>&emsp;&emsp;[3.1.5 嵌套 (A)](#315-嵌套-a)<br>&emsp;&emsp;[3.1.6 布尔值属性 (A)](#316-布尔值属性-a)<br>&emsp;[3.2 语义化](#32-语义化)<br>&emsp;&emsp;[3.2.1 常见标签语义 (B)](#321-常见标签语义-(B))<br>&emsp;&emsp;[3.2.2 示例 (B)](#322-示例-(B))<br>&emsp;[3.3 HEAD](#33-head)<br>&emsp;&emsp;[3.3.1 文档类型 (A)](#331-文档类型-a)<br>&emsp;&emsp;[3.3.2 语言属性 (C)](#332-语言属性-c)<br>&emsp;&emsp;[3.3.3 字符编码  (A)](#333-字符编码--a)<br>&emsp;&emsp;[3.3.4 IE 兼容模式 (A)](#334-ie-兼容模式-a)<br>&emsp;&emsp;[3.3.5 SEO 优化 (C)](#335-seo-优化-c)<br>&emsp;&emsp;[3.3.6 viewport (C)](#336-viewport-c)<br>&emsp;&emsp;[3.3.7 iOS 图标 (B)](#337-ios-图标-b)<br>&emsp;&emsp;[3.3.8 favicon (A)](#338-favicon-a)<br>&emsp;&emsp;[3.3.9 HEAD 模板 (B)](#339-head-模板-b)<br>[4 CSS](#4-css)<br>&emsp;[4.1 通用约定](#41-通用约定)<br>&emsp;&emsp;[4.1.1 样式表文件命名 (B)](#411-样式表文件命名-b)<br>&emsp;&emsp;[4.1.2 代码组织 Class 和 ID (B)](#412-代码组织-class-和-id-b)<br>&emsp;&emsp;[4.1.3 Class 和 ID (C)](#413-class-和-id-c)<br>&emsp;&emsp;[4.1.4 声明块格式 (A)](#414-声明块格式-a)<br>&emsp;&emsp;[4.1.5 声明顺序 (B)](#415-声明顺序-b)<br>&emsp;&emsp;[4.1.6 引号使用 (B)](#416-引号使用-b)<br>&emsp;&emsp;[4.1.7 媒体查询（Media query）的位置 (C)](#417-媒体查询media-query的位置-c)<br>&emsp;&emsp;[4.1.8 不要使用 @import (C)](#418-不要使用-import-c)<br>&emsp;&emsp;[4.1.9 链接的样式顺序 (C)](#419-链接的样式顺序-c)<br>&emsp;&emsp;[4.1.10 字体规则 (A)](#4110-字体规则-a)<br>&emsp;[4.2 LESS](#42-less)<br>&emsp;&emsp;[4.2.1 代码组织 (B)](#421-代码组织-b)<br>&emsp;&emsp;[4.2.2 @import 语句 (A)](#422-import-语句-(A))<br>&emsp;&emsp;[4.2.3 混入（Mixin）(B)](#423-混入mixinb)<br>&emsp;&emsp;[4.2.4 避免嵌套层级过多 (C)](#424-避免嵌套层级过多-c)<br>&emsp;&emsp;[4.2.5 字符串插值 (C)](#425-字符串插值-(C))<br>&emsp;[4.3 性能优化](#43-性能优化)<br>&emsp;&emsp;[4.3.1 慎重选择高消耗的样式 (C)](#431-慎重选择高消耗的样式-c)<br>&emsp;&emsp;[4.3.2 避免过分重排 (C)](#432-避免过分重排-c)<br>&emsp;&emsp;[4.3.3 正确使用 Display 的属性 (C)](#433-正确使用-display-的属性-c)<br>&emsp;&emsp;[4.3.4 不滥用 float (C)](#434-不滥用-float-c)<br>&emsp;&emsp;[4.3.5 动画性能优化 (C)](#435-动画性能优化-c)<br>&emsp;&emsp;[4.3.6 多利用硬件能力，如通过 3D 变形开启 GPU 加速 (C)](#436-多利用硬件能力如通过-3d-变形开启-gpu-加速-c)<br>&emsp;&emsp;[4.3.7 提升 CSS 选择器性能](#437-提升-css-选择器性能)<br>[5 JavaScript](#5-javascript)<br>&emsp;[5.1 通用约定](#51-通用约定)<br>&emsp;&emsp;[5.1.1 注释 (B)](#511-注释-b)<br>&emsp;&emsp;[5.1.2 命名 (B)](#512-命名-b)<br>&emsp;&emsp;[5.1.3 命名语法 (B)](#513-命名语法-b)<br>&emsp;&emsp;[5.1.4 接口命名规范 (B)](#514-接口命名规范-b)<br>&emsp;&emsp;[5.1.5 True 和 False 布尔表达式  (B)](#515-true-和-false-布尔表达式--b)<br>&emsp;&emsp;[5.1.6 不要在 Array 上使用 for-in 循环 (A)](#516-不要在-array-上使用-for-in-循环-(A))<br>&emsp;&emsp;[5.1.7 二元和三元操作符 (A)](#517-二元和三元操作符-a)<br>&emsp;&emsp;[5.1.8 条件(三元)操作符 (?:) (B)](#518-条件三元操作符--b)<br>&emsp;&emsp;[5.1.9 && 和 || (B)](#519--和--b)<br>&emsp;[5.2 jQuery 规范](#52-jquery-规范)<br>&emsp;&emsp;[5.2.1 使用最新版本的 jQuery (C)](#521-使用最新版本的-jquery-c)<br>&emsp;&emsp;[5.2.2 jQuery 变量 (A)](#522-jquery-变量-a)<br>&emsp;&emsp;[5.2.3	选择器 (B)](#523-选择器-b)<br>&emsp;&emsp;[5.2.4	DOM 操作 (B)](#524-dom-操作-(B))<br>&emsp;&emsp;[5.2.5 事件 (B)](#525-事件-b)<br>&emsp;&emsp;[5.2.6 链式写法 (B)](#526-链式写法-b)<br>&emsp;&emsp;[5.2.7 其他 (C)](#527-其他-c)<br>&emsp;&emsp;[5.2.8 jQuery 插件模板 (C)](#528-jquery-插件模板-c)<br>&emsp;[5.3 性能优化](#53-性能优化)<br>&emsp;&emsp;[5.3.1 避免不必要的 DOM 操作 (B)](#531-避免不必要的-dom-操作-b)<br>&emsp;&emsp;[5.3.2 缓存数组长度  (C)](#532-缓存数组长度--c)<br>&emsp;&emsp;[5.3.3 异步加载第三方内容  (A)](#533-异步加载第三方内容--a)

## 1. 规范目的
为了提高工作效率，便于后台人员添加功能及前端后期优化维护，输出高质量的文档，在平台建设中，使结构更加清晰，代码简明有序，有一个更好的前端架构。<br>
规范基本准则：符合web标准，使用具有语义的标签，使结构、表现、行为分离，兼容性优良。页面性能优化，代码简洁、明了、有序，尽可能的减少服务器的负载，保证最快的解析速度。

## 2. 基本原则
### 2.1 结构、样式、行为分离 (A)
确保文档和模板只包含 HTML 结构，样式都放到样式表里，行为都放到脚本里。
### 2.2 缩进 (A)
统一两个空格缩进（总之缩进统一即可），不要使用 Tab 或者 Tab、空格混搭（使用统一的代码编辑器并设置相同的编辑配置也可）。
### 2.3 文件编码 (A)
使用不带 BOM 的 UTF-8 编码。
- 在 HTML中指定编码 <meta charset="utf-8"> ；
-	无需使用 @charset 指定样式表的编码，它默认为 UTF-8 （参考 @charset）；
### 2.4 一律使用小写字母 (A)

``` html
<!-- Recommended -->
<img src="google.png" alt="Google">

<!-- Not recommended -->
<A HREF="/">Home</A>
```

``` css
/* Recommended */
color: #e5e5e5;

/* Not recommended */
color: #E5E5E5;
```

### 2.5 省略外链资源 URL 协议部分 (A)
省略外链资源（图片及其它媒体资源）URL 中的 http / https 协议，使 URL 成为相对地址，避免Mixed Content 问题，减小文件字节数。
其它协议（ftp 等）的 URL 不省略。

``` html
<!-- Recommended -->
<script src="//www.google.com/js/gweb/analytics/autotrack.js"></script>

<!-- Not recommended -->
<script src="http://www.google.com/js/gweb/analytics/autotrack.js"></script>
```

``` css
/* Recommended */
.example {
  background: url(//www.google.com/images/example);
}

/* Not recommended */
.example {
  background: url(http://www.google.com/images/example);
}
```

## 3. HTML
尽量遵循 HTML 标准和语义，但是不要以牺牲实用性为代价。任何时候都要尽量使用最少的标签并保持最小的复杂度。
### 3.1 通用约定
#### 3.1.1 标签 (B)
-	自闭合（self-closing）标签，无需闭合 ( 例如： `<img>` `<input>` `<br>` `<hr>` 等 )
-	可选的闭合标签（closing tag），需闭合 ( 例如：`</li>` 或 `</body>` )
-	尽量减少标签数量

``` html
<img src="images/google.png" alt="Google">
<input type="text" name="title">
```

``` html
<ul>
  <li>Style</li>
  <li>Guide</li>
</ul>
```

``` html
<!-- Not recommended -->
<span class="avatar">
  <img src="...">
</span>

<!-- Recommended -->
<img class="avatar" src="...">
```

#### 3.1.2 Class 与 ID (A)
- class 应以功能或内容命名，不以表现形式命名
- class 与 id 单词字母小写，多个单词组成时，采用中划线-分隔
- 使用唯一的 id 作为 Javascript hook, 同时避免创建无样式信息的 class

``` html
<!-- Not recommended -->
<div class="j-hook left contentWrapper"></div>

<!-- Recommended -->
<div id="j-hook" class="sidebar content-wrapper"></div>
```

#### 3.1.3 属性顺序 (A)
HTML 属性应该按照特定的顺序出现以保证易读性。<br>
id > class > name >	data-xxx > src, for, type, href >	title > alt > aria-xxx > role
``` html
<a id="..." class="..." data-modal="toggle" href="###"></a>

<input class="form-control" type="text">

<img src="..." alt="...">
```
#### 3.1.4 引号 (A)
属性的定义，统一使用双引号。
``` html
<!-- Not recommended -->
<span id='j-hook' class=text>Google</span>

<!-- Recommended -->
<span id="j-hook" class="text">Google</span>
```

#### 3.1.5 嵌套 (A)
a 不允许嵌套 div 这种约束属于语义嵌套约束，与之区别的约束还有严格嵌套约束，比如a 不允许嵌套 a。
严格嵌套约束在所有的浏览器下都不被允许；而语义嵌套约束，浏览器大多会容错处理，生成的文档树可能相互不太一样。
语义嵌套约束
-	`<li>` 用于 `<ul>` 或 `<ol>` 下；
-	`<dd>`, `<dt>` 用于 `<dl>` 下；
- `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<td>` 用于 `<table>` 下；
严格嵌套约束
-	inline-Level 元素，仅可以包含文本或其它 inline-Level 元素;
-	`<a>`里不可以嵌套交互式元素`<a>、<button>、<select>`等;
-	`<p>`里不可以嵌套块级元素`<div>、<h1>~<h6>、<p>、<ul>/<ol>/<li>、<dl>/<dt>/<dd>、<form>`等。
更多详情，参考WEB标准系列-HTML元素嵌套
#### 3.1.6 布尔值属性 (A)
HTML5 规范中 disabled、checked、selected 等属性不用设置值。
``` html
<input type="text" disabled>

<input type="checkbox" value="1" checked>

<select>
  <option value="1" selected>1</option>
</select>
```

### 3.2 语义化
没有 CSS 的 HTML 是一个语义系统而不是 UI 系统。<br>
通常情况下，每个标签都是有语义的。<br>
此外语义化的 HTML 结构，有助于机器（搜索引擎）理解，另一方面多人协作时，能迅速了解开发者意图。<br>
#### 3.2.1 常见标签语义 (B)
 标签 | 语义 | 标签 | 语义 
 --- | --- | --- | --- 
 `<p>` | 段落 | `<h1> <h2> <h3>` |	标题
`<ul>` |	无序列表 | `<blockquote>`	|大段引用
`<ol>` |	有序列表 | `<cite>`	| 一般引用
`<b>`	| 为样式加粗而加粗 | `<i>` | 为样式倾斜而倾斜
`<strong>` | 为强调内容而加粗 | `<em>` | 为强调内容而倾斜
`<code>` | 代码标识 | `<abbr>` | 缩写

#### 3.2.2 示例 (B)
将你构建的页面当作一本书，将标签的语义对应的其功能和含义
-	书的名称：`<h1>`
-	书的每个章节标题: `<h2>`
-	章节内的文章标题: `<h3>`
-	小标题/副标题: `<h4> <h5> <h6>`
-	章节的段落: `<p>`

### 3.3 HEAD
#### 3.3.1 文档类型 (A)
为每个 HTML 页面的第一行添加标准模式（standard mode）的声明， 这样能够确保在每个浏览器中拥有一致的表现。
``` html
<!DOCTYPE html>
```

#### 3.3.2 语言属性 (C)
为什么使用 lang="zh-cmn-Hans" 而不是我们通常写的 lang="zh-CN" 呢? 请参考知乎上的讨论: 网页头部的声明应该是用 lang="zh" 还是 lang="zh-cn"？
``` html
<!-- 中文（直接用这个就好了） --> 
<html lang="zh-Hans">

<!-- 简体中文 -->
<html lang="zh-cmn-Hans">

<!-- 繁体中文 -->
<html lang="zh-cmn-Hant">

<!-- English -->
<html lang="en">
```

#### 3.3.3 字符编码  (A)
- 以无 BOM 的 utf-8 编码作为文件格式
-	指定字符编码的 meta 必须是 head 的第一个直接子元素
``` html
<html>
  <head>
    <meta charset="utf-8">
    ......
  </head>
  <body>
    ......
  </body>
</html>
```

#### 3.3.4 IE 兼容模式 (A)
优先使用最新版本的IE 和 Chrome 内核
``` html
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
```

#### 3.3.5 SEO 优化 (C)
``` html
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <!-- SEO -->
    <title>Style Guide</title>
    <meta name="keywords" content="your keywords">
    <meta name="description" content="your description">
    <meta name="author" content="author,email address">
</head>
```

#### 3.3.6 viewport (C)
-	viewport: 一般指的是浏览器窗口内容区的大小，不包含工具条、选项卡等内容
-	width: 浏览器宽度，输出设备中的页面可见区域宽度
-	device-width: 设备分辨率宽度，输出设备的屏幕可见宽度
-	initial-scale: 初始缩放比例
-	maximum-scale: 最大缩放比例

**当需要为移动端设备作优化，设置可见区域的宽度和初始缩放比例为必须项。**
``` html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
#### 3.3.7 iOS 图标 (B)
-	apple-touch-icon 图片自动处理成圆角和高光等效果
-	apple-touch-icon-precomposed 禁止系统自动添加效果，直接显示设计原图
``` html
<!-- iPhone 和 iTouch，默认 57x57 像素，必须有 -->
<link rel="apple-touch-icon-precomposed" href="/apple-touch-icon-57x57-precomposed.png">

<!-- iPad，72x72 像素，可以没有，但推荐有 -->
<link rel="apple-touch-icon-precomposed" href="/apple-touch-icon-72x72-precomposed.png" sizes="72x72">

<!-- Retina iPhone 和 Retina iTouch，114x114 像素，可以没有，但推荐有 -->
<link rel="apple-touch-icon-precomposed" href="/apple-touch-icon-114x114-precomposed.png" sizes="114x114">

<!-- Retina iPad，144x144 像素，可以没有，但推荐有 -->
<link rel="apple-touch-icon-precomposed" href="/apple-touch-icon-144x144-precomposed.png" sizes="144x144">
```
#### 3.3.8 favicon (A)
在未指定 favicon 时，大多数浏览器会请求 Web Server 根目录下的 favicon.ico 。为了保证 favicon 可访问，避免404，必须遵循以下两种方法之一：
-	在 Web Server 根目录放置 favicon.ico 文件
-	使用 link 指定 favicon
``` html
<link rel="shortcut icon" href="path/to/favicon.ico">
```

#### 3.3.9 HEAD 模板 (B)
``` html
<!DOCTYPE html>
<html lang="zh-cmn-Hans">
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <title>Style Guide</title>
    <meta name="description" content="不超过150个字符">
    <meta name="keywords" content="">
    <meta name="author" content="name, email@gmail.com">

    <!-- 为移动设备添加 viewport -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- iOS 图标 -->
    <link rel="apple-touch-icon-precomposed" href="/apple-touch-icon-57x57-precomposed.png">

    <link rel="alternate" type="application/rss+xml" title="RSS" href="/rss.xml" />
    <link rel="shortcut icon" href="path/to/favicon.ico">
</head>
```
## 4 CSS
### 4.1 通用约定
#### 4.1.1 样式表文件命名 (B)
- 主要的 master.css
- 模块 module.css
- 基本共用 base.css
- 布局、版面 layout.css
- 主题 themes.css
- 专栏 columns.css
- 文字 font.css
- 表单 forms.css
- 补丁 mend.css
- 打印 print.css

#### 4.1.2 代码组织 Class 和 ID (B)
- 以组件为单位组织代码段
- 制定一致的注释规范
- 组件块和子组件块以及声明块之间使用一空行分隔，子组件块之间三空行分隔
- 如果使用了多个 CSS 文件，将其按照组件而非页面的形式分拆，因为页面会被重组，而组件只会被移动<br>

良好的注释是非常重要的。请留出时间来描述组件（component）的工作方式、局限性和构建它们的方法。不要让你的团队其它成员 来猜测一段不通用或不明显的代码的目的。<br>
**提示：通过配置编辑器，可以提供快捷键来输出一致认可的注释模式。**
``` css
/* ==========================================================================
   组件块
 ============================================================================ */

/* 子组件块
 ============================================================================ */
.selector {
  padding: 15px;
  margin-bottom: 15px;
}



/* 子组件块
 ============================================================================ */
.selector-secondary {
  display: block; /* 注释*/
}

.selector-three {
  display: span;
}
```

#### 4.1.3 Class 和 ID (C)
- 使用语义化、通用的命名方式
- 使用连字符 - 作为 ID、Class 名称界定符，不要驼峰命名法和下划线
- 避免选择器嵌套层级过多，尽量少于 3 级
- 避免选择器和 Class、ID 叠加使用
元素选择器和 ID、Class 混合使用也违反关注分离原则。如果HTML标签修改了，就要再去修改 CSS 代码，不利于后期维护。
``` css
/* Not recommended */
.red {}
.box_green {}
.page .header .login #username input {}
ul#example {}

/* Recommended */
#nav {}
.box-video {}
#username input {}
#example {}
```

#### 4.1.4 声明块格式 (A)
- 选择器分组时，保持独立的选择器占用一行
- 声明块的左括号 { 前添加一个空格
- 声明块的右括号 } 应单独成行
- 声明语句中的 : 后应添加一个空格
- 声明语句应以分号 ; 结尾
- 一般以逗号分隔的属性值，每个逗号后应添加一个空格
- rgb()、rgba()、hsl()、hsla() 或 rect() 括号内的值，逗号分隔，但逗号后不添加一个空格
- 对于属性值或颜色参数，省略小于 1 的小数前面的 0 （例如，.5 代替 0.5；-.5px 代替-0.5px）
- 十六进制值应该全部小写和尽量简写，例如，#fff 代替 #ffffff
- 避免为 0 值指定单位，例如，用 margin: 0; 代替 margin: 0px;
``` css
/*  Not recommended  */
.selector, .selector-secondary, .selector[type=text] {
  padding:15px;
  margin:0px 0px 15px;
  background-color:rgba(0, 0, 0, 0.5);
  box-shadow:0px 1px 2px #CCC,inset 0 1px 0 #FFFFFF
}

/* Recommended */
.selector,
.selector-secondary,
.selector[type="text"] {
  padding: 15px;
  margin-bottom: 15px;
  background-color: rgba(0,0,0,.5);
  box-shadow: 0 1px 2px #ccc, inset 0 1px 0 #fff;
}
```
 
#### 4.1.5 声明顺序 (B)
相关属性应为一组，推荐的样式编写顺序
1.	Positioning
2.	Box model
3.	Typographic
4.	Visual

由于定位（positioning）可以从正常的文档流中移除元素，并且还能覆盖盒模型（box model）相关的样式，因此排在首位。盒模型决定了组件的尺寸和位置，因此排在第二位。
其他属性只是影响组件的内部（inside）或者是不影响前两组属性，因此排在后面。
``` css
.declaration-order {
  /* Positioning */
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 100;

  /* Box model */
  display: block;
  box-sizing: border-box;
  width: 100px;
  height: 100px;
  padding: 10px;
  border: 1px solid #e5e5e5;
  border-radius: 3px;
  margin: 10px;
  float: right;
  overflow: hidden;

  /* Typographic */
  font: normal 13px "Helvetica Neue", sans-serif;
  line-height: 1.5;
  text-align: center;

  /* Visual */
  background-color: #f5f5f5;
  color: #fff;
  opacity: .8;

  /* Other */
  cursor: pointer;
}
```
 
#### 4.1.6 引号使用 (B)
url() 、属性选择符、属性值使用双引号。 参考 Is quoting the value of url() really necessary?
``` css
/* Not recommended */
@import url(//www.google.com/css/maia.css);

html {
  font-family: 'open sans', arial, sans-serif;
}

/* Recommended */
@import url("//www.google.com/css/maia.css");

html {
  font-family: "open sans", arial, sans-serif;
}

.selector[type="text"] {

}
```

#### 4.1.7 媒体查询（Media query）的位置 (C)
将媒体查询放在尽可能相关规则的附近。不要将他们打包放在一个单一样式文件中或者放在文档底部。如果你把他们分开了，将来只会被大家遗忘。

``` css
.element { ... }
.element-avatar { ... }
.element-selected { ... }

@media (max-width: 768px) {
  .element { ...}
  .element-avatar { ... }
  .element-selected { ... }
}
```

#### 4.1.8 不要使用 @import (C)
与 <link> 相比，@import 要慢很多，不光增加额外的请求数，还会导致不可预料的问题。
替代办法：
- 使用多个 元素
- 通过 Sass 或 Less 类似的 CSS 预处理器将多个 CSS 文件编译为一个文件
- 其他 CSS 文件合并工具

参考 don’t use @import

#### 4.1.9 链接的样式顺序 (C)
a:link -> a:visited -> a:hover -> a:active

#### 4.1.10 字体规则 (A)
为了防止文件合并及编码转换时造成问题，建议将样式中文字体名字改成对应的英文名字
 
### 4.2 LESS
#### 4.2.1 代码组织 (B)
代码按以下顺序组织：
1.	@import
2.	变量声明
3.	样式声明

``` css
@import "mixins/size.less";

@default-text-color: #333;

.page {
  width: 960px;
  margin: 0 auto1;
}
```

#### 4.2.2 @import 语句 (A)
@import 语句引用的文需要写在一对双引号内，.less 后缀不得省略。
``` css
/* Not recommended */
@import "mixins/size";
@import 'mixins/grid.less';

/* Recommended */
@import "mixins/size.less";
@import "mixins/grid.less";
```

#### 4.2.3 混入（Mixin）(B)
1.	在定义 mixin 时，如果 mixin 名称不是一个需要使用的 className，必须加上括号，否则即使不被调用也会输出到 CSS 中。
2.	如果混入的是本身不输出内容的 mixin，需要在 mixin 后添加括号（即使不传参数），以区分这是否是一个 className。
``` css
/* Not recommended */
.big-text {
  font-size: 2em;
}

h3 {
  .big-text;
  .clearfix;
}

/* Recommended */
.big-text() {
  font-size: 2em;
}

h3 {
  .big-text(); /* 1 */
  .clearfix(); /* 2 */
}
```

#### 4.2.4 避免嵌套层级过多 (C)
- 将嵌套深度限制在2级。对于超过3级的嵌套，给予重新评估。这可以避免出现过于详实的CSS选择器。
- 避免大量的嵌套规则。当可读性受到影响时，将之打断。推荐避免出现多于20行的嵌套规则出现。

#### 4.2.5 字符串插值 (C)
变量可以用类似ruby和php的方式嵌入到字符串中，像@{name}这样的结构:
```css
base-url: "http://assets.fnord.com"; 
background-image: url("@{base-url}/images/bg.png");
```

### 4.3 性能优化
#### 4.3.1 慎重选择高消耗的样式 (C)
高消耗属性在绘制前需要浏览器进行大量计算：
- box-shadows
- border-radius
- transparency
- transforms
- CSS filters（性能杀手）

#### 4.3.2 避免过分重排 (C)
当发生重排的时候，浏览器需要重新计算布局位置与大小，更多详情。
常见的重排元素:
- width
- height
- padding
- margin
- display
- border-width
- position
- top
- left
- right
- bottom
- font-size
- float
- text-align
- overflow-y
- font-weight
- overflow
- font-family
- line-height
- vertical-align
- clear
- white-space
- min-height

#### 4.3.3 正确使用 Display 的属性 (C)
Display 属性会影响页面的渲染，请合理使用。
-	display: inline后不应该再使用 width、height、margin、padding 以及 float
-	display: inline-block 后不应该再使用 float
-	display: block 后不应该再使用 vertical-align
-	display: table-* 后不应该再使用 margin 或者 float

#### 4.3.4 不滥用 float (C)
float在渲染时计算量比较大，尽量减少使用。

#### 4.3.5 动画性能优化 (C)
动画的实现原理，是利用了人眼的“视觉暂留”现象，在短时间内连续播放数幅静止的画面，使肉眼因视觉残象产生错觉，而误以为画面在“动”。
动画的基本概念：
- 帧：在动画过程中，每一幅静止画面即为一“帧”
- 帧率：即每秒钟播放的静止画面的数量，单位是fps(Frame per second)
- 帧时长：即每一幅静止画面的停留时间，单位一般是ms(毫秒)
- 跳帧(掉帧/丢帧)：在帧率固定的动画中，某一帧的时长远高于平均帧时长，导致其后续数帧被挤压而丢失的现象
一般浏览器的渲染刷新频率是 60 fps，所以在网页当中，帧率如果达到 50-60 fps 的动画将会相当流畅，让人感到舒适
- 如果使用基于 javaScript 的动画，尽量使用 requestAnimationFrame. 避免使用 setTimeout, setInterval
- 避免通过类似 jQuery animate()-style 改变每帧的样式，使用 CSS 声明动画会得到更好的浏览器优化
- 使用 translate 取代 absolute 定位就会得到更好的 fps，动画会更顺滑
 
#### 4.3.6 多利用硬件能力，如通过 3D 变形开启 GPU 加速 (C)
一般在 Chrome 中，3D或透视变换（perspective transform）CSS属性和对 opacity 进行 CSS 动画会创建新的图层，在硬件加速渲染通道的优化下，GPU 完成 3D 变形等操作后，将图层进行复合操作（Compesite Layers），从而避免触发浏览器大面积重绘和重排。
注：3D 变形会消耗更多的内存和功耗。
使用 translate3d 右移 500px 的动画流畅度要明显优于直接使用 left：
``` css
.ball-1 {
  transition: -webkit-transform .5s ease;
  -webkit-transform: translate3d(0, 0, 0);
}
.ball-1.slidein{
  -webkit-transform: translate3d(500px, 0, 0);
}
.ball-2 {
  transition: left .5s ease; left：0;
}
.ball-2.slidein {
  left：500px;
}
```

#### 4.3.7 提升 CSS 选择器性能 
CSS 选择器对性能的影响源于浏览器匹配选择器和文档元素时所消耗的时间，所以优化选择器的原则是应尽量避免使用消耗更多匹配时间的选择器。而在这之前我们需要了解 CSS 选择器匹配的机制， 如子选择器规则：
``` css
header > a {font-weight:blod;}
```

我们中的大多数人都是从左到右的阅读习惯，会习惯性的设定浏览器也是从左到右的方式进行匹配规则，推测这条规则的开销并不高。
我们会假设浏览器以这样的方式工作：寻找 id 为 header 的元素，然后将样式规则应用到直系子元素中的 a 元素上。我们知道文档中只有一个 id 为 header 的元素，并且它只有几个 a 元素的子节点，所以这个 CSS 选择器应该相当高效。
事实上，却恰恰相反，CSS 选择器是从右到左进行规则匹配。了解这个机制后，例子中看似高效的选择器在实际中的匹配开销是很高的，浏览器必须遍历页面中所有的 a 元素并且确定其父元素的 id 是否为 header 。
如果把例子的子选择器改为后代选择器则会开销更多，在遍历页面中所有 a 元素后还需向其上级遍历直到根节点。
``` css
header  a {font-weight:blod;}
```

理解了CSS选择器从右到左匹配的机制后，明白只要当前选择符的左边还有其他选择符，样式系统就会继续向左移动，直到找到和规则匹配的选择符，或者因为不匹配而退出。我们把最右边选择符称之为关键选择器。

1、避免使用通用选择器 (B)

``` css
/* Not recommended */
.content * {color: red;}
```
浏览器匹配文档中所有的元素后分别向上逐级匹配 class 为 content 的元素，直到文档的根节点。因此其匹配开销是非常大的，所以应避免使用关键选择器是通配选择器的情况。

2、避免使用标签或 class 选择器限制 id 选择器 (A)

``` css
/* Not recommended */
button #backButton {…}
/* Recommended */
#newMenuIcon {…}
```

3、避免使用标签限制 class 选择器 (B)
``` css
/* Not recommended */
treecell.indented {…}
/* Recommended */
.treecell-indented {…}
/* Much to recommended */
.hierarchy-deep {…}
```

4、避免使用多层标签选择器。使用 class 选择器替换，减少css查找 (B)
``` css
/* Not recommended */
treeitem[mailfolder="true"] > treerow > treecell {…}
/* Recommended */
.treecell-mailfolder {…}
```

5、避免使用子选择器 (B)
``` css
/* Not recommended */
treehead treerow treecell {…}
/* Recommended */
treehead > treerow > treecell {…}
/* Much to recommended */
.treecell-header {…}
```

6、使用继承 (B)
``` css
/* Not recommended */
#bookmarkMenuItem > .menu-left { list-style-image: url(blah) }
/* Recommended */
#bookmarkMenuItem { list-style-image: url(blah) }
```

## 5 JavaScript
### 5.1 通用约定
#### 5.1.1 注释 (B)
原则
- As short as possible（如无必要，勿增注释）：尽量提高代码本身的清晰性、可读性。
- As long as necessary（如有必要，尽量详尽）：合理的注释、空行排版等，可以让代码更易阅读、更具美感。

单行注释<br>
必须独占一行。// 后跟一个空格，缩进与下一行被注释说明的代码一致。

多行注释<br>
避免使用 /*...*/ 这样的多行注释。有多行注释内容时，使用多个单行注释。

函数/方法注释<br>
1.	函数/方法注释必须包含函数说明，有参数和返回值时必须使用注释标识
2.	参数和返回值注释必须包含类型信息和说明
3.	当函数是内部函数，外部不可访问时，可以使用 @inner 标识

``` js
/**
 * 函数描述
 *
 * @param {string} p1 参数1的说明
 * @param {string} p2 参数2的说明，比较长
 *     那就换行了.
 * @param {number=} p3 参数3的说明（可选）
 * @return {Object} 返回值描述
 */
function foo(p1, p2, p3) {
    var p3 = p3 || 10;
    return {
        p1: p1,
        p2: p2,
        p3: p3
    };
}
```

文件注释<br>
文件注释用于告诉不熟悉这段代码的读者这个文件中包含哪些东西。 应该提供文件的大体内容, 它的作者, 依赖关系和兼容性信息。如下:
``` js
/**
 * @fileoverview Description of file, its uses and information
 * about its dependencies.
 * @author user@meizu.com (Firstname Lastname)
 * Copyright 2009 Meizu Inc. All Rights Reserved.
 */
```
#### 5.1.2 命名 (B)
变量，使用 Camel 命名法。
``` js
var loadingModules = {};
```

私有属性、变量和方法以下划线 _ 开头。
``` js
var _privateMethod = {};
```
**注：在Vue中使用下划线可能和Vue内置的属性、API方法冲突，可以用 `p_privateMethod` 代替**

常量，使用全部字母大写，单词间下划线分隔的命名方式。
``` js
var HTML_ENTITY = {};
```

函数，使用 Camel 命名法。函数的参数，使用 Camel 命名法。
``` js
function stringFormat(source) {}

function hear(theBells) {}
```

类，使用 Pascal 命名法。类的方法/属性，使用 Camel 命名法
``` js
function TextNode(value, engine) {
    this.value = value;
    this.engine = engine;
}

TextNode.prototype.clone = function () {
    return this;
};
```

枚举变量 使用 Pascal 命名法。枚举的属性， 使用全部字母大写，单词间下划线分隔的命名方式。
``` js
var TargetState = {
    READING: 1,
    READED: 2,
    APPLIED: 3,
    READY: 4
};
```
由多个单词组成的 缩写词，在命名中，根据当前命名法和出现的位置，所有字母的大小写与首字母的大小写保持一致。
``` js
function XMLParser() {}

function insertHTML(element, html) {}

var httpRequest = new HTTPRequest();
```

#### 5.1.3 命名语法 (B)
类名，使用名词。
``` js
function Engine(options) {}
```
函数名，使用动宾短语。
``` js
function getStyle(element) {}
```
boolean 类型的变量使用 is 或 has 开头。
``` js
var isReady = false;

var hasMoreCommands = false;
``` 
Promise 对象用动宾短语的进行时表达。
``` js
var loadingData = ajax.get('url');

loadingData.then(callback);
```

#### 5.1.4 接口命名规范 (B)
1. 可读性强，见名晓义；
2. 尽量不与 jQuery 社区已有的习惯冲突；
3. 尽量写全，不用缩写，除非是下面列表中约定的；（变量以表达清楚为目标，uglify 会完成压缩体积工作）

常用词	| 说明
 --- | ---
options	| 表示选项，与 jQuery 社区保持一致，不要用 config, opts 等
active | 表示当前，不要用 current 等
index	| 表示索引，不要用 idx 等
trigger	| 触点元素
triggerType |	触发类型、方式
context	| 表示传入的 this 对象
object | 推荐写全，不推荐简写为 o, obj 等
element	| 推荐写全，不推荐简写为 el, elem 等
length | 不要写成 len, l
prev | previous 的缩写
next | next 下一个
constructor	| 不能写成 ctor
easing | 表示动画平滑函数
min	| minimize的缩写
max	| maximize的缩写
DOM	| 不要写成 dom, Dom
.hbs | 使用 hbs 后缀表示模版
btn | button 的缩写
link | 超链接
title | 主要文本
img | 图片路径（img标签src属性）
dataset | html5 data-xxx 数据接口
theme | 主题
className | 类名
classNameSpace | class 命名空间

#### 5.1.5 True 和 False 布尔表达式  (B)
类型检测优先使用 typeof。对象类型检测使用 instanceof。null 或 undefined 的检测使用 == null。
下面的布尔表达式都返回 false:
- null
-	undefined
-	'' 空字符串
-	0 数字0
但小心下面的, 可都返回 true:
-	'0' 字符串0
-	[] 空数组
-	{} 空对象

#### 5.1.6 不要在 Array 上使用 for-in 循环 (A)
for-in 循环只用于 object/map/hash 的遍历, 对 Array 用 for-in 循环有时会出错. 因为它并不是从 0 到 length - 1 进行遍历, 而是所有出现在对象及其原型链的键值。
``` js
// Not recommended
function printArray(arr) {
  for (var key in arr) {
    print(arr[key]);
  }
}

printArray([0,1,2,3]);  // This works.

var a = new Array(10);
printArray(a);  // This is wrong.

a = document.getElementsByTagName('*');
printArray(a);  // This is wrong.

a = [0,1,2,3];
a.buhu = 'wine';
printArray(a);  // This is wrong again.

a = new Array;
a[3] = 3;
printArray(a);  // This is wrong again.

// Recommended
function printArray(arr) {
  var l = arr.length;
  for (var i = 0; i < l; i++) {
    print(arr[i]);
  }
}
```

#### 5.1.7 二元和三元操作符 (A)
操作符始终写在前一行, 以免分号的隐式插入产生预想不到的问题。
``` js
var x = a ? b : c;

var y = a ?
    longButSimpleOperandB : longButSimpleOperandC;

var z = a ?
        moreComplicatedB :
        moreComplicatedC;
```

. 操作符也是如此：
``` js
var x = foo.bar().
    doSomething().
    doSomethingElse();
```

#### 5.1.8 条件(三元)操作符 (?:) (B)
三元操作符用于替代 if 条件判断语句。
``` js
// Not recommended
if (val != 0) {
  return foo();
} else {
  return bar();
}

// Recommended
return val ? foo() : bar();
``` 

#### 5.1.9 && 和 || (B)
二元布尔操作符是可短路的, 只有在必要时才会计算到最后一项。
``` js
// Not recommended
function foo(opt_win) {
  var win;
  if (opt_win) {
    win = opt_win;
  } else {
    win = window;
  }
  // ...
}

if (node) {
  if (node.kids) {
    if (node.kids[index]) {
      foo(node.kids[index]);
    }
  }
}

// Recommended
function foo(opt_win) {
  var win = opt_win || window;
  // ...
}

var kid = node && node.kids && node.kids[index];
if (kid) {
  foo(kid);
}
``` 

### 5.2 jQuery 规范

#### 5.2.1 使用最新版本的 jQuery (C)
最新版本的 jQuery 会改进性能和增加新功能，若不是为了兼容旧浏览器，建议使用最新版本的 jQuery。以下是三条常见的 jQuery 语句，版本越新，性能越好：<br>
$('.elem')<br>
$('.elem', context)<br>
context.find('.elem')<br>
分别使用 1.4.2、1.4.4、1.6.2 三个版本测试浏览器在一秒内能够执行多少次，结果 1.6.2 版执行次数远超两个老版本。
#### 5.2.2 jQuery 变量 (A)
1.	存放 jQuery 对象的变量以 $ 开头；
2.	将 jQuery 选择器返回的对象缓存到本地变量中复用；
3.	使用驼峰命名变量；
``` js
var $myDiv = $("#myDiv");
$myDiv.click(function(){...});
```
#### 5.2.3	选择器 (B)
1.	尽可能的使用 ID 选择器，因为它会调用浏览器原生方法 document.getElementById 查找元素。当然直接使用原生 document.getElementById 方法性能会更好；
2.	在父元素中选择子元素使用 .find() 方法性能会更好, 因为 ID 选择器没有使用到 Sizzle 选择器引擎来查找元素；
``` js
// Not recommended
var $productIds = $("#products .class");

// Recommended
var $productIds = $("#products").find(".class");
```

#### 5.2.4	DOM 操作 (B)
1.	当要操作 DOM 元素的时候，尽量将其分离节点，操作结束后，再插入节点；
2.	使用字符串连接或 array.join 要比 .append()性能更好；
``` js
var $myList = $("#list-container > ul").detach();
//...a lot of complicated things on $myList
$myList.appendTo("#list-container");

// Not recommended
var $myList = $("#list");
for(var i = 0; i < 10000; i++){
    $myList.append("<li>"+i+"</li>");
}

// Recommended
var $myList = $("#list");
var list = "";
for(var i = 0; i < 10000; i++){
    list += "<li>"+i+"</li>";
}
$myList.html(list);

// Much to recommended
var array = [];
for(var i = 0; i < 10000; i++){
    array[i] = "<li>"+i+"</li>";
}
$myList.html(array.join(''));
```

#### 5.2.5 事件 (B)
1.	如果需要，对事件使用自定义的 namespace，这样容易解绑特定的事件，而不会影响到此 DOM 元素的其他事件监听；
2.	对 Ajax 加载的 DOM 元素绑定事件时尽量使用事件委托。事件委托允许在父元素绑定事件，子代元素可以响应事件，也包括 Ajax 加载后添加的子代元素；
``` js
$("#myLink").on("click.mySpecialClick", myEventHandler); //绑定mySpecialClick事件
$("#myLink").unbind("click.mySpecialClick"); //解绑mySpecialClick事件

// Not recommended
$("#list a").on("click", myClickHandler);

// Recommended
$("#list").on("click", "a", myClickHandler);
```

#### 5.2.6 链式写法 (B)
1.	尽量使用链式写法而不是用变量缓存或者多次调用选择器方法；
2.	当链式写法超过三次或者因为事件绑定变得复杂后，使用换行和缩进保持代码可读性；

``` js
$("#myDiv").addClass("error").show();
$("#myLink")
  .addClass("bold")
  .on("click", myClickHandler)
  .on("mouseover", myMouseOverHandler)
  .show();
```

#### 5.2.7 其他 (C)
1.	多个参数使用对象字面量存储；
2.	不要将 CSS 写在 jQuery 里面；
3.	正则表达式仅准用 .test() 和 .exec() 。不准用 "string".match() ；

#### 5.2.8 jQuery 插件模板 (C)
``` js
// jQuery Plugin Boilerplate
// A boilerplate for jumpstarting jQuery plugins development
// version 1.1, May 14th, 2011
// by Stefan Gabos

// remember to change every instance of "pluginName" to the name of your plugin!
(function($) {

    // here we go!
    $.pluginName = function(element, options) {

        // plugin's default options
        // this is private property and is  accessible only from inside the plugin
        var defaults = {

            foo: 'bar',

            // if your plugin is event-driven, you may provide callback capabilities
            // for its events. execute these functions before or after events of your
            // plugin, so that users may customize those particular events without
            // changing the plugin's code
            onFoo: function() {}

        }

        // to avoid confusions, use "plugin" to reference the
        // current instance of the object
        var plugin = this;

        // this will hold the merged default, and user-provided options
        // plugin's properties will be available through this object like:
        // plugin.settings.propertyName from inside the plugin or
        // element.data('pluginName').settings.propertyName from outside the plugin,
        // where "element" is the element the plugin is attached to;
        plugin.settings = {}

        var $element = $(element), // reference to the jQuery version of DOM element
             element = element;    // reference to the actual DOM element

        // the "constructor" method that gets called when the object is created
        plugin.init = function() {

            // the plugin's final properties are the merged default and
            // user-provided options (if any)
            plugin.settings = $.extend({}, defaults, options);

            // code goes here

        }

        // public methods
        // these methods can be called like:
        // plugin.methodName(arg1, arg2, ... argn) from inside the plugin or
        // element.data('pluginName').publicMethod(arg1, arg2, ... argn) from outside
        // the plugin, where "element" is the element the plugin is attached to;

        // a public method. for demonstration purposes only - remove it!
        plugin.foo_public_method = function() {

            // code goes here

        }

        // private methods
        // these methods can be called only from inside the plugin like:
        // methodName(arg1, arg2, ... argn)

        // a private method. for demonstration purposes only - remove it!
        var foo_private_method = function() {

            // code goes here

        }

        // fire up the plugin!
        // call the "constructor" method
        plugin.init();

    }

    // add the plugin to the jQuery.fn object
    $.fn.pluginName = function(options) {

        // iterate through the DOM elements we are attaching the plugin to
        return this.each(function() {

            // if plugin has not already been attached to the element
            if (undefined == $(this).data('pluginName')) {

                // create a new instance of the plugin
                // pass the DOM element and the user-provided options as arguments
                var plugin = new $.pluginName(this, options);

                // in the jQuery version of the element
                // store a reference to the plugin object
                // you can later access the plugin and its methods and properties like
                // element.data('pluginName').publicMethod(arg1, arg2, ... argn) or
                // element.data('pluginName').settings.propertyName
                $(this).data('pluginName', plugin);

            }

        });

    }

})(jQuery);
```

### 5.3 性能优化
#### 5.3.1 避免不必要的 DOM 操作 (B)
浏览器遍历 DOM 元素的代价是昂贵的。最简单优化 DOM 树查询的方案是，当一个元素出现多次时，将它保存在一个变量中，就避免多次查询 DOM 树了。
``` js
// Recommended
var myList = "";
var myListHTML = document.getElementById("myList").innerHTML;

for (var i = 0; i < 100; i++) {
  myList += "<span>" + i + "</span>";
}

myListHTML = myList;

// Not recommended
for (var i = 0; i < 100; i++) {
  document.getElementById("myList").innerHTML += "<span>" + i + "</span>";
}
```

#### 5.3.2 缓存数组长度  (C)
循环无疑是和 JavaScript 性能非常相关的一部分。通过存储数组的长度，可以有效避免每次循环重新计算。
注: 虽然现代浏览器引擎会自动优化这个过程，但是不要忘记还有旧的浏览器。
``` js
var arr = new Array(1000),
    len, i;
// Recommended - size is calculated only 1 time and then stored
for (i = 0, len = arr.length; i < len; i++) {

}

// Not recommended - size needs to be recalculated 1000 times
for (i = 0; i < arr.length; i++) {

}
```
#### 5.3.3 异步加载第三方内容  (A)
当你无法保证嵌入第三方内容比如 Youtube 视频或者一个 like/tweet 按钮可以正常工作的时候，你需要考虑用异步加载这些代码，避免阻塞整个页面加载。
``` js
(function() {

    var script,
        scripts = document.getElementsByTagName('script')[0];

    function load(url) {
      script = document.createElement('script');
      script.async = true;
      script.src = url;
      scripts.parentNode.insertBefore(script, scripts);
    }

    load('//apis.google.com/js/plusone.js');
    load('//platform.twitter.com/widgets.js');
    load('//s.widgetsite.com/widget.js');

}());
```



