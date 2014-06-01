# Sketch Icon Stamper Plugin

## What Does It Do?

Takes full sized art for an icon and creates multiple sizes of it so you don't
have to.

Demo [https://vimeo.com/97067332](https://vimeo.com/97067332)
[![Screenshot of demo video](http://f.cl.ly/items/3V0d0F1h3m1h2H0u1s2r/icon-stamper.png)](https://vimeo.com/97067332)

## Installation
There are two different ways to install Icon Stamper. Official Sketch Plugin installation
documentation can be found in the [plugin docs](http://bohemiancoding.com/sketch/support/developer/01-introduction/01.html).

### Git clone (best way to go)
 - Using a command line app (Terminal, iTerm, etc) navigate to the Sketch Plugins
 directory. This is different depending on your set up. If you're unsure, open
 Sketch and go to the Plugins menu > Reveal Plugins Folder
 - Once you're in the Plugins directory `git clone https://github.com/tylergaw/icon-stamper.git` or your fork.
 - You can find the plugins in the Plugins Menu > icon-stamper

### Zip download
 - If you're reading this on GitHub, there should be a Download Zip button to the
 right of this text. Download the zip file.
 - Open your Sketch Plugins folder by going to the Plugins menu > Reveal Plugins Folder
 - Unzip the Icon Stamper zip file. Place the Icon Stamper.sketchplugin file in the Sketch plugins folder
 - You can find the plugins in the Plugins Menu > Icon Stamper (or the name you gave it)

## Usage

I made this for use with the Sketch iOS App Icon template, but it should work
with any Sketch document that has an artboard for each size icon you need to create.

iOS App Icon Template:

1. Create a new Sketch file from the template by going to File > New From Template >
iOS App Icon
![Creating a new iOS App Icon Sketch file](http://f.cl.ly/items/3O1U3R3h0E0w2F0y0j47/stamper-screens.png)
2. Create your icon graphics on the largest artboard named “iTunesArtwork@2x”. This
is the 1024x1024px version.
3. Be sure that your layers are contained within a layer group. This group will
be copied to all the other artboards.
![Creating the icon graphics](http://f.cl.ly/items/0P0d2C2Y270d1A04273s/icon-stamper-in-use.png)
4. Select the layer group that contains the graphics, go to Plugins > icon-stamper > Icon Stamper
(or the location and name you gave it)
5. Each artboard should have your icon at the size of that artboard.
6. Rinse and repeat.

I've found this most helpful for making tweaks to the icon and quickly seeing
what those changes will look like at the range of sizes.
