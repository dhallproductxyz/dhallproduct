# PRD: Interactive Contact Form
**Status:** ✅ Shipped (March 2026)
## Objective
Reduce friction for recruiters, hiring managers, and peers who want to reach out. Replacing a direct `mailto:` link with an on-page form prevents drop-off caused by launching desktop email clients.

## User Stories
* **Story 2.1:** As a visitor, when I click the "Email Me" button, I want to see an interactive form so I don't have to leave the browser.
* **Story 2.2:** As a visitor, I want to input my Name, Email, and Message so I can provide all relevant context.
* **Story 2.3:** As a visitor, when I hit submit, I want to see a clear success message so I know the message was sent.
* **Story 2.4:** As the product owner, I want these submissions seamlessly routed directly to my inbox without managing a backend database.

## Acceptance Criteria
* [x] Form fields (Name, Email, Message) are styled to match global CSS variables.
* [x] Dark mode toggle successfully applies to the form inputs.
* [x] Netlify form detection is enabled and capturing submissions.
* [x] Submissions trigger an email notification to the site owner.
* [x] Users are successfully redirected to `success.html` upon submission.
* [x] Mobile view is responsive and text does not overlap.