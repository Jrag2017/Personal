# 🚀 Quick Deployment Guide (Cursor → GitHub → Vercel)

## Step 1: Set Up in Cursor

1. **Download all files** from Claude to a new folder on your computer:
   - `portfolio.html`
   - `projects.html`
   - `Jarrett_Raghnal_Resume.pdf`
   - `README.md`
   - `.gitignore`
   - `vercel.json`

2. **Open folder in Cursor:**
   - File → Open Folder
   - Select your portfolio folder

3. **Open Cursor Terminal** (Ctrl+` or Cmd+`)

## Step 2: Initialize Git & Push to GitHub

Run these commands in Cursor's terminal:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit
git commit -m "Initial portfolio website"

# Create GitHub repo (Option 1: Use GitHub website)
# Go to github.com/new and create a repo named "portfolio"
# Then run:
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git branch -M main
git push -u origin main
```

**OR use GitHub CLI if installed:**
```bash
gh repo create portfolio --public --source=. --remote=origin --push
```

## Step 3: Deploy to Vercel

### Method A: Vercel Website (Easiest)
1. Go to [vercel.com/signup](https://vercel.com/signup)
2. Sign up with GitHub
3. Click "Add New Project"
4. Select your `portfolio` repository
5. Click "Deploy"
6. **Done!** Your site is live at `your-portfolio-xyz.vercel.app`

### Method B: Vercel CLI (Terminal)
```bash
# Install Vercel CLI
npm i -g vercel

# Login
vercel login

# Deploy
vercel

# Follow prompts and select your GitHub repo
```

## Step 4: Get Custom Domain (Optional)

### Free Option: Use Vercel subdomain
- Your site gets: `jarrett-raghnal.vercel.app`
- Go to Vercel dashboard → Settings → Domains
- Edit to customize the subdomain

### Paid Option: Buy custom domain
1. Buy domain from Namecheap/Google Domains (~$12/year)
2. In Vercel: Settings → Domains → Add
3. Follow DNS setup instructions
4. Done in ~10 minutes

## 🔄 Making Updates

Whenever you want to update your site:

```bash
# Make changes in Cursor
# Save files

# Push to GitHub
git add .
git commit -m "Updated projects section"
git push

# Vercel automatically deploys! (takes ~30 seconds)
```

## ✅ Verification Checklist

- [ ] All files downloaded from Claude
- [ ] Folder opened in Cursor
- [ ] Git initialized and pushed to GitHub
- [ ] Vercel connected to GitHub repo
- [ ] Site deployed and accessible
- [ ] Resume downloads correctly
- [ ] Projects page loads
- [ ] Chatbot works
- [ ] Mobile responsive (test on phone)

## 🆘 Troubleshooting

**Resume not downloading?**
- Make sure `Jarrett_Raghnal_Resume.pdf` is in the root folder
- Check file name matches exactly in HTML

**Projects page 404?**
- Verify `projects.html` is in root folder
- Check `vercel.json` is deployed

**Site not updating?**
- Check Vercel dashboard for deployment status
- May take 30-60 seconds after push

## 📞 Need Help?

- Vercel Docs: [vercel.com/docs](https://vercel.com/docs)
- GitHub Docs: [docs.github.com](https://docs.github.com)

---

**Pro Tip:** Set up Vercel GitHub integration so every push to `main` automatically deploys. This means you just edit in Cursor, push, and your site updates automatically!
