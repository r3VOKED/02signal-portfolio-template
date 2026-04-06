# 02Signal Portfolio — Setup Guide

This is your personal portfolio for the 02Signal program.
You will use it to showcase the automations you build each week.
Follow every step carefully — do not skip any.

---

## Part 1: Fork this repo to your own GitHub account

Forking means making your own personal copy of this repo.

### Step 1 — Create a GitHub account (if you don't have one)
1. Go to [github.com](https://github.com)
2. Click **Sign up**
3. Enter your email, create a password, choose a username
4. Verify your email address
5. You now have a GitHub account

### Step 2 — Fork this repo
1. Make sure you are logged into GitHub
2. Go to this repo:
   `https://github.com/02signal/02signal-portfolio-template`
3. Click the **Fork** button at the top right of the page
4. Under "Owner", make sure YOUR username is selected (not 02signal)
5. Leave the repo name as is: `02signal-portfolio-template`
6. Click **Create fork**
7. You will be taken to your own copy of the repo at:
   `https://github.com/YOUR-USERNAME/02signal-portfolio-template`

✅ You now have your own copy of the portfolio template.

---

## Part 2: Create a free Vercel account

Vercel is the service that publishes your portfolio as a live website.

### Step 1 — Sign up for Vercel
1. Go to [vercel.com](https://vercel.com)
2. Click **Sign Up**
3. Select **Continue with GitHub**
4. You will be asked to authorize Vercel to access your GitHub account
5. Click **Authorize Vercel**
6. Complete any remaining signup steps

✅ You now have a Vercel account connected to your GitHub.

---

## Part 3: Connect your forked repo to Vercel

This is the step that makes your portfolio go live automatically
every time you make a change.

### Step 1 — Create a new Vercel project
1. You should be on the Vercel dashboard after signing up
2. Click **Add New** → **Project**
3. You will see a list of your GitHub repos
4. Find `02signal-portfolio-template` and click **Import**

### Step 2 — Configure the project
1. Leave all settings as they are — no changes needed
2. Click **Deploy**
3. Vercel will build and publish your site (takes about 30 seconds)
4. You will see a success screen with your live URL

### Step 3 — Find your live URL
1. Your site is now live at a URL that looks like:
   `https://02signal-portfolio-template-YOUR-USERNAME.vercel.app`
2. Click the URL to confirm your portfolio loads in the browser

✅ Your portfolio is now live on the internet.

---

## Part 4: Personalise your portfolio

Now that your site is live, update it with your details.

### Step 1 — Edit your README.md on GitHub
1. Go to your forked repo on GitHub:
   `https://github.com/YOUR-USERNAME/02signal-portfolio-template`
2. Click on `README.md`
3. Click the **pencil icon** (Edit this file) at the top right
4. Replace `[Your Name]` with your actual name
5. Fill in the **About Me** section with a short intro
6. Scroll down and click **Commit changes**
7. Add a short description like `Update name and bio`
8. Click **Commit changes** again

### Step 2 — Confirm your site updated
1. Go back to your Vercel dashboard at [vercel.com](https://vercel.com)
2. You will see a new deployment happening automatically
3. Wait about 30 seconds, then visit your live URL again
4. Your changes should be visible

✅ Every time you push a change to GitHub, your site updates automatically.

---

## Part 5: Adding your work each week

### Adding a workflow
1. Export your n8n workflow as JSON
   (In n8n: open workflow → top right menu → Download)
2. Upload the JSON file to the `/workflows` folder in your repo
3. Commit the change
4. Your workflow is now saved and visible in your portfolio

### Updating your automations section
1. Edit `README.md`
2. Edit the automation you built that week
3. Commit the change

---

## Troubleshooting

**I can't find the Fork button**
Make sure you are logged into GitHub. The Fork button only appears
when you are logged in.

**My Vercel deployment failed**
Go to your Vercel dashboard, click on the failed deployment,
and read the error message. Most common cause is a file formatting
issue. Ask your mentor for help if unsure.

**My site didn't update after I made changes**
Wait 1-2 minutes and refresh. If still not updated, go to your
Vercel dashboard and check if a new deployment was triggered.
If not, check that you committed and pushed your changes on GitHub.

**I made a mistake in my README**
Just edit it again and commit. Every commit creates a new version —
you can never permanently break anything.