# laser-cut-optics-bench
Easy to make optics bench using a laser cutter


![Icon Suggestion](https://raw.githubusercontent.com/OpticsBench/laser-cut-optics-bench/master/images/Icon%20Suggestion.JPG)

The files here support the [Hackaday Lasercut Optics Bench Project](https://hackaday.io/project/10707-lasercut-optics-bench)

*After the initial submission a [Gitter Chat Room](https://gitter.im/OpticsBench/laser-cut-optics-bench) was created to Instant Message separate from the Hack A Day Prize.*

**This project describes a set of simple optics holders that can be made from common hardware and pieces cut using a laser cutter.**

*Source files are DXF found here and at the Hackaday project page.*

###An experiment was done using open source tools to convert original saved files (in inches) to inkscape (in millimeters).

* Read dxf into libreCAD 2D CAD tool
* Save as new name such as adding mm to filename
* Read new file into inkscape and change document properties to letter size
* Select all and move onto page then change document properties to mm. No resizing is required.
* Verify any known dimensions such as actual 6 mm which is 6.282 mm measured by inkscape.

*It is my opinion that 0.282 mm is 0.01110236 inch and is an acceptable tolerance.
The files were created using default CAD preferences (inches) but saving as DXF is unit independent so using
LibreCad makes an Inkscape readable file with same number of units.
Any modifications in Inkscape will allow the laser cutter to work reasonably accurately and measurably
with mm for final laser bench project*
