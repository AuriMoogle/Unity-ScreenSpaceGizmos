# Unity-ScreenSpaceGizmos
A small utility that let you draw gizmos in 'screen space'.

Unity’s default gizmos are essential for visual debugging but can only be drawn in world space. This restriction can be rather annoying if you try to debug custom UI or viewport-based camera movement. 

This script solves the problem by drawing gizmos at the camera.NearClipPlane. It works with all camera projection types (perspective, orthographic) and canvas modes except world-space. In world-space just use the default Unity gizmos.

Explanation and more content at my blog: http://anja-haumann.de/unity-easy-shader-property-access/
