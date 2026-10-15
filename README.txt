EXPERIMENT 1 — GIT, GITHUB AND GITHUB PAGES

Files:
- index.html: webpage to run and publish
- README.txt: this guide

OUTPUT:
Open index.html in your browser. You should see:
"Web Development Practical"
"Hello, GitHub Pages!"
"This is a simple static website created using HTML and CSS."

GIT COMMANDS:
Run these commands in VS Code terminal after opening the Experiment-1 folder:
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/Frostheim29/web-development-exp1.git
git push -u origin main

IMPORTANT:
1. Create a NEW empty public repository named web-development-exp1 under your GitHub account Frostheim29.
2. Do not run git remote add if a remote named origin already exists. If it says origin already exists, tell ChatGPT or run: git remote -v
3. Git must be installed and you must be signed in/authenticated to GitHub.
4. For branch/merge demonstration:
   git switch -c feature-update
   (edit index.html, save it)
   git add .
   git commit -m "Update webpage"
   git switch main
   git merge feature-update
   git push
5. To publish: GitHub repository > Settings > Pages > Deploy from a branch > main > /(root) > Save.
6. Use the actual Pages URL displayed by GitHub after deployment. Expected format:
   https://frostheim29.github.io/WD-EXP-1/
