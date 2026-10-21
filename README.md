# TripTailor — Your Trip. Your Way.

Static demo website for a Business Acceleration Lab project (Narayana Business School).
Single page: `index.html` (HTML + CSS + JavaScript in one file). No backend, no build step.

## Files
| File | Purpose |
|---|---|
| `index.html` | The whole website (GitHub Pages serves this at the root URL) |
| `requirements.txt` | Notes only: there are no packages to install |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (optional, harmless) |
| `README.md` | This guide |

## Deploy on GitHub Pages (browser only)
1. Create a **public** repository, e.g. `triptailor`.
2. Click **Add file → Upload files**, drag in the *contents* of this folder (`index.html`, `README.md`, `requirements.txt`, `.nojekyll`), then **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. Wait 1–2 minutes. Your site is live at `https://<your-username>.github.io/triptailor/`.

## Before sharing publicly
Open `index.html`, find the `CONFIG` block near the bottom, and replace:
- `whatsappNumber` (digits with country code, e.g. `919876543210`)
- `phoneDisplay`, `email`, `instagramUrl`

Contact details are placeholders until you do. The forms do not send data anywhere; real submissions need a backend or form service (see the `FORM INTEGRATION` comments in the code).

## Updating
Edit `index.html` on GitHub (pencil icon) and commit. The site refreshes in a minute or two.
