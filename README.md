# OnePlace Campus Hub

A responsive campus hub with seeded campus data, device-local profile sign-up/sign-in, opportunity application tracking, and browser-local persistence.

## Deploy with GitHub Pages

The `Publish OnePlace Campus Hub` workflow publishes the `outputs/` directory to GitHub Pages whenever a commit is pushed to `main`. After adding this repository to GitHub, enable GitHub Actions as the Pages deployment source under **Settings → Pages**. You can also run the workflow manually from the Actions tab.

Open `outputs/index.html` in a browser to preview the app locally. The app loads React and Babel from public CDNs, so those libraries require an internet connection. Profiles, sign-in data, applications, and campus activity are stored in that browser's `localStorage`; they do not sync between devices. The local sign-in is a demo flow, not a production identity service.

