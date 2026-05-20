---
layout: default
title: "CSS Notes"
nav_order: 4
---

#### Table of Contents
{:.no_toc}
- TOC
{:toc}

---


# CSS In a nutshell

CSS (Cascading Style Sheets) is a coding language that teams up with HTML.
It does this by selecting classes in the HTML code and editing them.
Making sure that the class you select is the right one is key.
You can change the entire site color, font, size of things, etc.
You can animate things too.


## How CSS works
CSS uses a simple system. Look in the box below to see
```css
body {
color: #insert Hex Code here;
}
```
Also, if you want your CSS code to work, you have to add this to the HTML file
```html
<!-- index.html -->

<head>
  <link rel="stylesheet" href="styles.css">
</head>
```
This links your CSS file to your HTML file, so you can style as you please.
You can add CSS inline in the HTML file, but using a CSS file is better.
