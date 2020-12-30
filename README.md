<p align="center"><img src="./assets/logo.svg" width="300"></p>

# Parcel boilerplate
Use Parcel with GitHub pages to get a seamless development experience.

## Why to use this one?
Besides all the default Parcel features:
- includes Sass
- easy deployment into the `gh-pages` branch. Not a manual process, just run the `npm run deploy` command
- examples of how to import images, split code and link main files are included in the repo, no need to figure it out
- no configuration

## How to use
- if you haven't already, install [Parcel](https://parceljs.org/getting_started.html) globally
- run `npm install`
- turn on the source for GitHub pages to be the `gh-pages` branch, if it doesn't exist it will be created automatically by the build script
- link `scss` or `sass` files directly inside `index.html` or import them in javascript 
- set the homepage inside package.json to follow this format `https://[your_gh_username].github.io/[your_repo_name]`, basically whatever the domain of your github page will be e.g. https://adamgiebl.github.io/neumorphism. If you have a custom domain then use that one
  
## Scripts
- `npm start` or `npm run dev` to run a local server with live reload
- `npm run deploy` to deploy into the gh-pages branch

