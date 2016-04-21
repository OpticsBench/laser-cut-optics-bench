# laser-cut-optics-bench
Easy to make optics bench using a laser cutter

The files here support the [Hackaday Lasercut Optics Bench Project](https://hackaday.io/project/10707-lasercut-optics-bench)

**This project describes a set of simple optics holders that can be made from common hardware and pieces cut using a laser cutter.**

*Source files are DXF found here and at the Hackaday project page.*

###An expiriment was done using open source tools to convert original inch saved files to inkscape milimeter.

* Read dxf into libreCAD 2D CAD tool
* Save as new name such as adding mm to filename
* Read new file into inkscape and change document properties to letter size
* Select all and change document properties to mm. No resizing is required.
* Verify any known dimension such as actual 6 mm which is 6.282 mm measured by inkscape.

*It is my opinion that 0.282 mm is 0.01110236 inch and is an aceptable tolerance.
The files were created using CAD preferances set in inches but saving as DXF is unit independant so using
LibreCad only makes an inkscape readable file with same number of units.
Any modifications in inkscape will allow the laser cutter to work reasonably accurately and measurably
with mm for final laser bench project*
