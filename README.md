# Martian Zoo site

This repository publishes the separate Martian Zoo website at
https://www.martianzoo.dev/ using GitHub Pages. It contains plain HTML and image
files, with no site generator or content management system.

The image collection lives in this repository under `images/`. It was initially
copied from `kevinb9n/martianzoo`, which no longer publishes images on the
personal site. Update the images here to publish changes to Martian Zoo.

The `playground/` directory contains the prebuilt Mars Playground Wasm app from
`MartianZoo/solarnet`. It is currently omitted from the home-page navigation and
requests no search indexing. Build with
`./gradlew :playground:wasmJsBrowserDistribution`, then replace only this directory
with the contents of the Playground module's `dist/wasmJs/productionExecutable`.
The app uses this site's image collection and runs entirely in the browser.
