# Campus-simulation

# Comado que copia o arquivo de uma origem para a pasta de /worlds
sudo cp pasta_origem /opt/ros/kinetic/share/turtlebot_gazebo/worlds

# Comando que inicializa o cenário
roslaunch turtlebot_gazebo turtlebot_world.launch world_file:=/opt/ros/kinetic/share/turtlebot_gazebo/worlds/campus.world
