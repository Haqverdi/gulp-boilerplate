# gulp-boilerplate
A boilerplate for building web projects with [Gulp](https://gulpjs.com/). Uses Gulp 4.x.

**Features**

- Concatenate, minify JavaScript.
- Minify,Clean CSS .
- Optimize Images.
- Copy static files and folders into your `dist` directory.
- Watch for file changes, and automatically recompile build and reload webpages.

## Getting Started

### Dependencies

*__Note:__ if you've previously installed Gulp globally, run `npm rm --global gulp` to remove it. [Details here.](https://medium.com/gulpjs/gulp-sips-command-line-interface-e53411d4467)*

Make sure these are installed first.

- [Node.js](http://nodejs.org)
- [Gulp Command Line Utility](http://gulpjs.com) `npm install --global gulp-cli`

### Quick Start

1. In bash/terminal/command line, `cd` into your project directory.
2. Run `npm install` to install required files and dependencies.
3. When it's done installing, run one of the task runners to get going:
	- `gulp` manually compiles files.
	- `gulp watch` automatically compiles files and applies changes using [BrowserSync](https://browsersync.io/) when you make changes to your source files.


## Documentation

Add your source files to the appropriate `src` subdirectories. Gulp will process and and compile them into `dist`.

- JavaScript files in the `src/js` directory will be compiled to `dist/js`. Files in subdirectories under the `js` folder will be concatenated. For example, files in `js/detects` will compile into `detects.js`.
- Files in the `src/css` directory will be compiled to `dist/css`.
- Images files placed in the `src/img` directory will be optimized compiled into `dist/img`.
- Files and folders placed in the `html` directory will be copied as-in into the `dist` directory.
