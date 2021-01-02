# brio_compatible_builder_series
Brio builder motor set (compatible) expansion kit
BRIO builder motor set (compatible) expansion kit

**Revised & streamlined design for 2021**

The marketing team is very clever. Our boys received a BRIO Builder ( 34591 ) Builder Motor Set as a shared Christmas gift. In this kit, you get just enough pieces to be fun for a few minutes, but not nearly enough pieces to really make fun stuff. This is where a few hundred dollars of "spare time equivalent" gets spent in CAD to make more pieces for the kiddos without the cognitive expense of having to go shopping (well .. given the current year, let's be honest .. I am NOT going to any stores for anything but essentials).

The components of this kit are dimensionally based on the aforementioned BRIO builder kit and should be completely compatible. Included are some badly needed "upgrades" and customization. This will be a living project as more components will be added as I dream them up.

As this design is parametric, the lengths of the beams can be very quickly tailored to your needs. Any directly user editable (critical) dimensions are highlighted with red in the design parameters "spreadsheet" in FreeCAD. Values in green have been proven to be scalable and accurate. Virtually all aspects of each design are editable in the spreadsheet.

Included STLs for those who are not yet familiar with FreeCAD include:

**Fasteners**
bolt length increments of: 15.5mm (8.5mm for nut, 2.3mm for bolt chamfer) plus 5mm for every beam thickness multiplier
nut thickness + (bolt diameter / 4) + (bolt length multiplier) * (beam thickness)
nut in thicknesses increments of **8.5mm** (17, 25.5, 34mm) - standard kit size is 8.5mm
<ul>
<li>bolt lengths: 13.5, 27, 40.5, 54mm</li>
<li>standard bolts</li>
<li>double-sided bolts</li>
<li>bolts with nut-stops (to serve as axles) with additional (nut stop length of 5.5mm)</li>
<li>slotted bolts to fit in beam slots</li>
<li>standard washer</li>
</ul>

**Beams**
beams come in the following hole counts: 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 1, 14, 16, 18, 20
*slotted beams start at 4 hole equivalents*
over all lengths are calculated as: ( # holes - 1 ) * 16mm + 30mm
{ eg. 4 holes = 78mm, 6 holes = 110mm }
<ul>
<li>normal beams have holes every 16mm</li>
<li>slotted beams with holes at the ends and a slot spaced 16mm from each hole, running the length</li>

</ul>
**Wheels and Pulleys**
the kit drive wheel diameter is 46mm
<ul>
<li>drive wheel single post 46mm</li>
<li>drive wheel double post 46mm</li>
<li>drive wheel single post 46mm (with nut-stop)</li>
<li>v pulleys diameters: 20, 30, 40, **46**, 50, 60, 70mm</li>
</ul>
**Gears**
<ul>
<li>single cross-driven gear tooth count: 10, 15, 20, 25</li>
<li>single idler gear tooth count: 10, 15, 20, 25</li>
<li>double cross-driven gear tooth count: 10/10, 10/15, 10/20, 10/25, 15/20, 15/25, 20/25</li>
<li>double idler gear tooth count: 10/10, 10/15, 10/20, 10/25, 15/20, 15/25, 20/25</li>
</ul>

The design was done in FreeCAD and as mentioned it is fully parametric. I have included the FreeCAD file so that you can modify the design to your heart's content.

I am open to any suggestions as to how to improve the design work-flow in FreeCAD.

**This design will be the foundation of a completely open source meccano type set. I am seeking collaborators for this project; if there is enough interest, I will draft up a set of "best practices" and establish some engineering criteria (i.e. standardized dimensions, etc).**
