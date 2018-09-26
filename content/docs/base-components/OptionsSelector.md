---
id: options-selector
title: "Options Selector"
layout: docs
sectionid: docs
permalink: base-components/options-selector.html
prev: tabs.html
prevTitle: "Tabs"
next: product-details.html
nextTitle: "Product Details"
redirect_from:
    - 'basic-components/options-selector.html'
    - 'base-components/options-selector'
---

![Image to be displayed](https://i.imgur.com/VPKoQbi.png)

## Usage

```js
<OptionsSelector 
    options={[
        {
            name: 'Size',
            values: [
                {
                    value: 5,
                },
                {
                    value: 6,
                },
                {
                    value: 7,
                },
                {
                    value: 8,
                },
            ],
        },
        {
            name: 'Color',
            values: [
                {
                    value: 'blue',
                },
                {
                    value: 'brown',
                },
                {
                    value: 'black',
                },
            ],
        },
    ]}
    selectedOptions={[6, 'brown']}
    onChange={(value, position) => {
        console.log(`Option ${position} changed to ${value}`)
    }}
/>
```

## Props

<br />

| prop            |  type    | default  | description                                  |
| --------------- | :----:   | :------: | :------------------------------------------- |
| options         | array    | -       | variant options                              |
| selectedOptions | array    | -       | selected options                             |
| onChange        | function | -       | called on an option change                   |
