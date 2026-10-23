# Sunshine Homes Website — Squarespace Custom Code

Live site: [sunshinehomeslimited.co.nz](https://www.sunshinehomeslimited.co.nz)  
GitHub Pages: [saifeem52-wq.github.io/sunshine-homes-website](https://saifeem52-wq.github.io/sunshine-homes-website)

---

## How This Works

Each page has its own HTML file in the `/pages/` folder.  
These files are served via **GitHub Pages** and loaded into Squarespace via a tiny Code Block snippet — so updates here go live automatically with a single `git push`.

## File Structure

```
pages/
  home.html        → Homepage (/)
  about.html       → About page (/about)
  services.html    → Services page (/services)
  projects.html    → Our Projects page (/our-projects)
  contact.html     → Contact page (/contact)

squarespace-snippets/
  home-snippet.html       → Paste this into Squarespace Code Block for Homepage
  about-snippet.html      → Paste into About page Code Block
  services-snippet.html   → Paste into Services page Code Block
  projects-snippet.html   → Paste into Projects page Code Block
  contact-snippet.html    → Paste into Contact page Code Block
```

## Updating the Site

1. Edit any file in `/pages/`
2. Run:
   ```
   git add .
   git commit -m "Your update description"
   git push
   ```
3. Wait ~60 seconds → changes are live on the site automatically ✅

## First-Time Setup in Squarespace

See `squarespace-snippets/` — each snippet is a one-time paste into the relevant page's Code Block.
