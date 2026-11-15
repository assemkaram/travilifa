# Travilifa

A responsive, single-page travel landing site built with Bootstrap 5. It includes a hero section with trip search, a "Travelers Point" stats section, a top destinations grid with pricing, customer testimonials, and a multi-column footer.

**Live demo:** https://assemkaram.github.io/travilifa/

## Features

- **Responsive navigation bar** with a collapsible mobile menu (Bootstrap navbar)
- **Hero section** with a headline, description, and a trip search bar
- **Travelers Point** section highlighting key figures (holiday packages, hotels, transportation options) alongside an illustration
- **Top Destinations** cards showing a destination image, name, price, and trip duration
- **Testimonials** section with reviewer avatars and quotes
- **Footer** with quick links, service links, contact details, and social media icons

## Tech Stack

- HTML5
- CSS3 (`style.css`)
- JavaScript (`app.js`)
- [Bootstrap 5.3.8](https://getbootstrap.com/) for layout, components, and the navbar toggle
- [Font Awesome 7.0.1](https://fontawesome.com/) for icons

## Project Structure

```
travilifa/
├── index.html              # Main page and layout
├── style.css               # Custom styles
├── app.js                  # Client-side script
├── Group34-CCNMeN_L.png    # Travelers Point illustration
├── 1.png – 6.png           # Destination images
└── user-DJYMfxhG.png       # Testimonial avatar
```

## Getting Started

No build step or dependencies are required.

1. Clone the repository:
   ```bash
   git clone https://github.com/assemkaram/travilifa.git
   cd travilifa
   ```
2. Open `index.html` in your browser, or serve the folder with a local server:
   ```bash
   npx serve .
   ```

Bootstrap and Font Awesome load from CDNs, so an internet connection is needed for full styling.

## Customization

- **Destinations:** edit the `.card` blocks in the "Top Destination" section of `index.html` and replace the images `1.png` through `6.png`.
- **Testimonials:** edit the `.card.cbb` blocks in the "Testimonial" section.
- **Colors and layout:** adjust `style.css`. The green accent is used across headings and the footer.

## Known Limitations

- Most text is placeholder content (Lorem ipsum), and destination prices use Indonesian Rupiah (`Rp.6,5jt`) as sample values.
- Navigation links, the search button, and the footer links use `href="index.html"` or `#` and do not lead to real pages yet.
- Social media icons are not linked to any accounts.

## License

No license has been specified. All rights are reserved by the author unless a license is added.

## Author

**Assem Karam**: [Portfolio](https://assemkaram.github.io/portfolio/)
