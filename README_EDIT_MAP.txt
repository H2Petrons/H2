# H2petrons Website (Annotated)

This version includes `<!-- EDIT: ... -->` comments in every page so you can quickly find what to change.

## Files
- `index.html` — Home (hero text, CTAs, optional hero image)
- `about.html` — About (project/company story, optional team section)
- `plans.html` — Plans (3-year outline; add more detail as needed)
- `tools.html` — Tools (your software/hardware stack)
- `contact.html` — Contact (wire to Formspree/Netlify Forms or replace with email/Discord links)

## Edit Map
Search for **`EDIT:`** in files to jump to editable spots:

### Global
- **Brand/Name:** header nav link text in all pages
- **Colors:** Tailwind brand colors in the `<script>` block (brand 400/500)
- **Socials:** footer links (`#`) → replace with real URLs
- **Main Page link:** nav includes link to https://h2petrons.github.io/H2/ (remove if not needed)

### index.html
- Headline & subheadline
- Buttons (labels + href)
- Optional hero image (commented block)

### about.html
- Overview text (who you are/mission)
- Optional team cards (comment block)

### plans.html
- Year 1/2/3 bullet points (edit freely)
- Optional timeline image

### tools.html
- CAD/CFD/FEA/Collab/Cloud lists (add/remove items)

### contact.html
- Form fields/labels
- **Form action** (Formspree/Netlify Forms) or replace with email/Discord links
- Button text

## Host on GitHub Pages
1. Create a public repo (e.g., `H2`), upload these files to the repo root.
2. Settings → Pages → Deploy from branch (`main` / root).
3. Live at `https://<USERNAME>.github.io/H2/`.

