how to set up visulization using ros \
1 run: \
ros run lanelet2_io convert_osm \
  ~/maps/laneletmapfinal.osm \
  ~/maps/laneletmapfinal.osm.bin \
2: \
  add map to ~/ros_ws/src/shuttle_navigation/maps/laneletmapfinal.osm.bin /n
3: /n
  change username in launch final to username of system /n 
4: /n
  launch final in ros /n 
        1: soure workspace /n
              cd ~/ros2_ws /n
              colcon build /n
              source install/setup.bash
        2: run 
          ros launch shuttle_navigation load_map.launch.py
5: try and visualize in RViz
    ros run rviz2 rviz2
    add by display type to lanelet2 
    point to loaded map in /map
    
    
