# Right Choice Cutz Barbershop — website

A single-page site with an online booking section. No build step, no dependencies — it's plain HTML, CSS and JavaScript in `index.html`, plus two photos in `images/`.

## Host it on GitHub Pages

1. Create a new repository on GitHub (e.g. `right-choice-cutz`) and upload everything in this folder — `index.html`, the `images/` folder, and this `README.md` — keeping the same structure.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to "Deploy from a branch."
4. Set **Branch** to `main` (or `master`) and folder to `/ (root)`, then **Save**.
5. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/` within a minute or two — refresh the Pages settings page to see the live link.

If you'd rather use a custom domain (e.g. `rightchoicecutz.com`), add it under **Settings → Pages → Custom domain** and point your domain's DNS at GitHub Pages per [GitHub's instructions](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

## Editing later

Everything is in `index.html` — services and prices, barber names, hours, the address/phone block, and the customer quotes are plain text near the top-to-bottom order they appear on the page. Search for `<!-- EDIT` comments in the file for the spots still using placeholder content (barber names, hours, and reviews).

The booking form on the page collects a request and shows a confirmation — it doesn't send anywhere yet. To have requests reach you, either point the "Book a chair" button at your Booksy page, or connect the form to a service like Formspree.
