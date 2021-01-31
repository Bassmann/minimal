# Minimal

This is a fork of the original minimal Personal blog theme powered by
[Hugo](https://gohugo.io). I want to change a few things e.g. remove unneccessary java
script, hence the fork.

A live demo of the original theme is available [here](https://themes.gohugo.io/theme/minimal/).

## Installation

In the past themes were installed as submodules. This is no longer recommended. Better add it as a [hugo module](https://gohugo.io/hugo-modules/use-modules/).

## Configuration

After installation, take a look at the `exampleSite` folder inside `themes/minimal`.

To get started, copy the `config.toml` file inside `exampleSite` to the root of your Hugo site:

```
$ cp themes/minimal/exampleSite/config.toml .
```

Now edit this file and add your own information. Note that some fields can be omitted.

I recommend you use the theme's archetypes so now delete your site's `archetypes/default.md`.

## Features

You can tweak the look of the theme to suit your needs in a number of ways:

- The accent colour can be changed by using the `accent` field in `config.toml`.

- You can also change the background colour by using `backgroundColor`.

- Add colored 5px borders at the top and bottom of pages by setting `showBorder` to `true`.

For best results, I recommend you use a dark accent colour with a light background, for example:

```toml
[params]
    accent = "red"
    showBorder = true
    backgroundColor = "white"
```

### Fonts

The theme uses [Google Fonts](https://fonts.google.com) to load its font. To change the font:

```toml
[params]
    font = "Raleway" # should match the name on Google Fonts!
```

### Syntax highlighting

The theme supports syntax highlighting using the standard hugo highlighting by means of the [hugo shortcode](https://gohugo.io/content-management/syntax-highlighting/#highlight-shortcode).
