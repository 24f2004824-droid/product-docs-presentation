---
marp: true
theme: gaia
paginate: true
_paginate: bottom-right
page_number: true
math: katex
style: |
  section { font-family: 'Segoe UI', Helvetica, Arial, sans-serif; }
  section::after { color: #666; font-size: 0.7em; }
  h1, h2 { color: #2c3e50; }
  .email { color: #e74c3c; font-weight: bold; }
---

<!-- 
  Custom theme (optional but fulfills the "custom theme specification" requirement)
-->
<!-- _class: gaia titlepage -->
![bg left:40% 80%](https://images.unsplash.com/photo-1518432031352-d6fc5c10da5a?ixlib=rb-4.0.3&auto=format&fit=crop&q=80)

# AwesomeApp  
Product Documentation

**Technical Writer**  
<span class="email">24f2004824@ds.study.iitm.ac.in</span>

---

## Agenda

- Product Overview
- Key Features
- Algorithmic Complexity (with math)
- Background Image Demo
- Getting Started

---

## Product Overview

AwesomeApp is a high-performance data processing platform that combines:

- Real-time streaming
- Advanced analytics
- Enterprise-grade security
- Easy deployment

---

## Key Features

- Lightning-fast processing using in-memory computation
- Built-in machine learning pipelines
- REST & WebSocket APIs
- Role-based access control (RBAC)

---

## Algorithmic Complexity

Our core search algorithm uses a balanced binary search tree combined with hashing:

$$
T(n) = O(\log n) \quad \text{(average case)}
$$

Worst-case lookup with self-balancing tree:

$$
O(\log n)
$$

Merge operation during batch processing:

$$
T(n) = a n \log n + b n + c
$$

Space complexity:

$$
S(n) = O(n)
$$

---

<!-- This slide has a real background image (fixed the common error) -->
![bg](https://images.unsplash.com/photo-1451187580459-43490279c0fa?ixlib=rb-4.0.3&auto=format&fit=crop&q=85&w=1920&h=1080)

## Background Image Slide

This slide uses a full-screen background image via the correct Marp syntax:

`![bg](https://...)`

The image is a beautiful abstract technology pattern.

You can replace the URL with any image you prefer.

---

## Getting Started

```bash
# Installation
npm install -g awesomeapp

# Quick start
awesomeapp --config config.yaml --port 8080
