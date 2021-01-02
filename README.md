<center><img src="https://github.com/jbuck2005/brio_compatible_builder_series/blob/master/base_shapes.png"></center><br>
# brio_compatible_builder_series<br>
Download the FreeCAD project here: <a href="https://github.com/jbuck2005/brio_compatible_builder_series/blob/main/brio_builder_set.FCStd">Brio builder motor set (compatible) expansion kit</a><br>
<br>
STL files are found in the <a href="https://github.com/jbuck2005/brio_compatible_builder_series/tree/main/stl_files">stl_files directory</a><br>
<br>
**Revised & streamlined design for 2021**<br>
<br>
The marketing team is very clever. Our boys received a BRIO Builder ( 34591 ) Builder Motor Set as a shared Christmas gift. In this kit, you get just enough pieces to be fun for a few minutes, but not nearly enough pieces to really make fun stuff. This is where a few hundred dollars of "spare time equivalent" gets spent in CAD to make more pieces for the kiddos without the cognitive expense of having to go shopping (well .. given the current year, let's be honest .. I am NOT going to any stores for anything but essentials).<br>
<br>
The components of this kit are dimensionally based on the aforementioned BRIO builder kit and should be completely compatible. Included are some badly needed "upgrades" and customization. This will be a living project as more components will be added as I dream them up.<br>
<br>
As this design is parametric, the lengths of the beams can be very quickly tailored to your needs. Any directly user editable (critical) dimensions are highlighted with red in the design parameters "spreadsheet" in FreeCAD. Values in green have been proven to be scalable and accurate. Virtually all aspects of each design are editable in the spreadsheet.<br>
<br>
Included are <a href="https://github.com/jbuck2005/brio_compatible_builder_series/tree/master/stl_files">STL files</a> for those who are not yet familiar with <a href="https://github.com/FreeCAD/FreeCAD/blob/master/README.md">FreeCAD</a> include:<br>
<br>
<b><a href="https://github.com/jbuck2005/brio_compatible_builder_series/blob/master/stl_files/fasteners/">Fasteners</a></b><br><img src="https://github.com/jbuck2005/brio_compatible_builder_series/blob/master/stl_files/fasteners/bolt_nut_stop_3-2.png">
bolt length increments of: 15.5mm (8.5mm for nut, 2.3mm for bolt chamfer) plus 5mm for every beam thickness multiplier<br>
nut in thicknesses increments of <b>8.5mm</b> (17, 25.5, 34mm) - standard kit size is 8.5mm<br>
<code>bolt length = bolt head thickness + nut thickness + (bolt diameter / 4) + (bolt length multiplier x beam thickness)</code><br>
<ul>
<li>bolt lengths: 13.5, 27, 40.5, 54mm</li>
<li>standard bolts</li>
<li>double-sided bolts</li>
<li>bolts with nut-stops (to serve as axles) with additional (nut stop length of 5.5mm)</li>
<li>slotted bolts to fit in beam slots</li>
<li>standard washer</li>
</ul>
<br>
<b><a href="https://github.com/jbuck2005/brio_compatible_builder_series/blob/master/stl_files/beams/">Beams</a></b><br><img src="https://github.com/jbuck2005/brio_compatible_builder_series/blob/master/stl_files/beams/normal_4.png">
beams come in the following hole counts: 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 1, 14, 16, 18, 20<br>
<b>slotted beams start at 4 hole equivalents</b><br>
<code>beam length = (# holes - 1) x 16mm + 30mm</code><br>
eg. 4 holes = 78mm, 6 holes = 110mm<br>
<ul>
<li>normal beams have holes every 16mm</li>
<li>slotted beams with holes at the ends and a slot spaced 16mm from each hole, running the length</li>
<br>
</ul>
<b><a href="https://github.com/jbuck2005/brio_compatible_builder_series/tree/master/stl_files/gears">Gears</a></b><br><img src="https://github.com/jbuck2005/brio_compatible_builder_series/blob/master/stl_files/gears/gears.png">
<ul>
<li>single cross-driven gear tooth count: 10, 15, 20, 25</li>
<li>single idler gear tooth count: 10, 15, 20, 25</li>
<li>double cross-driven gear tooth count: 10/10, 10/15, 10/20, 10/25, 15/20, 15/25, 20/25</li>
<li>double idler gear tooth count: 10/10, 10/15, 10/20, 10/25, 15/20, 15/25, 20/25</li>
</ul>
<b><a href="https://github.com/jbuck2005/brio_compatible_builder_series/tree/master/stl_files/wheels_and_pulleys">Wheels and Pulleys</a></b><br>
the kit drive wheel diameter is 46mm<br>
<ul>
<li>drive wheel single post 46mm</li>
<li>drive wheel double post 46mm</li>
<li>drive wheel single post 46mm (with nut-stop)</li>
<li>v pulleys diameters: 20, 30, 40, _<b>46</b>_, 50, 60, 70mm</li>
</ul>
<br>
The design was done in FreeCAD and as mentioned it is fully parametric. I have included the FreeCAD file so that you can modify the design to your heart's content.<br>
<br>
I am open to any suggestions as to how to improve the design work-flow in FreeCAD.<br>
<br>
<b>This design will be the foundation of a completely open source meccano type set. I am seeking collaborators for this project; if there is enough interest, I will draft up a set of "best practices" and establish some engineering criteria (i.e. standardized dimensions, etc).</b><br>
