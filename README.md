# Flight Simulator panel design template

Many aircraft cockpit panels are mounted with quick lock fasteners named after its inventor William Dzus. Many aircraft and equipment manufacturers follow the [MS25212C specification](http://everyspec.com/MS-Specs/MS2/MS25000-MS25999/MS25212C_42008/) for panel dimensions and mounting holes, and thus many planes have the same mounting hole pattern on their pedestal and overhead panel structures. This template aims to provide useful design files as a starting point for creating simulator panels. Additionally it documents some ideas for constructing them using acrylic sheets, basic tooling and a 3D printer.

![image](https://user-images.githubusercontent.com/2587818/119943882-49ddad00-bf9c-11eb-83cf-31caa491c414.png)

The template itself is a SVG vector graphics file, that can be edited and opened using [Inkscape](https://inkscape.org/) which is free and open source software and works on Windows, Mac and Linux computers.

## Mobiflight

This template is born from the collaborative design and brainstorming on the [MobiFlight](https://www.mobiflight.com/en/index.html) community. Mobiflight is a great open source tool that uses commonly available [Arduino](https://www.arduino.cc/) modules and lets you bring the switches and lights alive on your flight simulator.

## The Template 

The template is organized in three main layers: Lower layer that is the mounting plate, upper layer that is fastened on top of it and has those familiar cutouts for the Dzus fasteners, and a layer for button caps. 

To use the template, make a copy, select and copy the size of panel you need into the main document area (where the example panel is) and delete the other panel templates and stuff once you are done with your design. You can then save and cut one layer at a time. The layers are as follows, ordered from bottom to top:

The example panel above has the bottom plate made from clear 2mm acrylic sheet, and the top is 3mm white acrylic. The actual aircraft panels are much thicker, but most affordable laser cutters (you need a CO2 laser for cutting acrylic sheet!) work much better with 3mm, and in practice it works and looks fine. But keep this in mind if you intend to mix real parts with the panels you build yourself.

### Button designs and ideas

We have experimented with some 3D printed button caps, and while the actual construction depends on how you plan to construct the stuff behind your panels, one possible approach is to use 10mm nylon standoffs and M3 machine screws to mount a printed circuit board behind the panel (hence the M3 sized holes in the inside area of some panel templates). The switches and leds are then mounted on that PCB, and simple tactile push buttons can be used with a 3D printed button cap. We have also experimented cutting and engraving button labels on clear acrylic sheet that is painted black on the reverse side, with the labels engraved on the paint with laser or CNC. These button cap designs are part of the template, but they may evolve, as actual panels with them are being built.

![image](https://user-images.githubusercontent.com/2587818/119947021-ef465000-bf9f-11eb-8c3e-73d43bf00b48.png)

Contributions and Development

This is a work in progress and contributions for the file are welcome - though since the template is one big SVG file, simple pull requests might not work as well as with code. My current thought is that if you would like to contribute for example a button or other panel hole / marking element to the template, make a copy of the file, delete everything else than your contribution, so that the additional thing is the only thing in the file, with everything on their respective layers. I think that might work, let's see.
