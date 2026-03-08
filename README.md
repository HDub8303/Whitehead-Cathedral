# Whitehead Cathedral COGIC — Website

Static website for Whitehead Cathedral COGIC, hosted via GitHub Pages.

## Pages

| File | URL | Description |
|------|-----|-------------|
| `index.html` | `/` | Home page |
| `bios.html` | `/bios.html` | Pastor & First Lady bios |
| `team.html` | `/team.html` | Meet the Team |
| `give.html` | `/give.html` | Regular giving / tithes & offerings |
| `firstfruit.html` | `/firstfruit.html` | First Fruit offering |
| `join.html` | `/join.html` | Membership interest form |

## Social Media

All pages link to the church's social accounts in the footer:

- **Facebook:** https://www.facebook.com/profile.php?id=61560007231030
- **Instagram:** https://www.instagram.com/whitehead_cathedral
- **YouTube:** https://youtube.com/@whiteheadcathedralcogic

## Membership Form (`join.html`)

The Join Us form collects the following and sends responses to **whiteheadcathcogic@gmail.com** via the visitor's email client:

- Full name, email, phone
- Home address
- Baptism status
- Spouse and children information
- Areas of interest (membership, ministry, baptism, etc.)
- Open message field

All "Join Us" buttons and nav links across the site point to this page.

## Deploying to GitHub Pages

1. Create a new GitHub repository (e.g. `whitehead-cathedral`)
2. Push all files to the `main` branch
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch` → `main` → `/ (root)`
5. Save — your site will be live at `https://<your-username>.github.io/whitehead-cathedral/`

## Notes

- All pages are self-contained HTML files with embedded CSS
- Google Fonts (Cormorant Garamond, Outfit) are loaded from CDN — internet required to render correctly
- No build step or dependencies required
