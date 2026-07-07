# BTSY Website: publish steps

This folder is the complete BTSY single-page website: index.html, assets (logo, favicon, illustration), sitemap.xml, robots.txt. The audit request form link is already inserted.

## Before publishing, replace two things in the files

1. In index.html, robots.txt, and sitemap.xml: replace every "YOUR-GITHUB-USERNAME" with your GitHub username (lowercase). There are 3 spots in index.html, 1 in robots.txt, 1 in sitemap.xml.
2. The BTSY audit request form link has already been inserted. Only replace YOUR-GITHUB-USERNAME before publishing.

## Publish with GitHub Desktop

1. Open GitHub Desktop, File, New repository. Name: btsy. Local path: anywhere you like. Create.
2. Copy everything in this folder (index.html, assets folder, sitemap.xml, robots.txt) into that new repository folder. Do not copy this README unless you want it public.
3. In GitHub Desktop: write a commit summary like "BTSY site v1", click Commit to main, then Publish repository. Untick "Keep this code private".
4. On github.com open the btsy repository, Settings, Pages. Under Source pick "Deploy from a branch", branch main, folder / (root). Save.
5. Wait 1 to 2 minutes. The site goes live at https://YOUR-GITHUB-USERNAME.github.io/btsy/
6. Test on your phone: check the logo loads, the WhatsApp buttons open a chat with 1-868-795-3112, and the FAQ items expand.

## After it is live

- Submit the sitemap in Google Search Console (add the site as a URL prefix property, then Sitemaps, enter sitemap.xml).
- Put the live URL on the BTSY Instagram, TikTok, and Facebook profiles so every profile links to it word-for-word the same way.
- If you later buy a custom domain, add it under Settings, Pages, Custom domain, and update the canonical link, og:url, og:image, robots.txt, and sitemap.xml to the new domain.
