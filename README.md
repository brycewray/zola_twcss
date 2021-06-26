# Zola starter set

This is a starter set for the [Zola](https://getzola.org) [static site generator (SSG)](https://www.jamstack.org/generators), based on the appearance of my website at [brycewray.com](https://www.brycewray.com).

See the [online demo](https://zola-solo.vercel.app/).

## How to use

1. Clone this to a local repo.
2. Make appropriate changes to `config.toml` to conform to your site’s parameters.
3. Once you have [installed Zola](https://www.getzola.org/documentation/getting-started/installation/), run `zola serve` from your terminal app. You can then [view the site on your computer](https://www.getzola.org/documentation/getting-started/cli-usage/#serve).
4. Read the sample posts and their Markdown files to see how everything works.
5. Edit the content to make it your own!
6. When ready, [deploy the site](https://www.getzola.org/documentation/deployment/overview/) to your chosen host.

## What’s under the hood

- Zola’s [built-in image processing capabilities](https://www.getzola.org/documentation/content/image-processing/). (The **real** site’s repo uses [Cloudinary](https://cloudinary.com) rather than having the images in the repo and processing them as such.)
- [SCSS](https://sass-lang.com/) through [Zola’s built-in support](https://www.getzola.org/documentation/content/sass/).

## Handling footnotes

Please see `/content/about/index.md` for information concerning how Zola handles footnotes, since this is different than you’ll likely find on other SSGs.

*Effective 2021-06-25, development on this repository will be* ***on hold*** *at least until Zola is compatible with [Dart Sass](https://sass-lang.com/dart-sass) rather than the [deprecated Libsass](https://sass-lang.com/blog/libsass-is-deprecated) (see [Zola issue #1083](https://github.com/getzola/zola/issues/1083)).*