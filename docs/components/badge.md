---
title: Badge
description: "Refer to the list of the Kendo UI Default theme variables available for customization."
category: components
---

# Badge

General information about Badge.

## Example preview and markup

<demo language="html">
<div id="test-area" class="grid">
    <span></span>
    <span class="col">Baseline</span>
    <span class="col">Rectagle</span>
    <span class="col">Rounded</span>
    <span class="col">Pill</span>
    <span class="col">Circle</span>
    <span>Small</span>
    <span><span class="k-badge k-badge-sm k-badge-solid k-badge-success">99</span></span>
    <span><span class="k-badge k-badge-sm k-badge-solid k-badge-success"><span class="k-badge-icon k-icon k-i-tick"></span></span></span>
    <span><span class="k-badge k-badge-sm k-badge-solid k-badge-success k-badge-rounded"><span class="k-badge-icon k-icon k-i-tick"></span></span></span>
    <span><span class="k-badge k-badge-sm k-badge-solid k-badge-success k-badge-pill"><span class="k-badge-icon k-icon k-i-tick"></span></span></span>
    <span><span class="k-badge k-badge-sm k-badge-solid k-badge-success k-badge-circle"><span class="k-badge-icon k-icon k-i-tick"></span></span></span>
    <span>^ outline</span>
    <span><span class="k-badge k-badge-sm k-badge-outline k-badge-primary">99</span></span>
    <span><span class="k-badge k-badge-sm k-badge-outline k-badge-primary"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-sm k-badge-outline k-badge-primary k-badge-rounded"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-sm k-badge-outline k-badge-primary k-badge-pill"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-sm k-badge-outline k-badge-primary k-badge-circle"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span>Normal</span>
    <span><span class="k-badge k-badge-md k-badge-solid k-badge-info">99</span></span>
    <span><span class="k-badge k-badge-md k-badge-solid k-badge-info"><span class="k-badge-icon k-icon k-i-calendar"></span></span></span>
    <span><span class="k-badge k-badge-md k-badge-solid k-badge-info k-badge-rounded"><span class="k-badge-icon k-icon k-i-calendar"></span></span></span>
    <span><span class="k-badge k-badge-md k-badge-solid k-badge-info k-badge-pill"><span class="k-badge-icon k-icon k-i-calendar"></span></span></span>
    <span><span class="k-badge k-badge-md k-badge-solid k-badge-info k-badge-circle"><span class="k-badge-icon k-icon k-i-calendar"></span></span></span>
    <span>^ outline</span>
    <span><span class="k-badge k-badge-md k-badge-outline k-badge-tertiary">99</span></span>
    <span><span class="k-badge k-badge-md k-badge-outline k-badge-tertiary"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-md k-badge-outline k-badge-tertiary k-badge-rounded"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-md k-badge-outline k-badge-tertiary k-badge-pill"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-md k-badge-outline k-badge-tertiary k-badge-circle"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span>Large</span>
    <span><span class="k-badge k-badge-lg k-badge-solid k-badge-warning">99</span></span>
    <span><span class="k-badge k-badge-lg k-badge-solid k-badge-warning"><span class="k-badge-icon k-icon k-i-bell"></span></span></span>
    <span><span class="k-badge k-badge-lg k-badge-solid k-badge-warning k-badge-rounded"><span class="k-badge-icon k-icon k-i-bell"></span></span></span>
    <span><span class="k-badge k-badge-lg k-badge-solid k-badge-warning k-badge-pill"><span class="k-badge-icon k-icon k-i-bell"></span></span></span>
    <span><span class="k-badge k-badge-lg k-badge-solid k-badge-warning k-badge-circle"><span class="k-badge-icon k-icon k-i-bell"></span></span></span>
    <span>^ outline</span>
    <span><span class="k-badge k-badge-lg k-badge-outline k-badge-error">99</span></span>
    <span><span class="k-badge k-badge-lg k-badge-outline k-badge-error"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-lg k-badge-outline k-badge-error k-badge-rounded"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-lg k-badge-outline k-badge-error k-badge-pill"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-lg k-badge-outline k-badge-error k-badge-circle"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span></span>
    <span>Rectangle</span>
    <span>Rounded</span>
    <span>Pill</span>
    <span>Circle</span>
    <span>Dot</span>
    <span>Inline</span>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout">Rect</span>
    </div>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-rounded">Round</span>
    </div>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-pill">Pill</span>
    </div>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-circle">99+</span>
    </div>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-dot"></span>
    </div>
    <span>Edge</span>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-edge k-top-end">Rect</span>
    </div>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-rounded k-badge-edge k-top-end">Round</span>
    </div>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-pill k-badge-edge k-top-end">Pill</span>
    </div>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-circle k-badge-edge k-top-end">99+</span>
    </div>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-dot k-badge-edge k-top-end"></span>
    </div>
</div>
</demo>

<demo>
<div id="test-area" class="grid">
    <span></span>
    <span class="col">Baseline</span>
    <span class="col">Rectagle</span>
    <span class="col">Rounded</span>
    <span class="col">Pill</span>
    <span class="col">Circle</span>

    <span>Small</span>
    <span><span class="k-badge k-badge-sm k-badge-solid k-badge-success">99</span></span>
    <span><span class="k-badge k-badge-sm k-badge-solid k-badge-success"><span class="k-badge-icon k-icon k-i-tick"></span></span></span>
    <span><span class="k-badge k-badge-sm k-badge-solid k-badge-success k-badge-rounded"><span class="k-badge-icon k-icon k-i-tick"></span></span></span>
    <span><span class="k-badge k-badge-sm k-badge-solid k-badge-success k-badge-pill"><span class="k-badge-icon k-icon k-i-tick"></span></span></span>
    <span><span class="k-badge k-badge-sm k-badge-solid k-badge-success k-badge-circle"><span class="k-badge-icon k-icon k-i-tick"></span></span></span>

    <span>^ outline</span>
    <span><span class="k-badge k-badge-sm k-badge-outline k-badge-primary">99</span></span>
    <span><span class="k-badge k-badge-sm k-badge-outline k-badge-primary"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-sm k-badge-outline k-badge-primary k-badge-rounded"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-sm k-badge-outline k-badge-primary k-badge-pill"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-sm k-badge-outline k-badge-primary k-badge-circle"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>

    <span>Normal</span>
    <span><span class="k-badge k-badge-md k-badge-solid k-badge-info">99</span></span>
    <span><span class="k-badge k-badge-md k-badge-solid k-badge-info"><span class="k-badge-icon k-icon k-i-calendar"></span></span></span>
    <span><span class="k-badge k-badge-md k-badge-solid k-badge-info k-badge-rounded"><span class="k-badge-icon k-icon k-i-calendar"></span></span></span>
    <span><span class="k-badge k-badge-md k-badge-solid k-badge-info k-badge-pill"><span class="k-badge-icon k-icon k-i-calendar"></span></span></span>
    <span><span class="k-badge k-badge-md k-badge-solid k-badge-info k-badge-circle"><span class="k-badge-icon k-icon k-i-calendar"></span></span></span>

    <span>^ outline</span>
    <span><span class="k-badge k-badge-md k-badge-outline k-badge-tertiary">99</span></span>
    <span><span class="k-badge k-badge-md k-badge-outline k-badge-tertiary"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-md k-badge-outline k-badge-tertiary k-badge-rounded"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-md k-badge-outline k-badge-tertiary k-badge-pill"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-md k-badge-outline k-badge-tertiary k-badge-circle"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>

    <span>Large</span>
    <span><span class="k-badge k-badge-lg k-badge-solid k-badge-warning">99</span></span>
    <span><span class="k-badge k-badge-lg k-badge-solid k-badge-warning"><span class="k-badge-icon k-icon k-i-bell"></span></span></span>
    <span><span class="k-badge k-badge-lg k-badge-solid k-badge-warning k-badge-rounded"><span class="k-badge-icon k-icon k-i-bell"></span></span></span>
    <span><span class="k-badge k-badge-lg k-badge-solid k-badge-warning k-badge-pill"><span class="k-badge-icon k-icon k-i-bell"></span></span></span>
    <span><span class="k-badge k-badge-lg k-badge-solid k-badge-warning k-badge-circle"><span class="k-badge-icon k-icon k-i-bell"></span></span></span>

    <span>^ outline</span>
    <span><span class="k-badge k-badge-lg k-badge-outline k-badge-error">99</span></span>
    <span><span class="k-badge k-badge-lg k-badge-outline k-badge-error"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-lg k-badge-outline k-badge-error k-badge-rounded"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-lg k-badge-outline k-badge-error k-badge-pill"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>
    <span><span class="k-badge k-badge-lg k-badge-outline k-badge-error k-badge-circle"><span class="k-badge-icon k-svg-icon"><svg viewBox="0 0 50 50"><circle cx="25" cy="25" r="25" /></svg></span></span></span>


    <span></span>
    <span>Rectangle</span>
    <span>Rounded</span>
    <span>Pill</span>
    <span>Circle</span>
    <span>Dot</span>
    <span>Inline</span>


    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout">Rect</span>
    </div>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-rounded">Round</span>
    </div>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-pill">Pill</span>
    </div>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-circle">99+</span>
    </div>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-dot"></span>
    </div>
    <span>Edge</span>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-edge k-top-end">Rect</span>
    </div>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-rounded k-badge-edge k-top-end">Round</span>
    </div>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-pill k-badge-edge k-top-end">Pill</span>
    </div>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-circle k-badge-edge k-top-end">99+</span>
    </div>
    <div class="k-badge-container">
        <span class="k-badge k-badge-md k-badge-solid k-badge-primary k-badge-border-cutout k-badge-dot k-badge-edge k-top-end"></span>
    </div>
</div>
</demo>

## Theme Specific info

<import component="badge" file="index"></import>


```html
    <button class='k-button k-button-primary'></button>

    <style>
        .k-button { outline: none; }
    </style>
```
