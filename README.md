# Widths-responsive

The `widths-responsive` module is an extension of the default [`widths`
module](https://github.com/treeframework/trumps.widths).

## Dependencies

The `widths-responsive` module depends on four other modules:

* [settings.defaults](https://github.com/treeframework/settings.defaults)
* [settings.responsive](https://github.com/treeframework/settings.responsive)
* [tools.responsive](https://github.com/treeframework/tools.responsive)
* [trump.widths](https://github.com/treeframework/trump.widths)
* [tools.widths](https://github.com/treeframework/tools.widths)

If you install the `widths-responsive` module  using Bower or npm, you will get 
these dependencies at the same time. If not using Bower or npm, please be sure 
to install and @import these dependencies in the relevant way.

## Installation

You can install `widths-responsive` module via Bower, npm, Git Submodule, or copy and
paste.

### Install using Bower:

```sh
$ bower install tree-widths-responsive --save
```

Once installed, `@import` into your project in its Trump layer:

```scss
@import "bower_components/tree-widths-responsive/trump.widths-responsive";
```

### Install using npm:

```sh
$ npm install tree-widths-responsive --save
```

### Install as a Git Submodule

```sh
$ git submodule add git@github.com:treeframework/trump.widths-responsive.git
```

Once installed `@import` into your project in its Trump layer:

```scss
@import "trump.widths-responsive/trump.widths-responsive";
```

### Install via file download

The least recommended option for installation is to simply download
`_trump.widths-responsive.scss` into your project and `@import` it into your 
project in its Trump layer.

## Usage

`widths-responsive` loops through the breakpoints defined in
`settings.responsive` to generate prefixed breakpoint-based classes like
`u-1/4-lap-and-up`, or `u-1-of-2-desk`, etc.

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
