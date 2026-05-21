# AEM EDS Beaudon Playground

AEM Edge Delivery Services (EDS) playground for testing blocks, styling, page structure, and content publishing patterns.

This repository is used to:
- Experiment with AEM EDS block development
- Test styling and front-end behaviour safely
- Learn the EDS authoring and publishing workflow
- Prototype ideas before applying them to larger projects

## Environments

Preview: https://main--aem-beaudon-playground--beaudon.aem.page/  
Live: https://main--aem-beaudon-playground--beaudon.aem.live/

## Project structure

- `blocks/` – custom content blocks  
- `scripts/` – JavaScript used across the site  
- `styles/` – global and component styling  
- `icons/` – icon assets  
- `fonts/` – font assets

## Documentation

Before using the boilerplate, I recommend going through the documentation at https://www.aem.live/docs/, especially:

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

3. Open http://localhost:3000 in your browser.
