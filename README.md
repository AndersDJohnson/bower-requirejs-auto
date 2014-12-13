bower-requirejs-auto
====================

Automatically configures RequireJS paths for Bower components at runtime.

Recommended for development use only.

Simpler alternative to [yeoman/bower-requirejs](https://github.com/yeoman/bower-requirejs) (or [yeoman/grunt-bower-requirejs](https://github.com/yeoman/grunt-bower-requirejs)).

## Install

```sh
bower install --save-dev bower-requirejs-auto
```

## Use

See [example](example).

Add `bower-requirehs-auto/index.js` to you page, and specify following option attributes on its `<script>` tag:
* `data-then`: (*required*) a main module to load after automatic configuration is complete, like RequireJS's `data-main`.
* `data-base`: (*optional, default*: `''` ) a relative path to your "base" directory containing `bower.json` and `bower_components`.

