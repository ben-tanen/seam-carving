## Seam Carving

This is a project exploring [the seam carving algorithm](http://www.faculty.idc.ac.il/arik/SCWeb/imret/imret.pdf) for cropping images. For a good explainer on seam carving, check out [Grant Sanderson's (3Brown1Blue) lecture](https://www.youtube.com/watch?v=rpB6zQNsbQU) explaining the topic. For more detail, I would also recommend [the original paper](http://www.faculty.idc.ac.il/arik/SCWeb/imret/imret.pdf) outlining the algorithm.

This repo contains some experiments using the seam carving algorithm, mainly focusing on a comparison of how seam carving might improve upon other cropping algorithms (e.g., the algorithm used by Twitter for image preview).

The code used for seam carving was taken from [Karthik Karanth's post](https://karthikkaranth.me/blog/implementing-seam-carving-with-python/) for implementing the algorithm in python. Karthik's original code can be found in `src/carver.py` and can be used as `python src/carver.py c 0.5 imgs/img.jpg imgs/img-cropped.jpg`

![Image of landscape](imgs/landscape.JPG)

![Image of landscape after it has been seam carving cropped](imgs/landscape-cropped.JPG)