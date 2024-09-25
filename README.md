# Semantic and Accessible Page

This repository provides an example of using semantic HTML markup to create an accessible and well-structured web page. Proper semantics not only improves accessibility for users but also enhances SEO optimization. The project includes various examples of semantic elements such as headings, lists, tables, forms, images, interactive, and adaptive elements.

## Project Structure

The project consists of the following sections:

1. **Article** — An example of an article using `<article>`, `<header>`, `<time>`, and `<footer>` tags.
2. **Details** — An example of the `<details>` tag for creating expandable content.
3. **Form** — A contact form with `<input>`, `<textarea>`, and a `<button>`.
4. **Buttons** — Different examples of buttons: a regular button, a form submission button, and a reset button.
5. **List** — An example of using unordered lists to structure information.
6. **Table** — A table displaying students' grades, including a caption and header.
7. **Images** — An example of an image with a caption and an `alt` attribute for accessibility.
8. **Text Elements** — Using `<p>` and `<span>` for proper text structure and styling.

## Technologies Used

- **HTML5** — For semantic markup of the page.
- **CSS** — For styling the page elements (see `styles.css`).
- **JavaScript** — To dynamically update the year in the footer based on the current year.

## Importance of Semantics

Semantic markup enhances:

- Accessibility for users with disabilities.
- Optimization for search engines (SEO).
- Code maintainability for other developers.

## Accessibility Features

This project incorporates several key accessibility features:

- **Semantic HTML**: Using semantic tags to improve navigation for assistive technologies.
- **Alt Text for Images**: All images include descriptive `alt` attributes.
- **Keyboard Navigation**: Interactive elements are fully navigable via keyboard.
- **Contrast Ratios**: The color scheme meets WCAG contrast recommendations.
- **Form Labels**: Each form field has associated `<label>` elements.
- **Error Identification**: Clear error messages and instructions for forms enhance usability.

## Usage

Clone this repository using:
   ```bash
   git clone https://github.com/Olena-P/semantic-accessible
   ```
Navigate to the project directory: 
   ```bash
   cd semantic-accessible
   ```
Open the page in your browser by double-clicking on the `index.html` file or using the terminal: 
```bash
open index.html  # for Mac
```
```bash
start index.html # for Windows
```
Feel free to modify the HTML, CSS, or JavaScript files to customize the content, styles, or functionality.

## Testing Accessibility

To ensure the page is accessible, you can use tools such as:

- **Wave Chrome Extension**: Analyze your web page for accessibility issues.
- **axe DevTools**: Provides detailed accessibility reports during development.
- **Lighthouse**: Built-in tool in Chrome DevTools for auditing accessibility.

## Conclusion

Ensuring web accessibility is a continuous process that benefits everyone. By adhering to best practices and utilizing semantic HTML, developers can create more inclusive web experiences for all users.
