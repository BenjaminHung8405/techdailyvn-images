# techdailyvn-images

Public host for the daily **techdailyvn** TikTok carousel images.

- Served via GitHub Pages so the TikTok Content Posting API can fetch them
  with `PULL_FROM_URL` (photos must be public HTTPS URLs on a verified prefix).
- Each day gets a folder named `YYYY-MM-DD/`:
  - `01.jpg` — cover (data-center background + date)
  - `02.jpg` … `NN.jpg` — news slides
- Format: JPEG, 1080×1920, quality 85, each well under TikTok's 20 MB limit.

Example URL: `https://benjaminhung8405.github.io/techdailyvn-images/2026-11-14/01.jpg`
