# Frontend Mentor - My QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

### Links

- [Solution URL](https://your-solution-url.com)
- [Live Site URL](https://your-live-site-url.com)


## Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### Code

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  <title>Frontend Mentor | QR code component</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <main class="qr-container">
    <img class="qr-image" src="./images/image-qr-code.png" alt="">
    <div class="details">
      <h1 class="title">Improve your front-end skills by building projects</h1>
      <p class="sub-title">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
  </main>
</body>

</html>
```
```css
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');

*,
*::after,
*::before {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

img {
  max-width: 100%;
  display: block;
}

body {
  background-color: hsl(212, 45%, 89%);
  font-family: Outfit, sans-serif;
  font-size: 15px;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}

.qr-container {
  width: 90%;
  max-width: 320px;
  padding: 1rem;
  background-color: hsl(0, 0%, 100%);
  border-radius: 20px;
  text-align: center;
}

.qr-image {
  border-radius: 10PX;
}

.details {
  padding: 1.25rem;
}

.title {
  font-size: 1.25rem;
  margin-bottom: 1.25rem;
  color: hsl(218, 44%, 22%);
}

.sub-title {
  color: hsl(220, 15%, 55%);
}
```
