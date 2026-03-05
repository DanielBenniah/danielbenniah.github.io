# Personal website

Static personal site — [Daniel Benniah John](https://danielbenniah.github.io/) (Distributed Systems & Applied AI).

## Deploy as GitHub Pages

1. **Create a GitHub repository**
   - On GitHub: **New repository** (e.g. `personal-website` or `username.github.io` for a user site).
   - Do not add a README, .gitignore, or license if you’re pushing this folder.

2. **Initialize Git and push** (from this folder in terminal):
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```
   Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your GitHub username and repo name.

3. **Turn on GitHub Pages**
   - In the repo: **Settings** → **Pages** (left sidebar).
   - Under **Build and deployment**:
     - **Source**: Deploy from a branch.
     - **Branch**: `main` (or `master`), folder **/ (root)**.
   - Click **Save**.

4. **View the site**
   - After a minute or two it will be live at:
     - `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/` (e.g. `personal-website`)
     - Or `https://YOUR_USERNAME.github.io/` if the repo is named exactly `YOUR_USERNAME.github.io`.

## Repo name options

| Repo name              | Site URL                          |
|------------------------|-----------------------------------|
| `username.github.io`   | `https://username.github.io/`     |
| `personal-website`     | `https://username.github.io/personal-website/` |

For a clean URL like `https://yourname.github.io/`, create a repo named **yourusername.github.io** and push this project into it (use that repo as `origin` in step 2).
