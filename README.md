# Earthquake, Plate Tectonics and Active Faults: ArcGIS Instant App

An interactive web app that lets students view recent earthquakes, active fault lines and tectonic plate boundaries anywhere in the world.

**Live app:** https://uigis.maps.arcgis.com/apps/instant/sidebar/index.html?appid=25d5cb7ac7274307b043f72b531e20bb

![App interface](./images/fig-3-6-app-interface.png)

## Background
The scenario is an educational one: a secondary school science teacher wants his students to explore earthquakes on a map, alongside tectonic plates and fault lines. The scenario is fictional, but the data is real.

## Aim
Build a web app where students can view recent earthquakes, active faults and tectonic boundaries, and see where they are.

## Study area
The whole world.

## Tools
- ArcGIS Online (browser-based; no installation needed)
- ArcGIS Instant Apps, **Sidebar** template

## Data
All layers come from the **ArcGIS Living Atlas of the World**:
- *Global Earthquakes* web map (Esri Training Services)
- *Recent Earthquakes* layer (Esri)
- Active fault and tectonic plate boundary layers

## Method
1. **Create an account** and sign in to ArcGIS Online.
2. **Open a map.** Search for *global earthquakes*, open the web map, save it as a new map and add tags and a summary.
3. **Add data.** Search for *recent earthquakes* and add the Esri layer.
4. **Configure layer properties.** Style *Events by Magnitude* so stronger earthquakes stand out on the map.
5. **Select an app template.** Create an app from the **Sidebar** template and title it *Earthquake Research*.
6. **Configure in Express mode.** Set the app title, add a text alternative for the map, turn on the Shortcuts Menu, add details text, choose the Light mode and *Ocean* theme.
7. **Publish.** Publish the app, set sharing to *Everyone (Public)* and share the link.

## Result
About 70 recent earthquakes showed up across Africa at the time the data was loaded. Clicking an earthquake shows a short summary, and a link in the pop-up leads to the USGS page for more detail. Active faults are shown on the same map.

## Future work
The app only reflects the data as it was when I built it. A future version should update itself automatically when new earthquakes occur.

## Author
Adebayo Ilias Akinola, Department of Surveying and Geoinformatics, FUTA.
