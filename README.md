# PlanetGrow - An open-source platform to build community.

This project is built with NextJS, TailwindCSS, and PlanetScale DB.
This is a mono-repo built with turbo repo.

The architecture is as follows:
- apps
  - web : deployed on [planetgrow.site]](https://planetgrow.site)
  - application : deployed on [app.planetgrow.site](https://app.planetgrow.site)
  - docs : deployed on [docs.planetgrow.site](https://docs.planetgrow.site)

packages:
- ui : shared UI components
- tsconfig : shared tsconfig
- eslint-config-custom : shared eslint config


## Getting Started
run `pnpm install` to install all dependencies and then run `turbo dev` to run the applications.

this will start the following applications:
- application : [localhost:3000](http://localhost:3000)
- docs : [localhost:3001](http://localhost:3001)
- web : [localhost:3002](http://localhost:3002)


