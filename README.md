# OpenSCAD Spiral Extrude

The `spiral_extrude` OpenSCAD module does what `linear_extrude` and `rotate_extrude` can not do. Threads and other spiraling structures can be created with `spiral_extrude`.

Original code written by AKADAP, published 11 Dec 2016 on [ThingiVerse](https://www.thingiverse.com/thing:1958354). This repositoru is an attempt to mirror for continuous future use. It can happen that some improvements of the code happen over time.

## Usage

Clone the repository in your OpenSCAD project directory. Use as follows.

```
use <openscad_spiral_extrude/spiral_extrude.scad>
extrude_spiral(StartRadius = 20, ZPitch = 2, Angle = 340, StepsPerRev = 180){  
  square(size = [2, 1], center = true);
}
```

Consult the `spiral_extrude.scad` file for more examples.

## License

This work is licensed under a [GNU General Public License, version 2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
