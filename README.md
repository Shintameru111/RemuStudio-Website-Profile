# RemuStudio — Stage 1 refined

Static bilingual company website for RemuStudio (website development and data-entry services).

## Run locally
1. Extract the ZIP.
2. Open this folder in VS Code.
3. Open `index.html` in a browser, or use the Live Server extension.

## Contact form email setup
The contact form uses FormSubmit AJAX and sends inquiries to `kotaverse@gmail.com`. On the first real submission, FormSubmit sends an activation email to that inbox. Open it and confirm the activation before expecting future inquiries to arrive. Check spam/junk too. This static frontend does not expose an email password or SMTP credential.

## Notes
- The service dropdown uses a light option list for readable contrast on the dark contact panel.
- Project cards open concept-detail dialogs. They are sample concepts, not live client projects.
- The Client Portal is still a visual preview; real accounts, file uploads and project tracking require the next backend stage.
- For production use, add server-side validation, spam protection, privacy policy and a backend rather than relying only on a static form endpoint.
