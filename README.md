**Rise Paints & Chemicals — Landing Page**

- **Project:** A simple static landing page for Rise Paints & Chemicals (company website mockup).
- **Purpose:** Present company information, services, products, and customer feedback as a small marketing site.

**What's Included:**
- `index.html`, `about.html`, `services.html`, `product.html`, `contact.html` — page templates.
- `assets/css/main.min.css` — minified stylesheet (preloaded in pages).
- `assets/js/main.min.js` — minified JavaScript (loaded deferred).
- `assets/vendor/` — third-party vendor libraries (Bootstrap, Swiper, GLightbox, Isotope, etc.).
- `assets/img/` — images used across the site (hero, products, team, testimonials).

**Key optimizations already applied:**
- Preloaded and switched pages to use `assets/css/main.min.css` to reduce render-blocking.
- Added `assets/js/main.min.js` and load scripts with `defer` to improve initial render.
- Images use `loading="lazy"` (except the hero's primary slide/logo) to reduce initial payload.
- Inline head CSS added to enforce testimonial avatar sizing immediately (fixes oversized avatars).

**How to preview locally:**
- Open `index.html` directly in your browser, or run a simple local server for correct relative loading.

PowerShell example (from project root):

```powershell
# start a local web server on port 8000
python -m http.server 8000
# then open http://localhost:8000 in your browser
```
