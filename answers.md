Q1 https://shiny-space-yodel-v6qw7rv6x6pj369p7-8080.app.github.dev/geoserver/ows?service=WMS&version=1.3.0&request=GetCapabilities
Q2 https://shiny-space-yodel-v6qw7rv6x6pj369p7-8080.app.github.dev/geoserver/ows?service=WFS&acceptversions=2.0.0&request=GetCapabilities
Q3 See file "Q3 Updated WFS Layer Preview"
Q4 The The first item in a drawing order list is the layer on top, the last item in the layer on bottom
Q5 See file "Q5 Layer List"
Q6 https://shiny-space-yodel-v6qw7rv6x6pj369p7-8080.app.github.dev/geoserver/wms?SERVICE=WMS&VERSION=1.1.1&REQUEST=GetMap&FORMAT=image%2Fpng&TRANSPARENT=true&STYLES&LAYERS=spearfish&exceptions=application%2Fvnd.ogc.se_inimage&SRS=EPSG%3A26713&WIDTH=768&HEIGHT=539&BBOX=592907.2697692281%2C4915841.091629405%2C607566.7502657436%2C4926129.450988287
Q7 256x256 https://shiny-space-yodel-v6qw7rv6x6pj369p7-8080.app.github.dev/geoserver/wms?SERVICE=WMS&VERSION=1.1.1&REQUEST=GetMap&FORMAT=image%2Fpng&TRANSPARENT=true&tiled=true&STYLES&LAYERS=spearfish&exceptions=application%2Fvnd.ogc.se_inimage&tilesOrigin=589425.9342365642%2C4913959.224611808&WIDTH=256&HEIGHT=256&SRS=EPSG%3A26713&BBOX=601038.7003571391%2C4920698.953330398%2C605925.1938559776%2C4925585.446829236
Q8 https://shiny-space-yodel-v6qw7rv6x6pj369p7-8080.app.github.dev/geoserver/gwc/service/wmts?layer=spearfish&style=&tilematrixset=EPSG%3A4326&Service=WMTS&Request=GetTile&Version=1.0.0&Format=image%2Fpng&TileMatrix=EPSG%3A4326%3A13&TileCol=3473&TileRow=2
Q9 TileCol=3473 & TileRow=2
Q10 TileCol=3468 & TileRow=2
Q11 They act as a coordinate system for a tile image at a certain zoom level. The same point can have a different tilecol and tile row as the image is zoomed in or out
Q12 There is no difference in the tile matrix, yes %3A is an HTML encoding for a colon, espg is a coded number for a coordinate system reference 
