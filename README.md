# Scavenger
- A tool written in C# for managing graphics content in Unity

 # Menu:  
 <B>Unity -> Window -> Scavenger</B> (Shift + Command + T)
 
 # Graphics Content
 The following graphics content exposed from Unity Project,
 
 - <B>Mesh:</B> name, extension, vertices, triangle, uvs, sub-mats, size, format and location
 - <B>Material:</B> name, shader assigned, the size of shader and location
 - <B>Texture:</B> name, extension, width, height, type, format, mip maps, filter, size and location
 - <B>Animation:</B> name, extension, seconds, frame rate, number of events, size and location
 - <B>Audio:</B> name, extension, frequency, seconds, channels, size, loading type and location
 - <B>Script:</B> name, extension and location
 - <B>Prefab:</B> name, extension and location
 - <B>Scene:</B> name, loading, extension and location
 
 # Usage:
 
   <img src="https://thepossiblehorizon.files.wordpress.com/2017/01/scavenger1.gif"></img>
 
  It consolidates all the graphic resources and performance-related properties from Unity Project by the category of type and usage. Built purely using Unity GUI controls to trade for better performance. Most of columns are sortable. Each asset can be located and highlighted with yellow color in Project Browser by clicking on name button, or searching by non-case-sensitive string. All the current used assets in game can be highlighted with a background of soothing forest green. Audio asset can be played by clicking on play button. A brief summary is displayed on information bar at the bottom of window. The extracted information can be exported as a local cvs file like this,
  
  <img src="https://thepossiblehorizon.files.wordpress.com/2017/01/assetsexportedascsv1.jpg"></img>

  Even though all the unused assets wouldn’t be included in the final release when deploy a build from Unity, it is still necessary to monitor how efficient art assets are used in game and optimise whatever is necessary based exposed data here, for example vertex count, mesh LODs, texture resolution, compression, size, sub-materials, shader and etc. By all means to achieve the best visual fidelity with acceptable memory usage and performance possible.
  
 <a href="http://u3d.as/HoT"><img class="alignnone size-full wp-image-4089" src="https://thepossiblehorizon.files.wordpress.com/2017/02/scavengeronassetstore1.jpg" alt="scavengeronassetstore" width="1600" height="650" /></a>
 
  Will definitely follow up with user feedback for its future improvement especially with new ideas and bug reports.
