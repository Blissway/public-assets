 # Public Assets

  Static assets served at `public.blissway.com` via GitHub Pages, embedded by direct
  URL in email signatures and other external references.

  ## 🚨 Do not rename or move files
  
  Every file here is linked by its exact path from outside this repo (email signatures,
  etc.), with no build step or redirect layer in between. Renaming, moving, or
  deleting a file silently breaks every place that references it — there's no way to
  search those references from here to know what you'd be breaking.

  **If a file needs to change:** add a new file under a new name and update references
  to point at it. Only remove the old one once you've confirmed nothing external still
  points to it.

  ## Current assets
  
  **Icons** — `icons/`
  - [`web.png`](https://public.blissway.com/icons/web.png)
  - [`email.png`](https://public.blissway.com/icons/email.png)
  - [`phone.png`](https://public.blissway.com/icons/phone.png)

  **Logos** — `logos/`
  - [`blissway-color.png`](https://public.blissway.com/logos/blissway-color.png)
  - [`linkedin.png`](https://public.blissway.com/logos/linkedin.png)

  ## Adding a new asset

  Drop the file in the appropriate folder (or a new one) and commit to `main` — GitHub
  Pages publishes on push. No build step.
