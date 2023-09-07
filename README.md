# RailPoints
This is a point cloud database specifically for point cloud segmentation in railway scene called RailPoints, it consists of 120 frames captured from four representative railway scenes, comprising over 1 million 3D point cloud data.
We used LiDAR to capture point cloud centered on four types of railway scenes in Nanjing, covering up to 10 kilometers railway tracks, and more than 25,000 square meters of railway scenes. We manually annotate the point cloud in the database into five semantic categories, and gave the labeling specifications of each category:1) Terrain, 2) Track, 3) Pedestrian, 4) Vegetation, and 5) Artifact.
The web-based point cloud tagging tool Semantic Segmentation Editor, an open-source web-based solution. Each point's annotation information comprises four values: the first three representing the XYZ spatial position of the point, and the fourth denoting the category label of the point (0-4). The specific semantic rules for the five categories are as follows:
1) Terrain: Various non-transparent artificial and natural surfaces, including grass, concrete, gravel roads, sandy areas, etc. 
2) Track: Railway tracks for trains, light rails, subways, etc., consisting of straight track and curved track. The appearance of a straight is a long straight strip, with parallel sections on both sides that are significantly higher than the ground, and a solid section in the middle that is slightly concave. Since the curved tracks are far away from the LiDAR, they will be blocked to a certain extent. The appearance of the curved tracks is two parallel slender curves with a certain arc.
3) Pedestrian: People in the railway scene. Its appearance is significantly higher than the ground, and it is clearly separated from the rest of the category. 
4) Vegetation: This category includes trees, shrubs, and hedges etc. Its appearance is an irregularly shaped point above the ground. 
5) Artifact: This category includes man-made objects such as fences, barriers, utility poles, streetlights, and road signs etc. Its appearance is a series of more regular points above the ground, most of which are planar or columnar.
The number of point clouds of the five categories in the RailPoints database is listed in the table below:
Terrain	Track	Pedestrian	Vegetation	Artifact	All
309980	327431	8723	278195	93624	1017953




![)1VHHJD`AIQ4NTZ`}8V~03U](https://github.com/1999rockclimber/RailPoints/assets/139934658/ab5b31da-a6fb-44dd-9364-45596f30d9a4)

![9N$6$5HBKI$4)XQBW% K7$F](https://github.com/1999rockclimber/RailPoints/assets/139934658/d7db6947-e0a9-4815-816a-83732c348b6b)

