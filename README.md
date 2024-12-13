# 2024 election results map

Show election results by precinct on a Folium map.

- Build on field_map.ipynb base Folium map
- County, CD, SD, HD, precinct District boundaries
- Choropleth map layers to show data distributions like # of Dems, turnout, votes
- Layer control to show/hide layers

## Create base Folium map

- basemap layer
  - Cartodb positron
  - center in Boulder County
  - zoom to show all Boulder County
- add layer control

## Add District Boundary layers

- geojson feature layers
  - Boulder precincts
  - Boulder County
  - CD
  - SD
- add styling
- add popups
- add tooltips

## Add data layers

- preliminary Presidential results by precinct
- data/election_results_2024_president_boulder.csv
