# Deploying Byler & Sons Garage Website on Cloudflare Pages

## 1. Prerequisites
- You need a free Cloudflare account: https://dash.cloudflare.com/
- Your project folder should have an `index.html` (already present).
- (Optional) Add more files as your site grows (CSS, images, etc).

## 2. Project Structure
```
bylerandsonsgarage/
├── index.html
├── README.md
├── .gitignore
```

## 3. Steps to Deploy

1. **Initialize a Git Repository (if not already):**
   ```sh
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. **Push to GitHub (or GitLab/Bitbucket):**
   - Create a new repo on GitHub.
   - Add the remote and push:
     ```sh
     git remote add origin https://github.com/YOUR-USERNAME/bylerandsonsgarage.git
     git push -u origin main
     ```

3. **Set Up Cloudflare Pages:**
   - Go to Cloudflare Pages: https://dash.cloudflare.com/?to=/:account/pages
   - Click **Create a Project**.
   - Connect your GitHub repo.
   - For build settings, use:
     - **Framework preset:** None
     - **Build command:** (leave blank)
     - **Output directory:** `./`
   - Click **Save and Deploy**.

4. **Access Your Site:**
   - Cloudflare will give you a free URL like `https://bylerandsonsgarage.pages.dev`

---

*Update this file as you add more features or need to document deployment changes.*
