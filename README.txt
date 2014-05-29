GLmol - Molecular Viewer on WebGL/Javascript

== About GLmol ==

GLmol is a 3D molecular viewer based on WebGL and Javascript. You can
embed molecular models in Web pages without using Java or
plugins. GLmol is open-source software licensed under LGPL3 or MIT license.

== Features ==

Currently GLmol has following features. More is coming...

* Read PDB file
* Read SDF/MOL file
* Load local files (File API is used; Safari is not supported)
* Load PDB files directly from RCSB PDB server 
* Rotate/Translate/Zoom model with mouse (touchpanel support is under development) 
* Fog & Slab
* Representations
    - Line (depiction of double/triple bonds is supported for SDF/MOL file)
    - Stick
    - Sphere(van der Waals radius or fixed radius)
    - Star
    - Alpha carbon trace
    - Strand
    - Ribbon
    - Thick ribbon
    - Cylinder & Plate
    - Tube with radius reflecting B factor
    - Combination of above
* Smoothing of beta sheets
* Special representations for Nucleic acid bases
    - Stick
    - Ladder
    - Line
* Coloring
    - By chain
    - By secondary structure (when defined in SHEET/HELIX records)
    - By Elements
    - Gradation (a.k.a chainbow)
    - Polar/Nonpolar
    - B factor
    - Custom
* Crystallography
    - Display unit cell
    - Show crystal packing (when defined in REMARK section)
* Display biological assembly (when defined in REMARK section)
* Perspective or Orthographic projection
* Take screenshot

To run the app:

Clone the repository in your local directory.

run 'npm install'
 
run 'cd app'

run 'npm install consolidate'

run 'nodemon server.js'
