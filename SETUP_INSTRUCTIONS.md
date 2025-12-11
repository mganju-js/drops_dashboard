# 🚀 GitHub Pages Setup - Step by Step

Follow these exact steps to get your dashboard live on GitHub Pages:

## Part 1: Create GitHub Repository (5 minutes)

### Step 1: Go to GitHub
1. Open browser and go to https://github.com
2. Log in (or create account if you don't have one)

### Step 2: Create New Repository
1. Click the **"+"** icon in top right corner
2. Click **"New repository"**
3. Fill in:
   - **Repository name:** `pretzelized-dashboard`
   - **Description:** (optional) "Promotion performance analysis dashboard"
   - **Public** ← IMPORTANT: Must be public for free GitHub Pages
   - **DO NOT check** "Add a README file"
   - **DO NOT check** "Add .gitignore"
   - **DO NOT check** "Choose a license"
4. Click **"Create repository"**

### Step 3: Note Your Repository URL
After creating, you'll see commands on the screen. 
Your repo URL will look like: `https://github.com/YOUR_USERNAME/pretzelized-dashboard.git`

**Keep this page open!** You'll need these commands in a moment.

---

## Part 2: Upload Your Files (5 minutes)

### Option A: Using Command Line (Recommended)

1. **Open Terminal/Command Prompt**
   - Mac: Open "Terminal" app
   - Windows: Open "Git Bash" (install from https://git-scm.com if needed)

2. **Navigate to your downloaded folder**
   ```bash
   cd Downloads/pretzelized-dashboard
   ```

3. **Connect to GitHub** (replace YOUR_USERNAME with your actual GitHub username)
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/pretzelized-dashboard.git
   ```

4. **Push to GitHub**
   ```bash
   git branch -M main
   git push -u origin main
   ```

5. **Enter GitHub credentials when prompted**

### Option B: Using GitHub Web Interface (Easier, slower)

1. On your empty repository page, click **"uploading an existing file"**
2. Drag and drop ALL files from the pretzelized-dashboard folder
3. Click **"Commit changes"**

---

## Part 3: Enable GitHub Pages (2 minutes)

1. **Go to Settings**
   - In your repository, click **"Settings"** tab (top right)

2. **Navigate to Pages**
   - In left sidebar, scroll down and click **"Pages"**

3. **Configure Source**
   - Under "Branch", click dropdown and select **"main"**
   - Leave folder as **"/ (root)"**
   - Click **"Save"**

4. **Wait for Deployment**
   - A blue banner will appear saying "GitHub Pages source saved"
   - Refresh the page after 1-2 minutes
   - You'll see a green banner with your live URL!

5. **Your Dashboard is Live! 🎉**
   - URL will be: `https://YOUR_USERNAME.github.io/pretzelized-dashboard/`
   - Bookmark this link
   - Share with your team

---

## Part 4: Making Updates (Ongoing)

### Quick Edit on GitHub (Easiest)
1. Go to your repository
2. Click `index.html`
3. Click pencil icon (Edit)
4. Make changes
5. Scroll down, click "Commit changes"
6. Wait 1-2 minutes → changes are live!

### Edit Locally (For bigger changes)
1. Make changes to `index.html` on your computer
2. In terminal:
   ```bash
   cd pretzelized-dashboard
   git add index.html
   git commit -m "Updated metrics for Q4"
   git push
   ```
3. Wait 1-2 minutes → changes are live!

---

## 📋 Quick Reference

**Your Repository:** https://github.com/YOUR_USERNAME/pretzelized-dashboard
**Your Live Site:** https://YOUR_USERNAME.github.io/pretzelized-dashboard/
**Edit Files:** Click any file → Pencil icon → Make changes → Commit

---

## ❓ Troubleshooting

**Problem:** "404 - Page not found"
- **Solution:** Wait 2-3 minutes after enabling Pages, then refresh

**Problem:** "Changes aren't showing"
- **Solution:** Wait 1-2 minutes after commit, do hard refresh (Ctrl+Shift+R or Cmd+Shift+R)

**Problem:** "Permission denied" when pushing
- **Solution:** Generate GitHub Personal Access Token:
  1. GitHub Settings → Developer Settings → Personal Access Tokens
  2. Generate new token (classic)
  3. Select "repo" scope
  4. Use token as password when prompted

**Problem:** "Repository not found"
- **Solution:** Check your remote URL: `git remote -v`
- Update if wrong: `git remote set-url origin https://github.com/YOUR_USERNAME/pretzelized-dashboard.git`

---

## 🎯 Next Steps

1. ✅ Get your dashboard live
2. ✅ Share the link with your team
3. ✅ Make a test edit to see the update process
4. 📖 Read `EDIT_GUIDE.md` for common edits
5. 🎨 Customize as needed for future analyses

Need help? Check the README.md file for more details!
