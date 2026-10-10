Mohammad Khamaysi - personal site (static HTML, no build step)

Pages:   index.html (Home), research.html, work.html, about.html
Assets:  style.css, img/ (photos, VSA pictures, course-project schematics), figs/ (thesis figures),
         cv/Mohammad_Khamaysi_CV.pdf, thesis_khamaysi.pdf
         img/home_video.mp4 is the background video from the old Adobe Portfolio home page; it is not used
         by the pages (kept in case you want it back).

Publish (free, custom domain supported):
  GitHub Pages: create a repository, upload everything in this folder to its root, Settings > Pages >
  Source "Deploy from a branch" (main, / root). The site appears at https://<user>.github.io/<repo>/.
  For your own domain (e.g. khamaysi.com from Namecheap/Cloudflare, ~10 USD/year): add a file named
  CNAME containing the domain, and at the registrar add a CNAME record www -> <user>.github.io and the
  four GitHub Pages A records for the apex. GitHub issues the HTTPS certificate automatically.
  Netlify/Cloudflare Pages: drag this folder onto the dashboard; same custom-domain steps.

Before publishing:
  - Replace cv/Mohammad_Khamaysi_CV.pdf and thesis_khamaysi.pdf when you have newer versions.
