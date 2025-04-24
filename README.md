# Oceans & Seas GeoJSON/TopoJSON

[![Downloads](https://img.shields.io/npm/dm/oceans-seas.geojson.svg?style=flat-square)](https://www.npmjs.com/package/oceans-seas.geojson)
[![Size](https://img.shields.io/bundlephobia/minzip/oceans-seas.geojson.svg?style=flat-square)](https://bundlephobia.com/result?p=oceans-seas.geojson)
[![version](https://img.shields.io/npm/v/oceans-seas.geojson.svg?style=flat-square)](https://www.npmjs.com/package/oceans-seas.geojson)
[![MIT License](https://img.shields.io/npm/l/oceans-seas.geojson.svg?style=flat-square)](https://github.com/alvinometric/oceans-seas.geojson/blob/main/LICENSE)

The world's oceans and seas boundaries in GeoJSON and TopoJSON formats.

## Data Sources

The data is sourced from [Marine Regions](https://www.marineregions.org/), licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/).

Flanders Marine Institute (2018). IHO Sea Areas, version 3. Available online at https://www.marineregions.org/ https://doi.org/10.14284/323

## Installation

```bash
npm install oceans-seas.geojson
```

## Usage

```javascript
import map from "oceans-seas.geojson";
```

The name of each sea/ocean is in the `NAME` property of its GeoJSON feature.

For the TopoJSON file:

```javascript
import map from "oceans-seas.geojson/topojson";
```

## Creating a custom GeoJSON/TopoJSON file

1. Download the [World_Seas_IHO_v3](https://www.marineregions.org/downloads.php) shapefile from Marine Regions to the root directory of this repository.
2. Unzip the file.
3. Adjust the scripts in `package.json` (e.g. filter other fields or change the simplification level).
4. Run the build script.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
