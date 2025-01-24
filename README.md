# Pixel-Island-Generator-PIG-
Pixel Island Generator (PIG) is a Python-based tool for generating high-resolution, pixelated maps of islands surrounded by water. It provides a streamlined process for converting an uploaded image into a single, contiguous island with smooth edges and detailed visualization. The generated maps can be used for games, simulations, or as a basis for further map generation.

Single Island Generation:

Converts any uploaded grayscale image (or color image converted to grayscale) into a single, smoothed island surrounded by water.
Automatically removes stray landmasses and retains only the largest contiguous landmass.
Customizable Resolution:

User-defined grid dimensions (e.g., 400x400) allow for fine-grained control over the resolution of the map.
High-resolution output is achieved by upscaling with an adjustable upscale_factor.
Land/Water Classification:

Dynamically determines land and water regions using histogram-based thresholding, ensuring flexibility for different types of input images.
Edge Smoothing:

Smooths jagged edges using Gaussian filtering, creating a natural and polished island shape.
Checkerboard Visualization:

Alternating land pixel colors (checkerboard pattern) make it easy to identify individual pixel boundaries in the high-resolution output.
