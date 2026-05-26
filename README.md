# MRLR Speaker Recruitment Website

Static landing page for preliminary invited-speaker conversations for the
proposed MRLR 2027 workshop.

## Preview Locally

From this directory:

```bash
python3 -m http.server 4173
```

Then open `http://localhost:4173/`.

## Publishing Notes

- The page currently includes `noindex, nofollow` metadata because the
  workshop has not yet been submitted and speaker conversations are
  preliminary.
- Before making the site public, confirm the target venue, update organizer
  information, remove the `noindex` tag when appropriate, and add only
  speakers who have consented to being listed.
- Organizer cards currently contain portrait placeholders. Replace each
  `.portrait-placeholder` block in `index.html` with an `<img>` element once
  approved portrait images are available.
- The invited-speakers table contains public-facing participation status.
  Add or revise entries only when the relevant invitation status can be shown.
- The site is plain HTML and CSS and can be deployed directly through GitHub
  Pages, Netlify, or any static hosting service.
