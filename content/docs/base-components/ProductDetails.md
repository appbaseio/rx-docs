---
id: product-details
title: "Product Details"
layout: docs
sectionid: docs
permalink: base-components/product-details.html
prev: options-selector.html
prevTitle: "Options Selector"
next: product-image.html
nextTitle: "Product Image"
redirect_from:
    - 'basic-components/product-details.html'
    - 'base-components/product-details'
---

![Image to be displayed](https://i.imgur.com/Tif8Pcs.png)

## Usage

```js
<ProductDetails
    image={{
        src: 'https://cdn.shopify.com/s/files/1/0006/7724/9089/products/44694ee386818f3276566210464cf341_ac37348b-4add-45e3-8709-8d70ec9b6609_430x430.jpg?v=1522334356',
        alt: 'product_image',
    }}
    title="Casual shoes (White)"
    quantity={1}
    price="$200"
    deliveryText="Delivery in 3-4 days: $10"
    options={[
        {
            name: 'Size',
            value: 8,
        },
        {
            name: 'Color',
            value: 'white',
        },
    ]}
    onClickRemove={() => { console.log('Remove called')}}
    onChangeQuantity={(quantity) => { 
        console.log('Quantity changed to', quantity)}
    }
    onClickSaveLater={() => { console.log('Save later called')}}
/>
```
## Props

<br />

| prop              |  type            | default  | description                                  |
| ----------------- | :-------------- :| :------: | :------------------------------------------- |
| title             | string           |  -       | Product title                                |
| image             | object           |  -       | Product image details                        |
| price             | string or number |  -       | Product price                                |
| options           | array            |  -       | Product variant options                      |
| loading           | boolean          |  -       | if `true` then disables the pointer events   |
| quantity          | number           |  -       | Product quantity                             |
| deliveryText      | string           |  -       | Product delivery tag if any                  |
| onChangeQuantity  | function         |  -       | called when product quantity changed         |
| onClickRemove     | function         |  -       | called when remove button clicked            |
| onClickSaveLater  | function         |  -       | called when save later clicked               |