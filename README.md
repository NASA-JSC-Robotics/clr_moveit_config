# ChonkUR L Rail-E (CLR) MoveIt Configuration

[MoveIt 2](https://github.com/moveit/moveit2) configurations for [ChonkUR L Rail-E (CLR)](https://github.com/NASA-JSC-Robotics/chonkur_l_raile).

## Usage

A MoveIt RViz widget can then be launched with:

```bash
ros2 launch clr_moveit_config clr_moveit.launch.py

# Or to include the environment mockups
ros2 launch clr_moveit_config clr_moveit.launch.py include_mockups_in_description:=true

# If using a simulator, such as MuJoCo, use simulation time
ros2 launch clr_moveit_config clr_moveit.launch.py include_mockups_in_description:=true use_sim_time:=true
```

## Citation

This project falls under the purview of the iMETRO project.
If you use this in your own work, please cite the following paper:

```bibtex
@INPROCEEDINGS{imetro-facility-2025,
  author={Dunkelberger, Nathan and Sheetz, Emily and Rainen, Connor and Graf, Jodi and Hart, Nikki and Zemler, Emma and Azimi, Shaun},
  booktitle={2025 22nd International Conference on Ubiquitous Robots (UR)},
  title={Design of the iMETRO Facility: A Platform for Intravehicular Space Robotics Research},
  year={2025},
  volume={},
  number={},
  pages={390-397},
  keywords={NASA;Moon;Seals;Maintenance engineering;Maintenance;Robots;Standards;Open source software;Testing;Logistics},
  doi={10.1109/UR65550.2025.11077983}}
```
