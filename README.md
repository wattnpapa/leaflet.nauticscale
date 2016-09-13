# Leaflet scale control in nautic miles

[![GitHub version](https://badge.fury.io/gh/PowerPan%2Fleaflet.nauticscale.svg)](http://badge.fury.io/gh/PowerPan%2Fleaflet.nauticscale) [![Code Climate](https://codeclimate.com/github/PowerPan/leaflet.nauticscale/badges/gpa.svg)](https://codeclimate.com/github/PowerPan/leaflet.nauticscale) [![Build Status](https://travis-ci.org/PowerPan/leaflet.nauticscale.svg?branch=master)](https://travis-ci.org/PowerPan/leaflet.nauticscale)

Extends the default leaflet scale control based on [jtreml/leaflet.customscale](https://github.com/jtreml/leaflet.customscale) a scale control displaying the scale in nautical miles

## Package Repos

### Bower
```
bower install --save leaflet.nauticscale
```

### NPM
```
npm install --save leaflet.nauticscale
```

## Usage

```
map.addControl(new L.Control.ScaleNautic({
				metric: false,
				imperial: false,
				nautic: true
			}));
```
