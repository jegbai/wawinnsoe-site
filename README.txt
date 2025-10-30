Wawin National School of Excellence — Website Package
Generated: 2025-10-29T01:57:12.400454

Contents:
- index.html, about.html, admissions.html, academics.html, staff.html, gallery.html, contact.html
- admin/index.html (Netlify CMS placeholder) and admin/config.yml
- files/Prospectus.pdf, files/School_Rules.pdf, files/Fee_Structure.pdf (sample PDFs)

How to deploy (GitHub Pages):
1. Create a new GitHub repository and push the contents of this package to the repository root.
2. In GitHub repository settings -> Pages, set the source to the main branch (root) and enable GitHub Pages.
3. Your site will be available at https://<username>.github.io/<repo-name>/

How to deploy (Netlify) — recommended if you want Netlify CMS:
1. Create a Netlify site and connect your Git repository.
2. Add the folder 'admin' to the site root. Configure Netlify Identity and Git Gateway (follow Netlify docs).
3. Use Netlify's drag-and-drop deploy or connect to GitHub for continuous deploys.

Netlify CMS quick notes:
- Netlify CMS requires Identity and Git Gateway to be configured to edit content via admin panel.
- The file admin/config.yml is a minimal starter; adjust collections and fields to match your content structure.

Customizing:
- Edit the HTML files in the root to change text, images, and links.
- Replace files/ PDFs with your official documents.
- To enable form submissions, connect forms to a backend endpoint or use a service like Formspree / Netlify Forms / Google Forms.

Contact info included in site:
- Phone: +675 555 0123
- Email: info@wawin.edu.pg

