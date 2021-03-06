### 2014-05-13 v0.4.2

* Fix deps.

### 2014-05-13 v0.4.1

* Remove --windows-compatibility switch because it causes problems on Windows.
* Fix IE7 option (by [@peter-mouland](https://github.com/peter-mouland)).

### 2014-05-07 v0.4.0

* Normalize fonts by default (#108).
* Try to fix slashes on Windows again (#109, #126).
* Improve error message when fontforge fails (#10, #135).
* Show svgicons2svgfont “warnings” only in verbose mode (#107).

### 2014-03-03 v0.3.4

* Fix codepoints format bug (by [@reklis](https://github.com/reklis)).
* Fix CamelCase files handling (#116).
* Escape regexp to work with Windows paths (#127).

### 2014-02-13 v0.3.3

* `startCodepoint` option (by [@DanForys](https://github.com/DanForys)).
* Fix slash for Windows (should fix #109 , by [@MoOx](https://github.com/MoOx)).
* Sort files in fontforge script (should fix #91).
* Add `line-height` to icons (#112).
* Preserve CamelCased class names (#116).
* Template’s JSON file could be omitted (#81).

### 2014-01-22 v0.3.2

* Update svgicons2svgfont.

### 2014-01-20 v0.3.1

* Fixed failing npm install (by [@bloodyowl](https://github.com/bloodyowl)).
* Added optional IE7 support (by [@bloodyowl](https://github.com/bloodyowl)).

### 2014-01-10 v0.3.0

* Experimental `node` engine (should works on Windows).
* Tweak ttfautohint options.

### 2013-12-13 v0.2.2

* You can use templates with any extension: `.sass` for example (by [@borodean](https://github.com/borodean)).
* SVG fonts disabled by default.

### 2013-11-17 v0.2.1

* `templateOptions` option and templates refactoring (by [@tylerbeck](https://github.com/tylerbeck)).
* Improve fontforge result parsing (by [@jantimon](https://github.com/jantimon)).
* Tweak HTML demo page look & feel.
* Tweak `ttfautohint` call.

### 2013-10-29 v0.2.0

* Huge code refactoring.
* Templates refactoring (see readme and #55).
* Scripts now really works in Python 3 (#50).
* Smarter warnings handling (#38).
* `order` option.

### 2013-10-28 v0.1.12

* Scripts should work on Python 3 now.
* Custom HTML demo template receives CSS options (by [@andreu86](https://github.com/andreu86)).
* Readme improvements (by [@mrzmyr](https://github.com/mrzmyr)).

### 2013-10-23 v0.1.11

* Autohint for all formats (by [@borodean](https://github.com/borodean)).

### 2013-10-16 v0.1.10

* `rename` option.
* Quote Base64 strings to prevent errors in Stylus.

### 2013-09-22 v0.1.9

* Fix handling pathes with spaces.
* Font smoothing for Firefox on OS X (by [@MoOx](https://github.com/MoOx)).
* Deprecated `md5` Pyhton module replaced with `hashlib` (by [@Nyalab](https://github.com/Nyalab)).

### 2013-08-21 v0.1.8

* Set glyphs width automatically.

### 2013-08-21 v0.1.7

* Ligatures (by [@prehnRA](https://github.com/prehnRA)).

### 2013-08-20 v0.1.6

* Bug fixes.

### 2013-06-30 v0.1.5

* `destHtml` option (by [@timhettler](https://github.com/timhettler)).
* Improved kerning (by [@frekw](https://github.com/frekw)).

### 2013-05-08 v0.1.4

* `htmlDemoTemplate` option (by [@andreu86](https://github.com/andreu86)).
* Various bug fixes and tweaks (thanks [@MoOx](https://github.com/MoOx), [@iham](https://github.com/iham), [@timhettler](https://github.com/timhettler)).

### 2013-04-30 v0.1.3

* HTML demo works with CSS preprocessors stylesheets.
* TTF files embedding (by [@katzlbt](https://github.com/katzlbt) and me).
* Don not stop Grunt when font contains no glyphs (by [@iham](https://github.com/iham)).
* Better fontforge stdout handling (by [@MoOx](https://github.com/MoOx)).

### 2013-04-13 v0.1.2

* `relativeFontPath` option (by [@gregvanbrug](https://github.com/gregvanbrug)).
* `template` option.
* Better LESS support (by [@gregvanbrug](https://github.com/gregvanbrug)).
* Better Stylus support.
* Bug fixes.

### 2013-03-17 v0.1.1

* Fix error when generating font with one glyph.

### 2013-02-18 v0.1.0

* Grunt 0.4 support.
* Separate CSS/font destinations (by [@scanieso](https://github.com/scanieso)).
* Minimal CSS preprocessors support (by [@MoOx](https://github.com/MoOx)).
* Updated generator script (by [@MoOx](https://github.com/MoOx) and me).
* Generated CSS not include broken links to font files.
* Data:uri WOFF files embedding.
