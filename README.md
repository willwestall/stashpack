# Stashpack — Landing Page

A product landing page for Stashpack, the cooler backpack that keeps drinks cold without ice.

## 📁 Project Structure

```
stashpack/
├── index.html      # Entire site — styles, scripts, and images all embedded
├── vercel.json     # Vercel deployment config
└── README.md
```

> Everything is self-contained in `index.html`. No build step, no dependencies.

---

## 🚀 Deployment

### Option 1: GitHub + Vercel (Recommended)

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → **Add New Project**
3. Import your GitHub repo
4. Click **Deploy** — no config needed

Any future push to `main` will auto-redeploy.

### Option 2: Vercel CLI

```bash
npm i -g vercel
vercel
```

### Option 3: GitHub Pages

1. Go to your repo → **Settings** → **Pages**
2. Set source to `main` branch, `/ (root)`
3. Save — your site will be live at `https://yourusername.github.io/repo-name`

---

## 🛠 Customization

- **Colors** — Search for `#6c63ff` (purple accent) or `#0b0d1a` (background) in `index.html` to restyle
- **Content** — Edit text directly in `index.html`
- **Waitlist form** — Find the `handleWaitlist` function in the `<script>` tag at the bottom of `index.html` and connect to Mailchimp, ConvertKit, or Supabase

---

## 👥 Team

Anthony, Will, Jack, Quinn, Brady
