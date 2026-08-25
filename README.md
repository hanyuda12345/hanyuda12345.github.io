# Hanyu Da Portfolio Website

This repository contains a GitHub Pages/Jekyll personal portfolio website for Hanyu Da, adapted from the `luost26/academic-homepage` template and reshaped for a Machine Learning Engineer, AI Engineer, and Software Development Engineer profile.

## What Is Included

- Clean academic-style homepage
- About, Education, Experience, Selected Projects, Skills, Resume, and Contact sections
- Downloadable resume PDF at `assets/files/Hanyu_Da_Resume_2026.pdf`
- GitHub Actions workflow for GitHub Pages deployment
- Template attribution retained in the footer

## Local Preview

```bash
bundle install
bundle exec jekyll serve
```

Then open the local URL printed by Jekyll.

## Deploy To GitHub Pages

1. Create a new GitHub repository named `<your-github-username>.github.io`.
2. Upload or push every file from this repository to the `main` branch.
3. In GitHub, open `Settings` -> `Pages`.
4. Under `Build and deployment`, set `Source` to `GitHub Actions`.
5. Push a commit or run the `Deploy Jekyll site to GitHub Pages` workflow manually.
6. Your site will publish at `https://<your-github-username>.github.io/`.

## Update Links

- LinkedIn is set in `_data/profile.yml`.
- Email is set in `_data/profile.yml`.
- If you want to show a GitHub icon, add your GitHub username in `_data/profile.yml`:

```yaml
github: your_github_id
```

## Update Resume

Replace `assets/files/Hanyu_Da_Resume_2026.pdf` with a newer PDF using the same filename. The Resume buttons and embedded resume page will update automatically.
