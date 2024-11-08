---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Welcome to Slidev
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# take snapshot for each slide in the overview
overviewSnapshots: true
src: ./pages/welcome.md
---

---
src: ./pages/what-is-slidev.md
transition: fade-out
---

---
src: ./pages/navigation.md
transition: slide-up
level: 2
---

---
src: ./pages/table-of-content.md
layout: two-cols
layoutClass: gap-16
---

---
src: ./pages/code.md
layout: image-right
image: https://cover.sli.dev
---

---
src: ./pages/shiki-magic-move.md
level: 2
---

---
src: ./pages/components.md
---

---
src: ./pages/themes.md
class: px-20
---

---
src: ./pages/clicks-animations.md
---

---
src: ./pages/motions.md
---

---
src: ./pages/latex.md
---

---
src: ./pages/draggables.md
foo: bar
dragPos:
  square: 586,61,167,_,-16
---

---
src: ./pages/imported-slides.md
hide: false
---

---
src: ./pages/monaco-editor.md
---

---
src: ./pages/learn-more.md
layout: center
class: text-center
---
