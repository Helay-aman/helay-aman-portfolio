# Your Name - Creative Portfolio Website

## Project Overview

This repository contains the source code for my personal portfolio website, a final project for [Your Course Name, e.g., "Introduction to Web Development"]. The goal was to design and build a multi-page website using only HTML and CSS, focusing on creative expression and demonstrating foundational front-end development skills.

## Theme & Inspiration: "Zen & Flow"

My inspiration for this portfolio was to create a calm, organized, and inviting digital space. I aimed for a "Zen & Flow" aesthetic, where simplicity and clear presentation allow the content to shine without overwhelming the user.

* **Color Scheme:** I chose a calming green (`#4CAF50`) as the primary accent, representing growth, nature, and freshness. This is complemented by a warm, subtle yellow/gold (`#FFC107`) for secondary accents, symbolizing optimism and a touch of warmth. The main text is a soft black (`#333333`) for readability, set against light grey (`#F5F5F5`) and pure white (`#FFFFFF`) backgrounds to maintain a clean and spacious feel.
* **Typography:** For headings, I selected `Lora`, a classic serif font that brings an elegant and strong presence. For body text, `Open Sans`, a highly readable sans-serif font, ensures clarity and a modern, clean look. Both fonts are sourced from Google Fonts.
* **Visual Style:** The design emphasizes clean lines, subtle shadows, and ample white space to create a harmonious user experience.

## Design Decisions & Creative Elements

* **Custom Fonts:** Implemented `Lora` for headings and `Open Sans` for body text via Google Fonts to establish a distinct typographic voice.
* **Color Palette:** The chosen "Zen & Flow" palette aims to evoke feelings of calm and professionalism while still being visually engaging.
* **Hover Effects/Animations/Transitions:**
    * **Navigation Links:** A subtle slide-in underline effect on hover, indicating interactivity.
    * **Buttons:** A slight `translateY` (lift) and `background-color` change on hover, providing visual feedback.
    * **Portfolio Project Cards:** A subtle lift and increased box-shadow on hover to highlight interaction.
    * **Home Page Hero:** A `fadeIn` animation on the main content for a welcoming entrance.
    * **Profile Photo:** A gentle zoom effect on hover for the profile image on the About Me page.
* **Custom Graphic Element:** On the "About Me" page, I've included a placeholder for a custom SVG icon/graphic (e.g., a simple abstract shape, a small plant, a coding symbol) positioned as an overlay on the profile photo. This adds a unique personal touch and visual interest. *(Note: You will need to create and replace `images/custom-graphic.svg` with your own design.)*
* **Semantic HTML:** Used HTML5 semantic tags like `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<figure>`, `<figcaption>` to ensure meaningful structure and accessibility.
* **CSS Organization:** The `style.css` file is organized with comments into sections (Global Styles, Navigation, Buttons, Page-Specific Styles, Animations, Responsive Design) for clarity and maintainability.

## Technical Requirements Fulfilled

* **HTML & CSS Only:** No JavaScript is used for the core functionality. (A tiny JS snippet for `filterRecipes` on the list page is a placeholder and doesn't implement actual filtering, just console logs).
* **Flexbox/Grid Layout:**
    * The `navbar` utilizes **Flexbox** for horizontal alignment and spacing of navigation links.
    * The `portfolio-grid` on the Portfolio page uses **CSS Grid** to create a responsive layout for project cards.
    * The `about-section` on the About Me page uses **Flexbox** to arrange the image and text side-by-side on larger screens.
* **Responsive Design:** Media queries are implemented in `style.css` to adjust the layout for different screen sizes (mobile, tablet, desktop).
* **Semantic HTML & Validity:** All HTML elements are chosen for their semantic meaning, contributing to better accessibility and SEO.
* **Clean & Commented CSS:** The CSS is formatted for readability and includes comments to explain different sections and complex rules.

## Challenges Faced (Example - You should customize this!)

During the development of this project, I initially faced a challenge in achieving a consistent hover effect across different elements while maintaining a cohesive visual style. Experimenting with various `transition` properties and `transform` values helped me find a balance between subtle animation and clear user feedback. Another learning point was ensuring the responsiveness of the `about-section` where the image and text needed to stack gracefully on smaller screens, which was solved by adjusting `flex-direction` in media queries.

---

Remember to **replace `[Your Name]`** and all placeholder image paths/descriptions with your actual content and files. Good luck with your project! You've got this!