# Learning Unity

[![Join the chat at https://gitter.im/olange/learning-unity](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/olange/learning-unity?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Discovering and learning using Unity editor and scripting.

## References

[Unity Manual](http://docs.unity3d.com/Manual/)

[Building for iOS using Unity Cloud Build](https://build.cloud.unity3d.com/support/guides/ios/)

## Tutorials

### Data access

[Using Google Firebase in Unity and a Primer in Event Driven Programming](https://medium.com/grtech-student-blog/using-google-firebase-in-unity-and-a-primer-in-event-driven-programming-7f1bf2d61dc7) How to implement Google Firebase in a Unity project; also covers the use of events _Stephen King, 30.04.2017_

[Adding Firebase to your Unity Project](https://firebase.google.com/docs/unity/setup) Setting up an Unity project to use Firebase for authentication, messaging, and much more _Firecasts, 02.03.2017_

### Scripting geometry

[Unity · Spline-based Procedural Geometry](https://dayone.me/2hqvzt8) What is a mesh? What is space? Coordinate systems of various engines and mesh editing apps, Bézier-splines mathematics, Point-basis and tangent-basis functions, extrude a line-shape along a spline, adjusting UVs to consistently map textures, and tips _video, 61 min., Joachim Hólmer, 21.09.2015_

### Beginner projects

[Roll-a-ball tutorial](http://unity3d.com/learn/tutorials/projects/roll-ball-tutorial) Create a simple rolling ball game that teaches many of the principles of working with Unity _serie of 8 short videos, 74 min., Unity, 24.07-19.08.2015_

[Spring Joint](01-spring-joint/README.md) Playing with Rigid Body, Spring Joint and Line Renderer components _Gōng-fu I/O, 17.12.2015_

### Interface essentials

[Unity · Essentials](https://dayone.me/2jyNzWy) Game Objects, Prefabs, Tags and Layers _serie of 4 short videos, 8 min, Unity, 08.04-22.11.2013_

[Unity · Editor basics](https://dayone.me/2hqwz7d) Getting to know the fundamentals of the editor and a few tips _video, 61 min., Mike Geigh, 23.09.2013_

[Unity · Game Object](https://dayone.me/2hU7zKZ) Coordinate system in Unity, camera projection modes, game objects, components and transformations, nesting _video, 49 min., Mike Geigh, 30.09.2013_

[Unity · Tips & Tricks 1](https://dayone.me/2i11zIR) A bunch of tips, that do not fit in other tutorials _video, 59 min, Adam Buckner, 23.06.2014_

### UI

[Unity · New UI World Space Canvas](https://www.youtube.com/watch?v=Mzt1rEEdeOI) setting up and animating a UI canvas in world space; demonstrates parenting, alignment, scaling of UI elements (canvas, canvas group, text, images, mask) and animating their position and alpha to build a simple dialog _video, 35 min., 30.06.2014_

[Text Mesh Pro · Documentation](http://digitalnativestudios.com/textmeshpro/docs/) documentation of the [Text Mesh Pro](https://www.assetstore.unity3d.com/en/#!/content/17662) asset; see also the [video tutorials](https://www.youtube.com/user/Zolran/videos) of Zolran on YouTub.

### Shaders

[ShaderLab: Culling & Depth Testing](http://docs.unity3d.com/Manual/SL-CullAndDepth.html) in Unity's documentation; the ‹ Reveveal Backfaces › shader helps debugging Normals; see also the ‹ Glass Culling › shader.

## Libraries and integrations

### GitHub

[Prime31 / GoKit](https://github.com/prime31/GoKit/wiki/1.-GoKit-Code-Basics) « Lightweight tween library for Unity aimed at making tweening objects dead simple and completely flexible » (cité par David le 15.01.2015)

[UnityOSC](https://github.com/jorgegarcia/UnityOSC) Open Sound Control (OSC) C# classes interface for the Unity3d game engine. See also Paul Varcholik's [Bespoke OSC library](http://www.varcholik.org/wpress/open-sound-control/).

[TouchScript](https://github.com/TouchScript/TouchScript/wiki/Gestures) _« Complete multitouch solution for Unity: Win8, TUIO, Mobile. »_

### Clojure integration

[Arcadia Unity](https://github.com/arcadia-unity/Arcadia) Integration of the Clojure Programming Language with Unity; as of 07.02.2016, it embeds Clojure 1.7 into Unity 5.3.2 (see [branch develop](https://github.com/arcadia-unity/Arcadia/tree/develop))

## Articles

### Testing

* [The Unity Assertion Library](http://blogs.unity3d.com/2015/08/25/the-unity-assertion-library/) Unity, Tom Paszek, 25.08.2015
* [Unity Test Tools](https://bitbucket.org/Unity-Technologies/unitytesttools/wiki/Home) Wiki
* [Unity Test Runner](http://docs.unity3d.com/Manual/testing-editortestsrunner.html) Unity documentation
* [NUnit Quickstart](http://www.nunit.org/index.php?p=quickStart&r=2.6.4), [NSubstitue Quickstart](http://nsubstitute.github.io/help/getting-started/)

### Performance

* [10000 Update() calls](http://blogs.unity3d.com/2015/12/23/1k-update-calls/) Unity blog, Valentin Simonov, 23.12.2015
* [IL2CPP internals: Method calls](http://blogs.unity3d.com/2015/06/03/il2cpp-internals-method-calls/) Unity blog, Josh Peterson, 03.06.2015
