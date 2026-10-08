# Pulse Medical Magazine website

A plain HTML website with no server, no database, and nothing to maintain. You can host it for free on GitHub Pages, so the only cost is your domain.

## What's in this folder

| Path | What goes there |
|---|---|
| `index.html` | The whole website. Open it in a text editor to change text. |
| `issues/` | Issue PDFs, e.g. `issues/fall-2026.pdf` |
| `images/covers/` | Issue cover images, e.g. `images/covers/fall-2026.jpg` |
| `images/team/` | Staff headshots, e.g. `images/team/jane-doe.jpg` |
| `images/logo.png` | Your logo (used when the link is shared on social media) |

Every section of `index.html` has a comment explaining how to edit it. Search the file for these placeholders:
- `Full Name` (staff names)
- `Issue title` (issue titles and descriptions)
- `your-email@uchicago.edu` and `@your_handle` (contact info)
- `Location TBA` (event details)

## Publish for free with GitHub Pages

1. Create a free account at github.com (a shared club account works best, so access passes down between boards).
2. Click **New repository**, name it `pulse-website`, set it to **Public**, and create it.
3. Click **uploading an existing file** and drag in everything inside this folder (not the folder itself). Click **Commit changes**.
4. Go to **Settings → Pages**. Under "Branch," choose `main` and `/ (root)`, then **Save**.
5. After a minute or two, your site is live at `https://<account-name>.github.io/pulse-website/`.

### Use your own domain

1. Buy a domain from any registrar (Namecheap, Porkbun, Cloudflare, etc.).
2. In GitHub, go to **Settings → Pages → Custom domain**, enter your domain, and save.
3. At your registrar, add the DNS records GitHub shows you (GitHub's guide: "Managing a custom domain for your GitHub Pages site").
4. Once it connects, tick **Enforce HTTPS**.

## Updating the site later

In your repository on GitHub, click any file, then the pencil icon to edit it, or use **Add file → Upload files** to add PDFs and photos. Changes go live within a couple of minutes.

To add a new issue:
1. Upload the PDF to `issues/` and the cover to `images/covers/`.
2. In `index.html`, update the "Current issue" block and move the old one into "Past issues."

## Alternatives

Netlify and Cloudflare Pages are also free: drag this folder onto their site and it goes live the same way.
