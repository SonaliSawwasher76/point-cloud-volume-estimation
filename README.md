# Stockpile Volume Computation using Point Cloud Data

This project computes the volume of a stockpile using 3D point cloud data and Python.

## Workflow
1. Load point cloud data
2. Detect ground plane using RANSAC
3. Separate stockpile from ground
4. Remove noise from point cloud
5. Downsample point cloud
6. Generate triangular mesh surface
7. Compute stockpile volume

## Libraries Used
- Open3D
- NumPy
- SciPy
- Matplotlib

## Output
The notebook visualizes the point cloud processing pipeline and calculates the final stockpile volume.
