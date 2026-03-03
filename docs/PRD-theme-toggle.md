# PRD: Dark/Light Mode Theme Toggle

**Status:** ✅ Shipped (March 2026)

## Objective
Improve site accessibility and give users control over their viewing experience, demonstrating strong UX fundamentals.

## User Stories
* **Story 1.1:** As a visitor viewing the portfolio, I want to see a toggle that obviously indicates it is a dark/light switch, so I immediately know the option exists.
* **Story 1.2:** As a visitor, when I click the toggle, I want to see the page instantly switch from light to dark.
* **Story 1.3:** As a visitor viewing in dark mode, when I click the toggle, I want to see the page switch from dark to light.
* **Story 1.4:** As a returning visitor, I want the site to remember my previous theme selection so I don't have to toggle it every time I visit.

## Acceptance Criteria
* [x] Toggle UI (e.g., a sun/moon icon or text toggle) is placed prominently in the header or navigation area.
* [x] Clicking the toggle seamlessly updates the CSS variables (background and text colors) without requiring a page reload.
* [x] The user's preference is saved in the browser's `localStorage`.
* [x] On initial load, the site checks `localStorage` first; if empty, it defaults to the user's OS-level theme preference (`prefers-color-scheme`).