---
title: Installation
description: "Preview and install the Kendo UI Default theme and style the Kendo UI components in Angular and React projects."
category: "Getting Started"
position: 2
---

The `kendo-themes` project is a monorepo which hosts the packages for all available Kendo UI themes that are used across the Kendo UI suites and Telerik UI for Blazor:

* [[Default theme]] -- available as `@progress/kendo-theme-default` npm module
* [[Bootstrap theme]] -- available as `@progress/kendo-theme-bootstrap` npm module
* [[Material theme]] -- available as `@progress/kendo-theme-material` npm module

## Quick start

If you just need to include any Kendo theme in your project, without any customization, you can use copy-paste any of the following `<link>` into your `<head>`:

```html
<!-- Default theme -->
<link rel="stylesheet" href="http://unpkg.com/@progress/kendo-theme-default/dist/all.css" />

<!-- Bootstrap theme -->
<link rel="stylesheet" href="http://unpkg.com/@progress/kendo-theme-bootstrap/dist/all.css" />

<!-- Material theme -->
<link rel="stylesheet" href="http://unpkg.com/@progress/kendo-theme-material/dist/all.css" />
```

Alternatively, if you can install any of the themes trough npm:

```sh
# Default theme
npm install --save @progress/kendo-theme-default

# Bootstrap theme
npm install --save @progress/kendo-theme-bootstrap

# Material theme
npm install --save @progress/kendo-theme-material
```

## Further reading

* [[Known issues]]
* [[Compiling themes]]
* [[Customizing themes]]
* [[Including themes in React projects]]
* [[Including themes in Angular projects]]
