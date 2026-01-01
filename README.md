# Open-Source Arms Transfers Map

This repository hosts a fully client-side interactive map of international arms transfers from 2000–2024. The map is built with [Leaflet](https://leafletjs.com/) and uses an embedded JSON dataset, so no backend or external API is required once the page is loaded.

## How to use

1. Open `index.html` in your browser, or host it via GitHub Pages.
2. Use the **Year** slider at the top to select a year from 2000–2024.
3. Use the **View** toggle to switch between:
   - **As exporter** – shows transfers where the selected country is the exporter.
   - **As importer** – shows transfers where the selected country is the importer.
   - **Both** – shows all transfers involving the selected country in that year.
4. Click a country marker to see a breakdown by partner, weapon system, and transfer value for that year.

## GitHub Pages deployment

1. Create a new GitHub repository.
2. Upload `index.html` and `README.md` to the root of the repository.
3. In the repository settings, enable **GitHub Pages**:
   - Source: **Deploy from a branch**
   - Branch: **main** (or `master`), folder: **/** (root)
4. After Pages builds, your map will be available at the GitHub Pages URL shown in the settings page.

