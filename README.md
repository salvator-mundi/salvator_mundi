# Salvator Mundi Project
This repository contain 3D models, textures, scene setup, codes that have been used to generate renderings in two _Salvator Mundi_ papers:

***On the Optical Accuracy of the Salvator Mundi*** [[intro](https://www.ics.uci.edu/~zhanhanl/web_files/projects/salvator_mundi/salvator_mundi_hollowness.md.html)]

***Inverse-Rendering Based Analysis of the Fine Illumination Effects in the Salvator Mundi*** [[intro](https://www.ics.uci.edu/~zhanhanl/web_files/projects/salvator_mundi/salvator_mundi.md.html)]
## Mitsuba Render
We used Mitsuba 0.5.0 for the rendering. 
[Mitsuba 0.5.0](http://www.mitsuba-renderer.org/index_old.html)

Output results are HDR files. You can use following software to view HDR files:
[HDR file viewer](https://bitbucket.org/edgarv/hdritools)
## Files
```text
salvator_mundi/
├── component/
├── object/
├── texture/
├── rendering_defects_threewhitespots/
├── rendering_hollowness/
└── results
     ├── rendering_defects_threewhitespots/
     └── rendering_hollowness/
```
**component**

Commonly used scripts for different lighting setups.

**object**

3D models

**texture**

Textures

**rendering_defects_threewhitespots**

Rendering scripts that generate defects, three white spots. Used in paper  *Inverse-Rendering Based Analysis of the Fine Illumination Effects in the Salvator Mundi*

**rendering_hollowness**

Rendering scripts that generate hollow orb. Used in paper *On the Optical Accuracy of the Salvator Mundi*

**results**

This folder contains renderings generated by scripts in "rendering" folders.
