![PR welcome](https://camo.githubusercontent.com/b0ad703a46e8b249ef2a969ab95b2cb361a2866ecb8fe18495a2229f5847102d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5052732d77656c636f6d652d627269676874677265656e2e737667)

(https://github.com/BitMorest/material-bs-grid/blob/master/banner.png?raw=true)

The angular material with bootstrap 5 grid system

## Motivation

[Angular Material](https://material.angular.io/) is a good library UI component for angular. It has almost everything however they lack some important components such as the Grid System which makes it very difficult to use it independently. So I created this library that combines [Angular Material](https://material.angular.io/) and grid from [Bootstrap](https://getbootstrap.com/docs/5.2/layout/grid/) (because it has been developed for a long time and most developers know or belong to it). Also I also get some utilities from [Bootstrap](https://getbootstrap.com/docs/5.2/layout/grid/) like
is the display system, flex, float, distance from bootstrap.

This package depends on [@bitmorest/bootstrap-grid](https://www.npmjs.com/package/@bitmorest/bootstrap-grid). Read more about what's we have from bootstrap [here](https://github.com/BitMorest/bootstrap-grid)

## Install

`yarn add @angular/material @angular/cdk @bitmorest/bootstrap-grid @bitmorest/material-bs-grid` or `npm i @angular/material @angular/cdk @bitmorest/bootstrap-grid @bitmorest/material-bs-grid`

## Usage

in global style normally at src/style.scss add bellow code

```scss
@import "@bitmorest/material-bs-grid";
// add prebuild themes for angular
@import "@angular/material/prebuilt-themes/purple-green.css";
```
