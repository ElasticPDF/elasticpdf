**Abstract:** ElasticPDF is a **new professional PDF editor development library**, based on the open source pdf.js-dist, with added annotation features, supporting full offline deploy, and suitable for public and intranet systems. The code structure continues the simple style of pdf.js-dist, is compatible with all mainstream browsers, and can be deployed not only in Web projects, but also embedded in any desktop and mobile projects.

**Keywords:** Web PDF editor, pdf.js, PDF annotation, available in intranet, available in any project

# 1 Technical advantages

ElasticPDF continues the architectural style of pdf.js-dist, and is developed entirely with simple Javascript code. In short, it adds several js files to the pdf.js-dist code package, and can run without any online dependencies, so it is very suitable for integration into other projects as a functional module.

It not only can it be deployed in public network environment applications, but its independent and simple features also give it completely transparent and controllable security, so it is chosen to be **deployed in many intranet systems**.

After years of research and development, **even if it is a product that only relies on HTML, CSS and Javascript to run, the product power of annotation and other features is close to that of world-class PDF editors (such as Adobe Acrobat)**. Specifically, annotations can be written into PDF in a standard format, including text in any language of the annotation comment, and can be edited in other editors later.

In addition, **annotations can be exported independently in JSON** format, which is convenient for storage and reload echo. It is very convenient and economical in cloud-based collaborative systems, because only an online original document and an annotation file with a size of usually less than 1M are required, and there is no need to merge the annotations into the document and save them together in the back-end database, which can save a lot of traffic, broadband and storage costs.

# 2 Live Demo

There are currently two versions of the product available for selection (**not free**) to meet the development needs of different projects. The two versions differ in the authorization method and the technical effect of the final annotation writing into PDF. The specific instructions and operation effects of the online Demo website shall prevail.

**① Annotation synthesis version: <https://demos.libertynlp.com/#/pdfjs-annotation>**

**② Standard annotation version: <https://www.elasticpdf.com/demo>**

![Cover Image.png](https://blog-back.elasticpdf.com/static/blogs/fe3b9b0fd34052469f457f4876bc608f/first_post.png)

# 3 Features Demostration

In addition to the following features, others are also under continuous development, and features can be customized.

## 3.1 Annotation features

① Text highlighting

Whether it is desktop, tablet or mobile phone, you can accurately select text, support cross-page highlighting, color and other attributes of the highlighted content can be modified.
<video src="https://blog-back.elasticpdf.com/static/blogs/fe3b9b0fd34052469f457f4876bc608f/1-highlight.mp4"></video>

② Underline

Similar to the highlight, it realizes the precise selection of texts on multiple devices. After the annotation generated, the annotation color, line thickness, etc. can be modified

<video src="https://blog-back.elasticpdf.com/static/blogs/fe3b9b0fd34052469f457f4876bc608f/2-underline.mp4"></video>

③ Insert image

Supports inserting images by selecting files or dragging them in, and then the size, position, orientation, opacity, etc. of the image can be smoothly modified

<video src="https://blog-back.elasticpdf.com/static/blogs/fe3b9b0fd34052469f457f4876bc608f/3-insert-image.mp4"></video>

④ Screenshot

After drawing a rectangle, you can capture part of the current document, you can modify the position of the rectangle and take another screenshot

<video src="https://blog-back.elasticpdf.com/static/blogs/fe3b9b0fd34052469f457f4876bc608f/4-screen-shot.mp4"></video>

⑤ Brush Free drawing

You can freely adjust the size, color and opacity of the brush, and then freely draw on the document. When the opacity is set to a small value, it can also be used to highlight the text in the scanned document
<video src="https://blog-back.elasticpdf.com/static/blogs/fe3b9b0fd34052469f457f4876bc608f/5-brush.mp4"></video>

⑥ Add text

You can create text annotations by inserting and dragging, supporting all languages. After creation, you can modify the font shape, font size, etc. by dragging
<video src="https://blog-back.elasticpdf.com/static/blogs/fe3b9b0fd34052469f457f4876bc608f/6-add-text.mp4"></video>

⑦ Polygon

Supports the creation of polygons such as arrows, lines, rectangles, circles (ellipse), check marks and identity stamps. The generated annotations support the modification of color, size, position and orientation, etc.
<video src="https://blog-back.elasticpdf.com/static/blogs/fe3b9b0fd34052469f457f4876bc608f/7-polygon.mp4"></video>

⑧ Hyperlink

Create a hyperlink object by drawing a rectangular box or selecting text, and then you can link to a URL, page number, online document, etc.
<video src="https://blog-back.elasticpdf.com/static/blogs/fe3b9b0fd34052469f457f4876bc608f/8-hyperlink.mp4"></video>

## 3.2 Annotation Management Function

① Eraser

The powerful eraser can partially erase the annotation object. The track is visible during the erasing process, and the erased text is still editable
<video src="https://blog-back.elasticpdf.com/static/blogs/fe3b9b0fd34052469f457f4876bc608f/9-eraser.mp4"></video>

② Undo & Redo Annotation

Undo or redo annotations, including annotation generation, modification, and other editing and deletion operations
<video src="https://blog-back.elasticpdf.com/static/blogs/fe3b9b0fd34052469f457f4876bc608f/10-undo-redo.mp4"></video>

③ Export & Import JSON Annotation

Supports exporting annotation as JSON files, and then reloading JSON files to achieve perfect echo, which is the best solution for multi-terminal synchronization
<video src="https://blog-back.elasticpdf.com/static/blogs/fe3b9b0fd34052469f457f4876bc608f/11-output-input-annotation.mp4"></video>

④ Annotation Connection Line & Bilingual

Connect the annotations in the list on the right to the graphic objects on the page, and control each page separately; all page operations support Chinese and English
<video src="https://blog-back.elasticpdf.com/static/blogs/fe3b9b0fd34052469f457f4876bc608f/12-connect-line-language.mp4"></video>
