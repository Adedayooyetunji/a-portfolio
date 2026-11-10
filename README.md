# Adedayo Oyetunji Oluwayemisi — DevOps & Cloud Engineer Portfolio

A responsive static portfolio website built with HTML, CSS and vanilla JavaScript. It includes a GitHub Actions workflow to deploy to GitHub Pages.

## 1. Open in Visual Studio Code

1. Download and extract the ZIP.
2. Open Visual Studio Code.
3. Select **File → Open Folder** and choose `adedayo-devops-portfolio`.
4. Install the **Live Server** extension (optional).
5. Right-click `index.html` and choose **Open with Live Server**, or open `index.html` directly in a browser.

## 2. Personalise before publishing

Search in `index.html` and replace:
- `your.email@example.com` with your professional email.
- `https://www.linkedin.com/` with your LinkedIn profile URL.
- `https://github.com/` with your GitHub profile URL.
- Each project link currently points to the GitHub homepage. Replace it with the real repository URL when the project is ready.

Review the About and Skills sections. Keep only technologies and experience you can confidently demonstrate. Add project screenshots, architecture diagrams, README links, and measurable outcomes when you have them. Do not claim certifications you have not earned.

## 3. Publish the code to GitHub

This project is published in the public [`a-portfolio`](https://github.com/Adedayooyetunji/a-portfolio) repository. From the project folder, run:

```bash
git add .
git commit -m "Build DevOps portfolio website"
git branch -M main
git push
```

If you are setting up a fresh clone, use `git push -u origin main` the first time. If Git asks you to authenticate, complete the browser sign-in prompt.

## 4. Enable GitHub Pages deployment

1. Open your repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **GitHub Actions**.
4. Open the **Actions** tab and confirm the workflow named **Deploy portfolio to GitHub Pages** completes successfully.
5. Your site will be available at:

`https://Adedayooyetunji.github.io/a-portfolio/`

The first deployment can take a few minutes. Every push to `main` triggers another deployment.

## 5. Update the website

Edit files in VS Code, preview locally, then run:

```bash
git add .
git commit -m "Update portfolio content"
git push
```

GitHub Actions will deploy the update automatically.

## 6. Suggested next improvements

- Add real project repositories and detailed case studies.
- Include architecture diagrams and screenshots from your own deployments.
- Add a downloadable PDF CV.
- Add a custom domain and analytics if needed.
- Add a contact form only when you have a secure form service or backend.

## Project structure

```text
a-portfolio/
├── .github/
│   └── workflows/
│       └── deploy.yml
├── css/
│   └── style.css
├── js/
│   └── main.js
├── index.html
├── .gitignore
└── README.md
```
