Project boilerplate with parcel and automatic deployment into the GitHub pages branch.
SCSS included.

## How to use
- run `npm install`
- turn on the source for GitHub pages to be the `gh-pages` branch, if it doesn't exist it will be created automatically by the build script
- link scss files directly inside index.html or import them in javascript 
- set the homepage inside package.json to follow this format https://<your gh username>.github.io/<your repo name>
  
## Scripts
- `npm run deploy` to deploy into gh-pages branch
- `npm run dev` run development environment
