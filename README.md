# qgis_model_AffectedBuildings
QGIS model to determine affected buildings on land parcels that are a travel distance from some event

Affected Buidlings
Displays buildings affected by some event within a distance from the event location. 
The affected buildings are determined by 
• travelling a distance along the road network from the event location, 
• buffering the travel distance to intersect land parcels, 
• extracting building footprints that that intersect the land parcels.



For QGIS 3+

Requires https://github.com/pgssimon/qgis_pick_a_point
