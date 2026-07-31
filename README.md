# Handheld-LiDAR-Neighborhood-Accessibility-Dataset
Handheld LiDAR point cloud dataset for neighborhood-scale barrier-free accessibility analysis
## Project Introduction

This repository releases part of the handheld LiDAR point cloud data used in our study on neighborhood-scale barrier-free accessibility assessment.

To support further research, we publicly provide part of the point cloud data.

## Data Description

- Format: LAS/LAZ
- Attributes: XYZ + Intensity
- Approximate point spacing: 0.01 m

Coarse registration transformation matrices are also provided, so that users can transform individual stations into a common coordinate system.

## Data Download

Due to GitHub file size limitations, the dataset is available via Google Drive:

**[Download Link]**  
（Google Drive 文件夹或压缩包链接）

The download package includes:
- 7 point cloud files (`.laz`)
- Coarse registration matrices (`registration_matrix.docx`)

## Data Format

Each point cloud file contains the following attributes:

| Column | Meaning              | Description          |
|--------|----------------------|----------------------|
| 1      | X                    | X coordinate (float) |
| 2      | Y                    | Y coordinate (float) |
| 3      | Z                    | Z coordinate (float) |
| 4      | Intensity            | Intensity value      |



## License

This dataset is released under the MIT License.
