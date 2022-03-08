
This dataset includes 5008 images.
Faces are annotated in YOLO v5 PyTorch format.

Image naming convention (before first underscore):
Original images:
1. sober image - Soberface<image-number>A
2. drunk image - Drunkface<image-number>B

Augmented images:
1. Sober image - Soberface<image-number>A<augmentation-type>
2. Drunk image - Drunkface<image-number>B<augmentation-type>

Augmentation-type:
1 = horizontal flip
2 = clockwise rotation
3 = anticlockwise rotation


Labels format:
<class> <x1> <y1> <x2> <y2>

Class:
0 - Drunk
1 - Sober



