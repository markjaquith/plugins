# Elder.js plugins

In this repo you'll find [Elder.js](https://elderguide.com/tech/elderjs/) plugins.

> **NOTE:** All plugins require at least Elder.js V1.0.0.

## Official Plugins:

- [Images](https://github.com/Elderjs/plugins/tree/master/packages/images) Easily add and manage responsive images with your Elder.js website.
- [Markdown](https://github.com/Elderjs/plugins/tree/master/packages/markdown) An extensible markdown parser for [Elder.js](https://github.com/Elderjs/elderjs/) powered by [remark](https://github.com/remarkjs/remark).
- [Critical Path CSS](https://github.com/Elderjs/plugins/tree/master/packages/critical-path-css) Quickly and easily generate and include critical path css for your Elder.js website.
- [Sitemap](https://github.com/Elderjs/plugins/tree/master/packages/sitemap) Automatically generate the latest sitemap for your Elder.js website on build.
- [References](https://github.com/Elderjs/plugins/tree/master/packages/references) Easily add wikipedia style references to your content.
- [Random](https://github.com/Elderjs/plugins/tree/master/packages/random) Easily preview a random page of a route by visiting a single url speeding up design and debugging of large sites.

## Other Plugins:

- [i18n](https://github.com/kiuKisas/elderjs-plugin-i18n) Easily add internationalization to your Elder.js website.
  **NOTE:** This plugin require at least Elder.js v1.2.5.

- [elderjs-plugin-google-fonts](https://github.com/kevmodrome/elderjs-plugin-google-fonts): This plugin fetches fonts from google fonts, generates font-face definitions and inlines those in the head tag.

- [elderjs-plugin-blog-pagination](https://github.com/noxasch/elderjs-plugin-blog-pagination): This plugin help you to easily generate your blog pagination that use @elderjs/plugin-markdown to generate post from markdown.

- [RSS Feed](https://github.com/lukaskawerau/plugin-rss): Add an RSS feed to your Elder.js blog. Requires the [Markdown](https://github.com/Elderjs/plugins/tree/master/packages/markdown) Plugin.

- Have you written a plugin? If so, let us know we'd love to include it here.

## Writing A Plugin:

If you are interested in adding your own plugin the quickest way to do so it to:

```bash
npx degit Elderjs/plugin-template elderjs-plugin
cd elderjs-plugin
```

## Adding Your Plugin:

If you've got a plugin you'd like to see on this page, please create a pull request updating this readme. Thanks!
