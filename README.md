# Project0 - Responsive Multi-Page Website

## Overview
Project0 is a responsive multi-page website designed using **Bootstrap 4, SCSS, and HTML5**. It showcases modern web design techniques such as responsive layouts, modular styling with SCSS, and structured navigation.

## Project Structure

### HTML Files and Implementation Details

1. **`index.html`** - **Home Page**
   - Implements a **Bootstrap navbar** with a collapsible menu.
   - Uses a **two-column layout** (`col-md-6`) for content distribution.
   - Includes sections highlighting the **Taj Mahal** and its features.

2. **`about.html`** - **About Page**
   - Provides a **detailed historical overview** of the Taj Mahal.
   - Implements a **highlight section (`#highlight`)** for emphasis.
   - Uses **Bootstrap cards** to enhance content presentation.

3. **`gallery.html`** - **Gallery Page**
   - Features a **responsive image grid** implemented using Bootstrap’s grid system (`col-md-4 col-sm-6 col-12`).
   - Includes sample images from the "images" folder.
   - Ensures all images are **fluid (`img-fluid`)** to maintain responsiveness.

4. **`contact.html`** - **Contact Page**
   - Displays **contact details** in a structured table format.
   - Uses **Bootstrap utilities** for responsive design.
   - Includes an **email link (`mailto:`)** and phone number section.

### CSS & SCSS Files

1. **`styles.scss`** - **SCSS Source File**
   - Implements **variables** (e.g., `$primary-color`, `$highlight-color`) for easy theme changes.
   - Uses **mixins** to define reusable styles.
   - Applies **inheritance (`@extend`)** for styling elements like `.card`.
   - Organizes styles with **nesting**, improving maintainability.

2. **`styles.css`** - **Compiled CSS File**
   - Contains styles compiled from `styles.scss`.
   - Includes universal, element, class, and ID selectors.
   - Ensures proper styling for headers, navigation, sections, and responsive layouts.

3. **`styles.css.map`** - **Source Map for Debugging**
   - Allows developers to trace SCSS rules back to their source in `styles.scss`.

### JavaScript Integration
- **Bootstrap Components** (`navbar`, `collapse`, etc.) are enabled using:
  - `jQuery` (`jquery-3.5.1.slim.min.js`)
  - `Popper.js` (`popper.min.js`)
  - `Bootstrap JS` (`bootstrap.min.js`)

## Features and Implementation Highlights
✔ **Fully Responsive Design** – Ensures compatibility across all screen sizes.  
✔ **Bootstrap 4 Grid System** – Provides structured layout and flexible content arrangement.  
✔ **SCSS Enhancements** – Uses variables, mixins, and inheritance for maintainability.  
✔ **Navigation System** – Includes a responsive, collapsible navbar for smooth user interaction.  
✔ **Structured Content Sections** – Implements Bootstrap cards, highlights, and tables for content organization.  
✔ **Optimized Image Display** – Ensures images resize appropriately for various screen sizes.

## How to Run the Project
1. Open any `.html` file (e.g., `index.html`) in a web browser.
2. Ensure `styles.css` is in the same directory as the HTML files.
3. An internet connection is required to load Bootstrap and jQuery from CDN.

## Technologies Used
- **HTML5** – Structure and layout.
- **CSS3 & SCSS** – Styling and maintainability.
- **Bootstrap 4** – Responsive design and components.
- **JavaScript** – Bootstrap interactivity.

