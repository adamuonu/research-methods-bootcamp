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
  h1 {
    font-size: 48px;
  }
  h2 {
    margin-bottom: 15px;
    padding-bottom: 15px;
    font-size: 44px;
    border-bottom: 1.5px dotted rgba(20, 26, 70, 0.95);
  }
  blockquote {
    background: rgba(20, 26, 70, 0.05);
    padding: 12px;
    font-family: 'Aptos', sans-serif;
    font-size: 0.88em;
    border-radius: 15px;
    color: #896631;
  }
  a {
    color: #896631;
    text-decoration: none;
  }
  table {
    margin-left: auto;
    margin-right: auto;
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

