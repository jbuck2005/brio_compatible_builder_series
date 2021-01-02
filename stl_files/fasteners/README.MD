<b>Fasteners</b><br>
<hr>
Fasteners are bolts, nuts and washers that are dimensionally compatible with the Brio builder toy set.<br>
<br>
Bolts can be broken down into two main categories:
<ol>
  <li>single headed</li>
  <li>double headed</li>
</ol><br>
Within each main category of bolt, four sub-types exist:
<ol>
  <li>regular</li>
  <li>nut stop</li>
  <li>slotted</li>
  <li>slotted nut stop</li>
</ol><br>

<b>regular</b><br>
Regular bolts are bolts which lack any additional features. The length of a regular bolt is designed to clamp one beam thickness equivalent for every length multiplier.<br>
<p>Naming convention: if you wish to clamp one beam with a standard bolt, you would use a regular_1 bolt. If you need to clamp two beams,  you would use a regular_2 bolt.</p><br>
<b><code>regular bolt length = bolt head thickness + nut thickness + (bolt diameter / 4) + (bolt length multiplier x beam thickness)</code></b>
<br>
<b>nut stop</b><br>
Nut stop bolts are bolts with a built in non-threaded portion which serves to stop a nut from clamping some distance to the bolt head. These bolts are most useful when serving as "axles" for beams, wheels, pulleys and idler gears.<br>
<p>Naming convention: if you need an axle for a single beam, you would use a nut_stop_1 bolt. If you need an axle for two beams, you would use a nut_stop_2 bolt. Any number following an _# indicates the nut stop length. For example, say you needed a bolt which was able to accomodate 5 beam thicknesses, but wished to have the nut stop serve as an axle for 2 beams, you would use a nut_stop_5-2 bolt</p>
<code>nut stop bolt length = regular bolt length + (nut stop length x nut stop multiplier)</code>
<br>
<b>slotted</b><br>
<br>
<code>slotted bolt length = regular bolt length + beam thickness</code>
<br>
<b>slotted nut stop</b><br>
<br>
<code>slotted nut stop bolt length = regular bolt length + beam thickness + (nut stop length x nut stop multiplier)</code>
