[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/piTAsFCb)
# Front-End Challenge 2.0

## GitHub Classroom Workflow (Required)

This activity uses **GitHub Classroom**.

You are already viewing **your own Classroom repository** (created after you accepted the invite).

1. Clone this repository to your computer.
2. Make the required fixes locally.
3. Commit and **push your changes** back to this same repository.
4. Submit **your repository link** in the Canvas LMS assignment for this activity.

Your instructor will check your work by reviewing the files (and commit history, if applicable) in your Classroom repository.

## Objective

This is a **GitHub Classroom** activity. You will fix a broken mini-site, personalize it, apply Flexbox layouts, then deploy it on Netlify.

This activity tests:

- Correct HTML entry point (`index.html`)
- File naming conventions
- Folder organization
- Relative paths (`./` and `../`)
- Debugging broken CSS/image/link paths
- Personalizing a webpage while keeping structure clean
- Applying Flexbox in meaningful sections
- Atomic commits and clean Git workflow
- Deploying through Netlify + GitHub integration

---

## Required Workflow

1. Accept and open your GitHub Classroom repository.
2. Clone using **SSH** (not HTTPS).
3. Fix the project locally.
4. Commit changes in atomic batches.
5. Push to the `main` branch.
6. Connect your GitHub repo to Netlify (do not use drag-and-drop deploy).
7. Submit your **Netlify live URL** in Canvas.

SSH guide/tutorial:

- https://docs.google.com/document/d/1R_d8WqIQC4BN1vgmfVaUUna0FpH5hPsIBec3amjBmIk/edit?tab=t.fvowedjc7b0e

Atomic commits and Git commands guide:

- https://docs.google.com/presentation/d/e/2PACX-1vSbiR5Z2yHAHp76PPpM53JQFhGWMjZ-au2RSEa2cwBx30GwjFdPS8TKAUaX2ZAWNlB20RCsNwFr7U_f/pub?start=false&loop=false&delayms=3000&slide=id.g3a2f6edda82_0_70

---

## Core Tasks

1. **Refactor file/folder structure** into the target layout.
2. **Rename files** to clean, consistent names.
3. **Fix all relative paths** so CSS, images, and links work.
4. **Personalize the site** with your own content/theme.
5. **Use Flexbox properties** in at least 2 meaningful sections.

Example Flexbox sections:

- Navigation layout
- Card list or project section
- Footer links group
- Contact info row

Note: You may use your own images/assets. You are not required to use the provided pictures once you complete the file/path cleanup.

---

## Current (Intentionally Broken) Files

These files are intentionally messy and/or broken:

- `homepage.html` (this is NOT the correct entry point name)
- `about-us2.html` (bad naming)
- `pages/contactPage.html` (nested page)
- `styles/mainStyle.css` (CSS is in a non-standard folder)
- `assets/img/pexels-markusspiske-177598.jpg` (banner image not organized/renamed correctly)
- `assets/img/banner final FINAL.svg` (extra/incorrect banner asset)
- `assets/img/profile PIC.svg` (bad asset naming)

---

## Target Structure (Expected Final Layout)

Refactor the project to match this structure:

```
project/
├── index.html
├── about.html
├── pages/
│   └── contact.html
├── css/
│   └── styles.css
└── assets/
  └── img/
    ├── banner/
    │   └── hero-banner.jpg
    └── profile.svg
```

Notes:

- The only required nested page is Contact under `pages/`.
- The nested page must correctly use `../` where needed.

### Expected Renames / Moves (Guide)

- Rename `homepage.html` to `index.html`
- Rename `about-us2.html` to `about.html`
- Rename `pages/contactPage.html` to `pages/contact.html`
- Move `styles/mainStyle.css` to `css/styles.css`
- Create `assets/img/banner/`
- Move and rename `assets/img/pexels-markusspiske-177598.jpg` to `assets/img/banner/hero-banner.jpg`
- Rename `assets/img/profile PIC.svg` to `assets/img/profile.svg`

---

## Git Policy (Strict)

Do not commit all changes at once.

- Commit by file or logical group of related files.
- Use clear commit messages.
- Use atomic commits throughout your progress.

Example atomic commits:

```bash
git add index.html
git commit -m "feat(index.html): add personalized navbar and fixed links"

git add assets
git commit -m "feat(assets): add two profile images and rename banner file"
```

Penalty rule:

- Committing all at once results in **-50 points** from a total of 100.

---

## Netlify Deployment (Required)

You must host the final website on Netlify.

- Required method: **Connect Netlify to GitHub repository**
- Not allowed: **Drag & Drop deployment**

Minimum deployment expectations:

- Site builds from your Classroom repository
- Latest `main` branch changes are deployed
- Public live URL is accessible

---

## Done Checklist (Pass Conditions)

When opening `index.html` locally:

- [ ] CSS loads
- [ ] Images load
- [ ] Navigation links work

When opening `pages/contact.html` locally:

- [ ] CSS loads from `../css/styles.css`
- [ ] Links back to Home/About work

Project quality and requirements:

- [ ] Filenames and folders are clean and consistent
- [ ] Paths are correct from root and nested pages
- [ ] Site content is personalized
- [ ] At least 2 sections use Flexbox properties
- [ ] Commits are atomic and logically grouped
- [ ] Project is pushed to `main`
- [ ] Site is deployed to Netlify via GitHub connection

---

## Submission (Canvas)

Submit the following in Canvas:

1. Your **Netlify live URL**

Canvas activity link:

- https://xavierateneo.instructure.com/courses/2255/assignments/7570?module_item_id=77849

Do not submit the repository link as the final artifact for this activity.
