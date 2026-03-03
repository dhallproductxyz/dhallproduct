# PRD: Interactive Contact Form

## Objective
Reduce friction for recruiters, hiring managers, and peers who want to reach out. Replacing a direct `mailto:` link with an on-page form prevents drop-off caused by launching desktop email clients.

## User Stories
* **Story 2.1:** As a visitor, when I click the "Email Me" button, I want to see an interactive form so I don't have to leave the browser.
* **Story 2.2:** As a visitor, I want to input my Name, Email, and Message so I can provide all relevant context.
* **Story 2.3:** As a visitor, when I hit submit, I want to see a clear success message so I know the message was sent.
* **Story 2.4:** As the product owner, I want these submissions seamlessly routed directly to my inbox without managing a backend database.

## Acceptance Criteria
* [ ] Form includes three required fields: Name (text), Email (email validation), and Message (textarea).
* [ ] Submit button provides visual feedback (e.g., hover state) so users know it is clickable.
* [ ] Form uses Netlify's built-in form handling (`data-netlify="true"`) to capture submissions.
* [ ] Upon successful submission, the form clears or shows a "Thank you" confirmation state.