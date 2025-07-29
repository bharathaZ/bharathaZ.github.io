# Deploy Your Website to GitHub Pages

## Step 1: Create GitHub Repository
1. Go to [github.com](https://github.com) and sign in
2. Click the "+" icon → "New repository"
3. Name it: `personal-website` or `bharatha-rankothge`
4. Make it **Public** (required for free GitHub Pages)
5. Don't initialize with README
6. Click "Create repository"

## Step 2: Connect Your Local Repository
After creating the repository, GitHub will show you commands. Use these:

```bash
# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push your code to GitHub
git branch -M main
git push -u origin main
```

## Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" section (left sidebar)
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch
6. Click "Save"

## Step 4: Your Website is Live!
- Your site will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`
- It may take a few minutes to deploy
- You can add a custom domain later if desired

## Step 5: Update Your Website
To make changes:
```bash
git add .
git commit -m "Update website content"
git push
```

## Troubleshooting
- If you get a 404 error, wait 5-10 minutes for deployment
- Make sure your repository is public
- Check that `index.html` is in the root directory
- Verify the branch name is "main" (not "master")

## Custom Domain (Optional)
1. Buy a domain (e.g., from Namecheap, GoDaddy)
2. In repository Settings → Pages → Custom domain
3. Add your domain (e.g., `bharatharankothge.com`)
4. Update DNS settings with your domain provider 