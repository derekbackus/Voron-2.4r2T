<img src="/images/2.4r2T.png" height="300">

# Voron-2.4r2T
- 350X x 350Y x 950Z Voron 2.4r2 Tall.
- Basically the 2.4r2T is a Voron 2.4r2 with 4040 extrusions that has a Z travel of 950mm. 

Here's a 3D view of the printer. Unfortunately, Autodesk expires this every 30 days. If it's expired, let me know and I'll re-upload it.
[3D CAD View](https://bit.ly/3J8i0Tg) - Expires 4/12/2022

# Why Build this Monster?
At my model shop [KiwiMill](https://www.kiwimill.com) we like to print a lot of tall objects -- boat hulls, display models etc. and instead of printing them in multiple 350mm tall pieces, I wanted to build a printer that could do this in one or two pieces. This is a production machine so I'm not trying to save on costs or skimp on anything. I chose 4040 because it was strong, easy to work with, rigid and, most importantly, fully compatible with the existing Voron 2.4r2 parts made for 2020 extrusions.
# Design Objectives
- Make a printer that reuses most, if not all of the standard Voron parts, but is as tall as possible. The machine should hold up to 24hr/day use and be as easy as possible to maintain and use. Just like the Voron 2.4r2, it should be able to easily print ABS as well as PLA and other materials that can be printed on a Voron. The chamber needs to have filters to clean the air to keep the VOCs out of the work area.
# Videos
I've made some videos to demonstrate how to do some of the more complicated things in this build.
- [Tapping 4040 Extrusion for Blind Joints](https://youtu.be/ohi948kkzv4)
- [Drilling Clearance Holes in 4040 Extrusion for Blind Joings](https://youtu.be/enlHb-844ug)
# Notes & Design Choices
- 1000mm MGN9 rails were easy to get, so I used those for the Z rails. This makes the maximum print height about 950mm.
- A 350X x 350Y Voron design will be used as parts are readily available including built plates, heaters, gantry rails, etc.
- Coroplast will be used on the back and bottom -- laser cut to size. Or maybe ACM. We've got a local supplier of ACM sheet and I've got a 4K laser cutter, so this may be a fun side project.
- The bottom panels and top panel are unchanged from the 2.4r2.
- 4040 rails will be used on the entire frame.
- 2020 rails will be used on the single door.
- Clear anodized extrusions are about 1/2 the price so I used those.
- Extrusions will be ordered without machining -- Misumi has a month lead time on machining AND you can do it yourself with the ez drill jig I designd, a 1/4" drill bit and a 5mm tap.
- I'm trying to figure out how to heat this chamber -- it's so huge. Ideas are: 1) add a plate above the gantry that moves with the gantry, keeping the heat in the bottom of the printer, 2) add a second built plate & heater, controlled exactly like the bed somewhere in the chamber.
# Coverting from an Existing Voron 2.4
- If you have a Voron 2.4, upgrade to all the 2.4r2 parts while you are doing this project. I just printed everything and re-built the whole thing down to the last bolt.
- Follow the steps below for Converting from an Existing Voron 2.4r2
# Converting from an Existing Voron 2.4r2
- The gantry will be used, unchanged
- The gantry wiring and XY endstop pod wiring will need to be re-run because it is longer.
- You'll need a longer Z drag chain.
- 4040 extrusions are used on the entire frame for rigidity.
- 2020 extrusions are used on the door.
- Longer Z belts.
- You may want a new hot end so you can use bigger nozzles, faster. I chose the Rapido.
- New custom panels (back, sides, door)
# BOM (only the changes from a 2.4r2 are listed)
- Qty 1: Z chain -- I like the cheap, generic ones. [Amazon Link](https://www.amazon.com/gp/product/B08R1M9J2H/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8&th=1)
- Qty 4: 1M MGN9 Rails & Pillow Blocks [Robodigg MGN9-2H-1000](https://www.robotdigg.com/product/347/Custom-length-GCr15-MGN9,-MGN12-or-MGN15-Linear-Rail-n-Carriage)
- Qty 4: Misumi 1180mm 4040 Extrusion [Misumi Link](https://us.misumi-ec.com/vona2/detail/110302684530/?HissuCode=HFS5-4040-1180). Please note: you will need to drill your own clearance holes for the hex key. This is easy with a 1/4" drill bit and the guide in the STL folder.
- Qty 8: Misumi HFS5-4040-470 470mm 4040 Extrusion (I use clear anodized because it is MUCH cheaper, black works too) [Misumi Link](https://us.misumi-ec.com/vona2/detail/110302684530/?HissuCode=HFS5-4040-470). Plesae note: You will have to tap all the holes in this extrusion with an M5 tap. Use a pistol drill, tapping fluid and a new, sharp tap. Clamp the extrusion to a table because it likes to spin in you hand. This is easy, but be very careful -- you can break a tap. If you do break a tap, just break it off flat -- there are THREE other screws in each extursion to hold it -- which is plenty.
- Qty 2: Misumi 1088mm 2020 Extrusion HFS5-2020-1088 [Misumi Link](https://us.misumi-ec.com/vona2/detail/110302683830/?PNSearch=HFS5-2020-1088&HissuCode=HFS5-2020-1088&searchFlow=suggest2products&Keyword=HFS5-2020-1088) - vertical door extrusions - Please note: you will need to drill your own clearance holes for the hex key. This is easy with a 1/4" drill bit and the guide in the STL folder.
- Qty 3: Misumi 424mm 2020 Extrusion HFS5-2020-424 [Misumi Link](https://us.misumi-ec.com/vona2/detail/110302683830/?PNSearch=HFS5-2020-424&HissuCode=HFS5-2020-424&searchFlow=suggest2products&Keyword=HFS5-2020-424) - horizontal door extrusions - Plesae note: You will have to tap all the holes in this extrusion with an M5 tap. Use a pistol drill, tapping fluid and a new, sharp tap. Clamp the extrusion to a table because it likes to spin in you hand. This is easy, but be very careful -- you can break a tap and, if you do, you're fucked.
- Qty 9 Meters: 9mm Gates Belt [Fabreeko](https://www.fabreeko.com/products/gates-gt2-open-belt-ll-2gt-6-9-12-reinforced?variant=42466462761215)
- Qty 2: Side panels
- Qty 2: Door panels
- Qty 1: Back panel
- Qty 4: 2020 hinges & handles [Amazon Link](https://amazon.com/gp/product/B07NQ5WHW9/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1)
- Lots and Lots: 20ga PTFE Wire [Remington Industries](https://www.remingtonindustries.com/)
- Shit-ton of 3mm weather seal.
# stl Files to Print
- 2020_Drill_Jig - Use this to drill the clearance holes in the 2020 on your door.
- 4040_Drill_Jig - Use this to drill the clearance holes in your 4040 vertical pieces.
- Filtered_Inliet_Skirt - Removes the switch hole from the stock rear skirt.
- Switch_Skirt - Moves the switch to the right, front.
- MGN9_4040_Rail_Guide - Guide to align your MGN9 rails on the 4040 extrusion.
- Panel_Mount - PITFT50 mount for the 4040 extrusion. Use this repo for the PITFT50 frame and my mount for the 4040 extrusion. [PITFT Frame](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/alanho/BTT_PITFT50_v2_Mount)
# CAD Files
- Panels are in the DXF folder. You can use these to get custom laser-cut panels or cut them youself. I use coroplast for the back and bottom panels and polycarbonate for the top, sides and front panels.
- A STEP file is in the CAD folder so you can see how things go together.
# Mods (optional)
- Klicky [Klicky Github](https://github.com/jlas1/Klicky-Probe)
- Sexbolt Z Endstop [kb-3d.com Link](https://kb-3d.com/store/voron/301-hartk-sexbolt-z-endstop-mod-for-voron-v2-hardware-kit-1634072159749.html)
- LED Enclosure Lights [Voron Github](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/DerekBackus/LED_Holder)
- PITFT50 LCD [kb-3d.com Link](https://kb-3d.com/store/controllers-displays-drivers/419-btt-pitft50-v20-5-inch-pi-lcd-touchscreen-display-1639871340640.html)
- Qty 2. Nevermore filters [Nevermore Github](https://github.com/nevermore3d/Nevermore_Micro)
- I used 4 Z Rail Stops from the Trident Repo to prevent the Z pillow blocks from coming off the MGN9 rails. Trident/STLs/Z_Assembly/[a]_z_rail_stop_x3.stl


