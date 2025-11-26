---
marp: true
theme: minimal
description: A sample slide for Marp
header: 🎦 Sample スライド
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

# # Header 1 <!-- rumdl-disable-line MD025 -->

## ## Header 2

### ### Header 3

#### #### Header 4

---

### Text Styles

**bold text**

_italicized text_

~~strike through text~~

`inline code`

---

### Block quote

> block quote
> block quote

---

### Bullet List

<div class="columns">

- Bullet 1
  - Bullet 1-1
  - Bullet 1-2
- Bullet 2
  - Bullet 2-1
    - Bullet 2-1-1

<!-- rumdl-disable MD004 -->

* Fragmented 1
  * Fragmented 1-1
  * Fragmented 1-2
* Fragmented 2
  * Fragmented 2-1
    * Fragmented 2-1-1

</div>

---

### Ordered List

<div class="columns">

1. Ordered 1
   1. Ordered 1-1
   2. Ordered 1-2
2. Ordered 2
   1. Ordered 2-1
      1. Ordered 2-1-1

1) Fragmented 1
   1) Fragmented 1-1
   2) Fragmented 1-2
2) Fragmented 2
   1) Fragmented 2-1
      1) Fragmented 2-1-1

</div>

---

### Link

[5ouma/slide](https://github.com/5ouma/slide)

---

### Image

<div class="columns">

![Remote alt text](https://www.markdownguide.org/assets/images/tux.png)
Remote Image

<br />

![Local alt text](./images/sonoma.png)
Local Image

</div>

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

![bg contain right:30%][icon]

[icon]: https://images.5ouma.me/avatar/default.png

---

### Image Filters

<div class="columns">

![w:4em blur:10px][icon]
blur
![w:4em brightness:0.5][icon]
brightness

![w:4em drop-shadow:0,5px,10px,gray][icon]
drop-shadow
![w:4em grayscale][icon]
gray scale

![w:4em invert][icon]
invert
![w:4em opacity:0.5][icon]
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

<div class="columns">

Column 1
Description 1

Column 2
Description 2

Column 3
Description 3

</div>

---

### Color Inverted Section

<!-- _class: invert -->

```html
<!-- class: invert -->
```

---

### Highlight

<div class="columns">

<div class="highlight">

Text

</div>

<span class="highlight">Text</span>

</div>
