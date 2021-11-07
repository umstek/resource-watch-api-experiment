# How to preview

1. Create an account on mapbox.com and [create an API key](https://account.mapbox.com/access-tokens) with default permissions.
2. Rename mapboxAccessToken.example.js to mapboxAccessToken.js and paste your access token in the file.
3. Use any static server to preview the site.  
   e.g.: Install NodeJS, run `npx serve` and visit `http://localhost:3000`

# References

Mostly [ResourceWatch tutorial](https://resource-watch.github.io/doc-api/tutorials.html) but using a [newer Mapbox API](https://docs.mapbox.com/mapbox-gl-js/guides/install/).

# Notes

Mapbox free tier is quite [limited](https://www.mapbox.com/pricing/). We might need to use leaflet.js instead.
