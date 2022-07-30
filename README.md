# Hugo-PaperMod-NetlifyCMS-Starter

This repository should help you get started with using Hugo and the Papermod theme quickly on Netlify with NetlifyCMS.  It's based on the [hugo-Papermod example site](https://github.com/adityatelange/hugo-PaperMod), with NetlifyCMS support added in the /static/admin directory.  

## Install

There's two quick ways to get started with this:

1.) Use the deploy to Netlify button below. Once deployed you can add posts via NetlifyCMS at /admin.
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/cjreinhardt/Hugo-PaperMod-NetlifyCMS-Starter)

2.) Clone this repository and develop locally.
```
Install Hugo
Clone this repository
git submodule update --init --recursive
uncomment the local_backend line in /static/admin.config.yml
hugo server -D 
npx netlify-cms-proxy-server
```

## More Info on Hugo Papermod

VIsit the Hugo Papermod Github repo => [hugo-Papermod at Github](https://github.com/adityatelange/hugo-PaperMod)

Read the Hugo Papermod Wiki => [hugo-PaperMod - Installation](https://github.com/adityatelange/hugo-PaperMod/wiki/Installation)

## Directory Tree

```
.(site root)
├── configTaxo.yml
├── config.yml
├── content
│   ├── archives.fr.md
│   ├── archives.md
│   ├── posts
│   │   ├── emoji-support.md
│   │   ├── markdown-syntax.fa.md
│   │   ├── markdown-syntax.fr.md
│   │   ├── markdown-syntax.md
│   │   ├── math-typesetting.md
│   │   ├── papermod
│   │   │   ├── _index.md
│   │   │   ├── papermod-faq.md
│   │   │   ├── papermod-features
│   │   │   │   ├── images
│   │   │   │   │   ├── homeinfo.jpg
│   │   │   │   │   ├── profile.jpg
│   │   │   │   │   └── regular.jpg
│   │   │   │   └── index.md
│   │   │   ├── papermod-icons.md
│   │   │   ├── papermod-installation.md
│   │   │   └── papermod-variables.md
│   │   ├── placeholder-text.md
│   │   └── rich-content.md
│   ├── search.fr.md
│   ├── search.md
│   └── tags
├── LICENSE
├── README.md
├── resources
│   └── _gen
│       ├── assets
│       └── images
├── static
│   ├── android-chrome-192x192.png
│   ├── android-chrome-512x512.png
│   ├── apple-touch-icon.png
│   ├── favicon-16x16.png
│   ├── favicon-32x32.png
│   ├── favicon.ico
│   └── papermod-cover.png
└── themes
    └── hugo-PaperMod
```
