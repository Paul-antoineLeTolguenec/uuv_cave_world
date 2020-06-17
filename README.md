# uuv_cave_world

## Introduction
This repository contains the tools to generate a very realistic model of an underwater world containing a karst (cave) thanks to the Gazebo software.
This simulation was possible thanks to the work of:
<blockquote><p>
@inproceedings{Manhaes_2016,
    doi = {10.1109/oceans.2016.7761080},
    url = {https://doi.org/10.1109%2Foceans.2016.7761080},
    year = 2016,
    month = {sep},
    publisher = {{IEEE}},
    author = {Musa Morena Marcusso Manh{\~{a}}es and Sebastian A. Scherer and Martin Voss and Luiz Ricardo Douat and Thomas Rauschenbach},
    title = {{UUV} Simulator: A Gazebo-based package for underwater intervention and multi-robot simulation},
    booktitle = {{OCEANS} 2016 {MTS}/{IEEE} Monterey}
}
</p></blockquote>
Here is an overview of the generated world :

<p align="center">

[![video](https://github.com/Paul-antoineLeTolguenec/uuv_cave_world/blob/master/doc/video/world_cave.gif)]

</p>

As you can see I have made the cave transparent in order to have a better visualization of the robot moving inside. But for the sake of realism you can make it opaque. Just edit the file: model.sdf.

## Note
In this Markdown, I explain the installation of each element in an exhaustive way because this repository is created in order to bring together people with different backgrounds around the same formalism.
If you have bases in ROS and Gazebo, install this package the way you want.

## Installation
The installation is very simple if you have followed the installation procedure [here](https://github.com/Paul-antoineLeTolguenec/karst_simulation).
All you have to do is type the following commands :

        cd ~/workspaceRos/src
        git clone https://github.com/Paul-antoineLeTolguenec/uuv_cave_world.git
        cd ~/workspaceRos
        catkin_make

## Create your own world
if you want to create your own world, you can follow the procedure [here](https://uuvsimulator.github.io/packages/uuv_simulator/docs/tutorials/seabed_world/).

To get a custom simulation you can use blender and create any element :

<p align="center">
    <img src="https://github.com/Paul-antoineLeTolguenec/uuv_cave_world/tree/master/doc/image/blender.png" width="300">
</p>
