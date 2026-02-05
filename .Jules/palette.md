## 2025-05-15 - High-Contrast Focus Indicators for Dark Themes
**Learning:** In dark-themed interfaces, standard browser focus rings are often invisible. A 2px white outline with a 3px offset ensures focus visibility across all elements without interfering with their base design.
**Action:** Use `:focus-visible { outline: 2px solid #ffffff; outline-offset: 3px; }` as a baseline for dark themes.

## 2025-05-15 - Interactive Skip Link with Fixed Headers
**Learning:** When using fixed headers, skip-to-content links can be visually hidden but made accessible via a fixed-position container that translates into view on focus. This prevents layout shift while remaining perfectly accessible.
**Action:** Implement skip links using `position: fixed` and `transform: translateY(-100%)` (hidden) to `translateY(0)` (on focus).
