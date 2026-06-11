# Personal CV homepage placeholder

This repository is intended for the GitHub Pages user site:

```text
https://machenyu2023.github.io/
```

The existing blog can remain at:

```text
https://machenyu2023.github.io/blog/
```

## Local preview

Open `index.html` in a browser, or start a simple local server:

```powershell
cd D:\machenyu2023.github.io
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000/
```

## First-time GitHub deployment

Create a public GitHub repository named exactly:

```text
machenyu2023.github.io
```

Then run:

```powershell
cd D:\machenyu2023.github.io
git init
git add .
git commit -m "Create personal CV homepage"
git branch -M main
git remote add origin https://github.com/machenyu2023/machenyu2023.github.io.git
git push -u origin main
```

GitHub Pages will publish this repository at the root domain automatically. If it does not,
open the repository settings, go to Pages, and choose `Deploy from a branch`, branch `main`,
folder `/ (root)`.

## Content to replace

- Replace `your.email@example.com` with your real email.
- Replace the `About`, `Education`, `Experience`, `Publications`, and `Awards` placeholder text.
- Replace the portrait source if you want to use a formal headshot instead of the GitHub avatar.
