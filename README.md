# apps.zenika.com

A web page with links to our internal applications.

## How to run locally

Serve the `public` folder using the web server of your choice.

For example:
- using Node.js: `npx serve public/`.
- using Python 3: `python -m http.server --directory public/`.

## How to deploy

The `main` branch is automatically deployed to production.

To *temporarily* deploy another branch, on said branch, modify the filters of
the `deploy_prod` job of the `deploy_main` workflow in `.circleci/config.yml`.
