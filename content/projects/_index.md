---
title : "Projects"

---

This page higlights several of my personal projects. I have also included a few professional
projects which are in the public domain.

- [AssimpKit](#assimpkit)
- [Mayavi](#mayavi)

---

### AssimpKit

***Objective C, 3D Format Processor***

A cross platform library (macOS, iOS) that converts files supported by Assimp into SceneKit scenes.

- Supports geometry.
- Materials (both color and texture).
- Cameras. 
- Skeletal animations.
- Serialization to .scn format.

![AssimpKit-iOS](/images/assimpkit-ios.png) 
![AssimpKit](/images/assimpkit.png)

[Github](https://github.com/dmsurti/AssimpKit)

---

### Mayavi

***Python, Scientific Visualization***

***Work @ [Enthought](https://www.enthought.com)***

A python application and library for 3D scientific visualization built on top of VTK, with seamless
integration with python scientific libraries.

- Upgrade the VTK Compatibility to 5.10, 6.x and 7.0
- The upgrade to 6.x required an extensive refactor to use VTK's new pipeline architecture while
  ensuring backward compatibility with old VTK 5.10 version, which used the old pipeline
  architecture.
- Various other bug fixes, reducing memory leaks and release related tasks.

[Github](https://github.com/enthought/mayavi/commits?author=dmsurti)

![mayavi-visualization](/images/mayavi.png)
