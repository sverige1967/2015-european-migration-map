# 2015-european-migration-map
An interactive map visualizing connections between cities of origin and destination during the 2015 European Migration Crisis, using GeoJSON data.
# 2015 European Migration Crisis Map

An interactive map project visualizing connections between cities of origin and destination during the 2015 European Migration Crisis.

## Overview

This project represents city-to-city connections related to migration during the 2015 European Migration Crisis. It uses GeoJSON data to represent the relationships between places of origin and destination.

## Dataset

The project includes a GeoJSON file:

- **File:** `2015-avrupa-goc-krizi.geojson`
- **Format:** GeoJSON (`FeatureCollection`)
- **Total features:** 154
- **Geometry type:** `LineString`

Each feature contains the following properties:

| Property | Description |
|---|---|
| `id` | Feature identifier |
| `from` | City of origin |
| `to` | City of destination |
| `name` | Origin-to-destination connection label |

## Map Interpretation

The lines represent connections between cities of origin and destination in the dataset. They should be understood as origin-destination relationships, not necessarily as verified travel routes or exact migration paths.

## Purpose

The aim of this project is to provide a geographical perspective on migration connections during the 2015 European Migration Crisis and make these relationships easier to explore and understand.

## Data Format

The dataset is provided in GeoJSON format and can be used with compatible mapping and geospatial visualization tools.
