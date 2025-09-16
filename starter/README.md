
# Portfolio Starter (No React)

A clean, mobile‑friendly portfolio you can deploy in minutes on Vercel.

## Quick start
1. Replace placeholders:
   - In `index.html`, `about.html`, `contact.html`: set your name, email, GitHub/LinkedIn links.
   - Add/remove projects in `projects.html` (array at bottom of file).
2. (Optional) Put your resume file as `resume.pdf` in this folder.
3. Initialize git and push to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Portfolio starter"
   git branch -M main
   git remote add origin https://github.com/<you>/my-portfolio.git
   git push -u origin main
   ```
4. Deploy on Vercel:
   - Create an account on https://vercel.com, click **New Project**, import your repo, Deploy.
   - You’ll get a live URL like `https://my-portfolio.vercel.app`.

## Adding a project
Edit the `projects` array in `projects.html`:
```js
{
  title:"Expense Tracker",
  desc:"Track daily expenses with charts.",
  stack:["HTML","CSS","JS"],
  live:"https://your-live-url",
  code:"https://github.com/you/expense-tracker"
}
```

## Customize styles
All styles are in `styles.css`. Tweak the `:root` color variables to change the theme.
