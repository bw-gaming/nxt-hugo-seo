# Blue Window SEO Hugo theme component

A lightweight Hugo theme component that leverage json seo output for post processing

## Features

- Generate json (extension :.seo) file with SEO information for each page

Optional features:

- Show summaries on homepage
- Schema.org, Open Graph and Twitter Cards metadata
- Utterances comments widget
- CSS and JS can be [dynamically embedded](#dynamically-embedded-css-and-js) with shortcodes
- Built-in shortcodes:
  - Netlify contact form
  - On-click Soundcloud player


## Installation

From the website root:

```bash
git submodule add https://github.com/bw-gaming/nxt-hugo-seo.git themes/nxt-hugo-seo
```

The theme must be set in the website config:

```javascript
"theme": [
      "nxt-hugo-seo",
      "hugo-flex"
     ]
```

Then the extra output format should 

## Updating

From the website root:

```bash
git submodule update --remote --rebase
```

## License

[MIT](LICENSE.md)
