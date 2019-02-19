# LESS MIXINS (crossbrowser)

![Language](https://img.shields.io/github/languages/top/prod3v3loper/less-mixins.svg?style=flat "Language")
![Code size](https://img.shields.io/github/languages/code-size/prod3v3loper/less-mixins.svg?style=flat "Code size")
![Repo size](https://img.shields.io/github/repo-size/prod3v3loper/less-mixins.svg?style=flat "Repo size")
![License](https://img.shields.io/github/license/prod3v3loper/less-mixins.svg?style=flat "License")

LESS mixin repository for crossbrowser

![alt text](https://github.com/prod3v3loper/less-mixins/blob/master/test/img/ff.gif "Firefox")
![alt text](https://github.com/prod3v3loper/less-mixins/blob/master/test/img/g.gif "Google")
![alt text](https://github.com/prod3v3loper/less-mixins/blob/master/test/img/ie.gif "InternetExplorer")
![alt text](https://github.com/prod3v3loper/less-mixins/blob/master/test/img/o.gif "Opera")
![alt text](https://github.com/prod3v3loper/less-mixins/blob/master/test/img/s.gif "Safari")

> A curated list of awesome Less mixins

* [Tests Preview](test/img/tests.png)

### This repository has some Less-Mixins for you:

###### @mixins

* [.animation()](partials/_animation.less)
* [.appearance()](partials/_appearance.less)
* [.background-size()](partials/_background-size.less)
* [.border-radius()](partials/_border-radius.less)
* [.box-shadow()](partials/_box-shadow.less)
* [.box-sizing()](partials/_box-sizing.less)
* [.column()](partials/_column.less)
* [.font-smoothing()](partials/_font-smoothing.less)
* [.hyphens()](partials/_hyphens.less)
* [.linear-gradient()](partials/_linear-gradient.less)
* [.opacity()](partials/_opacity.less)
* [.perspective()](partials/_perspective.less)
* [.placeholder()](partials/_placeholder.less)
* [.tab-size()](partials/_tab-size.less)
* [.tap-highlight()](partials/_tap-highlight.less)
* [.t-rotate()](partials/_transform-rotate.less)
* [.t-rotate3d()](partials/_transform-rotate3d.less)
* [.t-scale()](partials/_transform-scale.less)
* [.t-scale3d()](partials/_transform-scale3d.less)
* [.t-skew()](partials/_transform-skew.less)
* [.t-translate()](partials/_transform-translate.less)
* [.t-translate3d()](partials/_transform-translate3d.less)
* [.transform()](partials/_transform.less)
* [.transition()](partials/_transition.less)
* [.user-select()](partials/_user-select.less)
* [.user-selection()](partials/_user-select.less)

###### @extra

* [breakpoint](partials/_breakpoint.less)
* [font](partials/_font.less)

## Usage

### General Usage

In general you should include the file `mixin.less` in `build` into your 
project less folder structur and use the mixins as suggested in the docs for each mixin.

###### @import

```less
@import 'your-less-folder/mixin.less';
```

###### @use

```less
.class {
    
    .box-shadow();
    .box-sizing();
}
```

## Contribute

Please [file an issue](https://github.com/Samettarim/less-mixins/issues) if you
think something could be improved. Please submit Pull Requests when ever
possible.

## Built with

* [NetBeans](https://netbeans.org/) - NetBeans editor for error-free code

## Authors

* **Samet Tarim** - *All works* - [prod3v3loper](https://www.tnado.com/author/prod3v3loper/)

## License

[GNU](https://github.com/prod3v3loper/less-mixins/blob/master/LICENSE)
