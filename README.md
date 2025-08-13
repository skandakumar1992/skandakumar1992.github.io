Tiny checklist (do this in order)
1.	Create repo (public).
2.	Add index.html (root or docs/).
3.	Push to GitHub (main or master).
4.	Settings → Pages → Source = Deploy from a branch → select branch + folder → Save.
5.	Actions → confirm Pages build and deployment succeeded.
6.	Open the URL shown in Settings → Pages.

A. One-time prep
⦁	   Open your Git Bash create a new folder and named them(Myproject) for your project.
   

B. Create the repo
⦁	   New repository → Name it
⦁	   For a user site: skandakumar192.github.io
⦁	   Choose Public, add a README (optional).
⦁	   Create the repo.

C. Add your static files
⦁	   Make a minimal site locally
⦁	   Create a file with at least an index.html (this file is the homepage).
⦁	   Create a file with at styles.css
⦁	   Push to GitHub (CLI)
⦁	   cd Myproject
⦁	   git init
⦁	   git add .
⦁	   git commit -m "feat: initial site"
⦁	   git branch -M main   
⦁	   git remote add origin https://github.com/skandakumar1992/skandakumar1992.github.io.git
⦁	   git push -u origin main

D. Turn on GitHub Pages
⦁	   Open repo → Settings → Pages
⦁	   Build and deployment → Source: select Deploy from a branch.
⦁	   Branch: choose the branch that has your files (main or master).
⦁	   Folder: choose / (root) if index.html is in the repo root, or /docs if you put the site inside a docs/ folder.
⦁	   Click Save.

GitHub will create a “Pages build and deployment” workflow run automatically (check it in the Actions tab).

E. Get your site URL
⦁	   Open that URL—your site should load.

F. Update the site (next changes)
⦁	   Edit files locally → git add, git commit, git push.
⦁	   The Pages build and deployment action runs again. When it completes, refresh your site.
