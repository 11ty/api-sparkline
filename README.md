# Sparkline API

A runtime service to generate sparkline SVG images.

## Demo

<img src="https://v1.sparkline.11ty.dev/120x30/41,25,9,12,10,6,12,14,19,17,23,30,36,21,25/%2394b388/" width="120" height="30" alt="Sparkline representing frequency of posts on zachleat.com written from 2007 to 2021">

## Deploy your own

<a href="https://app.netlify.com/start/deploy?repository=https://github.com/11ty/api-sparkline
"><img src="https://www.netlify.com/img/deploy/button.svg" border="0" alt="Deploy to Netlify"></a>

## Usage

Image URLs have the formats:

```
/[height]x[width]/[values]/
/[height]x[width]/[values]/[color]/
```

* `values` is a comma separated list of numbers
* `color` must be URI encoded (via `encodeURIComponent`)
