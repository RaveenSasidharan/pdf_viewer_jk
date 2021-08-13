# Changelog
## [2.1.5]
- updated dependencies

## [2.1.4]
- Fixed Issue #15 . https://github.com/jawadsahil/pdf_viewer_jk/issues/15
- removed numberpicker package
- updated dependencies

## [2.1.3]

- Fixed issue #16 . https://github.com/jawadsahil/pdf_viewer_jk/issues/16

## [2.1.2]

- Merge pull request #13.
- Upgraded dependencies.
- Dart format code

## [2.1.1]

- Upgraded dependencies.
- Dart format code

## [2.1.0]

- Upgraded dependencies.

## [2.0.0-nullsafety.2]

- Removed obsolete code.

## [2.0.0-nullsafety.1]

- Applied null safety guidelines.


## [1.2.0]

- updated dependencies
- as flutter_advanced_networkimage is archived, so the code is encorporated in the plugin. [Credits](https://github.com/mchome)


## [1.1.0]

- Custom navigation color
- Exposing `ZoomableWidget` from [flutter_advanced_networkimage](https://pub.dartlang.org/packages/flutter_advanced_networkimage) parameters (minScale, zoomSteps, maxScale,panLimit)
- Page controller initial page setting fixed (making able to set initially loaded page)
- Proper android cache cleanup
- Option to pass in controller `PDFViewer(document: document,controller: PageController())` that you can use to control the pageview rendering the PDF pages.
- Option to preload all pages in memory `PDFViewer(document: document,lazyLoad: false)`
- Option to disable swipe navigation `PDFViewer(document: document,scrollDirection: Aixs.vertical)`
- Option to change scroll axis to vertical or horizontal `PDFViewer(document: document,scrollDirection: Aixs.vertical)`
- Removed rxdart dependency
- Upgraded to androidX
- Added support to optional header while loading document from url
- Auto hide picker for 1 page documents
- Swipe control
- Zoom scale up to 5.0

## [1.0.1]

- updated dependencies

## [1.0.0]

- version number as stable.
- added example

## [0.0.4]

- fixed issue -- ios header files missing.

## [0.0.3]

- fixed issue -- No podspec found.

## [0.0.2]

- fixed few missing code parts.

## [0.0.1]

- initial release.
