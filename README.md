# Electrogram

A simple photo editor built with Angular 2 and electron. It allows you to upload/drag-and-drop images, apply filters to them, and save them to your desktop.

## Prerequisites
You will need to have [Git](https://git-scm.com/) and [Node.js + NPM](http://nodejs.org) installed on your machine.

## Getting started

First you will need to clone the repo; then you can install the necessary NPM packages and run the app.

```bash
# Clone the repo and enter it
git clone git@github.com:onehungrymind/electrogram.git
cd electrogram

#Install dependencies
npm i

# To build only
npm run build

# To watch for changes
npm run watch

# Start the Electron app
npm run electron
```

## Distributing the app
We've included an NPM script that will built a distrubtion version of the app for OSX. To use it, execute `npm run distribute`; this will create an OSX app in `releases/Electrogram-darwin-x64` that you can run from Spotlight and Finder. For more info, check out https://github.com/electron-userland/electron-packager.

## Author

Luke Ruebbelke | twitter.com/simpulton | onehungrymind.com
