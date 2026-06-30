# Ismael Bovingdon Castillejo — Portfolio Website

Personal portfolio site for a Junior Data Engineer, built as a static site ready to deploy on GitHub Pages. The site is fully bilingual (Spanish / English) and covers professional background, technical stack, projects, and contact information.

**Live site:** `https://i-bovingdon.github.io` *(once deployed)*

https://i-bovingdon.github.io/DataEngineer.com/index-en.html

[![image](https://github.com/user-attachments/assets/2420c432-315d-4e9c-a565-49e58f2fde12)](https://i-bovingdon.github.io/DataEngineer.com/index-en.html)

---

## Structure

```
/
├── index.html               # Spanish version (default)
├── index-en.html            # English version
├── styles.css               # Shared stylesheet
└── assets/
    ├── profile.png                        # Profile photo
    ├── CV_Ismael_Bovingdon_2026_ATS.pdf   # Spanish CV
    └── CV_en_Ismael_Bovingdon_2026_ATS.pdf # English CV
```

---

## Features

- **Bilingual** — Spanish (`index.html`) and English (`index-en.html`) with a language toggle in the nav bar.
- **Sections** — Hero, About, Technical Stack & Skills, Projects, Contact.
- **Project cards** — Enterprise-style cards with tech stack tags, impact bullet points, and action buttons (architecture, GitHub, dashboard).
- **Contact grid** — Phone, email, LinkedIn, GitHub, location, and CV download.
- **Fully static** — No build tools, no frameworks, no dependencies. Pure HTML + CSS + vanilla JS.
- **GitHub Pages ready** — Deploy directly from the repository root.

---

## Deployment (GitHub Pages)

1. Push the repository to GitHub.
2. Go to **Settings → Pages**.
3. Set source to **Deploy from a branch**, select `main` and `/ (root)`.
4. The site will be live at `https://<your-username>.github.io/<repo-name>`.

> The default page served will be `index.html` (Spanish). The English version is accessible via the EN toggle in the nav or by navigating directly to `index-en.html`.

---

## Customisation

| What | Where |
|---|---|
| Profile photo | Replace `assets/profile.png` |
| CV files | Replace the two PDFs in `assets/` keeping the same filenames |
| Colors / fonts | Edit CSS variables at the top of `styles.css` |
| Project cards | Edit the `<article class="project-card-enterprise">` blocks in both HTML files |
| Contact details | Edit the `#contact` section in both HTML files |

---

## Tech

- HTML5 / CSS3 / Vanilla JS
- No build step — open `index.html` in a browser to preview locally

---

## Author

**Ismael Bovingdon Castillejo** — Junior Data Engineer  
[LinkedIn](https://www.linkedin.com/in/ismael-bovingdon-castillejo-6a775074/) · [GitHub](https://github.com/I-Bovingdon) · ishmaelbovingdon@gmail.com
