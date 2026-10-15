# PianoScribbles

Minimal, responsive music portfolio for Carlos Corpeno Panameno. Plain HTML and CSS; no installation or build step required.

## Preview

Open `index.html`, or run `python3 -m http.server 8000` in this directory.

## Publish on GitHub Pages

1. Push these files to the `main` branch.
2. In the repository, open **Settings → Pages**.
3. Select **Deploy from a branch**, then **main** and **/ (root)**. Save.
4. The project URL is https://indoordragon.github.io/pianoscribbles-website/.

## Use PianoScribbles.com

After the project site works, enter `pianoscribbles.com` in **Settings → Pages → Custom domain** and configure the domain DNS using the current GitHub Pages documentation: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site . Enable HTTPS once the certificate is ready. A CNAME file is deliberately omitted until the domain is configured.

## Update content

Edit `index.html` for text, section links, published-score links, performance embeds, shop links, and contact details. Edit `styles.css` for layout and typography. All local assets use relative paths so the site works at either the project URL or a custom domain.

Profile, shop, and contact URLs have not been guessed. The corresponding sections currently explain where the verified links will go. Replace those notes with real links when supplied. Replace the spinet project summary with the specific repair work and photographs when available.
