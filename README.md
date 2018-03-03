# Atomic Bulldog kss theme :collision: :dog:

<p align="center"> 
<img src="https://image.ibb.co/mmS6Hc/Artboard_1.png" alt="Atomic Bulldog Logo">
</p>

This is a custom template for the KSS-node living style guide, build for [Atomic Bulldog](https://github.com/vinceumo/atomic-bulldog)

*Demo*: https://vinceumo.github.io/atomic-bulldog-style-guide-demo/styleguide/index.html

## Install Atomic Bulldog kss theme

You will need kss node to be installed in your project:
https://github.com/kss-node/kss-node

In `kss-config.json` add `"builder": "../kss_theme/"`:

```json
{
  "title": "Atomic Bulldog - UI/pattern library",
  "source": "",
  "mask": "*.scss",
  "placeholder": "[modifier]",
  "destination": "../static/styleguide/",
  "builder": "../kss_theme/",
  "css": [],
  "js": []
}
```

## Customize Atomic Bulldog kss theme

You can change the primary color in `kss-theme/scss/variables/_colors.scss`

## Custom classes

### Color swatches 

You will need to use CSS custom properties to output your colors:

```scss
// <div id="kss-map-colors" class="theme-default">
//  <div class="kss-color-item" data-color="primary"></div>
//  <div class="kss-color-item" data-color="secondary"></div>
//  <div class="kss-color-item" data-color="text"></div>
//  <div class="kss-color-item" data-color="link"></div>
//  <div class="kss-color-item" data-color="success"></div>
//  <div class="kss-color-item" data-color="danger"></div>
//  <div class="kss-color-item" data-color="warning"></div>
//  <div class="kss-color-item" data-color="light"></div>
//  <div class="kss-color-item" data-color="dark"></div>
// </div>
```

### `.kss-box`

This class will output a box with background color primary.