# README for index.html

1. What did you change? For what?
- Rebuilt the About, Projects, and Skills sections into a consistent card-based layout with the shared `section-neutral` styling. This keeps spacing, backgrounds, and typography uniform and easier to maintain.
- Converted the projects and skills content into matching two-column grids, making it simple to scan and ensuring responsive behavior mirrors across sections.
- Added supporting CSS hooks (like `.content-card`, `.project-card`, `.skill-card`) so future updates only need minimal edits for alignment or colors.

2. What is the main idea of this file?
- `index.html` is the single-page portfolio/landing site for Tran Tan Huan. It introduces the designer, highlights selected projects, showcases skills, and provides navigation anchors for experience, skills, and contact/CTA sections.

3. What did you use in this file?
- HTML5 semantics with Bootstrap 5 classes for layout, grids, and utilities.
- Custom CSS classes (`section-neutral`, `content-card`, etc.) defined in `css/11445030.css` to enforce the unified visual style.
- Font Awesome icons, Google Fonts, and the Start Bootstrap Grayscale theme assets already bundled with the project.
