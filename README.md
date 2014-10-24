#SweetAlert

An awesome replacement for JavaScript's alert by Tristan Edwards.

#Tweaks

* Added feature for Sweet Alert to be used as a wait dialog by passing using setting the option `waitDialog` to 'true'. The dialog can be ended by calling the method 
`swalCloseModal()`.

* Added feature for Sweet Alert to include HTML code in its buttons, set `allowHTML` to 'true' and pass HTML code to the `confirmButtonText` option.

* Fixed bug where the Tab key would stop navigating the web page when two 
SweetAlert dialogs are opened.

#Examples

[See it in action!](http://tristanedwards.me/sweetalert)

![A success modal](https://raw.github.com/t4t5/sweetalert/master/sweetalert.gif)

#Usage

You can install SweetAlert through bower:

```bash
bower install sweetalert
```

Alternatively, download the package and reference the JavaScript and CSS files manually:

```html
<script src="lib/sweet-alert.min.js"></script>
<link rel="stylesheet" type="text/css" href="lib/sweet-alert.css">
```

#SASS
The css is built with the `--style compressed` and `--sourcemap=none` options:

    sass --style compressed --sourcemap=none sweet-alert.scss sweet-alert.css
