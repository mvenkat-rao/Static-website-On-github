http://127.0.0.1:5500/index.html

Create a GitHub repo named <yourusername>.github.io. (Replace <yourusername> with your actual GitHub username).
Clone repo locally. Open your terminal or Git Bash and run:
code
Bash
git clone https://github.com/<yourusername>/<yourusername>.github.io.git
cd <yourusername>.github.io
Copy your static website files (HTML, CSS, JS) into repo folder. Place the index.html, style.css, and script.js files you created above directly into the yourusername.github.io folder you just cloned.
Commit and push files to GitHub.
code
Bash
git add .
git commit -m "Initial static website files"
git push origin main
Enable GitHub Pages in repo settings (branch: main, root folder). Go to your repository on GitHub, navigate to "Settings" -> "Pages". Select "main" as the branch and "/ (root)" as the folder, then click "Save".
Wait a few minutes and open https://<yourusername>.github.io to view site.
Update site by pushing new commits. If you make changes to your HTML, CSS, or JS files, repeat the git add ., git commit -m "Your update message", and git push origin main steps.
Share URL for portfolio or demo.
