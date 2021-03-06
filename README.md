Cubed's Unity Shaders
============

A compilation of custom shaders for Unity3D.  
You can download the latest version of this package to import **here**: [CubedsShaders.unitypackage](https://github.com/cubedparadox/Cubeds-Unity-Shaders/raw/master/Packages/CubedsShaders.unitypackage)  
Currently built for Unity 5.6.3p1

## Shaders
* Flat Lit Toon  
![alt text](Media/Flat_Lit_Toon.png) ![alt text](Media/Flat_Lit_Toon_Inspector.png)
  * Looks like a unlit shader under good neutral lighting, but actually responds to full ambient and realtime lighting color, intensity and shadow. Single Pass with geometry shader outline
* Unlit Shadowed  
![alt text](Media/Unlit_Shadowed_thumb.png)
  * A simple unlit texture shader, has inputs for main color tint and shadow color tint.
* Flat Lit Toon Rainbow  
![alt text](Media/Flat_Lit_Toon_Rainbow.gif)
  * An (old) version of 'Flat Lit Toon' with a cycling rainbow color. Hue and Saturation are exposed, Supports color mask.
* Flat Lit Toon Distance Fade  
![alt text](Media/Flat_Lit_Toon_Distance_Fade.gif)
  * An (old) version of 'Flat Lit Toon' that fades in based on proximity to camera. Uses noise to dither the fade effect into an alpha cutout. Dither amount, color tint, and color mask are exposed.
* Simple Gradient Sky  
![alt text](Media/Simple_Gradient_Sky_thumb.png)
  * A simple procedural skybox that fades from a sky color to a horizon color

## Notes
I've added an Amplify Shader Editor template! You can download it **here**: [FlatLitToonAmplifyTemplate.unitypackage](https://github.com/cubedparadox/Cubeds-Unity-Shaders/raw/master/Packages/FlatLitToonAmplifyTemplate.unitypackage)  
Project contains the following assets:  
* <a href="http://acegikmo.com/shaderforge/">ShaderForge</a> (gitignored)
* <a href="http://unity-chan.com/">SD UnityChan</a>
* <a href="http://saadkhawaja.com/instant-hi-res-screenshot/">Instant Screenshot</a>

### Tip Jar  
<a href="https://digitaltipjar.com/cubedparadox?_external=true"><img alt="Tip Jar" style="border-width: 0; background-color: grey;" src="Media/tipbutton.png" /></a>

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
