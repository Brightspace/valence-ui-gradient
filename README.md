#VUI Gradient [![Build Status](https://travis-ci.org/Desire2Learn-Valence/valence-ui-gradient.svg?branch=master)](https://travis-ci.org/Desire2Learn-Valence/valence-ui-gradient)

This library contains LESS mixins for creating CSS gradients which work
across browsers, including IE9.

##Usage

Install as a development dependency:

```shell
npm install --save-dev vui-gradient
```

Import the library into your LESS file:

```css
@import 'node_modules/vui-gradient/gradient'
```

##API

###Vertical

To apply a vertical gradient:

```css
div {
  #vui.gradient-vertical( @startColor, @endColor, @fallbackColor = @startColor );
}
```

The gradient will be applied top to bottom, and the `fallbackColor` is optional,
defaulting to the `startColor`.

###Horizontal

To apply a horizontal gradient:

```css
div {
  #vui.gradient-horizontal( @startColor, @endColor, @fallbackColor = @startColor );
}
```

The gradient will be applied left to right, and the `fallbackColor` is optional,
defaulting to the `startColor`.

## Contributing

### Code Style

This repository is configured with [EditorConfig](http://editorconfig.org) rules and contributions should make use of them. See the valence-ui [Code Style wiki page](https://github.com/Desire2Learn-Valence/valence-ui-helpers/wiki/Code-Style) for details.
