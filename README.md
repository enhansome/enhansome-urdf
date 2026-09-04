# Awesome URDF with stars

> A curated list of Unified Robot Description Format (URDF) libraries, tools and resources.

Unified Robot Description Format (URDF) is an XML format for representing some aspects of a robot model, that was initially proposed as part of the [Robot Operating System (ROS)](https://www.ros.org/), but it is now used in several robotics-related tools and software.

See the [official ROS documentation page on URDF](http://wiki.ros.org/urdf) for the official specification and more information about URDF.

## Contents

* [URDF](#urdf)
  * [Libraries](#libraries)
    * [C++](#c)
    * [Python](#python)
    * [MATLAB/Simulink](#matlabsimulink)
    * [Rust](#rust)
    * [Julia](#julia)
    * [Go](#go-golang)
  * [Resources](#resources)
  * [Extensions](#extensions)
  * [Tools](#tools)
* [Community](#community)

## URDF

There is no versioned specification of the URDF format. The main reference for the URDF format are the [ROS wiki docs on URDF](http://wiki.ros.org/urdf).

### Libraries

Libraries to import, export and manipulate URDF files.

#### C++

* [iDynTree](https://github.com/robotology/idyntree) ⭐ 235 | 🐛 196 | 🌐 C++ | 📅 2026-07-27 - Library for kinematics and dynamics computation of free-floating robot model, with support for import and export of URDF files. It includes Python and MATLAB bindings. \[BSD]
* [urdfdom](https://github.com/ros/urdfdom) ⭐ 136 | 🐛 56 | 🌐 C++ | 📅 2026-07-30 - Reference C++ URDF parser implementation mantained by OpenRobotics. \[BSD]
* [sdformat](http://sdformat.org/) - Reference C++ implementation of the SDFormat (Simulation Description Format), used in Gazebo and Ignition libraries that includes a converter (based on `urdfdom`) from URDF to SDF. \[APACHE2]

#### Python

* [urdf\_parser\_py](https://github.com/ros/urdf_parser_py) ⭐ 109 | 🐛 21 | 🌐 Python | 📅 2025-12-18 - Reference Python URDF parser mantained by OpenRobotics. \[BSD]
* [odio\_urdf](https://github.com/hauptmech/odio_urdf) ⭐ 105 | 🐛 4 | 🌐 Python | 📅 2023-12-15 - Library for building URDF files using Python. \[MIT]
* [compas\_robots](https://github.com/compas-dev/compas_robots/) ⭐ 4 | 🐛 5 | 🌐 Python | 📅 2026-08-13 - URDF parser & writer in Python based on the COMPAS framework. \[MIT]

#### MATLAB/Simulink

* [Simscape Multibody URDF Import](https://mathworks.com/help/physmod/sm/ug/urdf-import.html) - Simscape Multibody is the Multibody simulation environment of MATLAB, that supports importing URDFs. MATLAB docs contain also a useful [URDF primer](https://mathworks.com/help/physmod/sm/ug/urdf-model-import.html) documentation. \[Commercial]

#### Rust

* [urdf-rs](https://github.com/openrr/urdf-rs) ⭐ 49 | 🐛 9 | 🌐 Rust | 📅 2026-06-30 - URDF parser using [serde-xml-rs](https://github.com/RReverser/serde-xml-rs) ⭐ 333 | 🐛 38 | 🌐 Rust | 📅 2026-02-05 for Rust. \[APACHE2]

#### Julia

* [MeshCatMechanisms.jl](https://github.com/JuliaRobotics/MeshCatMechanisms.jl) ⭐ 43 | 🐛 3 | 🌐 Julia | 📅 2024-12-05 - 3D Visualization of mechanisms and URDFs using [MeshCat.jl](https://github.com/rdeits/MeshCat.jl) ⭐ 254 | 🐛 25 | 🌐 Julia | 📅 2025-10-14 and [RigidBodyDynamics.jl](https://github.com/JuliaRobotics/RigidBodyDynamics.jl) ⭐ 310 | 🐛 40 | 🌐 Julia | 📅 2024-11-08 . \[MIT]

#### Go (Golang)

* [urdf-go](https://github.com/WrenchRobotics/urdf-go) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2026-05-01 - URDF parser using the XML decorators of Golang for efficient reading.

### Resources

* [Awesome Robot Descriptions](https://github.com/robot-descriptions/awesome-robot-descriptions#readme) ⭐ 1,651 | 🐛 3 | 📅 2026-08-04 - A curated list of awesome robot descriptions, most in URDF or Xacro formats.

### Tools

* [urdf-viz](https://github.com/openrr/urdf-viz) ⭐ 590 | 🐛 17 | 🌐 Rust | 📅 2026-06-19 - Visualize URDF/XACRO file, URDF Viewer works on Windows/MacOS/Linux. \[APACHE2]
* [Unity-Technologies/URDF-Importer](https://github.com/Unity-Technologies/URDF-Importer) ⭐ 335 | 🐛 36 | 🌐 C# | 📅 2023-10-02 - URDF Importer allows you to import a robot defined in URDF format in a [Unity scene](https://unity.com). \[APACHE]
* [yourdfpy](https://github.com/clemense/yourdfpy) ⭐ 293 | 🐛 19 | 🌐 Python | 📅 2026-05-10 - Library and command-line tool to load, visualize, manipulate, validate and save URDF files.
* [URDFly](https://github.com/Democratizing-Dexterous/URDFly) ⭐ 250 | 🐛 5 | 🌐 Python | 📅 2026-03-29 - URDFly is a Python-based toolkit for working with URDF files, providing tools for parsing, visualizing, and analyzing robotic systems defined in URDF format, with a focus on axes visulazation, urdf editing, MDH parameter conversion, kinematics calculation, and dynamics regressor codegen.
* [URDFormer](https://github.com/WEIRDLabUW/urdformer) ⭐ 204 | 🐛 7 | 🌐 Python | 📅 2024-08-08 - Given an image, URDFormer predicts its corresponding interactive 'digital twin' in the URDF format.
* [bubblify](https://github.com/bheijden/bubblify) ⭐ 153 | 🐛 2 | 🌐 Python | 📅 2025-09-09 - Bubblify is an interactive tool for creating spherical approximations of robot geometries directly from Universal Robot Description Format (URDF) specifications
* [xacro](https://github.com/ros/xacro) ⭐ 125 | 🐛 11 | 🌐 Python | 📅 2026-04-07 - Xacro is an XML macro language. With xacro, you can construct shorter and more readable XML files by using macros that expand to larger XML expressions. Xacro is frequently used to mantain URDF models. \[BSD]
* [blender-robotics-utils](https://github.com/robotology/blender-robotics-utils) ⭐ 83 | 🐛 9 | 🌐 Python | 📅 2024-12-04 - Set of utilities for exporting/controlling your robot in [Blender](https://www.blender.org/). It includes a URDF to Blender model converter. \[BSD]
* [xacrodoc](https://github.com/adamheins/xacrodoc) ⭐ 75 | 🐛 0 | 🌐 Python | 📅 2026-04-20 - A wrapper around xacro providing friendly interfaces to compile xacro files to plain URDF or MJCF from Python or the command line. No ROS installation is required.
* [jupytercad\_urdf](https://github.com/jupytercad/JupyterCAD-urdf/) ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-16 - A JupyterLab extension allowing export of CAD designs to URDF.
* [Foxglove Studio](https://foxglove.dev/urdf) - Visualization app for web or desktop, supports URDFs as well as arbitrary bag or [MCAP](https://mcap.dev) data. \[MPL-2.0]
* [urdf-loaders](https://gkjohnson.github.io/urdf-loaders/javascript/example/bundle/) - URDF visualizer running in modern Web browsers with support for drag-and-dropping a full description directory. \[APACHE2]

### Extensions

Several libraries and groups have extended the URDF format beyond the official specs, a brief list is provided in the [`urdf-extensions.md`](urdf-extensions.md) file.

## Community

* [Robotics StackExchange](https://robotics.stackexchange.com/?tags=urdf) - Questions related to URDF in Robotics StackExchange.
* [ROS Answers](https://answers.ros.org/questions/scope%3Aall/sort%3Aactivity-desc/tags%3Aurdf/) - Questions related to URDF in ROS.
* [Foxglove Slack community](https://foxglove.dev/slack) - Questions and discussion related to robitics data visualization

## Contribute

Contributions are welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-04._
