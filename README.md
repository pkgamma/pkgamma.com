# pkgamma.com

This is the static sources of PKGamma's agency website. Built with [Eleventy](https://www.11ty.io/) and hosted on [Netlify](https://www.netlify.com/). Netlify builds the site automatically every time the source files are pushed to the [git repo](https://github.com/pkgamma/pkgamma.com) so that I don't have to build locally.

## Website structure

The texts on the website are located in the `.njk` files in the root directory. All the texts are read into the `index.njk` file in the `_includes/layouts` folder and built by Eleventy, generating static `html` files in the `_site` folder. To create more language specific pkgamma home pages, simply create more `.njk` files in the root directory.

`.css`, `.js`, picture, and font files are also copied into `_site` when `Eleventy` build commend is ran because of the rules created in `.eleventy.js`.

## Build websites locally

Simply run `Eleventy` (assuming all npm packages are installed correctly).

## Updating pkgamma.com

Simply push the local updates to the [git repo](https://github.com/pkgamma/pkgamma.com) and Netlify will updates it automatically.

Last (or first) updated on Dec 23rd, 2018 (third day of Winter Break).