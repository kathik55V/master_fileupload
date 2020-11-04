
##FILE UPLOAD
An enhanced HTML 5 file input for Bootstrap 3.x and 4.x with file preview for various files, offers multiple selection, resumable chunk uploads, and more. The plugin allows you a simple way to setup an advanced file picker/upload control built to work specially with Bootstrap 3.x or 4.x CSS3 styles. It enhances the file input functionality further, by offering support to preview a wide variety of files i.e. images, text, html, video, audio, flash, and objects. In addition, it includes AJAX based uploads, dragging &amp; dropping files, viewing upload progress, and selectively previewing, adding, or deleting files. 

> NOTE: Version 5.x is a significant rewrite. With version 5.x, the plugin code has been revamped with enhanced file management, resumable chunk uploads support, and other new features. You can go through the various closed enhancements and features and documented for [Release 5.x milestone](https://github.com/kartik-v/bootstrap-fileinput/milestone/1?closed=1).   

![ Default Theme](https://user-images.githubusercontent.com/3592619/60393698-ea1fc280-9b36-11e9-9f16-b27c529d6819.png)

![ Explorer Theme](https://user-images.githubusercontent.com/3592619/60393721-51d60d80-9b37-11e9-991c-810c942ac516.png)

## Pre-requisites  

1. [Bootstrap 3.x or 4.x](http://getbootstrap.com/)
2. Latest [JQuery](http://jquery.com/)
3. Most modern browsers supporting HTML5 (inputs and FileReader API) including CSS3 & JQuery. For Internet Explorer, one must use IE versions 10 and above. IE9 and below will work as a normal file input, and will not support multiple file selection or the HTML 5 FileReader API.
4. With release 4.0, AJAX uploads are supported. AJAX uploads require that the browser support HTML5 FormData and XHR2 (XMLHttpRequest 2). Most modern browsers support FormData and XHR2. The plugin will automatically degrade to normal form based submission for browsers not supporting AJAX uploads

## Installation

### Using Bower
To install using the `bower` package manager run:

    bower install bootstrap-fileinput

### Using NPM
To install using the `npm` package manager run:

    npm install bootstrap-fileinput

### Manual Install

You can also manually install the plugin easily to your project. Just download the source [ZIP](https://github.com/kartik-v/bootstrap-fileinput/zipball/master) or [TAR ball](https://github.com/kartik-v/bootstrap-fileinput/tarball/master) and extract the plugin assets (css and js folders) into your project.

If you noticed, you need to load the `jquery.min.js` and `bootstrap.min.css` in addition to the `fileinput.min.css` and `fileinput.min.js`. The theme file `themes/fa/theme.js` can be optionally included for the font awesome icons styling. The locale file `<lang>.js` can be optionally included for translating for your language if needed.

**Optional Dependent Plugins**

- The `piexif.min.js` file is the source for the [Piexifjs plugin by hMatoba](https://github.com/hMatoba/piexifjs). It is required to be loaded before `fileinput.min.js` if you wish to use the image resize feature of the **bootstrap-fileinput** plugin. 
- The `sortable.min.js` file is the source for the [Sortable plugin by rubaxa](https://github.com/rubaxa/Sortable). It is required to be loaded before `fileinput.min.js` if you wish to sort the thumbnails in the initial preview.
- The `purify.min.js` file is the source for the [DomPurify plugin by cure53](https://github.com/cure53/DOMPurify). It is required to be loaded before `fileinput.min.js` if you wish to purify your HTML for HTML content preview.

For ease of access, the sources for the above plugins are included in the `js/plugins` folder of this project repository.

Step 2: Initialize the plugin on your page. For example,

```js
// initialize with defaults
$("#input-id").fileinput();

// with plugin options
$("#input-id").fileinput({'showUpload':false, 'previewFileType':'any'});
```

The `#input-id` is the identifier for the input (e.g. `type = file`) on your page, which is hidden automatically by the plugin. 

Alternatively, you can directly call the plugin options by setting data attributes to your input field.

```html
<input id="input-id" type="file" class="file" data-preview-file-type="text" >
```

## Contributors

### Code Contributors

This project exists thanks to all the people who contribute. [[Contribute](.github/CONTRIBUTING.md)].
<a href="https://github.com/kartik-v/bootstrap-fileinput/graphs/contributors"><img src="https://opencollective.com/bootstrap-fileinput/contributors.svg?width=890&button=false" /></a>

### Financial Contributors

Become a financial contributor and help us sustain our community. [[Contribute](https://opencollective.com/bootstrap-fileinput/contribute)]

#### Individuals

<a href="https://opencollective.com/bootstrap-fileinput"><img src="https://opencollective.com/bootstrap-fileinput/individuals.svg?width=890"></a>

#### Organizations

Support this project with your organization. Your logo will show up here with a link to your website. [[Contribute](https://opencollective.com/bootstrap-fileinput/contribute)]

<a href="https://opencollective.com/bootstrap-fileinput/organization/0/website"><img src="https://opencollective.com/bootstrap-fileinput/organization/0/avatar.svg"></a>
<a href="https://opencollective.com/bootstrap-fileinput/organization/1/website"><img src="https://opencollective.com/bootstrap-fileinput/organization/1/avatar.svg"></a>
<a href="https://opencollective.com/bootstrap-fileinput/organization/2/website"><img src="https://opencollective.com/bootstrap-fileinput/organization/2/avatar.svg"></a>
<a href="https://opencollective.com/bootstrap-fileinput/organization/3/website"><img src="https://opencollective.com/bootstrap-fileinput/organization/3/avatar.svg"></a>
<a href="https://opencollective.com/bootstrap-fileinput/organization/4/website"><img src="https://opencollective.com/bootstrap-fileinput/organization/4/avatar.svg"></a>
<a href="https://opencollective.com/bootstrap-fileinput/organization/5/website"><img src="https://opencollective.com/bootstrap-fileinput/organization/5/avatar.svg"></a>
<a href="https://opencollective.com/bootstrap-fileinput/organization/6/website"><img src="https://opencollective.com/bootstrap-fileinput/organization/6/avatar.svg"></a>
<a href="https://opencollective.com/bootstrap-fileinput/organization/7/website"><img src="https://opencollective.com/bootstrap-fileinput/organization/7/avatar.svg"></a>
<a href="https://opencollective.com/bootstrap-fileinput/organization/8/website"><img src="https://opencollective.com/bootstrap-fileinput/organization/8/avatar.svg"></a>
<a href="https://opencollective.com/bootstrap-fileinput/organization/9/website"><img src="https://opencollective.com/bootstrap-fileinput/organization/9/avatar.svg"></a>

## License

**bootstrap-fileinput** is released under the BSD-3-Clause License. See the bundled `LICENSE.md` for details.
