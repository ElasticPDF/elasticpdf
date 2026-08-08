<h1 align="center">ElasticPDF-重拾阅读的乐趣</h1>
<h4 align="center" style='margin-bottom:30px;'>
	<a href="https://github.com/ElasticPDF/elasticpdf/tree/main">English</a> ·  
    <span>简体中文</span> · 
    <a href="https://www.elasticpdf.com/contact-us.html">联系我们</a> · 
    <a href="https://www.elasticpdf.com/documentation.html">文档</a> · 
	<a href="https://github.com/ElasticPDF/elasticpdf/issues/new?assignees=&labels=&projects=&template=bug_report.yml" target="_blank">Report Bug</a> · 
	<a href="https://github.com/ElasticPDF/elasticpdf/issues/new?assignees=&labels=%3Asparkles%3A+feature+request&projects=&template=feature_request.yml" target="_blank">Request Feature</a> · 
	<a href="https://github.com/ElasticPDF/elasticpdf/discussions" target="_blank">FAQ</a>
</h4>

<p align="center">
  <img src="https://img.shields.io/badge/Vue-aliceblue?logo=vue.js" alt="Vue Badge">
  <img src="https://img.shields.io/badge/React-blue?logo=react" alt="React Badge">
  <img src="https://img.shields.io/badge/Angular-red?logo=angular" alt="Angular Badge">
  <img src="https://img.shields.io/badge/jQuery-blue?logo=jquery" alt="jQuery Badge">
  <img src="https://img.shields.io/badge/HTML5-orange?logo=html5" alt="HTML5 Badge">
  <img src="https://img.shields.io/badge/Other-Frameworks-blue" alt="Other-Framework Badge">
</p>
<p align="center">
	<img src="https://img.shields.io/badge/Chrome-white?logo=googlechrome" alt="Chrome">
	<img src="https://img.shields.io/badge/Firefox-grey?logo=firefoxbrowser" alt="Firefox">
	<img src="https://img.shields.io/badge/Safari-lightgrey?logo=safari" alt="Safari">
	<img src="https://img.shields.io/badge/Edge-blue?logo=microsoftedge" alt="Edge">
	<img src="https://img.shields.io/badge/IE%2010+-lightblue?logo=internetexplorer" alt="IE">
  <img src="https://img.shields.io/badge/Android-green?logo=android" alt="Android Badge">
  <img src="https://img.shields.io/badge/OS-IOS-black" alt="iOS Badge">
  <img src="https://img.shields.io/badge/OS-Windows-blue" alt="Windows Badge">
  <img src="https://img.shields.io/badge/OS-Mac-orange" alt="Mac Badge">
</p>


AI 可以在几秒钟内读完一篇文章，为我们总结内容、提炼要点。

但我们也渐渐发现，知道得更快，并不意味着理解得更深。当阅读被一次次浓缩成摘要和答案，我们也可能在不经意间，失去了阅读本身的乐趣——那些沉浸其中的时刻，那些突然读懂一句话的欣喜，以及通过思考一点点拓宽认知的过程。

我们相信，AI 应该帮助我们更好地阅读，而不是替我们阅读。

通过 ElasticPDF，我们希望不断打磨更纯粹、更出色的阅读体验，`让技术退到身后，让内容重新回到眼前`。

和你一起，享受阅读，理解知识，也享受成长。

# 0 总览

为了让阅读和文档处理更加自由，我们首先为 ElasticPDF 构建了一套完整的 PDF 阅读与编辑基础设施，并持续优化阅读、编辑和交互体验。

现在集成了  `PDF 阅读、文字编辑、图片与图形编辑、页面增删合并导出、批注、图形标记和文档导出` 等功能。许多过去需要专业桌面软件才能完成的高级 PDF 编辑操作，现在可以直接在浏览器中完成。 整个处理过程无需将文件上传到后台服务器，在兼顾功能的同时，也尽可能保护文档隐私与安全。

无论是简历、合同、论文、教材、申请材料，还是其他日常 PDF 文档，都可以轻松应对。

官方网站：https://www.elasticpdf.com         

我们精心录制了操作视频教程方便更快上手和使用：             
① 综合视频教程：https://www.bilibili.com/video/BV1RL3F6HE6h/      
② 编辑文字：<https://www.bilibili.com/video/BV1VE3F6nEAJ/>          
③ 编辑图像图形：https://www.bilibili.com/video/BV19j3F6DELt/         
④ 批注功能：https://www.bilibili.com/video/BV1ET3F6ZEUo/       
⑤ 图形批注：https://www.bilibili.com/video/BV1iJ3P6KE23/         
⑥ 阅读功能：https://www.bilibili.com/video/BV1vW3P6YEnS/           


# 1 编辑 PDF 原有文字

在 Elasticpdf 中，修改PDF文字，只需要一次点击，无需先将文件转换为 Word。

视频演示：**<https://www.bilibili.com/video/BV1VE3F6nEAJ/>**

用户可以`新增或删除`文字，插入`空格、回车和换行`，例如修改姓名、日期、金额、编号、地址、段落、表格单元格和固定模板字段。

当文字长度发生变化时，ElasticPDF 会根据文本区域宽度、字号、字距和排版规则进行`自适应重排`，让新增内容自动换行，并推动后续文字重新布局。用户还可以拖动文本框改变`宽度、位置和排版`范围，获得接近 Word 的编辑体验。

同时支持下面这些高级功能：

* 编辑竖排、旋转和任意角度文字。
* 移动和旋转整个文本框。
* 修改加粗、颜色和对齐方式。
* 复制和粘贴带样式文字。
* 编辑中文、英文、日文、韩文及多语言混排内容。
* 保留原有字体、样式、位置和页面排版。
* 将编辑结果导出为标准 PDF。

切换工具、页面不可见或手动导出PDF后会**自动触发文本保存**，严格保持原有字体和排版，未被编辑的文字保持原样。

|  |  |  |
| --- | --- | --- |
| 1 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/70_edit_text_content_zh.png" alt="文字编辑功能 1" width="180"> | 删除已有文本、输入新字体和文本内容 |
| 2 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/71_text_reflow_zh.png" alt="文字编辑功能 2" width="180"> | 在具备多句文字的段落中，通过调整个文本框的大小，来实现多段文字的自适应排版补齐 |
| 3 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/72_move_text_block_zh.png" alt="文字编辑功能 3" width="180"> | 移动整个文本框到其他位置 |
| 4 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/73_rotate_text_zh.png" alt="文字编辑功能 4" width="180"> | 编辑已经存在的旋转文本内容<br><br>或者旋转已有文本 |
| 5 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/74_bold_text_zh.png" alt="文字编辑功能 5" width="180"> | 加粗对应的文字内容 |
| 6 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/75_text_color_zh.png" alt="文字编辑功能 6" width="180"> | 修改文本内容的颜色 |
| 7 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/76_text_alignment_zh.png" alt="文字编辑功能 7" width="180"> | 让文本居中、左、右对齐 |
| 8 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/77_copy_paste_text_zh.png" alt="文字编辑功能 8" width="180"> | 复制文本内容之后再粘贴（快捷键cmd/ctrl+c/v），可以保持原文本的字体、颜色等 |
| 9 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/78_delete_text_block_zh.png" alt="文字编辑功能 9" width="180"> | 删除整个文本组 |


# 2 编辑 PDF 原有图片和图形

ElasticPDF 支持直接选择 PDF 中已有的图片、线条和色块，并像在 Word 或 PPT 中一样修改这些对象。

视频演示：**<https://www.bilibili.com/video/BV19j3F6DELt/>**

选中对象后，可以`移动、缩放和旋转`，也可以调整`宽度、高度`和具体位置。未被修改的页面对象会继续保持原样。

图片与图形编辑功能包括：

* 移动、缩放和任意角度旋转。
* 裁剪图片及清除多余边缘,特别适用于`扫描件裁切黑边`。
* 水平或垂直镜像翻转。
* 替换为本地选择的新图片。
* 调整图片透明度。
* 通过数值精确控制图片大小。
* 调整`图像图层`，将对象置于顶层或底层。
* 将对象向上或向下移动一层。
* 将原始图片直接保存到本地。
* 从 PDF 页面中删除选中的图片或图形。

图层功能可以避免`图片、文字`和其他页面对象相互遮挡，适合`报告、论文、简历、证书、Logo、二维码、扫描件`和复杂图文页面的修改。

|  |  |  |  |
| --- | --- | --- | --- |
| 1 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/79_image_transform_controls_zh.png" alt="图像编辑工具 1" width="210"> | 通用操作按钮来旋转、移动、拖动改变位置、角度和大小 |  |
| 2 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/80_crop_image_controls_zh.png" alt="图像编辑工具 2" width="210"> | 裁剪对象 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/81_crop_image_example_zh.png" alt="图像编辑示例 2" width="280"> |
| 3 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/82_layer_order_controls_zh.png" alt="图像编辑工具 3" width="210"> | 置于顶层、底层；<br><br>上移、下移一层 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/83_layer_order_example_zh.png" alt="图像编辑示例 3" width="280"> |
| 4 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/84_rotate_image_controls_zh.png" alt="图像编辑工具 4" width="210"> | 顺时针、逆时针旋转对象 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/85_rotate_image_example_zh.png" alt="图像编辑示例 4" width="280"> |
| 5 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/86_flip_image_controls_zh.png" alt="图像编辑工具 5" width="210"> | 水平、垂直镜像 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/87_flip_image_example_zh.png" alt="图像编辑示例 5" width="280"> |
| 6 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/88_image_opacity_controls_zh.png" alt="图像编辑工具 6" width="210"> | 修改不透明度 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/89_image_opacity_example_zh.png" alt="图像编辑示例 6" width="280"> |
| 7 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/90_image_size_controls_zh.png" alt="图像编辑工具 7" width="210"> | 输入数值调整大小 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/91_image_size_example_zh.png" alt="图像编辑示例 7" width="280"> |
| 8 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/92_replace_image_controls_zh.png" alt="图像编辑工具 8" width="210"> | 替换图像 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/93_replace_image_example_zh.png" alt="图像编辑示例 8" width="280"> |
| 9 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/94_save_image_controls_zh.png" alt="图像编辑工具 9" width="210"> | 保存图像、图形到本地 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/95_save_image_example_zh.png" alt="图像编辑示例 9" width="280"> |
| 10 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/96_delete_image_controls_zh.png" alt="图像编辑工具 10" width="210"> | 删除对象 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/97_delete_image_example_zh.png" alt="图像编辑示例 10" width="280"> |


# 3 创建或编辑PDF原有批注
## 3.1 高亮、评论、图章、手绘与签名
ElasticPDF 提供完整的 PDF 批注工具，可以通过鼠标或触屏创建和编辑：

视频演示：**<https://www.bilibili.com/video/BV1ET3F6ZEUo/>**

* 高亮：高亮包括下面的下划线、删除线、波浪线等文字标记均支持普通文字和倾斜文字。批注创建后，仍然可以修改范围、颜色、线宽、线型和透明度，适合标记重点、错误、待确认内容和修改建议。
* 下划线。
* 删除线。
* 波浪线。
* 自由画笔。
* 引线批注。
* 便签。
* 文本框。
* 图片批注。
* 预设或自定义印章。
* 手写签名。

画笔支持连续绘制，多笔内容可以自动合并。引线、便签和文本框可用于指出具体页面位置并补充说明；图片、图章和签名则适用于合同确认、文件审核、教学批改、状态标记和日常签署。

企业客户还可以通过批注 API 构建在线协同功能，包括用户身份与权限管理、批注 JSON 导入导出、增量同步、接受或拒绝状态、批注缩略图以及批注选择、添加和删除控制。

|  |  |  |
| --- | --- | --- |
| 1 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/98_highlight_annotation_icon_zh.png" alt="PDF批注工具 1" width="64"> | 高亮：选中文本后高亮，支持倾斜文字，之后可以修改颜色、范围等<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/167_highlight_annotation_content_zh.png" alt="高亮批注内容示例" width="360"> |
| 2 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/100_underline_annotation_icon_zh.png" alt="PDF批注工具 2" width="64"> | 下划线：选中文本后下划线，支持倾斜文字，可改范围、线宽、线型、颜色等<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/168_underline_annotation_content_zh.png" alt="下划线批注内容示例" width="360"> |
| 3 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/101_strikethrough_annotation_icon_zh.png" alt="PDF批注工具 3" width="64"> | 删除线：各功能同下划线<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/169_strikethrough_annotation_content_zh.png" alt="删除线批注内容示例" width="360"> |
| 4 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/102_squiggly_annotation_icon_zh.png" alt="PDF批注工具 4" width="64"> | 波浪线：各功能同下划线<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/170_squiggly_annotation_content_zh.png" alt="波浪线批注内容示例" width="360"> |
| 5 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/103_freehand_ink_icon_zh.png" alt="PDF批注工具 5" width="64"> | 画笔：拖拽绘制线条，连续多笔画自动合并，可改线宽、线型、颜色<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/171_freehand_ink_content_zh.png" alt="画笔批注内容示例" width="360"> |
| 6 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/104_callout_annotation_icon_zh.png" alt="PDF批注工具 6" width="64"> | 引线批注：3次点击完成绘制，可修改形状位置、内容、字体等各种属性<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/172_callout_annotation_content_zh.png" alt="引线批注内容示例" width="360"> |
| 7 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/105_sticky_note_icon_zh.png" alt="PDF批注工具 7" width="64"> | 便签：单击完成绘制，用于在特定位置留下评论<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/173_sticky_note_marker_zh.png" alt="便签标记示例" width="360"> |
| 8 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/107_text_box_annotation_icon_zh.png" alt="PDF批注工具 8" width="64"> | 文本框：单击创建，可修改各类属性<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/174_text_box_annotation_content_zh.png" alt="文本框批注内容示例" width="360"> |
| 9 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/108_image_annotation_icon_zh.png" alt="PDF批注工具 9" width="64"> | 图像：单击或拖拽出区域后选择图像来插入<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/175_image_annotation_content_zh.png" alt="图像批注内容示例" width="360"> |
| 10 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/109_stamp_annotation_icon_zh.png" alt="PDF批注工具 10" width="64"> | 印章：左侧列表选择印章后，单击或拖拽出区域后生成批注；可自定义文字印章或者选中批注生成印章<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/176_stamp_annotation_content_zh.png" alt="印章批注内容示例" width="360"> |
| 11 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/110_signature_annotation_icon_zh.png" alt="PDF批注工具 11" width="64"> | 签名：左侧列表选择签名后，单击或拖拽出区域后生成批注<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/177_signature_annotation_content_zh.png" alt="签名批注内容示例" width="360"> |
| 12 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/112_annotation_style_panel_icon_zh.png" alt="PDF批注工具 12" width="64"> | 批注样式面板：<br><br>单击后打开属性面板，修改已选中批注的样式，或者修改默认批注样式 |
| 13 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/113_undo_annotation_icon_zh.png" alt="PDF批注工具 13" width="64"> | 撤销：撤销批注编辑操作 |
| 14 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/114_redo_annotation_icon_zh.png" alt="PDF批注工具 14" width="64"> | 重做：恢复被撤销的批注编辑操作 |


## 3.2 矩形、箭头、多边形、路径与超链接

ElasticPDF 支持在 PDF 页面中创建和编辑矩形、圆形、椭圆、直线、箭头、多边形、多段线和圆弧。

视频演示：**<https://www.bilibili.com/video/BV1iJ3P6KE23/>**

矩形、圆形和椭圆适合框选文字、图片、表格和重点区域；直线与箭头可以指出错误位置、连接页面对象或表达方向；多边形、多段线和圆弧则适合标记不规则区域、边界、路径和曲线内容。

图形创建后，可以继续调整：

* 位置。
* 大小。
* 旋转角度。
* 边框颜色。
* 填充颜色。
* 线条宽度。
* 线型。
* 箭头端点。
* 多边形和路径节点。

如果初次绘制不够准确，无需删除后重新绘制，可以直接拖动控制点修改多边形或多段线的形状。

图形批注还支持添加评论、编辑超链接、打开属性面板、生成印章和删除对象，将图形绘制、节点编辑、样式设置和链接管理整合到统一的标注流程中。

|  |  |  |
| --- | --- | --- |
| 1 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/115_rectangle_annotation_icon_zh.png" alt="图形批注工具 1" width="64"> | 矩形：单击或拖拽绘制矩形，可改外框线宽、线型、颜色及填充颜色<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/147_rectangle_annotation_shape_zh.png" alt="矩形批注示例" width="360"> |
| 2 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/117_ellipse_annotation_icon_zh.png" alt="图形批注工具 2" width="64"> | 圆形：单击或拖拽绘制圆形及椭圆<br><br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/149_ellipse_annotation_shape_zh.png" alt="椭圆批注示例" width="360"> |
| 3 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/118_line_annotation_icon_zh.png" alt="图形批注工具 3" width="64"> | 直线：单击或拖拽绘制直线，可改线属性和箭头属性<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/150_line_annotation_shape_zh.png" alt="直线批注示例" width="360"> |
| 4 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/119_arrow_annotation_icon_zh.png" alt="图形批注工具 4" width="64"> | 箭头：单击或拖拽绘制箭头，可改线属性和箭头属性<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/151_arrow_annotation_shape_zh.png" alt="箭头批注示例" width="360"> |
| 5 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/120_polygon_annotation_icon_zh.png" alt="图形批注工具 5" width="64"> | 多边形：多次单击绘制多边形，双击页面结束绘制，可修改边框及填充样式<br><br>选中批注后，可改变位置、缩放、旋转，还可以拖动节点来改变形状<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/152_polygon_annotation_shape_zh.png" alt="多边形批注示例" width="360"> |
| 6 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/122_polyline_annotation_icon_zh.png" alt="图形批注工具 6" width="64"> | 多段线：多次单击绘制多段线，双击结束绘制，可修改线条样式、颜色<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/153_polyline_annotation_shape_zh.png" alt="多段线批注示例" width="360"> |
| 7 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/123_arc_annotation_icon_zh.png" alt="图形批注工具 7" width="64"> | 弧线：3次点击绘制弧线，可修改线条样式、颜色<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/154_arc_annotation_shape_zh.png" alt="弧线批注示例" width="360"> |

## 3.3 批注编辑按钮

选中已有批注后，还可以打开评论列表和属性面板，修改样式、编辑超链接、删除批注，或将当前批注保存为可重复使用的印章，并通过撤销和重做快速修正操作。

|  |  |  |
| --- | --- | --- |
| 1 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/124_comments_button_zh.png" alt="批注编辑按钮 1" width="180"> | 评论：打开或者关闭批注的评论列表 |
| 2 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/125_hyperlink_button_zh.png" alt="批注编辑按钮 2" width="180"> | 超链接：编辑批注上的超链接 |
| 3 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/126_properties_panel_button_zh.png" alt="批注编辑按钮 3" width="180"> | 属性面板：打开或关闭批注属性编辑面板 |
| 4 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/127_create_stamp_button_zh.png" alt="批注编辑按钮 4" width="180"> | 生成印章：将当前批注生成印章以便重复使用 |
| 5 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/128_delete_annotation_button_zh.png" alt="批注编辑按钮 5" width="180"> | 删除：删除当前选中批注 |

# 4 智能阅读器

ElasticPDF 同时提供完整的纯前端 PDF 阅读器，阅读器与文字、图片、批注和图形编辑模块使用同一套客户端架构。

视频演示：**<https://www.bilibili.com/video/BV1vW3P6YEnS/>**

## 4.1 浏览器缩略图、书签与文本检索

<div class="joplin-table-wrapper"><table><tbody><tr><td><ul><li><a id="_Hlk235380399"></a><strong>缩略图</strong></li><li>点击快速跳转页面</li><li>自由调整缩略图大小</li><li>蓝色线框显示实际视窗浏览范围</li></ul></td><td><ul><li><strong>书签</strong></li><li>点击跳转页面及位置</li><li>点击左侧按钮展开/收起书签</li></ul></td><td><ul><li><strong>文本搜索</strong></li><li>全文档文本检索内容</li><li>区分大小写与全词匹配</li><li>选中蓝色高亮，未选中黄色高亮</li></ul></td></tr><tr><td><p><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/129_thumbnails_panel_zh.png" alt="ElasticPDF UI screenshot" width="300"></p></td><td><p><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/130_bookmarks_panel_zh.png" alt="ElasticPDF UI screenshot" width="300"></p></td><td><p><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/131_text_search_panel_zh.png" alt="ElasticPDF UI screenshot" width="300"></p></td></tr></tbody></table></div>

## 4.2 缩放比例面板、视图及滚动方向设置、多语言UI

<div class="joplin-table-wrapper"><table><tbody><tr><td><ul><li><strong>缩放比例面板</strong></li><li>10%-6400% 缩放</li><li>支持自适应页面缩放</li><li>可以双指缩放至任意比例</li></ul></td><td><ul><li><strong>浏览设置</strong></li><li>支持连续与翻页模式</li><li>支持单、双、书籍视图</li><li>支持旋转页面、双向滚动</li></ul></td><td><ul><li><strong>多语种UI</strong></li><li>内置13种语言，适配全球需求</li><li>简体中文、英语、繁体中文、日语、韩语、越南语</li><li>德语、西班牙语、法语、意大利语、荷兰语、葡萄牙语、俄语</li></ul></td></tr><tr><td><p><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/132_zoom_panel_zh.png" alt="ElasticPDF UI screenshot" width="300"></p></td><td><p><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/133_viewing_settings_zh.png" alt="ElasticPDF UI screenshot" width="300"></p></td><td><p><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/134_multilingual_ui_zh.png" alt="ElasticPDF UI screenshot" width="300"></p></td></tr></tbody></table></div>

## 4.3 明亮模式与黑夜模式

|  |
| --- |
| <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/135_light_mode_zh.png" alt="ElasticPDF 明亮模式" width="760"> |
| <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/136_dark_mode_zh.png" alt="ElasticPDF 黑夜模式" width="760"> |

# 总结

ElasticPDF 将五类核心能力整合到统一的 PDF 产品中：

1. 直接修改 PDF 原有文字，并自动换行和智能重排。
2. 编辑 PDF 原有图片与图形，包括裁剪、替换和图层管理。
3. 创建高亮、评论、手绘、图章和签名等完整批注。
4. 绘制矩形、箭头、多边形和路径，并添加超链接。
5. 使用缩略图、书签、全文搜索、6400% 缩放和多语言界面阅读 PDF。

* 对普通用户：可以免费完成 PDF 阅读、文字修改、图片调整、批注、签名和图形标记。

* 对企业客户：可以获得可集成、可私有化、跨平台、数据边界可控的 PDF Viewer 与编辑 SDK，并按业务需求组合文字、图片、批注、图形和阅读模块。

如果你正在寻找免费 PDF 编辑器、PDF 编辑 SDK、浏览器端 PDF 编辑器、PDF Viewer、PDF 批注 SDK，或可私有化部署的文档编辑引擎。

欢迎访问 Elasticpdf 官网了解更多和试用：**<https://www.elasticpdf.com>**

