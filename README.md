# expanding-cards-Project-1-50
Interactive expanding image cards built with HTML, CSS &amp; vanilla JavaScript. Click a card to smoothly expand it.
# Expanding Cards

An interactive image gallery built with **HTML, CSS, and vanilla JavaScript**. Click on any card and it smoothly expands to reveal its full image and title, while the other cards shrink.

## Features

- Smooth expand/collapse animation using CSS `flex` transitions
- Title fades in only on the active card
- Rounded, modern card design with full-height background images
- Responsive layout: on small screens (max 480px), extra panels are hidden for a cleaner view
- No frameworks or libraries, just plain HTML, CSS, and JavaScript

## Technologies Used

- **HTML5**: page structure
- **CSS3**: Flexbox, transitions, media queries, Google Fonts (Muli)
- **JavaScript (ES6)**: click events and class toggling

## Project Structure

```
expanding-cards-Project-1-50/
├── index.html
├── style.css
├── script.js
└── README.md
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Farhan-Gujjar/expanding-cards-Project-1-50.git
   ```
2. Open the project folder.
3. Open `index.html` in any modern web browser.

No installation or build step is needed. An internet connection is required to load the images (Unsplash) and the Google Font.

## How It Works

- Each card is a `.panel` element, and the one with the `.active` class gets a larger `flex` value (`5` vs `0.5`).
- When a panel is clicked, JavaScript removes `active` from all panels and adds it to the clicked one.
- CSS `transition` animates the size change, and the `<h3>` title fades in with a small delay.

## Customization

- Change the images by editing the `background-image` URLs in `index.html`.
- Change the titles by editing the `<h3>` text inside each panel.
- Add more panels by copying a `<div class="panel">` block.
- Adjust animation speed in `style.css` via `transition: flex 0.5s ease-in;`.

## Credits

- Images from [Unsplash](https://unsplash.com/)
- Font: Muli via [Google Fonts](https://fonts.google.com/)

## License

This project is open source and available under the [MIT License](LICENSE).
