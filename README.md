# Brijmohan Cinematic SEO Portfolio

A 3D-inspired, fully responsive SEO portfolio for **GitHub Pages** with cinematic visuals, project highlights, and two contact-ready forms.

## What was upgraded

- Attractive 3D / cinematic look with glowing gradients, glass cards, layered depth, and motion.
- Fully responsive design for desktop, tablet, and mobile.
- Detailed services and featured project sections for **Inditirth.com** and **Collegevidya.com**.
- Lead form and contact form ready to receive messages using **FormSubmit**.
- Easy-to-edit structure using plain `HTML`, `CSS`, and `JavaScript`.

## Files you will edit later

- `index.html` → change your text, links, projects, and form email.
- `styles.css` → change colors, spacing, design, and responsive styles.
- `script.js` → controls reveal animations, tilt effects, and footer year.
- `robots.txt` and `sitemap.xml` → search engine support files.

## Very important before going live

The two forms currently send to this placeholder email:

```text
yourname@example.com
```

Replace that placeholder in `index.html` with your real email address everywhere it appears. The forms use:

```text
https://formsubmit.co/yourname@example.com
```

After you replace it with your real email, FormSubmit will email you the submitted messages.

## How to update this site

### Update your name or hero section
Open `index.html` and edit the hero heading, paragraph, stats, and quick contact links.

### Update project details
Search for:

- `Inditirth.com`
- `Collegevidya.com`

Then edit the project descriptions, work details, and results.

### Update services
Edit the cards inside the `#services` section.

### Update the contact details
Search for:

- `yourname@example.com`
- `https://www.linkedin.com/`
- `https://github.com/Brijmohan`

Replace them with your real details.

## How to make it live on GitHub Pages

1. Open or create the repository named **`Brijmohan.github.io`**.
2. Upload all files to the **root** of the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Click **Save**.
6. Wait a few minutes.
7. Open **`https://brijmohan.github.io/`**.

## How to push updates after editing

```bash
git add .
git commit -m "Update portfolio website"
git push origin main
```

## Local preview

Run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://127.0.0.1:8000/
```
