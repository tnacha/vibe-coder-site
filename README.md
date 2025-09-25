# Vibe Coder Personal Introduction Website

This is a simple, static personal introduction website built with pure HTML and CSS, designed to be fast, clean, and mobile-responsive.

## Project Structure

```
vibe-coder-website/
├── index.html      (About page)
├── projects.html   (Projects page)
├── style.css       (Global styles)
└── images/         (Placeholder for project images)
└── README.md       (This file)
```

## Deployment Instructions

This site can be easily deployed to static hosting services like Vercel, Netlify, or GitHub Pages.

### 1. GitHub Pages

1.  **Create a GitHub Repository:**
    *   Go to GitHub and create a new public repository (e.g., `vibe-coder-website`).
    *   Do NOT initialize with a README, `.gitignore`, or license.
2.  **Upload Your Files:**
    *   Navigate to your `vibe-coder-website` directory in your terminal.
    *   Initialize a Git repository: `git init`
    *   Add your files: `git add .`
    *   Commit your changes: `git commit -m "Initial Vibe Coder website"`
    *   Link to your GitHub repository: `git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git` (Replace `YOUR_USERNAME` and `YOUR_REPOSITORY_NAME`)
    *   Push your code: `git push -u origin master`
3.  **Enable GitHub Pages:**
    *   On GitHub, go to your repository's "Settings" tab.
    *   In the left sidebar, click "Pages".
    *   Under "Build and deployment", select "Deploy from a branch".
    *   Choose the `master` branch and `/ (root)` folder, then click "Save".
    *   Your site will be deployed, and the URL will be provided on this page (e.g., `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY_NAME/`). It might take a few minutes to become active.

### 2. Vercel

1.  **Create a GitHub Repository:** (Follow step 1 from GitHub Pages instructions above)
2.  **Upload Your Files:** (Follow step 2 from GitHub Pages instructions above)
3.  **Connect to Vercel:**
    *   Go to [Vercel](https://vercel.com/) and sign up or log in.
    *   Click "Add New..." -> "Project".
    *   Select "Import Git Repository" and choose your GitHub repository.
    *   Vercel will automatically detect that it's a static HTML/CSS site.
    *   Click "Deploy".
    *   Your site will be deployed, and Vercel will provide you with a live URL.

### 3. Netlify

1.  **Create a GitHub Repository:** (Follow step 1 from GitHub Pages instructions above)
2.  **Upload Your Files:** (Follow step 2 from GitHub Pages instructions above)
3.  **Connect to Netlify:**
    *   Go to [Netlify](https://www.netlify.com/) and sign up or log in.
    *   Click "Add new site" -> "Import an existing project".
    *   Connect to GitHub and select your repository.
    *   Netlify will automatically detect that it's a static HTML/CSS site.
    *   Click "Deploy site".
    *   Your site will be deployed, and Netlify will provide you with a live URL.

## Next Steps

*   **Replace Placeholder Content:** Update `index.html` with your actual bio and `projects.html` with your real project details.
*   **Add Project Images:** Place your project images in the `images/` directory and update the `src` attributes in `projects.html`. You can use online placeholder image services (e.g., `https://via.placeholder.com/300x200`) temporarily if you don't have images ready.
*   **Customize Styling:** Modify `style.css` to match your preferred colors and aesthetics.
