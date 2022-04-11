# Hugo Bootstrap v5 Blog [![Build Status](https://ci.mjanja.ch/api/badges/alanorth/default/status.svg)](https://ci.mjanja.ch/alanorth/default)
A simple but opinionated [Hugo](https://gohugo.io) theme geared towards blog-style content. Based on the "snarky" (their words) [Bootstrap v5 blog example](https://getbootstrap.com/docs/5.0/examples/blog) that originally debuted in [Bootstrap 4's final release](https://blog.getbootstrap.com/2018/01/18/bootstrap-4/).

## Features

- Responsive design
- Supports automatic generation of `<img>` srcsets for images in [page bundles](https://gohugo.io/content-management/page-bundles/) using a [new figure shortcode]https://cpbotha.net/2020/05/02/drop-in-replacement-for-hugo-figure-shortcode-with-responsive-img-srcset/) (falls back to default Hugo behavior of looking up images in the static directory)

## Building (For Developers)
This theme uses the [Bootstrap](https://getbootstrap.com/) framework. A static version of this is already included, but if you want to bump the version, tweak the style, etc, you'll need to rebuild the assets. Make sure you have NodeJS >= v10 installed, and then run the following from inside the theme's directory:

```console
$ npm install
$ npm run dist
```

## License
This repository contains SASS and HTML code from the [Bootstrap](https://getbootstrap.com) project, which is licensed under the [MIT](https://tldrlegal.com/license/mit-license) and [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/) licenses, and the Playfair Display font, which is licensed under the [SIL Open Font License, 1.1](https://scripts.sil.org/OFL).
