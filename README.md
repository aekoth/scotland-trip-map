# Scotland · 10-Day Trip Map 🏴󠁧󠁢󠁳󠁣󠁴󠁿

An interactive, scroll-driven map of a 10-day Scotland trip (Inverness → Edinburgh).
Scrolling advances through the days: the map flies to each stop, the route draws in,
and a side panel fills with details. Region swap-options, a booking checklist, and a
packing list round it out.

## Files
- **`index.html`** — the whole app, self-contained (map tiles load from CARTO/OpenStreetMap via CDN).
- **`Scotland-10-Day-Plan.md`** — the source itinerary.

## View it locally
Open `index.html` in any browser, or serve the folder:

```bash
python -m http.server 4321
# then visit http://localhost:4321
```

## Hosting (GitHub Pages)
Settings → Pages → Build from branch → `main` / root. Live at
`https://<username>.github.io/<repo>/`.
(Pages on a **private** repo requires a GitHub Pro/Team plan.)
