# Pseudo

Easily use pseudo-elements. Adds properties so they display automatically.

## Installation

```
bower install fonzie-pseudo
```

## Usage

```scss
.box {
  @include fz-before {
    backgroud: blue;
  }
}
```

Outputs:

```css
.box:before {
  display: block;
  content: '';
  background: blue;
}
```

You can also use the mixins `fz-after` and `fz-beforeAndAfter`.