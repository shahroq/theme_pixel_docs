## Snippets <!-- omit in toc -->

### Table of Contents <!-- omit in toc -->

- [1. Media Queries](#1-media-queries)
- [2. Page-specific styles](#2-page-specific-styles)
- [3. Page background-image behavior](#3-page-background-image-behavior)
- [4. Changing the slider text color](#4-changing-the-slider-text-color)
- [5. Changing the primary menu padding](#5-changing-the-primary-menu-padding)
- [6. Reducing the white space on sides on mobile](#6-reducing-the-white-space-on-sides-on-mobile)



### 1. Media Queries
Sample code for implementing media queries
Break points:
[0] ... [479px] XSmall [767px] Small [991px] Medium [1199px] Large

```LESS
// Large down:
@media only screen and (max-width: 1199px) { #wrapper { border-color: MidnightBlue; } }
// Medium down:
@media only screen and (max-width: 991px) { #wrapper { border-color: Salmon; } }
// Small down:
@media only screen and (max-width: 767px) { #wrapper { border-color: SpringGreen; } }
// XSmall down:
@media only screen and (max-width: 479px) { #wrapper { border-color: GhostWhite; } }


// Medium only:
@media only screen and (min-width: 992px) and (max-width: 1199px) { #wrapper { border-color: Brown; } }
// Small only:
@media only screen and (min-width: 768px) and (max-width: 991px) {#wrapper { border-color: SkyBlue; } }
// XSmall only:
@media (min-width: 480px) and (max-width: 767px) { #wrapper { border-color: Orange; } }
```


### 2. Page-specific styles

```LESS
.pageid-[id] {
  // 
}
```

### 3. Page background-image behavior
for specific page use: `body.pageid-[id]`

```LESS
body  {
  // big image, cover whole background
  background-position: top center;
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: fixed;

  // small image, repeat on both dimension (default), sample image: /content_files/bg-image-small.png
  background-position: 0 0;
  background-repeat: repeat;

  // small image-vertical, repeat-x, sample image: /content_files/bg-image-small-ver.png
  background-size: auto 100%;
  background-repeat: repeat-x;

  // small image-horizontal, repeat-y, sample image: /content_files/bg-image-small-hor.png
  background-size: 100% auto;
  background-repeat: repeat-y;
}
```

### 4. Changing the slider text color
```LESS
.slider-caption {
  h1, h2, h3, h4, h5, h6 {
    color: yellowgreen!important;
  }    
  p, ul, a {
    color: skyblue!important;
  }    
}
```

### 5. Changing the primary menu padding
make it not break when menu is too long
```LESS
nav#primary-menu > ul > li > a {
  @media only screen and (min-width: 992px) and (max-width: 1199px) {
    padding-left: 5px !important;
    padding-right: 5px !important;
  }
}
```

### 6. Reducing the white space on sides on mobile
```LESS
@media only screen and (max-width: 479px) {
  .container,
  #header.full-header .container {
    width: 100% !important;
    padding-left: 30px;
    padding-right: 30px;
  }

  #content .content-wrap {
    padding: 50px 0;
  }
}
```
