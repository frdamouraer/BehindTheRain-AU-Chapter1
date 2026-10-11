# BEHIND THE RAIN AU — Chapter 1 (v2)

A standalone HTML/CSS/JavaScript site for the Emon × Ruby Twitter AU. This project is intended for a **new, separate repository**.

## Preview
Extract the ZIP and open `index.html` in a modern browser. Internet access is used for Google Fonts. A local server (such as VS Code Live Server) is recommended for audio testing.

## Publish to a new GitHub repository
1. Create a new empty repository for the AU. **Do not use the original `BehindTheRain-Frd` repository.**
2. Extract the ZIP and upload its contents to the root of the new repository. `index.html`, `style.css`, and `script.js` should be at the root.
3. Go to **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/(root)`, then Save.
5. Wait for GitHub Pages to publish.

## Add five music files
Put your files in `assets/music/` with these exact filenames:
- `song-01.mp3`
- `song-02.mp3`
- `song-03.mp3`
- `song-04.mp3`
- `song-05.mp3`

Then open `script.js` and edit the `MUSIC` array near the bottom: update `title` and `artist` for each track. Keep the `src` paths unless you rename the files. No audio files are included in the ZIP.

The music starts stopped. The reader must press Play. Once started, the playlist continues between scenes, and after song 5 it loops back to song 1. Minimizing the player does not stop playback. The player auto-minimizes after 10 seconds without interaction, or immediately when the reader presses the minus button at the bottom-right of the expanded panel.

## Story and privacy notes
- Ruby is a pseudonym; do not replace it with the real person's name.
- Some dialogue and social posts are creative reconstructions, not exact transcripts of real messages.
- The story preserves the established Chapter 1 cliffhanger. The present-day group mystery is left unexplained for Chapter 2.
- The ending currently shows “Chapter 2 Coming Soon” without an active external link.
- The story resets to the beginning on each fresh page load. No resume state is stored.

## Current content status
This is a more complete visual and story draft, but please review the reconstructed dialogue and all wording before public release. The social handles and friends' comments are fictional AU elements.
