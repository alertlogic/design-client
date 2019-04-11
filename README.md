# Design Client

A set of core colour palettes and variables for usage with Alert Logic User Interfaces

# Getting Started

To use these core styles inside your application:

`npm install @al/design`

Import whatever you want to use from the library into your stylesheets.

For example for SCSS:

```scss
@import "~@al/design/styles/palette";
@import "~@al/design/styles/utility";

html,body{
  color: al-color($al-gray, 500);
}
```