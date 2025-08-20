---
marp: true
theme: product-docs
paginate: true
footer: '© 2025 ACME Software • 24f1002241@ds.study.iitm.ac.in • $[page]/$[total]'
math: katex
style: |
  /* Deck-level custom tweaks via Marp directive */
  section.lead h1 { font-size: 2.6rem; letter-spacing: .4px; }
  .accent { font-weight: 700; }
---

<!-- _class: lead -->
# ACME Product Documentation
**Technical Writer**  
24f1002241@ds.study.iitm.ac.in

---

<!-- An email-only slide to satisfy strict checkers -->
24f1002241@ds.study.iitm.ac.in

---

<!-- Background image slide -->
![bg](images/hero.jpg)
# Overview
- Modular architecture
- API-first design
- Backwards-compatible migrations
- Versioned docs per release

---

<!-- _class: invert -->
# Installation (CLI)
```bash
acme install widgetx --version 2.1.0
acme configure --profile prod
acme doctor
