---
content_type: page
description: This section provides links to related resources for the course, including
  PSPICE simulation information, the PSIM power electronics simulator, and more free
  resources.
draft: false
learning_resource_types: []
ocw_type: CourseSection
title: Related Resources
uid: 75dbdf7c-80e7-be23-8752-a93976c0adb5
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---
## PSPICE Simulation Information

Download the Microsim (now known as Orcad) DesignLab Release 8 Evaluation version, containing both Schematics and PSpice for PCs. A more up-to-date version can be downloaded from [OrCAD](http://www.orcad.com/).

[Spice tutorial](http://homepage.seas.upenn.edu/~jan/spice/spice.overview.html) (courtesy of University of Pennsylvania Department of Electrical Engineering). In particular, see [How to Get Started with PSpice](http://homepage.seas.upenn.edu/~jan/spice/spice.guide.html#PSPICE).

### (Almost) Ideal Diode Model

idealdiode.lib ({{% resource_link "0ed41b18-1798-b71d-e05e-b7b1ec783e51" "LIB" %}}) – If you're creating your circuit with the "Schematics" tool, incorporate this library into "Schematics" as follows: Select Analysis -> Library and Include Files. Type the filename idealdiode.lib in the filename box (including the path to the file), and click Add Library. If you're creating your circuit using a standard textfile netlist, add the following lines to your file:

`X1 (node 1) (node 2) diode_ideal`    
`.lib idealdiode.lib`

idealdiode.slb ({{% resource_link "81d1c77c-c811-649b-9177-be5213b1c3e4" "SLB" %}}) – If you're creating your circuit with the "Schematics" tool, incorporate this *symbol* library into "Schematics" as follows: Select Options -> Editor Configuration. Select the Library Settings button, and then add the file idealdiode.slb. If you're creating your circuit using a standard textfile netlist, you do NOT need this file.

Half-wave rectifier with freewheeling diode and Commutating Inductance ({{% resource_link "31f59d88-3e08-3f2c-f278-72beb6a0b4b5" "CIR" %}})

Full-wave rectifier with Commutating Inductance and Current Source Load ({{% resource_link "c5abd7c5-75ee-f7e9-541c-927e19d8e31b" "CIR" %}})

Full-wave rectifier with RL Load ({{% resource_link "2df82751-7464-1713-4583-96307310adfc" "CIR" %}})

Another SPICE simulator that may be used is LTSPICE/SwitcherCAD III, developed by Linear Technology. 

## PSIM Power Electronics Simulator

Try out the PSIM power electronics simulator for free! A demo version is available from [POWERSIM](http://www.powersimtech.com/).

## More Free Resources

The Power Supply Manufacturer database is dedicated to designers of Switch Mode Power Supplies, and features:

- How to design a Switch Mode Power Supply, including software tools and examples.
- How to simulate a power supply. See PSpice simulation waveforms on their SMPS Simulation page.
- Lists of companies manufacturing power supplies.
- Information regarding SMPS components and component suppliers.
- Various technical articles.