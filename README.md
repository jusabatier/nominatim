Nominatim ADDON
===============

author: @jusabatier

The addon config should look like this:

    {
		"id": "nominatim_0",
		"name": "Nominatim",
		"title": {
			"en": "Nominatim search (OSM)",
			"es": "Buscar a través Nominatim (OSM)",
			"fr": "Recherche via Nominatim (OSM)"
		},
		"description": {
			"en": "Nominatim search (OSM)",
			"es": "Buscar a través Nominatim (OSM)",
			"fr": "Recherche via Nominatim (OSM)"
		},
		"options": {
			"serviceURL": "http://nominatim.openstreetmap.org/search",
			"target": "tbar_11",
			"boundingbox": "3.6239646,45.140811,4.0492900,44.874466",
			"minAccuracy": 0,
			"limit": 100,
			"cutFrom": ", Haute-Loire"
		},
		"preloaded": true
	}

Options
========

Mandatory options:
 * **serviceURL** - points to the nominatim service to use
 * **boundingbox** - bounding box where restrict the search
 * **minAccuracy** - minimum accuracy for results
 * **limit** - maximum number of results
 * **cutFrom** - Some text to find in the display_name from where to cute (the text is also cutted)
