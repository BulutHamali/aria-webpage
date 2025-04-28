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


# Reflection Questions
### What accessibility challenges did you face, and how did you address them?
- **Understanding ARIA**: I found ARIA roles and attributes (like `role="navigation"` and `aria-label`) challenging to implement correctly. I addressed this by researching ARIA best practices and adding roles to key sections, such as the navigation bar.


### How did you ensure that your design was responsive and accessible to all users?
- **Responsive Design**:
  - Implemented Flexbox for the navigation bar, allowing it to switch from a horizontal layout on desktop to a vertical stack on mobile devices.
  - Used CSS Grid in the "Our Services" section, with media queries to adjust the layout from three columns on desktop to two on tablet and one on mobile.
  - Tested the site by resizing the browser window to ensure it adapted well across different screen sizes.
    
- **Accessibility**:
  - Added ARIA roles and attributes to enhance screen reader compatibility, such as `role="banner"` for the header and `aria-live="polite"` for form error messages.
  - Ensured the contact form had accessible labels, `required` attributes, and `aria-describedby` for instructions and errors.

### What tools or resources did you find most helpful during this project?
- **Tools**:
  - Used Visual Studio Code as my editor, which helped with syntax highlighting and spotting errors in my HTML and CSS.
  - Leveraged Chrome Developer Tools to test responsive design and debug layout issues, such as adjusting image sizes.
- **Resources**:
  - Found W3Schools tutorials helpful for learning the basics of HTML, CSS, Flexbox, and Grid.
