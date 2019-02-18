[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/coliff/bootstrap-rfs/master/LICENSE)
[![](https://data.jsdelivr.com/v1/package/gh/coliff/bootstrap-rfs/badge)](https://www.jsdelivr.com/package/gh/coliff/bootstrap-rfs)
[![github-stars-image](https://img.shields.io/github/stars/coliff/bootstrap-rfs.svg?label=github%20stars)](https://github.com/coliff/bootstrap-rfs)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

# Responsive Font Sizes (RFS) for Bootstrap 4

Bootstrap 4.3 introduced Responsive Font Sizes (RFS) which you can enable in the SCSS compiler. If you're compiling the CSS for your project I highly recommend turning it on.

If you're loading Bootstrap from a CDN though you won't be able to take advantage of those RFS rules. This repo offers a quick fix. It's essentially a tiny CSS file with the relevant changes.

### Usage

A couple of options are available:

- **Copy the CSS rules to your site**

1.  Copy the `responsive-rfs.css` rules to your site's CSS
2.  Add the following to your sites `<head>` (after loading Bootstrap's) - `<link href="responsive-rfs.css" media="screen and (max-width: 1200px)" rel="stylesheet">`

- **Use a CDN**

1. Add the following to your sites `<head>` (after loading Bootstrap's) - `<link href="https://cdn.jsdelivr.net/gh/coliff/bootstrap-rfs/responsive-rfs.min.css" media="screen and (max-width: 1200px)" rel="stylesheet">`

Note: the `media="screen and (max-width: 1200px)"` will only load the stylesheet on screens up to 1200px, saving a HTTP request for larger screens. You can omit this from the HTML though if you wish. The CSS has the media query included as well.
