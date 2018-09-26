---
id: navbar
title: "Navbar"
layout: docs
sectionid: docs
permalink: base-components/navbar.html
next: section-header.html
nextTitle: "SectionHeader"
prev: button.html
prevTitle: "Button"
redirect_from:
    - 'basic-components/navbar.html'
    - 'base-components/navbar'
---

A styled `nav`.

## Usage

```js
<Navbar>
  <Container sticky={sticky}>
    <div className="wrapper">
      <a className="logo">Logo</a>
      <CategorySearch
        ...
      />
      <ul className="links">
        <li>Home</li>
      </ul>
    </div>
	</Container>
</Navbar>
```

## Props

<br />

| prop        |  type  | default  | description                                  |
| ----------- | :----: | :------: | :------------------------------------------- |
| sticky         | boolean | false | When `true`, sets the navbar to a fixed position                                    |

