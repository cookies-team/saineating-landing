# Saineating-Landing

The Landing Page for Saineating Project

This page is secondery developed based on [Doks](Doks.README.md)

## Install Deps

```bash
# install latest nodejs
# suggest using `nvm install node --lts` 
git clone https://github.com/cookies-team/saineating-landing && cd saineating-landing
npm i
```

## Debug

Run a local server for debugging

```bash
npm run server
```

Manually visit the URL

## Publish

```bash
npm run build
```

A new subfolder called `public` will be created.

Move the all content inside `public` subfolder to the root of your server engine (e.g. `/var/www/`)
