# Austin's Portfolio

A simple portfolio website connected to Supabase for feedback collection.

## Hosting
Hosted as a Static Site on [Render](https://render.com).

## Deployment
This project uses a **manual** CI/CD pipeline via GitHub Actions.

### How to deploy
1. Make your changes and push to GitHub:
   ```bash
   git add .
   git commit -m "Your changes"
   git push
   ```
2. Go to **GitHub → Actions → Deploy to Render**
3. Click **Run workflow → Run workflow**
4. Render will pull the latest code and go live.

## Setup Requirements
- Add `RENDER_DEPLOY_HOOK_URL` as a GitHub repository secret (Settings → Secrets → Actions)
- Get the Deploy Hook URL from your Render Static Site dashboard
