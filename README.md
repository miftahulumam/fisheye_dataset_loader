# KITTI360 LiDAR Point Cloud & Fisheye Camera Dataset Loader

This repository provides source code for dataloading the LiDAR point cloud and fisheye camera image from KITTI360 dataset.
This dataloader also provides depth image projection of point cloud data to fisheye image plane.

## Example
| ![gt_depth](./figures/ground_truth_proj_depth_0.png) | 
|:--:|
| Ground Truth Depth Image |

| ![gt_mis](./figures/misaligned_proj_depth_0.png) | 
|:--:|
| Misaligned Depth Image (Input Image) |

| ![gt_depth](./figures/ground_truth_proj_rgb_0.png) | 
|:--:|
| Ground Truth RGB Image with LiDAR projection |

| ![gt_mis](./figures/misaligned_proj_rgb_0.png) | 
|:--:|
| Ground Truth RGB Image with Misaligned LiDAR projection |