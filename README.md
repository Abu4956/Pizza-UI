# Pizza Restaurant Website

A responsive, accessible single-page website for a pizza restaurant, built with **HTML5, CSS3 and Bootstrap 5**. It follows a provided Figma design and works on phones, tablets and desktops.

**Live demo:** https://preeminent-paletas-e5218e.netlify.app/


## Features

- **Fixed header** with the restaurant name, navigation menu and social icons (Instagram, Facebook, WhatsApp). Collapses into a hamburger menu on small screens.
- **Hero banner** with a CSS background image, headline and intro text.
- **About Us** section with text and an image on the right.
- **Menu** section with six dishes, each with an image, name and description.
- **Carousel** with 5 slides, built with the Bootstrap carousel component.
- **Gallery** mosaic built with CSS Grid, matching the Figma layout.
- **Find Us** section with an embedded Google Map and contact details, laid out with Flexbox.
- **Footer** with brand, links and contact details.

## Accessibility

- Semantic HTML (`header`, `nav`, `main`, `section`, `article`, `figure`, `address`, `footer`).
- Descriptive `alt` text on every image.
- ARIA labels on the navigation, menu toggle, social links, carousel and map.
- "Skip to main content" link, visible keyboard focus and sufficient color contrast.
- Respects the `prefers-reduced-motion` setting.

## Responsive design

CSS media queries adjust the layout, font sizes and grids for different screen sizes. The menu, About Us, gallery, Find Us and footer sections stack into single or two-column layouts on mobile.

## Project structure

```
pizza-restaurant/
  index.html      page markup
  style.css       custom styles
  images/         photos and favicon
  README.md
```

## Run locally

1. Clone or download this repository.
2. Open `index.html` in a browser (or use VS Code Live Server).
3. An internet connection is needed for Bootstrap, Google Fonts and the Google Maps embed.

## Customize

- **Images:** Replace the files in `images/` with your own (keep the file names, or update the `src` and `alt` in `index.html`).
- **Contact details:** Edit the address, phone number, email and opening hours in the Find Us section and footer.
- **Map location:** Change the `?q=` value in the Google Maps `iframe` URL to your address.

## Deploy with GitHub Pages

1. Push the project so `index.html` is at the root of the repository.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` and `/ (root)` and save.
4. After a minute, the site is live at `https://<username>.github.io/<repo>/`.

## Tech stack

HTML5, CSS3 (Flexbox, Grid, media queries), Bootstrap 5.3 (navbar and carousel), Google Fonts (Quattrocento, Ropa Sans), Google Maps embed.
