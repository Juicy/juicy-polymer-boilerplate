# &lt;juicy-element&gt; [![Build Status](https://travis-ci.org/Juicy/juicy-element.svg?branch=master)](https://travis-ci.org/Juicy/juicy-element)

> A bare minimum custom element starter-kit using [Polymer](http://www.polymer-project.org/).
>
> Like [Yeoman](http://yeoman.io/)? Use the [generator-element](https://www.npmjs.org/package/generator-element) instead.
>
> Looking for a working example? Check [hello-world-polymer](https://github.com/webcomponents/hello-world-polymer).

## Demo

[Check it live!](http://Juicy.github.io/juicy-element)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install juicy-element --save
```

Or [download as ZIP](https://github.com/Juicy/juicy-element/archive/master.zip).

## Usage

1. Import Web Components' polyfill, if needed:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/juicy-element/juicy-element.html">
    ```

3. Start using it!

    ```html
    <juicy-element></juicy-element>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`foo`         | *string*    | `bar`        | Lorem ipsum dolor.

## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---
`unicorn()`   | None.        | Nothing.    | Magic stuff appears.

## Events

Event         | Description
---           | ---
`onsomething` | Triggers when something happens.

## CSS Custom Properties

Name                          | Description
---                           | ---
`--juicy-element-laser-color` | Color of the shooted lasers.

## [Contributing and Development](CONTRIBUTING.md)

## History

For detailed changelog, check [Releases](https://github.com/Juicy/juicy-element/releases).

## License

MIT
