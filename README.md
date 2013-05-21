Gerchberg
=========

Lightpipes Gerchberg Saxton
1) To download: https://github.com/nvutri/Gerchberg/archive/master.zip
2) Main program running Gerchberg algorithm: Gerchberg.vi

How to use:
1) Please use other tools to crop images, in case the picture has problems
2) Use Remove Noise.vi to remove noise from an image. Then save it.
3) Use Gerchberg Image Manipulation.vi. It will:
    - interpolate 2 images to the same resolution
    - center images
    - output images with the same specified final size using cropping and padding
    - save images using 2 buttons
4) Use Gerchberg.vi to run the algorithm. The forwarding feature will show up once 
iterations are done.

Notes:
1) All images run in Gerchberg.vi are in float mode. Thus, they cannot be saved.
One suggestion for now is to print screen and crop it.
2) The forwarded picture can look as an explosion whereas it is not.
3) Please put at least 20 iterations for Gerchberg to get a reasonable result.
