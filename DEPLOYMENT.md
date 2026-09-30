# 🚀 GitHub Pages Deployment — Step by Step

**Goal:** Get your interactive guide live at a public URL (completely free)

**Time needed:** 5-10 minutes

---

## ✅ Prerequisites

- GitHub account (free at [github.com](https://github.com))
- This folder with 3 files: `index.html`, `README.md`, `.gitignore`

---

## 📋 Step-by-Step Deployment

### **STEP 1: Create a GitHub Account**

1. Go to [github.com](https://github.com)
2. Click **Sign up**
3. Enter email, create password, username (e.g., `andre-marketing`)
4. Verify email
5. Done ✅

---

### **STEP 2: Create a New Repository**

1. Log in to GitHub
2. Click the **`+`** icon (top right corner)
3. Select **New repository**

   | Field | Enter |
   |-------|-------|
   | Repository name | `lift-creative-builder` |
   | Description | `Interactive guide for high-converting iGaming video ads` |
   | Visibility | **Public** ← Important! |
   | Add README? | Check the box |

4. Click **Create repository** ✅

---

### **STEP 3: Upload Files to Your Repository**

**Option A: Upload via Web (Easiest)**

1. You're now in your new repository
2. Click **Add file** (green button, top right)
3. Select **Upload files**
4. Drag and drop these files:
   - `index.html`
   - `README.md`
   - `.gitignore`
5. Click **Commit changes** ✅

**Option B: Upload via Terminal (If you know Git)**

```bash
# Clone your new repo
git clone https://github.com/YOUR-USERNAME/lift-creative-builder.git
cd lift-creative-builder

# Copy the files into this folder
cp /path/to/index.html .
cp /path/to/README.md .
cp /path/to/.gitignore .

# Push to GitHub
git add .
git commit -m "Add Lift creative builder guide"
git push origin main
```

---

### **STEP 4: Enable GitHub Pages**

1. In your repository, click **Settings** (top right)
2. In the left sidebar, click **Pages**
3. Under "Source", make sure you see:
   - Branch: **main**
   - Folder: **/ (root)**
4. Click **Save**

**GitHub will now show you:**
```
Your site is live at:
https://your-username.github.io/lift-creative-builder/
```

Copy this URL. ✅

---

### **STEP 5: Verify Your Site is Live**

1. Wait 1-2 minutes
2. Visit your URL: `https://your-username.github.io/lift-creative-builder/`
3. You should see the guide fully loaded
4. Try clicking the tabs to verify interactivity

**If you don't see it:**
- Wait another minute (GitHub sometimes needs time)
- Hard refresh your browser (Cmd+Shift+R on Mac, Ctrl+Shift+R on Windows)
- Check Settings → Pages again to see the deployment status

---

## 🎉 You're Done!

Your guide is now live and public. Anyone can visit:
```
https://your-username.github.io/lift-creative-builder/
```

**Share this link with your team!**

---

## 🔄 Update Your Guide (Later)

When you want to update the guide:

**Via Web (Easiest):**
1. Go to your repository
2. Click on `index.html`
3. Click the pencil icon (Edit)
4. Make your changes
5. Scroll down and click **Commit changes**
6. Your live site updates in 1-2 minutes ✅

**Via Terminal:**
```bash
cd lift-creative-builder
# Edit index.html in your editor
git add index.html
git commit -m "Update frameworks section"
git push origin main
# Site updates in 1-2 minutes
```

---

## 📊 What You Can Do Now

✅ Share the URL with your entire team  
✅ Update the guide anytime (no redeploy needed)  
✅ Get analytics via GitHub (if you set it up)  
✅ Collaborate with your team on edits  
✅ Fork this repo to create variations for different brands  

---

## ❓ Troubleshooting

| Problem | Solution |
|---------|----------|
| "Page not found" | Wait 2-3 minutes, then hard refresh (Cmd+Shift+R) |
| Site doesn't load | Check Settings → Pages, make sure "main" branch is selected |
| Changes not live | Make sure you clicked "Commit changes", then wait 1-2 min |
| Want custom domain? | GitHub Pages allows custom domains (settings → Pages → Custom domain) |

---

## 🔗 Your Public URLs

**Main guide:**  
`https://your-username.github.io/lift-creative-builder/`

**Edit on GitHub:**  
`https://github.com/your-username/lift-creative-builder`

---

**Questions? Drop them in the repository Issues tab.**

Happy deploying! 🚀
