# hugo-mock-landing-page

The workflow is automated with GitHub actions in file .github/workflows/gh-pages-deployment.yaml. It runs every time a push is made to the main branch:
1) Checks for new changes to code
2) Installs Hugo
3) Builds the static site
4) Website deployed to GitHub Pages
