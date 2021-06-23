# core-piston

***3D-printable piston to hold a sediment core in its barrel***

**Design by Bobby Schulz.** Please attribute following CC BY-SA 4.0 (see the [license](LICENSE))
[Add persistent Zenodo link and DOI here once these are generated.]

This core piston is made to work with a Pylonex HTH Gravity Corer with a 70mm tube diamter. The honeycomb structure within the 3D print ensures that it floats when invariably dropped into the water.

## Technical specifications

* Plastic body
  * Two 3D-printable components
  * **SUGGESTED FILL DENSITY?**
  * Suggested material: White or brightly colored ABS
* Rubber gasket **ADD INFO**
* Fasteners
  * Screws: **ADD INFO**
  * Threaded inserts: **ADD INFO**

## Instructions

Here, "bottom" refers to the plastic part that is held by the user, and "top" refers to the plastic part that is in direct contact with the core. These are connected by screws once assembly is complete.

1. Generate gCode for your 3D printer. We use [Slic3r with a Prusa 3D printer](https://www.prusa3d.com/prusaslicer/).
2. Print using ABS. We suggest a bright color that you can see amidst the muck.
3. Cut rubber rounds **diameter**. We use a laser cutter, but a compass with a pen knife should work well too.
4. Install threaded inserts into the bottom printed component. **@bschulz1701: installation method depends on type -- any info here?**
5. Center the rubber gasket over the bottom plastic component. **@bschulz1701: any tips on centering?**
6. Place the top component atop the gasket and bottom component, sandwiching the gasket betweent the two plastic parts.
7. Insert the three screws, piercing the rubber gasket in the process. **@bschulz1701 or do you cut holes in the gasket beforehand?** Ensure that these are tight
8. Inspect your piston for any obvious problems, and test it in the lab with a core barrel.

## Rendered images

Images from bottom to top in the direction from user's hand inserting the piston to top of core barrel.

### Bottom

This bottom portion of the piston is counterintuitively called ["Plug Top"](https://github.com/umn-earth-surface/core-piston/blob/master/Plug_Top_MultiHole.STL). Maybe we'll change the name.

![Bottom](images/bottom-3Dmodel-perspective.png)

***Bottom plastic component of core piston.*** *The thinner portion to the lower right is held to insert the piston into the core barrel in order to seal it and keep the core from falling out. Not visible is a hole that goes partway through the piston and can be used with a dowel to extrude the core out of the top of the barrel. On the upper left are three holes to hold threaded inserts for screws that connect the top half and bottom halves of the piston. A circular rubber gasket sits between these two halves, held in place by the screws.*


![Bottom of top](images/top-3Dmodel-bottom.png)

***Bottom side of top plastic component of core piston.*** *Screws pass between the three holes shown here, through the rubber gasket, and into the bottom plastic component (shown above). The angled edges of this component force the rubber gasket to bend towards the bottom of the piston, pinning it to the mating angled faces on the bottom plastic component. This ensures that the piston may extrude the core, but locks it against sliding downwards.*

### Top

This top portion of the piston is counterintuitively called ["Plug Base"](https://github.com/umn-earth-surface/core-piston/blob/master/Plug_Base_MultiHole.STL). Again, maybe we'll change the name. Or maybe not.

![Top of top](images/top-3Dmodel-top-core-base.png)

***Top side of top plastic component of core piston.*** *This side of the piston directly contacts the bottom of the core. The three countersunk holes hold the screws and ensure that their heads are flush with the remainder of the surface.*

<br>
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
