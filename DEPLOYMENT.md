# Deployment Instructions

## Quick Deploy

### Option 1: Using the deployment script

```bash
cd epistemic-greek-site
./deploy.sh
```

### Option 2: Manual deployment

1. **Create the GitHub repository under 33fg organization:**
   - Go to https://github.com/organizations/33fg/repositories/new
   - OR go to https://github.com/new and select **Owner: 33fg** from the dropdown
   - Repository name: `epistemic-greek`
   - Description: "Epistemic Greek Project - Exploring knowledge through ancient Greek philosophy and modern epistemic frameworks"
   - Make it **Public**
   - **Do NOT** initialize with README, .gitignore, or license
   - Click "Create repository"

2. **Push the code:**
   ```bash
   cd epistemic-greek-site
   git remote add origin https://github.com/33fg/Epistemic_greeks.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to: https://github.com/33fg/Epistemic_greeks/settings/pages
   - Under **Source**, select:
     - Branch: `main`
     - Folder: `/ (root)`
   - Click **Save**

4. **Your site will be live at:**
   ```
   https://33fg.github.io/Epistemic_greeks/
   ```

## Updating the Site

After making changes:

```bash
cd epistemic-greek-site
git add .
git commit -m "Your commit message"
git push
```

GitHub Pages will automatically rebuild and deploy your changes (usually takes 1-2 minutes).

## Troubleshooting

### Repository already exists
If the repository already exists on GitHub, you can force push:
```bash
git push -u origin main --force
```

### Check deployment status
Visit: https://github.com/33fg/epistemic-greek/actions

### View site logs
Go to: https://github.com/33fg/epistemic-greek/settings/pages
Scroll down to see build logs and deployment history.
