# JSDoc Setup Guide


An API documentation generator for JavaScript.


## Installation and Setup


**Step 01**: 

To install the latest version on npm globally

    npm install -g jsdoc


To install the latest version on npm locally and save it in your package's
`package.json` file:

    npm install --save-dev jsdoc

**Step 02**:

Create a directory and a `package.json` file 

```
    npm init -y
```


If you installed JSDoc locally, the JSDoc command-line tool is available in
`./node_modules/.bin`. To generate documentation for the file
`yourJavaScriptFile.js`:

    ./node_modules/.bin/jsdoc yourJavaScriptFile.js

If you installed JSDoc globally, run the `jsdoc` command:

    jsdoc yourJavaScriptFile.js

By default, the generated documentation is saved in a directory named `out`. You
can use the `--destination` (`-d`) option to specify another directory.

Run `jsdoc --help` for a complete list of command-line options.

#### Generates Documentation

```
npm run doc
```

## Templates and tools

The JSDoc community has created templates and other tools to help you generate
and customize your documentation. Here are a few of them:

### Templates

+ [jaguarjs-jsdoc](https://github.com/davidshimjs/jaguarjs-jsdoc)
+ [DocStrap](https://github.com/docstrap/docstrap)
([example](https://docstrap.github.io/docstrap))
+ [jsdoc3Template](https://github.com/DBCDK/jsdoc3Template)
  ([example](https://github.com/danyg/jsdoc3Template/wiki#wiki-screenshots))
+ [minami](https://github.com/Nijikokun/minami)
+ [docdash](https://github.com/clenemt/docdash)
([example](http://clenemt.github.io/docdash/))
+ [tui-jsdoc-template](https://github.com/nhnent/tui.jsdoc-template)
([example](https://nhnent.github.io/tui.jsdoc-template/latest/))
+ [better-docs](https://github.com/SoftwareBrothers/better-docs)
([example](https://softwarebrothers.github.io/admin-bro-dev/index.html))

### Build tools

+ [JSDoc Grunt plugin](https://github.com/krampstudio/grunt-jsdoc)
+ [JSDoc Gulp plugin](https://github.com/mlucool/gulp-jsdoc3)
+ [JSDoc GitHub Action](https://github.com/andstor/jsdoc-action)

### Other tools

+ [jsdoc-to-markdown](https://github.com/jsdoc2md/jsdoc-to-markdown)
+ [Integrating GitBook with
JSDoc](https://medium.com/@kevinast/integrate-gitbook-jsdoc-974be8df6fb3)

## For more information

+ Documentation is available at [jsdoc.app](https://jsdoc.app/).
+ Contribute to the docs at
[jsdoc/jsdoc.github.io](https://github.com/jsdoc/jsdoc.github.io).
+ [Join JSDoc's Slack channel](https://jsdoc-slack.appspot.com/).
+ Ask for help on the
[JSDoc Users mailing list](http://groups.google.com/group/jsdoc-users).
+ Post questions tagged `jsdoc` to
[Stack Overflow](http://stackoverflow.com/questions/tagged/jsdoc).

## License

JSDoc is copyright (c) 2011-present Michael Mathews <micmath@gmail.com> and
the [contributors to JSDoc](https://github.com/jsdoc/jsdoc/graphs/contributors).

JSDoc is free software, licensed under the Apache License, Version 2.0. See the
`LICENSE` file for more details.