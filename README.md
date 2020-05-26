# ORB_SLAM
Gitee.com



### Done:

- remove pangolin;
- publish pose and pointclouds in map coordinate;
- save map and load each submap in system;
- publish the OccupancyGrid-map to submap for navigation;
- when system get relocalization, re-draw the OccupancyGrid-map;
- switch submap by reloaclization in the map_set which loads all the submap in it.

### TODO:

- In Localizaiton Mode, need to open the LocalMapping thread;
- merge each gridmap into a whole map and publish in the rviz for navigation 
- ...

