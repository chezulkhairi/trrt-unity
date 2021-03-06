# trrt-unity
Unity3D-based implementation of the TRRT path-planning algorithm

![Unity Screenshot](/images/image10.png)

## Objectives
- Implement the random-trees path-planning algorithm described in the whitepaper ["Transition-based RRT for Path Planning in Continuous Cost Spaces"](http://www.leonardjaillet.com/Publications_files/Iros08_Jaillet_TransitRRT.pdf) (Jaillet, Cortés, and Siméon, 2008)
- Learn how to use the [Unity3D](https://unity3d.com/) engine

### Overview
This class project, created for CS689 with [Dr. Amarda Shehu](http://cs.gmu.edu/~ashehu/), is based upon the whitepaper "Transition-based RRT for Path Planning in Continuous Cost Spaces" (Jaillet, Cortés, and Siméon, 2008). Their paper described a novel modification to traditional rapidly-exploring random trees (RRTs) that "combines the exploration strength of the RRT algorithm [...] with the efficiency of stochastic optimization methods". The algorithm described therein is suitable for a broad class of problems, including high-dimensional tasks such as motion planning for a many-DOF manipulator, as well analyzing protein-ligand interactions. My task was to translate the authors’ pseudo-code into a fully-functional algorithm while also implementing a user interface and 3D visualization. I selected [Unity3D](https://unity3d.com/) (a popular game-development tool) as my engine of choice for the latter elements.

### Links
- [Video of the demo in action](https://www.dropbox.com/s/th1tqcyerogxq84/trrt_movie.mp4?dl=0)
- [Presentation slides](/docs/clark_cs689_trrt.pdf)

### Prerequisites
[Unity3D >= 5.0](https://unity3d.com/) (Originally developed under Unity 3.5 in 2012,  updated for Unity 5.0 in Aug 2015)

### Implementation Details
Implemented in C# (one of the 2/3 scripting languages available in Unity3D). The actual pathfinding code is in TerrainScript.cs.
