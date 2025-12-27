# Jarrett Raghnal - Portfolio Website

AI Integration Engineer & Gen AI Specialist portfolio showcasing enterprise AI systems and custom application development.

## 🚀 Live Site
- **Production:** [Your Vercel URL here]
- **Contact:** jraghnal613@gmail.com

## 💼 Features

- **Mission Control Design** - Dark, technical aesthetic inspired by NADO
- **Responsive Layout** - Works on desktop, tablet, and mobile
- **AI Chatbot** - Interactive assistant that answers questions about background and skills
- **Downloadable Resume** - PDF resume with one click
- **Projects Showcase** - Enterprise AI and custom app development portfolio
- **Smooth Animations** - Polished entrance animations and hover effects

## 🛠 Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Fonts:** JetBrains Mono, Space Mono (Google Fonts)
- **Hosting:** Vercel
- **Version Control:** GitHub

## 📂 File Structure

```
portfolio/
├── portfolio.html          # Homepage
├── projects.html          # Projects showcase
├── Jarrett_Raghnal_Resume.pdf  # Downloadable resume
└── README.md             # This file
```

## 🚢 Deployment Instructions

### Deploy to Vercel (Recommended)

1. **Push to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
   git push -u origin main
   ```

2. **Connect to Vercel:**
   - Go to [vercel.com](https://vercel.com)
   - Click "Add New Project"
   - Import your GitHub repository
   - Click "Deploy"
   - Done! Your site is live.

3. **Custom Domain (Optional):**
   - In Vercel dashboard → Settings → Domains
   - Add your custom domain
   - Update DNS records as instructed

### Deploy to GitHub Pages (Alternative)

1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Source: Deploy from branch `main`
4. Folder: `/ (root)`
5. Save and wait ~5 minutes
6. Site will be live at `https://YOUR_USERNAME.github.io/portfolio`

## 🎨 Customization

### Update Content
- Edit text in `portfolio.html` and `projects.html`
- Replace `Jarrett_Raghnal_Resume.pdf` with updated resume

### Change Colors
Edit CSS variables in both HTML files:
```css
:root {
    --accent-primary: #00ff88;  /* Change primary accent color */
    --accent-secondary: #00cc6e; /* Change hover states */
}
```

### Update Chatbot Responses
Find `generateResponse()` function in `portfolio.html` and modify responses

## 📱 Contact

- **Email:** jraghnal613@gmail.com
- **Phone:** 929-771-4066
- **LinkedIn:** [Add your LinkedIn]
- **GitHub:** [Add your GitHub]

## 📄 License

© 2024 Jarrett Raghnal. All rights reserved.
