# Brijmohan SEO Portfolio

A professional and attractive SEO portfolio website built for **GitHub Pages**.

## Quick answer: how to make it live on GitHub

If you want the shortest possible steps, do this: 

1. Create or open the GitHub repository named **`Brijmohan.github.io`**.
2. Upload all project files to the **root** of that repository.
3. Go to **Settings → Pages** on GitHub.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your main branch and folder **`/ (root)`**, then click **Save**.
6. Wait 1–5 minutes.
7. Open **`https://brijmohan.github.io/`**.

---

## What is included

- Premium one-page portfolio design
- SEO-friendly metadata and Open Graph tags
- Schema markup for personal branding
- Services, case studies, process, and contact sections
- `robots.txt`, `sitemap.xml`, and `.nojekyll` for GitHub Pages support
- Responsive layout for mobile and desktop

## Files

- `index.html` — main portfolio page
- `styles.css` — visual styling and responsive design
- `script.js` — small JavaScript enhancement
- `robots.txt` — crawler instructions
- `sitemap.xml` — site URL list for search engines
- `.nojekyll` — tells GitHub Pages not to process the site with Jekyll

## Step-by-step guide for beginners

### 1. Customize your content
Open `index.html` and replace these placeholder items:

- `yourname@example.com`
- LinkedIn URL
- GitHub URL if needed
- Sample testimonials
- Sample case study metrics

### 2. Upload the website to GitHub

#### Option A: Upload directly on GitHub website
1. Open your repository: `Brijmohan.github.io`
2. Click **Add file**
3. Click **Upload files**
4. Drag and drop all project files
5. Scroll down and click **Commit changes**

#### Option B: Upload with Git commands
Run these commands inside the project folder:

```bash
git add .
git commit -m "Update SEO portfolio website"
git push origin main
```

If your branch is `master` instead of `main`, use:

```bash
git push origin master
```

### 3. Turn on GitHub Pages

1. Open your repository on GitHub
2. Click **Settings**
3. Click **Pages**
4. Under **Build and deployment**, set:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` or `master`
   - **Folder:** `/ (root)`
5. Click **Save**

### 4. Wait for publishing
GitHub Pages normally takes a few minutes to publish the site.

After publishing, your site should be live at:

```text
https://brijmohan.github.io/
```

### 5. If the website does not open
Check these common problems:

- The repository name is not exactly `Brijmohan.github.io`
- Files were uploaded inside another folder instead of the root
- GitHub Pages is not enabled in **Settings → Pages**
- You need to wait a few more minutes for deployment

### 6. Submit your website to Google Search Console
After the website is live:

1. Open Google Search Console
2. Add the property `https://brijmohan.github.io/`
3. Verify ownership
4. Submit this sitemap:

```text
https://brijmohan.github.io/sitemap.xml
```

## Recommended next improvements

- Add a real profile photo or custom banner image
- Add real client testimonials
- Add 2–3 detailed case studies with before/after metrics
- Connect a custom domain like `www.yourname.com`
- Add Google Analytics or Plausible analytics
- Add a Calendly booking link

## Local preview

Run a simple local server:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```
