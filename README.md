# Quake Detect

<p align="center">
  <a href="https://github.com/chakrakan/spotify-box"><img src="https://github.com/chakrakan/quake-detect/blob/master/demo_imgs/quake-detect.gif" width="700" alt="Quake Detect Demo" /></a>
  <p align="center">An app made using Java, Processing, and the UnfoldingMaps library to generate a live view of earthquakes around the world, in real time!</p>
</p>

The application notably leverages `PApplet` from the Processing library, a lot of other classes and methods to draw items on screen, while also heavily utilizing the UnfoldingMaps library to display a live map view. Under the hood, the application fetches live earthquake data from [USGS earthquake data](https://earthquake.usgs.gov/earthquakes/map/?extent=21.1255,-132.97852&extent=52.3756,-57.04102), city/country data from the [WorldBankOpenData database](https://databank.worldbank.org/home.aspx) and combines the two to display a map using Microsoft's AerialProvider to display past/live earthquakes happening around the world. It also displays information for cities, and can show the number of earthquakes that occured near a given city either recently, or in the past. 

This repository also contains all starter and implemented code for the Object Oriented Programming in Java course offered by UC San Diego through Coursera.

The main program can be found in module 6 while the rest of the modules consist of building towards it, and some other apps built/demo'd as part of learning. 


### Installation

Import this folder in Eclipse ('File' -> 'Import' -> 'Existing Projects into
Workspace', Select this folder, 'Finish')


### Manual Install

If the import does not work follow the steps below.

- Create new Java project
- Copy+Paste all files into project
- Add all lib/*.jars to build path
- Set native library location for jogl.jar. Choose appropriate folder for your OS.
- Add data/ as src


### Troubleshooting

Switch Java Compiler to 1.8 if you get VM problems. (Processing should work with Java 1.6, 1.7 and 1.8)

I used `jdk1.8.0_261` along with its JRE to compile and work through all the projects and assignments.

### Other notable apps

| App | Demo |
|:-----:|:-----:|
| 2D Sun Changing color based on time of day | <img src="https://github.com/chakrakan/quake-detect/blob/master/demo_imgs/sun_changing_color.PNG" alt="sun-change" width="400" height="400" /> |
| WorldMap with life expectancy using WorldBankOpenData | <img src="https://github.com/chakrakan/quake-detect/blob/master/demo_imgs/life_expectancy.PNG" alt="life-expect" width="400" height="400" /> |



