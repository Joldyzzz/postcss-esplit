## [0.1.2] - 2017-03-31
* [#5](https://github.com/VitaliyR/postcss-esplit/issues/5) Fix splitting non-breakable at-rules

## [0.1.1] - 2017-03-31
* Add *fileNameStartIndex* option

## [0.1.0] - 2016-05-18
* Improved performance of processing children nodes

## [0.0.5] - 2016-05-16
* Fixed insert of import nodes before @charset declaration

## [0.0.4] - 2016-05-16
* Fixed bug with wrong import order
* Improved selectors separation by splitting nested selectors
* Refactor node moves methods
* Added counter for selectors count for splitted files

## [0.0.3] - 2015-01-02
* Removed IDE garbage from npm repository
* Fixed bug with passing source map options to children roots

## [0.0.2] - 2015-11-20
* [#3](https://github.com/VitaliyR/postcss-esplit/pull/3) Fixed scope bugs when processing a lot of files
* Fixed reprocessing performance by handling which plugins already finished process and which aren't
* Fixed handling plugin duplicates in processor plugins list

## [0.0.1] - 2015-11-12
* Initial release
