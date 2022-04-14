# Duet-Magnetic-Filament-Monitor-Housings
Redesigned MFM housing for reliable FDM printin

Critical/important print settings:

**0.1mm layer height**. Or anything that divides into that cleanly. NOT, say, 0.16mm because it's the *magic* layer height of your machine. 
**0.4mm wall line width**. Or width that cleanly divides into 1.2mm.

Notes and to expand on the above:

The only super critical print setting is to use 0.1mm layer height. I really cannot stress this enough. Moving down to 0.05mm is fine, as is any other layer height the divides neatly into 0.1. Anything else is likely to land you with some "odd" dimensions that are really quite important. Otherwise, just do what you'd normally do for accurate functional prints. In Cura, the "Horizontal Expansion" setting can be quite handy to compensate for any deviation of your printer - I'm sure other slicers have similar settings.

I've designed for 0.4mm line width, so best to stick to that. 10-20% infill of any type that ties the walls to the top/bottom will work fine. I used lines an gyroid while testing. You should get 3 x whole lines in the 1.2mm "walls" of the lid.

The lid might need a light deburr if you get some elephants foot on the first layer.

I opted for using flanged RC servo screws to mount the board, though you can easily drill and tap to
M2.5 for the board mounts. All the supplied hardware is used as standard otherwise.

Push the PTFE tube into the housings so it's close to, but not interfering with the hobbed section. This runs in further than the official housing and is best done before the rotating mag assembly is installed so you can be sure where it ends up. Running the point of a knife or deburring tool inside the entry to the outgoing PTFE completely eliminates any snag when loading filament.

The bottom bearing is best pressed in with the head of an M5 cap head screw if this is required. This puts the force purely on the outer race, though not much should be needed all other things being equal. As explained in the original post the seats have a slight taper which seems to account nicely for variations in prints and gives a snug fit without any fussing. The bearings snap nicely into place on all my prints now with no play or fettling needed.

The idler carrier halves will need gluing together around the bearing as per the original and need no special attention. I'd advise a tiny blob of glue where the stubs meet inside the bearing, but careful with the bearing itself, obviously.

Thanks to the Duet team for the support while I was developing this, it really is first class!
