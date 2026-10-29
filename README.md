# Lock In — your browser habit tracker

**This is the website version. You do not need Expo, Node.js, a terminal, or a phone app.**

## Use it immediately

Double-click **index.html**. It opens in your laptop’s browser. Bookmark it and use it every day.

Your check-ins and theme save in that browser. If the browser blocks saving a local file, the tracker shows a warning; use GitHub Pages below for a stable website address. Use **Personalize → Export backup** regularly.

## Put it on GitHub Pages

1. Sign in to [GitHub](https://github.com/new) and create a **public** repository named **habit-tracker**. Select **Add a README file** when creating it.
2. In the repository, choose **Add file → Upload files**. Upload **index.html** from this folder directly to the repository, then choose **Commit changes**. Upload the file itself, not this ZIP or its surrounding folder. You only need this one HTML file.
3. Open **Settings → Pages**. Under **Source**, select **Deploy from a branch**. Choose **main** and **/(root)**, then click **Save**.
4. Wait for GitHub’s deployment to finish. The same Pages screen will show **Visit site**. Open that link and bookmark it. Its usual format is `https://YOUR-USERNAME.github.io/habit-tracker/`.

From then on, use the website link. You do not need to keep GitHub open or keep your laptop running a server.

GitHub Pages settings are documented in the [official publishing guide](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site). GitHub Free supports Pages from public repositories. The website and its default source are public; your saved check-ins stay in your own browser and are not uploaded to the repository.

## Move progress from a local file to your website

1. In the local tracker, select **Personalize → Export backup**.
2. Open your GitHub Pages website.
3. Select **Personalize → Restore backup**, choose the exported JSON file, and confirm.

Different browsers, devices, and website addresses have separate saved data. There is no automatic cloud sync. Clearing browser storage removes its saved progress. Keep backup files outside the public GitHub repository.

## What’s included

- Your seven original good/bad habits and editable emojis.
- Daily completion or explicit avoidance, missed/occurred states, and undo.
- Date selection, past-day corrections, and calendar week navigation.
- Daily/weekly percentages, current streaks, weekly bars, and a monthly consistency line.
- A spreadsheet-style monthly grid with interactive cells.
- Create, edit, and archive habits without erasing history.
- Dark mode and four accent colors.
- Encouragement after a successful check-in.
- Local saving, backup export/import, and responsive laptop/mobile layouts.

The original workbook’s historical checkboxes are not imported. Seed habits start on your first use date. A bad habit earns credit only when explicitly marked Avoided; an unlogged cell does not imply avoidance. Weekly blocks follow the workbook’s 1–7, 8–14, etc. layout. Archiving takes effect tomorrow; previous dates retain their original habit denominator.

The app uses the date/scoring rules from the earlier mobile starter, adapted to a self-contained website. All styles, scripts, icons, and SVG charts are inside `index.html`. There are no external dependencies, remote fonts, sign-ins, analytics, or server requests from the app.

## Updating later

Replace `index.html` in the same GitHub repository to deploy an update. Keep the same website address to retain that browser’s stored progress. Export a backup before updating. GitHub hosts the app code; it does not store or synchronize your personal habit data.
