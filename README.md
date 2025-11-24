## Infinite Seamless Carousel Template

A simple, responsive, touch-friendly infinite carousel/slider in vanilla JavaScript.  
Includes ready-to-use HTML, CSS, and JS — **no dependencies**.

---

### Features

- Infinite “seamless” looping with smooth transitions
- Supports navigation by arrows, dots, keyboard (left/right), and swipe gestures (touch devices)
- Easy to adapt: just plug in your slides and go!
- Fully responsive and accessible markup

---

## Quick Start

1. **Download or clone this repository**.

2. **Add your images** to the HTML inside the `.carousel__tape` container:

```html
<div class="carousel__tape tape">
  <img src="image1.jpg" alt="Description 1" class="carousel__img">
  <img src="image2.jpg" alt="Description 2" class="carousel__img">
  <img src="image3.jpg" alt="Description 3" class="carousel__img">
  <!-- ... -->
</div>
```

3. **Include the CSS and JS in your project**:

```html
<link rel="stylesheet" href="template.css">
...
<script src="template.js"></script>
```

4. **That’s it!**  
The carousel is ready to use with seamless looping and all controls.

---

### Usage Example

```html
<div class="carousel">
  <div class="carousel__frame frame">
    <div class="carousel__tape tape">
      <img src="image1.jpg" alt="Landscape 1" class="carousel__img">
      <img src="image2.jpg" alt="Landscape 2" class="carousel__img">
      <img src="image3.jpg" alt="Landscape 3" class="carousel__img">
    </div>
  </div>
  <div class="carousel__controls">
    <button class="carousel__prev previous-btn" aria-label="Previous slide">&lt;</button>
    <button class="carousel__next next-btn" aria-label="Next slide">&gt;</button>
    <button class="carousel__play-pause play-btn" aria-label="Play or pause slideshow"></button>
  </div>
  <div class="carousel__dots dots-box"></div>
</div>
<link rel="stylesheet" href="template.css">
<script src="template.js"></script>
```

---

### Customization

- **To change autoplay** interval, edit `setInterval(playInterval, 5000)` in `template.js`.
- **Adjust carousel size** by setting `max-width` and `height` in `.carousel` and `.carousel__frame` (CSS).
- **Add or remove slides** by editing the `.carousel__tape` content.
- **Style icons** by changing the button contents in HTML or JS.

---

### Accessibility Notes

- All navigation controls have `aria-label` attributes.
- Dot navigation is keyboard accessible (Tab/Enter).  
- Keyboard navigation by Left/Right arrow is supported globally.
- You can further enhance accessibility as needed (eg. aria-live for announcements).

---

### License

MIT — free for personal and commercial use.  
Author: Bartłomiej Balcerzak

---
