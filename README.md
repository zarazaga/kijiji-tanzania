# Tanzania | Sustainable Rural Development in Kasisa

This folder is a complete static site prepared for GitHub Pages.

## Files
- `index.html` — page content
- `styles.css` — layout and responsive styling
- `images/2024/` — optimized 2024 project photographs
- `README.md` — setup notes

## Put it on GitHub Pages
1. Create a new GitHub repository, for example `tanzania-kijiji`.
2. Upload everything in this folder to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will show the public URL after deployment.

If you already have a GitHub Pages site, you can instead put this folder inside that repository and link to its `index.html` path.

## Add 2025 and 2026 later
The page already contains the 2025 and 2026 text sections. When photographs are selected, add new folders such as:

- `images/2025/`
- `images/2026/`

Then add image gallery blocks to the corresponding sections in `index.html`.

## Connect it to SMUSDP.com (Squarespace)
The simplest and most reliable method is to add an external link or button on the Squarespace site pointing to the GitHub Pages URL.

You can also add the GitHub Pages URL as an item in Squarespace navigation.

Embedding the full page inside Squarespace with an iframe is possible on Squarespace plans that allow iframe code in Code Blocks. A typical embed looks like:

```html
<iframe
  src="YOUR-GITHUB-PAGES-URL"
  title="Tanzania sustainable rural development project"
  style="width:100%; height:900px; border:0;"
  loading="lazy">
</iframe>
```

For this project, linking is recommended over embedding because the Tanzania site is a long, responsive page and will work better on phones and tablets as its own page.

## 2023 StoryMap
The 2023 StoryMap is linked from the page rather than recreated:
https://arcg.is/nmeba
