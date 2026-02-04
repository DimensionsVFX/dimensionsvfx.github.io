## 2025-05-14 - Accessible Focus in Dark Themes
**Learning:** On dark-themed sites, standard focus outlines are often invisible or high-contrast but poorly positioned. Using `:focus-visible` with a 2px white outline and a positive `outline-offset` (e.g., 3px) provides a clear, "floating" focus indicator that doesn't conflict with the element's design or borders, and ensures accessibility without cluttering the mouse-user experience.
**Action:** Default to `:focus-visible` with `outline-offset` for dark-themed projects to ensure clear keyboard navigation visibility.
