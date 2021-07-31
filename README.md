# ar600_description
XACRO & URDF model for humanoid robot AR600

![](https://pp.userapi.com/c845017/v845017403/3197/57ENEIq1Ag8.jpg)

---

## Features:
 - XACRO model of robot
 - Visual and collision meshes
 - Mass, CoMs and inertia properties
 - Gazebo-ready


## Examples
### Show model in RViz
You need our [urdf_viz](https://github.com/vstuhumanoid/urdf_viz) package.
```bash
$ roslaunch urdf_viz xacro.launch filename:=~/<ros workspace>/src/ar600_description/xacro/ar600.xacro
```

### Show model in Gazebo
```bash
$ roslaunch ar600_description gazebo.launch
```

### Spawn more robots to Gazebo!
```bash
$ roslaunch ar600_description spawn model:=one_more_robot z:=5
```
