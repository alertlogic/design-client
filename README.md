# Design Client

A set of core colour palettes and variables for usage with Alert Logic User Interfaces

# Getting Started

To use these core styles inside your application:

`npm install @al/design`

Import whatever you want to use from the library into your project.

## Example Usage

For example for base colours used in Alert Logic applications:

```scss
@import "~@al/design/styles/palette";
@import "~@al/design/styles/utility";

html,body{
  color: al-color($al-gray, 500);
}
```

## Themes

Under the `themes` folder you will find custom created Alert Logic themes that can be used with your application, provided you are using the UI framework the theme is intended to be used for.

Currently we only support themes for the [primeng](https://www.primefaces.org/primeng/#/) framework for use with Angular.

Example usage with Angular CLI:

```json
styles: [
  "node_modules/primeng/resources/primeng.min.css",
  "node_modules/@al/design/themes/primeng/al-default-theme.css",
  "node_modules/primeicons/primeicons.css"
]
```
