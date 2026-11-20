# PoliSci U at Illinois — Course Offerings Page

A one-page website listing graduate political methodology courses offered through the PoliSci U iTV consortium (Illinois, Minnesota, Ohio State, Wisconsin–Madison).

## Publish on GitHub Pages

1. Create a new public repository on GitHub (e.g. `polisciu-illinois`).
2. Upload `index.html` (and this README) to the repository: **Add file → Upload files → Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/polisciu-illinois/`.

## Updating each semester

Everything is in `index.html`. Each course is one `<article class="card">` block:

- Change the institution, title, instructor, description and dates.
- Set `data-status` to `confirmed`, `planned` or `potential`, and use the matching badge class (`b-confirmed`, `b-planned`, `b-potential`).
- Update the "Last updated" date near the top of the courses section.

Text in yellow (`class="placeholder"`) still needs to be filled in.

## Acknowledgement

Background on PoliSci U is adapted from the Ohio State University Department of Political Science page:
https://polisci.osu.edu/graduate/current-students/PoliSciU-advanced-methodology
