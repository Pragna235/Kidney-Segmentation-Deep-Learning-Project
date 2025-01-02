# Kidney-Segmentation-Deep-Learning-Project

* KiTS23 Dataset - https://github.com/neheller/kits23

* Data loading and visualization (without altering the dataset) - `kitsWorkspace_1` : https://colab.research.google.com/drive/1jYatfzwiUODhGNhTSvD7MDwYRKcjPfC5?usp=sharing (with outputs)
  - without outputs : `kitsWorkspace_1` file
 
* Data loading and visualization (without altering the dataset) along with the instances folder that contains annotations of kidneys and tumors - `kitsWorkspace_2` : _Output_ : `visualizations` folder (png images), `visualization_progress.txt` file

* Data Preprocessing step 1 - Windowing - `kitsWorkspace_3` : _output_ : `windowed_images` folder (.nii.gz images), `windowed_visualizations` folder (png images), `windowed_visulization.txt` file
 - `windowed_images` folder link : https://drive.google.com/drive/folders/1R85qyHH_f_09c6MuVytYd14v6L7G6F_b?usp=sharing

* Data Preprocessing steps 2 & 3 - Voxel Spacing Adjustment and Image Slicing : `kitsWorkspace_4` : _Output_ : `resampled_and_sliced_images` folder (.nii.gz images)(approx 190 gb), `resampled_visualization` folder (png images) and `resampled_progress.txt` file.

* Model Architecture - Encoder, Decoder, Loss functions : `kitsWorkspace_5` (part 1)

* Coronal, Sagittal and Axial visualizations (Data preprocessing experimentation) - `kitsWorkspace_6`

* Resampling of the Ground truths as well (Segmentation files) Pre-precessing : `kitsWorkspace_7` : _Output_ : `resampled_and_sliced_segmentations_files` folder (.nii.gz files), `segmentation_visualizations` folder (aka resampled_segmentation_visualizations) (png files) and `segmentation_progress.txt` file
  - `resampled_and_sliced_segmentation_files` : https://drive.google.com/drive/folders/1pFqwRAfT1_xifrfoz0TFkfmXYNhx932h?usp=sharing
 
* Extraction of 2D slices from the 3D images for training purposes : `kitsWorkspace_9`

* Extraction of 2D slices from the 3D images for training purposes attempt 2 : `kitsWorkspace_10` : _Output_ : `2d_slices` folder ( which contains 2 more folders names `images` and `masks` where again each contains 489 case folders again where each case folder contains the images of the number of slices present in .nii.gz format )
  - `E:\kits23\2d_slices\images\00000\slice_000.nii.gz`
  - `E:\kits23\2d_slices\masks\00000\slice_000.nii.gz`

  - Another output is the `png_slices` folder that contains the same hierarchy as above where instead of the .nii.gz format, all files are in a viewable .png format
  - Another output is the `zip_slices` format where some of the `png_slices` folder's files are uploaded for later purposes. Currently, `kitsWorkspace_10`'s output's are stored in the External harddisk, so for future purposes, some of those output are saved in the form of zip files for viewing in case.
  - Another output : `processed_cases.json` file (for checking the progress)
