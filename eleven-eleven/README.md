# 11:11 — A thread, a wish, a letter

A static, mobile-friendly tarot-and-letter experience. No build, account, or backend required.

## Publish with GitHub Pages

1. Create a GitHub repository and upload everything in this folder, keeping `assets/` intact.
2. Open repository **Settings → Pages**, choose **Deploy from a branch**, select your main branch and **/ (root)**, then save.
3. Visit the Pages URL GitHub provides once deployment finishes.

The included MP3 starts after the visitor clicks **Are you ready?** and loops. Sound can be paused with the header button. To replace it, use `assets/eleven-eleven.mp3`.

## Customize

- Edit `tanya` and `generic()` in `script.js` for the letters. The Tanya match ignores capitalization and surrounding spaces.
- Edit the signature in `index.html` to replace “me.” with your name.
- The date and time are part of the dedication, not a time lock. The site works at any hour.
- The three unique cards and their orientations are randomized. The topic changes the combined reflection; a custom question is displayed, not interpreted by AI.
- Names and questions stay in memory and are discarded on refresh. No analytics or submission server. Google Fonts is the only external design request; system fonts work offline.

## Important before sharing

This is a personal gift, but a static site is not private: both letters and the song can be read or downloaded by anyone who can access the hosted files. Entering a name is personalization, not a password. Use music you have permission to publish; the supplied recording is included at your request.

## Local preview

From this folder, run `python3 -m http.server 8000`, then open http://localhost:8000.
