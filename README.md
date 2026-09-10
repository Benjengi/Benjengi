# Ben Smith — Engineering Portfolio

A standalone HTML/CSS website. No dependencies, build step, API keys or Sites account required.

Files
- index.html: page content and structure
- style.css: colours, typography and responsive layout

Preview locally
Extract the ZIP and open index.html in a desktop web browser. Keep style.css beside it.

Publish to your existing GitHub Pages address
1. Sign in to GitHub and open https://github.com/Benjengi/Benjengi
2. In Code, select the branch you intend to publish (usually main; it may be master).
3. At the repository top level, choose Add file > Upload files.
4. Upload the extracted index.html and style.css files, replacing the existing index.html. Do not upload the ZIP or put the files inside an extra folder. Leave unrelated repository files alone.
5. Enter a commit message such as Update engineering portfolio and commit the change. If the branch is protected, create a branch and pull request, then merge it before publishing.
6. Open Settings > Pages. Under Build and deployment, set Source to Deploy from a branch.
7. Select the branch containing these files and /(root), then Save.
8. Check the Actions tab for completion of the Pages deployment. When successful, open https://benjengi.github.io/Benjengi/

Later updates
Edit index.html for content and style.css for appearance. Commit updates to the same publishing branch to redeploy.

Troubleshooting
- Unstyled page: confirm style.css is beside index.html with exactly that lowercase name.
- Old design: confirm deployment succeeded, then reload without cache or open a private browsing window.
- 404: confirm the selected branch and /(root) folder contain index.html at their top level.
- Failed deployment: open the failed Pages workflow in Actions to read the error.

Content notes
The export preserves the portfolio as created. Concept and academic work are labelled. The Open University degree is described generically because the exact award route was not confirmed. Text is editable in index.html.

Official instructions
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
