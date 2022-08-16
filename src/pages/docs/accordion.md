---
title: Accordion
description: Quidem magni aut exercitationem maxime rerum eos.
---

An accordion is a vertically stacked list of headers that reveal or hide
associated sections of content.

---

## Overview

The accordion component delivers large amounts of content in a small space
through progressive disclosure. The header title give the user a high level
overview of the content allowing the user to decide which sections to read.

Accordions can make information processing and discovering more effective.
However, it does hide content from users and it's important to account for a
user not noticing or reading all of the included content. If a user is likely to
read all of the content then don't use an accordion as it adds the burden of an
extra click; instead use a full scrolling page with normal headers.

### Anatomy

![Anatomy](https://res.cloudinary.com/dgcfg5cwe/image/upload/v1643157199/Accordion_Anatomy_-_Open_nzy6tc.svg)

1. **Header**: contains the section title and is control for revealing the
   panel.
2. **Subtitle**: a description of what that specific accordion section does (optional)
3. **Icon**: indicates if the panel is open or closed.
4. **Panel**: the section of content associated with an accordion header.

## When to use

- To organize related information.
- To shorten pages and reduce scrolling when content is not crucial to read in
  full.
- When space is at a premium and long content cannot be displayed all at once,
  like on a mobile interface or in a side panel.

---

## Content

### Title

- The title should be as brief as possible while still being clear and
  descriptive.
- Each title should be wrapped in a heading (h1-h6) that is appropriate for the information architecture of the page.

### Body Copy

- Content inside of a section may be split into paragraphs and include
  sub-headers if needed.

### Scrolling Content

When the accordion content is longer than the viewport the whole accordion
should vertically scroll. Content should not scroll inside of an individual
panel. Content should never scroll horizontally in an accordion.

## Variants

The accordion component has two main states: **collapsed** and **expanded**. The
chevron icon at the end of the accordion indicates which state the accordion is
in. The chevron points down to indicate collapsed and up to indicate expanded.

Accordions begin by default in the collapsed state with all content panels
closed. Starting in a collapsed state gives the user a high level overview of
the available information.

### Collapsed State

![Anatomy](https://res.cloudinary.com/dgcfg5cwe/image/upload/v1643158257/Accordion_Collapsed_j7wgue.svg)

### Expanded State

![Anatomy](https://res.cloudinary.com/dgcfg5cwe/image/upload/v1643158257/Accordion_Open_otxn0n.svg)
