# Sitefinity 5 HTML5Boilerplate template and theme

An empty starting point for theme development based on HTML5Boilerplate & Modernizr compatible with Sitefinity's layout editor and Sitefinity Thunder.
This theme has no widget styling, but offers only a clean cross-browser normalized startingpoint, weighing only 2.7Kb without any extra markup.
Comes with 1 masterpage, 3 css files (normalize, layout & layout_transformations) and pre-packed with minified production ready Modernizr.


## Quick start

Copy the entire unzipped files inside your solutions /App_Data/WebsiteTemplates folder. Rename the folder to suit your needs.
Choose whether you want minified CSS, development CSS or .LESS files and publish your site.


## Features

* A Sitefinity optimized port of the HTML5 Boilerplate project (http://html5boilerplate.com).
* HTML5 ready, with ARIA role definition and fallback browser support through Modernizr
* Based on and compatible with the standard Sitefinity lay-out region editor.
* Cross browser CSS normalizations and vertical rhythm.
* Responsive design & mobile friendly with Sitefinity column support
* The latest jQuery via CDN, with a local fallback.
* Browser hack and W3C validation breakers singled out.
* Support for .LESS and .CSS.


## LESS vs CSS

Inside the App_Themes/Global directory you'll find 3 types of files, .yui.less, .min.css and .css.
* The .min.css files are minified and production ready.
* The .css are development css files.
* The .yui.less files are the .LESS versions with variables of the .css files.
If you're comfortable with .less, use it otherwise just delete them. If you don't need minified css, delete the .min.css files.


## Responsive design & Mobile friendly media-queries
Out of the box this theme & template are already responsive and mobile friendly. Inside the layout_transformations.css (or .less) you'll
find a print and a mobile media-query already defined which is fully compatible with Sitefinity's layout editor.


## 1 column Masterpage
Inside the App_Master directory you'll find only 1 masterpage.
It is a HTML5 accessibility enhanced template based on 1 column layout, for easy alteration inside Sitefinity's layout editor. 
Header, nav, section and footer are defined with all the ARIA landmark roles. 
Complete with extra scriptwrapper placeholder which won't out on live sites so script & stylewidgets can be safely placed without breaking the PageEditor.


## Javascript & jQuery
jQuery is loaded from CDN with local fallback option. The masterpage references 2 .js files, script.top.min.js and script.bottom.min.js to seperate javascript loading.
The script.top.min.js already contains the latest minified Modernizr, script.bottom.min.js is empty and ready for your projects javascript/jQuery.


## Sitefinity-icons
Included are all precomposed icons for the iPhone/iPad & Android devices, and Windows 8 pinning. 
The favicon.ico comes in 2 flavors. The default favicon.ico is 64x64 which is enhanced for IE9/IE10 sitepinning, an old 16x16 icon is included.


## Contributing
Credits are due where credits go and special thanks to @stevemcniven and @timw255. For comments or questions use twitter @jbokkers


## License

### Major components:

* jQuery: MIT/GPL license
* Modernizr: MIT/BSD license
* Normalize.css: Public Domain

### Everything else:

The Unlicense (aka: public domain)
