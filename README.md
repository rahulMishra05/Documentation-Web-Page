# Animation usind AOS library

This is an example website to demonstrate the use of AOS library to add animation in a webpage.

## 📡 Important links
1. [Official documentation](https://github.com/michalsnik/aos)
2. [Official website](https://michalsnik.github.io/aos/)
3. [Live Demo](https://documentation-webpage.netlify.app/)

## 🛠 Instalation

### 📌 Basic
1. Add styles in `<head>`:
    ```HTML
      <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
    ```
2. Add script right before closing `</body>` tag, and initiazile ASO:
    ```HTML
    <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
    <script>
    AOS.init();
    </script>
    ```
### 📝 Using package managers
1. Install `aos` package:
    - `yarn add aos@next`
    - or `npm install --save aos@next`
2. Import script, style and initialize AOS:
    ```javascript
    import AOS from 'aos';
    import 'aos/dist/aos.css'; // You can also use <link> for styles
    // ..
    AOS.init();
    ```
In order to make it work you'll have to make sure your build process has configured styles loader, and bundles it all correctly. If you're using [Parcel](https://parceljs.org/) however, it will work out of the box as provided.

## 💡 Predefined options

### Animations

  * Fade animations:
    * fade
    * fade-up
    * fade-down
    * fade-left
    * fade-right
    * fade-up-right
    * fade-up-left
    * fade-down-right
    * fade-down-left

  * Flip animations:
    * flip-up
    * flip-down
    * flip-left
    * flip-right

  * Slide animations:
    * slide-up
    * slide-down
    * slide-left
    * slide-right

  * Zoom animations:
    * zoom-in
    * zoom-in-up
    * zoom-in-down
    * zoom-in-left
    * zoom-in-right
    * zoom-out
    * zoom-out-up
    * zoom-out-down
    * zoom-out-left
    * zoom-out-right

### Anchor placements:

  * top-bottom
  * top-center
  * top-top
  * center-bottom
  * center-center
  * center-top
  * bottom-bottom
  * bottom-center
  * bottom-top

### Easing functions:

  * linear
  * ease
  * ease-in
  * ease-out
  * ease-in-out
  * ease-in-back
  * ease-out-back
  * ease-in-out-back
  * ease-in-sine
  * ease-out-sine
  * ease-in-out-sine
  * ease-in-quad
  * ease-out-quad
  * ease-in-out-quad
  * ease-in-cubic
  * ease-out-cubic
  * ease-in-out-cubic
  * ease-in-quart
  * ease-out-quart
  * ease-in-out-quart