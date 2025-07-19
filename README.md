# Hugo Lost

A simple theme for Hugo, based on *Hugo Zen*.

It can do dark/light switch: dark mode is based the [everforest dark theme](https://github.com/sainnhe/everforest),
light mode loosely based on Rosé Pine Dawn.

Hugo Lost is a departure from [Hugo Zen](https://github.com/rakuishi/hugo-zen),
adding a few bits I needed for my sites
[Lost Among Notes](https://blog.silvela.org/) and Lost Among Europeans, and simplifying
the CSS.

## Installation & Usage

Best used as a submodule in your hugo project.

``` sh
git submodule add https://github.com/jsilvela/hugo-lost themes/lost
```

followed by `init`, `update` ... the usual.

## Styling with CSS

This theme includes some basic styling, in the form of a CSS file
`assets/css/custom.css`. It is expected that the users of this theme may add
a file called `assets/css/extra.css` in their site folder. This theme's layout
contiains code to concatenate `extra.css` and `custom.css` preserving the
priority for `extra.css`, and to generate a single file `main.css` to be
referenced in the HTML head section.

## Configuration

Some values from your top-level Hugo site config will be used by this theme,
for the footer, analytics, copyright.

``` toml
[params]
  copyright = "Name of copyright holder"
  github   = "github handle"
  email     = "owner email"
  goatcounter = "goatcounter URL"
  mastodon   = "mastodon handle"
  bluesky   = "bluesky handle"
  twitter   = "twitter handle"
```

## License

MIT License

## Author

[Jaime Silvela](https://github.com/jsilvela), acknowledging the debt to
[OCHIISHI Koichiro](https://github.com/rakuishi/)
