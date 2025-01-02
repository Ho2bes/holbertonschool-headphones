# Holberton School - Headphones

Welcome to the **Holberton School - Headphones** project! The main goal is to build **a fully functional web page** from scratch in pure **HTML and CSS**, without using any external libraries or JavaScript. You will apply all your knowledge in **HTML, CSS, Accessibility, and Responsive Design** to achieve a final result that matches the provided mockup.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Prerequisites and Constraints](#prerequisites-and-constraints)
3. [Resources](#resources)
4. [Repository Structure](#repository-structure)
5. [Tasks](#tasks)
   - [0. Figma Familiarization](#0-figma-familiarization)
   - [1. Header](#1-header)
   - [2. “What we do...” section](#2-what-we-do-section)
   - [3. “Our results” section](#3-our-results-section)
   - [4. Contact us](#4-contact-us)
   - [5. Footer](#5-footer)
6. [Important Design and Integration Notes](#important-design-and-integration-notes)
7. [Tips](#tips)
8. [Credits](#credits)

---

## Project Overview

Your task is to create a **static web page** that looks exactly like the design created by [Nicolas Philippot (UI/UX designer)](https://www.behance.net/nicolasphilippot).

Key objectives:
- Integrate a **complete design** in HTML/CSS **without any external libraries**.
- Handle **responsive design** so that the layout adapts to various screen sizes (especially below 480px).
- Pay attention to **accessibility** and semantic markup (as much as possible).
- Follow the **Figma specifications** for a **pixel-perfect** (or very close) result, keeping in mind that some values can be slightly rounded.

---

## Prerequisites and Constraints

- **No CSS libraries** (e.g., Bootstrap, Bulma, etc.) are allowed.
- **No JavaScript**—HTML and CSS only.
- Use a **CSS reset** or a **normalization** approach for a consistent base style.
- Consider using **CSS variables** for colors, fonts, etc.
- Keep your **HTML structure** clear with **generic CSS selectors** as much as possible.
- Ensure **responsiveness**:
  - The mobile version should activate when the screen width is ≤ `480px`.
  - Content should have a max-width of `1000px` and be centered on the page.
- Interactions:
  - **Link hover/active** color: `#FF6565`
  - **Button hover/active**: `opacity: 0.9`

---

## Resources

1. **Figma Mockups**
   - [Main Figma Project](https://www.figma.com/) – use “Duplicate to your Drafts” to get all design details (dimensions, colors, etc.).
   - [Alternate Figma File](https://www.figma.com/) if the main link is not accessible.
2. **Fonts and Icons**
   - [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro)
   - [Spin Cycle OT](https://www.dafont.com/spin-cycle.font)
   - [holberton_school-icon.zip](#) (included in the provided archive with custom icons and a demo file)
3. **Images**
   - [images_.zip](#) (archive containing all necessary images)

> **Note**: If some fonts are missing on your computer, please install them locally or use alternative ones.

---

## Repository Structure

Your **holbertonschool-headphones** GitHub repository will contain multiple pairs of HTML/CSS files for each stage of the project:


- Each **step** of the project is in a pair of files (e.g., `0-index.html` and `0-styles.css` for the first milestone).
- **Images** and **icons** should be placed in separate folders (e.g., `images/`, `icons/`) for clarity (create them as needed).
- The `README.md` file is at the root of the repository.

---

## Tasks

### 0. Figma Familiarization
**Deliverable**: `README.md`

1. Create a [Figma](https://www.figma.com/) account if you don’t have one already.
2. Duplicate the mockup (“Duplicate to your Drafts”) to measure elements, colors, and dimensions.
3. Install the required fonts or use a web-based approach (e.g., Google Fonts).
4. **Write** this README to explain the project, its objectives, resources, etc. (You’re reading it right now!)

### 1. Header
**Deliverables**: `0-index.html`, `0-styles.css`

- Set up the **foundation** of your page:
  - A CSS reset or normalization in your stylesheet.
  - **Variables** (colors, fonts...) if needed.
  - A clear **HTML structure** (semantic tags, containers, etc.).
- Integrate the **Header / Hero** section from the mockup:
  - The **logo** or title.
  - The **navigation bar** (no JavaScript, so keep it simple).
  - The **main hero image or illustration**.
  - Any **headline** or **introductory text**.

### 2. “What we do...” section
**Deliverables**: `1-index.html`, `1-styles.css`

- Copy your files from task #1 to a new version (`1-index.html`, `1-styles.css`).
- Build the **“What we do...”** section:
  - Integrate the **icons** (found in `holberton_school-icon.zip`).
  - Use a **reusable** layout (Flexbox or Grid).
  - Maintain **responsiveness** and follow the Figma design.

### 3. “Our results” section
**Deliverables**: `2-index.html`, `2-styles.css`

- Copy your files from task #2 to new files (`2-index.html`, `2-styles.css`).
- Implement the **“Our results”** section:
  - **Reuse** components or CSS classes you created earlier.
  - Incorporate **cards** (or a similar layout) to show results.

### 4. Contact us
**Deliverables**: `3-index.html`, `3-styles.css`

- Add a **contact form** with fields like name, email, and message, plus a “Send” button.
- You can enhance the form with **animations** or **constraints** (e.g., `required` inputs).
- Keep consistency with your **color palette** and **typography**.

### 5. Footer
**Deliverables**: `4-index.html`, `4-styles.css`

- Add the **footer** as specified in the mockup:
  - Additional links, copyright, logo, etc.
  - Responsive design below `480px`.
- Finalize the entire page:
  - Check the consistency of margins, paddings, colors, etc.
  - Ensure it matches the mockup in desktop and mobile views as closely as possible.

---

## Important Design and Integration Notes

- **Rounding values**: The Figma mockup might present floating values (e.g., `14.37px`). Feel free to round them to integers or tenths.
- **CSS organization**: Keep a clear structure (e.g., variables, reset, generic elements, layout, components, etc.).
- **Modern CSS**: Feel free to use `flexbox`, `grid`, and media queries (`@media`) for responsive design.

---

## Tips

- **Start from the outside in**: outline the main containers (header, sections, footer), then go deeper into specific elements.
- **Use reusable classes**: avoid overly specific selectors that are hard to maintain later.
- **Test frequently** on different screen sizes or use browser developer tools to emulate devices.
- For **hover/active** states, use the CSS pseudo-classes `:hover` and `:active`.
- Check **accessibility**: use `<label>` for form fields, `alt` attributes for images, etc.

---

## Credits

- **Designer**: [Nicolas Philippot](https://www.behance.net/nicolasphilippot)
- **Fonts**: [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro), [Spin Cycle OT](https://www.dafont.com/spin-cycle.font)
- **Icons**: Included in the `holberton_school-icon.zip` archive
- **Images**: Found in the `images_.zip` archive

Thank you for reading this README.
**Good luck** and have fun **building** this web page with (almost) pixel-perfect precision!

---

<p align="center">
  <strong>Happy coding!</strong>
</p>
