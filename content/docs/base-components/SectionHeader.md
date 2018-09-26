---
id: section-header
title: "SectionHeader"
layout: docs
sectionid: docs
permalink: base-components/section-header.html
next: tabs.html
nextTitle: "Tabs"
prev: navbar.html
prevTitle: "Navbar"
redirect_from:
    - 'basic-components/section-header.html'
    - 'base-components/section-header'
---

A block level section header to display the `title`, `description` and a 'View All' link.

## Usage

```js
<SectionHeader
  title="Shoes"
  description="Latest collection"
  href="collections/adidas"
/>
```

## Props

<br />

| prop        |  type  | default  | description                                  |
| ----------- | :----: | :------: | :------------------------------------------- |
| title         | string | - | Displays the title of header                      |
| description         | string | - | Displays the description of header                |
| href         | string | - | When provided displays a 'View All' button for this link |
