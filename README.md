
# MitolynSpecial Landing (Static Site)

Files you need are here. No coding.

## 1) Put on GitHub
- Go to github.com → New repository → name: `mitolynspecial-landing`
- Click **Upload files** → drag everything from this folder → **Commit**

## 2) Deploy on Vercel
- Go to vercel.com → Add New Project → Import from GitHub → pick `mitolynspecial-landing`
- Framework: **Other**
- Build command: leave blank
- Output directory: **/** (root)
- Click **Deploy**

## 3) Connect your domain (mitolynspecial.com)
- Vercel → Project → Settings → **Domains** → Add `mitolynspecial.com`
- At your domain provider:
  - A record for `mitolynspecial.com` → **76.76.21.21**
  - CNAME for `www.mitolynspecial.com` → **cname.vercel-dns.com**
- Wait a few minutes → Vercel will verify and give SSL automatically

## 4) Test
- Open your site and click buttons (they go to your affiliate link)
- Use Microsoft UET Tag Helper Chrome extension to confirm tracking
