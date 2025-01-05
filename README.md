# roadster

A clean, responsive Hugo theme focused on content, forked from the original [Mainroad theme](https://github.com/mansoorbarri/roadster).

**[Demo](https://roadster-hugo.pages.dev/)** • **[Documentation](https://roadster-hugo.pages.dev//docs/)**

![screenshot](https://raw.githubusercontent.com/mansoorbarri/roadster/master/images/screenshot.png)

## Issues fixed from the original theme: 
- [SVG added to mainmenu via "pre" changes colour depending on sidebar visible or not #388](https://github.com/mansoorbarri/roadster/issues/388)
- [ Lighthouse isn't happy with the contrast of hyperlinks in the footer #385 ](https://github.com/mansoorbarri/roadster/issues/385)
- [ Authorbox relies on [Author] configuration, but it's being deprecated. #382 ](https://github.com/mansoorbarri/roadster/issues/382)

## Features

+ Responsive design
+ Configurable theme settings (sidebar position, author box, post navigation, highlight color)
+ Widgetized sidebar
+ Translations (15+ languages)
+ Hugo internal templates (Open Graph, Schema, Twitter Cards, Disqus, Google Analytics)
+ Table of Contents, MathJax support, SVG icons
+ Custom Google Fonts support
+ Wide cross-browser compatibility

## Quick Start

1. Install Hugo following the [official guide](https://gohugo.io/getting-started/quick-start/#step-1-install-hugo)
2. Create a new site and navigate to its root directory
3. Install the theme:
```
git clone https://github.com/mansoorbarri/roadster.git themes/mainroad
```
Or as a submodule:
```
git submodule add https://github.com/mansoorbarri/roadster.git themes/mainroad
```
4. Add to your `config.toml`:
```
theme = "mainroad"
```

For detailed configuration options and examples, please visit the [documentation](https://roadster-hugo.pages.dev//docs/).

## Contributing

Found a bug or have an idea for a new feature? Feel free to open an issue or PR. 

## License

Released under the [GPLv2 license](https://github.com/mansoorbarri/roadster/blob/master/LICENSE.md).
