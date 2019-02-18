[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/coliff/bootstrap-rfs/master/LICENSE)
[![](https://data.jsdelivr.com/v1/package/gh/coliff/bootstrap-rfs/badge)](https://www.jsdelivr.com/package/gh/coliff/bootstrap-rfs)
[![github-stars-image](https://img.shields.io/github/stars/coliff/bootstrap-rfs.svg?label=github%20stars)](https://github.com/coliff/bootstrap-rfs)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

# Responsive Font Sizes (RFS) for Bootstrap 4

Bootstrap 4.3 introduced [Responsive Font Sizes (RFS)](https://getbootstrap.com/docs/4.3/content/typography/#responsive-font-sizes) which you can enable in the SCSS compiler. If you're compiling the CSS for your project I highly recommend turning it on.

If you're loading Bootstrap from a CDN though you won't be able to take advantage of those RFS rules. This repo offers a quick fix - a tiny CSS file with the relevant changes.

## Usage

A couple of options are available:

- **Copy the CSS rules to your site**

1.  Copy the `bootstrap-rfs.css` rules to your site's CSS
2.  Add the following to your sites `<head>` (after loading Bootstrap's) - `<link href="bootstrap-rfs.css" rel="stylesheet">`

- **Use a CDN**

1. Add the following to your sites `<head>` (after loading Bootstrap's) - `<link href="https://cdn.jsdelivr.net/gh/coliff/bootstrap-rfs/bootstrap-rfs.css" rel="stylesheet">`

Optional: You can add `media="screen and (max-width: 1200px)"` so it will only load the CSS file on screens up to 1200px, saving a HTTP request for users with larger screens. The CSS has the 'max-width: 1200px' media query included as well so this is optional.

## Demo

[See a demo of Bootstrap 4.3 with RFS](https://project-rfs.github.io/)
