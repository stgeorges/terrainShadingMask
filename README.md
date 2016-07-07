![Logo](https://github.com/stgeorges/terrainShadingMask/blob/master/miscellaneous/images/logo.png)

# terrainShadingMask
terrainShadingMask is a free collection of terrain masks for various locations.
They are given in geometrical (.obj files) and textual (.hor files) forms.



# Description
A terrain shading mask is a diagram which maps the silhouette of the surrounding terrain (hills, valleys, mountains, tree tops...) around the [chosen location](https://www.google.com/maps/place/42%C2%B041'25.6%22N+22%C2%B010'17.1%22E/@42.6904405,22.1708855,135m/data=!3m1!1e3!4m5!3m4!1s0x0:0x0!8m2!3d42.690457!4d22.171431):

<p align="center">
  <img src="https://github.com/stgeorges/terrainShadingMask/blob/master/miscellaneous/images/surdulica_panorama.jpg" width="650"/>
</p>

<p align="center">
  <img src="https://github.com/stgeorges/terrainShadingMask/blob/master/miscellaneous/images/terrain_shading_mask_surdulica.jpg" width="450"/>
</p>

Building simulation softwares (IES VE, Trnsys 3D, Design Builder...) can use the .obj geometry files, while solar-photovoltaic-thermal software (PV*SOL, PVsyst...) can use .hor files.



# Installation
No installation is required.

One just needs to look into the ```objFiles``` folder if one is looking for a geometric representation of the mask, or into the ```horFiles``` folder for textual representation of the mask.
Both folders contain ```0_terrain_shading_masks_download_links.tsv``` files which can be used to more easily search the masks according to a certain continent and country, and get their direct download links.



# Additional info


All .obj and .hor files are created with the use of Grasshopper 'Terrain shading mask' and 'Horizon Angles' components which are part of the [Ladybug](https://github.com/stgeorges/ladybug) project. Free and open source environmental plugin. Ladybug is licensed under the GPL-3.0+ license: http://spdx.org/licenses/GPL-3.0+.


'Terrain shading mask' component uses:

- [OpenTopography](http://www.opentopography.org/) SRTM GL3 Global 90m raster data.


- [Viewfinderpanoramas](http://viewfinderpanoramas.org) SRTM 3 arc second raster data.


- [C# GDAL libraries](http://gisinternals.com/) to project the SRTM raster data.


# Authors:

Developed by Djordje Spasic with assistance of Bojan Savric.
Support on various issues given by:


Alec Bennett, Andrew T. Young, Chen Weiqing, Christopher Crosby, Dragan Milenkovic, Even Rouault, Graham Dawson, Izabela Spasic, Jonathan de Ferranti, LiMinlu, Menno Deij-van Rijswijk, Michal Migurski, Mostapha Sadeghipour Roudsari, Paul Meems, Tamas Szekeres, Ulrich Deuschle
