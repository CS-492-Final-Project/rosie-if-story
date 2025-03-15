![active development](https://img.shields.io/badge/active%20dev-yes-brightgreen.svg)
![repo size](https://img.shields.io/github/languages/code-size/CS-492-Final-Project/rosie-if-story)
[![W3C Validation - https://validator.nu/](https://img.shields.io/w3c-validation/default?targetUrl=https%3A%2F%2Fcs492-rosie.simranthind.me%2F&label=w3c%20check)](https://validator.nu/?doc=https%3A%2F%2Fcs492-rosie.simranthind.me%2F)
[![Netlify Status](https://api.netlify.com/api/v1/badges/c24c8ae0-dfb6-43a1-9eb1-fabbaf3814d5/deploy-status)](https://app.netlify.com/sites/cs492-rosie/deploys)

# rosie-if-story
🌹CS 492 final project - interactive fiction game made with Twine!

### Website Development
This project uses [yarn](https://yarnpkg.com/) as a package manager, and [Svelte](https://svelte.dev/) as the frontend framework. [Tailwind CSS](https://tailwindcss.com/) is the preferred method of styling, and [prettier](https://prettier.io/) for formatting is a part of the repository. Finally, this project is deployed via [Netlify](https://www.netlify.com/).

1. Clone this repository locally.
2. In the root of this repository, run `yarn install`.
3. Other commands:
   * To start a development server: `yarn dev`.
   * To create a production version: `yarn build`.
   * Locally preview the production build: `yarn preview`.
   * To format: `yarn format`.
   * To lint: `yarn lint`.

### Twine Story Development
1. If you haven't already, install [Twine](https://twinery.org/).
2. Clone this repository locally, but do not put it in the same folder as the one that was automatically created by Twine to hold all Twine stories. 
3. All files relating to the story are located in the `rosie-if` folder, in this repository. The `CS492-Rosie-IF.html` file is the compiled Twine story. To open this story in Twine, head to Library → Import → then choose the aforementioned HTML file.
4. This will create a copy of the story in the Twine application folder, and any edits you make to the story will impact this copy. This means that to sync to git / GitHub, you need to copy back and replace the file in the repository folder. You can do this when in the story: Build → Publish to File → save to repository folder.
