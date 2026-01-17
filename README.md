# Starlet Computer Technology Website

This is a static website for Starlet Computer Technology, ready for deployment on Vercel and version control with GitHub.

## Features
- Modern responsive design
- WhatsApp integration for direct chat
- Course and admissions information
- Ready for static hosting (Vercel, Netlify, GitHub Pages)

## Getting Started

### 1. Local Development
You can preview the site locally with Python:

```bash
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080) in your browser.

### 2. Deploy to Vercel
1. [Sign up for Vercel](https://vercel.com/) if you don't have an account.
2. Install Vercel CLI (optional):
   ```bash
   npm i -g vercel
   ```
3. In this project folder, run:
   ```bash
   vercel
   ```
4. Follow the prompts to deploy your site.

### 3. Push to GitHub
1. Initialize a git repository (if not already):
   ```bash
   git init
   ```
2. Add all files:
   ```bash
   git add .
   ```
3. Commit your changes:
   ```bash
   git commit -m "Initial commit"
   ```
4. Create a new repository on GitHub and follow the instructions to push your code:
   ```bash
   git remote add origin https://github.com/yourusername/your-repo.git
   git branch -M main
   git push -u origin main
   ```

## Notes
- The `vercel.json` config ensures correct static deployment.
- `.gitignore` excludes unnecessary files from git and Vercel.
- You can add or update images in the `images/` folder.

---

For any issues, contact your developer or Starlet Computer Technology support.
# starlet-computer-school-
