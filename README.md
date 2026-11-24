# HipPro — Hip prosthesis CAD geometry explorer

Educational interactive visualization of an imported two-solid STEP assembly. Open `index.html` or deploy the repository root through GitHub Pages. No external runtime libraries are required.

## Provenance and rights
Source header: PROTESIS_ASM, Pro/ENGINEER, 2012-02-22, author identifier mundofr. Original design authorship and redistribution rights are unverified. The original STEP is not included. The derived mesh also requires appropriate permission before public redistribution. Do not claim original implant design authorship.

## Method
CadQuery/Open CASCADE imported two valid solids. Tessellation used linear tolerance 0.15 mm and angular tolerance 0.15 rad. Geometry measurements are calculated from CAD solids, not the display mesh. The viewer uses orthographic canvas projection with depth sorting, not a full CAD kernel. Body separation is illustrative. No FEA, material verification or clinical validation was performed.
