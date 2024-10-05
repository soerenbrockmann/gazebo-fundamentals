# gazebo-fundamentals

## Setup on Mac
ulimit -n = 256
Increase to ulimit -n 10240   

brew tap osrf/simulation
brew install gz-ionic
ulimit -n 256

## Run World

# launch server in one terminal
gz sim -v 4 building_robot.sdf -s  # Fortress and Citadel use "ign gazebo" instead of "gz sim"

# launch gui in a separate terminal
gz sim -v 4 -g  # Fortress and Citadel use "ign gazebo" instead of "gz sim"