---
layout: cover
background: https://sli.dev/demo-cover.png
---

# Welcome to Slidev!

Presentation Slides for Developers

---

# Page 2

- 📄 Write slides in a single Markdown file
- 🌈 Themes, code blocks, interactive components
- 😎 Read the docs to learn more!|

---

# page 3

Directly use code blocks for highlighting

```python
import matplotlib.pyplot as plt
from matplotlib import interactive
interactive(True)

plt.plot(x, y)
raw_input('press return to continue')

plt.plot(z, t)
raw_input('press return to end')
```

```ts {2-3|5|all}
function add(
  a: Ref<number> | number,
  b: Ref<number> | number
) {
  return computed(() => unref(a) + unref(b))
}
```

--- 

# page 4

```ts {monaco}
console.log('HelloWorld')
```

> Hello `world`

---

# Page 5

This is the cover page.

<!-- This is a note -->

---

# Page 6

<!-- This is NOT a note because it precedes the content of the slide -->

The second page

<!--
This is another note
-->

---

# Page 7

$\sqrt{3x-1}+(1+x)^2$

$$
\begin{array}{c}

\nabla \times \vec{\mathbf{B}} -\, \frac1c\, \frac{\partial\vec{\mathbf{E}}}{\partial t} &
= \frac{4\pi}{c}\vec{\mathbf{j}}    \nabla \cdot \vec{\mathbf{E}} & = 4 \pi \rho \\

\nabla \times \vec{\mathbf{E}}\, +\, \frac1c\, \frac{\partial\vec{\mathbf{B}}}{\partial t} & = \vec{\mathbf{0}} \\

\nabla \cdot \vec{\mathbf{B}} & = 0

\end{array}
$$

---

# Page 8

[](https://sli.dev/demo/starter/1)

<div v-click>Hello</div>
<div v-after>World</div>
<div v-click>1</div>
<div v-click>2</div>
<div v-click>3</div>
<!-- the order is reversed -->
<div v-click="3">1</div>
<div v-click="2">2</div>
<div v-click="1">3</div>
---
clicks: 3
---

<!-- visible after 3 clicks -->
<v-clicks at="3">
  <div>Hi</div>
</v-clicks>
