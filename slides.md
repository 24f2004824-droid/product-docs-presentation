---
marp: true
theme: custom-theme
paginate: true
footer: "Product Documentation — 24f2004824@ds.study.iitm.ac.in"
---

<!-- Custom Theme Styling -->
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

# 📄 Product Documentation  
### Maintainable • Version Controlled • Multi-Format  
**Author:** 24f2004824@ds.study.iitm.ac.in

---

## Why Use Marp for Documentation?

- Markdown-based → easy to edit & review  
- Version control friendly (GitHub / CI/CD)
- Convert to **PDF / PPTX / HTML** easily
- Customizable themes and styles

---

## Architecture Overview

```mermaid
flowchart TD
A[Product Features] --> B[Documentation System]
B --> C[Marp Markdown]
C --> D[HTML / PDF / PPTX]
