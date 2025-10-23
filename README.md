how to set up visulization using ros
first run:
ros2 run lanelet2_io convert_osm \
  ~/maps/laneletmapfinal.osm \
  ~/maps/laneletmapfinal.osm.bin
next add map to ~/ros2_ws/src/shuttle_navigation/maps/laneletmapfinal.osm.bin
