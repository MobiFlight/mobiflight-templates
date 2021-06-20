# Flight Simulator panel design template

![image](https://user-images.githubusercontent.com/2587818/119951371-8b725600-bfa4-11eb-8002-0fe23cdbc718.png)

Many aircraft cockpit panels are mounted with quick lock fasteners named after its inventor William Dzus. Many aircraft and equipment manufacturers follow the [MS25212C specification](http://everyspec.com/MS-Specs/MS2/MS25000-MS25999/MS25212C_42008/) for panel dimensions and mounting holes, and thus many planes have the same mounting hole pattern on their pedestal and overhead panel structures. This template aims to provide useful design files as a starting point for creating simulator panels. Additionally it documents some ideas for constructing them using acrylic sheets, a CNC router or a CO2 laser cutter and a 3D printer. [See the wiki for more information](https://github.com/Mobiflight/mobiflight-templates/wiki/Mobiflight-Templates-wiki---useful-extra-information/) - how to build these, suggested switches, components, and other useful information to get started.

Also, the [mobiflight-panels](https://github.com/Mobiflight/mobiflight-panels) repository is a growing collection of openly licensed panel designs based on this template, and the idea is to combine them with pcb designs and matching buttons, switches, and 3d printable parts so that panels can be built without too much guesswork.

![image](https://user-images.githubusercontent.com/2587818/119943882-49ddad00-bf9c-11eb-83cf-31caa491c414.png)

The template itself is a SVG vector graphics file, that can be edited and opened using [Inkscape](https://inkscape.org/). Inkscape is free and open source design software for vector graphics, popular with many "maker" and DIY projects since anyone can download it for Linux, Windows and Mac.

## Mobiflight

This template is born from the collaborative design and brainstorming on the [MobiFlight](https://www.mobiflight.com/en/index.html) community. Mobiflight is open source software that lets you connect your panels to flight simulators using commonly available [Arduino](https://www.arduino.cc/) modules. 

## The Template 

The template is organized in layers: Lower layer that is the mounting plate with attachment holes that fit M5 screws, an upper light plate layerthat has those familiar cutouts around the fastener screws, and a separate layer for button caps and labels. It is useful to keep things separated on different layers, because you can later export each layer for cutting. When you select something and use _Edit > Duplicate_ on Inkscape, the elements are kept in their original layers, and you can just move the copy around with the arrow keys of your keyboard.

To use the template, make a copy of the file, delete the example panel, select a correctly sized panel, and move it to the document page area. Select your panel, and open _File > Document Properties..._ and click _> Resize page to content..._ to make the document size match your selected panel exactly (by default it has a 2mm margin around).

The example panel above has the bottom plate made from clear 2mm acrylic sheet, and the light plate is 3mm white acrylic. The light plates on real aircraft are usually quite a bit thicker, but 3mm works and looks OK, so it is a compromise that seems to work OK. It also works much better with most common buttons and switches. But if you plan to mix your own panels with real or 3rd party sim panels, it's worth checking this. The template defines just the outline, so you can cut the plates from a sheet of any thickness.

The template itself is open source (even though it is not programming code) protected by a "share alike" license, which means that you are free to use it and create panels based on it, and even manufacture panels for others. But if you make changes or updates to the template, we ask that you contribute them back for the common good.

## How to Contribute?

This is a work in progress and contributions for the file are welcome - but since the template is one big SVG file, simple pull requests might not work as well as with code.

If you would like to contribute for example a button or other panel hole / marking element to the template, make a copy of the file with your additions, and delete everything else and share that by clicking the [Issues tab on the above toolbar](https://github.com/Mobiflight/mobiflight-templates/issues).
