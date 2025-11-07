# Final Steps to Push to GitHub

Your local Git repository is ready! Follow these final steps:

## Step 1: Create a GitHub Repository

1. Go to https://github.com and sign in
2. Click the "+" icon (top right) → "New repository"
3. Name your repository (e.g., "online-bookstore" or "WEBTEC")
4. **DO NOT** check "Initialize with README" (we already have one)
5. Click "Create repository"

## Step 2: Push to GitHub

After creating the repository, run these commands (replace `YOUR_USERNAME` and `YOUR_REPO_NAME`):

```powershell
# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push to GitHub
git push -u origin main
```

## If you need to authenticate:

GitHub no longer accepts passwords. You'll need a **Personal Access Token**:

1. Go to GitHub → Settings → Developer settings → Personal access tokens → Tokens (classic)
2. Click "Generate new token (classic)"
3. Select scopes: check `repo` (full control of private repositories)
4. Generate and copy the token
5. When prompted for password, paste the token instead

## Quick Command (copy and modify):

```powershell
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

That's it! Your code will be on GitHub. 🚀

