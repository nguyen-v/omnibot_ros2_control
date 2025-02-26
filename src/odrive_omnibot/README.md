
# OmniBot ros2_control package

## Usage Instructions

1. Clone this repository
   ```bash
   git clone git@github.com:nguyen-v/omnibot_ros2_control.git --recursive
   ```

1. Install Dependencies

   ```bash
   rosdep install --from-paths odrive_ros2_control odrive_omnibot -y --ignore-src
   ```

1. Build

   ```bash
   colcon build --symlink-install --packages-up-to odrive_omnibot
   ```

1. Launch

   ```bash
   source ./install/setup.sh
   ros2 launch odrive_omnibot omnibot.launch.py
   ```