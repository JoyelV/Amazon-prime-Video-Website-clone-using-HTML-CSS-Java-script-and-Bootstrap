# Amazon Prime Video Clone

This project is a responsive web page clone of the Amazon Prime Video interface, built using HTML, CSS, and JavaScript with Bootstrap for styling and layout. The page includes a navigation bar, hero section, movie rental section, favorite channels section, a remote (Fire TV Stick) section, and a footer with a scroll-to-top feature.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Responsive Design](#responsive-design)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Navigation Bar**: A sticky navbar with dropdown menus for Home, Store, and Categories, along with search and user profile icons.
- **Hero Section**: A full-screen hero section with a background image, welcoming users to Prime Video with a call-to-action button.
- **Movie Rentals Section**: Highlights movie rentals with a prominent image and a "Rent Now" button.
- **Favorite Channels Section**: Displays a grid of channel logos with hover effects for interactivity.
- **Fire TV Stick Section**: Promotes the Amazon Fire TV Stick with an image and a "Get Started" button.
- **Footer**: Includes the Amazon logo, terms, feedback links, and a scroll-to-top arrow with hover animation.
- **Scroll-to-Top Functionality**: Smooth scrolling to the top of the page when clicking the footer arrow.
- **Responsive Design**: Optimized for mobile, tablet, and desktop screens using media queries and Bootstrap's grid system.

## Technologies Used
- **HTML5**: For the structure of the web page.
- **CSS3**: For custom styling, including hover effects, media queries, and layout adjustments.
- **JavaScript**: For the sticky navbar functionality and scroll-to-top feature.
- **Bootstrap 5.3.1**: For responsive layout, navbar, buttons, and grid system.
- **Font Awesome 4.7.0**: For icons (search, user, and dropdown arrows).
- **External Resources**:
  - Bootstrap CSS and JS via CDN.
  - Font Awesome via CDN.
  - External images for hero, rentals, channels, and Fire TV Stick sections.

## File Structure
```
├── index.html        # Main HTML file
├── style.css         # Custom CSS for styling
├── index.js          # JavaScript for sticky navbar and scroll-to-top
└── README.md         # Project documentation
```

## Setup Instructions
1. **Clone or Download the Repository**:
   ```bash
   git clone <repository-url>
   ```
   Alternatively, download the project files as a ZIP and extract them.

2. **Open the Project**:
   - Navigate to the project folder.
   - Open `index.html` in a web browser to view the page.

3. **Dependencies**:
   - No local dependencies need to be installed, as the project uses CDNs for Bootstrap and Font Awesome.
   - Ensure you have an active internet connection for the CDNs to load properly.

## Usage
- **Navigation**: Use the navbar to explore dropdown menus for Home, Store, and Categories. Click the search or user icons for interactivity (currently placeholders).
- **Hero Section**: View the welcome message and click "Sign in to join Prime" (placeholder).
- **Movie Rentals**: Click "Rent Now" to simulate renting a movie (placeholder).
- **Favorite Channels**: Hover over channel logos for a zoom effect.
- **Fire TV Stick**: Click "Get Started" to simulate starting with Fire TV Stick (placeholder).
- **Scroll-to-Top**: Click the arrow in the footer to smoothly scroll back to the top.

## Responsive Design
The project is fully responsive with the following breakpoints:
- **Mobile (≤767px)**:
  - Collapsible navbar with a white toggler icon.
  - Adjusted font sizes and layouts for hero, rentals, channels, and Fire TV Stick sections.
  - Channel images take full width, and text is centered for better readability.
  - Footer arrow repositioned for smaller screens.
- **Tablet (768px–1024px)**:
  - Hero image scales to fit the screen.
  - Adjusted font sizes for headings and paragraphs.
  - Channel images and layouts optimized for tablet screens.
  - Footer arrow slightly repositioned.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

Please ensure your code follows the existing style and includes appropriate comments.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
