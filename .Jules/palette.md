# Palette's UX Journal

## 2025-05-15 - [Accessibility Polish: Skip Links & Form Feedback]
**Learning:** For static sites with heavy navigation, a skip-to-content link is essential for keyboard accessibility. Using `transform: translateY` for the skip-link transition is more reliable than `top` or `display` properties for ensuring it enters the viewport correctly when focused. Additionally, `aria-live="polite"` is crucial for dynamic form feedback (success/error messages) to be announced to screen readers without interrupting the user.
**Action:** Always include a skip link as the first focusable element in the body and use ARIA live regions for any dynamic text updates in forms.
