Editor.md
Open source online Markdown editor.

```
Side information: To use the application in a special environment use ```lorem ipsum``` to start
## Collaboration
***
Give instructions on how to collaborate with your project.
> Maybe you want to write a quote in this part. 
> It should go over several rows?
> This is how you do it.
## FAQs
***
A list of frequently asked questions
1. **This is a question in bold**
Answer of the first question with _italic words_. 
2. __Second question in bold__ 
To answer this question we use an unordered list:
* First point
* Second Point
* Third point
3. **Third question in bold**
Answer of the third question with *italic words*.
4. **Fourth question in bold**
| Headline 1 in the tablehead | Headline 2 in the tablehead | Headline 3 in the tablehead |
|:--------------|:-------------:|--------------:|
| text-align left | text-align center | text-align right |
​
​
​
​
​
​
​
    <!DOCTYPE html>
    <html>
    <head>
      <title>Carga de Archivos e Imágenes</title>
    </head>
    <body>
      <h2>Carga de Archivos e Imágenes</h2>
      <form action="procesar_formulario.php" method="POST" enctype="multipart/form-data">
        <label for="nombre_archivo">Nombre del archivo:</label>
        <input type="text" name="nombre_archivo" id="nombre_archivo" required><br><br>
        
        <label for="archivo">Selecciona el archivo:</label>
        <input type="file" name="archivo" id="archivo" required><br><br>
        
        <input type="submit" value="Cargar archivo">
      </form>
    </body>
    </html>
    
​
Table of Contents
General Info
Technologies
Installation
Collaboration
FAQs
General Info
Write down the general informations of your project. It is worth to always put a project status in the Readme file. This is where you can add it.

<!DOCTYPE html>
<html>
<head>
  <title>Carga de Archivos e Imágenes</title>
</head>
<body>
  <h2>Carga de Archivos e Imágenes</h2>
  <form action="procesar_formulario.php" method="POST" enctype="multipart/form-data">
    <label for="nombre_archivo">Nombre d
    <!DOCTYPE html>
    <html>
    <head>
      <title>Carga de Archivos e Imágenes</title>
    </head>
    <body>
      <h2>Carga de Archivos e Imágenes</h2>
      <form action="procesar_formulario.php" method="POST" enctype="multipart/form-data">
        <label for="nombre_archivo">Nombre del archivo:</label>
        <input type="text" name="nombre_archivo" id="nombre_archivo" required><br><br>
        <label for="archivo">Selecciona el archivo:</label>
        <input type="file" name="archivo" id="archivo" required><br><br>
        <input type="submit" value="Cargar archivo">
      </form>
    </body>
    </html>
    el archivo:</label>
    <input type="text" name="nombre_archivo" id="nombre_archivo" required><br><br>
    <label for="archivo">Selecciona el archivo:</label>
    <input type="file" name="archivo" id="archivo" required><br><br>
    <input type="submit" value="Cargar archivo">
  </form>
</body>
</html>
Screenshot
Image text

Technologies
A list of technologies used within the project:

Technologie name: Version 12.3
Technologie name: Version 2.34
Library name: Version 1234
Installation
A little intro about the installation.

$ git clone https://example.com
$ cd ../path/to/the/file
$ npm install
$ npm start
Side information: To use the application in a special environment use lorem ipsum to start

Collaboration
Give instructions on how to collaborate with your project.

Maybe you want to write a quote in this part.
It should go over several rows?
This is how you do it.

FAQs
A list of frequently asked questions

This is a question in bold
Answer of the first question with italic words.
Second question in bold
To answer this question we use an unordered list:
First point
Second Point
Third point
Third question in bold
Answer of the third question with italic words.
Fourth question in bold
| Headline 1 in the tablehead | Headline 2 in the tablehead | Headline 3 in the tablehead |
|:———————|:——————-:|———————:|
| text-align left | text-align center | text-align right |
<!DOCTYPE html>
<html>
<head>
  <title>Carga de Archivos e Imágenes</title>
</head>
<body>
  <h2>Carga de Archivos e Imágenes</h2>
  <form action="procesar_formulario.php" method="POST" enctype="multipart/form-data">
    <label for="nombre_archivo">Nombre del archivo:</label>
    <input type="text" name="nombre_archivo" id="nombre_archivo" required><br><br>
    <label for="archivo">Selecciona el archivo:</label>
    <input type="file" name="archivo" id="archivo" required><br><br>
    <input type="submit" value="Cargar archivo">
  </form>
</body>
</html>
Example
<link rel="stylesheet" href="editormd/css/editormd.css" />
<div id="test-editor">
    <textarea style="display:none;">### Editor.md

**Editor.md**: The open source embeddable online markdown editor, based on CodeMirror & jQuery & Marked.
    </textarea>
</div>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script src="editormd/editormd.min.js"></script>
<script type="text/javascript">
    $(function() {
        var editor = editormd("test-editor", {
            // width  : "100%",
            // height : "100%",
            path   : "editormd/lib/"
        });
    });
</script>Copy
More Examples >>

Features
Support Standard Markdown / CommonMark and GFM(GitHub Flavored Markdown);
Full-featured: Real-time Preview, Image (cross-domain) upload, Preformatted text/Code blocks/Tables insert, Code fold, Search replace, Read only, Themes, Multi-languages, L18n, HTML entities, Code syntax highlighting...;
Markdown Extras : Support ToC (Table of Contents), Emoji, Task lists, @Links...;
Support TeX (LaTeX expressions, Based on KaTeX), Flowchart and Sequence Diagram of Markdown extended syntax;
Support identification, interpretation, fliter of the HTML tags;
Support AMD/CMD (Require.js & Sea.js) Module Loader, and Custom/define editor plugins;
Compatible with all major browsers (IE8+), compatible Zepto.js and iPad;
Support Custom theme styles;
Download & install
Latest version: v1.5.0，Update: 2015-06-09



 


Or NPM install:

npm install editor.md



Or Bower install:

bower install editor.md




Change logs:

CHANGES

Dependents
Projects :

CodeMirror
marked
jQuery
FontAwesome
github-markdown.css
KaTeX
Rephael.js
prettify.js
flowchart.js
sequence-diagram.js
Prefixes.scss

Development tools :

Visual Studio Code
Sass/Scss
Gulp.js
License
Editor.md follows the MIT License, Anyone can freely use.





Fork me on Github :







Users

 Contact Us: editor.md@ipandao.com


Editor.md
Copyright © 2015-2019 Editor.md, MIT license.

Design & Develop By: Pandao     
