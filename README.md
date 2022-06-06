**Note: Actions will fail until you do these steps.**

1. Hit Use Template
2. Add a repo secret `GH_PAT` with the value of your personal access token w/ repo perms.
3. Fill out project name/urls/etc in `package.json`.
4. `npm install -g npm-check-updates`
5. `ncu -u`
6. `npm i`
7. Change `.github/labeler.yml` and `.github/labels.yml` to match your project.
8. Push to repo
