# Parallax Background Image & Video Plugin

A **cross-browser compatible** JavaScript plugin for creating stunning parallax scrolling effects for both images and videos. This plugin has **no external dependencies**, but can optionally integrate with **jQuery**. Supporting **CSS transforms**, **YouTube**, **Vimeo**, and local video formats, this lightweight plugin is a flexible solution for adding parallax scrolling to your project.

## Features

- **Parallax Scrolling for Images and Videos**: Create dynamic parallax effects for both images and videos (MP4, WebM, OGV).
- **YouTube and Vimeo Support**: Easily integrate external videos from YouTube and Vimeo.
- **Scale and Opacity Effects**: Add visual effects like scaling or opacity changes to images.
- **Old Browser Compatibility**: Works across a wide range of browsers, including older ones, thanks to CSS transforms support.
- **No Dependencies**: Fully independent of other libraries, but can optionally integrate with jQuery.
- **Flickity Carousel Support**: Add parallax effects to carousels with Flickity.

## Installation

1. Include the necessary CSS and JavaScript files in your project:

    ```html
    <link href="css/style.css" rel="stylesheet">
    <link href="dist/jarallax.css" rel="stylesheet">

    <script src="https://unpkg.com/object-fit-images/dist/ofi.min.js"></script>
    <script src="dist/jarallax.js"></script>
    <script src="dist/jarallax-video.js"></script>
    <script src="dist/jarallax-element.js"></script>
    ```

2. Initialize the parallax plugin on your desired elements:

    ```javascript
    // Initialize object-fit polyfill
    objectFitImages();

    // Initialize Jarallax for images
    jarallax(document.querySelectorAll('.jarallax'));

    // Initialize Jarallax for images with the original image kept
    jarallax(document.querySelectorAll('.jarallax-keep-img'), {
      keepImg: true
    });

    // Optional Flickity carousel integration
    new Flickity('.carousel', {
      initialIndex: 1,
      autoPlay: 3000,
      pauseAutoPlayOnHover: false,
      pageDots: false,
      prevNextButtons: false,
      wrapAround: true
    });
    jarallax(document.querySelectorAll('.carousel .jarallax'), {
      elementInViewport: document.querySelectorAll('.carousel')
    });
    ```

## Usage

### Image Parallax

```html
<div class="jarallax" data-speed="0.2">
  <img class="jarallax-img" src="path-to-image.jpg" alt="">
</div>
```
### Video Parallax

```html
<div class="jarallax" data-video-src="mp4:video/local-video.mp4,webm:video/local-video.webm,ogv:video/local-video.ogv">
  <img class="jarallax-img" src="path-to-video-thumbnail.jpg" alt="">
</div>
```

## Carousel

- Speed: 0.1
- Speed: 0.4, Video: mp4, webm, ogv
- Speed: 0.2
- Speed: 0.3

---

## Parallax Effect

Parallax scrolling effect for background images using **CSS transforms**, cross-browser supported and compatible with old browsers. Parallax plugin with **NO dependencies**. jQuery supported. **Youtube** and **Vimeo** parallax supported.

---

## Parallax Speed Options

- Speed: 0.2
- Speed: -0.2
- Speed: 1.4

---

## Parallax `<img>` Tag

Lorizzle ipsum dang sit amizzle, consectetuer adipiscing da bomb. Nullizzle sapien velit, break it down volutpizzle, suscipit quis, ma nizzle vizzle, boom shackalack...

- Speed: 0.5
- Speed: 0.8

---

## Scale and Opacity

- Speed: 0.2, Type: scale-opacity
- Type: scroll-opacity
- Type: opacity
- Speed: -0.2, Type: scale

---

## Youtube, Vimeo, and `<video>` Parallax

- Youtube Video: https://youtu.be/mru3Q5m4lkY
- Speed: 0, Video: mp4, webm, ogv
- Vimeo Video: https://vimeo.com/235212527

---

## Parallax for Small Blocks

- Speed: 0.2
- Speed: 0
- Speed: 1.4

---

## Credits

Terry van Prooien
All images taken from: [Freepik](https://freepik.com) | [Pexels](https://pexels.com) | [Unsplash](https://unsplash.com)

---



