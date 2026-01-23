+++
title = "About Me"
subtitle = "Étudiant en Ingénierie des médias"
layout = "about-alternative"
+++

I'm a software engineer passionate about building elegant solutions to complex problems. Currently working on modern web applications and exploring the intersection of design, performance, and developer experience.

## What I Do

I work across the full stack with expertise in:

- **Backend Development** — Scalable APIs, microservices, database design
- **Frontend Engineering** — React, Vue, modern JavaScript frameworks
- **Cloud & DevOps** — AWS, Docker, Kubernetes, CI/CD pipelines
- **Open Source** — Contributing to projects and building developer tools

## Current Projects

Right now I'm focused on:

- Building minimal Hugo themes for personal sites
- Exploring dark-mode design patterns and accessibility
- Writing about web performance and developer experience
- Contributing to open-source projects in the web ecosystem

## About This Layout

> This page demonstrates the **alternative about layout** with a sidebar profile card.

### Key Features

This layout includes:

1. **Left Sidebar Profile Card** with:
   - Avatar/profile image (or placeholder icon)
   - Name and role
   - Location indicator
   - Customizable stats (configured in `hugo.toml`)
   - Social media links

2. **Main Content Area** with:
   - Introduction section
   - Experience cards (from `---` separators)
   - Tech stack badges (configured in `hugo.toml`)

### How to Configure

**Stats and Skills** are parametrized in your `hugo.toml`:

```toml
[params.about.alt]
  # Custom stats
  [[params.about.alt.stats]]
    value = "5+"
    label = "Years Coding"

  # Tech stack with icons
  [[params.about.alt.skills]]
    label = "JavaScript"
    icon = "devicon-javascript-plain"
```

This makes it easy to update your stats and skills without editing this page!

---

**Freelance Graphic Designer** — [JF Design](https://www.instagram.com/jfd3sign/)
*mars 2023 – Aujourd'hui*

Leading development of cloud-native applications and mentoring engineering teams. Focus on scalable architecture, clean code practices, and continuous delivery.

---

<!-- **Livreur polyvalent** — Sushi Shop
*2020 – 2022 • Vevey*

Built full-stack applications from scratch. Worked with React, Node.js, PostgreSQL, and AWS to deliver features serving hundreds of thousands of users.

--- -->

## Layout Comparison

| Feature | Standard About | Alternative About |
|---------|---------------|-------------------|
| Layout | Centered, single column | Sidebar + content |
| Profile Info | Top hero section | Left sidebar card |
| Stats | Not included | Configurable stats grid |
| Tech Stack | Not included | Icon badges |
| Timeline | Vertical with markers | Card-based grid |
| Best For | Traditional resumes | Modern portfolios |

Try both layouts to see which fits your style! Switch by changing `layout = "about"` or `layout = "about-alternative"` in the frontmatter.

### Responsive Design

Both layouts are fully responsive:
- **Desktop:** Sidebar + content (alternative) or centered (standard)
- **Tablet:** Stacked layout with adjusted spacing
- **Mobile:** Single column, optimized for small screens

---

## Get Started

To use this layout on your site:

1. Copy this content file structure
2. Set `layout = "about-alternative"` in frontmatter
3. Configure stats and skills in `hugo.toml`
4. Add your own content and experience
5. Optionally add an avatar image to `static/images/`

That's it! The theme handles all the styling and responsive behavior automatically.
