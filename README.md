# Cpp_Image_filter
Image filter with cpp

Given an image(format .ppm) as input and the filtering it creates a new image with the filters applied.

Filters that can be applied are **gamma, linear, laplace** and any combination of them.

**Some examples(insert in argv):**
- filter -f gamma 2.0 image.ppm
- filter -f linear -1 -1 -1 1 1 1 image.ppm
- filter -f laplace

