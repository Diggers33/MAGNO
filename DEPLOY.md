# Deploy MAGNO Platform — 2 steps

## Step 1: Push to GitHub

```bash
cd /home/claude/magno-platform

# Create repo via GitHub CLI (if installed)
gh repo create Diggers33/magno-platform --public --description "MAGNO Digital Platform T6.4"

# OR create manually at https://github.com/new → name: magno-platform → Create

# Then push:
git remote add origin https://github.com/Diggers33/magno-platform.git
git branch -M main
git push -u origin main
```

## Step 2: Deploy to Vercel

1. Go to https://vercel.com/new
2. Import → select `magno-platform` from GitHub
3. Framework: **Create React App** (auto-detected)
4. Click **Deploy**

Done. Live URL will be: `https://magno-platform.vercel.app`
