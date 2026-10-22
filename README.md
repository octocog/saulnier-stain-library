# Saulnier Stain Library

A browsable photographic reference of the wood flooring stain samples Saulnier
Floors shot on 14 October 2026.

**Live:** https://octocog.github.io/saulnier-stain-library/

319 samples, searchable by color and filterable by collection and species.
Every swatch is cropped to pure grain from the original camera file and served
at 800 by 800 pixels in both JPEG and WebP.

## Layout

```
docs/
  index.html      the catalog, data inlined
  samples.json    the same records as plain data
  img/t/*.webp    320px grid thumbnails
  img/f/*.{jpg,webp}  800px swatches, also the download target
  og.jpg          link preview card
```

## Still open

Some records carry an orange status label because the post it note in the photo
did not give the full picture. They are marked in the catalog and can be
filtered to their own view:

* **needs collection** the species and color are known, the collection is not
* **needs collection and species** only the color name was written down
* **ambiguous label** the note could be read more than one way

One photo, Norwich 0503, would not yield a clean square crop. Norwich 0504
covers the same color.

Source photography and the renaming pipeline live outside this repository.

Designed and maintained by [OctoCog Marketing & Design](https://octocog.com).
