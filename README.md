# Zehua Wu — Academic Personal Website

This is a lightweight **HTML + CSS** academic CV website adapted from [Jon Barron’s personal website](https://jonbarron.info/) and his [source repository](https://github.com/jonbarron/jonbarron.github.io).

## Publish using GitHub Pages

1. Create a **public** repository named `cv` under your GitHub account (`zehua-wu`).
2. Upload **all files and folders** in this directory to the **root** of the repository (do not upload the ZIP itself).
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**.
4. Set **Branch = main**, **Folder = /(root)**, and **Save**.
5. When the deployment completes, visit **https://zehua-wu.github.io/cv/**. GitHub will also provide a **Visit site** link in the Pages settings.

Alternatively, name the public repository `zehua-wu.github.io` to use **https://zehua-wu.github.io/** as the site address.

## Editing

- `index.html`: content, links, experience, projects, publications and education.
- `stylesheet.css`: typography, width and responsive layout (matches Jon Barron's minimal style).
- `images/`: the three *illustrative* project thumbnails, favicon, and a neutral profile picture fallback.
- `data/Zehua_Wu_CV.pdf`: your supplied PDF resume, linked from the top of the page.
- The circular portrait uses your **GitHub avatar** automatically (`avatars.githubusercontent.com`); to show a personal headshot instead, put `images/profile.jpg` in the repo and replace the `<img src=...>` in `index.html` with `src="images/profile.jpg"`.

## Privacy note

The included PDF is your **original upload**, and it includes a phone number. If you don't want that information publicly accessible, replace the PDF with a redacted version **before publishing**. Publishing to GitHub Pages makes the site files accessible to anyone with the URL.

## Acknowledgement

Page styling is adapted from [Jon Barron's academic site](https://github.com/jonbarron/jonbarron.github.io), whose README explicitly allows cloning for personal use.
