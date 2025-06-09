# Geo-Image Matching & Satellite Harmonization

This project provides a robust template matching, feature-based matching, geometric transformation, and satellite image harmonization. It is designed for evaluating and visualizing region detection and alignment in satellite imagery from multiple sources.

## Contents

- `matching/tests/`: Test datasets for image matching and region detection.
  - Each subfolder (e.g., `1/`, `2_rotated/`) contains:
    - `search_area_mask.png`: Large image containing the target region.
    - `regoins_segments/`: Template regions (small image segments).
    - `result.csv`: Ground truth results for evaluation.

- `satlite_gap/`: Satellite images from multiple providers (Bing, Google, MapBox, Yandex).

- **Notebooks**:
  - `template_matching_multiscale.ipynb`: Multi-scale template matching and evaluation.
  - `template_matching_keypointHomography.ipynb`: Feature-based matching using keypoints and homography.
  - `feature_matching.ipynb`: Feature matching and visualization between satellite images.
  - `geometric_transformation.ipynb`: Affine and homography alignment of satellite images.
  - `histogram_matching.ipynb`: Histogram matching for harmonizing satellite image appearance.
  - `harmonization.ipynb`: Advanced harmonization and evaluation of satellite images.

