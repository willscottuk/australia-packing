# Australia Packing Companion

An installable, offline-capable packing checklist for Australia.

## Publish to GitHub Pages

1. Create a public repository named `australia-packing`.
2. Upload all files and the `icons/` folder from this directory **into the repository root** (not a nested folder).
3. Under **Settings → Pages**, set Source **Deploy from a branch**, Branch `main`, Folder `/ (root)`; save.
4. Visit `https://<USERNAME>.github.io/australia-packing/` after GitHub Pages deploys.
5. In iOS Safari use **Share → Add to Home Screen**.

## Offline use

Open the published app online at least once before going offline. The service worker caches app resources. Packing state and custom items are stored in this browser's localStorage. They **do not sync between devices**. Use JSON export/import to transfer or back up progress. Browser clearing or changing domains can erase local progress.

## Notes

The app contains travel reminders and packing guidance, not personal passport or prescription details. The repository and published Pages site may be public.
