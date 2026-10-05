<p align="center">
  <img src="https://raw.githubusercontent.com/abdoulrl2028-cloud-Dev/abdoulrl2028-cloud-Dev/main/assets/projects/portfolio.jpg" alt="Portfolio landing page" width="100%">
</p>

# Landing page and Vercel deploy

A simple static site (HTML and CSS) ready for automatic deploys with GitHub and Vercel.

Includes:

- a hero image at `assets/images/hero-image.svg`
- a favicon at `assets/images/favicon.svg`

## Structure

```txt
landing-page/
├── index.html
├── css/style.css
├── assets/images/
└── README.md
```

## 1) Push to GitHub

From the `landing-page` folder:

```bash
git init
git add .
git commit -m "feat: initial landing page"
git branch -M main
git remote add origin https://github.com/abdoulrl2028-cloud-Dev/Developer-Portfolio-Landing-Page.git
git push -u origin main
```

## 2) Connect Vercel

1. Open [https://vercel.com](https://vercel.com) and sign in.
2. Choose **Add New → Project**.
3. Select this repository.
4. Framework preset: **Other** (or leave it on auto).
5. Leave the build command and output directory empty.
6. Click **Deploy**.

## 3) Automatic deploys

After the project is imported, every push to the main branch creates a new deployment. Pull requests can create preview deployments.

## 4) Free domain

Vercel provides a free domain:

```txt
your-project.vercel.app
```

Confirm or edit it under **Settings → Domains**.
