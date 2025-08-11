# Deploy Your Travel Booking App to Vercel

## Simple Step-by-Step Guide

### Step 1: Prepare Your Code
1. Copy all your project files from VS Code to a new folder on your computer
2. Make sure you have the `vercel.json` file in the main folder

### Step 2: Create Vercel Account
1. Go to https://vercel.com
2. Sign up with your GitHub, GitLab, or email
3. Verify your email if needed

### Step 3: Upload Your Project
**Option A: Using Vercel Website (Easiest)**
1. Login to Vercel
2. Click "New Project"
3. Choose "Browse All Templates"
4. Select "Import Git Repository" 
5. Upload your project folder as a ZIP file

**Option B: Using GitHub (Recommended)**
1. Create a GitHub account at https://github.com
2. Create a new repository
3. Upload your project files to GitHub
4. Connect GitHub to Vercel
5. Import your repository in Vercel

### Step 4: Configure Deployment
1. In Vercel dashboard, find your project
2. Go to project settings
3. Add these Environment Variables:
   - `NODE_ENV` = `production`
4. Set Build Command: `npm run build`
5. Set Output Directory: `client/dist`

### Step 5: Deploy
1. Click "Deploy" button
2. Wait 2-5 minutes for deployment
3. Your app will be live at: `https://your-project-name.vercel.app`

## Important Notes:
- Your app password is: `Ttrave` (username: `admin`)
- The app uses in-memory storage, so data resets on each deployment
- For permanent data, you'll need to set up a database later

## Troubleshooting:
- If build fails, check the build logs in Vercel
- Make sure all files are uploaded correctly
- Contact Vercel support if needed

Your travel booking website will be live and accessible worldwide once deployed!