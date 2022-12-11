# Rekayasa Data Spasial

repository ini merupakan buku dokumentasi kehidupan Rekayasa Data Spasial dan rekayasadata.co.uk. Powered by ```jupyter-book```.

Repository ini merupakan _source code_ dari [https://tentang.rekayasadata.co.uk](https://tentang.rekayasadata.co.uk) 

## Building the book

1. buat virtual environment dan install ```jupyter-book```. _command_ ```python3 -m venv venv``` direkomendasikan karena folder ```venv``` masuk dalam ```.gitignore```.
2. invoke ```jupyter-book build about```.
3. static HTML ada pada ```./about/_build/html``` dan ini dapat dideploy dalam web-server

selebinya dapat baca dokumentasi ```jupyter-book```.

## Lingkup Kerja

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {},
      "geometry": {
        "coordinates": [
          [
            [
              92.48263483299615,
              11.094137330375759
            ],
            [
              92.48263483299615,
              -11.220094749945346
            ],
            [
              141.48427558462492,
              -11.220094749945346
            ],
            [
              141.48427558462492,
              11.094137330375759
            ],
            [
              92.48263483299615,
              11.094137330375759
            ]
          ]
        ],
        "type": "Polygon"
      }
    }
  ]
}
```