A reference repo for out currently used KiCAD libs.
It's referenced by all hardware projects, so don't
update without a reason.

We reference the KiCad libs as submodules, so to get them, do:

`git clone git@bitbucket.org:okrasolar/kicad-libs.git --recursive`

It you have limited bandwidth internet access, and don't want to download
1Gb worth of component 3D models, do:

`git clone git@bitbucket.org:okrasolar/kicad-libs.git`

`cd kicad-libs`

`git submodule update --init kicad-footprints`

`git submodule update --init kicad-symbols`

Then if you want to get the 3D models later:

`git submodule update --init kicad-packages3D`
`
