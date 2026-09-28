# Game Design Portfolio

A clean, professional portfolio site for showcasing university game design work, built with Jekyll and GitHub Pages.

## How to Customize

### 1. **Edit the Landing Page** (`index.md`)
Replace the placeholder text with your actual information:
- Your name
- University name
- Your design interests
- Featured projects (add or remove sections as needed)
- Skills and tools you use
- Contact information

### 2. **Update Site Settings** (`_config.yml`)
Change these fields:
- `title:` Your portfolio title
- `description:` A short tagline
- `author.name:` Your name
- `author.email:` Your email
- `url:` Your site URL (should be `https://pringles344.github.io`)

### 3. **Add Project Pages** (Optional)
Create individual project pages in a `_projects/` folder:
```
_projects/
  ├── project-1.md
  ├── project-2.md
  └── project-3.md
```

Each project file should look like:
```yaml
---
layout: default
title: Your Project Name
---

# Project Name

**Tools**: Unity, Unreal, etc.
**Semester**: Fall 2024

[Project description, screenshots, links, etc.]
```

### 4. **Change the Theme** (Optional)
Edit `_config.yml` and try a different Jekyll theme:
- `jekyll-theme-minimal` (clean, minimal)
- `jekyll-theme-slate` (dark, modern)
- `jekyll-theme-cayman` (colorful, friendly)
- `jekyll-theme-time-machine` (retro, unique)

## Next Steps

1. Go to [index.md](index.md) and replace all the `[Your ...]` placeholders
2. Visit `https://pringles344.github.io` to see your live site (may take a minute to update)
3. Add project pages as needed
4. Customize the theme if desired

That's it! Your portfolio is live.
