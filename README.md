# Sparkline API

A runtime service to generate sparkline SVG images.

<!-- ## Deploy

<a href="https://app.netlify.com/start/deploy?repository=https://github.com/11ty/api-sparkline
"><img src="https://www.netlify.com/img/deploy/button.svg" border="0" alt="Deploy to Netlify"></a> -->

## Usage

Image URLs have the formats:

```
/[height]x[width]/[values]/
/[height]x[width]/[values]/[color]/
```

* `values` is a comma separated list of numbers
* `color` must be URI encoded.
