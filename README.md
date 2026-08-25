# Hanyu Da Portfolio Website

This repository contains a GitHub Pages/Jekyll personal portfolio website for Hanyu Da, adapted from the `luost26/academic-homepage` template and reshaped for a Machine Learning Engineer, AI Engineer, and Software Development Engineer profile.

Live site: https://hanyuda12345.github.io/

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

## GitHub Pages Deployment

The site is published from `hanyuda12345/hanyuda12345.github.io`. Every push to the `main` branch runs the included GitHub Actions workflow and updates the live site.

## Update Links

- LinkedIn is set in `_data/profile.yml`.
- Email is set in `_data/profile.yml`.
- GitHub is set in `_data/profile.yml`.

## Update Resume

Replace `assets/files/Hanyu_Da_Resume_2026.pdf` with a newer PDF using the same filename. The Resume buttons and embedded resume page will update automatically.
