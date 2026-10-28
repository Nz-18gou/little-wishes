# Little Wishes ✿

A cute, mobile-first wishlist and goal manager.

## Features
- Add, edit, complete, and delete wishes
- Custom categories
- Target dates and overdue / due-soon labels
- High, medium, and someday priorities
- Search, filters, and sorting
- Completion percentage and progress counters
- Completed wishes are crossed out and tucked into a collapsible section
- Local browser storage plus JSON export/import backup
- PWA manifest and service worker for home-screen installation and offline shell caching

## Run it
Open `index.html` in a browser for basic use. Data is stored in that browser's local storage.

For iPhone home-screen installation and offline support, host the folder on an HTTPS static host such as GitHub Pages:
1. Create a repository and upload all files in this folder.
2. Enable GitHub Pages in the repository settings.
3. Open the published HTTPS URL in Safari on your iPhone.
4. Tap Share → Add to Home Screen.

## Important storage note
This starter version stores wishes locally in each browser/device. It does **not** automatically sync between devices. Use Export backup / Import backup to move data, or add a backend later for cloud sync. Export a backup before clearing site data or changing phones.
