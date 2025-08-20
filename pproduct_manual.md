---
marp: true
theme: custom-theme
paginate: true
header: 'Product Documentation: API v2.0'
footer: '© 2025 Software Co. | Contact: 23f3002037@ds.study.iitm.ac.in'
---

<!--
_class: lead
-->

# Product Documentation
## API Version 2.0
**A Guide for Developers**

---

<!--
Here we define the custom theme for the presentation.
We are setting a base color, header styles, and background color.
-->
<style>
:root {
  --color-background: #f0f4f8;
  --color-foreground: #2c3e50;
  --color-highlight: #3498db;
}

h1, h2 {
  color: var(--color-highlight);
  border-bottom: 2px solid currentColor;
}

section {
    background-color: var(--color-background);
    color: var(--color-foreground);
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
</style>

## Agenda

1.  **Introduction**: Core Concepts
2.  **Authentication**: Secure Access
3.  **Endpoints**: API Reference
4.  **Performance**: Algorithmic Complexity
5.  **Q&A**

---

<!--
This slide uses a background image and custom styling to make the text readable.
The 'invert' class is defined in the global style directive below.
-->

<!--
_class: invert
_background-image: url('https://picsum.photos/1280/720')
_background-size: cover
-->

## Our Core Philosophy
**Simplicity. Scalability. Security.**

---

<style scoped>
section.invert {
  filter: invert(100%) hue-rotate(180deg);
}

section.invert h2 {
    color: #3498db; /* Keep highlight color consistent */
}
</style>

## Algorithmic Complexity

Our sorting algorithm's performance is crucial for handling large datasets efficiently.

The average time complexity is described by the following equation:

$$
O(n \log n)
$$

This ensures that the system remains responsive even as data volume grows, avoiding common $O(n^2)$ bottlenecks.

---

## Thank You

**Questions?**

For further details, please contact:
**23f3002037@ds.study.iitm.ac.in**