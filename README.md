# POVnoiseillusion
A vanilla html/js implementation of the pov noise trick.


Upload an image with a transparent background, and it will be used as a mask, all opaque parts of the image will become randomised noise that you will only be able to see while the animation is playing. This took some clever trickery to make it efficient in browsers. 


Be sure that all pixels in your mask.png are either fully opaque, or fully white, otherwise you will be able to see where your shape was in screenshots since it will be the only part of the image with semi transparent pixels.
