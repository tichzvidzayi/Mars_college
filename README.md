# ipsum_campus

# Careers and Study Opportunities Page

This project contains an HTML page titled **Careers and Study Opportunities**, which showcases a simple web layout using Bootstrap for responsive design. The page features a navigation bar, hero section, content with images and text, an accordion, a blog section, and a footer. The project is designed to be informative, user-friendly, and visually appealing.

## Project Structure

The project is built using HTML, Bootstrap, and custom CSS. The assets (images) are linked locally, and Bootstrap is loaded from a CDN.

### Key Features:
- **Responsive Navigation Bar:**
  - Includes a logo, navigation links, and a button aligned on the right.
  - Collapsible on smaller screens.
  
- **Hero Section:**
  - Contains a full-width banner image.

- **Content Section:**
  - Includes a text area with headings, paragraphs, and a call-to-action button.
  - Features two columns: one with text and the other with an image.

- **Form:**
  - A simple search input with a text field.

- **Blog Section:**
  - Displays three blog cards, each with an image and a short description.
  - Includes pagination controls.

- **Accordion:**
  - A collapsible section that allows users to expand and view different content blocks.

- **Footer:**
  - Displays the logo and social media icons.
  - Contains three columns with repeated placeholder content.

## Installation and Usage

### Prerequisites:
Ensure you have an internet connection to load Bootstrap via the CDN.
### SEO Notes

Added the following meta tags for SEO considerations:

```html
<meta name="description" content="Careers and study opportunities to advance your skills.">
<meta name="keywords" content="careers, study, education, opportunities">

### Setup Instructions:
1. Clone the project to your local machine.
2. Place your images in the `../public/images` folder as referenced in the HTML.
3. Ensure your custom styles are placed in the `styles.css` file, linked to the HTML page.
4. Open the `.html` file in any web browser to view the page.

```bash
# Clone the repository
git clone https://github.com/tichzvidzayi/ipsum_campus.git

# Navigate to the directory
cd careers-opportunities-page

# Open the HTML file in your preferred browser
open index.html

 .
├── index.html              # The main HTML file for the Careers and Study Opportunities page
├── styles.css              # Custom styles (if any) linked to the HTML page
└── public/
    └── images/
        ├── logo.svg        # Logo for the navbar
        ├── Banner.svg      # Hero section banner image
        ├── mountain.svg    # Image used in the content section
        ├── waterfall.svg   # Image for the first blog card
        ├── plane.svg       # Image for the second blog card
        └── camera.svg      # Image for the third blog card
