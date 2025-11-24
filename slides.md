---
marp: true
theme: custom-theme
paginate: true
footer: "Product Documentation Presentation — 24f2004824@ds.study.iitm.ac.in"
---

<!-- Custom Theme -->
<style>
section {
  font-family: "Segoe UI", sans-serif;
}
h1 {
  color: #007ACC;
}
h2 {
  color: #003366;
}
footer {
  font-size: 12px;
  color: #666;
}
.big-text {
  font-size: 32px;
  font-weight: bold;
}
</style>

<!-- Custom Theme Definition -->
<!--
You can also store theme in a separate .css file for reuse in repo
-->
<style>
:root {
  --background: #FFFFFF;
  --color: #111111;
}
section {
  background-color: var(--background);
  color: var(--color);
}
</style>

# 📄 Product Documentation  
### A Maintainable + Multi-format Approach  
**Author:** 24f2004824@ds.study.iitm.ac.in

---

## Why Marp?

- Markdown-based → easy version control  
- Export to PDF / PPTX / HTML  
- Lightweight and maintainable  
- Easily customizable themes

---

## Architecture Overview

```mermaid
flowchart TD
A[Product Features] --> B[Documentation System]
B --> C[Marp Markdown]
C --> D[HTML / PDF / PPTX]
