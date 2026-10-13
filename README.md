# wp8_emdb

e-MDB version for the edutainment and museum experiments, derived from <https://github.com/pillar-robots/wp5_gii>.

## Installation

To install the software of e-MDB, firstly it’s necessary to create a ROS workspace and clone this repository:

```bash
cd ~
git clone https://github.com/pillar-robots/wp8_emdb.git
```

Finally, you have to compile the ROS workspace:

```bash
cd ~/wp8_emdb/
source /opt/ros/humble/setup.bash
colcon build --symlink-install
```
