Install Ladybug _Terrain shading mask_ component on Rhino 5 x86.
==================

Follow these four simple steps:

**1)** Go to: http://gisinternals.com/release.php.

Click on the latest ```GDAL 1.x.x version and MapServer 6.x.x```  ```MSVC 2013 win32``` version (at the moment that may be: ```release-1800-gdal-1-11-4-mapserver-6-4-3```. Maybe a new version has been released in the mean time, for example: ```release-1800-gdal-1-11-5-mapserver-6-4-5```).
Here is a screenshot of the above link when ```release-1800-gdal-1-11-4-mapserver-6-4-3``` was the latest version:

<p align="center">
  <img src="https://github.com/stgeorges/terrainShadingMask/blob/master/miscellaneous/images/step1a_32bit.jpg" width="450"/>
</p>

Then click on the link at the very top. This will activate the .zip file download.
Again here is a screenshot of the link when ```release-1800-gdal-1-11-4-mapserver-6-4-3``` was the latest version:

<p align="center">
  <img src="https://github.com/stgeorges/terrainShadingMask/blob/master/miscellaneous/images/step1b_32bit.jpg" width="450"/>
</p>


==================
**2)** Check if the downloaded .zip file has been blocked: right click on it, choose ```Properties```. If there is an ```Unblock``` button click on it, and then click on ```OK```. If there is no ```Unblock``` button, just click on ```OK```:

<p align="center">
  <img src="https://github.com/stgeorges/terrainShadingMask/blob/master/miscellaneous/images/step2_32bit.jpg" width="250"/>
</p>


==================
**3)** Extract the downloaded .zip file content anywhere.
Then copy the content from its ```bin``` folder to the terrain shading mask libraries folder:

<p align="center">
  <img src="https://github.com/stgeorges/terrainShadingMask/blob/master/miscellaneous/images/step3a_32bit.jpg" width="450"/>
</p>

You can find where terrain shading mask libraries folder is located by checking the component's ```librariesFolder``` output:

<p align="center">
  <img src="https://github.com/stgeorges/terrainShadingMask/blob/master/miscellaneous/images/step3b_32bit.jpg" width="450"/>
</p>

In the last two photos it is ```c:\ladybug\terrain shading mask libraries 32-bit``` but in your case it may be a different one.


==================
**4)** Copy the content from its ```bin\gdal\csharp``` folder to the same ```c:\ladybug\terrain shading mask libraries 32-bit``` folder:

<p align="center">
  <img src="https://github.com/stgeorges/terrainShadingMask/blob/master/miscellaneous/images/step4_32bit.jpg" width="450"/>
</p>

That's it!
Now close the Grasshopper and Rhino, and run both again.
 

==================
**Note**: Windows XP operating system may need a different version of GDAL libraries not available from the [gisinternals.com](http://gisinternals.com/release.php) website.
If you are using Windows XP, instead of following the step 1, download the appropriate XP GDAL libraries from: https://www.dropbox.com/s/08mt7r45l68s27v/release-1500-gdal-1-11-1-mapserver-6-4-1_windowsXP.zip?dl=0

Then follow the steps 2, 3 and 4.
