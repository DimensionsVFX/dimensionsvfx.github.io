## 2024-07-23 - Accessible Names for Symbolic Buttons

**Learning:** Buttons that use symbolic characters (e.g., '‹', '›', '×', '+') as their visual content must have an `aria-label` to provide an accessible name for screen readers. Relying on the symbol alone is insufficient, as screen readers may announce them non-descriptively (e.g., "less-than sign," "multiplication sign"), confusing users.

**Action:** Whenever implementing or reviewing buttons that contain only symbols or icons, I will ensure they have a descriptive `aria-label` that clearly communicates their function (e.g., "Scroll left," "Close dialog," "Add item").
