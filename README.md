# Cesium Bonus Flight Tracker

# Live demo:
https://eientk88.github.io/Cesium-Bonus-Flight-Tracker/

# Overview

This project is a 3D flight visualization built with CesiumJS. It animates a flight route from PDX (Portland, Oregon) to Osaka, Japan on a real-time 3D globe using time-based position samples and a 3D aircraft model.

The application is hosted as a static website on GitHub Pages.

CesiumJS enables developers to visualize geospatial data on a high-precision 3D globe in the browser.

# Features

1. Airplane point following a flight path

2. Animated route using SampledPositionProperty

3. Global terrain and satellite imagery

4. Additional imagery layers (night lights and nautical seamarks)

5. Split-view interface:

    (a) Main view tracking the aircraft

    (b) Mini-map showing the full route overview

6. Camera animation and smooth interpolation along the route

# Technologies

CesiumJS

JavaScript

HTML / CSS

Cesium ion (terrain, imagery, and 3D assets)

GitHub Pages for deployment

# How It Works

The flight path is defined as a series of time-stamped longitude, latitude, and altitude samples. Cesium interpolates these positions and animates the aircraft across the globe while updating the camera and route visualization.

# Author

Athanasios Karageorgos

Oregon State University

3/4/2026

# Credits

Based on the CesiumJS “Build a Flight Tracker” tutorial, adapted to run as an independent website with additional visualization features.
