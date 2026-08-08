<h1 align="center">ElasticPDF-Rediscovery the joy of Reading</h1>

<h4 align="center" style='margin-bottom:30px;'>
     <span>English</span> · 
	<a href="https://github.com/ElasticPDF/elasticpdf/tree/doc-zh_cn">简体中文</a> · 
    <a href="https://www.elasticpdf.com/contact-us.html">Contact</a> · 
    <a href="https://www.elasticpdf.com/documentation.html">Doc</a> · 
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

AI can read an article in seconds, summarize its content, and extract the key points for us.

But we are also beginning to realize that getting information faster does not necessarily mean understanding it more deeply. When reading is repeatedly reduced to summaries and answers, we may gradually lose some of the joy of reading itself — the moments of being fully immersed, the satisfaction of suddenly understanding a sentence, and the process of expanding our perspective little by little through reflection.

We believe AI should help us read better, not replace reading itself.

With ElasticPDF, we hope to keep refining a purer and better reading experience — `letting technology fade into the background, so the content can return to the center of attention`.

Together with you, we hope to enjoy reading, deepen our understanding, and embrace the joy of learning and growth.

# 0 Overview

To make reading and document handling more flexible and accessible, we first built a complete PDF reading and editing foundation for ElasticPDF, and we continue to improve the reading, editing, and interaction experience.

ElasticPDF now integrates `PDF reading, text editing, image and graphics editing, page insertion, deletion, merging and export, annotations, graphical markup, and document export`. Many advanced PDF editing tasks that once required professional desktop software can now be completed directly in the browser.

The entire process works without uploading your files to a backend server, helping preserve document privacy and security while still providing powerful editing capabilities.

Whether you are working with resumes, contracts, academic papers, textbooks, application materials, or everyday PDF documents, ElasticPDF helps make the process easier and more flexible.

Official Website: https://www.elasticpdf.com

We have also carefully prepared a series of video tutorials to help you get started and use ElasticPDF more efficiently:

① Text Editing: https://youtu.be/Mk8hJOb4l4g          
② Image and Graphics Editing: https://youtu.be/htyjlX-eedU          
③ Highlights and Other Annotations: https://youtu.be/VU81Qf3VPlE            
④ Shape Annotations, Including Polygons: https://youtu.be/lgVpriXD0tk          
⑤ Smart PDF Viewer: https://youtu.be/gTTBiILhSrA             
⑥ Complete 15-Minute Tutorial Combining All the Above Modules: https://youtu.be/HWasP3Qfu00      

# 1 Edit Existing Text PDF

In ElasticPDF, editing existing PDF text requires only one click, with no need to convert the file to Word first.

Video demo: **<https://www.bilibili.com/video/BV1VE3F6nEAJ/>**

Users can `add or delete` text and insert `spaces, carriage returns, and line breaks`. This makes it possible to modify names, dates, amounts, reference numbers, addresses, paragraphs, table cells, and fixed template fields.

When the text length changes, ElasticPDF performs `adaptive reflow` according to the width of the text area, font size, character spacing, and layout rules. New content wraps automatically and pushes subsequent text into the correct position. Users can also drag a text box to change its `width, position, and layout area`, providing an editing experience similar to Word.

The following advanced capabilities are also supported:

* Edit vertical, rotated, and arbitrarily angled text.
* Move and rotate an entire text box.
* Change bold styling, color, and alignment.
* Copy and paste styled text.
* Edit Chinese, English, Japanese, Korean, and mixed multilingual content.
* Preserve the original fonts, styles, positions, and page layout.
* Export edited results as a standard PDF.

Switching tools, moving the page out of view, or manually exporting the PDF will **automatically trigger text saving**. The original fonts and layout are strictly preserved, while unedited text remains unchanged.

|  |  |  |
| --- | --- | --- |
| 1 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/70_edit_text_content_zh.png" alt="Text editing feature 1" width="180"> | Delete existing text and enter new font and text content |
| 2 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/71_text_reflow_zh.png" alt="Text editing feature 2" width="180"> | In a paragraph containing multiple sentences, resize the entire text box to make multiple blocks of text reflow and fill the available space adaptively |
| 3 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/72_move_text_block_zh.png" alt="Text editing feature 3" width="180"> | Move the entire text box to another position |
| 4 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/73_rotate_text_zh.png" alt="Text editing feature 4" width="180"> | Edit existing rotated text<br><br>or rotate existing text |
| 5 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/74_bold_text_zh.png" alt="Text editing feature 5" width="180"> | Apply bold formatting to the selected text |
| 6 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/75_text_color_zh.png" alt="Text editing feature 6" width="180"> | Change the text color |
| 7 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/76_text_alignment_zh.png" alt="Text editing feature 7" width="180"> | Align text to the center, left, or right |
| 8 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/77_copy_paste_text_zh.png" alt="Text editing feature 8" width="180"> | Copy and paste text using Cmd/Ctrl+C/V while preserving the original font, color, and other styling |
| 9 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/78_delete_text_block_zh.png" alt="Text editing feature 9" width="180"> | Delete the entire text group |


# 2 Edit Existing Images and Shapes PDF

ElasticPDF allows users to directly select existing images, lines, and color blocks in a PDF and modify them just as they would in Word or PowerPoint.

Video demo: **<https://www.bilibili.com/video/BV19j3F6DELt/>**

After selecting an object, users can `move, scale, and rotate` it, or adjust its `width, height`, and exact position. Page objects that are not modified remain unchanged.

Image and shape editing features include:

* Move, scale, and rotate objects to any angle.
* Crop images and remove unwanted edges, especially useful for `removing black borders from scanned documents`.
* Flip horizontally or vertically.
* Replace an image with a new local image.
* Adjust image opacity.
* Precisely control image dimensions using numeric values.
* Adjust the `image layer order` by moving an object to the top or bottom.
* Move an object one layer forward or backward.
* Save the original image directly to the local device.
* Delete a selected image or shape from the PDF page.

Layer controls prevent `images, text`, and other page objects from covering one another. They are suitable for editing `reports, academic papers, resumes, certificates, logos, QR codes, scanned documents`, and complex illustrated pages.

|  |  |  |  |
| --- | --- | --- | --- |
| 1 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/79_image_transform_controls_zh.png" alt="Image editing tool 1" width="210"> | General controls for rotating, moving, dragging, and changing an object's position, angle, and size |  |
| 2 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/80_crop_image_controls_zh.png" alt="Image editing tool 2" width="210"> | Crop an object | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/81_crop_image_example_zh.png" alt="Image editing example 2" width="280"> |
| 3 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/82_layer_order_controls_zh.png" alt="Image editing tool 3" width="210"> | Bring to front or send to back;<br><br>move one layer forward or backward | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/83_layer_order_example_zh.png" alt="Image editing example 3" width="280"> |
| 4 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/84_rotate_image_controls_zh.png" alt="Image editing tool 4" width="210"> | Rotate an object clockwise or counterclockwise | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/85_rotate_image_example_zh.png" alt="Image editing example 4" width="280"> |
| 5 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/86_flip_image_controls_zh.png" alt="Image editing tool 5" width="210"> | Flip horizontally or vertically | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/87_flip_image_example_zh.png" alt="Image editing example 5" width="280"> |
| 6 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/88_image_opacity_controls_zh.png" alt="Image editing tool 6" width="210"> | Change opacity | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/89_image_opacity_example_zh.png" alt="Image editing example 6" width="280"> |
| 7 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/90_image_size_controls_zh.png" alt="Image editing tool 7" width="210"> | Enter numeric values to resize the object | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/91_image_size_example_zh.png" alt="Image editing example 7" width="280"> |
| 8 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/92_replace_image_controls_zh.png" alt="Image editing tool 8" width="210"> | Replace an image | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/93_replace_image_example_zh.png" alt="Image editing example 8" width="280"> |
| 9 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/94_save_image_controls_zh.png" alt="Image editing tool 9" width="210"> | Save an image or shape to the local device | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/95_save_image_example_zh.png" alt="Image editing example 9" width="280"> |
| 10 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/96_delete_image_controls_zh.png" alt="Image editing tool 10" width="210"> | Delete an object | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/97_delete_image_example_zh.png" alt="Image editing example 10" width="280"> |


# 3 Create or Edit Existing PDF Annotations

## 3.1 Highlights, Comments, Stamps, Freehand Drawing, and Signatures

ElasticPDF provides a complete set of PDF annotation tools that can be created and edited using a mouse or touchscreen:

Video demo: **<https://www.bilibili.com/video/BV1ET3F6ZEUo/>**

* Highlight: Highlights and the text-markup tools listed below—including underlines, strikethroughs, and squiggly lines—support both regular and slanted text. After an annotation is created, users can still modify its range, color, line width, line style, and opacity. These tools are suitable for marking key points, errors, content requiring confirmation, and revision suggestions.
* Underline.
* Strikethrough.
* Squiggly underline.
* Freehand ink.
* Callout annotation.
* Sticky note.
* Text box.
* Image annotation.
* Preset or custom stamp.
* Handwritten signature.

The freehand tool supports continuous drawing, and multiple strokes can be merged automatically. Callouts, sticky notes, and text boxes can identify specific positions on a page and add explanations. Images, stamps, and signatures are suitable for contract confirmation, document review, teaching and grading, status marking, and everyday signing.

Enterprise customers can also use the annotation API to build online collaboration features, including user identity and permission management, annotation JSON import and export, incremental synchronization, accepted or rejected statuses, annotation thumbnails, and controls for selecting, adding, and deleting annotations.

|  |  |  |
| --- | --- | --- |
| 1 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/98_highlight_annotation_icon_zh.png" alt="PDF annotation tool 1" width="64"> | Highlight: Select text and apply highlighting, including to slanted text; the color, range, and other properties can be changed afterward<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/167_highlight_annotation_content_zh.png" alt="Highlight annotation content example" width="360"> |
| 2 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/100_underline_annotation_icon_zh.png" alt="PDF annotation tool 2" width="64"> | Underline: Select text and underline it, including slanted text; the range, line width, line style, color, and other properties can be changed<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/168_underline_annotation_content_zh.png" alt="Underline annotation content example" width="360"> |
| 3 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/101_strikethrough_annotation_icon_zh.png" alt="PDF annotation tool 3" width="64"> | Strikethrough: Supports the same editing options as underline<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/169_strikethrough_annotation_content_zh.png" alt="Strikethrough annotation content example" width="360"> |
| 4 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/102_squiggly_annotation_icon_zh.png" alt="PDF annotation tool 4" width="64"> | Squiggly underline: Supports the same editing options as underline<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/170_squiggly_annotation_content_zh.png" alt="Squiggly annotation content example" width="360"> |
| 5 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/103_freehand_ink_icon_zh.png" alt="PDF annotation tool 5" width="64"> | Freehand ink: Drag to draw lines; consecutive strokes are merged automatically, and the line width, style, and color can be changed<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/171_freehand_ink_content_zh.png" alt="Freehand annotation content example" width="360"> |
| 6 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/104_callout_annotation_icon_zh.png" alt="PDF annotation tool 6" width="64"> | Callout annotation: Complete the drawing with three clicks, then modify its position, content, font, and other properties<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/172_callout_annotation_content_zh.png" alt="Callout annotation content example" width="360"> |
| 7 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/105_sticky_note_icon_zh.png" alt="PDF annotation tool 7" width="64"> | Sticky note: Create with one click to leave a comment at a specific position<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/173_sticky_note_marker_zh.png" alt="Sticky note marker example" width="360"> |
| 8 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/107_text_box_annotation_icon_zh.png" alt="PDF annotation tool 8" width="64"> | Text box: Create with one click and modify its various properties<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/174_text_box_annotation_content_zh.png" alt="Text box annotation content example" width="360"> |
| 9 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/108_image_annotation_icon_zh.png" alt="PDF annotation tool 9" width="64"> | Image: Click or drag to define an area, then select an image to insert<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/175_image_annotation_content_zh.png" alt="Image annotation content example" width="360"> |
| 10 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/109_stamp_annotation_icon_zh.png" alt="PDF annotation tool 10" width="64"> | Stamp: Select a stamp from the list on the left, then click or drag an area to create the annotation; users can create custom text stamps or generate a stamp from a selected annotation<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/176_stamp_annotation_content_zh.png" alt="Stamp annotation content example" width="360"> |
| 11 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/110_signature_annotation_icon_zh.png" alt="PDF annotation tool 11" width="64"> | Signature: Select a signature from the list on the left, then click or drag an area to create the annotation<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/177_signature_annotation_content_zh.png" alt="Signature annotation content example" width="360"> |
| 12 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/112_annotation_style_panel_icon_zh.png" alt="PDF annotation tool 12" width="64"> | Annotation style panel:<br><br>Click to open the properties panel and modify the style of the selected annotation or the default annotation style |
| 13 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/113_undo_annotation_icon_zh.png" alt="PDF annotation tool 13" width="64"> | Undo: Undo an annotation editing operation |
| 14 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/114_redo_annotation_icon_zh.png" alt="PDF annotation tool 14" width="64"> | Redo: Restore an annotation editing operation that was undone |


## 3.2 Rectangles, Arrows, Polygons, Paths, and Hyperlinks

ElasticPDF supports creating and editing rectangles, circles, ellipses, straight lines, arrows, polygons, polylines, and arcs on PDF pages.

Video demo: **<https://www.bilibili.com/video/BV1iJ3P6KE23/>**

Rectangles, circles, and ellipses are suitable for enclosing text, images, tables, and important areas. Lines and arrows can point to errors, connect page objects, or indicate direction. Polygons, polylines, and arcs are suitable for marking irregular regions, boundaries, paths, and curved content.

After a shape has been created, users can continue adjusting its:

* Position.
* Size.
* Rotation angle.
* Border color.
* Fill color.
* Line width.
* Line style.
* Arrow endpoints.
* Polygon and path nodes.

When an initial drawing is not precise enough, there is no need to delete and redraw it. Users can directly drag the control points to modify the shape of a polygon or polyline.

Shape annotations also support adding comments, editing hyperlinks, opening the properties panel, generating stamps, and deleting objects. Shape drawing, node editing, style settings, and link management are integrated into one unified annotation workflow.

|  |  |  |
| --- | --- | --- |
| 1 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/115_rectangle_annotation_icon_zh.png" alt="Shape annotation tool 1" width="64"> | Rectangle: Click or drag to draw a rectangle, then modify the border width, line style, border color, and fill color<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/147_rectangle_annotation_shape_zh.png" alt="Rectangle annotation example" width="360"> |
| 2 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/117_ellipse_annotation_icon_zh.png" alt="Shape annotation tool 2" width="64"> | Circle: Click or drag to draw a circle or ellipse<br><br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/149_ellipse_annotation_shape_zh.png" alt="Ellipse annotation example" width="360"> |
| 3 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/118_line_annotation_icon_zh.png" alt="Shape annotation tool 3" width="64"> | Line: Click or drag to draw a straight line, then modify its line and arrow properties<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/150_line_annotation_shape_zh.png" alt="Line annotation example" width="360"> |
| 4 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/119_arrow_annotation_icon_zh.png" alt="Shape annotation tool 4" width="64"> | Arrow: Click or drag to draw an arrow, then modify its line and arrow properties<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/151_arrow_annotation_shape_zh.png" alt="Arrow annotation example" width="360"> |
| 5 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/120_polygon_annotation_icon_zh.png" alt="Shape annotation tool 5" width="64"> | Polygon: Click multiple times to draw a polygon and double-click the page to finish. Border and fill styles can be changed.<br><br>After selecting the annotation, users can move, scale, and rotate it, or drag its nodes to change the shape<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/152_polygon_annotation_shape_zh.png" alt="Polygon annotation example" width="360"> |
| 6 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/122_polyline_annotation_icon_zh.png" alt="Shape annotation tool 6" width="64"> | Polyline: Click multiple times to draw a polyline and double-click to finish; the line style and color can be changed<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/153_polyline_annotation_shape_zh.png" alt="Polyline annotation example" width="360"> |
| 7 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/123_arc_annotation_icon_zh.png" alt="Shape annotation tool 7" width="64"> | Arc: Click three times to draw an arc, then modify its line style and color<br><br><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/154_arc_annotation_shape_zh.png" alt="Arc annotation example" width="360"> |

## 3.3 Annotation Editing Buttons

After selecting an existing annotation, users can open the comments list and properties panel, modify its style, edit hyperlinks, delete the annotation, or save the current annotation as a reusable stamp. Undo and redo make it easy to correct operations quickly.

|  |  |  |
| --- | --- | --- |
| 1 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/124_comments_button_zh.png" alt="Annotation editing button 1" width="180"> | Comments: Open or close the annotation's comments list |
| 2 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/125_hyperlink_button_zh.png" alt="Annotation editing button 2" width="180"> | Hyperlink: Edit the hyperlink attached to the annotation |
| 3 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/126_properties_panel_button_zh.png" alt="Annotation editing button 3" width="180"> | Properties panel: Open or close the annotation properties panel |
| 4 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/127_create_stamp_button_zh.png" alt="Annotation editing button 4" width="180"> | Create stamp: Convert the current annotation into a reusable stamp |
| 5 | <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/128_delete_annotation_button_zh.png" alt="Annotation editing button 5" width="180"> | Delete: Delete the currently selected annotation |

# 4 Intelligent PDF Reader

ElasticPDF also provides a complete, fully client-side PDF reader. The reader and the text, image, annotation, and shape editing modules all use the same client-side architecture.

Video demo: **<https://www.bilibili.com/video/BV1vW3P6YEnS/>**

## 4.1 Thumbnails, Bookmarks, and Text Search

<div class="joplin-table-wrapper"><table><tbody><tr><td><ul><li><a id="_Hlk235380399"></a><strong>Thumbnails</strong></li><li>Click to jump quickly to a page</li><li>Freely adjust thumbnail size</li><li>A blue outline shows the actual visible area of the viewport</li></ul></td><td><ul><li><strong>Bookmarks</strong></li><li>Click to jump to a page and position</li><li>Use the button on the left to expand or collapse bookmarks</li></ul></td><td><ul><li><strong>Text Search</strong></li><li>Search text throughout the entire document</li><li>Support case-sensitive and whole-word matching</li><li>The selected result is highlighted in blue, while unselected results are highlighted in yellow</li></ul></td></tr><tr><td><p><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/129_thumbnails_panel_zh.png" alt="ElasticPDF UI screenshot" width="300"></p></td><td><p><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/130_bookmarks_panel_zh.png" alt="ElasticPDF UI screenshot" width="300"></p></td><td><p><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/131_text_search_panel_zh.png" alt="ElasticPDF UI screenshot" width="300"></p></td></tr></tbody></table></div>

## 4.2 Zoom Panel, View and Scrolling Settings, and Multilingual UI

<div class="joplin-table-wrapper"><table><tbody><tr><td><ul><li><strong>Zoom Panel</strong></li><li>10%–6400% zoom</li><li>Supports fit-to-page zoom</li><li>Pinch to zoom to any scale</li></ul></td><td><ul><li><strong>Viewing Settings</strong></li><li>Supports continuous and page-by-page modes</li><li>Supports single-page, two-page, and book views</li><li>Supports page rotation and both vertical and horizontal scrolling</li></ul></td><td><ul><li><strong>Multilingual UI</strong></li><li>Includes 13 languages for global use</li><li>Simplified Chinese, English, Traditional Chinese, Japanese, Korean, and Vietnamese</li><li>German, Spanish, French, Italian, Dutch, Portuguese, and Russian</li></ul></td></tr><tr><td><p><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/132_zoom_panel_zh.png" alt="ElasticPDF UI screenshot" width="300"></p></td><td><p><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/133_viewing_settings_zh.png" alt="ElasticPDF UI screenshot" width="300"></p></td><td><p><img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/134_multilingual_ui_zh.png" alt="ElasticPDF UI screenshot" width="300"></p></td></tr></tbody></table></div>

## 4.3 Light Mode and Dark Mode

|  |
| --- |
| <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/135_light_mode_zh.png" alt="ElasticPDF light mode" width="760"> |
| <img src="https://raw.githubusercontent.com/ElasticPDF/elasticpdf/main/images/20260805/136_dark_mode_zh.png" alt="ElasticPDF dark mode" width="760"> |

# Summary

ElasticPDF integrates five core capabilities into one unified PDF product:

1. Directly edit existing PDF text with automatic line wrapping and intelligent reflow.
2. Edit existing PDF images and shapes, including cropping, replacement, and layer management.
3. Create complete annotations such as highlights, comments, freehand drawings, stamps, and signatures.
4. Draw rectangles, arrows, polygons, and paths, and add hyperlinks.
5. Read PDFs with thumbnails, bookmarks, full-text search, up to 6400% zoom, and a multilingual interface.

* For individual users: Read PDFs, modify text, adjust images, add annotations and signatures, and create graphical markup for free.

* For enterprise customers: Access an integrable, self-hostable, cross-platform PDF Viewer and editing SDK with controllable data boundaries, and combine text, image, annotation, shape, and reading modules according to business requirements.

This solution is suitable for anyone looking for a free PDF editor, PDF editing SDK, browser-based PDF editor, PDF Viewer, PDF annotation SDK, or a document editing engine that supports private deployment.

Visit the ElasticPDF official website to learn more and try it: **<https://www.elasticpdf.com>**
