# Pseudo

Easily use pseudo-elements. Adds properties so they display automatically.

## Installation

```
fonzie install pseudo
```

## Usage

```scss
.box {
  @include before {
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

You can also use the mixins `after` and `before-and-after`.