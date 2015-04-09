## **Blender in game creation & Three.js**

- Toni Alatalo &lt;toni@playsign.net&gt;
- Playsign Ltd., Oulu, Finland
- +358-40-7198759

!

## Outline

1. <a href="http://www.playsign.net/">Playsign</a> in general
 - Games & Anything Playful!
2. Blender background & basics
3. From Blender to Unity, Unreal
 - State of FBX
4. Blender & Three.js
 - about WebGL & Three.js pipeline
5. Blender support & networking 

!

## Blender background

- VJ tool with Blender Game Engine (2003)
- TD in 1st Open Movie (2005-2006)
 * <a href="https://orange.blender.org/">Studio Orange / Elephants Dream</a>
- For games & other real-time 3D at Playsign 2006-
- Occasional Blender dev & conference visits

!

## Example Blender Game Models

- <a href="http:://yofrankie.org">Yo Frankie!</a> from Big Buck Bunny open movie
- <a
  href="https://github.com/realXtend/chesapeakebay/tree/master/objects">Chesapeake
  Bay</a> from realXtend
  - [10 animated animals](https://www.dropbox.com/sh/cayeixooy00av5p/AABp75hj_JzSIta1yrx7muPMa?dl=0)
- Both are Creative Commons projects, models available for use

!

## FBX - Blender to Unity & Unreal

- FBX format is **secret** so pain for open source
 - Blender devs reverse engineered & documented
- [Blender FBX status info](http://wiki.blender.org/index.php/Extensions:2.6/Py/Scripts/Import-Export/Autodesk_FBX)
- [Unreal Blender docs](https://wiki.unrealengine.com/Static_Mesh_from_Blender)
- [Unity Blender docs](http://docs.unity3d.com/Manual/HOWTO-ImportObjectBlender.html)

!

## Blender & Three.js

- WebGL is pretty mature and usable
 - for other apps but  games too
- Three.js JSON format
 - exporters for Blender(, Max, Maya)
 - also a tool for converting FBX
- Three.js simple [scene editor](http://threejs.org/editor/)
- Simple example: *Playsign logo city*
- Arbitrary shaders possible
- Physically based rendering WIP

!

## Blender support & networking 

* [Blender Cloud](https://cloud.blender.org/) - Blender Open Project's info & material + Blender Training Tutorials etc. A nice way to fund Blender development also!

* [Blender Network](http://www.blendernetwork.org/) - The Blender Network is Blender Foundation’s partnership program, an online directory and social network for Blender professionals.

!

##Questions?

##Comments?


!
 
## <a href="https://github.com/playsign/fidemo">FIDEMO</a> - WebUI & Context Broker

- buildings automatically from map data (GIS/OSM)
- real-time public traffic data (from the transit company)
- cafes, shops etc. (also from Openstreetmaps (OSM))
- Open311 issues from Context Broker (‘fix the city’ in HKI)
- Building prices (Finnish Statistics Open Data)
- adding comments to POIs to Context Broker (Orion)

!

<a href="webui-architecture.png">
<img src="webui-architecture.png">
</a>

!

## How to do self?

- For a multi-user game or other application, a minimal example:
 - <a
 href="https://forge.fiware.org/plugins/mediawiki/wiki/fiware/index.php/3D-UI_-_WebTundra_-_User_and_Programmers_Guide#Pong_Example">
 3D-UI WebTundra - User and Programmers Guide, Pong Example
 </a>
- <a href="http://www.meshmoon.com/">Meshmoon</a> is a commercial
 hosting & service provider for this technology
 - realXtend.org 's WebTundra & Tundra (FIWARE GEs)
 - branded as WebRocket and Rocket on Meshmoon

!

## Simple way to try 3D Web

- Get <a href="http://threejs.org/">three.js</a>
- Have local web dev env
 - http server (Apache, Python, IIS, ..)
 - or start chrome with <a href="http://www.chrome-allow-file-access-from-file.com/">--allow-file-access-from-files</a>
- Use an example as a starting point
- Use any VM / server hosting to publish on the web
- Or e.g. Google App Engine
