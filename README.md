# 🐍 Snake ID — All Snakes of the World

A lightweight, offline-capable web app to search and explore **every currently recognized living snake species** (~4,249 species across 33 families).

## Features

- **Full taxonomic coverage** from The Reptile Database (June 2026 checklist)
- Instant search by scientific name, genus, or family
- Filter by family or by venomous / typically non-venomous families
- Direct links to each species page on the Reptile Database
- Mobile-friendly dark UI
- No backend, no API keys — pure static HTML + JS

## How to use

1. Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge).
2. Type a name (e.g. `Naja`, `Python`, `Viperidae`, `mamba`) in the search box.
3. Use the family dropdown or the quick chips to narrow results.
4. Click **Open in Reptile DB** for detailed distribution, synonyms, and references.

## Data source

Taxonomy and species list:

> Uetz, P., Freed, P., Aguilar, R., Reyes, F., Kudera, J. & Hošek, J. (eds.) (2026)  
> The Reptile Database, http://www.reptile-database.org, accessed via the 17 June 2026 checklist.

Venom status is a **family-level heuristic** only (Viperidae, Elapidae, Atractaspididae = medically significant venomous families). Many colubrids and other families contain rear-fanged species with mild venom. Always treat this as educational reference, never as medical advice.

## Disclaimer

**This is not a medical tool.** If you or someone else is bitten by a snake, seek emergency medical care immediately. Do not rely on any app (including this one) for treatment decisions.
