## 2025-05-22 - Skip Link Positioning in Fixed Header Contexts
**Learning:** In projects with potentially complex or sticky headers, using `position: fixed` for 'Skip to content' links is more robust than `position: absolute`. Absolute positioning can cause the link to be partially obscured by other layout elements if not carefully managed.
**Action:** Default to `position: fixed` for skip links to ensure they always appear at the top of the viewport when focused, regardless of the surrounding layout.

## 2025-05-22 - Global Focus Indicators for Dark Themes
**Learning:** Dark-themed websites often suffer from invisible focus states. A global `:focus-visible` rule with a high-contrast outline (e.g., 2px white) and an `outline-offset` provides immediate accessibility gains across all interactive elements with minimal code.
**Action:** Always check for focus visibility in dark themes and implement a high-contrast `:focus-visible` fallback if needed.
