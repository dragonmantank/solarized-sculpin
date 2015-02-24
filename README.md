# Solarized Sculpin

This is a basic theme for Sculpin, which uses the [Solarized](http://ethanschoonover.com/solarized) color scheme.

To use, extract these files into `source/themes/dragonmantank/solarized-sculpin` and add the following to `app/config/sculpin_kernel.yml`:

```
sculpin_theme:
    theme: dragonmantank/solarized
```

## Overriding

You can override the theme defaults by creating the appropriate file structure in your `source/` directory. For example, to override the default navigation bar, you can create the a folder at `source/_includes/`, copy over `source/themes/dragonmantank/solarized/_includes/navigation.html` into that new folder, and edit it to your heart's content.

## Components

This theme uses [Foundation 5](http://foundation.zurb.com/) and [highlight.js](https://highlightjs.org/).