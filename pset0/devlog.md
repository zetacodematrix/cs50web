# CS50W – Project 0: Search  
# Developer Log (`devlog.md`)

A running development log documenting progress, decisions, learning, and next steps for the CS50W Project 0.

---

## 📅 22 Nov 2025

### What I built today
- Created the basic project structure with `index.html` and `style.css`.
- Added a Google-style search form:
  - Text input for the query.
  - Submit button sending a `GET` request with the correct query parameter.
- Added an “I’m Feeling Lucky” button (basic version).
- Added initial styling:
  - Centred the search box.
  - Adjusted padding/margins.
  - Cleaned up buttons and link styles.

### What I practised / learned
- Form mechanics (`action`, `method="get"`, named parameters).
- Using two submit buttons for different behaviours.
- Basic CSS layout and spacing.
- Small UI refinements like hover and cursor behaviour.

### Things to improve next time
- Better responsiveness on small screens.
- Accessibility through `<label>`s and proper focus states.
- Cleaner, more DRY CSS.

### Open questions
- How to share header/nav/base styles across multiple pages?
- Should I keep plain CSS or introduce lightweight utilities?

---

## 📅 23 Nov 2025

### What I built today
- Refactored and polished `index.html`:
  - Added semantic structure: header, main, section, footer.
  - Added accessible labels, `sr-only` class, ARIA improvements.
  - Added a minimal nav (Images / Advanced).
  - Wrapped form in a centred search panel.
- Expanded `styles.css`:
  - Added reset + CSS custom properties with design tokens.
  - Built responsive, centred layout with flexbox.
  - Created Google-style rounded search bar.
  - Created `btn-primary` and `btn-secondary` styles.
  - Added mobile-friendly tweaks.
- Interaction polish:
  - Focus-within glow on search bar.
  - Hover and focus-visible states.
  - Improved keyboard accessibility.

### What I practised / learned
- Semantic HTML + accessibility patterns.
- CSS architecture with design tokens.
- Responsive layout using flexbox.
- Interaction styling using `:focus-visible` and `:focus-within`.
- Component-style CSS (nav links, search bar, buttons).

### Things to improve next time
- Apply styles + structure to `images.html` and `advanced.html`.
- Consider shared header/nav patterns.
- Consider light utility spacing classes.
- Maybe explore theme variables (optional).

### Open questions
- Should header/nav be extracted to a shared stylesheet later?
- How closely to mimic actual Google “I’m Feeling Lucky” behaviour?

---

_End of current log._

