### Features

1. Dynamic Shadows
2. Normal Maps
3. Physics Simulations
4. Screen Space Ambient Occlusion (SSAO)
5. Cross Platform Support (Mac, Windows, iPhone, Android, WebGL, XBox, PlayStation)
6. Visual Editor

### Basics


Visual Editor : art assets can be laid out in this editor. 

The assets can be controlled by scripts. 

Scripting is done in MonoDevelop. Scripts are attached to objects as components.

Unity added *#pragma strict* to enforce 

Scripts, that contain code, are attached to objects in the scene.

A game object can have a component collection attached to it, which can include scripts to execute. 

Game objects are 

The Unity game engine executes the script code 

### MonoBehaviour

A script is a component only if it inherits from *MonoBehaviour* and only scripts can be attached to game objects, as *MonoBehaviour* does the heavylifting of attaching components to 
the game objects.

The following methods of *MonoBehaviour* could be overridden to provide custom behavior

1. Start()
2. Update()

The *Start()* method is called when the object becomes active which is when the level with that object is loaded.

The *Update()* method is called for every frame.
