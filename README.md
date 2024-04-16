Para accionar el robot pueden usarse los siguiente comandos
roslaunch qhali_bringup qhali_no_sensors.launch : es para operar los brazos y roboclaw, no la parte de navegaci[on aut[onoma
roslaunch qhali_bringup qhali_remote.launch : solo activa la parte de los sensores ultrasonido y el modelo 3D para navegaci[on
roslaunch qhali_bringup qhali_robot.launch : activa todo (brazos y navegaci[on)

DEPENDENCIAS
- map_server
- rviz
- move_base
