# Depth map viewer
Creates a 3D parallax effect from images that have depth map data embedded.


* Uses https://github.com/MikeKovarik/exifr to extract EXIF data on page load 
* Uses https://github.com/pixijs/pixijs to create the 3D box
* To change sample image, edit [pen](https://codepen.io/r0d3r1ck0rd0n3z/pen/eYxPbEv) and replace the SRC with your own URL
* Note that some image hosting services will strip EXIF data during upload
<br>

## Image requirements

Requires only one image. However, image must have an embedded depth map. iPhone images taken in portrait mode [will already have the depth map data](https://developer.apple.com/documentation/avfoundation/additional_data_capture/capturing_photos_with_depth) embedded. For Android, the *Google Camera* app can take pictures with depth data via the *Lens Blur* feature. See links below for more info: 

* [Tutorial on the lens blur feature for Google camera app (Android)](https://www.youtube.com/watch?v=GmpmhvVlklc)
* [Google Camera Lens Blur Mode](https://www.youtube.com/watch?v=_CqXbX4i240)
* [How to use the Lens Blur mode in Google Camera](https://www.youtube.com/results?search_query=google+lens+blur)

<br>

## Codepen

Edit codepen here: <br>
https://codepen.io/r0d3r1ck0rd0n3z/pen/eYxPbEv
<br>


## Live Demo
View demo here: <br>
https://r0d3r1ck0rd0n3z.github.io/Depth-map-viewer/
