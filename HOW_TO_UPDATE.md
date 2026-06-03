# 🚀 How to Update & Deploy Your Portfolio

## ✅ Step 1: Enable GitHub Pages (One-Time Setup)

1. Go to: https://github.com/sheriff786/My_Portfolio_Website/settings/pages
2. Under **"Source"**, select **"Deploy from a branch"**
3. Under **"Branch"**, select **"main"** and folder **"/ (root)"**
4. Click **"Save"**
5. Wait 1-2 minutes — your site will be live at:
   **https://sheriff786.github.io/My_Portfolio_Website/**

---

## 📝 How to Update Your Website

Every time you want to make changes:

### 1. Edit the `index.html` file
Open `index.html` in VS Code and make changes to the sections below.

### 2. Save and push to GitHub
```bash
cd "D:\full_end_to_end_project_implementation\Reserach _faang_projects\Faang_level_my_portfolio_website\My_Portfolio_Website"
git add -A
git commit -m "Update portfolio"
git push origin main
```

Your website will auto-update within 1-2 minutes!

---

## 🔧 What to Update and Where

### Update Your About Section
Search for `<!-- ABOUT -->` in index.html. Edit the `<p>` tags inside `.about-text`.

### Add/Update Projects
Search for `<!-- PROJECTS -->` in index.html. Copy an existing `proj-card` div and modify:
```html
<div class="proj-card">
  <div class="proj-top">
    <i class="ti ti-brain proj-folder"></i>
    <div class="proj-links">
      <a href="YOUR_GITHUB_LINK" title="GitHub"><i class="ti ti-brand-github"></i></a>
      <a href="YOUR_LIVE_DEMO_LINK" title="Live Demo"><i class="ti ti-external-link"></i></a>
    </div>
  </div>
  <div>
    <div class="proj-featured">Featured Project</div>
    <div class="proj-name">PROJECT NAME</div>
  </div>
  <p class="proj-desc">PROJECT DESCRIPTION</p>
  <div class="proj-tags">
    <span class="tag">Tag1</span><span class="tag">Tag2</span><span class="tag">Tag3</span>
  </div>
</div>
```

### Add Certifications
Search for `<!-- CERTIFICATIONS -->`. Copy a `cert-card` and modify:
```html
<div class="cert-card">
  <div class="cert-issuer">ISSUER (e.g., AWS, Google)</div>
  <div class="cert-name">Certification Name</div>
  <div class="cert-year">Year</div>
</div>
```

### Update Experience
Search for `<!-- EXPERIENCE -->`. Edit the `exp-panel` sections with your roles and bullet points.

### Update Tech Stack
Search for `skills-box`. Edit the `skill-item` entries with your technologies.

### Update Profile Picture
Replace the `profile.jpg` file in the project folder with your new photo (keep the same filename).

### Add Resume
Drop your `resume.pdf` file into the project folder and it'll be linked automatically.

---

## 🎨 Icons Available
The template uses Tabler Icons. Browse all icons at: https://tabler.io/icons
Use them as: `<i class="ti ti-ICON-NAME"></i>`

Common icons for projects:
- `ti-brain` — AI/ML
- `ti-robot` — Automation
- `ti-chart-line` — Analytics
- `ti-database` — Data
- `ti-cloud` — Cloud
- `ti-code` — Coding
- `ti-server` — Backend

---

## 🌐 Custom Domain (Optional & Free)
If you buy a domain (e.g., sheriffmehmood.com):
1. Go to GitHub repo → Settings → Pages
2. Add your custom domain
3. Update your DNS to point to GitHub Pages

---

## 💡 Tips
- Always test locally first by opening `index.html` in your browser
- Use `git diff` to see what changed before committing
- Keep project descriptions concise (2-3 sentences max)
- Update your stats in the hero section as you grow
