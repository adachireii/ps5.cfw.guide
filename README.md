<link rel="shortcut icon" type="image/x-icon" href="images/favicon.ico">
<meta property="og:type" content="website">
<meta property="og:description" content="A complete PS5 modding guide, from stock to etaHEN.">

## PS5 Jailbreak Guide

A complete PS5 modding guide, from stock to jailbroken.

## Running the site locally

This requires the following installed to your system:
- [Node.js v12+](https://nodejs.org/)
- [Yarn v1 classic](https://classic.yarnpkg.com/en/) (npm install --global yarn)

Git clone the repository
```
git clone --recurse-submodules <repo url>
```

To test the website locally, simply run the following commands:
```
yarn install
```
to install all packages required by the website (VuePress v2 and plugins), then
```
yarn docs:dev
```
to build the Markdown files into HTML and start a testing webserver on http://127.0.0.1:8080.
