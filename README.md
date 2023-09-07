# RailPoints
This is a point cloud database specifically for point cloud segmentation in railway scene called RailPoints, it consists of 120 frames captured from four representative railway scenes, comprising over 1 million 3D point cloud data.Based on the results, we also propose 按enhanced point cloud segmentation neural networks called RPSN, improving their overall effectiveness for railway point cloud segmentation. Our evaluation and analysis reveal that formulating point cloud shape features and selecting feature hierarchies for different categories significantly impact railway point cloud segmentation task accuracy and efficiency.The RailPoints dataset and the improved segmentation networks proposed herein can facilitate research and development of applications such as railway detection, augmenting the development and application of point cloud-based 3D object detection in railway transportation.
We used LiDAR to capture point cloud centered on four types of railway scenes in Nanjing, covering up to 10 kilometers railway tracks, and more than 25,000 square meters of railway scenes. We manually annotate the point cloud in the database into five semantic categories, and gave the labeling specifications of each category:1) Terrain, 2) Track, 3) Pedestrian, 4) Vegetation, and 5) Artifact.
The web-based point cloud tagging tool Semantic Segmentation Editor, an open-source web-based solution. Each point's annotation information comprises four values: the first three representing the XYZ spatial position of the point, and the fourth denoting the category label of the point (0-4). The specific semantic rules for the five categories are as follows:
1) Terrain: Various non-transparent artificial and natural surfaces, including grass, concrete, gravel roads, sandy areas, etc. 
2) Track: Railway tracks for trains, light rails, subways, etc., consisting of straight track and curved track. The appearance of a straight is a long straight strip, with parallel sections on both sides that are significantly higher than the ground, and a solid section in the middle that is slightly concave. Since the curved tracks are far away from the LiDAR, they will be blocked to a certain extent. The appearance of the curved tracks is two parallel slender curves with a certain arc.
3) Pedestrian: People in the railway scene. Its appearance is significantly higher than the ground, and it is clearly separated from the rest of the category. 
4) Vegetation: This category includes trees, shrubs, and hedges etc. Its appearance is an irregularly shaped point above the ground. 
5) Artifact: This category includes man-made objects such as fences, barriers, utility poles, streetlights, and road signs etc. Its appearance is a series of more regular points above the ground, most of which are planar or columnar.
The number of point clouds of the five categories in the RailPoints database is listed in the table below:
Terrain	| Track  | Pedestrian | Vegetation | Artifact	|   All
309980	| 327431 |	  8723	  |  278195	   |  93624	  | 1017953

The visualization of some point clouds in the database is as follows:
![image](https://github.com/1999rockclimber/RailPoints/assets/139934658/f46572a0-3eba-46b5-b719-5e2ba99cab9f)

Within this visualization, the Terrain category is represented by brown points, the Track category by blue points, the Pedestrian category by red points, the Vegetation category by green points, and the Artifact category by yellow points.

If you need the specific data content of the RailPoints database, please consult these emails for more details:ssmytxdy@gmail.com


