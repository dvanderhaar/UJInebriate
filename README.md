
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

Please cite our work:
@inproceedings{bhango2019model,
  title={A model for inebriation recognition in humans using computer vision},
  author={Bhango, Zibusiso and van der Haar, Dustin},
  booktitle={Business Information Systems: 22nd International Conference, BIS 2019, Seville, Spain, June 26--28, 2019, Proceedings, Part I 22},
  pages={259--270},
  year={2019},
  organization={Springer}
}

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
