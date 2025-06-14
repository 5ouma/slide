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

<div class="columns">

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

</div>

---

### Link

[5ouma/slide](https://github.com/5ouma/slide)

---

### Image

<div class="columns">

![remote alt text](https://www.markdownguide.org/assets/images/tux.png)
Remote Image

<br />

![local alt text](./images/sonoma.png)
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
grayscale

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

### Highlight

<span class="highlight">Text</span>
