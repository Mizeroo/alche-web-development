# CSS, Advanced

## About the Project

This project is the styling phase of the **Smile School** landing page, built as part of the Front-End Web Development curriculum at ALCHE (African Leadership College of Higher Education). It follows directly from the previous project, *HTML, Advanced*, where the full page structure was built in `index.html`.

Here, the focus shifts entirely to **CSS**: taking the static HTML skeleton and turning it into a fully styled, pixel-accurate page based on a Figma design file. The goal is not just to make the page "look nice," but to reproduce the designer's intent precisely — correct colors, spacing, typography, alignment, and layout — while keeping the CSS clean, simple, and reusable.

No external libraries or frameworks are used. Only plain HTML, CSS, and (where needed) JavaScript.

## What This Project Covers

By working through this project, the following concepts are put into practice:

- What CSS is and how it's used to style a webpage
- How to add styles to elements using classes and selectors
- How CSS specificity is calculated and how it affects which styles apply
- Box model properties (margin, border, padding, content) and how they shape layout
- How a browser loads and renders a webpage, from HTML parsing to final paint

## Project Structure

```
css_advanced/
├── README.md
├── index.html
└── styles.css
```

- **`index.html`** — The complete markup for the Smile School landing page (carried over from the HTML, Advanced project).
- **`styles.css`** — All styling for the page, imported into `index.html` via:
  ```html
  <link rel="stylesheet" href="styles.css">
  ```
- **`README.md`** — This file.

## Sections Styled

The page is built and styled section by section, matching the Figma design:

1. **Header & Banner** — Logo, navigation links, hero heading, subtext, call-to-action button, and background image.
2. **Quotes** — A highlighted testimonial block with author image and title.
3. **Videos List** — A grid/list of popular video cards, each with a thumbnail, play icon, title, description, author, star rating, and duration.
4. **Membership** — A row of membership benefits, each with an icon, heading, and description, plus a call-to-action button.
5. **FAQ** — A 2x2 grid of frequently asked questions with titles and text.
6. **Footer** — Logo, social media links, and copyright notice.

## Design Reference

All colors, dimensions, fonts, and spacing come directly from the project's Figma file. Where values were given as decimals, they were rounded for practical use in CSS.

Fonts used:
- Source Sans Pro
- Spin Cycle OT

## Approach

- CSS selectors are kept as simple and specific as possible, avoiding unnecessary nesting or overly complex specificity chains.
- Repeated patterns (buttons, rounded images, section titles) are styled with reusable, shared class rules instead of duplicating styles across sections.
- Layout is built with a combination of Flexbox and centered containers to match the Figma spacing without stretching content to the full width of the page.

## Deployment

The finished page is deployed using **GitHub Pages**, making it viewable directly from the repository without any local setup.

## Author

Built by Laetitia  Mizero as part of the Front-End Web Development curriculum at ALCHE.