# RoK Kill Point Tracker

Single-file, browser-only tracker for Rise of Kingdoms kill point gains.
Data is stored in the visitor's browser (localStorage); there is no backend.

## Run locally
Open `index.html` in a browser.

## Deploy with GitLab Pages
1. Create a new GitLab project and push these files to the default branch.
2. The pipeline in `.gitlab-ci.yml` runs automatically and publishes the site.
3. Find the URL under Deploy > Pages (usually https://<user>.gitlab.io/<project>).
