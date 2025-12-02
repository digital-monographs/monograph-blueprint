# Monograph blueprint

## Description

This is a blueprint for Jupyter Book v2 monograph meant to be served as a static website.

## Building a book automatically

This repository is connected to GitHub actions. Whenever a change is pushed to the repository, GitHub builds the book for you.

You can see the book [here](https://digital-monographs.github.io/monograph-blueprint/).

## Building a book on your machine

To build a book out of the blueprint, follow the [mystmd documentation](https://mystmd.org/guide/deployment#creating-static-html).

1. Install `mystmd@v1.6.7`. 
1. Build the static book with `myst build --html && cp -r ./assets _build/html/assets`
1. Serve the book with `npx serve _build/html`

The blueprint was tested with node.js v20.15.0.

