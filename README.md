AEM EDS Beaudon Playground
AEM Edge Delivery Services (EDS) playground for testing blocks, styling, page structure, and content publishing patterns.

This repository is used to:

- Experiment with AEM EDS block development
- Test styling and front-end behaviour safely
- Learn the EDS authoring and publishing workflow
- Prototype ideas before applying them to larger projects

## Environments
Preview: ttps://main--aem-beaudon-playground--beaudon.aem.page/
Live: https://main--aem-beaudon-playground--beaudon.aem.live/ 

Project structure

- `blocks/` - custom content blocks
- `scripts/` - JavaScript used across the site
- `styles/` - global and component styling
- `icons/` - icon assets
- `fonts/` - font assets

Documentation

Before using the aem-boilerplate, I recommand you to go through the documentation on https://www.aem.live/docs/ and more specifically:
1. [Developer Tutorial](https://www.aem.live/developer/tutorial)
2. [The Anatomy of a Project](https://www.aem.live/developer/anatomy-of-a-project)
3. [Web Performance](https://www.aem.live/developer/keeping-it-100)
4. [Markup, Sections, Blocks, and Auto Blocking](https://www.aem.live/developer/markup-sections-blocks)

## Installation

```sh
npm i
```

## Linting

```sh
npm run lint
```

## Local development

1. Install the [AEM CLI](https://github.com/adobe/helix-cli):
   ```bash
   npm install -g @adobe/aem-cli
   ```
2. Start the local proxy:
   ```bash
   aem up
   ```
3. Open [http://localhost:3000](http://localhost:3000)
4. Edit the repository in your IDE and test changes locally

## Notes

This project was generated from the [adobe/aem-boilerplate](https://github.com/adobe/aem-boilerplate) template and adapted as a personal EDS sandbox.

