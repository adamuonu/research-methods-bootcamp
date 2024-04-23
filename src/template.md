---
marp: true
theme: default
size: 16:9
math: mathjax
html: true
paginate: true
_paginate: skip
style: |
  section {
    background-image: url(img/slide-bg.svg);
    font-family: 'Aptos', sans-serif;
  }
  section::after {
    content: 'Page ' attr(data-marpit-pagination) ' / ' attr(data-marpit-pagination-total);
  }
  footer, section::after {
    font-family: 'Aptos', sans-serif;
    font-size: 0.65em;
  }
  h1, h2, h3 {
    font-family: "Creato Display", sans-serif;
    color: rgba(20, 26, 70, 0.85);
  }
  h2 {
    margin-bottom: 15px;
    padding-bottom: 15px;
    border-bottom: 1.5px dotted rgba(20, 26, 70, 0.95);
  }
  blockquote {
    font-family: 'Aptos', sans-serif;
    color: #896631;
  }
  a {
    color: #896631;
    text-decoration: none;
  }
  table {
    margin: auto;
    font-size: 90%;
  }
  ul ol {
    list-style-type: decimal;
  }
  .left-column {
    float: left;
    width: 48%;
  }
  .right-column {
    float: right;
    width: 48%;
  }
  .center {
    margin-left: auto;
    margin-right: auto;
    width: 97%;
    text-align: center;
  }
  .smaller {
    font-size: 0.92em;
  }
  .accent {
    font-weight: bold;
    color: #896631;
  }

---

![bg](img/first-slide-bg.svg)

---

# Presentation title<!--fit-->

<!-- footer: Presentation title -->

---
## First slide

### Numbered list

1) First item
2) Second item
3) Third item

---
## Second slide

Two column display: Set `"markdown.marp.enableHtml": true,` in settings. 

<div>
<div class='left-column'>

### Bullet list
  
  * One
  * Two
  * Three

</div>

<div class='right-column'>

### Math equation

<br>

$$
\Gamma \left( a \right) = \int\limits_0^\infty{s^{a - 1}} e^{ - s} ds
$$

</div>

</div>

---
## Centered text

<div class='center'>

This text is centered and <span class='accent'>emphasized with a different color</span>

</div>

---
## Famous quotation

![bg left](img/lincoln.jpg)


> Don't believe everything you read on the internet.

<span style="float: right">&mdash; Abraham Lincoln, 30.02.1945</span>