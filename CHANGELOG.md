# Changelog
This file contains highlights of what changes on each version of the [Gulp-PHP-Minify](https://github.com/aquafadas-com/gulp-php-minify) package.

#### Version 0.4.0
- Breaking change: the plug-in is not anymore a default export. The use of destructuring assignment is advised to access it.
- Breaking change: ported the [CommonJS](https://nodejs.org/api/modules.html) modules to ES2015 format.
- Breaking change: ported the [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)-based APIs to [Observables](http://reactivex.io/intro.html).
- Breaking change: raised the required [Node.js](https://nodejs.org) version.
- Breaking change: replaced the test classes by plain tests.
- Added a build task for fixing the coding standards issues.
- Replaced [JSDoc](http://usejsdoc.org) documentation generator by [ESDoc](https://esdoc.org).
- Replaced [JSHint](http://jshint.com) linter by [ESLint](http://eslint.org).
- Updated the package dependencies.

#### Version 0.3.1
- Added support for code coverage.
- Added support for [Travis CI](https://travis-ci.org) continuous integration.

#### Version 0.3.0
- Breaking change: raised the required [Node.js](https://nodejs.org) version.
- Added the `silent` option: conditionally displaying the path of the minified scripts to the standard output.
- Drastically improved the performance (up to a 30x factor).
- Updated the package dependencies.

#### Version 0.2.0
- Breaking change: renamed the `PHPMinifier` class to `Minifier`.
- Breaking change: raised the required [Node.js](https://nodejs.org) version.
- Breaking change: using ES2015 features, like default parameters and destructuring assignment.
- Turned the package into a [scoped one](https://docs.npmjs.com/getting-started/scoped-packages).

#### Version 0.1.2
- Added support for [Codacy](https://www.codacy.com) code analyzer.
- Renamed the project according to its [npm](https://www.npmjs.com) package name.
- Updated the package dependencies.

#### Version 0.1.1
- Fixed some bugs.
- Updated the package dependencies.

#### Version 0.1.0
- Initial release.
