## droneTools

File replacement:

- For husky_description folder
```bash
  sudo cp -r husky_description /opt/ros/<ros_distro>/share/
  ```

- For iris & iris_opt_flow folders
```bash
  cp -r iris path_to_Firmware/Tools/sitl_gazeb/models/
  cp -r iris_opt_flow path_to_Firmware/Tools/sitl_gazebo/models/
  ```
- For launchFirmware folder
```bash
  cp -r launchFirmware/* path_to_Firmware/launch/
  ```
- For velodyne_simulator folder
```bash
  cp -r velodyne_simulato/velodyne_description your_ROS_ws/src/velodyne_simulator/
  ```
- For worlds folder
```bash
  cp -r worlds path_to_Firmware/Tools/sitl_gazebo/
  ```
