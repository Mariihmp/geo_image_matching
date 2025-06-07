# Project Overview

This project appears to involve image segmentation and matching, possibly for satellite imagery analysis. The structure suggests the use of test datasets and region segmentation for evaluation.

## Directory Structure

```
project/
├── project.pdf                  # Project documentation or report
├── matching/
│   └── tests/
│       ├── 1/
│       │   ├── result.csv
│       │   ├── search_area_mask.png
│       │   └── regoins_segments/   # Segmented region images (0.png, 1.png, ...)
│       └── 2_rotated/
│           ├── result.csv
│           ├── search_area_mask.png
│           └── regoins_segments/   # Segmented region images (0.png, 1.png, ...)
└── satlite_gap/
    └── satlite_gap/
        ├── Bing_Map_Tiles(*).tif
        ├── Google_Map_Tiles(*).tif
        ├── MapBox_Map_Tiles(*).tif
        └── Yandex_Map_Tiles(*).tif
```

## Contents
- **project.pdf**: Main documentation or report for the project.
- **matching/tests/**: Contains test cases for image matching and segmentation.
  - Each test folder (e.g., `1/`, `2_rotated/`) includes:
    - `result.csv`: Results of the matching/segmentation.
    - `search_area_mask.png`: Mask image for the search area.
    - `regoins_segments/`: Folder with segmented region images.
- **satlite_gap/satlite_gap/**: Contains satellite map tiles from various providers (Bing, Google, MapBox, Yandex) in TIFF format.



## Notes
- The project structure suggests a focus on geospatial image analysis, segmentation, and comparison across different map providers.
- For more details, refer to the documentation or contact the project maintainer.


Project 1: Satellite Image Harmonization
The goal here is to make satellite images from different providers (Google, Bing, etc.) look more similar, so a machine learning model trained on one provider's images can work well on the others. We'll use a classic technique called Histogram Matching.


Project 2: Target Area Detection in Aerial Imagery using feature based matching 
The main goal of this project is to find the exact location of a small image (template) inside a much larger image (search area)