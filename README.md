# my_stdr_ctrl
Uses setablished stdr command code (see stdr_control src/ stdr_open_loop_commander.cpp)
runs a robot up to the upper left corner of the map then does a dance
## Example usage
`roslaunch stdr_launchers server_with_map_and_gui_plus_robot.launch`
to start the simulator.  Run a simple, open-loop command sequence with:
`rosrun my_stdr_ctrl my_stdr_open_loop_commander`

    
