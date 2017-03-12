[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/dimitardanailov/polymer-grid-layout)

# Polymer grid layout

The `<polymer-grid-layout>` component provides simple ways to use [CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)

*Important note:*

```
CSS Grid is landing in several browsers in Spring 2017. Older versions of those browsers require a flag to be enabled to make use of this API. Make sure to reference the compatibility table for each property and function for more information.
```

Only Google Chrome 57 is supporting this feature. More about: [Chrome 57: Grid based layouts](https://www.youtube.com/watch?v=57Scec2XPd0)

Chris House has a wonderful article about all Grid layout features: [CSS tricks: A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

Additional resources:
- [CSS Grid – Table layout is back. Be there and be square.](https://developers.google.com/web/updates/2017/01/css-grid)
- []()

### Examples

##### Example 1 (Grid layout and justify-items: start)

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="polymer-grid-layout.html">

    <next-code-block></next-code-block>

  </template>
</custom-element-demo>
```
-->

```html
<!-- main document apply mixins in a custom-style element -->
<style is="custom-style">
  .container {
      @apply(--layout-grid-justify-items-start);

      grid-template-columns: 200px 200px 200px;
  }

  .container > div {
      border: 1px solid rgba(0,95,107);
      border-radius: 3px;
      background-color: rgba(0, 95, 107, 0.8);
      padding: 0.2em;
      color: #fff;
      margin-bottom: 10px;
  }

  .container > div:nth-child(odd) {
      background-color: rgba(110, 195, 107, 0.8);
  }
</style>

<div class="container">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
</div>
```

##### Example 2 (Grid layout and justify-items: end)

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="polymer-grid-layout.html">

    <next-code-block></next-code-block>

  </template>
</custom-element-demo>
```
-->

```html
<!-- main document: apply mixins in a custom-style element -->
<style is="custom-style">
  .container {
      @apply(--layout-grid-justify-items-end);

      grid-template-columns: 200px 200px 200px;
  }

  .container > div {
      border: 1px solid rgba(0,95,107);
      border-radius: 3px;
      background-color: rgba(0, 95, 107, 0.8);
      padding: 0.2em;
      color: #fff;
      margin-bottom: 10px;
  }

  .container > div:nth-child(odd) {
      background-color: rgba(110, 195, 107, 0.8);
  }
</style>

<div class="container">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
</div>
```

##### Example 3 (Grid layout and justify-items: center)

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="polymer-grid-layout.html">

    <next-code-block></next-code-block>

  </template>
</custom-element-demo>
```
-->

```html
<!-- main document: apply mixins in a custom-style element -->
<style is="custom-style">
  .container {
      @apply(--layout-grid-justify-items-center);

      grid-template-columns: 200px 200px 200px;
  }

  .container > div {
      border: 1px solid rgba(0,95,107);
      border-radius: 3px;
      background-color: rgba(0, 95, 107, 0.8);
      padding: 0.2em;
      color: #fff;
      margin-bottom: 10px;
  }

  .container > div:nth-child(odd) {
      background-color: rgba(110, 195, 107, 0.8);
  }
</style>

<div class="container">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
</div>
```

##### Example 4 (Grid layout and justify-items: stretch)

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="polymer-grid-layout.html">

    <next-code-block></next-code-block>

  </template>
</custom-element-demo>
```
-->

```html
<!-- main document: apply mixins in a custom-style element -->
<style is="custom-style">
  .container {
      @apply(--layout-grid-justify-items-stretch);

      grid-template-columns: 200px 200px 200px;
  }

  .container > div {
      border: 1px solid rgba(0,95,107);
      border-radius: 3px;
      background-color: rgba(0, 95, 107, 0.8);
      padding: 0.2em;
      color: #fff;
      margin-bottom: 10px;
  }

  .container > div:nth-child(odd) {
      background-color: rgba(110, 195, 107, 0.8);
  }
</style>

<div class="container">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
</div>
```
