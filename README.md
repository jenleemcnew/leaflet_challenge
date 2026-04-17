# USGS Earthquake Visualization

## Overview
An interactive map visualization of real-time earthquake data sourced from the 
United States Geological Survey (USGS) GeoJSON feed. Built with Leaflet.js, the 
map plots global earthquake activity with markers scaled by magnitude and colored 
by depth, updated every 5 minutes from live USGS data.

---

## Features

### Part 1 — Earthquake Visualization
- Live earthquake data pulled from the USGS GeoJSON feed
- Markers scaled by earthquake magnitude
- Marker color reflects earthquake depth (darker = deeper)
- Popups with detailed earthquake information on click
- Map legend providing depth color context

### Part 2 — Tectonic Plates Overlay
- Tectonic plate boundaries plotted alongside earthquake data
- Multiple base map options
- Independent layer toggles for earthquakes and tectonic plates
- Layer controls for customized viewing

---

## Tech Stack
- JavaScript
- Leaflet.js
- HTML / CSS
- USGS GeoJSON API

---

## Data Sources
- [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)
- [Tectonic Plates Dataset](https://github.com/fraxen/tectonicplates)

---

## Repository Structure
| Folder | Description |
|--------|-------------|
| `Leaflet-Part-1/` | Core earthquake visualization |
| `Leaflet-Part-2/` | Extended map with tectonic plates and layer controls |
