# Flipkart Clone 🛒

A responsive Flipkart UI clone built using HTML & CSS.

## Features

- Responsive Flipkart-like UI built with semantic HTML and CSS
- Desktop and mobile layouts using CSS Grid/Flexbox and media queries
- Product grid, header with search, navigation, and footer styling
- Hover states and basic accessibility considerations

## Technologies

- HTML5
- CSS3 (Flexbox, Grid, Media Queries)

## Installation

Follow the steps below to run the project locally.

### Clone the repository

Replace `<repo-url>` with the actual repository URL:

```bash
git clone https://github.com/ronaksharma-simform/html_and_css_assessment
```

Navigate into the project directory
cd html_and_css_assessment

Open the project in your browser

Open index.html using the command for your operating system:

### macOS
```bash
open index.html
```

### Linux

```bash
open index.html
```

### Windows (PowerShell)

```powershell
start index.html
```

## Project Structure

- index.html
- styles.css
- images/
  - Desktop_View.jpeg
  - tablet_view.jpeg
  - mobile.jpeg
- readme.md

## Usage

- View on desktop and resize the browser or use device emulator to test responsiveness.
- Update HTML/CSS files to customize layout, colors, or content.
## Implementation Details

### Overview
The project is implemented with semantic HTML5 and modular CSS to recreate Flipkart's core UI: header, category navigation, horizontal product carousels, and responsive layouts.

### Structure & Components
- Header: search input, flipkart logo, login, cart and a simple select-based "More" menu.
- Category bar: icon tiles with images and labels of different categories like Grocery, Fashion, Electronics.
- Product sections: horizontally scrollable product lists implemented as flex containers .
- Offer sidebar: aside element with a promotional image.

### HTML
- Semantic tags used: header, nav, section, aside.
- Each product is a simple card (img + description) for easy iteration.
- All images include alt text; interactive items use buttons or native controls (select) for basic accessibility.

### CSS & Layout
- CSS variables (e.g., --blue-color) for theme values.
- Flexbox for layout and horizontal scrolling lists (product carousels).
- Object-fit on images for consistent sizing.
- Custom scrollbar styling for product containers.
- Reusable utility styles for buttons and text.

### Responsiveness
- Mobile breakpoint: max-width: 768px
    - Search bar is hidden, product carousels wrap, offer image hidden.
- Tablet range: 768–1023px
    - Input width reduced; header spacing adjusted.
- Desktop: full-width search, fixed-height product images, horizontal carousels.

## Screenshots

### Desktop View 

<img src="./images/Desktop_View.jpeg" width="800" />

### Tablet View
<img src="./images/tablet_view.jpeg" width="500" />

### Mobile View

<img src="./images/mobile.jpeg" height="700">


## Contributing

Contributions are welcome! You can:

  - Fork the repository

  - Create a new branch (git checkout -b feature/your-feature)
  - Commit your changes (git commit -m "Add feature")

  - Push to the branch (git push origin feature/your-feature)

  - Open a Pull Request

## License

This project is for assessment purposes. Modify and use as needed.




