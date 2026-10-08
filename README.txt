Neither Employee Nor Free (digital exhibit)

Files
  index.html              the whole site (all pages are inside this one file)
  assets/posters/poster-1..5.jpg   the five gallery photographs
  assets/posters/poster-hero*.jpg  the large poster at the top of the Gallery (web size, 4K and 8K downloads)
  assets/history/sewa.jpg the SEWA photo on the History page
  assets/tex/*.webp       stain, sweat, damp and grime textures
  vercel.json             optional, harmless

Deploy
  1. Put these files at the ROOT of your GitHub repo (replace the old index.html, keep the assets folder structure).
  2. Commit and push to the branch Vercel watches (usually main).
  3. Vercel redeploys on its own. The domain gig-eco.vercel.app does not change.

Edit later
  Big poster: replace the three poster-hero files, keeping the names.
  Posters: edit the POSTERS list near the bottom of index.html.
  Videos:  edit the VIDEOS list. EMBED = true plays inside the page, false links out.
  History: edit the ERAS list.

Gallery note: the Melbourne exhibition PDF is shown through the University of Melbourne repository's (figshare) own embed widget on the live site, with Download and Open buttons beside it. The PDF is under a restrictive licence, so it is deliberately not copied into this folder.

Favicon: favicon.ico sits at the site root; the SVG and PNG versions are in assets/icons/. Keep both when uploading.
