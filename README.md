# Ishani Ganguly — personal portfolio

This is a static Jekyll site for the GitHub user site `ishaniganguly-afk.github.io`. GitHub Pages can publish it directly from the `main` branch and the repository root; there is no separate build workflow to set up.

## Publish with GitHub Pages

1. In Replit, open **Git** from the sidebar or **Tools → Git**. Create a new GitHub remote repository named exactly `ishaniganguly-afk.github.io`. Check the connected repository name before continuing, and make the repository **Public**, not Private.
2. While on the `main` branch in Replit, commit the first version with a short message such as `Create first portfolio version`, then **Push**.
3. On GitHub, open the repository `ishaniganguly-afk.github.io` and confirm the website files are visible on its `main` branch.
4. While viewing that repository, open its **Settings** tab (not your personal GitHub account settings).
5. In the repository’s left sidebar, select **Pages** under **Code and automation**.
6. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/(root)`

   Then click **Save**.
7. Wait for GitHub Pages to finish publishing. Return to the repository’s **Settings → Pages** screen and click **Visit site**.
8. Open `https://ishaniganguly-afk.github.io/`. Confirm the site loads and test every navigation link.

The site uses an empty `baseurl` and Jekyll’s `relative_url` / `absolute_url` filters for links.

## Update the site

- `index.md`, `about.md`, `work-experience.md`, and `contact.md` contain page content and YAML front matter.
- `_layouts/default.html` and `_includes/` contain the shared page shell, navigation, SEO tags, and footer.
- `_data/navigation.yml` controls the main navigation.
- `assets/css/site.css` contains the responsive styles; `assets/favicon.svg` is the favicon.
- `about.md` contains the biography you supplied. `work-experience.md` contains the roles, dates, locations, and responsibilities you shared; no achievements or metrics were added.
- Replace or add content only with details you want to publish. The website is public.
- The public email link is intentionally omitted. The LinkedIn link on Contact was provided directly; its profile content was not accessed.

## Preview locally

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000/`. Jekyll watches the files and rebuilds as you edit.

## Run Lighthouse

1. Start the local preview with `bundle exec jekyll serve`.
2. Open `http://127.0.0.1:4000/` in Chrome.
3. Open Chrome DevTools → **Lighthouse**, select Performance, Accessibility, Best Practices, and SEO, and run the report. Test both mobile and desktop.

The target is 90 or higher in each category. Re-run Lighthouse after changing page content, styles, or metadata.

## Technical choices

- GitHub Pages’ supported `github-pages` gem keeps local preview aligned with its Jekyll environment.
- The `jekyll-seo-tag` and `jekyll-sitemap` plugins provide page metadata and a sitemap without a custom build step.
- The site uses semantic HTML, plain CSS, system font stacks, and no JavaScript, external fonts, backend, trackers, or contact form.

## Assumptions

- `ishaniganguly-afk` is the GitHub username and the matching user-site repository will be used.
- The dark-only visual direction should feel pop-culture-inspired and fun while keeping the typography elegant and the presentation appropriate for senior People leadership.
- The LinkedIn URL is used only as a direct contact link. It has not been opened or used as a content source.
- The About and Work Experience pages use only details you supplied directly. The LinkedIn profile was not opened or used as a source.
