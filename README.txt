Neither Employee Nor Free (digital exhibit)

Files
  index.html              the whole site (all pages are inside this one file)
  assets/posters/*.jpg    the five gallery photographs
  assets/history/sewa.jpg the SEWA photo on the History page
  assets/tex/*.webp       stain, sweat, damp and grime textures
  vercel.json             optional, harmless

Deploy
  1. Put these files at the ROOT of your GitHub repo (replace the old index.html, keep the assets folder structure).
  2. Commit and push to the branch Vercel watches (usually main).
  3. Vercel redeploys on its own. The domain gig-eco.vercel.app does not change.

Edit later
  Posters: edit the POSTERS list near the bottom of index.html.
  Videos:  edit the VIDEOS list. EMBED = true plays inside the page, false links out.
  History: edit the ERAS list.
