# sign-up-form

A static sign-up page with a split layout: a full-height photo panel on the left and a registration form on the right. Built with plain HTML and CSS as part of [The Odin Project](https://www.theodinproject.com/) curriculum.


## Features

- Two-panel layout built with Flexbox (photo on the left, form on the right)
- Background photo that fills its panel without stretching
- Logo band and photo credit positioned over the image
- Two-column form rows (first/last name, email/phone, password/confirm password)
- Built-in browser validation using `required` on all fields except phone
- Validation styling that only appears after the user interacts with a field (`:user-invalid`)
- Focus and hover states on the inputs, button, and links

## Built With

- HTML5
- CSS3 (Flexbox, custom `@font-face` rules, `:user-invalid`, `:focus`, `:hover`)
- Fonts: Norse (logo), Roboto (body text, falls back to Arial)

## Project Structure

```
sign-up-form/
├── index.html
├── style.css
├── README.md
├── fonts/
│   ├── Norse.woff2
│   └── Norse-Bold.woff2
└── images/
    ├── background.jpg
    └── odin-lined.png
```

## Getting Started

1. Clone or download this repository.
2. Open `index.html` in your browser.

No build step or dependencies are required.

## What I Learned

- Building a split-screen layout with Flexbox
- Positioning elements over a background image with `position: relative` and `absolute`
- Structuring a form with labels, inputs, and wrapper divs for layout
- Styling form states without JavaScript

## Credits

- Photo by [Halie West](https://unsplash.com/@haliewestphoto) on [Unsplash](https://unsplash.com/photos/green-leaf-plant-in-close-up-photography-25xggax4bSA)
- Design and project brief from [The Odin Project](https://www.theodinproject.com/)