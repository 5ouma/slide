---
marp: true
theme: minimal
title: Sample Slide
description: A sample slide for Marp
header: Sample Slide
paginate: true
image: index.png
---

<!--
_header: ""
_paginate: false
-->

# 🎦 Sample スライド

---

<!-- _paginate: false -->

## Markdown

---

<!-- footer: Markdown -->

### Headers

# # H1 <!-- markdownlint-disable MD025 -->

## ## H2

### ### H3

#### #### H4

---

### Text Styles

**bold text**

_italicized text_

~~strikethrough text~~

`inline code`

---

### Blockquote

> blockquote
> blockquote

---

### List

<span class="column">

1. Ordered List 1
   1. Ordered List 1-1
      1. Ordered List 1-1-1
2. Ordered List 2
   1. Ordered List 2-1
   2. Ordered List 2-2

- Unordered List 1
  - Unordered List 1-1
    - Unordered List 1-1-1
- Unordered List 2
  - Unordered List 2-1
  - Unordered List 2-2

</span>

---

### Link

[5ouma/slide](https://github.com/5ouma/slide)

---

### Image

<span class="column">

![remote alt text](https://www.markdownguide.org/assets/images/tux.png)
Remote Image

<br />

![local alt text](./images/sonoma.png)
Local Image

</span>

---

### Table

|  Center   | Left       |       Right |
| :-------: | :--------- | ----------: |
|  Header   | Left Title | Right Title |
| Paragraph | Left Text  |  Right Text |

---

### Fenced Code Block

```ts
type args = { a: number; b: number };
const add = ({ a, b }: args): number => a + b;

const result = add(1, 2);
console.log(result); // 3
```

---

### Task List

- [x] Completed task
- [ ] Incomplete task 1
- [ ] Incomplete task 2

---

### Emoji

`:joy:` → :joy:

---

<!--
_footer: ""
_paginate: false
 -->

### Marp Syntax

---

<!-- footer: Marp Syntax -->

### Background Image

![bg contain right:30%](https://images.5ouma.me/avatar/default.png)

---

### Image Filters

<div class="column">

![w:5em blur:10px](https://images.5ouma.me/avatar/default.png)
blur
![w:5em brightness:0.5](https://images.5ouma.me/avatar/default.png)
brightness

![w:5em drop-shadow:0,5px,10px,gray](https://images.5ouma.me/avatar/default.png)
drop-shadow
![w:5em grayscale](https://images.5ouma.me/avatar/default.png)
grayscale

![w:5em invert](https://images.5ouma.me/avatar/default.png)
invert
![w:5em opacity:0.5](https://images.5ouma.me/avatar/default.png)
opacity

</div>

---

<!--
_footer: ""
_paginate: false
 -->

## CSS Styling

---

<!-- footer: CSS Styling -->

### Column

<div class="column">

Column 1
Description 1

Column 2
Description 2

Column 3
Description 3

</div>

---

### Highlight

<span class="highlight">Text</span>
