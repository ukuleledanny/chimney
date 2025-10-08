Chiminy Cricket — Static Website
=================================

How to use
----------
1) Replace placeholder images in /assets/images with your own.
   The filenames are descriptive, e.g. "hero-family-fireplace-placeholder.jpg".
   Keep filenames the same or update the <img src="..."> paths in the HTML.

2) Replace placeholder copy (headlines, testimonials, etc.) directly in the HTML files:
   - index.html (home)
   - about.html
   - services.html
   - news.html (listing)
   - post.html (single-post template — duplicate this per article)
   - contact.html

3) Contact form:
   This site has no backend.
   If you later want submissions without opening an email client, consider a free static form service
   like Netlify Forms or Formspree (free tiers exist). Do not add paid APIs unless you want them.

4) Hosting:
   - GitHub Pages: push these files to a repo and turn on Pages in repo settings.
   - Netlify: drag-and-drop the folder into the Netlify dashboard or connect the repo.
   Both work as pure static hosting (no build step required).

5) Analytics (optional):
   In each HTML file's <head>, there's a commented GA4 snippet. Paste your tag ID to enable it.

6) SEO:
   - Edit <title>, <meta name="description">, and Open Graph tags in the <head> of each page.
   - Keep alt text descriptive.
   - Update sitemap.xml/robots.txt with your real domain.

7) Accessibility:
   - Semantic headings (h1, h2, etc.), visible focus outlines, sufficient color contrast.
   - "Skip to content" link and ARIA labels included.

8) Performance:
   - Minimal CSS/JS; no frameworks. Optimize your own images for web (≈1200px width is often fine).
   - Loading should be well under 3 seconds on standard broadband.

9) Scalability:
   - Add more pages by duplicating an existing HTML file and updating nav and sitemap.xml.

Branding
--------
Primary burgundy: #772432
Secondary slate:  #5F6A72

License
-------
You own this website. No external dependencies, no paid APIs.
