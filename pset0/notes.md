# CS50W – Project 0 / Search  
## Notes – 22 Nov 2025

### What I built today
- Created the basic project structure with `index.html` and `style.css`.
- Added a Google-style search form:
  - Text input for the query.
  - Submit button sending a `GET` request with the correct query parameter.
- Added an **“I’m Feeling Lucky”** button that submits the form with different behaviour (will wire fully later if needed).
- Added initial styling to the form:
  - Centred the search box on the page.
  - Adjusted padding/margins for inputs and buttons.
  - Removed default link/button styles where needed and applied custom ones.

### What I practised / learned
- Reviewing how HTML forms work with `action`, `method="get"` and named inputs.
- Using separate submit buttons in the same form for different behaviours.
- Basic layout with CSS (centering, spacing around the form).
- Refining small UI details: button appearance, hover cursor, and text decoration.

### Things I’d like to improve next time
- Make the layout more responsive (behave better on small screens).
- Improve accessibility:
  - Ensure all inputs have `<label>` elements.
  - Check focus styles instead of just removing outlines.
- DRY up the CSS if I repeat styles between buttons or future pages.

### Open questions / follow-ups
- Best way to share header/nav and base styles across index / image / advanced pages.
- Whether to keep using plain CSS or introduce a small utility class system for spacing.

