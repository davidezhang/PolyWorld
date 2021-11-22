<!--
*** PolyWorld README
*** Author: Davide Zhang, Aria Xiying Bao
*** Last Updated: 11/21/2021
-->


# PolyWorld: An AR Low-Poly Mesh Maker


<!-- ABOUT THE PROJECT -->
## About The Project
The Problem
Imagine that you need to provide a model of the sofa in your living room with its exact size for the furniture factory to work on. Or you want to 3D print a low-poly style of your lamp, while you have no experience of using 3D modeling software like Blender. There is a lack of 3D modeling solutions for users who are not trained with professional 3D software.

The Solution
We introduce PolyWorld, an Augmented Reality 3D-Modeling application that creates and designs 3D within minutes, without the technical skills required. It is an intuitive vertex-based low-poly modeling AR app that offers low-poly model creation, coloring, and I/O. With the pass-through function in Oculus, it enables you to trace over objects in the real world for more intuitive modeling creation.


## Interface
1. Create
    Choose 'Create' button in the radial menu by toggling the the joysticker on the left, or simply speak "create mode" to the controller to switch to create mode. User can create, select, and delete vertices. To create mesh,  clockwise selection of 3 vertices.
2. Sculpt
    Choose 'Sculpt' button in the radial menu by toggling the the joysticker on the left, or simply speak "sculpt mode" to the controller to switch to sculpt mode. User can select vertices and moving it to differnt locations so as to refine the model.
3. Color
    Choose 'Color' button in the radial menu by toggling the the joysticker on the left, or simply speak "color mode" to the controller to switch to color mode.  User could **color the vertices.** Drag the Hue Ring selector and simply touch the Value triangle to finish color selection. Then apply the color by selecting vertices. We enable user to achieve a **blended look** or a **discrete look** depending on the number of vertices having the same color.


<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->


### Built With
* []() Unity 2020.3.21f1
* []() Oculus Integration Package Version 34.0 (Presence Platform, Voice SDK, Passthrough API)
* []() Deployed to Oculus Quest 2


<!-- USAGE EXAMPLES -->
## Usage Example
1. Modeling a low-poly mesh by tracing a real-world object


## Known Bugs
1. Can only delete one vertex per time
2. OBJ import and export not available in this build

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
Acknowledgements of 3rd party scripts are in the scripts.
Radial menu and color picker assets are purchased from Unity Asset Store and modified by us.