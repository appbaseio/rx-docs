---
id: banner
title: "Banner"
layout: docs
sectionid: docs
permalink: base-components/banner.html
next: base-components/button.html
nextTitle: "Button"
redirect_from:
    - 'docs'
    - 'basic-components'
    - 'base-components'
    - 'base-components/'
    - 'basic-components/banner.html'
    - 'base-components/banner'
---

An Image Banner.

## Usage

```js
<Banner
	src="https://images-eu.ssl-images-amazon.com/images/G/31/img18/movies/1103933_750x600_gps_cn_qifq.jpg"
	href="movies/oscars"
	target="_blank"
	heightRatio={60}
	widthRatio={75}
/>
```

## Props

<br />

| prop        |  type  | default  | description                                  |
| ----------- | :----: | :------: | :------------------------------------------- |
| src         | string | required | image url                                    |
| href        | string | required | links the image to this ur                   |
| widthRatio  | number |    4     | width of the image or a proportionate number |
| heightRatio | number |    3     | width of the image or a proportionate number |


