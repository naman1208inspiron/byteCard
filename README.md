# ByteCards PWA — Deploy on GitHub Pages

1. Create a new GitHub repository and upload all files in this folder (`index.html`, `cards.json`, `manifest.json`, `sw.js`, `icon.svg`).
2. Go to **Settings -> Pages**, set Source to **Deploy from a branch** (`main` / `/root`), and save.
3. Open your live `https://<username>.github.io/<repo>/` URL on your phone and tap **Add to Home Screen**.
4. **Adding new content:** Paste new card/quiz objects into `cards.json` and commit—every user's phone syncs automatically.
5. **Live Google Sign-In (Optional):** Create a free Firebase project, enable **Authentication -> Google**, and paste your `apiKey`, `authDomain`, and `projectId` into `FIREBASE_CONFIG` inside `index.html`.
