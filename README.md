# agjgd

[![MIT License](https://img.shields.io/badge/license-MIT-0366d6.png?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADYAAAAcCAYAAAAqckyNAAABS2lUWHRYTUw6Y29tLmFkb2JlLnhtcAAAAAAAPD94cGFja2V0IGJlZ2luPSLvu78iIGlkPSJXNU0wTXBDZWhpSHpyZVN6TlRjemtjOWQiPz4KPHg6eG1wbWV0YSB4bWxuczp4PSJhZG9iZTpuczptZXRhLyIgeDp4bXB0az0iQWRvYmUgWE1QIENvcmUgNS42LWMxMzggNzkuMTU5ODI0LCAyMDE2LzA5LzE0LTAxOjA5OjAxICAgICAgICAiPgogPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4KICA8cmRmOkRlc2NyaXB0aW9uIHJkZjphYm91dD0iIi8+CiA8L3JkZjpSREY+CjwveDp4bXBtZXRhPgo8P3hwYWNrZXQgZW5kPSJyIj8+IEmuOgAAAGxJREFUWIXt1tEJgDAMAFErbpT9N+hO+m0pokVoL9z7UypyBCUlIs6trzTXq517tI88RGAYjWE0x8R3t3+/oXO11u79tBMzjGbmN/b3hnKTdmKG0RhGYxiNYTRfNo+32/gS0k7MMBrDaAyjuQCAGAo9rf4wcgAAAABJRU5ErkJggg==)](https://github.com/agjgd/agjgd/blob/master/LICENSE)
[![Current Release](https://img.shields.io/github/release/agjgd/agjgd.png?colorB=0366d6&logo=github)](https://github.com/agjgd/agjgd/releases)
[![GitHub Stars](https://img.shields.io/github/stars/agjgd/agjgd.png?colorB=0366d6&logo=github)](https://github.com/agjgd/agjgd/stargazers)
[![Contributors](https://img.shields.io/github/contributors/agjgd/agjgd.png?colorB=0366d6&logo=github)](https://github.com/agjgd/agjgd/graphs/contributors)
[![Packagist Downloads](https://img.shields.io/packagist/dt/agjgd/agjgd.png?colorB=0366d6&logo=data:image/png;base64,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)](https://packagist.org/packages/agjgd/agjgd/stats)
[![Issues](https://img.shields.io/github/issues/agjgd/agjgd.png?colorB=0366d6&logo=github)](https://github.com/agjgd/agjgd/issues)

<p align="center"><a href="https://agjgd.org/" title=""><img src="https://agjgd.org/documentation/agjgd.org/images/avatar.png" alt="" title="" width="400" id="avatar" /></a></p>

## Description

**agjgd** is a collection of projects started by [Andrew G. Johnson](https://github.com/andrewgjohnson) for [PHP](http://php.net)'s [GD](http://php.net/manual/book.image.php) library.

All **agjgd** projects:
 * [imagettftextblur](https://imagettftextblur.agjgd.org/) ([GitHub](https://github.com/andrewgjohnson/imagettftextblur), [Packagist](https://packagist.org/packages/andrewgjohnson/imagettftextblur) & [Twitter](https://twitter.com/imagettftextblu))
 * [imagettftextgradient](https://imagettftextgradient.agjgd.org/) ([GitHub](https://github.com/andrewgjohnson/imagettftextgradient), [Packagist](https://packagist.org/packages/andrewgjohnson/imagettftextgradient) & [Twitter](https://twitter.com/imagettftextgra))
 * [imageblendedcolorallocate](https://imageblendedcolorallocate.agjgd.org/) ([GitHub](https://github.com/andrewgjohnson/imageblendedcolorallocate), [Packagist](https://packagist.org/packages/andrewgjohnson/imageblendedcolorallocate) & [Twitter](https://twitter.com/imagebca))
 * [imagecolorallocatefromstring](https://imagecolorallocatefromstring.agjgd.org/) ([GitHub](https://github.com/andrewgjohnson/imagecolorallocatefromstring), [Packagist](https://packagist.org/packages/andrewgjohnson/imagecolorallocatefromstring) & [Twitter](https://twitter.com/imagecafs))
 * [imagegradientrectangle](https://imagegradientrectangle.agjgd.org/) ([GitHub](https://github.com/andrewgjohnson/imagegradientrectangle), [Packagist](https://packagist.org/packages/andrewgjohnson/imagegradientrectangle) & [Twitter](https://twitter.com/imagegradrect))
 * [linebreaks4imagettftext](https://linebreaks4imagettftext.agjgd.org/) ([GitHub](https://github.com/andrewgjohnson/linebreaks4imagettftext), [Packagist](https://packagist.org/packages/andrewgjohnson/linebreaks4imagettftext) & [Twitter](https://twitter.com/lb4ittft))

## Usage

### With Composer

This project offers support for the [Composer](https://getcomposer.org/) dependency manager.  You can find the agjgd package online on [packagist.org](https://packagist.org/packages/agjgd/agjgd).

#### Install using Composer

Either run this command:

    composer require agjgd/agjgd

or add this to the `require` section of your composer.json file:

    "agjgd/agjgd": "1.*"

### Without Composer

To use without Composer you will need to set up each project individually.

## Help Requests

Please post any questions on [stackoverflow.com](https://stackoverflow.com/) if you need help.

If you discover a bug please enter an issue on GitHub.

## Acknowledgements

Full list of contributors across all projects:
 * [Andrew G. Johnson (@andrewgjohnson)](https://github.com/andrewgjohnson)
 * [Philip van Heemstra (@vHeemstra)](https://github.com/vHeemstra)

Our [issue template](https://github.com/agjgd/agjgd/blob/master/ISSUE_TEMPLATE.md) & [pull request template](https://github.com/agjgd/agjgd/blob/master/PULL_REQUEST_TEMPLATE.md) come via the [stevemao/github-issue-templates](https://github.com/stevemao/github-issue-templates) project. The [mountains photo](https://unsplash.com/photos/qJvpykJ5SKs) comes via [Gabriel Garcia Marengo](https://unsplash.com/@gabrielgm).

## Changelog

You can find all notable changes in the [changelog](https://github.com/agjgd/agjgd/blob/master/CHANGELOG.md).
