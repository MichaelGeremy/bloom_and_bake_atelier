# Bloom & Bake Atelier - Vercel Deployment

## Quick Deploy to Vercel

### Option 1: Deploy via Vercel CLI (Recommended)

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm install -g vercel
   ```

2. **Navigate to the project folder**:
   ```bash
   cd bloom-bake-vercel
   ```

3. **Deploy**:
   ```bash
   vercel
   ```
   
4. Follow the prompts:
   - Set up and deploy? **Yes**
   - Which scope? Select your account
   - Link to existing project? **No**
   - Project name: `bloom-bake-atelier` (or your preferred name)
   - In which directory is your code located? **./`**
   - Want to override settings? **No**

5. Your site will be deployed and you'll get a URL like: `https://bloom-bake-atelier.vercel.app`

### Option 2: Deploy via Vercel Dashboard

1. Go to [vercel.com](https://vercel.com)
2. Sign in with GitHub, GitLab, or Bitbucket
3. Click **"Add New..."** → **"Project"**
4. **Import the project**:
   - Either push this folder to a Git repository and import from there
   - Or drag and drop the entire `bloom-bake-vercel` folder
5. Vercel will auto-detect the settings
6. Click **"Deploy"**

### Option 3: Deploy via GitHub (Best for updates)

1. Create a new repository on GitHub
2. Push this folder to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/bloom-bake-atelier.git
   git push -u origin main
   ```
3. Go to [vercel.com](https://vercel.com) and click "Import Project"
4. Select your GitHub repository
5. Click "Deploy"

## Files Included

- `index.html` - Main website file
- `vercel.json` - Vercel configuration
- `README.md` - This file

## Features

✨ Emerald velvet luxury design
🎨 Gold metallic accents
📱 Fully responsive
🔗 QR code for contact
🌟 Animated elements
📲 Social media integration

## Custom Domain (Optional)

After deployment, you can add a custom domain:
1. Go to your project in Vercel Dashboard
2. Click "Settings" → "Domains"
3. Add your custom domain
4. Follow DNS configuration instructions

## Support

For issues or questions:
- Email: support@vercel.com
- Docs: https://vercel.com/docs

---

**Bloom & Bake Atelier** | A Division of Tanzanite Lux Events
