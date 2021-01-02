<h1><b>Fasteners</b></h1>
Fasteners are <a href=#Bolts>bolts</a>, <a href=#Nuts>nuts</a> and <a href=#Washers>washers</a> that are dimensionally compatible with the Brio builder toy set.<br>
<h2>Bolts</h2>
Bolts can be broken down into the following categories:
<ol>
  <li>single headed - hexagonal head with a single threaded shaft</li>
  <li>double headed - two threaded shafts separated by hexagonal shaped fixed washer</li>
  <li>angled - future feature - threaded shafts at discrete angular interections (e.g. two threaded shafts at a 90° angle)</li>
</ol><br>
Within the main categories, bolts can be futher sub-dividied into the following profiles:
<ol>
  <li><a href=#regular>regular</a></li>
  <li><a href=#nut-stop>nut stop</a></li>
  <li><a href=#slotted>slotted</a></li>
  <li><a href=#slotted-nut-stop>slotted nut stop</a></li>
</ol>
<b><h3>regular</h3></b><br><img src="https://github.com/jbuck2005/brio_compatible_builder_series/blob/master/stl_files/fasteners/bolt_regular_3.png">
Regular bolts are bolts which lack any additional features. The length of a regular bolt is designed to clamp one beam thickness equivalent for every length multiplier.<br>
Naming convention: if you wish to clamp one beam with a standard bolt, you would use a regular_1 bolt. If you need to clamp two beams,  you would use a regular_2 bolt. The image above would be regular_3<br>
<b><br><code>regular bolt length = <a href="https://github.com/jbuck2005/brio_compatible_builder_series/blob/master/brio_builder_set-dimensions.csv">bolt head thickness + nut thickness + (bolt diameter / 4) + (bolt length multiplier x beam thickness)</a></code></b><br>
<br>
<b><h3>nut stop</h3></b><br><img src="https://github.com/jbuck2005/brio_compatible_builder_series/blob/master/stl_files/fasteners/bolt_nut_stop_3-2.png">
Nut stop bolts are bolts with a built in non-threaded portion which serves to stop a nut from clamping some distance to the bolt head. These bolts are most useful when serving as "axles" for beams, wheels, pulleys and idler gears.<br>
Naming convention: if you need an axle for a single beam, you would use a nut_stop_1 bolt. If you need an axle for two beams, you would use a nut_stop_2 bolt. Any number following an 'n-dash' (\-) indicates the nut stop length. For example, say you needed a bolt which was able to accomodate 5 beam thicknesses, but wished to have the nut stop serve as an axle for 2 beams, you would use a nut_stop_5-2 bolt. The image above would be nut_stop_3-2<br>
<br><code>nut stop bolt length = regular bolt length + <a href="<a href="https://github.com/jbuck2005/brio_compatible_builder_series/blob/master/brio_builder_set-dimensions.csv">(nut stop length x nut stop multiplier)</a></code><br>
<br>
<b><h3>slotted</h3></b><br><img src="https://github.com/jbuck2005/brio_compatible_builder_series/blob/master/stl_files/fasteners/bolt_slotted_3.png">
Slotted bolts have an oval neck profile immediately below the bolt head that allows the bolt to be retained in a slotted beam. These bolts can be used to clamp an object anywhere along the slot length.<br>
Naming convention: if you wish to clamp one beam with a slotted bolt, you would use a slotted_1 bolt. If you need to clamp two beams,  you would use a slotted bolt.  The image above would be slotted_3<br>
<br><code>slotted bolt length = regular bolt length + <a href="https://github.com/jbuck2005/brio_compatible_builder_series/blob/master/brio_builder_set-dimensions.csv">beam thickness</a></code><br>
<br>
<b><h3>slotted nut stop</h3></b><br><img src="https://github.com/jbuck2005/brio_compatible_builder_series/blob/master/stl_files/fasteners/bolt_slotted_3-2.png">
Slotted nut stop bolts have an oval neck profile immediately below the bolt head as well as a nut stop profile, allowing the slotted bolt to slide along a beam slot while acting as an axle.<br>
Naming convention: Any number following an an 'n-dash' (\-) indicates the nut stop length. For example, say you needed a bolt which was able to accomodate 5 beam thicknesses, but wished to have the nut stop serve as an axle for 2 beams, you would use a slotted_nut_stop_5-2 bolt. The image above would be slotted_nut_stop_3-2<br>
<br><code>slotted nut stop bolt length = regular bolt length + beam thickness + (nut stop length x nut stop multiplier)</code>
<h2>Nuts</h2>
Nuts are standard clamping hardware that come in a variety of thicknesses.
<h2>Washers</h2>
Washers are available in incremental thicknesses with standardized inner and outer diameters.
