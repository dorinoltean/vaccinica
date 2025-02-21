# Vaccinica

Downloads and presents covid data publicly available from data.gov.ro

http://bit.ly/vaccinica

Explore https://data.gov.ro/dataset/transparenta-covid data and get informed
of the available vaccination statistics in Romania. Would be nice to receive
data pre March 2020.

Please review the code to help me fix potential mistakes.

## Running locally

Automatically download and convert the data from data.gov.ro

```
yarn install
yarn download
yarn dl2json
```

Serve `docs` folder though a http server

```
cd docs && python -m SimpleHTTPServer 8000
google-chome http://localhost:8000
```

## Roadmap

* [x] show chart
* [x] download data with a script
* [x] github pages
* [x] filter counties
* [x] filter cities
* [x] filter centers
* [x] filter categories
* [x] filter doses
* [x] persist hidden states
* [x] filter cities/centers depending on current selection
* [x] shortcut for selecting all categories grouped by their number (example: select III-a with one click)
* [ ] positive messages
* [ ] estimate how long until you get vaccinated
* [ ] persist state in query params
* [ ] ability to select time frame
* [ ] split per months
* [ ] show more statistics, perscentages etc

## Thanks

* https://data.gov.ro/dataset/transparenta-covid
* https://github.com/chartjs/Chart.js
* https://github.com/nagix/chartjs-plugin-colorschemes
* https://github.com/LCweb-ita/LC-select
* https://github.com/DiegoZoracKy/convert-excel-to-json/
* https://loading.io/
