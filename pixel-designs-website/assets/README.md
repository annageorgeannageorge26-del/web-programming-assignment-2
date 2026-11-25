# Assets folder

This folder is where all images and media for the Pixel Designs site live,
so the HTML/CSS never needs to change when you swap placeholder graphics
for real photography.

```
assets/
  img/
    logo-mark.svg       — brand mark (5x5 pixel-grid "P"), used in header + footer
    favicon.svg         — browser tab icon, same mark on a dark tile
    icons/
      tv.svg            — Television service icon
      video.svg         — Digital video / YouTube service icon
      web.svg           — Websites service icon
      transit.svg       — Public transport service icon
      mall.svg          — Malls & retail service icon
```

## What's here now

Every file above is an original, hand-built SVG (no stock photography or
third-party icon packs), so the site works out of the box with zero
licensing questions.

## Adding your own photography

The design deliberately keeps the hero and services sections illustration-led
(the animated pixel-grid graphic) rather than photo-led, so it renders
identically for every visitor with no load-time cost. If you'd like to add
real campaign photography — billboards in the wild, a mall activation, a
studio shoot — drop files in here using this pattern and reference them from
`index.html` / `css/style.css`:

```
assets/img/photos/hero-banner.jpg      (recommended: 1600x1600, WebP or JPG)
assets/img/photos/channel-tv.jpg
assets/img/photos/channel-video.jpg
assets/img/photos/channel-web.jpg
assets/img/photos/channel-transit.jpg
assets/img/photos/channel-mall.jpg
```

Keep photography licensed for commercial use (your own campaign shots, or a
paid stock library) — Pixel Designs is a real client-facing site, so treat
every image as something you have the rights to publish.
