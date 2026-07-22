# Oregon Coast + Yamhill Trip

A mobile-friendly road-trip planner for the July 23–August 3, 2026 trip through Ogden, Pendleton, Hood River, Depoe Bay, and Yamhill.

The site includes the daily itinerary, projected driving time, location-ranked roadside stops, a persistent packing checklist, Depoe Bay planning, and official weather/AQI/fire/road-condition links.

## Publish with GitHub Pages

1. Create a new repository on GitHub. A public repository works with GitHub Free.
2. Upload all files from this repository, including the `.github` folder.
3. Open **Settings → Pages** in the GitHub repository.
4. Under **Build and deployment**, choose **GitHub Actions** as the source.
5. Open the **Actions** tab. The included workflow will build and publish the site.
6. When the workflow finishes, return to **Settings → Pages** for the public URL.

Every push to `main` republishes the app automatically.

## Run locally

Requires Node.js 20 or newer.

```bash
npm install
npm run dev
```

Then open `http://localhost:3000`.

## Build locally

```bash
npm run build
```

The static site is written to `out/`.

## Privacy reminder

GitHub Pages sites published through a free public repository are public. Do not add reservation codes, entry instructions, private family addresses, or other sensitive details. The public version intentionally says the Depoe Bay rental address is saved offline.

The packing checklist is stored only in each browser's local storage. Brian and Miranda will therefore have separate checklist state on their respective phones.
