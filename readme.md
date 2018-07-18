# A comparison of several plotting techniques for Jupyter Notebooks compared. 

if you miss a repo please PR. 


## Geopandas

Pros:
1. Simple.  
1. No API keys required.  

Cons:
1. Static. 
1. No tooltip.

## Folium

Pros:
1. Open Source
1. Fair inter operability with geopandas.
1. Customizable.

Cons:
1. Data is all client side. 
1. No vector tiles.
1. Fails with larger datasets.

## MapboxGL for Jupyter

Pros:
1. Vector tiles.
1. 3D.
1. WebGL power.
1. Useful tools to generate colormaps.
1. use client side data for choropleth maps.

Cons:
1. API key required
1. Choropleth maps created with join method have a limited tooltip. 
1. Need to convert data into JSON.
1. No layered approach (yet).

## Cartoframes

Pros:
1. Vector tiles.
1. Querable.
1. Choropleth and tooltips supported.
1. Can handle server side and client side data layers.

Cons:
1. In alpha stage.
1. 2D only. 
1. How to combine server and client side data in one map. 

## Other
1. cartopy. Good for printing static maps.
1. ... please add PR. 


