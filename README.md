# Luna's Bakery - Portfolio Website 3

A beautiful responsive website for a fictional bakery called Luna's Bakery. This project is built with HTML, CSS, and JavaScript and is ready to be hosted on GitHub Pages.

## Features

- Fully responsive design that works on desktop, tablet, and mobile devices
- Modern, clean design with a warm color palette appropriate for a bakery
- Four page layout: Home, Menu, Gallery, and Contact
- Interactive elements including:
  - Mobile-friendly navigation
  - Menu and gallery filtering
  - Testimonial slider
  - FAQ accordion
  - Contact form with validation

## Getting Started

### Prerequisites

- A modern web browser
- Git (for cloning the repository)

### Installation

1. Clone the repository to your local machine or download the ZIP file.
2. Navigate to the project directory.
3. Open `index.html` in your browser to view the website.

### Deployment on GitHub Pages

To deploy this website on GitHub Pages:

1. Push the code to your GitHub repository.
2. Go to the repository settings on GitHub.
3. Scroll down to the "GitHub Pages" section.
4. Select the branch you want to deploy (usually `main` or `master`).
5. The website will be available at `https://yourusername.github.io/repository-name`.

## Customization

### Images

The website uses placeholder image references. To fully customize the site:

1. Replace the image references in the HTML files with your own images.
2. Place your images in the `images` directory.
3. Suggested image sizes:
   - Hero background: 1920x1080px
   - Product cards: 600x400px
   - Gallery images: 600x600px
   - Menu items: 300x300px

### Colors

The color scheme can be easily modified by changing the CSS variables in the `:root` selector in `css/style.css`:

```css
:root {
    --primary: #e85a4f;
    --primary-light: #ff8c7f;
    --secondary: #e98074;
    --dark: #8e8d8a;
    --light: #eae7dc;
    --lighter: #f8f5f1;
    --text: #5d5c58;
    --heading: #2c2b2a;
    /* ... other variables ... */
}
```

### Content

1. Update the bakery information (address, phone, hours, etc.) throughout the HTML files.
2. Modify menu items, prices, and descriptions in `menu.html`.
3. Update testimonials in the index.html file.
4. Change the FAQ content in the contact.html file.

## Project Structure

```
Luna's Bakery/
├── index.html           # Home page
├── menu.html            # Menu page
├── gallery.html         # Gallery page
├── contact.html         # Contact page
├── css/
│   └── style.css        # Main stylesheet
├── js/
│   └── main.js          # Main JavaScript file
├── images/              # Directory for images
└── README.md            # This file
```

## Browser Compatibility

This website is compatible with the latest versions of:
- Chrome
- Firefox
- Safari
- Edge

## License

Feel free to use and modify this project for personal or commercial use.

## Acknowledgments

- Fonts from Google Fonts (Playfair Display and Poppins)
- Icons from Font Awesome 