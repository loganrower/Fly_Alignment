# Utilizing the fly alignment and image node with ROS

The scripts within this repository will be paird with the Warren-Lab Magno-Test in order to run experiments utilizing the Magnotether.

The image node will subscribe to the raw image that is generated from the the pylon camera.

The fly_align_node also is subscribed to this image and will draw the concentric circles in the same way that the single image was used. It is important to note that for both this node and the image node the image will be updating continuously.