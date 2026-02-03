# Palette's Journal - Dimensions VFX

## 2025-05-14 - Accessibility Polish
**Learning:** Dark-themed websites often use very subtle focus indicators or even `outline: none` to maintain a "clean" aesthetic, which severely impacts keyboard accessibility. Symbolic buttons (like `‹` and `›`) also frequently lack ARIA labels.
**Action:** Always implement high-contrast `:focus-visible` styles with `outline-offset` for dark themes and ensure all icon/symbol buttons have descriptive `aria-label` attributes.
