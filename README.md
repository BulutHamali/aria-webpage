# My Training Website: Accessible Design Company
This is a static website for **Accessible Design Co**, a fictional company focused on accessibility in design. I built this as a learning project to practice web development skills, focusing on semantic HTML, responsive design, and accessibility.

## What’s in This Website?
- **Semantic HTML**: Structured with proper elements like `<header>`, `<main>`, `<section>`, and `<footer>` for better accessibility and SEO.
- **Responsive Design**:
  - Uses Flexbox for the navigation bar, which stacks vertically on mobile.
  - Uses CSS Grid for the "Our Services" section, switching from three columns on desktop to two on tablet and one on mobile.
- **Accessibility**:
  - Includes ARIA roles (e.g., `role="navigation"`, `role="banner"`) and attributes (e.g., `aria-label`, `aria-live`).
  - All images have meaningful `alt` text; decorative images use `alt=""`.
  - Contact form has accessible labels, `required` attributes, and `aria-describedby` for instructions and error messages.
- **Contact Form**: Fields for Name, Email, Subject, and Message, with validation-ready error spans.
- **Visual Design**: Styled with a clean, minimal design, including a consistent background for the header and footer.