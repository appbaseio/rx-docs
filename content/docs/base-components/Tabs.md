---
id: tabs
title: "Tabs"
layout: docs
sectionid: docs
permalink: base-components/tabs.html
prev: base-components/section-header.html
prevTitle: "SectionHeader"
redirect_from:
    - 'basic-components/tabs.html'
    - 'base-components/tabs'
---

Displays the data arranged in selectable tabs.

## Usage

```js
<Tab active>Home</Tab>

<Tabs
  onChange={(value) => console.log('Selected tab', value)}
  active="Home"
  options={[
    {
      label: 'Home',
      value: 'Home',
    },
    {
      label: 'Cart',
      value: 'Cart',
    }
  ]}
/>
```

## Props

<br />

| prop        |  type  | default  | description                                  |
| ----------- | :----: | :------: | :------------------------------------------- |
| active         | string | - | sets the matching value in `options` as active                      |
| options         | array | - | An array of objects with `label` and `value` key for the tabs               |
| onChange         | function | - | Calls this function with the selected tab |
