---
id: product-image
title: "Product Image"
layout: docs
sectionid: docs
permalink: base-components/product-image.html
prev: product-details.html
prevTitle: "Product Details"
next: flex.html
nextTitle: "Flex"
redirect_from:
    - 'basic-components/product-image.html'
    - 'base-components/product-image'
---

![Image to be displayed](https://i.imgur.com/rfLhmh9.png)

## Usage

```js
<ProductImage
    image={{
        src:'https://cdn.shopify.com/s/files/1/0006/7724/9089/products/44694ee386818f3276566210464cf341_ac37348b-4add-45e3-8709-8d70ec9b6609_430x430.jpg?v=1522334356',
        alt: 'product_image',
    }}
    displayOfferTag={true}
/>
```

## Props

<br />

| prop              |  type            | default  | description                                  |
| ----------------- | :-------------- :| :------: | :------------------------------------------- |
| image             | object           |  -       | Product image                                |
| zoomable          | boolean          |  true    | `true` means display the enlarged image on hover    |
| displayOfferTag   | boolean          |  false   | if `true` then it'll display an offer tag    |
| bordered          | boolean          |  true    | To define, if the product image should have a border            |
| scalingFactor     | number           |  2      | Can be used to control the image quality of enlarged image           |
| smallImageContainerDimensions| object|  -      | Dimensions of small image container           |
| enlargedImageDimensions      | object|  -       | Dimensions of enlarged image         |
| smallImageDimensions  | object       |  -       | Dimensions of small image          |
| calculateSrc      | function         |  -       | Can be used to calculate the small image url                        |
| calculateSrcLarge   | function       |  -       | Can be used to calculate the large image url                              |