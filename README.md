# Afrin Ameer Khan — QA Portfolio

A clean, single-page portfolio site for QA Engineer / SDET roles.

**Live URL (after deployment):** `https://afrinlearning111.github.io/Afrin_Portfolio/`

---

## 🚀 Deploy to GitHub Pages — 3 Steps

### Step 1 — Upload files to your repo

1. Go to your repo: **https://github.com/afrinlearning111/Afrin_Portfolio**
2. Click **Add file → Upload files**
3. Drag and drop these two files:
   - `index.html`
   - `styles.css`
4. Scroll down, click **Commit changes**

> 💡 *Alternative if you use Git locally:*
> ```bash
> git clone https://github.com/afrinlearning111/Afrin_Portfolio.git
> cd Afrin_Portfolio
> # copy index.html and styles.css into this folder
> git add .
> git commit -m "Add portfolio site"
> git push origin main
> ```

### Step 2 — Enable GitHub Pages

1. In your repo, click **Settings** (top tab)
2. In the left sidebar, click **Pages**
3. Under **Source**, select:
   - Branch: `main` (or `master` if that's what you have)
   - Folder: `/ (root)`
4. Click **Save**
5. Wait 1–2 minutes. Refresh the page — you'll see a green box with your live URL.

### Step 3 — Visit your site

Open: **https://afrinlearning111.github.io/Afrin_Portfolio/**

That's the URL you put on your resume, LinkedIn, and job applications. ✅

---

## ✏️ How to Edit Content Later

All your content lives in `index.html`. You don't need to know coding — just find the text and replace it.

### Update GitHub project repos

In `index.html`, search for `project-repo` (there are 2 placeholder cards near the bottom of the Projects section). For each card, replace:

- `<h3>Selenium Java Automation Framework</h3>` → your actual repo name
- `<p>...</p>` → your actual description
- `<span>Java</span><span>Selenium</span>...` → your actual tech stack
- `href="https://github.com/afrinlearning111"` → the **direct link to that specific repo**

### Add a new certification

In `index.html`, find the `cert-list` section and copy any `<li>...</li>` block. Update the name and date.

### Update tagline / about / anything else

All content is plain text inside HTML tags. Just find and replace.

After editing, commit the changes — GitHub Pages auto-rebuilds in ~1 minute.

---

## 📄 Optional: Add a Resume Download

1. Add your resume PDF to the repo (e.g., `Afrin_AmeerKhan_QA_Engineer.pdf`)
2. In `index.html`, find the hero section and add a download button. Example, just below the existing buttons:
   ```html
   <a href="Afrin_AmeerKhan_QA_Engineer.pdf" download class="btn btn-secondary">Download Resume</a>
   ```

---

## 🎨 Sections Included

1. **Hero** — name, tagline, key stats, summary card
2. **About** — your story + currently/based-in/languages aside
3. **Skills** — 6 categorized cards (Manual, Automation, API, CI/CD, Languages, Process)
4. **Experience** — timeline of UST + WhiteRabbit roles with achievements
5. **Projects** — 4 case studies (anonymized client work) + 2 GitHub repo cards
6. **Certifications & Education** — side-by-side
7. **Contact** — email, phone, LinkedIn, GitHub cards

Fully responsive. Works on mobile. No frameworks, no build step — just HTML + CSS.

---

## 🔧 Tech

- Pure HTML/CSS/JS (no frameworks)
- Google Fonts: Fraunces (serif), Inter (sans), JetBrains Mono (code)
- Smooth scroll, mobile menu, scroll-triggered fade-in animations
- Optimized for desktop and mobile

---

Built with care. Tested manually. Deployed in 3 steps. 🚀
