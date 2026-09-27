# PUMPKINS.food — Landing Page

A single-page website for PUMPKINS.food (Bantama, Kumasi). All four photos are embedded directly inside `index.html` as inline images, so this is a single file with **no separate assets folder needed** — nothing can go missing when you upload it.

## Updating your live GitHub Pages site

You already have a repo deployed at `thecreator-06-lbl.github.io/pump/`. To update it with this fixed version:

1. Go to your `pump` repository on GitHub.
2. Open `index.html` and click the pencil (Edit) icon — or delete the file and use **Add file → Upload files** to upload this one instead.
3. Replace all the content with this file's content (or just drag-and-drop this file in if uploading fresh).
4. Commit the change.
5. Wait about a minute — GitHub Pages will redeploy automatically at the same link.

## Starting fresh (new repo)

1. Create a GitHub account at https://github.com if you don't have one.
2. Create a new **public** repository.
3. Upload `index.html` (this one file is all you need).
4. Go to **Settings → Pages** → Source: **Deploy from a branch** → Branch **main**, folder **/ (root)** → Save.
5. Your live link appears at the top of that page within a minute.

## Editing the site yourself
All text, colors, and copy live inside `index.html`. Colors are defined once at the top under `:root` (search for `--rust`, `--brass`, `--paper`) so you can restyle the whole site by changing a few lines. The four photos are embedded as long `data:image/jpeg;base64,...` strings inside the `<img>` tags and the hero's CSS `background-image` — you don't need to touch those unless you're swapping in new photos.
