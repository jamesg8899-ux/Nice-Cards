# Paramedic NICE Cards

NICE guidance and LAS tools for paramedics, by complaint. Works on iPhone as a Home Screen app, including offline.

## Put it on GitHub Pages (about 10 minutes, all from your phone or a computer)

1. **Make a GitHub account** at github.com if you don't have one.
2. **Create a repository:** tap **+** then **New repository**. Name it `nice-cards`. Choose **Private** if you have GitHub Pro, otherwise **Public** (see the note below). Tick **Add a README file**, then **Create repository**.
3. **Upload the files:** on the repository page tap **Add file** then **Upload files**. Upload everything from this folder, keeping the `icons` folder: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` and the `icons` folder with its 4 images. Tap **Commit changes**.
   - On iPhone, unzip the download in the Files app first, then upload. If the upload page won't take a folder, create it by naming a file `icons/icon-192.png` when you upload each icon, or do this step on a computer.
4. **Turn on Pages:** **Settings** then **Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**, Branch **main**, folder **/ (root)**, then **Save**.
5. Wait 1 to 2 minutes. Your app is at `https://YOUR-USERNAME.github.io/nice-cards/`.

## Add it to your iPhone

1. Open that link in **Safari** (it must be Safari).
2. Tap **Share**, then **Add to Home Screen**, then **Add**.
3. Open it once with signal so it saves itself for offline use.

## Updating it later

1. Upload the new `index.html` over the old one.
2. Open `sw.js`, change `nice-cards-v1` to `nice-cards-v2` (then v3 and so on), and commit. This tells phones to pick up the new version.
3. Close and reopen the app on your phone. It may take two opens to update.

## Important before sharing

- **Public repositories are visible to anyone.** The LAS tools (Pathfinder, Major Trauma Tool, maternity tools) belong to London Ambulance Service. Keep it to yourself unless LAS has agreed it can be shared.
- Software that gives clinical decision outputs can count as a medical device under MHRA rules once it's distributed to others. Talk to LAS before rolling it out to colleagues.
- This app summarises NICE guidance. JRCALC and LAS guidance take precedence, and drug doses are not included.
