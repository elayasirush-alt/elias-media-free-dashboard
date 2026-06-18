# Elias Media Cloudflare Canva + No Repeat Version

Changes:
- Removed Openverse, NASA, Wikimedia, Internet Archive, Flickr, and GIPHY.
- Added Canva, Coverr, Mixkit, Videvo, Freepik, StockSnap, Burst, Pikwizard, and Life of Pix.
- Direct preview/download works best with Pexels, Pixabay, and Unsplash.
- Other sources open their search pages so you can preview/download from the original site.
- Clips are filtered so the same URL is not repeated across timestamps in one suggestion run.
- The UI also hides repeated links during the same run.
- Two media search terms and two Canva terms are shown for every timestamp.
- Logo, media preview, background music, SFX, and report export remain.

Upload to GitHub:
- public/
- functions/
- README.md

Cloudflare Pages settings:
- Build command: blank
- Build output directory: public

- Added Pinterest as a reference / inspiration source link.

- Strict no-repeat mode: if media was already used in one suggestion run, it will be skipped instead of repeated.
- If a source runs out of unique results, the tool will show fewer results rather than duplicates.
