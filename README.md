
- data/my_scene_video.mp4  
  This is the original video I captured by walking around a dining table. It serves as the input for frame extraction and SLAM reconstruction.

- code/SLAM_Demo.mlx  
  A MATLAB Live Script containing:  
  1. Video frame extraction  
  2. Map initialization and feature-matching visualization  
  3. Tracking, local mapping, loop closure detection, and global optimization  
  4. Final 3D point cloud and camera trajectory plots  

  Simply open this `.mlx` in MATLAB and run each section in order to see the reconstruction process and results in real time.

- report/vSLAM_Report.pdf  
  The detailed report including:  
  - Data collection and camera calibration methodology  
  - Keyframe matching montages and 3D visualizations from each stage  
  - Algorithm workflow, parameter tuning, and result analysis  
  - Conclusions and lessons learned  

---

## Quick Start

1. Clone or download this repository.  
2. In MATLAB, change the current folder to the project root.  
3. Open `code/SLAM_Demo.mlx` in the Live Editor and run all sections sequentially.  
4. View the generated figures in the report or export your own versions.

All required files are included—no additional downloads needed. Enjoy reproducing the results!  
