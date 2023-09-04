This folder contains the interactive maps developed as part of Shuying's dissertation.

(1)
Files named as eps_num1_minPts_num2.html are interactive maps showing the clustering results for alcohol outlets (using the union of circle as boundaries). These maps were generated using the DBSCAN algorithm with specific settings:

eps=num1: The radius (in the same unit as the data) that DBSCAN uses to search for neighboring data points. A smaller value means that only points very close to each other will be considered part of the same cluster.

minPts=num2: The minimum number of points required to form a cluster. A higher value will result in fewer but more densely packed clusters.

For example, a file named eps_50_minPts_2.html used an eps value of 50 and a minPts value of 2 in the DBSCAN algorithm to create the map. 


(2)
The PolygonCluster.html file is an interactive map that shows clustering results for alcohol outlets using polygons to outline cluster boundaries. This map is generated using the DBSCAN algorithm with specific parameters eps=100 & minPts=3.

(3)
IMD_Manchester.html: This interactive map showcases the LSOA (Lower Layer Super Output Areas) polygons in the Manchester region, colored according to the IMD (Index of Multiple Deprivation) Decile for each LSOA. The map aims to explore the relationship between alcohol outlet clusters and IMD within Manchester.

AHAH_Manchester.html: Similarly, this interactive map features the LSOA polygons in the Manchester area and are colored based on the AHAH (Access to Healthy Assets and Hazards) index. The purpose is also to investigate the connection between alcohol clusters and AHAH in the area.

To view these maps, simply double-click on the desired html file.





