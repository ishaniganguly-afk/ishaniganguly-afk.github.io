# Personal Portfolio Plan

## Goal

Create a personal portfolio for `ishaniganguly-afk` as a static Jekyll site published by GitHub Pages from the `main` branch and repository root. The expected user-site URL is `https://ishaniganguly-afk.github.io/`.

## Pages and design

- Create Home, About, Work Experience, and Contact pages with shared navigation and footer.
- Keep page content in Markdown with YAML front matter, separate from reusable Jekyll layouts and includes.
- Use a responsive, single-column layout with semantic HTML and accessible color contrast.
- Use a dark-only theme with a fun, pop-culture-inspired editorial feel, balanced by chic, sophisticated, elegant typography and a polished tone suited to senior People leadership. No reference sites or specific fandoms were provided.
- Omit a public email link.

## Content and assumptions

- The user is currently employed and is interested in Chief People Officer, Head of People, or Head of Talent roles.
- User-provided About text includes the current People and Talent Partner role at Mirendil, MBA studies at UC Berkeley Haas, professional interests, and future role interests.
- Work-history details supplied in an image include the Mirendil role (Mar 2026–present) and four SoFi recruiting roles spanning Jun 2019–Jul 2025. Use only the supplied titles, dates, locations, and responsibilities; do not infer missing achievements or metrics.
- A LinkedIn URL was provided, but the profile will not be opened or used. Replace placeholders only with details the user supplies directly or in an uploaded résumé.

## Technical scope

- Keep the complete publish-ready Jekyll site directly in the repository root, including `index.md`, `_config.yml`, `_layouts`, `_includes`, assets, and documentation.
- Use plain HTML and CSS with minimal JavaScript. Do not add a backend, database, blog, CMS, contact form backend, animation system, framework, unnecessary libraries, or third-party trackers.
- Include SEO tags, a sitemap, a favicon, and a README covering site updates, local preview, and Lighthouse checks.
- Keep `baseurl` empty and use URL filters so links work on a GitHub user site.
- The current project includes separate starter API and design-preview apps plus workspace setup. Remove those generated scaffolds so the repository contains only the requested static Jekyll site.

## Verification

- Confirm the root contains the complete site and that it can publish directly from `main` and `/` on GitHub Pages without a manual build step.
- Check navigation and display at 375px and 1280px widths.
- Target Lighthouse scores of at least 90 for Performance, Accessibility, Best Practices, and SEO.
