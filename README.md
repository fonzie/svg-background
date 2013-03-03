# SVG Background

Use SVGs as background with a fallback for <IE9.

## Installation

```
fonzie install svg-background
```

## Usage

```scss
.icon {
  @include svg-background('../images/icons/arrow', 'png');
}
```

Because we don't have access to string method in Sass yet, we need
to pass in the file extension for the fallback. By default this is 
.png so you can leave off the second paramter if it's a png.