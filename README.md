# feathericons-for-mobile
Free, MIT-based redistribution of beautiful open source icon set [Feather](https://github.com/feathericons/feather) converted to various formats particularly useful for mobile developers (Android and iOS). 

I found original vector `svg` format a bit painful to work with on my projects, so I decided to share my renders here.


### Contents
This repository contains [Feather](https://github.com/feathericons/feather) icons in diverse array of different formats, types and resolutions which are 100% ready to use out of the box in either Android or iOS application development.


1. `/svg` folder contains original vector `svg` files on 24x24 grid.

2. `/ios` folder contains vector `pdf` files.

3. `/android` folder contains rasterized copies of original icons in `png`.

   Separate files for all Android screen densities available (`ldpi, mdpi, hdpi, xhdpi, xxhdpi, xxxhdpi, tvdpi`). 
   
   All densities were rendered slightly above Google's suggested standard for dpi count for given density, as per [here](https://developer.android.com/training/multiscreen/screendensities).

   `xxxhdpi`s are rendered at `256x256px@1024dpi` (standard is ~640dpi for xxxhdpi) and all lower densities are scaled accordingly (going as low as `64x64px@192dpi` for `ldpi` density).
   
4. `/png-2048px` contains ultra-high resolution (2048x2048px, 8192 pixels/inch) `png` rasters.
      
5. `/png-1024px` contains slightly lower resolution (1024x1024px, 4096 pixels/inch) `png` rasters.

6. Heavily optimized and compressed versions of all raster images are available on branch `imgbot` ([link](https://github.com/sharaquss/feathericons-for-mobile/tree/imgbot)). Details in the [pull request](https://github.com/sharaquss/feathericons-for-mobile/pull/1).


<br/>


### Feather
Original, live repo of Feather icons can be found here: https://github.com/feathericons/feather.

Website of the project showcasing all of the icons (with search function as well): https://feathericons.com.

If you found this redistribution or the original icon set useful, **I strongly encourage** starring the [repository](https://github.com/feathericons/feather) and/or **donating** few bucks to the author(s) [here](https://www.paypal.me/colebemis/5).
