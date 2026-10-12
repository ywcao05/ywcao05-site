# Updating the site

The homepage text is in `content/_index.md`. Edit that file to change your bio.

- Writings: add a PDF to `static/files/`, then add its title, description, and file path to `data/writings.yaml`.
- Videos: add an MP4 to `static/videos/`, add its title and description to `data/videos.yaml`, and add a matching page in `content/videos/` pointing to the MP4.
- Teaching: edit `data/teaching.yaml`.
- Portrait: replace `static/images/portrait-warm-stone.png` with a photo of the same name.
- Look and spacing: edit `assets/css/style.css`.

After the site is published, updates to the `main` branch build and deploy through GitHub Actions.
