# ETHIQ — Think. Reflect. Decide.

Interactive ethics reflection website for OLVAL02 Ethics, ICCT College Cainta, 2026.

## Included
- 300 source reflection cards from `ETHICARDS_300.pdf`
- Six categories
- English / Tagalog toggle
- Search and category filtering
- Random Question
- Reflection notes saved in the browser with localStorage
- Progress tracking on the current device
- Animated category cards and question cards
- About and Credits sections with the supplied photos
- Responsive desktop/mobile layout

## GitHub Pages
Upload the contents of this folder to your GitHub repository and enable GitHub Pages from the repository's Pages settings.

The site is static: `index.html`, `questions.js`, `questions.json`, and `assets/` are all that are needed for the website to run.

## Important source note
The supplied 300-card source contains these actual category counts: Self 50, Relationships 50, Dilemmas 50, Digital Life 50, Moral Compass 48, Justice 52. The website preserves the source organization and keeps the total at 300 rather than silently rewriting or inventing cards.

## Google Sheets feature
The About section describes the planned personal Google-account/Google-Sheet save feature. The current GitHub-only build uses browser localStorage for reflections and progress; Google OAuth/Sheets API integration is a separate configuration step and is not falsely presented as already connected.
