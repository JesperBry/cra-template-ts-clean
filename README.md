# cra-template-ts-clean

This is a cleand version of the official typescript template form CRA. This template also extends with setting up a developing and production enviorment with Docker and Nginx (See all the commands in the Makefile).

## Usage

```bash
$ npx create-react-app [name of app/location] --template ts-clean
```

## Project structure

```bash
|____node_modules
|____public
| |____favicon.ico
| |____index.html
| |____manifest.json
| |____robots.txt
|____src
| |____assets
| |____components
| | |____styles
| |____hooks
| |____utils
| |____App.css
| |____App.tsx
| |____index.css
| |____index.tsx
| |____reportWebVitals.ts
| |____setupTests.ts
| |____react-app-env.d.ts
|____.dockerignore
|____Dockerfile
|____.gitignore
|____Makefile
|____nginx.conf
|____nodemon.json
|____README.md
|____package-lock.json
|____package.json
|____tsconfig.json
```
