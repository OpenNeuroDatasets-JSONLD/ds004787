Node: single_subject_24563_wf (anat_preproc_wf (brain_extraction_wf (norm (fixes)
=================================================================================


 Hierarchy : fmriprep_23_2_wf.single_subject_24563_wf.anat_preproc_wf.brain_extraction_wf.norm
 Exec ID : norm


Original Inputs
---------------


* args : <undefined>
* collapse_output_transforms : True
* convergence_threshold : [1e-08, 1e-08, 1e-09]
* convergence_window_size : [10, 10, 15]
* dimension : 3
* environ : {'NSLOTS': '16'}
* fixed_image : ['/home/zugmana2/.cache/templateflow/tpl-OASIS30ANTs/tpl-OASIS30ANTs_res-01_T1w.nii.gz', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/lap_tmpl/tpl-OASIS30ANTs_res-01_T1w_maths.nii.gz']
* fixed_image_mask : <undefined>
* fixed_image_masks : ['/home/zugmana2/.cache/templateflow/tpl-OASIS30ANTs/tpl-OASIS30ANTs_res-01_desc-BrainCerebellumExtraction_mask.nii.gz']
* float : True
* initial_moving_transform : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/init_aff/initialization.mat']
* initial_moving_transform_com : <undefined>
* initialize_transforms_per_stage : False
* interpolation : LanczosWindowedSinc
* interpolation_parameters : <undefined>
* invert_initial_moving_transform : <undefined>
* metric : ['MI', 'MI', ['CC', 'CC']]
* metric_item_trait : <undefined>
* metric_stage_trait : <undefined>
* metric_weight : [1.0, 1.0, [0.5, 0.5]]
* metric_weight_item_trait : 1.0
* metric_weight_stage_trait : <undefined>
* moving_image : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/inu_n4/mapflow/_inu_n40/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template_maths_corrected.nii.gz', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/lap_target/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template_maths_corrected_maths.nii.gz']
* moving_image_mask : <undefined>
* moving_image_masks : <undefined>
* num_threads : 16
* number_of_iterations : [[1000, 500, 250, 100], [1000, 500, 250, 100], [50, 10, 0]]
* output_inverse_warped_image : <undefined>
* output_transform_prefix : anat_to_template
* output_warped_image : True
* radius_bins_item_trait : 5
* radius_bins_stage_trait : <undefined>
* radius_or_number_of_bins : [32, 32, [4, 4]]
* random_seed : <undefined>
* restore_state : <undefined>
* restrict_deformation : <undefined>
* sampling_percentage : [0.25, 0.25, [1.0, 1.0]]
* sampling_percentage_item_trait : <undefined>
* sampling_percentage_stage_trait : <undefined>
* sampling_strategy : ['Regular', 'Regular', ['None', 'None']]
* sampling_strategy_item_trait : <undefined>
* sampling_strategy_stage_trait : <undefined>
* save_state : <undefined>
* shrink_factors : [[8, 4, 2, 1], [8, 4, 2, 1], [4, 2, 1]]
* sigma_units : ['vox', 'vox', 'vox']
* smoothing_sigmas : [[4.0, 2.0, 1.0, 0.0], [4.0, 2.0, 1.0, 0.0], [2.0, 1.0, 0.0]]
* transform_parameters : [(0.1,), (0.1,), (0.1, 3.0, 0.0)]
* transforms : ['Rigid', 'Affine', 'SyN']
* use_estimate_learning_rate_once : <undefined>
* use_histogram_matching : True
* verbose : True
* winsorize_lower_quantile : 0.025
* winsorize_upper_quantile : 0.975
* write_composite_transform : False


Execution Inputs
----------------


* args : <undefined>
* collapse_output_transforms : True
* convergence_threshold : [1e-08, 1e-08, 1e-09]
* convergence_window_size : [10, 10, 15]
* dimension : 3
* environ : {'NSLOTS': '16'}
* fixed_image : ['/home/zugmana2/.cache/templateflow/tpl-OASIS30ANTs/tpl-OASIS30ANTs_res-01_T1w.nii.gz', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/lap_tmpl/tpl-OASIS30ANTs_res-01_T1w_maths.nii.gz']
* fixed_image_mask : <undefined>
* fixed_image_masks : ['/home/zugmana2/.cache/templateflow/tpl-OASIS30ANTs/tpl-OASIS30ANTs_res-01_desc-BrainCerebellumExtraction_mask.nii.gz']
* float : True
* initial_moving_transform : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/init_aff/initialization.mat']
* initial_moving_transform_com : <undefined>
* initialize_transforms_per_stage : False
* interpolation : LanczosWindowedSinc
* interpolation_parameters : <undefined>
* invert_initial_moving_transform : <undefined>
* metric : ['MI', 'MI', ['CC', 'CC']]
* metric_item_trait : <undefined>
* metric_stage_trait : <undefined>
* metric_weight : [1.0, 1.0, [0.5, 0.5]]
* metric_weight_item_trait : 1.0
* metric_weight_stage_trait : <undefined>
* moving_image : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/inu_n4/mapflow/_inu_n40/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template_maths_corrected.nii.gz', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/lap_target/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template_maths_corrected_maths.nii.gz']
* moving_image_mask : <undefined>
* moving_image_masks : <undefined>
* num_threads : 16
* number_of_iterations : [[1000, 500, 250, 100], [1000, 500, 250, 100], [50, 10, 0]]
* output_inverse_warped_image : <undefined>
* output_transform_prefix : anat_to_template
* output_warped_image : True
* radius_bins_item_trait : 5
* radius_bins_stage_trait : <undefined>
* radius_or_number_of_bins : [32, 32, [4, 4]]
* random_seed : <undefined>
* restore_state : <undefined>
* restrict_deformation : <undefined>
* sampling_percentage : [0.25, 0.25, [1.0, 1.0]]
* sampling_percentage_item_trait : <undefined>
* sampling_percentage_stage_trait : <undefined>
* sampling_strategy : ['Regular', 'Regular', ['None', 'None']]
* sampling_strategy_item_trait : <undefined>
* sampling_strategy_stage_trait : <undefined>
* save_state : <undefined>
* shrink_factors : [[8, 4, 2, 1], [8, 4, 2, 1], [4, 2, 1]]
* sigma_units : ['vox', 'vox', 'vox']
* smoothing_sigmas : [[4.0, 2.0, 1.0, 0.0], [4.0, 2.0, 1.0, 0.0], [2.0, 1.0, 0.0]]
* transform_parameters : [(0.1,), (0.1,), (0.1, 3.0, 0.0)]
* transforms : ['Rigid', 'Affine', 'SyN']
* use_estimate_learning_rate_once : <undefined>
* use_histogram_matching : True
* verbose : True
* winsorize_lower_quantile : 0.025
* winsorize_upper_quantile : 0.975
* write_composite_transform : False


Execution Outputs
-----------------


* composite_transform : <undefined>
* elapsed_time : <undefined>
* forward_invert_flags : <undefined>
* forward_transforms : <undefined>
* inverse_composite_transform : <undefined>
* inverse_warped_image : <undefined>
* metric_value : <undefined>
* reverse_forward_invert_flags : <undefined>
* reverse_forward_transforms : <undefined>
* reverse_invert_flags : [True, False]
* reverse_transforms : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/norm/anat_to_template0GenericAffine.mat', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/norm/anat_to_template1InverseWarp.nii.gz']
* save_state : <undefined>
* warped_image : <undefined>


Runtime info
------------


* cmdline : antsRegistration --collapse-output-transforms 1 --dimensionality 3 --float 1 --initial-moving-transform [ /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/init_aff/initialization.mat, 0 ] --initialize-transforms-per-stage 0 --interpolation LanczosWindowedSinc --output [ anat_to_template, anat_to_template_Warped.nii.gz ] --transform Rigid[ 0.1 ] --metric MI[ /home/zugmana2/.cache/templateflow/tpl-OASIS30ANTs/tpl-OASIS30ANTs_res-01_T1w.nii.gz, /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/inu_n4/mapflow/_inu_n40/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template_maths_corrected.nii.gz, 1, 32, Regular, 0.25 ] --convergence [ 1000x500x250x100, 1e-08, 10 ] --smoothing-sigmas 4.0x2.0x1.0x0.0vox --shrink-factors 8x4x2x1 --use-histogram-matching 1 --masks [ /home/zugmana2/.cache/templateflow/tpl-OASIS30ANTs/tpl-OASIS30ANTs_res-01_desc-BrainCerebellumExtraction_mask.nii.gz, NULL ] --transform Affine[ 0.1 ] --metric MI[ /home/zugmana2/.cache/templateflow/tpl-OASIS30ANTs/tpl-OASIS30ANTs_res-01_T1w.nii.gz, /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/inu_n4/mapflow/_inu_n40/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template_maths_corrected.nii.gz, 1, 32, Regular, 0.25 ] --convergence [ 1000x500x250x100, 1e-08, 10 ] --smoothing-sigmas 4.0x2.0x1.0x0.0vox --shrink-factors 8x4x2x1 --use-histogram-matching 1 --masks [ /home/zugmana2/.cache/templateflow/tpl-OASIS30ANTs/tpl-OASIS30ANTs_res-01_desc-BrainCerebellumExtraction_mask.nii.gz, NULL ] --transform SyN[ 0.1, 3.0, 0.0 ] --metric CC[ /home/zugmana2/.cache/templateflow/tpl-OASIS30ANTs/tpl-OASIS30ANTs_res-01_T1w.nii.gz, /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/inu_n4/mapflow/_inu_n40/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template_maths_corrected.nii.gz, 0.5, 4, None, 1 ] --metric CC[ /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/lap_tmpl/tpl-OASIS30ANTs_res-01_T1w_maths.nii.gz, /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/lap_target/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template_maths_corrected_maths.nii.gz, 0.5, 4, None, 1 ] --convergence [ 50x10x0, 1e-09, 15 ] --smoothing-sigmas 2.0x1.0x0.0vox --shrink-factors 4x2x1 --use-histogram-matching 1 --masks [ /home/zugmana2/.cache/templateflow/tpl-OASIS30ANTs/tpl-OASIS30ANTs_res-01_desc-BrainCerebellumExtraction_mask.nii.gz, NULL ] -v --winsorize-image-intensities [ 0.025, 0.975 ]  --write-composite-transform 0
* duration : 280.140981
* hostname : cn4271
* prev_wd : /vf/users/EDB/TMSpilot/code
* working_dir : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/norm


Terminal output
~~~~~~~~~~~~~~~


 


Terminal - standard output
~~~~~~~~~~~~~~~~~~~~~~~~~~


 All_Command_lines_OK
Using single precision for computations.
=============================================================================
The composite transform comprises the following transforms (in order): 
  1. /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/init_aff/initialization.mat (type = AffineTransform)
=============================================================================
  Reading mask(s).
    Registration stage 0
      Fixed mask = /home/zugmana2/.cache/templateflow/tpl-OASIS30ANTs/tpl-OASIS30ANTs_res-01_desc-BrainCerebellumExtraction_mask.nii.gz
      No moving mask
    Registration stage 1
      Fixed mask = /home/zugmana2/.cache/templateflow/tpl-OASIS30ANTs/tpl-OASIS30ANTs_res-01_desc-BrainCerebellumExtraction_mask.nii.gz
      No moving mask
    Registration stage 2
      Fixed mask = /home/zugmana2/.cache/templateflow/tpl-OASIS30ANTs/tpl-OASIS30ANTs_res-01_desc-BrainCerebellumExtraction_mask.nii.gz
      No moving mask
  number of levels = 4
  number of levels = 4
  number of levels = 3
  fixed image: /home/zugmana2/.cache/templateflow/tpl-OASIS30ANTs/tpl-OASIS30ANTs_res-01_T1w.nii.gz
  moving image: /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/inu_n4/mapflow/_inu_n40/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template_maths_corrected.nii.gz
  fixed image: /home/zugmana2/.cache/templateflow/tpl-OASIS30ANTs/tpl-OASIS30ANTs_res-01_T1w.nii.gz
  moving image: /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/inu_n4/mapflow/_inu_n40/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template_maths_corrected.nii.gz
  fixed image: /home/zugmana2/.cache/templateflow/tpl-OASIS30ANTs/tpl-OASIS30ANTs_res-01_T1w.nii.gz
  moving image: /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/inu_n4/mapflow/_inu_n40/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template_maths_corrected.nii.gz
  fixed image: /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/lap_tmpl/tpl-OASIS30ANTs_res-01_T1w_maths.nii.gz
  moving image: /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/lap_target/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template_maths_corrected_maths.nii.gz
Dimension = 3
Number of stages = 3
Use histogram matching = true
Winsorize image intensities = true
  Lower quantile = 0.025
  Upper quantile = 0.975


Stage 1 State
   Image metric = Mattes
     Fixed image = Image (0x555555a7d1f0)
  RTTI typeinfo:   itk::Image<float, 3u>
  Reference Count: 2
  Modified Time: 2141
  Debug: Off
  Object Name: 
  Observers: 
    none
  Source: (none)
  Source output name: (none)
  Release Data: Off
  Data Released: False
  Global Release Data: Off
  PipelineMTime: 0
  UpdateMTime: 1924
  RealTimeStamp: 0 seconds 
  LargestPossibleRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [216, 291, 256]
  BufferedRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [216, 291, 256]
  RequestedRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [216, 291, 256]
  Spacing: [1, 1, 1]
  Origin: [215, 293, -255]
  Direction: 
-1 0 0
0 -1 0
0 0 1

  IndexToPointMatrix: 
-1 0 0
0 -1 0
0 0 1

  PointToIndexMatrix: 
-1 0 0
0 -1 0
0 0 1

  Inverse Direction: 
-1 0 0
0 -1 0
0 0 1

  PixelContainer: 
    ImportImageContainer (0x555555a765f0)
      RTTI typeinfo:   itk::ImportImageContainer<unsigned long, float>
      Reference Count: 1
      Modified Time: 1921
      Debug: Off
      Object Name: 
      Observers: 
        none
      Pointer: 0x7fffe5321010
      Container manages memory: true
      Size: 16091136
      Capacity: 16091136

     Moving image = Image (0x5555569ddca0)
  RTTI typeinfo:   itk::Image<float, 3u>
  Reference Count: 2
  Modified Time: 2142
  Debug: Off
  Object Name: 
  Observers: 
    none
  Source: (none)
  Source output name: (none)
  Release Data: Off
  Data Released: False
  Global Release Data: Off
  PipelineMTime: 0
  UpdateMTime: 2139
  RealTimeStamp: 0 seconds 
  LargestPossibleRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [250, 320, 320]
  BufferedRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [250, 320, 320]
  RequestedRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [250, 320, 320]
  Spacing: [0.799995, 0.8, 0.8]
  Origin: [99.5989, 109.183, -134.457]
  Direction: 
-1 0 0
0 -1 0
0 0 1

  IndexToPointMatrix: 
-0.799995 0 0
0 -0.8 0
0 0 0.8

  PointToIndexMatrix: 
-1.25001 0 0
0 -1.25 0
0 0 1.25

  Inverse Direction: 
-1 0 0
0 -1 0
0 0 1

  PixelContainer: 
    ImportImageContainer (0x5555569ddfd0)
      RTTI typeinfo:   itk::ImportImageContainer<unsigned long, float>
      Reference Count: 1
      Modified Time: 2136
      Debug: Off
      Object Name: 
      Observers: 
        none
      Pointer: 0x7fffdf178010
      Container manages memory: true
      Size: 25600000
      Capacity: 25600000

     Weighting = 1
     Sampling strategy = regular
     Number of bins = 32
     Radius = 4
     Sampling percentage  = 0.25
   Transform = Rigid
     Gradient step = 0.1
     Update field sigma (voxel space) = 0
     Total field sigma (voxel space) = 0
     Update field time sigma = 0
     Total field time sigma  = 0
     Number of time indices = 0
     Number of time point samples = 0
Stage 2 State
   Image metric = Mattes
     Fixed image = Image (0x55555793fdf0)
  RTTI typeinfo:   itk::Image<float, 3u>
  Reference Count: 2
  Modified Time: 2571
  Debug: Off
  Object Name: 
  Observers: 
    none
  Source: (none)
  Source output name: (none)
  Release Data: Off
  Data Released: False
  Global Release Data: Off
  PipelineMTime: 0
  UpdateMTime: 2354
  RealTimeStamp: 0 seconds 
  LargestPossibleRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [216, 291, 256]
  BufferedRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [216, 291, 256]
  RequestedRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [216, 291, 256]
  Spacing: [1, 1, 1]
  Origin: [215, 293, -255]
  Direction: 
-1 0 0
0 -1 0
0 0 1

  IndexToPointMatrix: 
-1 0 0
0 -1 0
0 0 1

  PointToIndexMatrix: 
-1 0 0
0 -1 0
0 0 1

  Inverse Direction: 
-1 0 0
0 -1 0
0 0 1

  PixelContainer: 
    ImportImageContainer (0x55555793cde0)
      RTTI typeinfo:   itk::ImportImageContainer<unsigned long, float>
      Reference Count: 1
      Modified Time: 2351
      Debug: Off
      Object Name: 
      Observers: 
        none
      Pointer: 0x7fffdb415010
      Container manages memory: true
      Size: 16091136
      Capacity: 16091136

     Moving image = Image (0x555557942970)
  RTTI typeinfo:   itk::Image<float, 3u>
  Reference Count: 2
  Modified Time: 2572
  Debug: Off
  Object Name: 
  Observers: 
    none
  Source: (none)
  Source output name: (none)
  Release Data: Off
  Data Released: False
  Global Release Data: Off
  PipelineMTime: 0
  UpdateMTime: 2569
  RealTimeStamp: 0 seconds 
  LargestPossibleRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [250, 320, 320]
  BufferedRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [250, 320, 320]
  RequestedRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [250, 320, 320]
  Spacing: [0.799995, 0.8, 0.8]
  Origin: [99.5989, 109.183, -134.457]
  Direction: 
-1 0 0
0 -1 0
0 0 1

  IndexToPointMatrix: 
-0.799995 0 0
0 -0.8 0
0 0 0.8

  PointToIndexMatrix: 
-1.25001 0 0
0 -1.25 0
0 0 1.25

  Inverse Direction: 
-1 0 0
0 -1 0
0 0 1

  PixelContainer: 
    ImportImageContainer (0x55555793b5b0)
      RTTI typeinfo:   itk::ImportImageContainer<unsigned long, float>
      Reference Count: 1
      Modified Time: 2566
      Debug: Off
      Object Name: 
      Observers: 
        none
      Pointer: 0x7fffd526c010
      Container manages memory: true
      Size: 25600000
      Capacity: 25600000

     Weighting = 1
     Sampling strategy = regular
     Number of bins = 32
     Radius = 4
     Sampling percentage  = 0.25
   Transform = Affine
     Gradient step = 0.1
     Update field sigma (voxel space) = 0
     Total field sigma (voxel space) = 0
     Update field time sigma = 0
     Total field time sigma  = 0
     Number of time indices = 0
     Number of time point samples = 0
Stage 3 State
   Image metric = CC
     Fixed image = Image (0x5555579424d0)
  RTTI typeinfo:   itk::Image<float, 3u>
  Reference Count: 2
  Modified Time: 3001
  Debug: Off
  Object Name: 
  Observers: 
    none
  Source: (none)
  Source output name: (none)
  Release Data: Off
  Data Released: False
  Global Release Data: Off
  PipelineMTime: 0
  UpdateMTime: 2784
  RealTimeStamp: 0 seconds 
  LargestPossibleRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [216, 291, 256]
  BufferedRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [216, 291, 256]
  RequestedRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [216, 291, 256]
  Spacing: [1, 1, 1]
  Origin: [215, 293, -255]
  Direction: 
-1 0 0
0 -1 0
0 0 1

  IndexToPointMatrix: 
-1 0 0
0 -1 0
0 0 1

  PointToIndexMatrix: 
-1 0 0
0 -1 0
0 0 1

  Inverse Direction: 
-1 0 0
0 -1 0
0 0 1

  PixelContainer: 
    ImportImageContainer (0x555557942ca0)
      RTTI typeinfo:   itk::ImportImageContainer<unsigned long, float>
      Reference Count: 1
      Modified Time: 2781
      Debug: Off
      Object Name: 
      Observers: 
        none
      Pointer: 0x7fffd1509010
      Container manages memory: true
      Size: 16091136
      Capacity: 16091136

     Moving image = Image (0x555557947c80)
  RTTI typeinfo:   itk::Image<float, 3u>
  Reference Count: 2
  Modified Time: 3002
  Debug: Off
  Object Name: 
  Observers: 
    none
  Source: (none)
  Source output name: (none)
  Release Data: Off
  Data Released: False
  Global Release Data: Off
  PipelineMTime: 0
  UpdateMTime: 2999
  RealTimeStamp: 0 seconds 
  LargestPossibleRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [250, 320, 320]
  BufferedRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [250, 320, 320]
  RequestedRegion: 
    Dimension: 3
    Index: [0, 0, 0]
    Size: [250, 320, 320]
  Spacing: [0.799995, 0.8, 0.8]
  Origin: [99.5989, 109.183, -134.457]
  Direction: 
-1 0 0
0 -1 0
0 0 1

  IndexToPointMatrix: 
-0.799995 0 0
0 -0.8 0
0 0 0.8

  PointToIndexMatrix: 
-1.25001 0 0
0 -1.25 0
0 0 1.25

  Inverse Direction: 
-1 0 0
0 -1 0
0 0 1

  PixelContainer: 
    ImportImageContainer (0x555557941510)
      RTTI typeinfo:   itk::ImportImageContainer<unsigned long, float>
      Reference Count: 1
      Modified Time: 2996
      Debug: Off
      Object Name: 
      Observers: 
        none
      Pointer: 0x7fffcb360010
      Container manages memory: true
      Size: 25600000
      Capacity: 25600000

     Weighting = 0.5
     Sampling strategy = none
     Number of bins = 32
     Radius = 4
     Sampling percentage  = 1
   Transform = SyN
     Gradient step = 0.1
     Update field sigma (voxel space) = 3
     Total field sigma (voxel space) = 0
     Update field time sigma = 0
     Total field time sigma  = 0
     Number of time indices = 0
     Number of time point samples = 0
Registration using 3 total stages.

Stage 0
  iterations = 1000x500x250x100
  convergence threshold = 1e-08
  convergence window size = 10
  number of levels = 4
  using the Mattes MI metric (number of bins = 32, weight = 1, use gradient filter = 0)
  preprocessing:  winsorizing the image intensities
  preprocessing:  histogram matching the images
  Shrink factors (level 1 out of 4): [8, 8, 8]
  Shrink factors (level 2 out of 4): [4, 4, 4]
  Shrink factors (level 3 out of 4): [2, 2, 2]
  Shrink factors (level 4 out of 4): [1, 1, 1]
  smoothing sigmas per level: [4, 2, 1, 0]
  regular sampling (percentage = 0.25)

*** Running Euler3DTransform registration ***

DIAGNOSTIC,Iteration,metricValue,convergenceValue,ITERATION_TIME_INDEX,SINCE_LAST
 2DIAGNOSTIC,     1, -7.678915262222e-01, inf, 1.2839e+00, 1.2839e+00, 
 2DIAGNOSTIC,     2, -7.724438905716e-01, inf, 1.2885e+00, 4.6170e-03, 
 2DIAGNOSTIC,     3, -7.793090343475e-01, inf, 1.2928e+00, 4.3380e-03, 
 2DIAGNOSTIC,     4, -7.894399166107e-01, inf, 1.2976e+00, 4.7460e-03, 
 2DIAGNOSTIC,     5, -8.038088679314e-01, inf, 1.3020e+00, 4.3960e-03, 
 2DIAGNOSTIC,     6, -8.171356320381e-01, inf, 1.3064e+00, 4.4529e-03, 
 2DIAGNOSTIC,     7, -8.319925665855e-01, inf, 1.3109e+00, 4.4801e-03, 
 2DIAGNOSTIC,     8, -8.367315530777e-01, inf, 1.3153e+00, 4.3590e-03, 
 2DIAGNOSTIC,     9, -8.402217626572e-01, inf, 1.3196e+00, 4.3490e-03, 
 2DIAGNOSTIC,    10, -8.448363542557e-01, 6.983453407884e-03, 1.3249e+00, 5.2590e-03, 
 2DIAGNOSTIC,    11, -8.477528691292e-01, 5.922667216510e-03, 1.3328e+00, 7.9381e-03, 
 2DIAGNOSTIC,    12, -8.482533097267e-01, 4.659793339670e-03, 1.3373e+00, 4.4429e-03, 
 2DIAGNOSTIC,    13, -8.499128818512e-01, 3.408023854718e-03, 1.3416e+00, 4.3530e-03, 
 2DIAGNOSTIC,    14, -8.512411713600e-01, 2.314193639904e-03, 1.3460e+00, 4.3490e-03, 
 2DIAGNOSTIC,    15, -8.520504832268e-01, 1.505071297288e-03, 1.3504e+00, 4.4150e-03, 
 2DIAGNOSTIC,    16, -8.543595075607e-01, 9.921084856614e-04, 1.3562e+00, 5.8460e-03, 
 2DIAGNOSTIC,    17, -8.575866818428e-01, 8.148608612828e-04, 1.3613e+00, 5.0640e-03, 
 2DIAGNOSTIC,    18, -8.580808639526e-01, 6.812689825892e-04, 1.3657e+00, 4.4320e-03, 
 2DIAGNOSTIC,    19, -8.592961430550e-01, 5.831350572407e-04, 1.3711e+00, 5.3680e-03, 
 2DIAGNOSTIC,    20, -8.701397776604e-01, 7.041428470984e-04, 1.3756e+00, 4.5538e-03, 
 2DIAGNOSTIC,    21, -8.736668825150e-01, 8.471776382066e-04, 1.3816e+00, 5.9359e-03, 
 2DIAGNOSTIC,    22, -8.752264380455e-01, 9.290849557146e-04, 1.3873e+00, 5.7669e-03, 
 2DIAGNOSTIC,    23, -8.760296702385e-01, 9.555929573253e-04, 1.3918e+00, 4.4310e-03, 
 2DIAGNOSTIC,    24, -8.771771788597e-01, 9.260890074074e-04, 1.3986e+00, 6.8140e-03, 
 2DIAGNOSTIC,    25, -8.776457309723e-01, 8.266956428997e-04, 1.4036e+00, 5.0459e-03, 
 2DIAGNOSTIC,    26, -8.777346014977e-01, 6.868366617709e-04, 1.4079e+00, 4.3190e-03, 
 2DIAGNOSTIC,    27, -8.778083920479e-01, 5.364468670450e-04, 1.4129e+00, 5.0020e-03, 
 2DIAGNOSTIC,    28, -8.778488636017e-01, 3.548777895048e-04, 1.4174e+00, 4.4091e-03, 
 2DIAGNOSTIC,    29, -8.779104948044e-01, 1.646646123845e-04, 1.4230e+00, 5.6579e-03, 
 2DIAGNOSTIC,    30, -8.779629468918e-01, 9.315433999291e-05, 1.4274e+00, 4.3380e-03, 
 2DIAGNOSTIC,    31, -8.779919743538e-01, 5.596199844149e-05, 1.4324e+00, 5.0280e-03, 
 2DIAGNOSTIC,    32, -8.780046701431e-01, 3.240615114919e-05, 1.4394e+00, 7.0529e-03, 
 2DIAGNOSTIC,    33, -8.780069351196e-01, 1.525315110484e-05, 1.4446e+00, 5.1279e-03, 
 2DIAGNOSTIC,    34, -8.780081272125e-01, 8.963201253209e-06, 1.4497e+00, 5.1610e-03, 
 2DIAGNOSTIC,    35, -8.780090212822e-01, 6.743999165337e-06, 1.4542e+00, 4.5171e-03, 
 2DIAGNOSTIC,    36, -8.780097961426e-01, 4.918543254462e-06, 1.4594e+00, 5.2018e-03, 
 2DIAGNOSTIC,    37, -8.780106902122e-01, 3.487435151328e-06, 1.4640e+00, 4.5359e-03, 
 2DIAGNOSTIC,    38, -8.780128955841e-01, 2.253650109196e-06, 1.4692e+00, 5.1761e-03, 
 2DIAGNOSTIC,    39, -8.780155777931e-01, 1.492471596976e-06, 1.4737e+00, 4.5190e-03, 
 2DIAGNOSTIC,    40, -8.780198097229e-01, 1.173570922219e-06, 1.4782e+00, 4.5300e-03, 
 2DIAGNOSTIC,    41, -8.780262470245e-01, 1.120979163716e-06, 1.4827e+00, 4.5040e-03, 
 2DIAGNOSTIC,    42, -8.780341148376e-01, 1.201429881803e-06, 1.4872e+00, 4.4911e-03, 
 2DIAGNOSTIC,    43, -8.780450224876e-01, 1.338140918961e-06, 1.4917e+00, 4.4820e-03, 
 2DIAGNOSTIC,    44, -8.780571818352e-01, 1.512402263870e-06, 1.5013e+00, 9.6171e-03, 
 2DIAGNOSTIC,    45, -8.780610561371e-01, 1.638877620280e-06, 1.5065e+00, 5.2230e-03, 
 2DIAGNOSTIC,    46, -8.780606389046e-01, 1.675563453318e-06, 1.5123e+00, 5.7409e-03, 
 2DIAGNOSTIC,    47, -8.780609369278e-01, 1.627155143069e-06, 1.5175e+00, 5.2259e-03, 
 2DIAGNOSTIC,    48, -8.780607581139e-01, 1.504420538367e-06, 1.5233e+00, 5.8479e-03, 
 2DIAGNOSTIC,    49, -8.780607581139e-01, 1.324579898210e-06, 1.5283e+00, 4.9989e-03, 
 2DIAGNOSTIC,    50, -8.780607581139e-01, 1.116639850807e-06, 1.5336e+00, 5.2950e-03, 
 2DIAGNOSTIC,    51, -8.780611753464e-01, 9.173490980174e-07, 1.5397e+00, 6.1011e-03, 
 2DIAGNOSTIC,    52, -8.780601024628e-01, 7.414491278723e-07, 1.5450e+00, 5.2519e-03, 
 2DIAGNOSTIC,    53, -8.780599832535e-01, 6.266703280744e-07, 1.5502e+00, 5.2490e-03, 
 2DIAGNOSTIC,    54, -8.780601024628e-01, 5.892712238165e-07, 1.5549e+00, 4.6880e-03, 
 2DIAGNOSTIC,    55, -8.780603408813e-01, 5.790020054519e-07, 1.5601e+00, 5.2040e-03, 
 2DIAGNOSTIC,    56, -8.780593276024e-01, 5.615955842586e-07, 1.5654e+00, 5.2750e-03, 
 2DIAGNOSTIC,    57, -8.780594468117e-01, 5.492328796208e-07, 1.5705e+00, 5.0831e-03, 
 2DIAGNOSTIC,    58, -8.780599832535e-01, 5.412181280917e-07, 1.5757e+00, 5.2471e-03, 
 2DIAGNOSTIC,    59, -8.780599236488e-01, 5.345809199753e-07, 1.5808e+00, 5.0881e-03, 
 2DIAGNOSTIC,    60, -8.780602812767e-01, 5.314361146702e-07, 1.5868e+00, 5.9631e-03, 
 2DIAGNOSTIC,    61, -8.780598640442e-01, 5.294434117786e-07, 1.5927e+00, 5.9159e-03, 
 2DIAGNOSTIC,    62, -8.780600428581e-01, 5.230231749920e-07, 1.5985e+00, 5.7650e-03, 
 2DIAGNOSTIC,    63, -8.780598640442e-01, 5.150023412170e-07, 1.6039e+00, 5.3999e-03, 
 2DIAGNOSTIC,    64, -8.780599832535e-01, 5.082353027319e-07, 1.6083e+00, 4.4639e-03, 
 2DIAGNOSTIC,    65, -8.780598044395e-01, 5.018817432756e-07, 1.6128e+00, 4.4680e-03, 
 2DIAGNOSTIC,    66, -8.780597448349e-01, 4.900151679976e-07, 1.6174e+00, 4.6411e-03, 
 2DIAGNOSTIC,    67, -8.780600428581e-01, 4.805011144526e-07, 1.6215e+00, 4.0908e-03, 
 2DIAGNOSTIC,    68, -8.780595660210e-01, 4.716981436559e-07, 1.6256e+00, 4.0751e-03, 
 2DIAGNOSTIC,    69, -8.780596256256e-01, 4.635150787635e-07, 1.6309e+00, 5.2979e-03, 
 2DIAGNOSTIC,    70, -8.780598640442e-01, 4.588818285356e-07, 1.6351e+00, 4.2191e-03, 
 2DIAGNOSTIC,    71, -8.780596852303e-01, 4.517874572230e-07, 1.6393e+00, 4.1599e-03, 
 2DIAGNOSTIC,    72, -8.780595660210e-01, 4.455083910671e-07, 1.6439e+00, 4.6670e-03, 
 2DIAGNOSTIC,    73, -8.780596852303e-01, 4.394459836021e-07, 1.6481e+00, 4.1940e-03, 
 2DIAGNOSTIC,    74, -8.780598640442e-01, 4.351486779797e-07, 1.6523e+00, 4.1182e-03, 
 2DIAGNOSTIC,    75, -8.780598640442e-01, 4.302331433337e-07, 1.6569e+00, 4.6930e-03, 
 2DIAGNOSTIC,    76, -8.780598640442e-01, 4.251670588928e-07, 1.6610e+00, 4.0901e-03, 
 2DIAGNOSTIC,    77, -8.780593276024e-01, 4.192572475858e-07, 1.6651e+00, 4.0870e-03, 
 2DIAGNOSTIC,    78, -8.780597448349e-01, 4.132679123359e-07, 1.6692e+00, 4.0989e-03, 
 2DIAGNOSTIC,    79, -8.780598044395e-01, 4.078136157659e-07, 1.6743e+00, 5.1100e-03, 
 2DIAGNOSTIC,    80, -8.780596852303e-01, 4.030212608086e-07, 1.6784e+00, 4.0710e-03, 
 2DIAGNOSTIC,    81, -8.780596852303e-01, 3.977087033036e-07, 1.6825e+00, 4.0920e-03, 
 2DIAGNOSTIC,    82, -8.780596852303e-01, 3.920998210560e-07, 1.6866e+00, 4.0720e-03, 
 2DIAGNOSTIC,    83, -8.780596852303e-01, 3.871431601965e-07, 1.6907e+00, 4.0860e-03, 
 2DIAGNOSTIC,    84, -8.780595660210e-01, 3.826046395261e-07, 1.6947e+00, 4.0781e-03, 
 2DIAGNOSTIC,    85, -8.780596256256e-01, 3.785199851336e-07, 1.6988e+00, 4.0751e-03, 
 2DIAGNOSTIC,    86, -8.780596852303e-01, 3.748775156964e-07, 1.7030e+00, 4.1561e-03, 
 2DIAGNOSTIC,    87, -8.780597448349e-01, 3.694312056268e-07, 1.7075e+00, 4.5810e-03, 
 2DIAGNOSTIC,    88, -8.780597448349e-01, 3.657271179236e-07, 1.7120e+00, 4.4451e-03, 
 2DIAGNOSTIC,    89, -8.780597448349e-01, 3.623719067036e-07, 1.7161e+00, 4.0841e-03, 
 2DIAGNOSTIC,    90, -8.780597448349e-01, 3.586007721879e-07, 1.7204e+00, 4.3259e-03, 
 2DIAGNOSTIC,    91, -8.780597448349e-01, 3.548143752141e-07, 1.7250e+00, 4.6449e-03, 
 2DIAGNOSTIC,    92, -8.780597448349e-01, 3.509998123263e-07, 1.7301e+00, 5.1019e-03, 
 2DIAGNOSTIC,    93, -8.780597448349e-01, 3.471727154647e-07, 1.7348e+00, 4.6399e-03, 
 2DIAGNOSTIC,    94, -8.780597448349e-01, 3.429020409840e-07, 1.7392e+00, 4.4479e-03, 
 2DIAGNOSTIC,    95, -8.780597448349e-01, 3.388665561488e-07, 1.7434e+00, 4.1480e-03, 
 2DIAGNOSTIC,    96, -8.780597448349e-01, 3.350936026436e-07, 1.7475e+00, 4.1430e-03, 
 2DIAGNOSTIC,    97, -8.780597448349e-01, 3.316004608678e-07, 1.7517e+00, 4.1389e-03, 
 2DIAGNOSTIC,    98, -8.780597448349e-01, 3.281793681253e-07, 1.7558e+00, 4.1559e-03, 
 2DIAGNOSTIC,    99, -8.780597448349e-01, 3.248281643664e-07, 1.7602e+00, 4.3640e-03, 
 2DIAGNOSTIC,   100, -8.780597448349e-01, 3.215446895410e-07, 1.7646e+00, 4.3890e-03, 
 2DIAGNOSTIC,   101, -8.780597448349e-01, 3.183269541296e-07, 1.7687e+00, 4.1461e-03, 
 2DIAGNOSTIC,   102, -8.780597448349e-01, 3.151729686124e-07, 1.7729e+00, 4.1702e-03, 
 2DIAGNOSTIC,   103, -8.780597448349e-01, 3.120808571566e-07, 1.7770e+00, 4.1351e-03, 
 2DIAGNOSTIC,   104, -8.780597448349e-01, 3.090488291946e-07, 1.7812e+00, 4.1490e-03, 
 2DIAGNOSTIC,   105, -8.780597448349e-01, 3.060751794237e-07, 1.7853e+00, 4.1308e-03, 
 2DIAGNOSTIC,   106, -8.780597448349e-01, 3.031581741197e-07, 1.7895e+00, 4.1640e-03, 
 2DIAGNOSTIC,   107, -8.780597448349e-01, 3.002962785104e-07, 1.7936e+00, 4.1599e-03, 
 2DIAGNOSTIC,   108, -8.780597448349e-01, 2.974878725581e-07, 1.7978e+00, 4.1299e-03, 
 2DIAGNOSTIC,   109, -8.780597448349e-01, 2.947315351776e-07, 1.8020e+00, 4.2510e-03, 
 2DIAGNOSTIC,   110, -8.780597448349e-01, 2.920258168615e-07, 1.8061e+00, 4.1249e-03, 
 2DIAGNOSTIC,   111, -8.780597448349e-01, 2.893692965245e-07, 1.8102e+00, 4.1120e-03, 
 2DIAGNOSTIC,   112, -8.780597448349e-01, 2.867606951895e-07, 1.8143e+00, 4.0770e-03, 
 2DIAGNOSTIC,   113, -8.780597448349e-01, 2.841986770363e-07, 1.8185e+00, 4.1518e-03, 
 2DIAGNOSTIC,   114, -8.780597448349e-01, 2.816820483531e-07, 1.8225e+00, 4.0739e-03, 
 2DIAGNOSTIC,   115, -8.780597448349e-01, 2.792096154280e-07, 1.8266e+00, 4.0851e-03, 
 2DIAGNOSTIC,   116, -8.780597448349e-01, 2.767801845494e-07, 1.8308e+00, 4.1270e-03, 
 2DIAGNOSTIC,   117, -8.780597448349e-01, 2.743926756921e-07, 1.8349e+00, 4.1080e-03, 
 2DIAGNOSTIC,   118, -8.780597448349e-01, 2.720460088312e-07, 1.8395e+00, 4.6079e-03, 
 2DIAGNOSTIC,   119, -8.780597448349e-01, 2.697391323636e-07, 1.8436e+00, 4.1358e-03, 
 2DIAGNOSTIC,   120, -8.780597448349e-01, 2.674710515294e-07, 1.8477e+00, 4.1051e-03, 
 2DIAGNOSTIC,   121, -8.780597448349e-01, 2.652407999904e-07, 1.8518e+00, 4.1041e-03, 
 2DIAGNOSTIC,   122, -8.780597448349e-01, 2.630474398302e-07, 1.8560e+00, 4.1821e-03, 
 2DIAGNOSTIC,   123, -8.780597448349e-01, 2.608900331325e-07, 1.8601e+00, 4.1058e-03, 
 2DIAGNOSTIC,   124, -8.780597448349e-01, 2.587677556676e-07, 1.8642e+00, 4.0910e-03, 
 2DIAGNOSTIC,   125, -8.780597448349e-01, 2.566796979409e-07, 1.8683e+00, 4.0810e-03, 
 2DIAGNOSTIC,   126, -8.780597448349e-01, 2.546250925661e-07, 1.8724e+00, 4.0731e-03, 
 2DIAGNOSTIC,   127, -8.780597448349e-01, 2.526031153138e-07, 1.8765e+00, 4.1220e-03, 
 2DIAGNOSTIC,   128, -8.780597448349e-01, 2.506129987978e-07, 1.8805e+00, 4.0700e-03, 
 2DIAGNOSTIC,   129, -8.780597448349e-01, 2.486539756319e-07, 1.8847e+00, 4.1780e-03, 
 2DIAGNOSTIC,   130, -8.780597448349e-01, 2.467253636951e-07, 1.8889e+00, 4.1630e-03, 
 2DIAGNOSTIC,   131, -8.780597448349e-01, 2.448264240229e-07, 1.8930e+00, 4.1442e-03, 
 2DIAGNOSTIC,   132, -8.780597448349e-01, 2.429565029161e-07, 1.8972e+00, 4.1530e-03, 
 2DIAGNOSTIC,   133, -8.780597448349e-01, 2.411149182535e-07, 1.9013e+00, 4.1180e-03, 
 2DIAGNOSTIC,   134, -8.780597448349e-01, 2.393010731794e-07, 1.9054e+00, 4.0839e-03, 
 2DIAGNOSTIC,   135, -8.780597448349e-01, 2.375142713618e-07, 1.9095e+00, 4.1370e-03, 
 2DIAGNOSTIC,   136, -8.780597448349e-01, 2.357539869990e-07, 1.9137e+00, 4.1752e-03, 
 2DIAGNOSTIC,   137, -8.780597448349e-01, 2.340195806028e-07, 1.9178e+00, 4.0789e-03, 
 2DIAGNOSTIC,   138, -8.780597448349e-01, 2.323105121604e-07, 1.9219e+00, 4.0829e-03, 
 2DIAGNOSTIC,   139, -8.780597448349e-01, 2.306262416596e-07, 1.9259e+00, 4.0679e-03, 
 2DIAGNOSTIC,   140, -8.780597448349e-01, 2.289662006660e-07, 1.9300e+00, 4.0839e-03, 
 2DIAGNOSTIC,   141, -8.780597448349e-01, 2.273298917999e-07, 1.9341e+00, 4.0820e-03, 
 2DIAGNOSTIC,   142, -8.780597448349e-01, 2.257168034703e-07, 1.9382e+00, 4.0610e-03, 
 2DIAGNOSTIC,   143, -8.780597448349e-01, 2.241264525082e-07, 1.9422e+00, 4.0760e-03, 
 2DIAGNOSTIC,   144, -8.780597448349e-01, 2.225583415338e-07, 1.9463e+00, 4.0729e-03, 
 2DIAGNOSTIC,   145, -8.780597448349e-01, 2.210120300106e-07, 1.9504e+00, 4.0669e-03, 
 2DIAGNOSTIC,   146, -8.780597448349e-01, 2.194870631911e-07, 1.9545e+00, 4.0860e-03, 
 2DIAGNOSTIC,   147, -8.780597448349e-01, 2.179829863280e-07, 1.9585e+00, 4.0770e-03, 
 2DIAGNOSTIC,   148, -8.780597448349e-01, 2.164993873066e-07, 1.9626e+00, 4.0860e-03, 
 2DIAGNOSTIC,   149, -8.780597448349e-01, 2.150358398012e-07, 1.9667e+00, 4.0839e-03, 
 2DIAGNOSTIC,   150, -8.780597448349e-01, 2.135919601187e-07, 1.9715e+00, 4.8060e-03, 
 2DIAGNOSTIC,   151, -8.780597448349e-01, 2.121673361444e-07, 1.9757e+00, 4.1959e-03, 
 2DIAGNOSTIC,   152, -8.780597448349e-01, 2.107615841851e-07, 1.9877e+00, 1.1961e-02, 
 2DIAGNOSTIC,   153, -8.780597448349e-01, 2.093743489695e-07, 1.9920e+00, 4.3800e-03, 
 2DIAGNOSTIC,   154, -8.780597448349e-01, 2.080052468045e-07, 1.9962e+00, 4.1499e-03, 
 2DIAGNOSTIC,   155, -8.780597448349e-01, 2.066539366297e-07, 2.0003e+00, 4.0948e-03, 
 2DIAGNOSTIC,   156, -8.780597448349e-01, 2.053200631735e-07, 2.0044e+00, 4.0791e-03, 
 2DIAGNOSTIC,   157, -8.780597448349e-01, 2.040033137973e-07, 2.0084e+00, 4.0650e-03, 
 2DIAGNOSTIC,   158, -8.780597448349e-01, 2.027033332297e-07, 2.0126e+00, 4.1561e-03, 
 2DIAGNOSTIC,   159, -8.780597448349e-01, 2.014198230427e-07, 2.0167e+00, 4.0979e-03, 
 2DIAGNOSTIC,   160, -8.780597448349e-01, 2.001524563866e-07, 2.0209e+00, 4.2071e-03, 
 2DIAGNOSTIC,   161, -8.780597448349e-01, 1.989009490444e-07, 2.0251e+00, 4.1671e-03, 
 2DIAGNOSTIC,   162, -8.780597448349e-01, 1.976649883773e-07, 2.0291e+00, 4.0860e-03, 
 2DIAGNOSTIC,   163, -8.780597448349e-01, 1.964442901681e-07, 2.0332e+00, 4.0681e-03, 
 2DIAGNOSTIC,   164, -8.780597448349e-01, 1.952385844106e-07, 2.0373e+00, 4.0681e-03, 
 2DIAGNOSTIC,   165, -8.780597448349e-01, 1.940475868878e-07, 2.0414e+00, 4.0770e-03, 
 2DIAGNOSTIC,   166, -8.780597448349e-01, 1.928710275934e-07, 2.0454e+00, 4.0770e-03, 
 2DIAGNOSTIC,   167, -8.780597448349e-01, 1.917086507319e-07, 2.0495e+00, 4.0710e-03, 
 2DIAGNOSTIC,   168, -8.780597448349e-01, 1.905602005081e-07, 2.0536e+00, 4.0681e-03, 
 2DIAGNOSTIC,   169, -8.780597448349e-01, 1.894254353374e-07, 2.0576e+00, 4.0650e-03, 
 2DIAGNOSTIC,   170, -8.780597448349e-01, 1.883040994244e-07, 2.0617e+00, 4.0839e-03, 
 2DIAGNOSTIC,   171, -8.780597448349e-01, 1.871959653954e-07, 2.0658e+00, 4.1001e-03, 
 2DIAGNOSTIC,   172, -8.780597448349e-01, 1.861007916659e-07, 2.0699e+00, 4.0720e-03, 
 2DIAGNOSTIC,   173, -8.780597448349e-01, 1.850183650731e-07, 2.0740e+00, 4.0669e-03, 
 2DIAGNOSTIC,   174, -8.780597448349e-01, 1.839484440325e-07, 2.0780e+00, 4.0720e-03, 
 2DIAGNOSTIC,   175, -8.780597448349e-01, 1.828908438029e-07, 2.0821e+00, 4.0720e-03, 
 2DIAGNOSTIC,   176, -8.780597448349e-01, 1.818453227997e-07, 2.0862e+00, 4.0848e-03, 
 2DIAGNOSTIC,   177, -8.780597448349e-01, 1.808116820712e-07, 2.0904e+00, 4.2050e-03, 
 2DIAGNOSTIC,   178, -8.780597448349e-01, 1.797897368760e-07, 2.0945e+00, 4.1120e-03, 
 2DIAGNOSTIC,   179, -8.780597448349e-01, 1.787792740515e-07, 2.0986e+00, 4.1161e-03, 
 2DIAGNOSTIC,   180, -8.780597448349e-01, 1.777801088565e-07, 2.1027e+00, 4.1010e-03, 
 2DIAGNOSTIC,   181, -8.780597448349e-01, 1.767920565499e-07, 2.1068e+00, 4.0970e-03, 
 2DIAGNOSTIC,   182, -8.780597448349e-01, 1.758149181796e-07, 2.1109e+00, 4.1020e-03, 
 2DIAGNOSTIC,   183, -8.780597448349e-01, 1.748485232156e-07, 2.1154e+00, 4.5080e-03, 
 2DIAGNOSTIC,   184, -8.780597448349e-01, 1.738926869166e-07, 2.1195e+00, 4.0951e-03, 
 2DIAGNOSTIC,   185, -8.780597448349e-01, 1.729472529632e-07, 2.1236e+00, 4.0722e-03, 
 2DIAGNOSTIC,   186, -8.780597448349e-01, 1.720120366144e-07, 2.1277e+00, 4.0791e-03, 
 2DIAGNOSTIC,   187, -8.780597448349e-01, 1.710868957616e-07, 2.1321e+00, 4.4549e-03, 
 2DIAGNOSTIC,   188, -8.780597448349e-01, 1.701716314528e-07, 2.1362e+00, 4.0901e-03, 
 2DIAGNOSTIC,   189, -8.780597448349e-01, 1.692661300012e-07, 2.1403e+00, 4.0562e-03, 
 2DIAGNOSTIC,   190, -8.780597448349e-01, 1.683701924549e-07, 2.1444e+00, 4.0669e-03, 
 2DIAGNOSTIC,   191, -8.780597448349e-01, 1.674837051269e-07, 2.1484e+00, 4.0660e-03, 
 2DIAGNOSTIC,   192, -8.780597448349e-01, 1.666064974870e-07, 2.1525e+00, 4.0650e-03, 
 2DIAGNOSTIC,   193, -8.780597448349e-01, 1.657384274267e-07, 2.1566e+00, 4.1649e-03, 
 2DIAGNOSTIC,   194, -8.780597448349e-01, 1.648793670483e-07, 2.1607e+00, 4.0860e-03, 
 2DIAGNOSTIC,   195, -8.780597448349e-01, 1.640291600324e-07, 2.1648e+00, 4.0829e-03, 
 2DIAGNOSTIC,   196, -8.780597448349e-01, 1.631876784813e-07, 2.1689e+00, 4.0820e-03, 
 2DIAGNOSTIC,   197, -8.780597448349e-01, 1.623547802865e-07, 2.1730e+00, 4.0679e-03, 
 2DIAGNOSTIC,   198, -8.780597448349e-01, 1.615303375502e-07, 2.1770e+00, 4.0729e-03, 
 2DIAGNOSTIC,   199, -8.780597448349e-01, 1.607142365856e-07, 2.1811e+00, 4.0700e-03, 
 2DIAGNOSTIC,   200, -8.780597448349e-01, 1.599063352842e-07, 2.1854e+00, 4.2560e-03, 
 2DIAGNOSTIC,   201, -8.780597448349e-01, 1.591065199591e-07, 2.1894e+00, 4.0789e-03, 
 2DIAGNOSTIC,   202, -8.780597448349e-01, 1.583146627127e-07, 2.1935e+00, 4.1029e-03, 
 2DIAGNOSTIC,   203, -8.780597448349e-01, 1.575306498580e-07, 2.1976e+00, 4.0600e-03, 
 2DIAGNOSTIC,   204, -8.780597448349e-01, 1.567543677083e-07, 2.2017e+00, 4.0572e-03, 
 2DIAGNOSTIC,   205, -8.780597448349e-01, 1.559856883659e-07, 2.2057e+00, 4.0751e-03, 
 2DIAGNOSTIC,   206, -8.780597448349e-01, 1.552245265657e-07, 2.2098e+00, 4.0691e-03, 
 2DIAGNOSTIC,   207, -8.780597448349e-01, 1.544707401990e-07, 2.2139e+00, 4.0569e-03, 
 2DIAGNOSTIC,   208, -8.780597448349e-01, 1.537242440008e-07, 2.2179e+00, 4.0751e-03, 
 2DIAGNOSTIC,   209, -8.780597448349e-01, 1.529849384951e-07, 2.2220e+00, 4.0739e-03, 
 2DIAGNOSTIC,   210, -8.780597448349e-01, 1.522526957842e-07, 2.2261e+00, 4.0641e-03, 
 2DIAGNOSTIC,   211, -8.780597448349e-01, 1.515274448138e-07, 2.2302e+00, 4.0801e-03, 
 2DIAGNOSTIC,   212, -8.780597448349e-01, 1.508090576863e-07, 2.2343e+00, 4.1342e-03, 
 2DIAGNOSTIC,   213, -8.780597448349e-01, 1.500974491364e-07, 2.2384e+00, 4.1010e-03, 
 2DIAGNOSTIC,   214, -8.780597448349e-01, 1.493925338991e-07, 2.2425e+00, 4.0960e-03, 
 2DIAGNOSTIC,   215, -8.780597448349e-01, 1.486941982876e-07, 2.2466e+00, 4.0829e-03, 
 2DIAGNOSTIC,   216, -8.780597448349e-01, 1.480023712475e-07, 2.2507e+00, 4.0879e-03, 
 2DIAGNOSTIC,   217, -8.780597448349e-01, 1.473169533028e-07, 2.2548e+00, 4.0982e-03, 
 2DIAGNOSTIC,   218, -8.780597448349e-01, 1.466378449777e-07, 2.2588e+00, 4.0882e-03, 
 2DIAGNOSTIC,   219, -8.780597448349e-01, 1.459649752178e-07, 2.2629e+00, 4.0860e-03, 
 2DIAGNOSTIC,   220, -8.780597448349e-01, 1.452982445471e-07, 2.2670e+00, 4.0660e-03, 
 2DIAGNOSTIC,   221, -8.780597448349e-01, 1.446375819114e-07, 2.2714e+00, 4.3850e-03, 
 2DIAGNOSTIC,   222, -8.780597448349e-01, 1.439829020455e-07, 2.2760e+00, 4.5731e-03, 
 2DIAGNOSTIC,   223, -8.780597448349e-01, 1.433341338952e-07, 2.2800e+00, 4.0741e-03, 
 2DIAGNOSTIC,   224, -8.780597448349e-01, 1.426911637736e-07, 2.2841e+00, 4.0720e-03, 
 2DIAGNOSTIC,   225, -8.780597448349e-01, 1.420539490482e-07, 2.2882e+00, 4.0748e-03, 
 2DIAGNOSTIC,   226, -8.780597448349e-01, 1.414224044538e-07, 2.2922e+00, 4.0679e-03, 
 2DIAGNOSTIC,   227, -8.780597448349e-01, 1.407964305145e-07, 2.2963e+00, 4.0720e-03, 
 2DIAGNOSTIC,   228, -8.780597448349e-01, 1.401759988084e-07, 2.3004e+00, 4.0619e-03, 
 2DIAGNOSTIC,   229, -8.780597448349e-01, 1.395609956489e-07, 2.3045e+00, 4.0760e-03, 
 2DIAGNOSTIC,   230, -8.780597448349e-01, 1.389513641925e-07, 2.3085e+00, 4.0879e-03, 
 2DIAGNOSTIC,   231, -8.780597448349e-01, 1.383470475957e-07, 2.3127e+00, 4.1530e-03, 
 2DIAGNOSTIC,   232, -8.780597448349e-01, 1.377479463827e-07, 2.3169e+00, 4.2350e-03, 
 2DIAGNOSTIC,   233, -8.780597448349e-01, 1.371540321315e-07, 2.3210e+00, 4.0722e-03, 
 2DIAGNOSTIC,   234, -8.780597448349e-01, 1.365652053664e-07, 2.3251e+00, 4.0681e-03, 
 2DIAGNOSTIC,   235, -8.780597448349e-01, 1.359814092439e-07, 2.3291e+00, 4.0572e-03, 
 2DIAGNOSTIC,   236, -8.780597448349e-01, 1.354025869205e-07, 2.3332e+00, 4.0841e-03, 
 2DIAGNOSTIC,   237, -8.780597448349e-01, 1.348286815528e-07, 2.3373e+00, 4.0691e-03, 
 2DIAGNOSTIC,   238, -8.780597448349e-01, 1.342596078757e-07, 2.3413e+00, 4.0638e-03, 
 2DIAGNOSTIC,   239, -8.780597448349e-01, 1.336953232567e-07, 2.3454e+00, 4.0660e-03, 
 2DIAGNOSTIC,   240, -8.780597448349e-01, 1.331357566414e-07, 2.3495e+00, 4.0669e-03, 
 2DIAGNOSTIC,   241, -8.780597448349e-01, 1.325808653974e-07, 2.3535e+00, 4.0669e-03, 
 2DIAGNOSTIC,   242, -8.780597448349e-01, 1.320305642594e-07, 2.3576e+00, 4.1010e-03, 
 2DIAGNOSTIC,   243, -8.780597448349e-01, 1.314848248057e-07, 2.3617e+00, 4.0772e-03, 
 2DIAGNOSTIC,   244, -8.780597448349e-01, 1.309435759822e-07, 2.3658e+00, 4.0581e-03, 
 2DIAGNOSTIC,   245, -8.780597448349e-01, 1.304067751562e-07, 2.3699e+00, 4.1001e-03, 
 2DIAGNOSTIC,   246, -8.780597448349e-01, 1.298743370626e-07, 2.3740e+00, 4.0710e-03, 
 2DIAGNOSTIC,   247, -8.780597448349e-01, 1.293462474905e-07, 2.3780e+00, 4.0650e-03, 
 2DIAGNOSTIC,   248, -8.780597448349e-01, 1.288224211748e-07, 2.3821e+00, 4.0941e-03, 
 2DIAGNOSTIC,   249, -8.780597448349e-01, 1.283028296939e-07, 2.3862e+00, 4.1361e-03, 
 2DIAGNOSTIC,   250, -8.780597448349e-01, 1.277874019934e-07, 2.3907e+00, 4.4219e-03, 
 2DIAGNOSTIC,   251, -8.780597448349e-01, 1.272761096516e-07, 2.3951e+00, 4.4229e-03, 
 2DIAGNOSTIC,   252, -8.780597448349e-01, 1.267688958251e-07, 2.3992e+00, 4.0700e-03, 
 2DIAGNOSTIC,   253, -8.780597448349e-01, 1.262656894596e-07, 2.4033e+00, 4.1430e-03, 
 2DIAGNOSTIC,   254, -8.780597448349e-01, 1.257664763443e-07, 2.4074e+00, 4.0731e-03, 
 2DIAGNOSTIC,   255, -8.780597448349e-01, 1.252711996358e-07, 2.4114e+00, 4.0672e-03, 
 2DIAGNOSTIC,   256, -8.780597448349e-01, 1.247798024906e-07, 2.4159e+00, 4.4429e-03, 
 2DIAGNOSTIC,   257, -8.780597448349e-01, 1.242922422762e-07, 2.4201e+00, 4.1881e-03, 
 2DIAGNOSTIC,   258, -8.780597448349e-01, 1.238084763600e-07, 2.4241e+00, 4.0631e-03, 
 2DIAGNOSTIC,   259, -8.780597448349e-01, 1.233284763202e-07, 2.4282e+00, 4.0691e-03, 
 2DIAGNOSTIC,   260, -8.780597448349e-01, 1.228521711027e-07, 2.4323e+00, 4.0770e-03, 
 2DIAGNOSTIC,   261, -8.780597448349e-01, 1.223795322858e-07, 2.4364e+00, 4.0700e-03, 
 2DIAGNOSTIC,   262, -8.780597448349e-01, 1.219105172368e-07, 2.4407e+00, 4.3080e-03, 
 2DIAGNOSTIC,   263, -8.780597448349e-01, 1.214450833231e-07, 2.4449e+00, 4.2589e-03, 
 2DIAGNOSTIC,   264, -8.780597448349e-01, 1.209831879123e-07, 2.4490e+00, 4.0998e-03, 
 2DIAGNOSTIC,   265, -8.780597448349e-01, 1.205247883718e-07, 2.4531e+00, 4.0820e-03, 
 2DIAGNOSTIC,   266, -8.780597448349e-01, 1.200698562798e-07, 2.4572e+00, 4.0710e-03, 
 2DIAGNOSTIC,   267, -8.780597448349e-01, 1.196183490038e-07, 2.4612e+00, 4.0700e-03, 
 2DIAGNOSTIC,   268, -8.780597448349e-01, 1.191702168057e-07, 2.4653e+00, 4.0770e-03, 
 2DIAGNOSTIC,   269, -8.780597448349e-01, 1.187254312640e-07, 2.4694e+00, 4.0741e-03, 
 2DIAGNOSTIC,   270, -8.780597448349e-01, 1.182839568514e-07, 2.4735e+00, 4.0729e-03, 
 2DIAGNOSTIC,   271, -8.780597448349e-01, 1.178457509354e-07, 2.4775e+00, 4.0729e-03, 
 2DIAGNOSTIC,   272, -8.780597448349e-01, 1.174107850943e-07, 2.4816e+00, 4.0550e-03, 
 2DIAGNOSTIC,   273, -8.780597448349e-01, 1.169790095901e-07, 2.4857e+00, 4.0610e-03, 
 2DIAGNOSTIC,   274, -8.780597448349e-01, 1.165504031064e-07, 2.4897e+00, 4.0739e-03, 
 2DIAGNOSTIC,   275, -8.780597448349e-01, 1.161249230108e-07, 2.4938e+00, 4.0669e-03, 
 2DIAGNOSTIC,   276, -8.780597448349e-01, 1.157025408816e-07, 2.4979e+00, 4.0779e-03, 
 2DIAGNOSTIC,   277, -8.780597448349e-01, 1.152832211915e-07, 2.5019e+00, 4.0691e-03, 
 2DIAGNOSTIC,   278, -8.780597448349e-01, 1.148669284134e-07, 2.5060e+00, 4.0541e-03, 
 2DIAGNOSTIC,   279, -8.780597448349e-01, 1.144536341258e-07, 2.5101e+00, 4.0710e-03, 
 2DIAGNOSTIC,   280, -8.780597448349e-01, 1.140433028013e-07, 2.5141e+00, 4.0741e-03, 
 2DIAGNOSTIC,   281, -8.780597448349e-01, 1.136358989129e-07, 2.5182e+00, 4.0681e-03, 
 2DIAGNOSTIC,   282, -8.780597448349e-01, 1.132314011443e-07, 2.5223e+00, 4.0622e-03, 
 2DIAGNOSTIC,   283, -8.780597448349e-01, 1.128297668629e-07, 2.5263e+00, 4.0531e-03, 
 2DIAGNOSTIC,   284, -8.780597448349e-01, 1.124309747524e-07, 2.5304e+00, 4.0569e-03, 
 2DIAGNOSTIC,   285, -8.780597448349e-01, 1.120349892858e-07, 2.5345e+00, 4.0669e-03, 
 2DIAGNOSTIC,   286, -8.780597448349e-01, 1.116417891467e-07, 2.5385e+00, 4.0600e-03, 
 2DIAGNOSTIC,   287, -8.780597448349e-01, 1.112513317025e-07, 2.5426e+00, 4.0581e-03, 
 2DIAGNOSTIC,   288, -8.780597448349e-01, 1.108636027425e-07, 2.5466e+00, 4.0660e-03, 
 2DIAGNOSTIC,   289, -8.780597448349e-01, 1.104785596340e-07, 2.5507e+00, 4.0510e-03, 
 2DIAGNOSTIC,   290, -8.780597448349e-01, 1.100961881662e-07, 2.5548e+00, 4.0829e-03, 
 2DIAGNOSTIC,   291, -8.780597448349e-01, 1.097164528119e-07, 2.5589e+00, 4.0810e-03, 
 2DIAGNOSTIC,   292, -8.780597448349e-01, 1.093393251494e-07, 2.5629e+00, 4.0610e-03, 
 2DIAGNOSTIC,   293, -8.780597448349e-01, 1.089647838626e-07, 2.5670e+00, 4.0669e-03, 
 2DIAGNOSTIC,   294, -8.780597448349e-01, 1.085928005296e-07, 2.5710e+00, 4.0579e-03, 
 2DIAGNOSTIC,   295, -8.780597448349e-01, 1.082233467287e-07, 2.5751e+00, 4.1060e-03, 
 2DIAGNOSTIC,   296, -8.780597448349e-01, 1.078564011436e-07, 2.5792e+00, 4.0810e-03, 
 2DIAGNOSTIC,   297, -8.780597448349e-01, 1.074919353528e-07, 2.5833e+00, 4.0772e-03, 
 2DIAGNOSTIC,   298, -8.780597448349e-01, 1.071299209343e-07, 2.5878e+00, 4.4861e-03, 
 2DIAGNOSTIC,   299, -8.780597448349e-01, 1.067703365720e-07, 2.5922e+00, 4.4611e-03, 
 2DIAGNOSTIC,   300, -8.780597448349e-01, 1.064131609496e-07, 2.5964e+00, 4.1330e-03, 
 2DIAGNOSTIC,   301, -8.780597448349e-01, 1.060583656454e-07, 2.6005e+00, 4.1208e-03, 
 2DIAGNOSTIC,   302, -8.780597448349e-01, 1.057059293430e-07, 2.6046e+00, 4.0588e-03, 
 2DIAGNOSTIC,   303, -8.780597448349e-01, 1.053558236208e-07, 2.6086e+00, 4.0851e-03, 
 2DIAGNOSTIC,   304, -8.780597448349e-01, 1.050080342679e-07, 2.6127e+00, 4.0772e-03, 
 2DIAGNOSTIC,   305, -8.780597448349e-01, 1.046625328627e-07, 2.6168e+00, 4.0770e-03, 
 2DIAGNOSTIC,   306, -8.780597448349e-01, 1.043192980887e-07, 2.6209e+00, 4.1459e-03, 
 2DIAGNOSTIC,   307, -8.780597448349e-01, 1.039783015244e-07, 2.6250e+00, 4.0629e-03, 
 2DIAGNOSTIC,   308, -8.780597448349e-01, 1.036395360643e-07, 2.6291e+00, 4.0679e-03, 
 2DIAGNOSTIC,   309, -8.780597448349e-01, 1.033029661812e-07, 2.6332e+00, 4.1070e-03, 
 2DIAGNOSTIC,   310, -8.780597448349e-01, 1.029685705589e-07, 2.6373e+00, 4.0822e-03, 
 2DIAGNOSTIC,   311, -8.780597448349e-01, 1.026363349865e-07, 2.6414e+00, 4.0920e-03, 
 2DIAGNOSTIC,   312, -8.780597448349e-01, 1.023062452532e-07, 2.6454e+00, 4.0600e-03, 
 2DIAGNOSTIC,   313, -8.780597448349e-01, 1.019782658318e-07, 2.6495e+00, 4.0832e-03, 
 2DIAGNOSTIC,   314, -8.780597448349e-01, 1.016523754060e-07, 2.6536e+00, 4.0889e-03, 
 2DIAGNOSTIC,   315, -8.780597448349e-01, 1.013285739759e-07, 2.6577e+00, 4.0729e-03, 
 2DIAGNOSTIC,   316, -8.780597448349e-01, 1.010068189089e-07, 2.6617e+00, 4.0660e-03, 
 2DIAGNOSTIC,   317, -8.780597448349e-01, 1.006871030995e-07, 2.6663e+00, 4.5321e-03, 
 2DIAGNOSTIC,   318, -8.780597448349e-01, 1.003694123369e-07, 2.6709e+00, 4.6160e-03, 
 2DIAGNOSTIC,   319, -8.780597448349e-01, 1.000537110940e-07, 2.6754e+00, 4.5519e-03, 
 2DIAGNOSTIC,   320, -8.780597448349e-01, 9.973999226531e-08, 2.6796e+00, 4.1852e-03, 
 2DIAGNOSTIC,   321, -8.780597448349e-01, 9.942823453457e-08, 2.6837e+00, 4.0841e-03, 
 2DIAGNOSTIC,   322, -8.780597448349e-01, 9.911842369092e-08, 2.6878e+00, 4.0660e-03, 
 2DIAGNOSTIC,   323, -8.780597448349e-01, 9.881053131267e-08, 2.6919e+00, 4.1449e-03, 
 2DIAGNOSTIC,   324, -8.780597448349e-01, 9.850455029436e-08, 2.6960e+00, 4.0739e-03, 
 2DIAGNOSTIC,   325, -8.780597448349e-01, 9.820045221431e-08, 2.7001e+00, 4.0700e-03, 
 2DIAGNOSTIC,   326, -8.780597448349e-01, 9.789823707251e-08, 2.7041e+00, 4.0689e-03, 
 2DIAGNOSTIC,   327, -8.780597448349e-01, 9.759786934183e-08, 2.7082e+00, 4.0679e-03, 
 2DIAGNOSTIC,   328, -8.780597448349e-01, 9.729933481140e-08, 2.7123e+00, 4.0679e-03, 
 2DIAGNOSTIC,   329, -8.780597448349e-01, 9.700262637580e-08, 2.7163e+00, 4.0600e-03, 
 2DIAGNOSTIC,   330, -8.780597448349e-01, 9.670772271875e-08, 2.7210e+00, 4.6530e-03, 
 2DIAGNOSTIC,   331, -8.780597448349e-01, 9.641460252396e-08, 2.7254e+00, 4.3871e-03, 
 2DIAGNOSTIC,   332, -8.780597448349e-01, 9.612325868602e-08, 2.7294e+00, 4.0798e-03, 
 2DIAGNOSTIC,   333, -8.780597448349e-01, 9.583366988863e-08, 2.7335e+00, 4.0700e-03, 
 2DIAGNOSTIC,   334, -8.780597448349e-01, 9.554582192095e-08, 2.7376e+00, 4.0600e-03, 
 2DIAGNOSTIC,   335, -8.780597448349e-01, 9.525969346669e-08, 2.7417e+00, 4.0810e-03, 
 2DIAGNOSTIC,   336, -8.780597448349e-01, 9.497527742042e-08, 2.7457e+00, 4.0522e-03, 
 2DIAGNOSTIC,   337, -8.780597448349e-01, 9.469255246586e-08, 2.7498e+00, 4.0650e-03, 
 2DIAGNOSTIC,   338, -8.780597448349e-01, 9.441150439216e-08, 2.7538e+00, 4.0689e-03, 
 2DIAGNOSTIC,   339, -8.780597448349e-01, 9.413211898845e-08, 2.7579e+00, 4.0650e-03, 
 2DIAGNOSTIC,   340, -8.780597448349e-01, 9.385438204390e-08, 2.7620e+00, 4.0641e-03, 
 2DIAGNOSTIC,   341, -8.780597448349e-01, 9.357828645307e-08, 2.7660e+00, 4.0810e-03, 
 2DIAGNOSTIC,   342, -8.780597448349e-01, 9.330380379424e-08, 2.7701e+00, 4.0772e-03, 
 2DIAGNOSTIC,   343, -8.780597448349e-01, 9.303092696200e-08, 2.7742e+00, 4.0650e-03, 
 2DIAGNOSTIC,   344, -8.780597448349e-01, 9.275964885092e-08, 2.7783e+00, 4.0841e-03, 
 2DIAGNOSTIC,   345, -8.780597448349e-01, 9.248994103928e-08, 2.7823e+00, 4.0598e-03, 
 2DIAGNOSTIC,   346, -8.780597448349e-01, 9.222179642165e-08, 2.7864e+00, 4.0841e-03, 
 2DIAGNOSTIC,   347, -8.780597448349e-01, 9.195520789262e-08, 2.7905e+00, 4.0550e-03, 
 2DIAGNOSTIC,   348, -8.780597448349e-01, 9.169014703048e-08, 2.7945e+00, 4.0560e-03, 
 2DIAGNOSTIC,   349, -8.780597448349e-01, 9.142662094064e-08, 2.7986e+00, 4.0522e-03, 
 2DIAGNOSTIC,   350, -8.780597448349e-01, 9.116459409597e-08, 2.8026e+00, 4.0610e-03, 
 2DIAGNOSTIC,   351, -8.780597448349e-01, 9.090407360191e-08, 2.8067e+00, 4.0739e-03, 
 2DIAGNOSTIC,   352, -8.780597448349e-01, 9.064503103673e-08, 2.8108e+00, 4.0641e-03, 
 2DIAGNOSTIC,   353, -8.780597448349e-01, 9.038746640044e-08, 2.8148e+00, 4.0681e-03, 
 2DIAGNOSTIC,   354, -8.780597448349e-01, 9.013135837677e-08, 2.8189e+00, 4.0641e-03, 
 2DIAGNOSTIC,   355, -8.780597448349e-01, 8.987669986027e-08, 2.8231e+00, 4.1981e-03, 
 2DIAGNOSTIC,   356, -8.780597448349e-01, 8.962347664010e-08, 2.8273e+00, 4.1969e-03, 
 2DIAGNOSTIC,   357, -8.780597448349e-01, 8.937167450540e-08, 2.8314e+00, 4.0579e-03, 
 2DIAGNOSTIC,   358, -8.780597448349e-01, 8.912128635075e-08, 2.8354e+00, 4.0638e-03, 
 2DIAGNOSTIC,   359, -8.780597448349e-01, 8.887229085985e-08, 2.8395e+00, 4.0741e-03, 
 2DIAGNOSTIC,   360, -8.780597448349e-01, 8.862468803272e-08, 2.8436e+00, 4.0650e-03, 
 2DIAGNOSTIC,   361, -8.780597448349e-01, 8.837845655307e-08, 2.8476e+00, 4.0689e-03, 
 2DIAGNOSTIC,   362, -8.780597448349e-01, 8.813359642090e-08, 2.8517e+00, 4.0641e-03, 
 2DIAGNOSTIC,   363, -8.780597448349e-01, 8.789008631993e-08, 2.8558e+00, 4.0860e-03, 
 2DIAGNOSTIC,   364, -8.780597448349e-01, 8.764791203930e-08, 2.8599e+00, 4.0789e-03, 
 2DIAGNOSTIC,   365, -8.780597448349e-01, 8.740707357902e-08, 2.8640e+00, 4.0960e-03, 
 2DIAGNOSTIC,   366, -8.780597448349e-01, 8.716755672822e-08, 2.8680e+00, 4.0860e-03, 
 2DIAGNOSTIC,   367, -8.780597448349e-01, 8.692934727605e-08, 2.8722e+00, 4.1749e-03, 
 2DIAGNOSTIC,   368, -8.780597448349e-01, 8.669243811710e-08, 2.8769e+00, 4.7100e-03, 
 2DIAGNOSTIC,   369, -8.780597448349e-01, 8.645681504049e-08, 2.8813e+00, 4.3762e-03, 
 2DIAGNOSTIC,   370, -8.780597448349e-01, 8.622247094081e-08, 2.8857e+00, 4.4131e-03, 
 2DIAGNOSTIC,   371, -8.780597448349e-01, 8.598939160720e-08, 2.8898e+00, 4.1118e-03, 
 2DIAGNOSTIC,   372, -8.780597448349e-01, 8.575756993423e-08, 2.8941e+00, 4.2210e-03, 
 2DIAGNOSTIC,   373, -8.780597448349e-01, 8.552699171105e-08, 2.8981e+00, 4.0691e-03, 
 2DIAGNOSTIC,   374, -8.780597448349e-01, 8.529764983223e-08, 2.9022e+00, 4.0729e-03, 
 2DIAGNOSTIC,   375, -8.780597448349e-01, 8.506954429777e-08, 2.9063e+00, 4.0669e-03, 
 2DIAGNOSTIC,   376, -8.780597448349e-01, 8.484264668596e-08, 2.9103e+00, 4.0560e-03, 
 2DIAGNOSTIC,   377, -8.780597448349e-01, 8.461695699680e-08, 2.9144e+00, 4.0770e-03, 
 2DIAGNOSTIC,   378, -8.780597448349e-01, 8.439246812486e-08, 2.9185e+00, 4.0941e-03, 
 2DIAGNOSTIC,   379, -8.780597448349e-01, 8.416916585929e-08, 2.9226e+00, 4.0720e-03, 
 2DIAGNOSTIC,   380, -8.780597448349e-01, 8.394704309467e-08, 2.9268e+00, 4.1971e-03, 
 2DIAGNOSTIC,   381, -8.780597448349e-01, 8.372608562013e-08, 2.9308e+00, 4.0650e-03, 
 2DIAGNOSTIC,   382, -8.780597448349e-01, 8.350629343568e-08, 2.9349e+00, 4.0631e-03, 
 2DIAGNOSTIC,   383, -8.780597448349e-01, 8.328764522503e-08, 2.9390e+00, 4.0958e-03, 
 2DIAGNOSTIC,   384, -8.780597448349e-01, 8.307014098818e-08, 2.9431e+00, 4.0879e-03, 
 2DIAGNOSTIC,   385, -8.780597448349e-01, 8.285377361972e-08, 2.9471e+00, 4.0779e-03, 
 2DIAGNOSTIC,   386, -8.780597448349e-01, 8.263852890877e-08, 2.9512e+00, 4.0979e-03, 
 2DIAGNOSTIC,   387, -8.780597448349e-01, 8.242439974993e-08, 2.9553e+00, 4.0679e-03, 
 2DIAGNOSTIC,   388, -8.780597448349e-01, 8.221137903774e-08, 2.9594e+00, 4.0829e-03, 
 2DIAGNOSTIC,   389, -8.780597448349e-01, 8.199945256138e-08, 2.9635e+00, 4.0619e-03, 
 2DIAGNOSTIC,   390, -8.780597448349e-01, 8.178862032082e-08, 2.9675e+00, 4.0619e-03, 
 2DIAGNOSTIC,   391, -8.780597448349e-01, 8.157886810523e-08, 2.9716e+00, 4.0538e-03, 
 2DIAGNOSTIC,   392, -8.780597448349e-01, 8.137018880916e-08, 2.9756e+00, 4.0591e-03, 
 2DIAGNOSTIC,   393, -8.780597448349e-01, 8.116257532720e-08, 2.9797e+00, 4.0610e-03, 
 2DIAGNOSTIC,   394, -8.780597448349e-01, 8.095601344849e-08, 2.9837e+00, 4.0500e-03, 
 2DIAGNOSTIC,   395, -8.780597448349e-01, 8.075050317302e-08, 2.9878e+00, 4.1010e-03, 
 2DIAGNOSTIC,   396, -8.780597448349e-01, 8.054603739538e-08, 2.9919e+00, 4.0710e-03, 
 2DIAGNOSTIC,   397, -8.780597448349e-01, 8.034260190470e-08, 2.9960e+00, 4.0810e-03, 
 2DIAGNOSTIC,   398, -8.780597448349e-01, 8.014018959557e-08, 3.0001e+00, 4.0541e-03, 
 2DIAGNOSTIC,   399, -8.780597448349e-01, 7.993880046797e-08, 3.0041e+00, 4.0641e-03, 
 2DIAGNOSTIC,   400, -8.780597448349e-01, 7.973841320563e-08, 3.0082e+00, 4.0669e-03, 
 2DIAGNOSTIC,   401, -8.780597448349e-01, 7.953903491398e-08, 3.0122e+00, 4.0569e-03, 
 2DIAGNOSTIC,   402, -8.780597448349e-01, 7.934064427673e-08, 3.0163e+00, 4.0731e-03, 
 2DIAGNOSTIC,   403, -8.780597448349e-01, 7.914324129388e-08, 3.0204e+00, 4.0810e-03, 
 2DIAGNOSTIC,   404, -8.780597448349e-01, 7.894682596543e-08, 3.0246e+00, 4.1850e-03, 
 2DIAGNOSTIC,   405, -8.780597448349e-01, 7.875137697511e-08, 3.0287e+00, 4.0948e-03, 
 2DIAGNOSTIC,   406, -8.780597448349e-01, 7.855689432290e-08, 3.0328e+00, 4.0948e-03, 
 2DIAGNOSTIC,   407, -8.780597448349e-01, 7.836337090339e-08, 3.0368e+00, 4.0650e-03, 
 2DIAGNOSTIC,   408, -8.780597448349e-01, 7.817079961114e-08, 3.0409e+00, 4.0781e-03, 
 2DIAGNOSTIC,   409, -8.780597448349e-01, 7.797916623531e-08, 3.0450e+00, 4.0731e-03, 
 2DIAGNOSTIC,   410, -8.780597448349e-01, 7.778847788131e-08, 3.0490e+00, 4.0631e-03, 
 2DIAGNOSTIC,   411, -8.780597448349e-01, 7.759871323287e-08, 3.0531e+00, 4.0691e-03, 
 2DIAGNOSTIC,   412, -8.780597448349e-01, 7.740987939542e-08, 3.0572e+00, 4.0770e-03, 
 2DIAGNOSTIC,   413, -8.780597448349e-01, 7.722195505266e-08, 3.0613e+00, 4.0922e-03, 
 2DIAGNOSTIC,   414, -8.780597448349e-01, 7.703494731004e-08, 3.0654e+00, 4.0832e-03, 
 2DIAGNOSTIC,   415, -8.780597448349e-01, 7.684884195669e-08, 3.0695e+00, 4.0879e-03, 
 2DIAGNOSTIC,   416, -8.780597448349e-01, 7.666363188719e-08, 3.0735e+00, 4.0791e-03, 
 2DIAGNOSTIC,   417, -8.780597448349e-01, 7.647930999610e-08, 3.0776e+00, 4.0638e-03, 
 2DIAGNOSTIC,   418, -8.780597448349e-01, 7.629587628344e-08, 3.0820e+00, 4.3540e-03, 
 2DIAGNOSTIC,   419, -8.780597448349e-01, 7.611331653834e-08, 3.0862e+00, 4.2112e-03, 
 2DIAGNOSTIC,   420, -8.780597448349e-01, 7.593163076081e-08, 3.0902e+00, 4.0691e-03, 
 2DIAGNOSTIC,   421, -8.780597448349e-01, 7.575081184541e-08, 3.0943e+00, 4.0631e-03, 
 2DIAGNOSTIC,   422, -8.780597448349e-01, 7.557085268672e-08, 3.0983e+00, 4.0510e-03, 
 2DIAGNOSTIC,   423, -8.780597448349e-01, 7.539174617932e-08, 3.1024e+00, 4.0541e-03, 
 2DIAGNOSTIC,   424, -8.780597448349e-01, 7.521348521777e-08, 3.1065e+00, 4.0629e-03, 
 2DIAGNOSTIC,   425, -8.780597448349e-01, 7.503606269665e-08, 3.1105e+00, 4.0579e-03, 
 2DIAGNOSTIC,   426, -8.780597448349e-01, 7.485947861596e-08, 3.1146e+00, 4.0979e-03, 
 2DIAGNOSTIC,   427, -8.780597448349e-01, 7.468371876485e-08, 3.1187e+00, 4.0610e-03, 
 2DIAGNOSTIC,   428, -8.780597448349e-01, 7.450879024873e-08, 3.1227e+00, 4.0591e-03, 
 2DIAGNOSTIC,   429, -8.780597448349e-01, 7.433467175133e-08, 3.1268e+00, 4.0619e-03, 
 2DIAGNOSTIC,   430, -8.780597448349e-01, 7.416137037808e-08, 3.1309e+00, 4.0591e-03, 
 2DIAGNOSTIC,   431, -8.780597448349e-01, 7.398887191812e-08, 3.1349e+00, 4.0619e-03, 
 2DIAGNOSTIC,   432, -8.780597448349e-01, 7.381717637145e-08, 3.1390e+00, 4.0779e-03, 
 2DIAGNOSTIC,   433, -8.780597448349e-01, 7.364627663264e-08, 3.1431e+00, 4.0638e-03, 
 2DIAGNOSTIC,   434, -8.780597448349e-01, 7.347616559628e-08, 3.1471e+00, 4.0729e-03, 
 2DIAGNOSTIC,   435, -8.780597448349e-01, 7.330683615692e-08, 3.1512e+00, 4.0581e-03, 
 2DIAGNOSTIC,   436, -8.780597448349e-01, 7.313828831457e-08, 3.1553e+00, 4.0579e-03, 
 2DIAGNOSTIC,   437, -8.780597448349e-01, 7.297050785837e-08, 3.1593e+00, 4.0679e-03, 
 2DIAGNOSTIC,   438, -8.780597448349e-01, 7.280350189376e-08, 3.1634e+00, 4.0598e-03, 
 2DIAGNOSTIC,   439, -8.780597448349e-01, 7.263725620987e-08, 3.1675e+00, 4.0951e-03, 
 2DIAGNOSTIC,   440, -8.780597448349e-01, 7.247177080671e-08, 3.1716e+00, 4.0720e-03, 
 2DIAGNOSTIC,   441, -8.780597448349e-01, 7.230703147343e-08, 3.1756e+00, 4.0679e-03, 
 2DIAGNOSTIC,   442, -8.780597448349e-01, 7.214304531544e-08, 3.1797e+00, 4.0660e-03, 
 2DIAGNOSTIC,   443, -8.780597448349e-01, 7.197979812190e-08, 3.1838e+00, 4.0669e-03, 
 2DIAGNOSTIC,   444, -8.780597448349e-01, 7.181728989281e-08, 3.1878e+00, 4.0619e-03, 
 2DIAGNOSTIC,   445, -8.780597448349e-01, 7.165551352273e-08, 3.1919e+00, 4.0720e-03, 
 2DIAGNOSTIC,   446, -8.780597448349e-01, 7.149446901167e-08, 3.1960e+00, 4.0722e-03, 
 2DIAGNOSTIC,   447, -8.780597448349e-01, 7.133413504334e-08, 3.2001e+00, 4.1142e-03, 
 2DIAGNOSTIC,   448, -8.780597448349e-01, 7.117452582861e-08, 3.2041e+00, 4.0641e-03, 
 2DIAGNOSTIC,   449, -8.780597448349e-01, 7.101563426204e-08, 3.2082e+00, 4.0960e-03, 
 2DIAGNOSTIC,   450, -8.780597448349e-01, 7.085743902735e-08, 3.2123e+00, 4.0870e-03, 
 2DIAGNOSTIC,   451, -8.780597448349e-01, 7.069995433540e-08, 3.2164e+00, 4.1010e-03, 
 2DIAGNOSTIC,   452, -8.780597448349e-01, 7.054316597532e-08, 3.2205e+00, 4.0631e-03, 
 2DIAGNOSTIC,   453, -8.780597448349e-01, 7.038707394713e-08, 3.2246e+00, 4.0920e-03, 
 2DIAGNOSTIC,   454, -8.780597448349e-01, 7.023167114539e-08, 3.2287e+00, 4.1349e-03, 
 2DIAGNOSTIC,   455, -8.780597448349e-01, 7.007695046468e-08, 3.2328e+00, 4.0929e-03, 
 2DIAGNOSTIC,   456, -8.780597448349e-01, 6.992291190500e-08, 3.2369e+00, 4.0889e-03, 
 2DIAGNOSTIC,   457, -8.780597448349e-01, 6.976954836091e-08, 3.2416e+00, 4.6680e-03, 
 2DIAGNOSTIC,   458, -8.780597448349e-01, 6.961685272699e-08, 3.2458e+00, 4.2689e-03, 
 2DIAGNOSTIC,   459, -8.780597448349e-01, 6.946483210868e-08, 3.2499e+00, 4.0751e-03, 
 2DIAGNOSTIC,   460, -8.780597448349e-01, 6.931346518968e-08, 3.2540e+00, 4.0631e-03, 
 2DIAGNOSTIC,   461, -8.780597448349e-01, 6.916275907543e-08, 3.2580e+00, 4.0641e-03, 
 2DIAGNOSTIC,   462, -8.780597448349e-01, 6.901271376591e-08, 3.2622e+00, 4.1230e-03, 
 2DIAGNOSTIC,   463, -8.780597448349e-01, 6.886330794487e-08, 3.2662e+00, 4.0851e-03, 
 2DIAGNOSTIC,   464, -8.780597448349e-01, 6.871455582314e-08, 3.2703e+00, 4.0801e-03, 
 2DIAGNOSTIC,   465, -8.780597448349e-01, 6.856643608444e-08, 3.2744e+00, 4.0689e-03, 
 2DIAGNOSTIC,   466, -8.780597448349e-01, 6.841896293963e-08, 3.2785e+00, 4.0929e-03, 
 2DIAGNOSTIC,   467, -8.780597448349e-01, 6.827211507243e-08, 3.2826e+00, 4.0729e-03, 
 2DIAGNOSTIC,   468, -8.780597448349e-01, 6.812589958827e-08, 3.2866e+00, 4.0669e-03, 
 2DIAGNOSTIC,   469, -8.780597448349e-01, 6.798030938171e-08, 3.2907e+00, 4.0889e-03, 
 2DIAGNOSTIC,   470, -8.780597448349e-01, 6.783534445276e-08, 3.2949e+00, 4.1699e-03, 
 2DIAGNOSTIC,   471, -8.780597448349e-01, 6.769099059056e-08, 3.2990e+00, 4.0751e-03, 
 2DIAGNOSTIC,   472, -8.780597448349e-01, 6.754724779512e-08, 3.3031e+00, 4.1580e-03, 
 2DIAGNOSTIC,   473, -8.780597448349e-01, 6.740412317185e-08, 3.3072e+00, 4.0829e-03, 
 2DIAGNOSTIC,   474, -8.780597448349e-01, 6.726159540449e-08, 3.3113e+00, 4.0641e-03, 
 2DIAGNOSTIC,   475, -8.780597448349e-01, 6.711967159845e-08, 3.3153e+00, 4.0779e-03, 
 2DIAGNOSTIC,   476, -8.780597448349e-01, 6.697834464831e-08, 3.3194e+00, 4.0710e-03, 
 2DIAGNOSTIC,   477, -8.780597448349e-01, 6.683761455406e-08, 3.3235e+00, 4.0629e-03, 
 2DIAGNOSTIC,   478, -8.780597448349e-01, 6.669747421029e-08, 3.3275e+00, 4.0581e-03, 
 2DIAGNOSTIC,   479, -8.780597448349e-01, 6.655791651156e-08, 3.3316e+00, 4.0920e-03, 
 2DIAGNOSTIC,   480, -8.780597448349e-01, 6.641894145787e-08, 3.3357e+00, 4.0598e-03, 
 2DIAGNOSTIC,   481, -8.780597448349e-01, 6.628054904922e-08, 3.3397e+00, 4.0591e-03, 
 2DIAGNOSTIC,   482, -8.780597448349e-01, 6.614273218020e-08, 3.3438e+00, 4.0660e-03, 
 2DIAGNOSTIC,   483, -8.780597448349e-01, 6.600548374536e-08, 3.3479e+00, 4.0610e-03, 
 2DIAGNOSTIC,   484, -8.780597448349e-01, 6.586881085013e-08, 3.3519e+00, 4.0779e-03, 
 2DIAGNOSTIC,   485, -8.780597448349e-01, 6.573269928367e-08, 3.3560e+00, 4.0529e-03, 
 2DIAGNOSTIC,   486, -8.780597448349e-01, 6.559714194054e-08, 3.3601e+00, 4.0600e-03, 
 2DIAGNOSTIC,   487, -8.780597448349e-01, 6.546215303160e-08, 3.3641e+00, 4.0710e-03, 
 2DIAGNOSTIC,   488, -8.780597448349e-01, 6.532771124057e-08, 3.3682e+00, 4.0729e-03, 
 2DIAGNOSTIC,   489, -8.780597448349e-01, 6.519382367287e-08, 3.3723e+00, 4.0629e-03, 
 2DIAGNOSTIC,   490, -8.780597448349e-01, 6.506048322308e-08, 3.3764e+00, 4.1051e-03, 
 2DIAGNOSTIC,   491, -8.780597448349e-01, 6.492768989119e-08, 3.3804e+00, 4.0691e-03, 
 2DIAGNOSTIC,   492, -8.780597448349e-01, 6.479543657179e-08, 3.3845e+00, 4.0710e-03, 
 2DIAGNOSTIC,   493, -8.780597448349e-01, 6.466371615943e-08, 3.3886e+00, 4.0760e-03, 
 2DIAGNOSTIC,   494, -8.780597448349e-01, 6.453253575955e-08, 3.3927e+00, 4.0979e-03, 
 2DIAGNOSTIC,   495, -8.780597448349e-01, 6.440188116130e-08, 3.3969e+00, 4.2200e-03, 
 2DIAGNOSTIC,   496, -8.780597448349e-01, 6.427175947010e-08, 3.4012e+00, 4.2641e-03, 
 2DIAGNOSTIC,   497, -8.780597448349e-01, 6.414215647510e-08, 3.4052e+00, 4.0660e-03, 
 2DIAGNOSTIC,   498, -8.780597448349e-01, 6.401307928172e-08, 3.4093e+00, 4.0729e-03, 
 2DIAGNOSTIC,   499, -8.780597448349e-01, 6.388452078454e-08, 3.4134e+00, 4.0650e-03, 
 2DIAGNOSTIC,   500, -8.780597448349e-01, 6.375648098356e-08, 3.4174e+00, 4.0731e-03, 
 2DIAGNOSTIC,   501, -8.780597448349e-01, 6.362894566792e-08, 3.4216e+00, 4.1921e-03, 
 2DIAGNOSTIC,   502, -8.780597448349e-01, 6.350192904847e-08, 3.4258e+00, 4.1671e-03, 
 2DIAGNOSTIC,   503, -8.780597448349e-01, 6.337540980894e-08, 3.4301e+00, 4.2620e-03, 
 2DIAGNOSTIC,   504, -8.780597448349e-01, 6.324939505475e-08, 3.4343e+00, 4.2131e-03, 
 2DIAGNOSTIC,   505, -8.780597448349e-01, 6.312388478591e-08, 3.4384e+00, 4.0801e-03, 
 2DIAGNOSTIC,   506, -8.780597448349e-01, 6.299887189698e-08, 3.4424e+00, 4.0779e-03, 
 2DIAGNOSTIC,   507, -8.780597448349e-01, 6.287434928254e-08, 3.4467e+00, 4.2779e-03, 
 2DIAGNOSTIC,   508, -8.780597448349e-01, 6.275031694258e-08, 3.4509e+00, 4.2050e-03, 
 2DIAGNOSTIC,   509, -8.780597448349e-01, 6.262677487712e-08, 3.4550e+00, 4.1149e-03, 
 2DIAGNOSTIC,   510, -8.780597448349e-01, 6.250372308614e-08, 3.4591e+00, 4.0691e-03, 
 2DIAGNOSTIC,   511, -8.780597448349e-01, 6.238114735879e-08, 3.4632e+00, 4.0770e-03, 
 2DIAGNOSTIC,   512, -8.780597448349e-01, 6.225905480051e-08, 3.4673e+00, 4.0920e-03, 
 2DIAGNOSTIC,   513, -8.780597448349e-01, 6.213743830585e-08, 3.4713e+00, 4.0729e-03, 
 2DIAGNOSTIC,   514, -8.780597448349e-01, 6.201629787483e-08, 3.4754e+00, 4.0789e-03, 
 2DIAGNOSTIC,   515, -8.780597448349e-01, 6.189562640202e-08, 3.4795e+00, 4.0820e-03, 
 2DIAGNOSTIC,   516, -8.780597448349e-01, 6.177542388741e-08, 3.4836e+00, 4.0720e-03, 
 2DIAGNOSTIC,   517, -8.780597448349e-01, 6.165568322558e-08, 3.4877e+00, 4.1420e-03, 
 2DIAGNOSTIC,   518, -8.780597448349e-01, 6.153641152196e-08, 3.4919e+00, 4.1769e-03, 
 2DIAGNOSTIC,   519, -8.780597448349e-01, 6.141760167111e-08, 3.4961e+00, 4.2269e-03, 
 2DIAGNOSTIC,   520, -8.780597448349e-01, 6.129924656761e-08, 3.5003e+00, 4.1649e-03, 
 2DIAGNOSTIC,   521, -8.780597448349e-01, 6.118134621147e-08, 3.5044e+00, 4.1211e-03, 
 2DIAGNOSTIC,   522, -8.780597448349e-01, 6.106390060268e-08, 3.5085e+00, 4.0731e-03, 
 2DIAGNOSTIC,   523, -8.780597448349e-01, 6.094690263581e-08, 3.5126e+00, 4.0691e-03, 
 2DIAGNOSTIC,   524, -8.780597448349e-01, 6.083035231086e-08, 3.5167e+00, 4.0991e-03, 
 2DIAGNOSTIC,   525, -8.780597448349e-01, 6.071424962784e-08, 3.5208e+00, 4.1091e-03, 
 2DIAGNOSTIC,   526, -8.780597448349e-01, 6.059858748131e-08, 3.5248e+00, 4.0698e-03, 
 2DIAGNOSTIC,   527, -8.780597448349e-01, 6.048336587128e-08, 3.5289e+00, 4.0710e-03, 
 2DIAGNOSTIC,   528, -8.780597448349e-01, 6.036857769232e-08, 3.5332e+00, 4.3182e-03, 
 2DIAGNOSTIC,   529, -8.780597448349e-01, 6.025423004985e-08, 3.5373e+00, 4.0720e-03, 
 2DIAGNOSTIC,   530, -8.780597448349e-01, 6.014030873303e-08, 3.5414e+00, 4.0851e-03, 
 2DIAGNOSTIC,   531, -8.780597448349e-01, 6.002682084727e-08, 3.5454e+00, 4.0600e-03, 
 2DIAGNOSTIC,   532, -8.780597448349e-01, 5.991376639258e-08, 3.5500e+00, 4.5910e-03, 
 2DIAGNOSTIC,   533, -8.780597448349e-01, 5.980113115811e-08, 3.5547e+00, 4.7171e-03, 
 2DIAGNOSTIC,   534, -8.780597448349e-01, 5.968891514385e-08, 3.5595e+00, 4.7152e-03, 
 2DIAGNOSTIC,   535, -8.780597448349e-01, 5.957712545523e-08, 3.5639e+00, 4.4250e-03, 
 2DIAGNOSTIC,   536, -8.780597448349e-01, 5.946575143412e-08, 3.5679e+00, 4.0629e-03, 
 2DIAGNOSTIC,   537, -8.780597448349e-01, 5.935479308050e-08, 3.5721e+00, 4.1499e-03, 
 2DIAGNOSTIC,   538, -8.780597448349e-01, 5.924424684167e-08, 3.5763e+00, 4.2489e-03, 
 2DIAGNOSTIC,   539, -8.780597448349e-01, 5.913411271763e-08, 3.5805e+00, 4.1661e-03, 
 2DIAGNOSTIC,   540, -8.780597448349e-01, 5.902438715566e-08, 3.5846e+00, 4.0650e-03, 
 2DIAGNOSTIC,   541, -8.780597448349e-01, 5.891507015576e-08, 3.5887e+00, 4.1578e-03, 
 2DIAGNOSTIC,   542, -8.780597448349e-01, 5.880615461251e-08, 3.5929e+00, 4.1590e-03, 
 2DIAGNOSTIC,   543, -8.780597448349e-01, 5.869764052591e-08, 3.5974e+00, 4.4880e-03, 
 2DIAGNOSTIC,   544, -8.780597448349e-01, 5.858952789595e-08, 3.6020e+00, 4.6549e-03, 
 2DIAGNOSTIC,   545, -8.780597448349e-01, 5.848181316992e-08, 3.6061e+00, 4.0560e-03, 
 2DIAGNOSTIC,   546, -8.780597448349e-01, 5.837449279511e-08, 3.6102e+00, 4.0720e-03, 
 2DIAGNOSTIC,   547, -8.780597448349e-01, 5.826756677152e-08, 3.6143e+00, 4.0939e-03, 
 2DIAGNOSTIC,   548, -8.780597448349e-01, 5.816103154643e-08, 3.6183e+00, 4.0660e-03, 
 2DIAGNOSTIC,   549, -8.780597448349e-01, 5.805488356714e-08, 3.6224e+00, 4.0569e-03, 
 2DIAGNOSTIC,   550, -8.780597448349e-01, 5.794912283363e-08, 3.6266e+00, 4.2140e-03, 
 2DIAGNOSTIC,   551, -8.780597448349e-01, 5.784374579321e-08, 3.6310e+00, 4.3879e-03, 
 2DIAGNOSTIC,   552, -8.780597448349e-01, 5.773875244586e-08, 3.6357e+00, 4.6930e-03, 
 2DIAGNOSTIC,   553, -8.780597448349e-01, 5.763413923887e-08, 3.6404e+00, 4.6780e-03, 
 2DIAGNOSTIC,   554, -8.780597448349e-01, 5.752990617225e-08, 3.6450e+00, 4.5960e-03, 
 2DIAGNOSTIC,   555, -8.780597448349e-01, 5.742604969328e-08, 3.6497e+00, 4.7600e-03, 
 2DIAGNOSTIC,   556, -8.780597448349e-01, 5.732256624924e-08, 3.6541e+00, 4.3468e-03, 
 2DIAGNOSTIC,   557, -8.780597448349e-01, 5.721945228743e-08, 3.6581e+00, 4.0751e-03, 
 2DIAGNOSTIC,   558, -8.780597448349e-01, 5.711671136055e-08, 3.6622e+00, 4.0672e-03, 
 2DIAGNOSTIC,   559, -8.780597448349e-01, 5.701433991590e-08, 3.6663e+00, 4.0808e-03, 
 2DIAGNOSTIC,   560, -8.780597448349e-01, 5.691233440075e-08, 3.6703e+00, 4.0669e-03, 
 2DIAGNOSTIC,   561, -8.780597448349e-01, 5.681069126240e-08, 3.6745e+00, 4.1311e-03, 
 2DIAGNOSTIC,   562, -8.780597448349e-01, 5.670941050084e-08, 3.6787e+00, 4.2281e-03, 
 2DIAGNOSTIC,   563, -8.780597448349e-01, 5.660849211608e-08, 3.6828e+00, 4.0860e-03, 
 2DIAGNOSTIC,   564, -8.780597448349e-01, 5.650793255541e-08, 3.6869e+00, 4.0710e-03, 
 2DIAGNOSTIC,   565, -8.780597448349e-01, 5.640772826609e-08, 3.6910e+00, 4.1730e-03, 
 2DIAGNOSTIC,   566, -8.780597448349e-01, 5.630787924815e-08, 3.6951e+00, 4.0710e-03, 
 2DIAGNOSTIC,   567, -8.780597448349e-01, 5.620838194886e-08, 3.6992e+00, 4.0832e-03, 
 2DIAGNOSTIC,   568, -8.780597448349e-01, 5.610923636823e-08, 3.7033e+00, 4.0610e-03, 
 2DIAGNOSTIC,   569, -8.780597448349e-01, 5.601043895354e-08, 3.7073e+00, 4.0660e-03, 
 2DIAGNOSTIC,   570, -8.780597448349e-01, 5.591198970478e-08, 3.7114e+00, 4.0810e-03, 
 2DIAGNOSTIC,   571, -8.780597448349e-01, 5.581388862197e-08, 3.7155e+00, 4.0681e-03, 
 2DIAGNOSTIC,   572, -8.780597448349e-01, 5.571612859967e-08, 3.7196e+00, 4.1029e-03, 
 2DIAGNOSTIC,   573, -8.780597448349e-01, 5.561870963788e-08, 3.7237e+00, 4.0960e-03, 
 2DIAGNOSTIC,   574, -8.780597448349e-01, 5.552163173661e-08, 3.7278e+00, 4.1511e-03, 
 2DIAGNOSTIC,   575, -8.780597448349e-01, 5.542489134314e-08, 3.7319e+00, 4.1020e-03, 
 2DIAGNOSTIC,   576, -8.780597448349e-01, 5.532848845746e-08, 3.7362e+00, 4.2732e-03, 
 2DIAGNOSTIC,   577, -8.780597448349e-01, 5.523241952687e-08, 3.7403e+00, 4.0681e-03, 
 2DIAGNOSTIC,   578, -8.780597448349e-01, 5.513668455137e-08, 3.7444e+00, 4.1041e-03, 
 2DIAGNOSTIC,   579, -8.780597448349e-01, 5.504127997824e-08, 3.7484e+00, 4.0791e-03, 
 2DIAGNOSTIC,   580, -8.780597448349e-01, 5.494620580748e-08, 3.7525e+00, 4.0731e-03, 
 2DIAGNOSTIC,   581, -8.780597448349e-01, 5.485145848638e-08, 3.7566e+00, 4.0650e-03, 
 2DIAGNOSTIC,   582, -8.780597448349e-01, 5.475703801494e-08, 3.7607e+00, 4.0700e-03, 
 2DIAGNOSTIC,   583, -8.780597448349e-01, 5.466294439316e-08, 3.7647e+00, 4.0791e-03, 
 2DIAGNOSTIC,   584, -8.780597448349e-01, 5.456917051561e-08, 3.7688e+00, 4.0772e-03, 
 2DIAGNOSTIC,   585, -8.780597448349e-01, 5.447571993500e-08, 3.7729e+00, 4.0781e-03, 
 2DIAGNOSTIC,   586, -8.780597448349e-01, 5.438258554591e-08, 3.7769e+00, 4.0631e-03, 
 2DIAGNOSTIC,   587, -8.780597448349e-01, 5.428977090105e-08, 3.7810e+00, 4.0691e-03, 
 2DIAGNOSTIC,   588, -8.780597448349e-01, 5.419727244771e-08, 3.7851e+00, 4.0619e-03, 
 2DIAGNOSTIC,   589, -8.780597448349e-01, 5.410509018589e-08, 3.7892e+00, 4.0791e-03, 
 2DIAGNOSTIC,   590, -8.780597448349e-01, 5.401322056287e-08, 3.7933e+00, 4.1358e-03, 
 2DIAGNOSTIC,   591, -8.780597448349e-01, 5.392166002594e-08, 3.7974e+00, 4.0860e-03, 
 2DIAGNOSTIC,   592, -8.780597448349e-01, 5.383041212781e-08, 3.8015e+00, 4.1399e-03, 
 2DIAGNOSTIC,   593, -8.780597448349e-01, 5.373946976306e-08, 3.8058e+00, 4.3130e-03, 
 2DIAGNOSTIC,   594, -8.780597448349e-01, 5.364883648440e-08, 3.8099e+00, 4.0901e-03, 
 2DIAGNOSTIC,   595, -8.780597448349e-01, 5.355850873912e-08, 3.8140e+00, 4.0629e-03, 
 2DIAGNOSTIC,   596, -8.780597448349e-01, 5.346848297449e-08, 3.8180e+00, 4.0610e-03, 
 2DIAGNOSTIC,   597, -8.780597448349e-01, 5.337875919054e-08, 3.8221e+00, 4.0760e-03, 
 2DIAGNOSTIC,   598, -8.780597448349e-01, 5.328933738724e-08, 3.8262e+00, 4.0700e-03, 
 2DIAGNOSTIC,   599, -8.780597448349e-01, 5.320021401189e-08, 3.8303e+00, 4.1530e-03, 
 2DIAGNOSTIC,   600, -8.780597448349e-01, 5.311138906450e-08, 3.8346e+00, 4.2269e-03, 
 2DIAGNOSTIC,   601, -8.780597448349e-01, 5.302285899234e-08, 3.8389e+00, 4.3380e-03, 
 2DIAGNOSTIC,   602, -8.780597448349e-01, 5.293462379541e-08, 3.8430e+00, 4.0789e-03, 
 2DIAGNOSTIC,   603, -8.780597448349e-01, 5.284668347372e-08, 3.8471e+00, 4.0820e-03, 
 2DIAGNOSTIC,   604, -8.780597448349e-01, 5.275903447455e-08, 3.8512e+00, 4.0829e-03, 
 2DIAGNOSTIC,   605, -8.780597448349e-01, 5.267167324519e-08, 3.8555e+00, 4.3190e-03, 
 2DIAGNOSTIC,   606, -8.780597448349e-01, 5.258460333835e-08, 3.8600e+00, 4.5719e-03, 
 2DIAGNOSTIC,   607, -8.780597448349e-01, 5.249781764860e-08, 3.8647e+00, 4.6511e-03, 
 2DIAGNOSTIC,   608, -8.780597448349e-01, 5.241131972866e-08, 3.8691e+00, 4.3631e-03, 
 2DIAGNOSTIC,   609, -8.780597448349e-01, 5.232510957853e-08, 3.8734e+00, 4.3700e-03, 
 2DIAGNOSTIC,   610, -8.780597448349e-01, 5.223918009278e-08, 3.8776e+00, 4.1811e-03, 
 2DIAGNOSTIC,   611, -8.780597448349e-01, 5.215353127141e-08, 3.8817e+00, 4.0970e-03, 
 2DIAGNOSTIC,   612, -8.780597448349e-01, 5.206816311443e-08, 3.8858e+00, 4.0801e-03, 
 2DIAGNOSTIC,   613, -8.780597448349e-01, 5.198307562182e-08, 3.8902e+00, 4.4482e-03, 
 2DIAGNOSTIC,   614, -8.780597448349e-01, 5.189826168817e-08, 3.8944e+00, 4.2090e-03, 
 2DIAGNOSTIC,   615, -8.780597448349e-01, 5.181372841889e-08, 3.8985e+00, 4.0619e-03, 
 2DIAGNOSTIC,   616, -8.780597448349e-01, 5.172946870857e-08, 3.9026e+00, 4.0829e-03, 
 2DIAGNOSTIC,   617, -8.780597448349e-01, 5.164548255721e-08, 3.9066e+00, 4.0579e-03, 
 2DIAGNOSTIC,   618, -8.780597448349e-01, 5.156176996479e-08, 3.9107e+00, 4.0600e-03, 
 2DIAGNOSTIC,   619, -8.780597448349e-01, 5.147832737862e-08, 3.9149e+00, 4.2391e-03, 
 2DIAGNOSTIC,   620, -8.780597448349e-01, 5.139515124597e-08, 3.9190e+00, 4.0679e-03, 
 2DIAGNOSTIC,   621, -8.780597448349e-01, 5.131224867228e-08, 3.9231e+00, 4.0700e-03, 
 2DIAGNOSTIC,   622, -8.780597448349e-01, 5.122960899939e-08, 3.9272e+00, 4.0731e-03, 
 2DIAGNOSTIC,   623, -8.780597448349e-01, 5.114723578004e-08, 3.9312e+00, 4.0681e-03, 
 2DIAGNOSTIC,   624, -8.780597448349e-01, 5.106512901421e-08, 3.9353e+00, 4.0650e-03, 
 2DIAGNOSTIC,   625, -8.780597448349e-01, 5.098328514919e-08, 3.9397e+00, 4.3969e-03, 
 2DIAGNOSTIC,   626, -8.780597448349e-01, 5.090170418498e-08, 3.9442e+00, 4.5459e-03, 
 2DIAGNOSTIC,   627, -8.780597448349e-01, 5.082037901616e-08, 3.9489e+00, 4.6849e-03, 
 2DIAGNOSTIC,   628, -8.780597448349e-01, 5.073931674815e-08, 3.9533e+00, 4.3468e-03, 
 2DIAGNOSTIC,   629, -8.780597448349e-01, 5.065851382824e-08, 3.9574e+00, 4.1761e-03, 
 2DIAGNOSTIC,   630, -8.780597448349e-01, 5.057796670371e-08, 3.9615e+00, 4.0951e-03, 
 2DIAGNOSTIC,   631, -8.780597448349e-01, 5.049767537457e-08, 3.9657e+00, 4.1239e-03, 
 2DIAGNOSTIC,   632, -8.780597448349e-01, 5.041763628810e-08, 3.9698e+00, 4.1850e-03, 
 2DIAGNOSTIC,   633, -8.780597448349e-01, 5.033785299702e-08, 3.9740e+00, 4.1299e-03, 
 2DIAGNOSTIC,   634, -8.780597448349e-01, 5.025832194860e-08, 3.9854e+00, 1.1454e-02, 
 2DIAGNOSTIC,   635, -8.780597448349e-01, 5.017904314286e-08, 3.9895e+00, 4.1008e-03, 
 2DIAGNOSTIC,   636, -8.780597448349e-01, 5.010000947436e-08, 3.9938e+00, 4.2582e-03, 
 2DIAGNOSTIC,   637, -8.780597448349e-01, 5.002122804854e-08, 3.9985e+00, 4.7488e-03, 
 2DIAGNOSTIC,   638, -8.780597448349e-01, 4.994269175995e-08, 4.0031e+00, 4.6051e-03, 
 2DIAGNOSTIC,   639, -8.780597448349e-01, 4.986440416133e-08, 4.0074e+00, 4.2832e-03, 
 2DIAGNOSTIC,   640, -8.780597448349e-01, 4.978636169994e-08, 4.0118e+00, 4.3502e-03, 
 2DIAGNOSTIC,   641, -8.780597448349e-01, 4.970856082309e-08, 4.0159e+00, 4.1311e-03, 
 2DIAGNOSTIC,   642, -8.780597448349e-01, 4.963100508348e-08, 4.0201e+00, 4.1521e-03, 
 2DIAGNOSTIC,   643, -8.780597448349e-01, 4.955368737569e-08, 4.0242e+00, 4.1010e-03, 
 2DIAGNOSTIC,   644, -8.780597448349e-01, 4.947661480514e-08, 4.0282e+00, 4.0810e-03, 
 2DIAGNOSTIC,   645, -8.780597448349e-01, 4.939977671370e-08, 4.0323e+00, 4.0770e-03, 
 2DIAGNOSTIC,   646, -8.780597448349e-01, 4.932318020678e-08, 4.0364e+00, 4.0820e-03, 
 2DIAGNOSTIC,   647, -8.780597448349e-01, 4.924682173169e-08, 4.0406e+00, 4.2360e-03, 
 2DIAGNOSTIC,   648, -8.780597448349e-01, 4.917069773569e-08, 4.0448e+00, 4.1502e-03, 
 2DIAGNOSTIC,   649, -8.780597448349e-01, 4.909480821880e-08, 4.0489e+00, 4.0951e-03, 
 2DIAGNOSTIC,   650, -8.780597448349e-01, 4.901915318101e-08, 4.0535e+00, 4.5831e-03, 
 2DIAGNOSTIC,   651, -8.780597448349e-01, 4.894372906961e-08, 4.0582e+00, 4.7731e-03, 
 2DIAGNOSTIC,   652, -8.780597448349e-01, 4.886853943731e-08, 4.0623e+00, 4.1091e-03, 
 2DIAGNOSTIC,   653, -8.780597448349e-01, 4.879357717869e-08, 4.0666e+00, 4.2372e-03, 
 2DIAGNOSTIC,   654, -8.780597448349e-01, 4.871884939917e-08, 4.0707e+00, 4.1091e-03, 
 2DIAGNOSTIC,   655, -8.780597448349e-01, 4.864434544061e-08, 4.0748e+00, 4.0700e-03, 
 2DIAGNOSTIC,   656, -8.780597448349e-01, 4.857007240844e-08, 4.0789e+00, 4.0970e-03, 
 2DIAGNOSTIC,   657, -8.780597448349e-01, 4.849602319723e-08, 4.0830e+00, 4.1389e-03, 
 2DIAGNOSTIC,   658, -8.780597448349e-01, 4.842220135970e-08, 4.0871e+00, 4.0741e-03, 
 2DIAGNOSTIC,   659, -8.780597448349e-01, 4.834860334313e-08, 4.0912e+00, 4.1101e-03, 
 2DIAGNOSTIC,   660, -8.780597448349e-01, 4.827522914752e-08, 4.0955e+00, 4.3011e-03, 
 2DIAGNOSTIC,   661, -8.780597448349e-01, 4.820207877287e-08, 4.0996e+00, 4.0660e-03, 
 2DIAGNOSTIC,   662, -8.780597448349e-01, 4.812914511376e-08, 4.1036e+00, 4.0741e-03, 
 2DIAGNOSTIC,   663, -8.780597448349e-01, 4.805643527561e-08, 4.1077e+00, 4.1089e-03, 
 2DIAGNOSTIC,   664, -8.780597448349e-01, 4.798394570571e-08, 4.1119e+00, 4.2038e-03, 
 2DIAGNOSTIC,   665, -8.780597448349e-01, 4.791167285134e-08, 4.1160e+00, 4.0882e-03, 
 2DIAGNOSTIC,   666, -8.780597448349e-01, 4.783961671251e-08, 4.1201e+00, 4.0901e-03, 
 2DIAGNOSTIC,   667, -8.780597448349e-01, 4.776777728921e-08, 4.1243e+00, 4.1659e-03, 
 2DIAGNOSTIC,   668, -8.780597448349e-01, 4.769615458144e-08, 4.1284e+00, 4.1471e-03, 
 2DIAGNOSTIC,   669, -8.780597448349e-01, 4.762474503650e-08, 4.1325e+00, 4.0960e-03, 
 2DIAGNOSTIC,   670, -8.780597448349e-01, 4.755354865438e-08, 4.1366e+00, 4.0751e-03, 
 2DIAGNOSTIC,   671, -8.780597448349e-01, 4.748256543508e-08, 4.1407e+00, 4.1120e-03, 
 2DIAGNOSTIC,   672, -8.780597448349e-01, 4.741179537859e-08, 4.1450e+00, 4.2751e-03, 
 2DIAGNOSTIC,   673, -8.780597448349e-01, 4.734123493222e-08, 4.1491e+00, 4.0989e-03, 
 2DIAGNOSTIC,   674, -8.780597448349e-01, 4.727088409595e-08, 4.1532e+00, 4.0679e-03, 
 2DIAGNOSTIC,   675, -8.780597448349e-01, 4.720073931708e-08, 4.1573e+00, 4.1029e-03, 
 2DIAGNOSTIC,   676, -8.780597448349e-01, 4.713080770102e-08, 4.1617e+00, 4.4599e-03, 
 2DIAGNOSTIC,   677, -8.780597448349e-01, 4.706107858965e-08, 4.1658e+00, 4.0920e-03, 
 2DIAGNOSTIC,   678, -8.780597448349e-01, 4.699155908838e-08, 4.1699e+00, 4.0739e-03, 
 2DIAGNOSTIC,   679, -8.780597448349e-01, 4.692224209180e-08, 4.1741e+00, 4.2019e-03, 
 2DIAGNOSTIC,   680, -8.780597448349e-01, 4.685312759989e-08, 4.1783e+00, 4.1840e-03, 
 2DIAGNOSTIC,   681, -8.780597448349e-01, 4.678421916537e-08, 4.1823e+00, 4.0760e-03, 
 2DIAGNOSTIC,   682, -8.780597448349e-01, 4.671551323554e-08, 4.1866e+00, 4.2210e-03, 
 2DIAGNOSTIC,   683, -8.780597448349e-01, 4.664700981039e-08, 4.1913e+00, 4.7629e-03, 
 2DIAGNOSTIC,   684, -8.780597448349e-01, 4.657870533720e-08, 4.1960e+00, 4.6740e-03, 
 2DIAGNOSTIC,   685, -8.780597448349e-01, 4.651059981597e-08, 4.2004e+00, 4.3678e-03, 
 2DIAGNOSTIC,   686, -8.780597448349e-01, 4.644269324672e-08, 4.2046e+00, 4.2231e-03, 
 2DIAGNOSTIC,   687, -8.780597448349e-01, 4.637498562943e-08, 4.2087e+00, 4.1089e-03, 
 2DIAGNOSTIC,   688, -8.780597448349e-01, 4.630747696410e-08, 4.2131e+00, 4.4019e-03, 
 2DIAGNOSTIC,   689, -8.780597448349e-01, 4.624016014532e-08, 4.2172e+00, 4.0781e-03, 
 2DIAGNOSTIC,   690, -8.780597448349e-01, 4.617304227850e-08, 4.2213e+00, 4.0741e-03, 
 2DIAGNOSTIC,   691, -8.780597448349e-01, 4.610611625822e-08, 4.2253e+00, 4.0920e-03, 
 2DIAGNOSTIC,   692, -8.780597448349e-01, 4.603938563719e-08, 4.2295e+00, 4.1599e-03, 
 2DIAGNOSTIC,   693, -8.780597448349e-01, 4.597285041541e-08, 4.2336e+00, 4.0889e-03, 
 2DIAGNOSTIC,   694, -8.780597448349e-01, 4.590650348746e-08, 4.2378e+00, 4.2090e-03, 
 2DIAGNOSTIC,   695, -8.780597448349e-01, 4.584034840605e-08, 4.2420e+00, 4.1542e-03, 
 2DIAGNOSTIC,   696, -8.780597448349e-01, 4.577438517117e-08, 4.2462e+00, 4.2062e-03, 
 2DIAGNOSTIC,   697, -8.780597448349e-01, 4.570861023012e-08, 4.2503e+00, 4.0932e-03, 
 2DIAGNOSTIC,   698, -8.780597448349e-01, 4.564302358290e-08, 4.2544e+00, 4.1401e-03, 
 2DIAGNOSTIC,   699, -8.780597448349e-01, 4.557762522950e-08, 4.2585e+00, 4.0972e-03, 
 2DIAGNOSTIC,   700, -8.780597448349e-01, 4.551241516992e-08, 4.2628e+00, 4.3421e-03, 
 2DIAGNOSTIC,   701, -8.780597448349e-01, 4.544738985146e-08, 4.2674e+00, 4.5390e-03, 
 2DIAGNOSTIC,   702, -8.780597448349e-01, 4.538255282682e-08, 4.2715e+00, 4.1170e-03, 
 2DIAGNOSTIC,   703, -8.780597448349e-01, 4.531789699058e-08, 4.2756e+00, 4.0739e-03, 
 2DIAGNOSTIC,   704, -8.780597448349e-01, 4.525342944817e-08, 4.2796e+00, 4.0770e-03, 
 2DIAGNOSTIC,   705, -8.780597448349e-01, 4.518914309415e-08, 4.2841e+00, 4.4680e-03, 
 2DIAGNOSTIC,   706, -8.780597448349e-01, 4.512503792853e-08, 4.2888e+00, 4.7331e-03, 
 2DIAGNOSTIC,   707, -8.780597448349e-01, 4.506111395131e-08, 4.2933e+00, 4.4589e-03, 
 2DIAGNOSTIC,   708, -8.780597448349e-01, 4.499737116248e-08, 4.2980e+00, 4.7269e-03, 
 2DIAGNOSTIC,   709, -8.780597448349e-01, 4.493380956205e-08, 4.3027e+00, 4.6940e-03, 
 2DIAGNOSTIC,   710, -8.780597448349e-01, 4.487042559731e-08, 4.3073e+00, 4.5919e-03, 
 2DIAGNOSTIC,   711, -8.780597448349e-01, 4.480722282096e-08, 4.3117e+00, 4.3802e-03, 
 2DIAGNOSTIC,   712, -8.780597448349e-01, 4.474419768030e-08, 4.3159e+00, 4.2470e-03, 
 2DIAGNOSTIC,   713, -8.780597448349e-01, 4.468134662261e-08, 4.3204e+00, 4.4060e-03, 
 2DIAGNOSTIC,   714, -8.780597448349e-01, 4.461867320060e-08, 4.3247e+00, 4.3430e-03, 
 2DIAGNOSTIC,   715, -8.780597448349e-01, 4.455617741428e-08, 4.3291e+00, 4.3759e-03, 
 2DIAGNOSTIC,   716, -8.780597448349e-01, 4.449385571093e-08, 4.3332e+00, 4.1370e-03, 
 2DIAGNOSTIC,   717, -8.780597448349e-01, 4.443170453783e-08, 4.3373e+00, 4.0810e-03, 
 2DIAGNOSTIC,   718, -8.780597448349e-01, 4.436973100042e-08, 4.3414e+00, 4.1358e-03, 
 2DIAGNOSTIC,   719, -8.780597448349e-01, 4.430792799326e-08, 4.3462e+00, 4.8170e-03, 
 2DIAGNOSTIC,   720, -8.780597448349e-01, 4.424629906907e-08, 4.3503e+00, 4.1020e-03, 
 2DIAGNOSTIC,   721, -8.780597448349e-01, 4.418483712243e-08, 4.3546e+00, 4.2970e-03, 
 2DIAGNOSTIC,   722, -8.780597448349e-01, 4.412354925876e-08, 4.3587e+00, 4.0820e-03, 
 2DIAGNOSTIC,   723, -8.780597448349e-01, 4.406243192534e-08, 4.3628e+00, 4.0829e-03, 
 2DIAGNOSTIC,   724, -8.780597448349e-01, 4.400148156947e-08, 4.3669e+00, 4.0839e-03, 
 2DIAGNOSTIC,   725, -8.780597448349e-01, 4.394069819114e-08, 4.3711e+00, 4.1800e-03, 
 2DIAGNOSTIC,   726, -8.780597448349e-01, 4.388008534306e-08, 4.3754e+00, 4.3480e-03, 
 2DIAGNOSTIC,   727, -8.780597448349e-01, 4.381963947253e-08, 4.3795e+00, 4.0808e-03, 
 2DIAGNOSTIC,   728, -8.780597448349e-01, 4.375935702683e-08, 4.3836e+00, 4.0760e-03, 
 2DIAGNOSTIC,   729, -8.780597448349e-01, 4.369924155867e-08, 4.3876e+00, 4.0710e-03, 
 2DIAGNOSTIC,   730, -8.780597448349e-01, 4.363929306805e-08, 4.3917e+00, 4.0731e-03, 
 2DIAGNOSTIC,   731, -8.780597448349e-01, 4.357950800227e-08, 4.3962e+00, 4.4811e-03, 
 2DIAGNOSTIC,   732, -8.780597448349e-01, 4.351988636131e-08, 4.4006e+00, 4.3771e-03, 
 2DIAGNOSTIC,   733, -8.780597448349e-01, 4.346042459247e-08, 4.4050e+00, 4.3728e-03, 
 2DIAGNOSTIC,   734, -8.780597448349e-01, 4.340112980117e-08, 4.4091e+00, 4.1251e-03, 
 2DIAGNOSTIC,   735, -8.780597448349e-01, 4.334199488198e-08, 4.4132e+00, 4.1411e-03, 
 2DIAGNOSTIC,   736, -8.780597448349e-01, 4.328301983492e-08, 4.4173e+00, 4.0960e-03, 
 2DIAGNOSTIC,   737, -8.780597448349e-01, 4.322420465996e-08, 4.4214e+00, 4.1351e-03, 
 2DIAGNOSTIC,   738, -8.780597448349e-01, 4.316554935713e-08, 4.4256e+00, 4.1251e-03, 
 2DIAGNOSTIC,   739, -8.780597448349e-01, 4.310705392641e-08, 4.4296e+00, 4.0760e-03, 
 2DIAGNOSTIC,   740, -8.780597448349e-01, 4.304871836780e-08, 4.4338e+00, 4.1640e-03, 
 2DIAGNOSTIC,   741, -8.780597448349e-01, 4.299053912860e-08, 4.4379e+00, 4.1008e-03, 
 2DIAGNOSTIC,   742, -8.780597448349e-01, 4.293251620879e-08, 4.4420e+00, 4.0870e-03, 
 2DIAGNOSTIC,   743, -8.780597448349e-01, 4.287464960839e-08, 4.4462e+00, 4.1871e-03, 
 2DIAGNOSTIC,   744, -8.780597448349e-01, 4.281693932739e-08, 4.4503e+00, 4.0789e-03, 
 2DIAGNOSTIC,   745, -8.780597448349e-01, 4.275938536580e-08, 4.4543e+00, 4.0820e-03, 
 2DIAGNOSTIC,   746, -8.780597448349e-01, 4.270198417089e-08, 4.4584e+00, 4.0772e-03, 
 2DIAGNOSTIC,   747, -8.780597448349e-01, 4.264473574267e-08, 4.4625e+00, 4.0720e-03, 
 2DIAGNOSTIC,   748, -8.780597448349e-01, 4.258764363385e-08, 4.4666e+00, 4.1001e-03, 
 2DIAGNOSTIC,   749, -8.780597448349e-01, 4.253070073901e-08, 4.4707e+00, 4.1242e-03, 
 2DIAGNOSTIC,   750, -8.780597448349e-01, 4.247391416357e-08, 4.4748e+00, 4.0841e-03, 
 2DIAGNOSTIC,   751, -8.780597448349e-01, 4.241727680210e-08, 4.4789e+00, 4.0720e-03, 
 2DIAGNOSTIC,   752, -8.780597448349e-01, 4.236078865461e-08, 4.4834e+00, 4.4818e-03, 
 2DIAGNOSTIC,   753, -8.780597448349e-01, 4.230445327380e-08, 4.4875e+00, 4.1599e-03, 
 2DIAGNOSTIC,   754, -8.780597448349e-01, 4.224826710697e-08, 4.4916e+00, 4.1239e-03, 
 2DIAGNOSTIC,   755, -8.780597448349e-01, 4.219223015411e-08, 4.4957e+00, 4.0729e-03, 
 2DIAGNOSTIC,   756, -8.780597448349e-01, 4.213633886252e-08, 4.4999e+00, 4.2040e-03, 
 2DIAGNOSTIC,   757, -8.780597448349e-01, 4.208060033761e-08, 4.5040e+00, 4.0791e-03, 
 2DIAGNOSTIC,   758, -8.780597448349e-01, 4.202500392125e-08, 4.5081e+00, 4.0870e-03, 
 2DIAGNOSTIC,   759, -8.780597448349e-01, 4.196955671887e-08, 4.5122e+00, 4.1111e-03, 
 2DIAGNOSTIC,   760, -8.780597448349e-01, 4.191425873046e-08, 4.5164e+00, 4.2491e-03, 
 2DIAGNOSTIC,   761, -8.780597448349e-01, 4.185910285059e-08, 4.5205e+00, 4.0779e-03, 
 2DIAGNOSTIC,   762, -8.780597448349e-01, 4.180409263199e-08, 4.5246e+00, 4.0600e-03, 
 2DIAGNOSTIC,   763, -8.780597448349e-01, 4.174922452194e-08, 4.5286e+00, 4.0631e-03, 
 2DIAGNOSTIC,   764, -8.780597448349e-01, 4.169450207314e-08, 4.5327e+00, 4.0789e-03, 
 2DIAGNOSTIC,   765, -8.780597448349e-01, 4.163992528561e-08, 4.5368e+00, 4.1101e-03, 
 2DIAGNOSTIC,   766, -8.780597448349e-01, 4.158548705391e-08, 4.5410e+00, 4.2112e-03, 
 2DIAGNOSTIC,   767, -8.780597448349e-01, 4.153119448347e-08, 4.5454e+00, 4.3349e-03, 
 2DIAGNOSTIC,   768, -8.780597448349e-01, 4.147704046886e-08, 4.5496e+00, 4.2081e-03, 
 2DIAGNOSTIC,   769, -8.780597448349e-01, 4.142302856280e-08, 4.5537e+00, 4.1342e-03, 
 2DIAGNOSTIC,   770, -8.780597448349e-01, 4.136915876529e-08, 4.5580e+00, 4.2779e-03, 
 2DIAGNOSTIC,   771, -8.780597448349e-01, 4.131542752361e-08, 4.5621e+00, 4.0700e-03, 
 2DIAGNOSTIC,   772, -8.780597448349e-01, 4.126183483777e-08, 4.5663e+00, 4.2679e-03, 
 2DIAGNOSTIC,   773, -8.780597448349e-01, 4.120838070776e-08, 4.5704e+00, 4.0910e-03, 
 2DIAGNOSTIC,   774, -8.780597448349e-01, 4.115506868629e-08, 4.5746e+00, 4.1571e-03, 
 2DIAGNOSTIC,   775, -8.780597448349e-01, 4.110189166795e-08, 4.5787e+00, 4.0689e-03, 
 2DIAGNOSTIC,   776, -8.780597448349e-01, 4.104884965273e-08, 4.5827e+00, 4.0779e-03, 
 2DIAGNOSTIC,   777, -8.780597448349e-01, 4.099594619333e-08, 4.5870e+00, 4.2241e-03, 
 2DIAGNOSTIC,   778, -8.780597448349e-01, 4.094318128978e-08, 4.5911e+00, 4.1752e-03, 
 2DIAGNOSTIC,   779, -8.780597448349e-01, 4.089055138934e-08, 4.5952e+00, 4.0820e-03, 
 2DIAGNOSTIC,   780, -8.780597448349e-01, 4.083805293931e-08, 4.5993e+00, 4.0681e-03, 
 2DIAGNOSTIC,   781, -8.780597448349e-01, 4.078569304511e-08, 4.6034e+00, 4.0841e-03, 
 2DIAGNOSTIC,   782, -8.780597448349e-01, 4.073346460132e-08, 4.6074e+00, 4.0631e-03, 
 2DIAGNOSTIC,   783, -8.780597448349e-01, 4.068137116064e-08, 4.6115e+00, 4.1091e-03, 
 2DIAGNOSTIC,   784, -8.780597448349e-01, 4.062941272309e-08, 4.6156e+00, 4.0798e-03, 
 2DIAGNOSTIC,   785, -8.780597448349e-01, 4.057758218323e-08, 4.6198e+00, 4.1530e-03, 
 2DIAGNOSTIC,   786, -8.780597448349e-01, 4.052588664649e-08, 4.6238e+00, 4.0739e-03, 
 2DIAGNOSTIC,   787, -8.780597448349e-01, 4.047432256016e-08, 4.6280e+00, 4.1590e-03, 
 2DIAGNOSTIC,   788, -8.780597448349e-01, 4.042288992423e-08, 4.6321e+00, 4.0920e-03, 
 2DIAGNOSTIC,   789, -8.780597448349e-01, 4.037158873871e-08, 4.6362e+00, 4.0689e-03, 
 2DIAGNOSTIC,   790, -8.780597448349e-01, 4.032041545088e-08, 4.6404e+00, 4.1909e-03, 
 2DIAGNOSTIC,   791, -8.780597448349e-01, 4.026937006074e-08, 4.6445e+00, 4.1308e-03, 
 2DIAGNOSTIC,   792, -8.780597448349e-01, 4.021845612101e-08, 4.6486e+00, 4.0920e-03, 
 2DIAGNOSTIC,   793, -8.780597448349e-01, 4.016767363169e-08, 4.6527e+00, 4.0789e-03, 
 2DIAGNOSTIC,   794, -8.780597448349e-01, 4.011701548734e-08, 4.6567e+00, 4.0579e-03, 
 2DIAGNOSTIC,   795, -8.780597448349e-01, 4.006648524069e-08, 4.6608e+00, 4.0739e-03, 
 2DIAGNOSTIC,   796, -8.780597448349e-01, 4.001608289173e-08, 4.6651e+00, 4.2751e-03, 
 2DIAGNOSTIC,   797, -8.780597448349e-01, 3.996580488774e-08, 4.6694e+00, 4.3330e-03, 
 2DIAGNOSTIC,   798, -8.780597448349e-01, 3.991565478145e-08, 4.6735e+00, 4.0619e-03, 
 2DIAGNOSTIC,   799, -8.780597448349e-01, 3.986563257286e-08, 4.6775e+00, 4.0770e-03, 
 2DIAGNOSTIC,   800, -8.780597448349e-01, 3.981573470924e-08, 4.6816e+00, 4.0669e-03, 
 2DIAGNOSTIC,   801, -8.780597448349e-01, 3.976596119060e-08, 4.6858e+00, 4.1630e-03, 
 2DIAGNOSTIC,   802, -8.780597448349e-01, 3.971630846422e-08, 4.6899e+00, 4.1571e-03, 
 2DIAGNOSTIC,   803, -8.780597448349e-01, 3.966678363554e-08, 4.6940e+00, 4.0882e-03, 
 2DIAGNOSTIC,   804, -8.780597448349e-01, 3.961737959912e-08, 4.6981e+00, 4.0851e-03, 
 2DIAGNOSTIC,   805, -8.780597448349e-01, 3.956809990768e-08, 4.7022e+00, 4.1170e-03, 
 2DIAGNOSTIC,   806, -8.780597448349e-01, 3.951894456122e-08, 4.7064e+00, 4.1389e-03, 
 2DIAGNOSTIC,   807, -8.780597448349e-01, 3.946991000703e-08, 4.7104e+00, 4.0870e-03, 
 2DIAGNOSTIC,   808, -8.780597448349e-01, 3.942099624510e-08, 4.7145e+00, 4.0648e-03, 
 2DIAGNOSTIC,   809, -8.780597448349e-01, 3.937220327543e-08, 4.7190e+00, 4.5221e-03, 
 2DIAGNOSTIC,   810, -8.780597448349e-01, 3.932353109803e-08, 4.7236e+00, 4.5271e-03, 
 2DIAGNOSTIC,   811, -8.780597448349e-01, 3.927497971290e-08, 4.7282e+00, 4.6170e-03, 
 2DIAGNOSTIC,   812, -8.780597448349e-01, 3.922654556732e-08, 4.7323e+00, 4.0832e-03, 
 2DIAGNOSTIC,   813, -8.780597448349e-01, 3.917823221400e-08, 4.7368e+00, 4.5240e-03, 
 2DIAGNOSTIC,   814, -8.780597448349e-01, 3.913003965295e-08, 4.7409e+00, 4.1330e-03, 
 2DIAGNOSTIC,   815, -8.780597448349e-01, 3.908196433144e-08, 4.7450e+00, 4.1349e-03, 
 2DIAGNOSTIC,   816, -8.780597448349e-01, 3.903400624949e-08, 4.7493e+00, 4.2870e-03, 
 2DIAGNOSTIC,   817, -8.780597448349e-01, 3.898616540710e-08, 4.7535e+00, 4.1921e-03, 
 2DIAGNOSTIC,   818, -8.780597448349e-01, 3.893844180425e-08, 4.7581e+00, 4.5791e-03, 
 2DIAGNOSTIC,   819, -8.780597448349e-01, 3.889083899367e-08, 4.7631e+00, 5.0089e-03, 
 2DIAGNOSTIC,   820, -8.780597448349e-01, 3.884334631721e-08, 4.7680e+00, 4.8881e-03, 
 2DIAGNOSTIC,   821, -8.780597448349e-01, 3.879597443301e-08, 4.7727e+00, 4.6790e-03, 
 2DIAGNOSTIC,   822, -8.780597448349e-01, 3.874871623566e-08, 4.7771e+00, 4.3709e-03, 
 2DIAGNOSTIC,   823, -8.780597448349e-01, 3.870157172514e-08, 4.7816e+00, 4.5059e-03, 
 2DIAGNOSTIC,   824, -8.780597448349e-01, 3.865454090146e-08, 4.7861e+00, 4.5171e-03, 
 2DIAGNOSTIC,   825, -8.780597448349e-01, 3.860762731733e-08, 4.7905e+00, 4.3740e-03, 
 2DIAGNOSTIC,   826, -8.780597448349e-01, 3.856082742004e-08, 4.7945e+00, 4.0851e-03, 
 2DIAGNOSTIC,   827, -8.780597448349e-01, 3.851413765688e-08, 4.7986e+00, 4.0870e-03, 
 2DIAGNOSTIC,   828, -8.780597448349e-01, 3.846756158055e-08, 4.8029e+00, 4.3058e-03, 
 2DIAGNOSTIC,   829, -8.780597448349e-01, 3.842109919105e-08, 4.8070e+00, 4.0731e-03, 
 2DIAGNOSTIC,   830, -8.780597448349e-01, 3.837475048840e-08, 4.8111e+00, 4.1041e-03, 
 2DIAGNOSTIC,   831, -8.780597448349e-01, 3.832851191987e-08, 4.8152e+00, 4.0951e-03, 
 2DIAGNOSTIC,   832, -8.780597448349e-01, 3.828238348547e-08, 4.8195e+00, 4.3099e-03, 
 2DIAGNOSTIC,   833, -8.780597448349e-01, 3.823636873790e-08, 4.8243e+00, 4.7469e-03, 
 2DIAGNOSTIC,   834, -8.780597448349e-01, 3.819046057174e-08, 4.8290e+00, 4.7078e-03, 
 2DIAGNOSTIC,   835, -8.780597448349e-01, 3.814466609242e-08, 4.8337e+00, 4.7030e-03, 
 2DIAGNOSTIC,   836, -8.780597448349e-01, 3.809898174723e-08, 4.8383e+00, 4.6282e-03, 
 2DIAGNOSTIC,   837, -8.780597448349e-01, 3.805340398344e-08, 4.8430e+00, 4.6961e-03, 
 2DIAGNOSTIC,   838, -8.780597448349e-01, 3.800793635378e-08, 4.8472e+00, 4.1571e-03, 
 2DIAGNOSTIC,   839, -8.780597448349e-01, 3.796257530553e-08, 4.8514e+00, 4.2949e-03, 
 2DIAGNOSTIC,   840, -8.780597448349e-01, 3.791732439140e-08, 4.8558e+00, 4.3061e-03, 
 2DIAGNOSTIC,   841, -8.780597448349e-01, 3.787218005868e-08, 4.8598e+00, 4.0801e-03, 
 2DIAGNOSTIC,   842, -8.780597448349e-01, 3.782714586009e-08, 4.8639e+00, 4.0948e-03, 
 2DIAGNOSTIC,   843, -8.780597448349e-01, 3.778221469020e-08, 4.8694e+00, 5.4982e-03, 
 2DIAGNOSTIC,   844, -8.780597448349e-01, 3.773739365442e-08, 4.8756e+00, 6.2001e-03, 
 2DIAGNOSTIC,   845, -8.780597448349e-01, 3.769267564735e-08, 4.8794e+00, 3.8149e-03, 
 2DIAGNOSTIC,   846, -8.780597448349e-01, 3.764806777440e-08, 4.8832e+00, 3.7489e-03, 
 2DIAGNOSTIC,   847, -8.780597448349e-01, 3.760356293014e-08, 4.8876e+00, 4.3731e-03, 
 2DIAGNOSTIC,   848, -8.780597448349e-01, 3.755916111459e-08, 4.8915e+00, 3.9029e-03, 
 2DIAGNOSTIC,   849, -8.780597448349e-01, 3.751486588044e-08, 4.8954e+00, 3.9158e-03, 
 2DIAGNOSTIC,   850, -8.780597448349e-01, 3.747067367499e-08, 4.8991e+00, 3.7332e-03, 
 2DIAGNOSTIC,   851, -8.780597448349e-01, 3.742658805095e-08, 4.9029e+00, 3.7620e-03, 
 2DIAGNOSTIC,   852, -8.780597448349e-01, 3.738260545560e-08, 4.9066e+00, 3.7501e-03, 
 2DIAGNOSTIC,   853, -8.780597448349e-01, 3.733872588896e-08, 4.9103e+00, 3.7119e-03, 
 2DIAGNOSTIC,   854, -8.780597448349e-01, 3.729494935101e-08, 4.9141e+00, 3.7560e-03, 
 2DIAGNOSTIC,   855, -8.780597448349e-01, 3.725127228904e-08, 4.9179e+00, 3.8002e-03, 
 2DIAGNOSTIC,   856, -8.780597448349e-01, 3.720770180848e-08, 4.9217e+00, 3.8221e-03, 
 2DIAGNOSTIC,   857, -8.780597448349e-01, 3.716423080391e-08, 4.9253e+00, 3.5582e-03, 
 2DIAGNOSTIC,   858, -8.780597448349e-01, 3.712086282803e-08, 4.9288e+00, 3.5689e-03, 
 2DIAGNOSTIC,   859, -8.780597448349e-01, 3.707759432814e-08, 4.9325e+00, 3.6900e-03, 
 2DIAGNOSTIC,   860, -8.780597448349e-01, 3.703442530423e-08, 4.9363e+00, 3.7260e-03, 
 2DIAGNOSTIC,   861, -8.780597448349e-01, 3.699135930901e-08, 4.9400e+00, 3.7451e-03, 
 2DIAGNOSTIC,   862, -8.780597448349e-01, 3.694839278978e-08, 4.9439e+00, 3.8950e-03, 
 2DIAGNOSTIC,   863, -8.780597448349e-01, 3.690552574653e-08, 4.9476e+00, 3.7429e-03, 
 2DIAGNOSTIC,   864, -8.780597448349e-01, 3.686275817927e-08, 4.9512e+00, 3.5880e-03, 
 2DIAGNOSTIC,   865, -8.780597448349e-01, 3.682009008799e-08, 4.9549e+00, 3.6440e-03, 
 2DIAGNOSTIC,   866, -8.780597448349e-01, 3.677751791997e-08, 4.9584e+00, 3.4869e-03, 
 2DIAGNOSTIC,   867, -8.780597448349e-01, 3.673504878066e-08, 4.9620e+00, 3.6860e-03, 
 2DIAGNOSTIC,   868, -8.780597448349e-01, 3.669267201190e-08, 4.9654e+00, 3.3891e-03, 
 2DIAGNOSTIC,   869, -8.780597448349e-01, 3.665039827183e-08, 4.9690e+00, 3.5729e-03, 
 2DIAGNOSTIC,   870, -8.780597448349e-01, 3.660821690232e-08, 4.9725e+00, 3.5400e-03, 
 2DIAGNOSTIC,   871, -8.780597448349e-01, 3.656613500880e-08, 4.9761e+00, 3.5889e-03, 
 2DIAGNOSTIC,   872, -8.780597448349e-01, 3.652415259126e-08, 4.9800e+00, 3.8290e-03, 
 2DIAGNOSTIC,   873, -8.780597448349e-01, 3.648226254427e-08, 4.9837e+00, 3.7711e-03, 
 2DIAGNOSTIC,   874, -8.780597448349e-01, 3.644046842055e-08, 4.9873e+00, 3.5369e-03, 
 2DIAGNOSTIC,   875, -8.780597448349e-01, 3.639877022010e-08, 4.9911e+00, 3.8190e-03, 
 2DIAGNOSTIC,   876, -8.780597448349e-01, 3.635717149564e-08, 4.9951e+00, 3.9649e-03, 
 2DIAGNOSTIC,   877, -8.780597448349e-01, 3.631566158901e-08, 4.9989e+00, 3.8249e-03, 
 2DIAGNOSTIC,   878, -8.780597448349e-01, 3.627425115837e-08, 5.0026e+00, 3.7479e-03, 
 2DIAGNOSTIC,   879, -8.780597448349e-01, 3.623293309829e-08, 5.0065e+00, 3.8571e-03, 
 2DIAGNOSTIC,   880, -8.780597448349e-01, 3.619170740876e-08, 5.0102e+00, 3.6869e-03, 
 2DIAGNOSTIC,   881, -8.780597448349e-01, 3.615057764250e-08, 5.0135e+00, 3.3710e-03, 
 2DIAGNOSTIC,   882, -8.780597448349e-01, 3.610954024680e-08, 5.0170e+00, 3.4621e-03, 
 2DIAGNOSTIC,   883, -8.780597448349e-01, 3.606859877436e-08, 5.0208e+00, 3.7670e-03, 
 2DIAGNOSTIC,   884, -8.780597448349e-01, 3.602774611977e-08, 5.0247e+00, 3.8910e-03, 
 2DIAGNOSTIC,   885, -8.780597448349e-01, 3.598698938845e-08, 5.0284e+00, 3.7479e-03, 
 2DIAGNOSTIC,   886, -8.780597448349e-01, 3.594632147497e-08, 5.0320e+00, 3.5472e-03, 
 2DIAGNOSTIC,   887, -8.780597448349e-01, 3.590574593204e-08, 5.0355e+00, 3.5181e-03, 
 2DIAGNOSTIC,   888, -8.780597448349e-01, 3.586526275967e-08, 5.0392e+00, 3.7520e-03, 
 2DIAGNOSTIC,   889, -8.780597448349e-01, 3.582487195786e-08, 5.0428e+00, 3.5830e-03, 
 2DIAGNOSTIC,   890, -8.780597448349e-01, 3.578456997388e-08, 5.0464e+00, 3.5479e-03, 
 2DIAGNOSTIC,   891, -8.780597448349e-01, 3.574436036047e-08, 5.0498e+00, 3.4480e-03, 
 2DIAGNOSTIC,   892, -8.780597448349e-01, 3.570423956489e-08, 5.0534e+00, 3.6199e-03, 
 2DIAGNOSTIC,   893, -8.780597448349e-01, 3.566420758716e-08, 5.0570e+00, 3.5381e-03, 
 2DIAGNOSTIC,   894, -8.780597448349e-01, 3.562426797998e-08, 5.0608e+00, 3.8490e-03, 
 2DIAGNOSTIC,   895, -8.780597448349e-01, 3.558441719065e-08, 5.0645e+00, 3.6819e-03, 
 2DIAGNOSTIC,   896, -8.780597448349e-01, 3.554465521916e-08, 5.0680e+00, 3.4702e-03, 
 2DIAGNOSTIC,   897, -8.780597448349e-01, 3.550498206550e-08, 5.0717e+00, 3.7119e-03, 
 2DIAGNOSTIC,   898, -8.780597448349e-01, 3.546539417698e-08, 5.0751e+00, 3.4239e-03, 
 2DIAGNOSTIC,   899, -8.780597448349e-01, 3.542589865901e-08, 5.0788e+00, 3.7172e-03, 
 2DIAGNOSTIC,   900, -8.780597448349e-01, 3.538648840617e-08, 5.0826e+00, 3.7370e-03, 
 2DIAGNOSTIC,   901, -8.780597448349e-01, 3.534716697118e-08, 5.0862e+00, 3.6690e-03, 
 2DIAGNOSTIC,   902, -8.780597448349e-01, 3.530793435402e-08, 5.0899e+00, 3.7088e-03, 
 2DIAGNOSTIC,   903, -8.780597448349e-01, 3.526878700200e-08, 5.0938e+00, 3.8779e-03, 
 2DIAGNOSTIC,   904, -8.780597448349e-01, 3.522972491510e-08, 5.0978e+00, 4.0021e-03, 
 2DIAGNOSTIC,   905, -8.780597448349e-01, 3.519075164604e-08, 5.1013e+00, 3.5169e-03, 
 2DIAGNOSTIC,   906, -8.780597448349e-01, 3.515186364211e-08, 5.1049e+00, 3.6061e-03, 
 2DIAGNOSTIC,   907, -8.780597448349e-01, 3.511306090331e-08, 5.1085e+00, 3.5641e-03, 
 2DIAGNOSTIC,   908, -8.780597448349e-01, 3.507434698236e-08, 5.1120e+00, 3.5441e-03, 
 2DIAGNOSTIC,   909, -8.780597448349e-01, 3.503571477381e-08, 5.1156e+00, 3.5241e-03, 
 2DIAGNOSTIC,   910, -8.780597448349e-01, 3.499716783040e-08, 5.1190e+00, 3.4680e-03, 
 2DIAGNOSTIC,   911, -8.780597448349e-01, 3.495870615211e-08, 5.1225e+00, 3.4680e-03, 
 2DIAGNOSTIC,   912, -8.780597448349e-01, 3.492032973895e-08, 5.1262e+00, 3.6962e-03, 
 2DIAGNOSTIC,   913, -8.780597448349e-01, 3.488203859092e-08, 5.1298e+00, 3.6099e-03, 
 2DIAGNOSTIC,   914, -8.780597448349e-01, 3.484382915531e-08, 5.1334e+00, 3.5961e-03, 
 2DIAGNOSTIC,   915, -8.780597448349e-01, 3.480570143211e-08, 5.1370e+00, 3.6330e-03, 
 2DIAGNOSTIC,   916, -8.780597448349e-01, 3.476766252675e-08, 5.1405e+00, 3.4809e-03, 
 2DIAGNOSTIC,   917, -8.780597448349e-01, 3.472970178109e-08, 5.1440e+00, 3.4871e-03, 
 2DIAGNOSTIC,   918, -8.780597448349e-01, 3.469182630056e-08, 5.1478e+00, 3.7911e-03, 
 2DIAGNOSTIC,   919, -8.780597448349e-01, 3.465403253244e-08, 5.1513e+00, 3.4750e-03, 
 2DIAGNOSTIC,   920, -8.780597448349e-01, 3.461632047674e-08, 5.1546e+00, 3.3472e-03, 
 2DIAGNOSTIC,   921, -8.780597448349e-01, 3.457869013346e-08, 5.1581e+00, 3.4990e-03, 
 2DIAGNOSTIC,   922, -8.780597448349e-01, 3.454114505530e-08, 5.1618e+00, 3.6280e-03, 
 2DIAGNOSTIC,   923, -8.780597448349e-01, 3.450367813684e-08, 5.1653e+00, 3.5291e-03, 
 2DIAGNOSTIC,   924, -8.780597448349e-01, 3.446629293080e-08, 5.1687e+00, 3.4130e-03, 
 2DIAGNOSTIC,   925, -8.780597448349e-01, 3.442898943717e-08, 5.1721e+00, 3.4301e-03, 
 2DIAGNOSTIC,   926, -8.780597448349e-01, 3.439176410325e-08, 5.1756e+00, 3.5250e-03, 
 2DIAGNOSTIC,   927, -8.780597448349e-01, 3.435462403445e-08, 5.1792e+00, 3.5360e-03, 
 2DIAGNOSTIC,   928, -8.780597448349e-01, 3.431755857264e-08, 5.1828e+00, 3.5729e-03, 
 2DIAGNOSTIC,   929, -8.780597448349e-01, 3.428057837596e-08, 5.1863e+00, 3.5350e-03, 
 2DIAGNOSTIC,   930, -8.780597448349e-01, 3.424367278626e-08, 5.1898e+00, 3.5079e-03, 
 2DIAGNOSTIC,   931, -8.780597448349e-01, 3.420684890898e-08, 5.1937e+00, 3.8841e-03, 
 2DIAGNOSTIC,   932, -8.780597448349e-01, 3.417010319140e-08, 5.1972e+00, 3.5172e-03, 
 2DIAGNOSTIC,   933, -8.780597448349e-01, 3.413343918623e-08, 5.2009e+00, 3.6509e-03, 
 2DIAGNOSTIC,   934, -8.780597448349e-01, 3.409684978806e-08, 5.2046e+00, 3.7570e-03, 
 2DIAGNOSTIC,   935, -8.780597448349e-01, 3.406034210229e-08, 5.2083e+00, 3.6831e-03, 
 2DIAGNOSTIC,   936, -8.780597448349e-01, 3.402391257623e-08, 5.2118e+00, 3.5429e-03, 
 2DIAGNOSTIC,   937, -8.780597448349e-01, 3.398755765716e-08, 5.2156e+00, 3.7529e-03, 
 2DIAGNOSTIC,   938, -8.780597448349e-01, 3.395128089778e-08, 5.2191e+00, 3.5391e-03, 
 2DIAGNOSTIC,   939, -8.780597448349e-01, 3.391508585082e-08, 5.2226e+00, 3.5150e-03, 
 2DIAGNOSTIC,   940, -8.780597448349e-01, 3.387896185814e-08, 5.2263e+00, 3.6840e-03, 
 2DIAGNOSTIC,   941, -8.780597448349e-01, 3.384291957786e-08, 5.2299e+00, 3.5732e-03, 
 2DIAGNOSTIC,   942, -8.780597448349e-01, 3.380695190458e-08, 5.2335e+00, 3.6492e-03, 
 2DIAGNOSTIC,   943, -8.780597448349e-01, 3.377105883828e-08, 5.2371e+00, 3.5300e-03, 
 2DIAGNOSTIC,   944, -8.780597448349e-01, 3.373524393169e-08, 5.2407e+00, 3.6311e-03, 
 2DIAGNOSTIC,   945, -8.780597448349e-01, 3.369950718479e-08, 5.2442e+00, 3.5081e-03, 
 2DIAGNOSTIC,   946, -8.780597448349e-01, 3.366384149217e-08, 5.2477e+00, 3.4561e-03, 
 2DIAGNOSTIC,   947, -8.780597448349e-01, 3.362825395925e-08, 5.2509e+00, 3.2690e-03, 
 2DIAGNOSTIC,   948, -8.780597448349e-01, 3.359274103332e-08, 5.2545e+00, 3.5579e-03, 
 2DIAGNOSTIC,   949, -8.780597448349e-01, 3.355730271437e-08, 5.2581e+00, 3.6161e-03, 
 2DIAGNOSTIC,   950, -8.780597448349e-01, 3.352193900241e-08, 5.2616e+00, 3.4959e-03, 
 2DIAGNOSTIC,   951, -8.780597448349e-01, 3.348664989744e-08, 5.2650e+00, 3.4268e-03, 
 2DIAGNOSTIC,   952, -8.780597448349e-01, 3.345143539946e-08, 5.2685e+00, 3.4161e-03, 
 2DIAGNOSTIC,   953, -8.780597448349e-01, 3.341629550846e-08, 5.2722e+00, 3.7699e-03, 
 2DIAGNOSTIC,   954, -8.780597448349e-01, 3.338123022445e-08, 5.2759e+00, 3.6490e-03, 
 2DIAGNOSTIC,   955, -8.780597448349e-01, 3.334623599471e-08, 5.2795e+00, 3.6221e-03, 
 2DIAGNOSTIC,   956, -8.780597448349e-01, 3.331131637196e-08, 5.2827e+00, 3.2420e-03, 
 2DIAGNOSTIC,   957, -8.780597448349e-01, 3.327646780349e-08, 5.2865e+00, 3.7692e-03, 
 2DIAGNOSTIC,   958, -8.780597448349e-01, 3.324169384200e-08, 5.2903e+00, 3.7961e-03, 
 2DIAGNOSTIC,   959, -8.780597448349e-01, 3.320699093479e-08, 5.2938e+00, 3.5379e-03, 
 2DIAGNOSTIC,   960, -8.780597448349e-01, 3.317236263456e-08, 5.2975e+00, 3.6650e-03, 
 2DIAGNOSTIC,   961, -8.780597448349e-01, 3.313780538861e-08, 5.3008e+00, 3.3200e-03, 
 2DIAGNOSTIC,   962, -8.780597448349e-01, 3.310331919693e-08, 5.3043e+00, 3.4480e-03, 
 2DIAGNOSTIC,   963, -8.780597448349e-01, 3.306890761223e-08, 5.3077e+00, 3.3748e-03, 
 2DIAGNOSTIC,   964, -8.780597448349e-01, 3.303456352910e-08, 5.3112e+00, 3.5071e-03, 
 2DIAGNOSTIC,   965, -8.780597448349e-01, 3.300029405295e-08, 5.3147e+00, 3.5219e-03, 
 2DIAGNOSTIC,   966, -8.780597448349e-01, 3.296609563108e-08, 5.3182e+00, 3.5539e-03, 
 2DIAGNOSTIC,   967, -8.780597448349e-01, 3.293196471077e-08, 5.3216e+00, 3.3281e-03, 
 2DIAGNOSTIC,   968, -8.780597448349e-01, 3.289790839744e-08, 5.3252e+00, 3.6440e-03, 
 2DIAGNOSTIC,   969, -8.780597448349e-01, 3.286391958568e-08, 5.3287e+00, 3.4759e-03, 
 2DIAGNOSTIC,   970, -8.780597448349e-01, 3.283000182819e-08, 5.3322e+00, 3.4881e-03, 
 2DIAGNOSTIC,   971, -8.780597448349e-01, 3.279615512497e-08, 5.3355e+00, 3.3431e-03, 
 2DIAGNOSTIC,   972, -8.780597448349e-01, 3.276237592331e-08, 5.3390e+00, 3.4399e-03, 
 2DIAGNOSTIC,   973, -8.780597448349e-01, 3.272866777593e-08, 5.3422e+00, 3.2921e-03, 
 2DIAGNOSTIC,   974, -8.780597448349e-01, 3.269502713010e-08, 5.3458e+00, 3.5710e-03, 
 2DIAGNOSTIC,   975, -8.780597448349e-01, 3.266145753855e-08, 5.3495e+00, 3.6802e-03, 
 2DIAGNOSTIC,   976, -8.780597448349e-01, 3.262795544856e-08, 5.3531e+00, 3.5541e-03, 
 2DIAGNOSTIC,   977, -8.780597448349e-01, 3.259452441284e-08, 5.3564e+00, 3.3569e-03, 
 2DIAGNOSTIC,   978, -8.780597448349e-01, 3.256115732597e-08, 5.3599e+00, 3.5090e-03, 
 2DIAGNOSTIC,   979, -8.780597448349e-01, 3.252786129337e-08, 5.3635e+00, 3.5582e-03, 
 2DIAGNOSTIC,   980, -8.780597448349e-01, 3.249463631505e-08, 5.3669e+00, 3.3920e-03, 
 2DIAGNOSTIC,   981, -8.780597448349e-01, 3.246147528557e-08, 5.3704e+00, 3.5691e-03, 
 2DIAGNOSTIC,   982, -8.780597448349e-01, 3.242838175765e-08, 5.3739e+00, 3.4521e-03, 
 2DIAGNOSTIC,   983, -8.780597448349e-01, 3.239535573130e-08, 5.3773e+00, 3.3779e-03, 
 2DIAGNOSTIC,   984, -8.780597448349e-01, 3.236239720650e-08, 5.3808e+00, 3.5570e-03, 
 2DIAGNOSTIC,   985, -8.780597448349e-01, 3.232950618326e-08, 5.3845e+00, 3.6371e-03, 
 2DIAGNOSTIC,   986, -8.780597448349e-01, 3.229668266158e-08, 5.3881e+00, 3.6170e-03, 
 2DIAGNOSTIC,   987, -8.780597448349e-01, 3.226392664146e-08, 5.3916e+00, 3.5250e-03, 
 2DIAGNOSTIC,   988, -8.780597448349e-01, 3.223123457019e-08, 5.3960e+00, 4.3931e-03, 
 2DIAGNOSTIC,   989, -8.780597448349e-01, 3.219861000048e-08, 5.4006e+00, 4.5719e-03, 
 2DIAGNOSTIC,   990, -8.780597448349e-01, 3.216604937961e-08, 5.4055e+00, 4.9150e-03, 
 2DIAGNOSTIC,   991, -8.780597448349e-01, 3.213355626031e-08, 5.4100e+00, 4.4711e-03, 
 2DIAGNOSTIC,   992, -8.780597448349e-01, 3.210113064256e-08, 5.4144e+00, 4.4858e-03, 
 2DIAGNOSTIC,   993, -8.780597448349e-01, 3.206876542095e-08, 5.4186e+00, 4.2112e-03, 
 2DIAGNOSTIC,   994, -8.780597448349e-01, 3.203647125360e-08, 5.4229e+00, 4.2670e-03, 
 2DIAGNOSTIC,   995, -8.780597448349e-01, 3.200423748240e-08, 5.4270e+00, 4.1120e-03, 
 2DIAGNOSTIC,   996, -8.780597448349e-01, 3.197207121275e-08, 5.4313e+00, 4.2288e-03, 
 2DIAGNOSTIC,   997, -8.780597448349e-01, 3.193996889195e-08, 5.4355e+00, 4.2372e-03, 
 2DIAGNOSTIC,   998, -8.780597448349e-01, 3.190793051999e-08, 5.4397e+00, 4.1740e-03, 
 2DIAGNOSTIC,   999, -8.780597448349e-01, 3.187595609688e-08, 5.4439e+00, 4.2498e-03, 
 2DIAGNOSTIC,  1000, -8.780597448349e-01, 3.184404562262e-08, 5.4480e+00, 4.1151e-03, 
DIAGNOSTIC,Iteration,metricValue,convergenceValue,ITERATION_TIME_INDEX,SINCE_LAST
 2DIAGNOSTIC,     1, -6.721085309982e-01, inf, 5.8321e+00, 3.8405e-01, 
 2DIAGNOSTIC,     2, -6.734731793404e-01, inf, 5.8474e+00, 1.5366e-02, 
 2DIAGNOSTIC,     3, -6.750124692917e-01, inf, 5.8602e+00, 1.2782e-02, 
 2DIAGNOSTIC,     4, -6.763466000557e-01, inf, 5.8698e+00, 9.6040e-03, 
 2DIAGNOSTIC,     5, -6.770649552345e-01, inf, 5.8896e+00, 1.9751e-02, 
 2DIAGNOSTIC,     6, -6.772565245628e-01, inf, 5.8994e+00, 9.7871e-03, 
 2DIAGNOSTIC,     7, -6.774200797081e-01, inf, 5.9105e+00, 1.1114e-02, 
 2DIAGNOSTIC,     8, -6.775614023209e-01, inf, 5.9178e+00, 7.2920e-03, 
 2DIAGNOSTIC,     9, -6.784912347794e-01, inf, 5.9248e+00, 7.0229e-03, 
 2DIAGNOSTIC,    10, -6.792746186256e-01, 5.860645906068e-04, 5.9340e+00, 9.1579e-03, 
 2DIAGNOSTIC,    11, -6.795809268951e-01, 4.456409078557e-04, 5.9425e+00, 8.5199e-03, 
 2DIAGNOSTIC,    12, -6.798282861710e-01, 3.452603414189e-04, 5.9497e+00, 7.2660e-03, 
 2DIAGNOSTIC,    13, -6.800864338875e-01, 2.867191797122e-04, 5.9585e+00, 8.7259e-03, 
 2DIAGNOSTIC,    14, -6.803640127182e-01, 2.580308937468e-04, 5.9706e+00, 1.2163e-02, 
 2DIAGNOSTIC,    15, -6.804191470146e-01, 2.309126139153e-04, 5.9811e+00, 1.0453e-02, 
 2DIAGNOSTIC,    16, -6.806586980820e-01, 1.977553765755e-04, 5.9903e+00, 9.2180e-03, 
 2DIAGNOSTIC,    17, -6.808190345764e-01, 1.587768492755e-04, 5.9990e+00, 8.6889e-03, 
 2DIAGNOSTIC,    18, -6.808567643166e-01, 1.133731493610e-04, 6.0075e+00, 8.5361e-03, 
 2DIAGNOSTIC,    19, -6.809778809547e-01, 8.525401062798e-05, 6.0162e+00, 8.6288e-03, 
 2DIAGNOSTIC,    20, -6.811308264732e-01, 7.170260505518e-05, 6.0257e+00, 9.4960e-03, 
 2DIAGNOSTIC,    21, -6.812602877617e-01, 6.147594103822e-05, 6.0375e+00, 1.1865e-02, 
 2DIAGNOSTIC,    22, -6.813882589340e-01, 5.359996066545e-05, 6.0465e+00, 8.9729e-03, 
 2DIAGNOSTIC,    23, -6.814721822739e-01, 4.767436257680e-05, 6.0568e+00, 1.0303e-02, 
 2DIAGNOSTIC,    24, -6.815860271454e-01, 4.477530092117e-05, 6.0651e+00, 8.3451e-03, 
 2DIAGNOSTIC,    25, -6.820691227913e-01, 4.690537753049e-05, 6.0734e+00, 8.2300e-03, 
 2DIAGNOSTIC,    26, -6.821027994156e-01, 4.871228884440e-05, 6.0807e+00, 7.3631e-03, 
 2DIAGNOSTIC,    27, -6.821140646935e-01, 4.867463940172e-05, 6.0888e+00, 8.0659e-03, 
 2DIAGNOSTIC,    28, -6.821190118790e-01, 4.488979175221e-05, 6.0969e+00, 8.1029e-03, 
 2DIAGNOSTIC,    29, -6.821243762970e-01, 3.899872535840e-05, 6.1050e+00, 8.1000e-03, 
 2DIAGNOSTIC,    30, -6.821268200874e-01, 3.195395038347e-05, 6.1121e+00, 7.0832e-03, 
 2DIAGNOSTIC,    31, -6.821303963661e-01, 2.419372867735e-05, 6.1263e+00, 1.4234e-02, 
 2DIAGNOSTIC,    32, -6.821303963661e-01, 1.648288161959e-05, 6.1364e+00, 1.0101e-02, 
 2DIAGNOSTIC,    33, -6.821309924126e-01, 8.881687790563e-06, 6.1437e+00, 7.2970e-03, 
 2DIAGNOSTIC,    34, -6.821318268776e-01, 2.223751380370e-06, 6.1510e+00, 7.3121e-03, 
 2DIAGNOSTIC,    35, -6.821319460869e-01, 1.586273583598e-06, 6.1609e+00, 9.8360e-03, 
 2DIAGNOSTIC,    36, -6.821328401566e-01, 1.318890326729e-06, 6.1700e+00, 9.1450e-03, 
 2DIAGNOSTIC,    37, -6.821328401566e-01, 1.151371293417e-06, 6.1801e+00, 1.0087e-02, 
 2DIAGNOSTIC,    38, -6.821347475052e-01, 1.039818585014e-06, 6.1883e+00, 8.2002e-03, 
 2DIAGNOSTIC,    39, -6.821354627609e-01, 9.791639286050e-07, 6.1962e+00, 7.9188e-03, 
 2DIAGNOSTIC,    40, -6.821376085281e-01, 9.530896249998e-07, 6.2041e+00, 7.8862e-03, 
 2DIAGNOSTIC,    41, -6.821381449699e-01, 9.551860102874e-07, 6.2118e+00, 7.7450e-03, 
 2DIAGNOSTIC,    42, -6.821384429932e-01, 9.432933438802e-07, 6.2191e+00, 7.2658e-03, 
 2DIAGNOSTIC,    43, -6.821393370628e-01, 9.287695093008e-07, 6.2278e+00, 8.6560e-03, 
 2DIAGNOSTIC,    44, -6.821394562721e-01, 9.057663419298e-07, 6.2355e+00, 7.6931e-03, 
 2DIAGNOSTIC,    45, -6.821390986443e-01, 8.640544137961e-07, 6.2452e+00, 9.7110e-03, 
 2DIAGNOSTIC,    46, -6.821394562721e-01, 8.210449777835e-07, 6.2529e+00, 7.7569e-03, 
 2DIAGNOSTIC,    47, -6.821395158768e-01, 7.678608540118e-07, 6.2615e+00, 8.5540e-03, 
 2DIAGNOSTIC,    48, -6.821388006210e-01, 7.186558832473e-07, 6.2694e+00, 7.8921e-03, 
 2DIAGNOSTIC,    49, -6.821384429932e-01, 6.690690952382e-07, 6.2773e+00, 7.8750e-03, 
 2DIAGNOSTIC,    50, -6.821383237839e-01, 6.367137075358e-07, 6.2857e+00, 8.4820e-03, 
 2DIAGNOSTIC,    51, -6.821383237839e-01, 6.100022460487e-07, 6.2954e+00, 9.6450e-03, 
 2DIAGNOSTIC,    52, -6.821390390396e-01, 5.936090587966e-07, 6.3094e+00, 1.3980e-02, 
 2DIAGNOSTIC,    53, -6.821390986443e-01, 5.871282269254e-07, 6.3198e+00, 1.0435e-02, 
 2DIAGNOSTIC,    54, -6.821388602257e-01, 5.815876420456e-07, 6.3302e+00, 1.0398e-02, 
 2DIAGNOSTIC,    55, -6.821390390396e-01, 5.757392500527e-07, 6.3409e+00, 1.0678e-02, 
 2DIAGNOSTIC,    56, -6.821386814117e-01, 5.702771090910e-07, 6.3519e+00, 1.0985e-02, 
 2DIAGNOSTIC,    57, -6.821389794350e-01, 5.675977945430e-07, 6.3611e+00, 9.2850e-03, 
 2DIAGNOSTIC,    58, -6.821386218071e-01, 5.564516527556e-07, 6.3704e+00, 9.2971e-03, 
 2DIAGNOSTIC,    59, -6.821388006210e-01, 5.439374604066e-07, 6.3795e+00, 9.0461e-03, 
 2DIAGNOSTIC,    60, -6.821391582489e-01, 5.331687020771e-07, 6.3897e+00, 1.0204e-02, 
 2DIAGNOSTIC,    61, -6.821390986443e-01, 5.219249601396e-07, 6.4006e+00, 1.0942e-02, 
 2DIAGNOSTIC,    62, -6.821386814117e-01, 5.131341254128e-07, 6.4105e+00, 9.8860e-03, 
 2DIAGNOSTIC,    63, -6.821389794350e-01, 5.072374733572e-07, 6.4182e+00, 7.7300e-03, 
 2DIAGNOSTIC,    64, -6.821392774582e-01, 5.016340764996e-07, 6.4278e+00, 9.5222e-03, 
 2DIAGNOSTIC,    65, -6.821392774582e-01, 4.969273845745e-07, 6.4361e+00, 8.3499e-03, 
 2DIAGNOSTIC,    66, -6.821391582489e-01, 4.887020850219e-07, 6.4437e+00, 7.6170e-03, 
 2DIAGNOSTIC,    67, -6.821390986443e-01, 4.818421643904e-07, 6.4514e+00, 7.6239e-03, 
 2DIAGNOSTIC,    68, -6.821392178535e-01, 4.730798650598e-07, 6.4591e+00, 7.7260e-03, 
 2DIAGNOSTIC,    69, -6.821390986443e-01, 4.643165993912e-07, 6.4672e+00, 8.1499e-03, 
 2DIAGNOSTIC,    70, -6.821390390396e-01, 4.573635976612e-07, 6.4762e+00, 9.0020e-03, 
 2DIAGNOSTIC,    71, -6.821389198303e-01, 4.494897325458e-07, 6.4836e+00, 7.4110e-03, 
 2DIAGNOSTIC,    72, -6.821388006210e-01, 4.386351406538e-07, 6.4911e+00, 7.4520e-03, 
 2DIAGNOSTIC,    73, -6.821387410164e-01, 4.297521911667e-07, 6.4988e+00, 7.6661e-03, 
 2DIAGNOSTIC,    74, -6.821388602257e-01, 4.240936561928e-07, 6.5063e+00, 7.5169e-03, 
 2DIAGNOSTIC,    75, -6.821387410164e-01, 4.185460511508e-07, 6.5139e+00, 7.5901e-03, 
 2DIAGNOSTIC,    76, -6.821382641792e-01, 4.105158950551e-07, 6.5219e+00, 8.0550e-03, 
 2DIAGNOSTIC,    77, -6.821386218071e-01, 4.052050712744e-07, 6.5295e+00, 7.6060e-03, 
 2DIAGNOSTIC,    78, -6.821387410164e-01, 4.020421044970e-07, 6.5372e+00, 7.6599e-03, 
 2DIAGNOSTIC,    79, -6.821388602257e-01, 3.995222073172e-07, 6.5447e+00, 7.5009e-03, 
 2DIAGNOSTIC,    80, -6.821388006210e-01, 3.968451096625e-07, 6.5522e+00, 7.4680e-03, 
 2DIAGNOSTIC,    81, -6.821388006210e-01, 3.938367001410e-07, 6.5598e+00, 7.6041e-03, 
 2DIAGNOSTIC,    82, -6.821388602257e-01, 3.905316532382e-07, 6.5672e+00, 7.4720e-03, 
 2DIAGNOSTIC,    83, -6.821387410164e-01, 3.861113953008e-07, 6.5752e+00, 7.9281e-03, 
 2DIAGNOSTIC,    84, -6.821387410164e-01, 3.821895688816e-07, 6.5829e+00, 7.7808e-03, 
 2DIAGNOSTIC,    85, -6.821387410164e-01, 3.775843708809e-07, 6.5904e+00, 7.4630e-03, 
 2DIAGNOSTIC,    86, -6.821387410164e-01, 3.704547566485e-07, 6.5980e+00, 7.6182e-03, 
 2DIAGNOSTIC,    87, -6.821388006210e-01, 3.654649276541e-07, 6.6056e+00, 7.5982e-03, 
 2DIAGNOSTIC,    88, -6.821388602257e-01, 3.614792092321e-07, 6.6131e+00, 7.4570e-03, 
 2DIAGNOSTIC,    89, -6.821387410164e-01, 3.576379299375e-07, 6.6211e+00, 7.9989e-03, 
 2DIAGNOSTIC,    90, -6.821387410164e-01, 3.536462145348e-07, 6.6295e+00, 8.3721e-03, 
 2DIAGNOSTIC,    91, -6.821386814117e-01, 3.494749307720e-07, 6.6370e+00, 7.5779e-03, 
 2DIAGNOSTIC,    92, -6.821386218071e-01, 3.454535431047e-07, 6.6448e+00, 7.7519e-03, 
 2DIAGNOSTIC,    93, -6.821386218071e-01, 3.410557667394e-07, 6.6526e+00, 7.8149e-03, 
 2DIAGNOSTIC,    94, -6.821387410164e-01, 3.374211701157e-07, 6.6602e+00, 7.6330e-03, 
 2DIAGNOSTIC,    95, -6.821388006210e-01, 3.342505294768e-07, 6.6677e+00, 7.4580e-03, 
 2DIAGNOSTIC,    96, -6.821386814117e-01, 3.307152951493e-07, 6.6753e+00, 7.6432e-03, 
 2DIAGNOSTIC,    97, -6.821389794350e-01, 3.289083281288e-07, 6.6829e+00, 7.5691e-03, 
 2DIAGNOSTIC,    98, -6.821389198303e-01, 3.270525610333e-07, 6.6905e+00, 7.6330e-03, 
 2DIAGNOSTIC,    99, -6.821388006210e-01, 3.240253363401e-07, 6.6984e+00, 7.8721e-03, 
 2DIAGNOSTIC,   100, -6.821387410164e-01, 3.206144185697e-07, 6.7062e+00, 7.8011e-03, 
 2DIAGNOSTIC,   101, -6.821388006210e-01, 3.170773084094e-07, 6.7139e+00, 7.7138e-03, 
 2DIAGNOSTIC,   102, -6.821387410164e-01, 3.129244987576e-07, 6.7215e+00, 7.5591e-03, 
 2DIAGNOSTIC,   103, -6.821388602257e-01, 3.092541476235e-07, 6.7301e+00, 8.5859e-03, 
 2DIAGNOSTIC,   104, -6.821388006210e-01, 3.058897846131e-07, 6.7377e+00, 7.6041e-03, 
 2DIAGNOSTIC,   105, -6.821386814117e-01, 3.024201475910e-07, 6.7464e+00, 8.6970e-03, 
 2DIAGNOSTIC,   106, -6.821386218071e-01, 2.983675244650e-07, 6.7601e+00, 1.3732e-02, 
 2DIAGNOSTIC,   107, -6.821386814117e-01, 2.959788787393e-07, 6.7701e+00, 1.0035e-02, 
 2DIAGNOSTIC,   108, -6.821386814117e-01, 2.935530574177e-07, 6.7792e+00, 9.0380e-03, 
 2DIAGNOSTIC,   109, -6.821386814117e-01, 2.908493001996e-07, 6.7873e+00, 8.1370e-03, 
 2DIAGNOSTIC,   110, -6.821387410164e-01, 2.883307388402e-07, 6.7953e+00, 8.0080e-03, 
 2DIAGNOSTIC,   111, -6.821386814117e-01, 2.859752896711e-07, 6.8030e+00, 7.6790e-03, 
 2DIAGNOSTIC,   112, -6.821387410164e-01, 2.837319073024e-07, 6.8110e+00, 7.9961e-03, 
 2DIAGNOSTIC,   113, -6.821387410164e-01, 2.820149802574e-07, 6.8188e+00, 7.8249e-03, 
 2DIAGNOSTIC,   114, -6.821386814117e-01, 2.798815614824e-07, 6.8265e+00, 7.6680e-03, 
 2DIAGNOSTIC,   115, -6.821388006210e-01, 2.777456415970e-07, 6.8347e+00, 8.2078e-03, 
 2DIAGNOSTIC,   116, -6.821388006210e-01, 2.753293699698e-07, 6.8443e+00, 9.6078e-03, 
 2DIAGNOSTIC,   117, -6.821388006210e-01, 2.730879771207e-07, 6.8536e+00, 9.3229e-03, 
 2DIAGNOSTIC,   118, -6.821388006210e-01, 2.707988642214e-07, 6.8631e+00, 9.4399e-03, 
 2DIAGNOSTIC,   119, -6.821387410164e-01, 2.682426725187e-07, 6.8726e+00, 9.5139e-03, 
 2DIAGNOSTIC,   120, -6.821386814117e-01, 2.656715025751e-07, 6.8821e+00, 9.5570e-03, 
 2DIAGNOSTIC,   121, -6.821386814117e-01, 2.628972026741e-07, 6.8916e+00, 9.4209e-03, 
 2DIAGNOSTIC,   122, -6.821386814117e-01, 2.603939037726e-07, 6.9011e+00, 9.5189e-03, 
 2DIAGNOSTIC,   123, -6.821388006210e-01, 2.584004050732e-07, 6.9103e+00, 9.2211e-03, 
 2DIAGNOSTIC,   124, -6.821387410164e-01, 2.560634868587e-07, 6.9200e+00, 9.6791e-03, 
 2DIAGNOSTIC,   125, -6.821387410164e-01, 2.542444121900e-07, 6.9292e+00, 9.2380e-03, 
 2DIAGNOSTIC,   126, -6.821388602257e-01, 2.528954894387e-07, 6.9380e+00, 8.7810e-03, 
 2DIAGNOSTIC,   127, -6.821388006210e-01, 2.513304195872e-07, 6.9471e+00, 9.1341e-03, 
 2DIAGNOSTIC,   128, -6.821389198303e-01, 2.501241738173e-07, 6.9559e+00, 8.8122e-03, 
 2DIAGNOSTIC,   129, -6.821387410164e-01, 2.480313696651e-07, 6.9655e+00, 9.5479e-03, 
 2DIAGNOSTIC,   130, -6.821386218071e-01, 2.453015497395e-07, 6.9750e+00, 9.5129e-03, 
 2DIAGNOSTIC,   131, -6.821386814117e-01, 2.427706533581e-07, 6.9843e+00, 9.2630e-03, 
 2DIAGNOSTIC,   132, -6.821387410164e-01, 2.404600820682e-07, 6.9938e+00, 9.5141e-03, 
 2DIAGNOSTIC,   133, -6.821388602257e-01, 2.390015083620e-07, 7.0027e+00, 8.8909e-03, 
 2DIAGNOSTIC,   134, -6.821390986443e-01, 2.381629684578e-07, 7.0119e+00, 9.2251e-03, 
 2DIAGNOSTIC,   135, -6.821390390396e-01, 2.370841372112e-07, 7.0210e+00, 9.1219e-03, 
 2DIAGNOSTIC,   136, -6.821390986443e-01, 2.364656381815e-07, 7.0305e+00, 9.5170e-03, 
 2DIAGNOSTIC,   137, -6.821388006210e-01, 2.345135925452e-07, 7.0402e+00, 9.6400e-03, 
 2DIAGNOSTIC,   138, -6.821386814117e-01, 2.324124039887e-07, 7.0495e+00, 9.3241e-03, 
 2DIAGNOSTIC,   139, -6.821387410164e-01, 2.298221204455e-07, 7.0589e+00, 9.3849e-03, 
 2DIAGNOSTIC,   140, -6.821387410164e-01, 2.268159988716e-07, 7.0683e+00, 9.4340e-03, 
 2DIAGNOSTIC,   141, -6.821387410164e-01, 2.240933696385e-07, 7.0777e+00, 9.4080e-03, 
 2DIAGNOSTIC,   142, -6.821388006210e-01, 2.219371282308e-07, 7.0869e+00, 9.1801e-03, 
 2DIAGNOSTIC,   143, -6.821388602257e-01, 2.205357816365e-07, 7.0961e+00, 9.2330e-03, 
 2DIAGNOSTIC,   144, -6.821387410164e-01, 2.196903636786e-07, 7.1052e+00, 9.0520e-03, 
 2DIAGNOSTIC,   145, -6.821388006210e-01, 2.189843542055e-07, 7.1144e+00, 9.2430e-03, 
 2DIAGNOSTIC,   146, -6.821387410164e-01, 2.183592329175e-07, 7.1237e+00, 9.2719e-03, 
 2DIAGNOSTIC,   147, -6.821387410164e-01, 2.168763586496e-07, 7.1331e+00, 9.3648e-03, 
 2DIAGNOSTIC,   148, -6.821387410164e-01, 2.150406999135e-07, 7.1428e+00, 9.7001e-03, 
 2DIAGNOSTIC,   149, -6.821385025978e-01, 2.127391098838e-07, 7.1526e+00, 9.8290e-03, 
 2DIAGNOSTIC,   150, -6.821386218071e-01, 2.109109686899e-07, 7.1620e+00, 9.4149e-03, 
 2DIAGNOSTIC,   151, -6.821386218071e-01, 2.092115494179e-07, 7.1710e+00, 8.9810e-03, 
 2DIAGNOSTIC,   152, -6.821387410164e-01, 2.081691832245e-07, 7.1804e+00, 9.4240e-03, 
 2DIAGNOSTIC,   153, -6.821389794350e-01, 2.080823406914e-07, 7.1895e+00, 9.0570e-03, 
 2DIAGNOSTIC,   154, -6.821389794350e-01, 2.076604062040e-07, 7.1985e+00, 9.0280e-03, 
 2DIAGNOSTIC,   155, -6.821388602257e-01, 2.070057405490e-07, 7.2112e+00, 1.2695e-02, 
 2DIAGNOSTIC,   156, -6.821387410164e-01, 2.057298047475e-07, 7.2210e+00, 9.7651e-03, 
 2DIAGNOSTIC,   157, -6.821386218071e-01, 2.039860902414e-07, 7.2304e+00, 9.4080e-03, 
 2DIAGNOSTIC,   158, -6.821387410164e-01, 2.024696925673e-07, 7.2393e+00, 8.8789e-03, 
 2DIAGNOSTIC,   159, -6.821387410164e-01, 2.002274470669e-07, 7.2484e+00, 9.1631e-03, 
 2DIAGNOSTIC,   160, -6.821386814117e-01, 1.981853330335e-07, 7.2585e+00, 1.0075e-02, 
 2DIAGNOSTIC,   161, -6.821389198303e-01, 1.968761580429e-07, 7.2669e+00, 8.4400e-03, 
 2DIAGNOSTIC,   162, -6.821388602257e-01, 1.957813822173e-07, 7.2746e+00, 7.6389e-03, 
 2DIAGNOSTIC,   163, -6.821389794350e-01, 1.956807267334e-07, 7.2822e+00, 7.6699e-03, 
 2DIAGNOSTIC,   164, -6.821390390396e-01, 1.956935875569e-07, 7.2895e+00, 7.2341e-03, 
 2DIAGNOSTIC,   165, -6.821389794350e-01, 1.951062955641e-07, 7.2968e+00, 7.3459e-03, 
 2DIAGNOSTIC,   166, -6.821390986443e-01, 1.943276402017e-07, 7.3046e+00, 7.7670e-03, 
 2DIAGNOSTIC,   167, -6.821390986443e-01, 1.929910666831e-07, 7.3124e+00, 7.8409e-03, 
 2DIAGNOSTIC,   168, -6.821390986443e-01, 1.917385219485e-07, 7.3203e+00, 7.8831e-03, 
 2DIAGNOSTIC,   169, -6.821390390396e-01, 1.901441066821e-07, 7.3280e+00, 7.7009e-03, 
 2DIAGNOSTIC,   170, -6.821389794350e-01, 1.880929261233e-07, 7.3358e+00, 7.7660e-03, 
 2DIAGNOSTIC,   171, -6.821389198303e-01, 1.864270586793e-07, 7.3433e+00, 7.5541e-03, 
 2DIAGNOSTIC,   172, -6.821388602257e-01, 1.844543362495e-07, 7.3510e+00, 7.6239e-03, 
 2DIAGNOSTIC,   173, -6.821389794350e-01, 1.831376295058e-07, 7.3584e+00, 7.3979e-03, 
 2DIAGNOSTIC,   174, -6.821389794350e-01, 1.820602903990e-07, 7.3673e+00, 8.9750e-03, 
 2DIAGNOSTIC,   175, -6.821390390396e-01, 1.810767287225e-07, 7.3766e+00, 9.2442e-03, 
 2DIAGNOSTIC,   176, -6.821390986443e-01, 1.806085805356e-07, 7.3855e+00, 8.9571e-03, 
 2DIAGNOSTIC,   177, -6.821391582489e-01, 1.803055624805e-07, 7.3947e+00, 9.2099e-03, 
 2DIAGNOSTIC,   178, -6.821390390396e-01, 1.796765189965e-07, 7.4040e+00, 9.2361e-03, 
 2DIAGNOSTIC,   179, -6.821390986443e-01, 1.789816366227e-07, 7.4118e+00, 7.8452e-03, 
 2DIAGNOSTIC,   180, -6.821390390396e-01, 1.779044680461e-07, 7.4197e+00, 7.8940e-03, 
 2DIAGNOSTIC,   181, -6.821389794350e-01, 1.764653916325e-07, 7.4272e+00, 7.5369e-03, 
 2DIAGNOSTIC,   182, -6.821389198303e-01, 1.747068409941e-07, 7.4351e+00, 7.8762e-03, 
 2DIAGNOSTIC,   183, -6.821389198303e-01, 1.732641976560e-07, 7.4427e+00, 7.5510e-03, 
 2DIAGNOSTIC,   184, -6.821389794350e-01, 1.720326565646e-07, 7.4504e+00, 7.7460e-03, 
 2DIAGNOSTIC,   185, -6.821390390396e-01, 1.711654817882e-07, 7.4580e+00, 7.5948e-03, 
 2DIAGNOSTIC,   186, -6.821388602257e-01, 1.701227461126e-07, 7.4657e+00, 7.6840e-03, 
 2DIAGNOSTIC,   187, -6.821388006210e-01, 1.692136777365e-07, 7.4737e+00, 7.9501e-03, 
 2DIAGNOSTIC,   188, -6.821389794350e-01, 1.685369284132e-07, 7.4812e+00, 7.5660e-03, 
 2DIAGNOSTIC,   189, -6.821389198303e-01, 1.679199925775e-07, 7.4890e+00, 7.7701e-03, 
 2DIAGNOSTIC,   190, -6.821389794350e-01, 1.673642486821e-07, 7.4965e+00, 7.5021e-03, 
 2DIAGNOSTIC,   191, -6.821389198303e-01, 1.665828222031e-07, 7.5045e+00, 8.0009e-03, 
 2DIAGNOSTIC,   192, -6.821389198303e-01, 1.656949706330e-07, 7.5142e+00, 9.6712e-03, 
 2DIAGNOSTIC,   193, -6.821388602257e-01, 1.646818645895e-07, 7.5235e+00, 9.3400e-03, 
 2DIAGNOSTIC,   194, -6.821389198303e-01, 1.639494513483e-07, 7.5327e+00, 9.2170e-03, 
 2DIAGNOSTIC,   195, -6.821389198303e-01, 1.633724622252e-07, 7.5419e+00, 9.2189e-03, 
 2DIAGNOSTIC,   196, -6.821389198303e-01, 1.624137127010e-07, 7.5514e+00, 9.4619e-03, 
 2DIAGNOSTIC,   197, -6.821389198303e-01, 1.613288702629e-07, 7.5603e+00, 8.9281e-03, 
 2DIAGNOSTIC,   198, -6.821389198303e-01, 1.606591126802e-07, 7.5694e+00, 9.0721e-03, 
 2DIAGNOSTIC,   199, -6.821390390396e-01, 1.601228802883e-07, 7.5787e+00, 9.2509e-03, 
 2DIAGNOSTIC,   200, -6.821392178535e-01, 1.600650989531e-07, 7.5878e+00, 9.1369e-03, 
 2DIAGNOSTIC,   201, -6.821391582489e-01, 1.596634717771e-07, 7.5973e+00, 9.5150e-03, 
 2DIAGNOSTIC,   202, -6.821390390396e-01, 1.589087190723e-07, 7.6063e+00, 9.0199e-03, 
 2DIAGNOSTIC,   203, -6.821390986443e-01, 1.580374942023e-07, 7.6156e+00, 9.2461e-03, 
 2DIAGNOSTIC,   204, -6.821389198303e-01, 1.567955933979e-07, 7.6248e+00, 9.2521e-03, 
 2DIAGNOSTIC,   205, -6.821389794350e-01, 1.556125823754e-07, 7.6339e+00, 9.0530e-03, 
 2DIAGNOSTIC,   206, -6.821389198303e-01, 1.542854306535e-07, 7.6431e+00, 9.2309e-03, 
 2DIAGNOSTIC,   207, -6.821390390396e-01, 1.532440592200e-07, 7.6525e+00, 9.3980e-03, 
 2DIAGNOSTIC,   208, -6.821390390396e-01, 1.522518999764e-07, 7.6617e+00, 9.1970e-03, 
 2DIAGNOSTIC,   209, -6.821390390396e-01, 1.515718537348e-07, 7.6710e+00, 9.2590e-03, 
 2DIAGNOSTIC,   210, -6.821391582489e-01, 1.515652314765e-07, 7.6803e+00, 9.3210e-03, 
 2DIAGNOSTIC,   211, -6.821391582489e-01, 1.514364811328e-07, 7.6898e+00, 9.5260e-03, 
 2DIAGNOSTIC,   212, -6.821392178535e-01, 1.511271676691e-07, 7.6992e+00, 9.3811e-03, 
 2DIAGNOSTIC,   213, -6.821390986443e-01, 1.506158895381e-07, 7.7084e+00, 9.1810e-03, 
 2DIAGNOSTIC,   214, -6.821392178535e-01, 1.498832205016e-07, 7.7179e+00, 9.5220e-03, 
 2DIAGNOSTIC,   215, -6.821389794350e-01, 1.486924361416e-07, 7.7275e+00, 9.5799e-03, 
 2DIAGNOSTIC,   216, -6.821389794350e-01, 1.473375448313e-07, 7.7362e+00, 8.7521e-03, 
 2DIAGNOSTIC,   217, -6.821388602257e-01, 1.459967933215e-07, 7.7436e+00, 7.3950e-03, 
 2DIAGNOSTIC,   218, -6.821386218071e-01, 1.442820121156e-07, 7.7513e+00, 7.6840e-03, 
 2DIAGNOSTIC,   219, -6.821387410164e-01, 1.429806957276e-07, 7.7590e+00, 7.7422e-03, 
 2DIAGNOSTIC,   220, -6.821386814117e-01, 1.420213777692e-07, 7.7664e+00, 7.3421e-03, 
 2DIAGNOSTIC,   221, -6.821387410164e-01, 1.414394290578e-07, 7.7741e+00, 7.7450e-03, 
 2DIAGNOSTIC,   222, -6.821388006210e-01, 1.413432499930e-07, 7.7816e+00, 7.4382e-03, 
 2DIAGNOSTIC,   223, -6.821386218071e-01, 1.408794076951e-07, 7.7894e+00, 7.8220e-03, 
 2DIAGNOSTIC,   224, -6.821386218071e-01, 1.408406831160e-07, 7.7970e+00, 7.6001e-03, 
 2DIAGNOSTIC,   225, -6.821388006210e-01, 1.408011343074e-07, 7.8045e+00, 7.4699e-03, 
 2DIAGNOSTIC,   226, -6.821386814117e-01, 1.405930163401e-07, 7.8120e+00, 7.5121e-03, 
 2DIAGNOSTIC,   227, -6.821386218071e-01, 1.401033244974e-07, 7.8196e+00, 7.5822e-03, 
 2DIAGNOSTIC,   228, -6.821386218071e-01, 1.391967288100e-07, 7.8270e+00, 7.4761e-03, 
 2DIAGNOSTIC,   229, -6.821385622025e-01, 1.384458414577e-07, 7.8359e+00, 8.9159e-03, 
 2DIAGNOSTIC,   230, -6.821386814117e-01, 1.378507903382e-07, 7.8434e+00, 7.4511e-03, 
 2DIAGNOSTIC,   231, -6.821388602257e-01, 1.377302822902e-07, 7.8512e+00, 7.7600e-03, 
 2DIAGNOSTIC,   232, -6.821388602257e-01, 1.377307370376e-07, 7.8586e+00, 7.4759e-03, 
 2DIAGNOSTIC,   233, -6.821388006210e-01, 1.372594056193e-07, 7.8662e+00, 7.5619e-03, 
 2DIAGNOSTIC,   234, -6.821389794350e-01, 1.370411553125e-07, 7.8738e+00, 7.6380e-03, 
 2DIAGNOSTIC,   235, -6.821390390396e-01, 1.371369080516e-07, 7.8814e+00, 7.5350e-03, 
 2DIAGNOSTIC,   236, -6.821389794350e-01, 1.367436652799e-07, 7.8889e+00, 7.5459e-03, 
 2DIAGNOSTIC,   237, -6.821389794350e-01, 1.360754708912e-07, 7.8966e+00, 7.7171e-03, 
 2DIAGNOSTIC,   238, -6.821389198303e-01, 1.351455694021e-07, 7.9045e+00, 7.8700e-03, 
 2DIAGNOSTIC,   239, -6.821389198303e-01, 1.339743107565e-07, 7.9122e+00, 7.7360e-03, 
 2DIAGNOSTIC,   240, -6.821389794350e-01, 1.330296015567e-07, 7.9203e+00, 8.0779e-03, 
 2DIAGNOSTIC,   241, -6.821390390396e-01, 1.324641658584e-07, 7.9283e+00, 7.9920e-03, 
 2DIAGNOSTIC,   242, -6.821389198303e-01, 1.316654589800e-07, 7.9365e+00, 8.2228e-03, 
 2DIAGNOSTIC,   243, -6.821388006210e-01, 1.305524506279e-07, 7.9457e+00, 9.2161e-03, 
 2DIAGNOSTIC,   244, -6.821389794350e-01, 1.301006733456e-07, 7.9545e+00, 8.7969e-03, 
 2DIAGNOSTIC,   245, -6.821389794350e-01, 1.297706972991e-07, 7.9635e+00, 8.9161e-03, 
 2DIAGNOSTIC,   246, -6.821389794350e-01, 1.293524718449e-07, 7.9728e+00, 9.3000e-03, 
 2DIAGNOSTIC,   247, -6.821389794350e-01, 1.289523652304e-07, 7.9833e+00, 1.0492e-02, 
 2DIAGNOSTIC,   248, -6.821388006210e-01, 1.281500630057e-07, 7.9918e+00, 8.5919e-03, 
 2DIAGNOSTIC,   249, -6.821388006210e-01, 1.273705407812e-07, 7.9992e+00, 7.3900e-03, 
 2DIAGNOSTIC,   250, -6.821386814117e-01, 1.265273823492e-07, 8.0068e+00, 7.5250e-03, 
 2DIAGNOSTIC,   251, -6.821387410164e-01, 1.259728605874e-07, 8.0142e+00, 7.4141e-03, 
 2DIAGNOSTIC,   252, -6.821387410164e-01, 1.253102936971e-07, 8.0222e+00, 7.9911e-03, 
 2DIAGNOSTIC,   253, -6.821388006210e-01, 1.246443730452e-07, 8.0299e+00, 7.7031e-03, 
 2DIAGNOSTIC,   254, -6.821388006210e-01, 1.243891318836e-07, 8.0377e+00, 7.7889e-03, 
 2DIAGNOSTIC,   255, -6.821387410164e-01, 1.241257052698e-07, 8.0451e+00, 7.4861e-03, 
 2DIAGNOSTIC,   256, -6.821386218071e-01, 1.237359157358e-07, 8.0576e+00, 1.2483e-02, 
 2DIAGNOSTIC,   257, -6.821385025978e-01, 1.232207864632e-07, 8.0672e+00, 9.5642e-03, 
 2DIAGNOSTIC,   258, -6.821386218071e-01, 1.226717927238e-07, 8.0751e+00, 7.8809e-03, 
 2DIAGNOSTIC,   259, -6.821386218071e-01, 1.221886947178e-07, 8.0833e+00, 8.1980e-03, 
 2DIAGNOSTIC,   260, -6.821386218071e-01, 1.215851028746e-07, 8.0921e+00, 8.8601e-03, 
 2DIAGNOSTIC,   261, -6.821386218071e-01, 1.211691653680e-07, 8.1019e+00, 9.7470e-03, 
 2DIAGNOSTIC,   262, -6.821385622025e-01, 1.207346542742e-07, 8.1118e+00, 9.9390e-03, 
 2DIAGNOSTIC,   263, -6.821386814117e-01, 1.206539366194e-07, 8.1215e+00, 9.6531e-03, 
 2DIAGNOSTIC,   264, -6.821387410164e-01, 1.206920074992e-07, 8.1295e+00, 8.0440e-03, 
 2DIAGNOSTIC,   265, -6.821387410164e-01, 1.206258275488e-07, 8.1369e+00, 7.4019e-03, 
 2DIAGNOSTIC,   266, -6.821386218071e-01, 1.201463248890e-07, 8.1448e+00, 7.9350e-03, 
 2DIAGNOSTIC,   267, -6.821386814117e-01, 1.195300995960e-07, 8.1526e+00, 7.7469e-03, 
 2DIAGNOSTIC,   268, -6.821386814117e-01, 1.190626051084e-07, 8.1603e+00, 7.6580e-03, 
 2DIAGNOSTIC,   269, -6.821387410164e-01, 1.186542135656e-07, 8.1679e+00, 7.6551e-03, 
 2DIAGNOSTIC,   270, -6.821387410164e-01, 1.182156594837e-07, 8.1754e+00, 7.5262e-03, 
 2DIAGNOSTIC,   271, -6.821386218071e-01, 1.175728954195e-07, 8.1829e+00, 7.5030e-03, 
 2DIAGNOSTIC,   272, -6.821386814117e-01, 1.169225356534e-07, 8.1902e+00, 7.2482e-03, 
 2DIAGNOSTIC,   273, -6.821387410164e-01, 1.165461327446e-07, 8.1977e+00, 7.4739e-03, 
 2DIAGNOSTIC,   274, -6.821388602257e-01, 1.164399421327e-07, 8.2053e+00, 7.5951e-03, 
 2DIAGNOSTIC,   275, -6.821388006210e-01, 1.162191978210e-07, 8.2124e+00, 7.1192e-03, 
 2DIAGNOSTIC,   276, -6.821386814117e-01, 1.155991498081e-07, 8.2197e+00, 7.3729e-03, 
 2DIAGNOSTIC,   277, -6.821387410164e-01, 1.151407289512e-07, 8.2272e+00, 7.4451e-03, 
 2DIAGNOSTIC,   278, -6.821386814117e-01, 1.145570820427e-07, 8.2347e+00, 7.4639e-03, 
 2DIAGNOSTIC,   279, -6.821386814117e-01, 1.140552683410e-07, 8.2426e+00, 7.9122e-03, 
 2DIAGNOSTIC,   280, -6.821388006210e-01, 1.137444556321e-07, 8.2504e+00, 7.8769e-03, 
 2DIAGNOSTIC,   281, -6.821386218071e-01, 1.129827680302e-07, 8.2588e+00, 8.3132e-03, 
 2DIAGNOSTIC,   282, -6.821387410164e-01, 1.125239847966e-07, 8.2682e+00, 9.4202e-03, 
 2DIAGNOSTIC,   283, -6.821388602257e-01, 1.123500794620e-07, 8.2779e+00, 9.7530e-03, 
 2DIAGNOSTIC,   284, -6.821387410164e-01, 1.121812260862e-07, 8.2877e+00, 9.8081e-03, 
 2DIAGNOSTIC,   285, -6.821388602257e-01, 1.121006718563e-07, 8.2978e+00, 1.0013e-02, 
 2DIAGNOSTIC,   286, -6.821388602257e-01, 1.117991175192e-07, 8.3069e+00, 9.1510e-03, 
 2DIAGNOSTIC,   287, -6.821387410164e-01, 1.113632706051e-07, 8.3168e+00, 9.9151e-03, 
 2DIAGNOSTIC,   288, -6.821389198303e-01, 1.110585117203e-07, 8.3267e+00, 9.8939e-03, 
 2DIAGNOSTIC,   289, -6.821389198303e-01, 1.106878144697e-07, 8.3363e+00, 9.5930e-03, 
 2DIAGNOSTIC,   290, -6.821387410164e-01, 1.101881821342e-07, 8.3458e+00, 9.5000e-03, 
 2DIAGNOSTIC,   291, -6.821388602257e-01, 1.095680275398e-07, 8.3551e+00, 9.3241e-03, 
 2DIAGNOSTIC,   292, -6.821387410164e-01, 1.089211636440e-07, 8.3650e+00, 9.8851e-03, 
 2DIAGNOSTIC,   293, -6.821388006210e-01, 1.085448602112e-07, 8.3742e+00, 9.1860e-03, 
 2DIAGNOSTIC,   294, -6.821388602257e-01, 1.080834763911e-07, 8.3834e+00, 9.2230e-03, 
 2DIAGNOSTIC,   295, -6.821388602257e-01, 1.078103650798e-07, 8.3929e+00, 9.5220e-03, 
 2DIAGNOSTIC,   296, -6.821389794350e-01, 1.077218954038e-07, 8.4025e+00, 9.5630e-03, 
 2DIAGNOSTIC,   297, -6.821388006210e-01, 1.071820108223e-07, 8.4124e+00, 9.8491e-03, 
 2DIAGNOSTIC,   298, -6.821389198303e-01, 1.070667394742e-07, 8.4219e+00, 9.5539e-03, 
 2DIAGNOSTIC,   299, -6.821389198303e-01, 1.069244746077e-07, 8.4319e+00, 9.9690e-03, 
 2DIAGNOSTIC,   300, -6.821389198303e-01, 1.064779340254e-07, 8.4412e+00, 9.2959e-03, 
 2DIAGNOSTIC,   301, -6.821389794350e-01, 1.062504111360e-07, 8.4511e+00, 9.9311e-03, 
 2DIAGNOSTIC,   302, -6.821390390396e-01, 1.058896756945e-07, 8.4611e+00, 9.9649e-03, 
 2DIAGNOSTIC,   303, -6.821389198303e-01, 1.053958342823e-07, 8.4754e+00, 1.4327e-02, 
 2DIAGNOSTIC,   304, -6.821389198303e-01, 1.049549069876e-07, 8.4866e+00, 1.1173e-02, 
 2DIAGNOSTIC,   305, -6.821388006210e-01, 1.043209607587e-07, 8.4976e+00, 1.1076e-02, 
 2DIAGNOSTIC,   306, -6.821389794350e-01, 1.041075776698e-07, 8.5081e+00, 1.0451e-02, 
 2DIAGNOSTIC,   307, -6.821390390396e-01, 1.037079115918e-07, 8.5189e+00, 1.0766e-02, 
 2DIAGNOSTIC,   308, -6.821390986443e-01, 1.035492331880e-07, 8.5288e+00, 9.9182e-03, 
 2DIAGNOSTIC,   309, -6.821389198303e-01, 1.031338427993e-07, 8.5388e+00, 1.0021e-02, 
 2DIAGNOSTIC,   310, -6.821388602257e-01, 1.026332299148e-07, 8.5494e+00, 1.0579e-02, 
 2DIAGNOSTIC,   311, -6.821389794350e-01, 1.023698601443e-07, 8.5604e+00, 1.0998e-02, 
 2DIAGNOSTIC,   312, -6.821390986443e-01, 1.023322084848e-07, 8.5709e+00, 1.0568e-02, 
 2DIAGNOSTIC,   313, -6.821390390396e-01, 1.020208060254e-07, 8.5814e+00, 1.0435e-02, 
 2DIAGNOSTIC,   314, -6.821389794350e-01, 1.016171111701e-07, 8.5920e+00, 1.0620e-02, 
 2DIAGNOSTIC,   315, -6.821388602257e-01, 1.008746508546e-07, 8.6017e+00, 9.6910e-03, 
 2DIAGNOSTIC,   316, -6.821389794350e-01, 1.005383225561e-07, 8.6120e+00, 1.0351e-02, 
 2DIAGNOSTIC,   317, -6.821388602257e-01, 1.001246161536e-07, 8.6219e+00, 9.8851e-03, 
 2DIAGNOSTIC,   318, -6.821387410164e-01, 9.967369862807e-08, 8.6327e+00, 1.0789e-02, 
 2DIAGNOSTIC,   319, -6.821387410164e-01, 9.904427145102e-08, 8.6425e+00, 9.7690e-03, 
 2DIAGNOSTIC,   320, -6.821387410164e-01, 9.840432113606e-08, 8.6524e+00, 9.8982e-03, 
 2DIAGNOSTIC,   321, -6.821386814117e-01, 9.793625821430e-08, 8.6617e+00, 9.3169e-03, 
 2DIAGNOSTIC,   322, -6.821390986443e-01, 9.828554681235e-08, 8.6712e+00, 9.5029e-03, 
 2DIAGNOSTIC,   323, -6.821389794350e-01, 9.844408310755e-08, 8.6805e+00, 9.3381e-03, 
 2DIAGNOSTIC,   324, -6.821389198303e-01, 9.846935000724e-08, 8.6900e+00, 9.4430e-03, 
 2DIAGNOSTIC,   325, -6.821388006210e-01, 9.816434953791e-08, 8.6988e+00, 8.7800e-03, 
 2DIAGNOSTIC,   326, -6.821388006210e-01, 9.799166633684e-08, 8.7085e+00, 9.7172e-03, 
 2DIAGNOSTIC,   327, -6.821387410164e-01, 9.754812424490e-08, 8.7180e+00, 9.5382e-03, 
 2DIAGNOSTIC,   328, -6.821387410164e-01, 9.693205527128e-08, 8.7274e+00, 9.3329e-03, 
 2DIAGNOSTIC,   329, -6.821386814117e-01, 9.626151609154e-08, 8.7367e+00, 9.3751e-03, 
 2DIAGNOSTIC,   330, -6.821386814117e-01, 9.564955405494e-08, 8.7458e+00, 9.0950e-03, 
 2DIAGNOSTIC,   331, -6.821387410164e-01, 9.509891896187e-08, 8.7552e+00, 9.3760e-03, 
 2DIAGNOSTIC,   332, -6.821387410164e-01, 9.517530941139e-08, 8.7649e+00, 9.7239e-03, 
 2DIAGNOSTIC,   333, -6.821386814117e-01, 9.509461307289e-08, 8.7753e+00, 1.0371e-02, 
 2DIAGNOSTIC,   334, -6.821387410164e-01, 9.506720743957e-08, 8.7845e+00, 9.1732e-03, 
 2DIAGNOSTIC,   335, -6.821387410164e-01, 9.490766217368e-08, 8.7944e+00, 9.9039e-03, 
 2DIAGNOSTIC,   336, -6.821386218071e-01, 9.460830341368e-08, 8.8042e+00, 9.7930e-03, 
 2DIAGNOSTIC,   337, -6.821386814117e-01, 9.432459791014e-08, 8.8146e+00, 1.0392e-02, 
 2DIAGNOSTIC,   338, -6.821388602257e-01, 9.427306935095e-08, 8.8244e+00, 9.8391e-03, 
 2DIAGNOSTIC,   339, -6.821387410164e-01, 9.398151235018e-08, 8.8339e+00, 9.5291e-03, 
 2DIAGNOSTIC,   340, -6.821387410164e-01, 9.368539366506e-08, 8.8432e+00, 9.2449e-03, 
 2DIAGNOSTIC,   341, -6.821386218071e-01, 9.331314032579e-08, 8.8525e+00, 9.3262e-03, 
 2DIAGNOSTIC,   342, -6.821387410164e-01, 9.309177073646e-08, 8.8620e+00, 9.4771e-03, 
 2DIAGNOSTIC,   343, -6.821388602257e-01, 9.292556057972e-08, 8.8711e+00, 9.1450e-03, 
 2DIAGNOSTIC,   344, -6.821388602257e-01, 9.281376378567e-08, 8.8807e+00, 9.6090e-03, 
 2DIAGNOSTIC,   345, -6.821389794350e-01, 9.282981494607e-08, 8.8905e+00, 9.7802e-03, 
 2DIAGNOSTIC,   346, -6.821389794350e-01, 9.264226719097e-08, 8.9004e+00, 9.8739e-03, 
 2DIAGNOSTIC,   347, -6.821388602257e-01, 9.230970476892e-08, 8.9102e+00, 9.8610e-03, 
 2DIAGNOSTIC,   348, -6.821389198303e-01, 9.221047037045e-08, 8.9194e+00, 9.1882e-03, 
 2DIAGNOSTIC,   349, -6.821388602257e-01, 9.181865578967e-08, 8.9286e+00, 9.1381e-03, 
 2DIAGNOSTIC,   350, -6.821389198303e-01, 9.144360291202e-08, 8.9383e+00, 9.7749e-03, 
 2DIAGNOSTIC,   351, -6.821388602257e-01, 9.080272178608e-08, 8.9478e+00, 9.4361e-03, 
 2DIAGNOSTIC,   352, -6.821389794350e-01, 9.043552040566e-08, 8.9569e+00, 9.1131e-03, 
 2DIAGNOSTIC,   353, -6.821390986443e-01, 9.034582149070e-08, 8.9658e+00, 8.9312e-03, 
 2DIAGNOSTIC,   354, -6.821389794350e-01, 9.008728341087e-08, 8.9753e+00, 9.4640e-03, 
 2DIAGNOSTIC,   355, -6.821389794350e-01, 8.995741751505e-08, 8.9846e+00, 9.3191e-03, 
 2DIAGNOSTIC,   356, -6.821390986443e-01, 8.994097555615e-08, 8.9938e+00, 9.1951e-03, 
 2DIAGNOSTIC,   357, -6.821389794350e-01, 8.958122066360e-08, 9.0034e+00, 9.5780e-03, 
 2DIAGNOSTIC,   358, -6.821389794350e-01, 8.925401573379e-08, 9.0129e+00, 9.4900e-03, 
 2DIAGNOSTIC,   359, -6.821390390396e-01, 8.889424663039e-08, 9.0215e+00, 8.6269e-03, 
 2DIAGNOSTIC,   360, -6.821390390396e-01, 8.858185651661e-08, 9.0307e+00, 9.2168e-03, 
 2DIAGNOSTIC,   361, -6.821390986443e-01, 8.824684982756e-08, 9.0401e+00, 9.3651e-03, 
 2DIAGNOSTIC,   362, -6.821390986443e-01, 8.803625206610e-08, 9.0492e+00, 9.1221e-03, 
 2DIAGNOSTIC,   363, -6.821389794350e-01, 8.782078708691e-08, 9.0581e+00, 8.9338e-03, 
 2DIAGNOSTIC,   364, -6.821390390396e-01, 8.752565605619e-08, 9.0673e+00, 9.1820e-03, 
 2DIAGNOSTIC,   365, -6.821390390396e-01, 8.721190880578e-08, 9.0763e+00, 8.9381e-03, 
 2DIAGNOSTIC,   366, -6.821389794350e-01, 8.696685682708e-08, 9.0852e+00, 8.9431e-03, 
 2DIAGNOSTIC,   367, -6.821389794350e-01, 8.658918204674e-08, 9.0943e+00, 9.1169e-03, 
 2DIAGNOSTIC,   368, -6.821389794350e-01, 8.622496494581e-08, 9.1034e+00, 9.1081e-03, 
 2DIAGNOSTIC,   369, -6.821389198303e-01, 8.588538236154e-08, 9.1131e+00, 9.6850e-03, 
 2DIAGNOSTIC,   370, -6.821389794350e-01, 8.564641262865e-08, 9.1227e+00, 9.5949e-03, 
 2DIAGNOSTIC,   371, -6.821387410164e-01, 8.524014560862e-08, 9.1319e+00, 9.2130e-03, 
 2DIAGNOSTIC,   372, -6.821388602257e-01, 8.503327819653e-08, 9.1401e+00, 8.1868e-03, 
 2DIAGNOSTIC,   373, -6.821388006210e-01, 8.466813739005e-08, 9.1474e+00, 7.2980e-03, 
 2DIAGNOSTIC,   374, -6.821388006210e-01, 8.443294774452e-08, 9.1546e+00, 7.2281e-03, 
 2DIAGNOSTIC,   375, -6.821388006210e-01, 8.426543018913e-08, 9.1622e+00, 7.5762e-03, 
 2DIAGNOSTIC,   376, -6.821387410164e-01, 8.402545148556e-08, 9.1697e+00, 7.4821e-03, 
 2DIAGNOSTIC,   377, -6.821386814117e-01, 8.378065530223e-08, 9.1769e+00, 7.1712e-03, 
 2DIAGNOSTIC,   378, -6.821386814117e-01, 8.359783976175e-08, 9.1848e+00, 7.9391e-03, 
 2DIAGNOSTIC,   379, -6.821385622025e-01, 8.327148037779e-08, 9.1924e+00, 7.5629e-03, 
 2DIAGNOSTIC,   380, -6.821386814117e-01, 8.322068367761e-08, 9.1996e+00, 7.1890e-03, 
 2DIAGNOSTIC,   381, -6.821387410164e-01, 8.301626763796e-08, 9.2067e+00, 7.1321e-03, 
 2DIAGNOSTIC,   382, -6.821386814117e-01, 8.292743558513e-08, 9.2139e+00, 7.2029e-03, 
 2DIAGNOSTIC,   383, -6.821386814117e-01, 8.281465824211e-08, 9.2212e+00, 7.3571e-03, 
 2DIAGNOSTIC,   384, -6.821386218071e-01, 8.266371764876e-08, 9.2285e+00, 7.2372e-03, 
 2DIAGNOSTIC,   385, -6.821387410164e-01, 8.266194839734e-08, 9.2357e+00, 7.1990e-03, 
 2DIAGNOSTIC,   386, -6.821386814117e-01, 8.252403205233e-08, 9.2452e+00, 9.5561e-03, 
 2DIAGNOSTIC,   387, -6.821388602257e-01, 8.251005567672e-08, 9.2544e+00, 9.1341e-03, 
 2DIAGNOSTIC,   388, -6.821388006210e-01, 8.240642301871e-08, 9.2633e+00, 8.9128e-03, 
 2DIAGNOSTIC,   389, -6.821388006210e-01, 8.213650914968e-08, 9.2721e+00, 8.8551e-03, 
 2DIAGNOSTIC,   390, -6.821388006210e-01, 8.196035850006e-08, 9.2818e+00, 9.6190e-03, 
 2DIAGNOSTIC,   391, -6.821386814117e-01, 8.168483844884e-08, 9.2908e+00, 9.0489e-03, 
 2DIAGNOSTIC,   392, -6.821387410164e-01, 8.138306384353e-08, 9.3001e+00, 9.2471e-03, 
 2DIAGNOSTIC,   393, -6.821388006210e-01, 8.112468918853e-08, 9.3100e+00, 9.9001e-03, 
 2DIAGNOSTIC,   394, -6.821387410164e-01, 8.072175461393e-08, 9.3198e+00, 9.8560e-03, 
 2DIAGNOSTIC,   395, -6.821388006210e-01, 8.052026601035e-08, 9.3297e+00, 9.8689e-03, 
 2DIAGNOSTIC,   396, -6.821387410164e-01, 8.019187447417e-08, 9.3398e+00, 1.0118e-02, 
 2DIAGNOSTIC,   397, -6.821386814117e-01, 8.000831286381e-08, 9.3484e+00, 8.5590e-03, 
 2DIAGNOSTIC,   398, -6.821388006210e-01, 7.990072958819e-08, 9.3560e+00, 7.6580e-03, 
 2DIAGNOSTIC,   399, -6.821387410164e-01, 7.973072513323e-08, 9.3633e+00, 7.2782e-03, 
 2DIAGNOSTIC,   400, -6.821388006210e-01, 7.963223680463e-08, 9.3707e+00, 7.4561e-03, 
 2DIAGNOSTIC,   401, -6.821388006210e-01, 7.940056434563e-08, 9.3782e+00, 7.4489e-03, 
 2DIAGNOSTIC,   402, -6.821388006210e-01, 7.922582057063e-08, 9.3857e+00, 7.5309e-03, 
 2DIAGNOSTIC,   403, -6.821385622025e-01, 7.886067976415e-08, 9.3930e+00, 7.2460e-03, 
 2DIAGNOSTIC,   404, -6.821386218071e-01, 7.851040351170e-08, 9.4007e+00, 7.6771e-03, 
 2DIAGNOSTIC,   405, -6.821385622025e-01, 7.818367464552e-08, 9.4083e+00, 7.6599e-03, 
 2DIAGNOSTIC,   406, -6.821384429932e-01, 7.771270560397e-08, 9.4160e+00, 7.6799e-03, 
 2DIAGNOSTIC,   407, -6.821385025978e-01, 7.730974260767e-08, 9.4236e+00, 7.5731e-03, 
 2DIAGNOSTIC,   408, -6.821385622025e-01, 7.717836325583e-08, 9.4311e+00, 7.5629e-03, 
 2DIAGNOSTIC,   409, -6.821385025978e-01, 7.700045046022e-08, 9.4384e+00, 7.2930e-03, 
 2DIAGNOSTIC,   410, -6.821385622025e-01, 7.702299598122e-08, 9.4464e+00, 8.0049e-03, 
 2DIAGNOSTIC,   411, -6.821385622025e-01, 7.710100646818e-08, 9.4555e+00, 9.1250e-03, 
 2DIAGNOSTIC,   412, -6.821387410164e-01, 7.739602381207e-08, 9.4647e+00, 9.1519e-03, 
 2DIAGNOSTIC,   413, -6.821386218071e-01, 7.730290008112e-08, 9.4740e+00, 9.3279e-03, 
 2DIAGNOSTIC,   414, -6.821386218071e-01, 7.725224548949e-08, 9.4841e+00, 1.0034e-02, 
 2DIAGNOSTIC,   415, -6.821386218071e-01, 7.710919902593e-08, 9.4936e+00, 9.5670e-03, 
 2DIAGNOSTIC,   416, -6.821386814117e-01, 7.685957825743e-08, 9.5036e+00, 9.9311e-03, 
 2DIAGNOSTIC,   417, -6.821385622025e-01, 7.650950806237e-08, 9.5132e+00, 9.6679e-03, 
 2DIAGNOSTIC,   418, -6.821385622025e-01, 7.620830189126e-08, 9.5228e+00, 9.5270e-03, 
 2DIAGNOSTIC,   419, -6.821386814117e-01, 7.596046458502e-08, 9.5321e+00, 9.3248e-03, 
 2DIAGNOSTIC,   420, -6.821386218071e-01, 7.570640292442e-08, 9.5405e+00, 8.4689e-03, 
 2DIAGNOSTIC,   421, -6.821387410164e-01, 7.557267878155e-08, 9.5484e+00, 7.8211e-03, 
 2DIAGNOSTIC,   422, -6.821387410164e-01, 7.561970960523e-08, 9.5561e+00, 7.6940e-03, 
 2DIAGNOSTIC,   423, -6.821386814117e-01, 7.547023983534e-08, 9.5636e+00, 7.5171e-03, 
 2DIAGNOSTIC,   424, -6.821386814117e-01, 7.529776269166e-08, 9.5711e+00, 7.4720e-03, 
 2DIAGNOSTIC,   425, -6.821388006210e-01, 7.521447997760e-08, 9.5786e+00, 7.5371e-03, 
 2DIAGNOSTIC,   426, -6.821388006210e-01, 7.515519229173e-08, 9.5859e+00, 7.2720e-03, 
 2DIAGNOSTIC,   427, -6.821388006210e-01, 7.493616038801e-08, 9.5933e+00, 7.4029e-03, 
 2DIAGNOSTIC,   428, -6.821388006210e-01, 7.467789941984e-08, 9.6004e+00, 7.1630e-03, 
 2DIAGNOSTIC,   429, -6.821388602257e-01, 7.456458916977e-08, 9.6082e+00, 7.8011e-03, 
 2DIAGNOSTIC,   430, -6.821389198303e-01, 7.440530680469e-08, 9.6162e+00, 7.9522e-03, 
 2DIAGNOSTIC,   431, -6.821388602257e-01, 7.426237402797e-08, 9.6240e+00, 7.8681e-03, 
 2DIAGNOSTIC,   432, -6.821386814117e-01, 7.391165013360e-08, 9.6324e+00, 8.4000e-03, 
 2DIAGNOSTIC,   433, -6.821387410164e-01, 7.354367426160e-08, 9.6422e+00, 9.7411e-03, 
 2DIAGNOSTIC,   434, -6.821389198303e-01, 7.333409968169e-08, 9.6516e+00, 9.4159e-03, 
 2DIAGNOSTIC,   435, -6.821388006210e-01, 7.311554384160e-08, 9.6614e+00, 9.7480e-03, 
 2DIAGNOSTIC,   436, -6.821388006210e-01, 7.290945802652e-08, 9.6710e+00, 9.6490e-03, 
 2DIAGNOSTIC,   437, -6.821388006210e-01, 7.271685120713e-08, 9.6806e+00, 9.5990e-03, 
 2DIAGNOSTIC,   438, -6.821388006210e-01, 7.252958056370e-08, 9.6899e+00, 9.3150e-03, 
 2DIAGNOSTIC,   439, -6.821387410164e-01, 7.234663002009e-08, 9.6994e+00, 9.4690e-03, 
 2DIAGNOSTIC,   440, -6.821386814117e-01, 7.218076802928e-08, 9.7089e+00, 9.5310e-03, 
 2DIAGNOSTIC,   441, -6.821386218071e-01, 7.192563344915e-08, 9.7178e+00, 8.9030e-03, 
 2DIAGNOSTIC,   442, -6.821386814117e-01, 7.157973413996e-08, 9.7256e+00, 7.7400e-03, 
 2DIAGNOSTIC,   443, -6.821388602257e-01, 7.149022707154e-08, 9.7333e+00, 7.7269e-03, 
 2DIAGNOSTIC,   444, -6.821389198303e-01, 7.165680671051e-08, 9.7410e+00, 7.6649e-03, 
 2DIAGNOSTIC,   445, -6.821388006210e-01, 7.160258519434e-08, 9.7490e+00, 8.0421e-03, 
 2DIAGNOSTIC,   446, -6.821386218071e-01, 7.137823132553e-08, 9.7569e+00, 7.9138e-03, 
 2DIAGNOSTIC,   447, -6.821386814117e-01, 7.120819844886e-08, 9.7643e+00, 7.4041e-03, 
 2DIAGNOSTIC,   448, -6.821388006210e-01, 7.113856526075e-08, 9.7719e+00, 7.5550e-03, 
 2DIAGNOSTIC,   449, -6.821388006210e-01, 7.099804832933e-08, 9.7793e+00, 7.4658e-03, 
 2DIAGNOSTIC,   450, -6.821388602257e-01, 7.085452580213e-08, 9.7870e+00, 7.6349e-03, 
 2DIAGNOSTIC,   451, -6.821388006210e-01, 7.059156104106e-08, 9.7945e+00, 7.4930e-03, 
 2DIAGNOSTIC,   452, -6.821389198303e-01, 7.048618755334e-08, 9.8020e+00, 7.5209e-03, 
 2DIAGNOSTIC,   453, -6.821392178535e-01, 7.080037534024e-08, 9.8096e+00, 7.6251e-03, 
 2DIAGNOSTIC,   454, -6.821390390396e-01, 7.094291021303e-08, 9.8175e+00, 7.8659e-03, 
 2DIAGNOSTIC,   455, -6.821390390396e-01, 7.090792308873e-08, 9.8250e+00, 7.4871e-03, 
 2DIAGNOSTIC,   456, -6.821386218071e-01, 7.023537307305e-08, 9.8325e+00, 7.5548e-03, 
 2DIAGNOSTIC,   457, -6.821386218071e-01, 6.957861131696e-08, 9.8403e+00, 7.7350e-03, 
 2DIAGNOSTIC,   458, -6.821385025978e-01, 6.891990977920e-08, 9.8479e+00, 7.6420e-03, 
 2DIAGNOSTIC,   459, -6.821386814117e-01, 6.847842115576e-08, 9.8555e+00, 7.6551e-03, 
 2DIAGNOSTIC,   460, -6.821386218071e-01, 6.812432928882e-08, 9.8631e+00, 7.5719e-03, 
 2DIAGNOSTIC,   461, -6.821386814117e-01, 6.787934125896e-08, 9.8707e+00, 7.5560e-03, 
 2DIAGNOSTIC,   462, -6.821386814117e-01, 6.784678419081e-08, 9.8783e+00, 7.5939e-03, 
 2DIAGNOSTIC,   463, -6.821387410164e-01, 6.823555054325e-08, 9.8857e+00, 7.4651e-03, 
 2DIAGNOSTIC,   464, -6.821387410164e-01, 6.850211065057e-08, 9.8929e+00, 7.1602e-03, 
 2DIAGNOSTIC,   465, -6.821387410164e-01, 6.878412506239e-08, 9.9004e+00, 7.5030e-03, 
 2DIAGNOSTIC,   466, -6.821386218071e-01, 6.855163547925e-08, 9.9080e+00, 7.6191e-03, 
 2DIAGNOSTIC,   467, -6.821386814117e-01, 6.835338695055e-08, 9.9157e+00, 7.6380e-03, 
 2DIAGNOSTIC,   468, -6.821386814117e-01, 6.802019214547e-08, 9.9237e+00, 8.0619e-03, 
 2DIAGNOSTIC,   469, -6.821386814117e-01, 6.784486572542e-08, 9.9314e+00, 7.6630e-03, 
 2DIAGNOSTIC,   470, -6.821388006210e-01, 6.772339844474e-08, 9.9391e+00, 7.7028e-03, 
 2DIAGNOSTIC,   471, -6.821389794350e-01, 6.781002070966e-08, 9.9469e+00, 7.7720e-03, 
 2DIAGNOSTIC,   472, -6.821386814117e-01, 6.760282644791e-08, 9.9548e+00, 7.9439e-03, 
 2DIAGNOSTIC,   473, -6.821388602257e-01, 6.759696447034e-08, 9.9619e+00, 7.1280e-03, 
 2DIAGNOSTIC,   474, -6.821388602257e-01, 6.755306714012e-08, 9.9698e+00, 7.8530e-03, 
 2DIAGNOSTIC,   475, -6.821388602257e-01, 6.746653724576e-08, 9.9787e+00, 8.9400e-03, 
 2DIAGNOSTIC,   476, -6.821388602257e-01, 6.722792278424e-08, 9.9867e+00, 7.9391e-03, 
 2DIAGNOSTIC,   477, -6.821387410164e-01, 6.690562059930e-08, 9.9943e+00, 7.6542e-03, 
 2DIAGNOSTIC,   478, -6.821388602257e-01, 6.667396235116e-08, 1.0002e+01, 7.6101e-03, 
 2DIAGNOSTIC,   479, -6.821388602257e-01, 6.642238759014e-08, 1.0010e+01, 7.6640e-03, 
 2DIAGNOSTIC,   480, -6.821388602257e-01, 6.627009696558e-08, 1.0017e+01, 7.8831e-03, 
 2DIAGNOSTIC,   481, -6.821389198303e-01, 6.633793958599e-08, 1.0026e+01, 8.8100e-03, 
 2DIAGNOSTIC,   482, -6.821389198303e-01, 6.612476965984e-08, 1.0036e+01, 9.3310e-03, 
 2DIAGNOSTIC,   483, -6.821390390396e-01, 6.615780279162e-08, 1.0043e+01, 7.8709e-03, 
 2DIAGNOSTIC,   484, -6.821390390396e-01, 6.615888281658e-08, 1.0051e+01, 7.3581e-03, 
 2DIAGNOSTIC,   485, -6.821389198303e-01, 6.601796087580e-08, 1.0058e+01, 7.3950e-03, 
 2DIAGNOSTIC,   486, -6.821388602257e-01, 6.579387701322e-08, 1.0066e+01, 7.6170e-03, 
 2DIAGNOSTIC,   487, -6.821388602257e-01, 6.543358921363e-08, 1.0073e+01, 7.6051e-03, 
 2DIAGNOSTIC,   488, -6.821388602257e-01, 6.516363271203e-08, 1.0081e+01, 7.7000e-03, 
 2DIAGNOSTIC,   489, -6.821389198303e-01, 6.494885695929e-08, 1.0089e+01, 7.8068e-03, 
 2DIAGNOSTIC,   490, -6.821388602257e-01, 6.469635138728e-08, 1.0097e+01, 7.6978e-03, 
 2DIAGNOSTIC,   491, -6.821387410164e-01, 6.442191846645e-08, 1.0104e+01, 7.5719e-03, 
 2DIAGNOSTIC,   492, -6.821387410164e-01, 6.418434139732e-08, 1.0112e+01, 7.5080e-03, 
 2DIAGNOSTIC,   493, -6.821386814117e-01, 6.404118835235e-08, 1.0119e+01, 7.4930e-03, 
 2DIAGNOSTIC,   494, -6.821389794350e-01, 6.419993070494e-08, 1.0126e+01, 7.1270e-03, 
 2DIAGNOSTIC,   495, -6.821389198303e-01, 6.422242648796e-08, 1.0134e+01, 7.2582e-03, 
 2DIAGNOSTIC,   496, -6.821389198303e-01, 6.420641796012e-08, 1.0142e+01, 8.1182e-03, 
 2DIAGNOSTIC,   497, -6.821388006210e-01, 6.408859576368e-08, 1.0149e+01, 7.3111e-03, 
 2DIAGNOSTIC,   498, -6.821388006210e-01, 6.396268048547e-08, 1.0157e+01, 7.4761e-03, 
 2DIAGNOSTIC,   499, -6.821389198303e-01, 6.397470286856e-08, 1.0164e+01, 7.3340e-03, 
 2DIAGNOSTIC,   500, -6.821389794350e-01, 6.396336971193e-08, 1.0171e+01, 7.0012e-03, 
DIAGNOSTIC,Iteration,metricValue,convergenceValue,ITERATION_TIME_INDEX,SINCE_LAST
 2DIAGNOSTIC,     1, -5.794739127159e-01, inf, 1.0646e+01, 4.7546e-01, 
 2DIAGNOSTIC,     2, -5.796970725060e-01, inf, 1.0719e+01, 7.2391e-02, 
 2DIAGNOSTIC,     3, -5.797088146210e-01, inf, 1.0780e+01, 6.1471e-02, 
 2DIAGNOSTIC,     4, -5.797174572945e-01, inf, 1.0844e+01, 6.3617e-02, 
 2DIAGNOSTIC,     5, -5.797424912453e-01, inf, 1.0933e+01, 8.9697e-02, 
 2DIAGNOSTIC,     6, -5.797470808029e-01, inf, 1.0995e+01, 6.1166e-02, 
 2DIAGNOSTIC,     7, -5.797571539879e-01, inf, 1.1055e+01, 6.0298e-02, 
 2DIAGNOSTIC,     8, -5.797678232193e-01, inf, 1.1111e+01, 5.5709e-02, 
 2DIAGNOSTIC,     9, -5.797876715660e-01, inf, 1.1200e+01, 8.9142e-02, 
 2DIAGNOSTIC,    10, -5.797953009605e-01, 2.579435204098e-05, 1.1256e+01, 5.6489e-02, 
 2DIAGNOSTIC,    11, -5.797961950302e-01, 1.347551278741e-05, 1.1313e+01, 5.7196e-02, 
 2DIAGNOSTIC,    12, -5.798051357269e-01, 1.175705529022e-05, 1.1378e+01, 6.4018e-02, 
 2DIAGNOSTIC,    13, -5.798067450523e-01, 9.973596206692e-06, 1.1443e+01, 6.5416e-02, 
 2DIAGNOSTIC,    14, -5.798219442368e-01, 8.567250915803e-06, 1.1543e+01, 9.9995e-02, 
 2DIAGNOSTIC,    15, -5.798220038414e-01, 7.583662409161e-06, 1.1616e+01, 7.2686e-02, 
 2DIAGNOSTIC,    16, -5.798225998878e-01, 6.389972440957e-06, 1.1689e+01, 7.3142e-02, 
 2DIAGNOSTIC,    17, -5.798231363297e-01, 5.241179678706e-06, 1.1754e+01, 6.5307e-02, 
 2DIAGNOSTIC,    18, -5.798225402832e-01, 4.167066435912e-06, 1.1818e+01, 6.4248e-02, 
 2DIAGNOSTIC,    19, -5.798224210739e-01, 3.485166871542e-06, 1.1884e+01, 6.5458e-02, 
 2DIAGNOSTIC,    20, -5.798228383064e-01, 2.901723973991e-06, 1.1949e+01, 6.5191e-02, 
 2DIAGNOSTIC,    21, -5.798228383064e-01, 2.272015080962e-06, 1.2024e+01, 7.4581e-02, 
 2DIAGNOSTIC,    22, -5.798228979111e-01, 1.832357270359e-06, 1.2088e+01, 6.4678e-02, 
 2DIAGNOSTIC,    23, -5.798223018646e-01, 1.407606305293e-06, 1.2152e+01, 6.4145e-02, 
 2DIAGNOSTIC,    24, -5.798225998878e-01, 1.333204181719e-06, 1.2220e+01, 6.8001e-02, 
 2DIAGNOSTIC,    25, -5.798226594925e-01, 1.265553464691e-06, 1.2290e+01, 7.0086e-02, 
 2DIAGNOSTIC,    26, -5.798232555389e-01, 1.225591063303e-06, 1.2350e+01, 5.9973e-02, 
 2DIAGNOSTIC,    27, -5.798224806786e-01, 1.184290795209e-06, 1.2419e+01, 6.8931e-02, 
 2DIAGNOSTIC,    28, -5.798228383064e-01, 1.142025325862e-06, 1.2503e+01, 8.3885e-02, 
 2DIAGNOSTIC,    29, -5.798229575157e-01, 1.101716520679e-06, 1.2580e+01, 7.7004e-02, 
 2DIAGNOSTIC,    30, -5.798228383064e-01, 1.068105461854e-06, 1.2654e+01, 7.3776e-02, 
 2DIAGNOSTIC,    31, -5.798228383064e-01, 1.035921968651e-06, 1.2729e+01, 7.4486e-02, 
 2DIAGNOSTIC,    32, -5.798231363297e-01, 1.010790697364e-06, 1.2804e+01, 7.5435e-02, 
 2DIAGNOSTIC,    33, -5.798227190971e-01, 9.703696832730e-07, 1.2876e+01, 7.2107e-02, 
 2DIAGNOSTIC,    34, -5.798230767250e-01, 9.412522672392e-07, 1.2947e+01, 7.0588e-02, 
 2DIAGNOSTIC,    35, -5.798224806786e-01, 9.053403005055e-07, 1.3018e+01, 7.1132e-02, 
 2DIAGNOSTIC,    36, -5.798225998878e-01, 8.820783818919e-07, 1.3089e+01, 7.0783e-02, 
 2DIAGNOSTIC,    37, -5.798231959343e-01, 8.576031973462e-07, 1.3160e+01, 7.1198e-02, 
 2DIAGNOSTIC,    38, -5.798223018646e-01, 8.273729577013e-07, 1.3239e+01, 7.9226e-02, 
 2DIAGNOSTIC,    39, -5.798226594925e-01, 8.061297194217e-07, 1.3322e+01, 8.2610e-02, 
 2DIAGNOSTIC,    40, -5.798226594925e-01, 7.853220722609e-07, 1.3392e+01, 7.0644e-02, 
 2DIAGNOSTIC,    41, -5.798223614693e-01, 7.626779279235e-07, 1.3464e+01, 7.1527e-02, 
 2DIAGNOSTIC,    42, -5.798222422600e-01, 7.446212180184e-07, 1.3536e+01, 7.2401e-02, 
 2DIAGNOSTIC,    43, -5.798223018646e-01, 7.245018309732e-07, 1.3608e+01, 7.1773e-02, 
 2DIAGNOSTIC,    44, -5.798223614693e-01, 7.116033202692e-07, 1.3680e+01, 7.2433e-02, 
 2DIAGNOSTIC,    45, -5.798224210739e-01, 6.943708399376e-07, 1.3750e+01, 7.0089e-02, 
 2DIAGNOSTIC,    46, -5.798220038414e-01, 6.757357482456e-07, 1.3821e+01, 7.0910e-02, 
 2DIAGNOSTIC,    47, -5.798223614693e-01, 6.698384140691e-07, 1.3892e+01, 7.0509e-02, 
 2DIAGNOSTIC,    48, -5.798224210739e-01, 6.560268275280e-07, 1.3982e+01, 9.0281e-02, 
 2DIAGNOSTIC,    49, -5.798224210739e-01, 6.468872015830e-07, 1.4054e+01, 7.1535e-02, 
 2DIAGNOSTIC,    50, -5.798222422600e-01, 6.367293394760e-07, 1.4127e+01, 7.3263e-02, 
 2DIAGNOSTIC,    51, -5.798225402832e-01, 6.270812491493e-07, 1.4198e+01, 7.1336e-02, 
 2DIAGNOSTIC,    52, -5.798223018646e-01, 6.139681545392e-07, 1.4270e+01, 7.2134e-02, 
 2DIAGNOSTIC,    53, -5.798224210739e-01, 6.027664198882e-07, 1.4333e+01, 6.2262e-02, 
 2DIAGNOSTIC,    54, -5.798223018646e-01, 5.911758762522e-07, 1.4407e+01, 7.4734e-02, 
 2DIAGNOSTIC,    55, -5.798223614693e-01, 5.810484253743e-07, 1.4476e+01, 6.8557e-02, 
 2DIAGNOSTIC,    56, -5.798224210739e-01, 5.677717922481e-07, 1.4550e+01, 7.3954e-02, 
 2DIAGNOSTIC,    57, -5.798224806786e-01, 5.585322355728e-07, 1.4620e+01, 7.0455e-02, 
 2DIAGNOSTIC,    58, -5.798226594925e-01, 5.516005217032e-07, 1.4701e+01, 8.0281e-02, 
 2DIAGNOSTIC,    59, -5.798227190971e-01, 5.451203151097e-07, 1.4775e+01, 7.3926e-02, 
 2DIAGNOSTIC,    60, -5.798223614693e-01, 5.338289383872e-07, 1.4846e+01, 7.1233e-02, 
 2DIAGNOSTIC,    61, -5.798223018646e-01, 5.246233740763e-07, 1.4925e+01, 7.9135e-02, 
 2DIAGNOSTIC,    62, -5.798223614693e-01, 5.139407903698e-07, 1.4996e+01, 7.0972e-02, 
 2DIAGNOSTIC,    63, -5.798221826553e-01, 5.029993417338e-07, 1.5066e+01, 7.0365e-02, 
 2DIAGNOSTIC,    64, -5.798221826553e-01, 4.917075671074e-07, 1.5138e+01, 7.1450e-02, 
 2DIAGNOSTIC,    65, -5.798221826553e-01, 4.817778744837e-07, 1.5207e+01, 6.9027e-02, 
 2DIAGNOSTIC,    66, -5.798220634460e-01, 4.724450946014e-07, 1.5277e+01, 6.9884e-02, 
 2DIAGNOSTIC,    67, -5.798220634460e-01, 4.646951481391e-07, 1.5346e+01, 6.9002e-02, 
 2DIAGNOSTIC,    68, -5.798221826553e-01, 4.602534886544e-07, 1.5417e+01, 7.1791e-02, 
 2DIAGNOSTIC,    69, -5.798221826553e-01, 4.571334386583e-07, 1.5488e+01, 7.0942e-02, 
 2DIAGNOSTIC,    70, -5.798222422600e-01, 4.524006556039e-07, 1.5560e+01, 7.1665e-02, 
 2DIAGNOSTIC,    71, -5.798222422600e-01, 4.475751040900e-07, 1.5633e+01, 7.3108e-02, 
 2DIAGNOSTIC,    72, -5.798222422600e-01, 4.433739491105e-07, 1.5709e+01, 7.5341e-02, 
 2DIAGNOSTIC,    73, -5.798222422600e-01, 4.379168103696e-07, 1.5781e+01, 7.2204e-02, 
 2DIAGNOSTIC,    74, -5.798221826553e-01, 4.319905997363e-07, 1.5854e+01, 7.2918e-02, 
 2DIAGNOSTIC,    75, -5.798222422600e-01, 4.264473716376e-07, 1.5926e+01, 7.2310e-02, 
 2DIAGNOSTIC,    76, -5.798221230507e-01, 4.192820597382e-07, 1.5996e+01, 7.0364e-02, 
 2DIAGNOSTIC,    77, -5.798224806786e-01, 4.145143748246e-07, 1.6066e+01, 7.0105e-02, 
 2DIAGNOSTIC,    78, -5.798224806786e-01, 4.104227571133e-07, 1.6138e+01, 7.1214e-02, 
 2DIAGNOSTIC,    79, -5.798221826553e-01, 4.043440924306e-07, 1.6198e+01, 6.0788e-02, 
 2DIAGNOSTIC,    80, -5.798223614693e-01, 3.998020474683e-07, 1.6268e+01, 7.0046e-02, 
 2DIAGNOSTIC,    81, -5.798223018646e-01, 3.947460527343e-07, 1.6340e+01, 7.1961e-02, 
 2DIAGNOSTIC,    82, -5.798222422600e-01, 3.892239135439e-07, 1.6413e+01, 7.2188e-02, 
 2DIAGNOSTIC,    83, -5.798223018646e-01, 3.840868316729e-07, 1.6482e+01, 6.9630e-02, 
 2DIAGNOSTIC,    84, -5.798223018646e-01, 3.786656463944e-07, 1.6562e+01, 7.9799e-02, 
 2DIAGNOSTIC,    85, -5.798223614693e-01, 3.740960892173e-07, 1.6633e+01, 7.0549e-02, 
 2DIAGNOSTIC,    86, -5.798223614693e-01, 3.688803076329e-07, 1.6704e+01, 7.1414e-02, 
 2DIAGNOSTIC,    87, -5.798221826553e-01, 3.648955839708e-07, 1.6774e+01, 6.9758e-02, 
 2DIAGNOSTIC,    88, -5.798221826553e-01, 3.611570491557e-07, 1.6844e+01, 7.0148e-02, 
 2DIAGNOSTIC,    89, -5.798221826553e-01, 3.558408820936e-07, 1.6915e+01, 7.1229e-02, 
 2DIAGNOSTIC,    90, -5.798221826553e-01, 3.517590414504e-07, 1.6987e+01, 7.2060e-02, 
 2DIAGNOSTIC,    91, -5.798221230507e-01, 3.473039669188e-07, 1.7060e+01, 7.2566e-02, 
 2DIAGNOSTIC,    92, -5.798223614693e-01, 3.441385558745e-07, 1.7129e+01, 6.9201e-02, 
 2DIAGNOSTIC,    93, -5.798223614693e-01, 3.414805576085e-07, 1.7200e+01, 7.1067e-02, 
 2DIAGNOSTIC,    94, -5.798221230507e-01, 3.376766812835e-07, 1.7272e+01, 7.2360e-02, 
 2DIAGNOSTIC,    95, -5.798223614693e-01, 3.356068418725e-07, 1.7344e+01, 7.1274e-02, 
 2DIAGNOSTIC,    96, -5.798221826553e-01, 3.325708917146e-07, 1.7413e+01, 6.9746e-02, 
 2DIAGNOSTIC,    97, -5.798223614693e-01, 3.294817929600e-07, 1.7485e+01, 7.1829e-02, 
 2DIAGNOSTIC,    98, -5.798223018646e-01, 3.259869458816e-07, 1.7557e+01, 7.1590e-02, 
 2DIAGNOSTIC,    99, -5.798223018646e-01, 3.224639613109e-07, 1.7627e+01, 7.0023e-02, 
 2DIAGNOSTIC,   100, -5.798223614693e-01, 3.192138819941e-07, 1.7699e+01, 7.2132e-02, 
 2DIAGNOSTIC,   101, -5.798222422600e-01, 3.149949350245e-07, 1.7771e+01, 7.1582e-02, 
 2DIAGNOSTIC,   102, -5.798223018646e-01, 3.123016369955e-07, 1.7840e+01, 6.9466e-02, 
 2DIAGNOSTIC,   103, -5.798221826553e-01, 3.090748919021e-07, 1.7911e+01, 7.0523e-02, 
 2DIAGNOSTIC,   104, -5.798223614693e-01, 3.055881165892e-07, 1.7983e+01, 7.2320e-02, 
 2DIAGNOSTIC,   105, -5.798224806786e-01, 3.038653915155e-07, 1.8053e+01, 7.0350e-02, 
 2DIAGNOSTIC,   106, -5.798224806786e-01, 3.012256684087e-07, 1.8127e+01, 7.3717e-02, 
 2DIAGNOSTIC,   107, -5.798224210739e-01, 2.991039593780e-07, 1.8199e+01, 7.1893e-02, 
 2DIAGNOSTIC,   108, -5.798225402832e-01, 2.971326864554e-07, 1.8269e+01, 7.0462e-02, 
 2DIAGNOSTIC,   109, -5.798224210739e-01, 2.943685046830e-07, 1.8342e+01, 7.3089e-02, 
 2DIAGNOSTIC,   110, -5.798224806786e-01, 2.919557005043e-07, 1.8414e+01, 7.1611e-02, 
 2DIAGNOSTIC,   111, -5.798223614693e-01, 2.882577518903e-07, 1.8485e+01, 7.1050e-02, 
 2DIAGNOSTIC,   112, -5.798221826553e-01, 2.839865089754e-07, 1.8555e+01, 7.0383e-02, 
 2DIAGNOSTIC,   113, -5.798223018646e-01, 2.797926015319e-07, 1.8625e+01, 6.9786e-02, 
 2DIAGNOSTIC,   114, -5.798222422600e-01, 2.763058262190e-07, 1.8698e+01, 7.2582e-02, 
 2DIAGNOSTIC,   115, -5.798222422600e-01, 2.736585429375e-07, 1.8767e+01, 6.9348e-02, 
 2DIAGNOSTIC,   116, -5.798224210739e-01, 2.721195642152e-07, 1.8836e+01, 6.9002e-02, 
 2DIAGNOSTIC,   117, -5.798221826553e-01, 2.695337002478e-07, 1.8906e+01, 6.9550e-02, 
 2DIAGNOSTIC,   118, -5.798223614693e-01, 2.684993489765e-07, 1.8976e+01, 7.0135e-02, 
 2DIAGNOSTIC,   119, -5.798224210739e-01, 2.672980485841e-07, 1.9048e+01, 7.1749e-02, 
 2DIAGNOSTIC,   120, -5.798224806786e-01, 2.666025409326e-07, 1.9118e+01, 7.0670e-02, 
 2DIAGNOSTIC,   121, -5.798224806786e-01, 2.653104616002e-07, 1.9188e+01, 6.9987e-02, 
 2DIAGNOSTIC,   122, -5.798225998878e-01, 2.635667613049e-07, 1.9260e+01, 7.1470e-02, 
 2DIAGNOSTIC,   123, -5.798224210739e-01, 2.613391245632e-07, 1.9332e+01, 7.2001e-02, 
 2DIAGNOSTIC,   124, -5.798225402832e-01, 2.591308430056e-07, 1.9402e+01, 7.0256e-02, 
 2DIAGNOSTIC,   125, -5.798224806786e-01, 2.564333669852e-07, 1.9473e+01, 7.0955e-02, 
 2DIAGNOSTIC,   126, -5.798221826553e-01, 2.531627956159e-07, 1.9545e+01, 7.2464e-02, 
 2DIAGNOSTIC,   127, -5.798223018646e-01, 2.494349473636e-07, 1.9616e+01, 7.0971e-02, 
 2DIAGNOSTIC,   128, -5.798224806786e-01, 2.472096412021e-07, 1.9690e+01, 7.3939e-02, 
 2DIAGNOSTIC,   129, -5.798224806786e-01, 2.453365652855e-07, 1.9760e+01, 6.9956e-02, 
 2DIAGNOSTIC,   130, -5.798224806786e-01, 2.438551689465e-07, 1.9831e+01, 7.0432e-02, 
 2DIAGNOSTIC,   131, -5.798225402832e-01, 2.427161973628e-07, 1.9901e+01, 7.0023e-02, 
 2DIAGNOSTIC,   132, -5.798224210739e-01, 2.416139466277e-07, 1.9971e+01, 7.0197e-02, 
 2DIAGNOSTIC,   133, -5.798224210739e-01, 2.397777336682e-07, 2.0042e+01, 7.1564e-02, 
 2DIAGNOSTIC,   134, -5.798224806786e-01, 2.385606592270e-07, 2.0113e+01, 7.1009e-02, 
 2DIAGNOSTIC,   135, -5.798224210739e-01, 2.368479670167e-07, 2.0187e+01, 7.3577e-02, 
 2DIAGNOSTIC,   136, -5.798224806786e-01, 2.341852791687e-07, 2.0260e+01, 7.3095e-02, 
 2DIAGNOSTIC,   137, -5.798224210739e-01, 2.317298708476e-07, 2.0329e+01, 6.9267e-02, 
 2DIAGNOSTIC,   138, -5.798223614693e-01, 2.297878012314e-07, 2.0397e+01, 6.7622e-02, 
 2DIAGNOSTIC,   139, -5.798223614693e-01, 2.279436159824e-07, 2.0467e+01, 6.9773e-02, 
 2DIAGNOSTIC,   140, -5.798224210739e-01, 2.264076357505e-07, 2.0536e+01, 6.9577e-02, 
 2DIAGNOSTIC,   141, -5.798225402832e-01, 2.255976880861e-07, 2.0606e+01, 6.9777e-02, 
 2DIAGNOSTIC,   142, -5.798224806786e-01, 2.241759347044e-07, 2.0677e+01, 7.0371e-02, 
 2DIAGNOSTIC,   143, -5.798225402832e-01, 2.229762117167e-07, 2.0746e+01, 6.9459e-02, 
 2DIAGNOSTIC,   144, -5.798225402832e-01, 2.219482411192e-07, 2.0816e+01, 6.9717e-02, 
 2DIAGNOSTIC,   145, -5.798225402832e-01, 2.206143676631e-07, 2.0886e+01, 7.0231e-02, 
 2DIAGNOSTIC,   146, -5.798224806786e-01, 2.191788723849e-07, 2.0957e+01, 7.1022e-02, 
 2DIAGNOSTIC,   147, -5.798225402832e-01, 2.176523423714e-07, 2.1026e+01, 6.9352e-02, 
 2DIAGNOSTIC,   148, -5.798227190971e-01, 2.164174617292e-07, 2.1097e+01, 7.0623e-02, 
 2DIAGNOSTIC,   149, -5.798225402832e-01, 2.144443840280e-07, 2.1169e+01, 7.1639e-02, 
 2DIAGNOSTIC,   150, -5.798225998878e-01, 2.128119547251e-07, 2.1239e+01, 7.0180e-02, 
 2DIAGNOSTIC,   151, -5.798225402832e-01, 2.113297910000e-07, 2.1309e+01, 7.0179e-02, 
 2DIAGNOSTIC,   152, -5.798225998878e-01, 2.097906843801e-07, 2.1380e+01, 7.1436e-02, 
 2DIAGNOSTIC,   153, -5.798224806786e-01, 2.080149812400e-07, 2.1451e+01, 7.0504e-02, 
 2DIAGNOSTIC,   154, -5.798224806786e-01, 2.062697888050e-07, 2.1520e+01, 6.9106e-02, 
 2DIAGNOSTIC,   155, -5.798224210739e-01, 2.044019709047e-07, 2.1590e+01, 7.0393e-02, 
 2DIAGNOSTIC,   156, -5.798224806786e-01, 2.026315968351e-07, 2.1658e+01, 6.7973e-02, 
 2DIAGNOSTIC,   157, -5.798225998878e-01, 2.015381994624e-07, 2.1730e+01, 7.1359e-02, 
 2DIAGNOSTIC,   158, -5.798223018646e-01, 2.002026633363e-07, 2.1800e+01, 7.0552e-02, 
 2DIAGNOSTIC,   159, -5.798222422600e-01, 1.982898822916e-07, 2.1868e+01, 6.8046e-02, 
 2DIAGNOSTIC,   160, -5.798223018646e-01, 1.969427785298e-07, 2.1939e+01, 7.1034e-02, 
 2DIAGNOSTIC,   161, -5.798224210739e-01, 1.959403022056e-07, 2.2012e+01, 7.2415e-02, 
 2DIAGNOSTIC,   162, -5.798223018646e-01, 1.949221797304e-07, 2.2084e+01, 7.1995e-02, 
 2DIAGNOSTIC,   163, -5.798224210739e-01, 1.940889831076e-07, 2.2155e+01, 7.1535e-02, 
 2DIAGNOSTIC,   164, -5.798223614693e-01, 1.932015294415e-07, 2.2228e+01, 7.2432e-02, 
 2DIAGNOSTIC,   165, -5.798223614693e-01, 1.922066559246e-07, 2.2297e+01, 6.9235e-02, 
 2DIAGNOSTIC,   166, -5.798224210739e-01, 1.916072136510e-07, 2.2367e+01, 6.9843e-02, 
 2DIAGNOSTIC,   167, -5.798223018646e-01, 1.910382394499e-07, 2.2439e+01, 7.1727e-02, 
 2DIAGNOSTIC,   168, -5.798223018646e-01, 1.895731998047e-07, 2.2507e+01, 6.8004e-02, 
 2DIAGNOSTIC,   169, -5.798223614693e-01, 1.880973172774e-07, 2.2575e+01, 6.8971e-02, 
 2DIAGNOSTIC,   170, -5.798224806786e-01, 1.871480037607e-07, 2.2643e+01, 6.7642e-02, 
 2DIAGNOSTIC,   171, -5.798223018646e-01, 1.860380081098e-07, 2.2710e+01, 6.7198e-02, 
 2DIAGNOSTIC,   172, -5.798224210739e-01, 1.849543451726e-07, 2.2778e+01, 6.7535e-02, 
 2DIAGNOSTIC,   173, -5.798225402832e-01, 1.845556596436e-07, 2.2844e+01, 6.6369e-02, 
 2DIAGNOSTIC,   174, -5.798223614693e-01, 1.834023493075e-07, 2.2924e+01, 7.9917e-02, 
 2DIAGNOSTIC,   175, -5.798224806786e-01, 1.825498401331e-07, 2.2996e+01, 7.2332e-02, 
 2DIAGNOSTIC,   176, -5.798225402832e-01, 1.819715009788e-07, 2.3071e+01, 7.4633e-02, 
 2DIAGNOSTIC,   177, -5.798224806786e-01, 1.807783576169e-07, 2.3145e+01, 7.4323e-02, 
 2DIAGNOSTIC,   178, -5.798223614693e-01, 1.791656529804e-07, 2.3223e+01, 7.7827e-02, 
 2DIAGNOSTIC,   179, -5.798224210739e-01, 1.778588938350e-07, 2.3300e+01, 7.6450e-02, 
 2DIAGNOSTIC,   180, -5.798223614693e-01, 1.767223096749e-07, 2.3377e+01, 7.6800e-02, 
 2DIAGNOSTIC,   181, -5.798224210739e-01, 1.752602685201e-07, 2.3453e+01, 7.6742e-02, 
 2DIAGNOSTIC,   182, -5.798223018646e-01, 1.738513191185e-07, 2.3537e+01, 8.4127e-02, 
 2DIAGNOSTIC,   183, -5.798221826553e-01, 1.725823040033e-07, 2.3610e+01, 7.2491e-02, 
 2DIAGNOSTIC,   184, -5.798221826553e-01, 1.709689314566e-07, 2.3682e+01, 7.2502e-02, 
 2DIAGNOSTIC,   185, -5.798223018646e-01, 1.701717309288e-07, 2.3752e+01, 7.0051e-02, 
 2DIAGNOSTIC,   186, -5.798223614693e-01, 1.698582821064e-07, 2.3823e+01, 7.0168e-02, 
 2DIAGNOSTIC,   187, -5.798224210739e-01, 1.696749336588e-07, 2.3894e+01, 7.1034e-02, 
 2DIAGNOSTIC,   188, -5.798224806786e-01, 1.693853732831e-07, 2.3964e+01, 7.0141e-02, 
 2DIAGNOSTIC,   189, -5.798223614693e-01, 1.689278263939e-07, 2.4037e+01, 7.2895e-02, 
 2DIAGNOSTIC,   190, -5.798223614693e-01, 1.682552834836e-07, 2.4107e+01, 7.0069e-02, 
 2DIAGNOSTIC,   191, -5.798223614693e-01, 1.676612697565e-07, 2.4175e+01, 6.7907e-02, 
 2DIAGNOSTIC,   192, -5.798223018646e-01, 1.665134305995e-07, 2.4244e+01, 6.8968e-02, 
 2DIAGNOSTIC,   193, -5.798223614693e-01, 1.651532812730e-07, 2.4309e+01, 6.4947e-02, 
 2DIAGNOSTIC,   194, -5.798223614693e-01, 1.637687461198e-07, 2.4375e+01, 6.6758e-02, 
 2DIAGNOSTIC,   195, -5.798223614693e-01, 1.627181092090e-07, 2.4439e+01, 6.3490e-02, 
 2DIAGNOSTIC,   196, -5.798223614693e-01, 1.618629426048e-07, 2.4507e+01, 6.7964e-02, 
 2DIAGNOSTIC,   197, -5.798223018646e-01, 1.610528101992e-07, 2.4572e+01, 6.5177e-02, 
 2DIAGNOSTIC,   198, -5.798225998878e-01, 1.611878559515e-07, 2.4642e+01, 6.9641e-02, 
 2DIAGNOSTIC,   199, -5.798225402832e-01, 1.608037933920e-07, 2.4709e+01, 6.7633e-02, 
 2DIAGNOSTIC,   200, -5.798224806786e-01, 1.601959098707e-07, 2.4776e+01, 6.7048e-02, 
 2DIAGNOSTIC,   201, -5.798225402832e-01, 1.596487351208e-07, 2.4841e+01, 6.4273e-02, 
 2DIAGNOSTIC,   202, -5.798224806786e-01, 1.586698488154e-07, 2.4909e+01, 6.8768e-02, 
 2DIAGNOSTIC,   203, -5.798224806786e-01, 1.577208195158e-07, 2.4979e+01, 6.9729e-02, 
 2DIAGNOSTIC,   204, -5.798225402832e-01, 1.568235461491e-07, 2.5045e+01, 6.6399e-02, 
 2DIAGNOSTIC,   205, -5.798223614693e-01, 1.554266475523e-07, 2.5111e+01, 6.5197e-02, 
 2DIAGNOSTIC,   206, -5.798223614693e-01, 1.540413592238e-07, 2.5178e+01, 6.7723e-02, 
 2DIAGNOSTIC,   207, -5.798223614693e-01, 1.525398403146e-07, 2.5245e+01, 6.6228e-02, 
 2DIAGNOSTIC,   208, -5.798225402832e-01, 1.522844570445e-07, 2.5315e+01, 6.9948e-02, 
 2DIAGNOSTIC,   209, -5.798225402832e-01, 1.519455850030e-07, 2.5385e+01, 6.9978e-02, 
 2DIAGNOSTIC,   210, -5.798222422600e-01, 1.508060449851e-07, 2.5455e+01, 7.0681e-02, 
 2DIAGNOSTIC,   211, -5.798221826553e-01, 1.497770085734e-07, 2.5526e+01, 7.1055e-02, 
 2DIAGNOSTIC,   212, -5.798225998878e-01, 1.496691339753e-07, 2.5596e+01, 7.0183e-02, 
 2DIAGNOSTIC,   213, -5.798225998878e-01, 1.495430552723e-07, 2.5665e+01, 6.8564e-02, 
 2DIAGNOSTIC,   214, -5.798224806786e-01, 1.492843040296e-07, 2.5736e+01, 7.0993e-02, 
 2DIAGNOSTIC,   215, -5.798224210739e-01, 1.484641245497e-07, 2.5804e+01, 6.8332e-02, 
 2DIAGNOSTIC,   216, -5.798223018646e-01, 1.473381701089e-07, 2.5873e+01, 6.8688e-02, 
 2DIAGNOSTIC,   217, -5.798223614693e-01, 1.463142638158e-07, 2.5943e+01, 6.9586e-02, 
 2DIAGNOSTIC,   218, -5.798224210739e-01, 1.458407297150e-07, 2.6014e+01, 7.1316e-02, 
 2DIAGNOSTIC,   219, -5.798226594925e-01, 1.459438863094e-07, 2.6085e+01, 7.1384e-02, 
 2DIAGNOSTIC,   220, -5.798225998878e-01, 1.451897588822e-07, 2.6154e+01, 6.8939e-02, 
 2DIAGNOSTIC,   221, -5.798224210739e-01, 1.438413477217e-07, 2.6223e+01, 6.9220e-02, 
 2DIAGNOSTIC,   222, -5.798224806786e-01, 1.435785463855e-07, 2.6295e+01, 7.1087e-02, 
 2DIAGNOSTIC,   223, -5.798226594925e-01, 1.436693111145e-07, 2.6364e+01, 6.9747e-02, 
 2DIAGNOSTIC,   224, -5.798226594925e-01, 1.433767522485e-07, 2.6434e+01, 6.9318e-02, 
 2DIAGNOSTIC,   225, -5.798225402832e-01, 1.425837865554e-07, 2.6505e+01, 7.0948e-02, 
 2DIAGNOSTIC,   226, -5.798226594925e-01, 1.417070052412e-07, 2.6575e+01, 7.0857e-02, 
 2DIAGNOSTIC,   227, -5.798220038414e-01, 1.394458166715e-07, 2.6647e+01, 7.1906e-02, 
 2DIAGNOSTIC,   228, -5.798221230507e-01, 1.376655518470e-07, 2.6718e+01, 7.0567e-02, 
 2DIAGNOSTIC,   229, -5.798221230507e-01, 1.365721971069e-07, 2.6804e+01, 8.6534e-02, 
 2DIAGNOSTIC,   230, -5.798222422600e-01, 1.358452408340e-07, 2.6886e+01, 8.2030e-02, 
 2DIAGNOSTIC,   231, -5.798224210739e-01, 1.353639049739e-07, 2.6962e+01, 7.5781e-02, 
 2DIAGNOSTIC,   232, -5.798224210739e-01, 1.352395457843e-07, 2.7039e+01, 7.6356e-02, 
 2DIAGNOSTIC,   233, -5.798224806786e-01, 1.358109074090e-07, 2.7118e+01, 7.9346e-02, 
 2DIAGNOSTIC,   234, -5.798224806786e-01, 1.364353039435e-07, 2.7198e+01, 7.9635e-02, 
 2DIAGNOSTIC,   235, -5.798225402832e-01, 1.368582331907e-07, 2.7274e+01, 7.6283e-02, 
 2DIAGNOSTIC,   236, -5.798224210739e-01, 1.371652302851e-07, 2.7350e+01, 7.6502e-02, 
 2DIAGNOSTIC,   237, -5.798223614693e-01, 1.357624910270e-07, 2.7428e+01, 7.7283e-02, 
 2DIAGNOSTIC,   238, -5.798224210739e-01, 1.345990199297e-07, 2.7508e+01, 7.9873e-02, 
 2DIAGNOSTIC,   239, -5.798222422600e-01, 1.329742786993e-07, 2.7585e+01, 7.7360e-02, 
 2DIAGNOSTIC,   240, -5.798220634460e-01, 1.312536141995e-07, 2.7664e+01, 7.9119e-02, 
 2DIAGNOSTIC,   241, -5.798222422600e-01, 1.304136674207e-07, 2.7733e+01, 6.8851e-02, 
 2DIAGNOSTIC,   242, -5.798223018646e-01, 1.298355414292e-07, 2.7810e+01, 7.7602e-02, 
 2DIAGNOSTIC,   243, -5.798224806786e-01, 1.298923990589e-07, 2.7889e+01, 7.8416e-02, 
 2DIAGNOSTIC,   244, -5.798224210739e-01, 1.299235066199e-07, 2.7967e+01, 7.7980e-02, 
 2DIAGNOSTIC,   245, -5.798224210739e-01, 1.301401084675e-07, 2.8044e+01, 7.7198e-02, 
 2DIAGNOSTIC,   246, -5.798224210739e-01, 1.300862066955e-07, 2.8115e+01, 7.1118e-02, 
 2DIAGNOSTIC,   247, -5.798223614693e-01, 1.297004814660e-07, 2.8183e+01, 6.8253e-02, 
 2DIAGNOSTIC,   248, -5.798225402832e-01, 1.297090364005e-07, 2.8248e+01, 6.4843e-02, 
 2DIAGNOSTIC,   249, -5.798225402832e-01, 1.292304574463e-07, 2.8316e+01, 6.7271e-02, 
 2DIAGNOSTIC,   250, -5.798224806786e-01, 1.281439949707e-07, 2.8380e+01, 6.4595e-02, 
DIAGNOSTIC,Iteration,metricValue,convergenceValue,ITERATION_TIME_INDEX,SINCE_LAST
 2DIAGNOSTIC,     1, -5.042909979820e-01, inf, 2.9412e+01, 1.0318e+00, 
 2DIAGNOSTIC,     2, -5.044369697571e-01, inf, 2.9758e+01, 3.4566e-01, 
 2DIAGNOSTIC,     3, -5.044355988503e-01, inf, 3.0068e+01, 3.1076e-01, 
 2DIAGNOSTIC,     4, -5.044354200363e-01, inf, 3.0334e+01, 2.6545e-01, 
 2DIAGNOSTIC,     5, -5.044371485710e-01, inf, 3.0598e+01, 2.6469e-01, 
 2DIAGNOSTIC,     6, -5.044405460358e-01, inf, 3.0870e+01, 2.7141e-01, 
 2DIAGNOSTIC,     7, -5.044471025467e-01, inf, 3.1136e+01, 2.6640e-01, 
 2DIAGNOSTIC,     8, -5.044566988945e-01, inf, 3.1576e+01, 4.3931e-01, 
 2DIAGNOSTIC,     9, -5.044567584991e-01, inf, 3.1871e+01, 2.9507e-01, 
 2DIAGNOSTIC,    10, -5.044561028481e-01, 1.463128228352e-05, 3.2194e+01, 3.2365e-01, 
 2DIAGNOSTIC,    11, -5.044562220573e-01, 6.085851509852e-06, 3.2491e+01, 2.9646e-01, 
 2DIAGNOSTIC,    12, -5.044561028481e-01, 5.521520051843e-06, 3.2801e+01, 3.1072e-01, 
 2DIAGNOSTIC,    13, -5.044559240341e-01, 4.712843292509e-06, 3.3117e+01, 3.1601e-01, 
 2DIAGNOSTIC,    14, -5.044558644295e-01, 3.807090479313e-06, 3.3416e+01, 2.9817e-01, 
 2DIAGNOSTIC,    15, -5.044558644295e-01, 2.952400109280e-06, 3.3722e+01, 3.0683e-01, 
 2DIAGNOSTIC,    16, -5.044561028481e-01, 2.253708089484e-06, 3.3990e+01, 2.6773e-01, 
 2DIAGNOSTIC,    17, -5.044567584991e-01, 1.842162873800e-06, 3.4292e+01, 3.0158e-01, 
 2DIAGNOSTIC,    18, -5.044569969177e-01, 1.786246798474e-06, 3.4602e+01, 3.1043e-01, 
 2DIAGNOSTIC,    19, -5.044572949409e-01, 1.745802592268e-06, 3.4931e+01, 3.2857e-01, 
 2DIAGNOSTIC,    20, -5.044574737549e-01, 1.689225200607e-06, 3.5244e+01, 3.1296e-01, 
 2DIAGNOSTIC,    21, -5.044577717781e-01, 1.639933771003e-06, 3.5548e+01, 3.0421e-01, 
 2DIAGNOSTIC,    22, -5.044578313828e-01, 1.581658466421e-06, 3.5878e+01, 3.3024e-01, 
 2DIAGNOSTIC,    23, -5.044580698013e-01, 1.517281020824e-06, 3.6208e+01, 3.2939e-01, 
 2DIAGNOSTIC,    24, -5.044581294060e-01, 1.445822704227e-06, 3.6512e+01, 3.0402e-01, 
 2DIAGNOSTIC,    25, -5.044578313828e-01, 1.362102807434e-06, 3.6783e+01, 2.7140e-01, 
 2DIAGNOSTIC,    26, -5.044580101967e-01, 1.285346115765e-06, 3.7086e+01, 3.0268e-01, 
 2DIAGNOSTIC,    27, -5.044580101967e-01, 1.221898855874e-06, 3.7388e+01, 3.0241e-01, 
 2DIAGNOSTIC,    28, -5.044584274292e-01, 1.171876533590e-06, 3.7686e+01, 2.9792e-01, 
 2DIAGNOSTIC,    29, -5.044581294060e-01, 1.121723585129e-06, 3.7992e+01, 3.0631e-01, 
 2DIAGNOSTIC,    30, -5.044583082199e-01, 1.079542926163e-06, 3.8307e+01, 3.1456e-01, 
 2DIAGNOSTIC,    31, -5.044578909874e-01, 1.036070671034e-06, 3.8619e+01, 3.1166e-01, 
 2DIAGNOSTIC,    32, -5.044583678246e-01, 1.003749162010e-06, 3.8919e+01, 3.0024e-01, 
 2DIAGNOSTIC,    33, -5.044581890106e-01, 9.730765668792e-07, 3.9190e+01, 2.7118e-01, 
 2DIAGNOSTIC,    34, -5.044578909874e-01, 9.396824225405e-07, 3.9519e+01, 3.2922e-01, 
 2DIAGNOSTIC,    35, -5.044583082199e-01, 9.099769613385e-07, 3.9816e+01, 2.9660e-01, 
 2DIAGNOSTIC,    36, -5.044584870338e-01, 8.871990644366e-07, 4.0116e+01, 3.0009e-01, 
 2DIAGNOSTIC,    37, -5.044582486153e-01, 8.613258160040e-07, 4.0417e+01, 3.0132e-01, 
 2DIAGNOSTIC,    38, -5.044580101967e-01, 8.396411885769e-07, 4.0714e+01, 2.9711e-01, 
 2DIAGNOSTIC,    39, -5.044585466385e-01, 8.223962595366e-07, 4.1018e+01, 3.0379e-01, 
 2DIAGNOSTIC,    40, -5.044584870338e-01, 8.068539045780e-07, 4.1322e+01, 3.0439e-01, 
 2DIAGNOSTIC,    41, -5.044582486153e-01, 7.816776133041e-07, 4.1621e+01, 2.9824e-01, 
 2DIAGNOSTIC,    42, -5.044584274292e-01, 7.663080623388e-07, 4.1922e+01, 3.0115e-01, 
 2DIAGNOSTIC,    43, -5.044581294060e-01, 7.446905669894e-07, 4.2231e+01, 3.0961e-01, 
 2DIAGNOSTIC,    44, -5.044583082199e-01, 7.218694122457e-07, 4.2531e+01, 2.9958e-01, 
 2DIAGNOSTIC,    45, -5.044580698013e-01, 7.021832857390e-07, 4.2832e+01, 3.0125e-01, 
 2DIAGNOSTIC,    46, -5.044582486153e-01, 6.884339995850e-07, 4.3128e+01, 2.9540e-01, 
 2DIAGNOSTIC,    47, -5.044580101967e-01, 6.699254413434e-07, 4.3426e+01, 2.9813e-01, 
 2DIAGNOSTIC,    48, -5.044581890106e-01, 6.520164674839e-07, 4.3722e+01, 2.9632e-01, 
 2DIAGNOSTIC,    49, -5.044581294060e-01, 6.412967081815e-07, 4.4028e+01, 3.0573e-01, 
 2DIAGNOSTIC,    50, -5.044581294060e-01, 6.311671540971e-07, 4.4348e+01, 3.2050e-01, 
 2DIAGNOSTIC,    51, -5.044581294060e-01, 6.192308887876e-07, 4.4648e+01, 2.9915e-01, 
 2DIAGNOSTIC,    52, -5.044580101967e-01, 6.089235853324e-07, 4.4953e+01, 3.0535e-01, 
 2DIAGNOSTIC,    53, -5.044581890106e-01, 5.979699153613e-07, 4.5250e+01, 2.9743e-01, 
 2DIAGNOSTIC,    54, -5.044583082199e-01, 5.907331797061e-07, 4.5547e+01, 2.9640e-01, 
 2DIAGNOSTIC,    55, -5.044581890106e-01, 5.798548841085e-07, 4.5844e+01, 2.9710e-01, 
 2DIAGNOSTIC,    56, -5.044582486153e-01, 5.717841986552e-07, 4.6151e+01, 3.0750e-01, 
 2DIAGNOSTIC,    57, -5.044581890106e-01, 5.606348167930e-07, 4.6444e+01, 2.9235e-01, 
 2DIAGNOSTIC,    58, -5.044583678246e-01, 5.530896487471e-07, 4.6744e+01, 2.9997e-01, 
 2DIAGNOSTIC,    59, -5.044583678246e-01, 5.446988780022e-07, 4.7117e+01, 3.7342e-01, 
 2DIAGNOSTIC,    60, -5.044582486153e-01, 5.349729690352e-07, 4.7410e+01, 2.9307e-01, 
 2DIAGNOSTIC,    61, -5.044584274292e-01, 5.268802283354e-07, 4.7707e+01, 2.9716e-01, 
 2DIAGNOSTIC,    62, -5.044583678246e-01, 5.167941026230e-07, 4.7999e+01, 2.9135e-01, 
 2DIAGNOSTIC,    63, -5.044583678246e-01, 5.082261509415e-07, 4.8300e+01, 3.0097e-01, 
 2DIAGNOSTIC,    64, -5.044583678246e-01, 5.007026402382e-07, 4.8595e+01, 2.9497e-01, 
 2DIAGNOSTIC,    65, -5.044583678246e-01, 4.920315177515e-07, 4.8890e+01, 2.9532e-01, 
 2DIAGNOSTIC,    66, -5.044581890106e-01, 4.823639869755e-07, 4.9186e+01, 2.9585e-01, 
 2DIAGNOSTIC,    67, -5.044584274292e-01, 4.744372006371e-07, 4.9490e+01, 3.0465e-01, 
 2DIAGNOSTIC,    68, -5.044586062431e-01, 4.696793780568e-07, 4.9793e+01, 3.0231e-01, 
 2DIAGNOSTIC,    69, -5.044584274292e-01, 4.634134995740e-07, 5.0103e+01, 3.1021e-01, 
 2DIAGNOSTIC,    70, -5.044584870338e-01, 4.566640257053e-07, 5.0395e+01, 2.9246e-01, 
 2DIAGNOSTIC,    71, -5.044583082199e-01, 4.499123349433e-07, 5.0699e+01, 3.0332e-01, 
 2DIAGNOSTIC,    72, -5.044586062431e-01, 4.450236019693e-07, 5.0992e+01, 2.9340e-01, 
 2DIAGNOSTIC,    73, -5.044583678246e-01, 4.379962490475e-07, 5.1297e+01, 3.0480e-01, 
 2DIAGNOSTIC,    74, -5.044583082199e-01, 4.305752554501e-07, 5.1610e+01, 3.1263e-01, 
 2DIAGNOSTIC,    75, -5.044583678246e-01, 4.238438862103e-07, 5.1939e+01, 3.2933e-01, 
 2DIAGNOSTIC,    76, -5.044584274292e-01, 4.163433686699e-07, 5.2243e+01, 3.0429e-01, 
 2DIAGNOSTIC,    77, -5.044584870338e-01, 4.113460363442e-07, 5.2532e+01, 2.8876e-01, 
 2DIAGNOSTIC,    78, -5.044584870338e-01, 4.079832649495e-07, 5.2819e+01, 2.8711e-01, 
 2DIAGNOSTIC,    79, -5.044584870338e-01, 4.034459948343e-07, 5.3117e+01, 2.9778e-01, 
 2DIAGNOSTIC,    80, -5.044584870338e-01, 3.993998518581e-07, 5.3417e+01, 3.0009e-01, 
 2DIAGNOSTIC,    81, -5.044583678246e-01, 3.931131686841e-07, 5.3716e+01, 2.9864e-01, 
 2DIAGNOSTIC,    82, -5.044584274292e-01, 3.894625137946e-07, 5.4075e+01, 3.5933e-01, 
 2DIAGNOSTIC,    83, -5.044583678246e-01, 3.837289170860e-07, 5.4373e+01, 2.9829e-01, 
 2DIAGNOSTIC,    84, -5.044583678246e-01, 3.776893322538e-07, 5.4667e+01, 2.9341e-01, 
 2DIAGNOSTIC,    85, -5.044584274292e-01, 3.726770501089e-07, 5.4960e+01, 2.9321e-01, 
 2DIAGNOSTIC,    86, -5.044584870338e-01, 3.686960496907e-07, 5.5255e+01, 2.9515e-01, 
 2DIAGNOSTIC,    87, -5.044584870338e-01, 3.652990585579e-07, 5.5550e+01, 2.9475e-01, 
 2DIAGNOSTIC,    88, -5.044583678246e-01, 3.612518355567e-07, 5.5909e+01, 3.5951e-01, 
 2DIAGNOSTIC,    89, -5.044583678246e-01, 3.573423441594e-07, 5.6202e+01, 2.9289e-01, 
 2DIAGNOSTIC,    90, -5.044583678246e-01, 3.535300834301e-07, 5.6495e+01, 2.9278e-01, 
 2DIAGNOSTIC,    91, -5.044583678246e-01, 3.490207802770e-07, 5.6791e+01, 2.9634e-01, 
 2DIAGNOSTIC,    92, -5.044583678246e-01, 3.450446683928e-07, 5.7087e+01, 2.9566e-01, 
 2DIAGNOSTIC,    93, -5.044583678246e-01, 3.408848670006e-07, 5.7380e+01, 2.9315e-01, 
 2DIAGNOSTIC,    94, -5.044583678246e-01, 3.369225396455e-07, 5.7667e+01, 2.8733e-01, 
 2DIAGNOSTIC,    95, -5.044583678246e-01, 3.335189830977e-07, 5.7983e+01, 3.1523e-01, 
 2DIAGNOSTIC,    96, -5.044583678246e-01, 3.306559221983e-07, 5.8290e+01, 3.0707e-01, 
 2DIAGNOSTIC,    97, -5.044583678246e-01, 3.279394604760e-07, 5.8592e+01, 3.0227e-01, 
 2DIAGNOSTIC,    98, -5.044583678246e-01, 3.245931168294e-07, 5.8897e+01, 3.0550e-01, 
 2DIAGNOSTIC,    99, -5.044583678246e-01, 3.213143884295e-07, 5.9205e+01, 3.0766e-01, 
 2DIAGNOSTIC,   100, -5.044583678246e-01, 3.181012289133e-07, 5.9521e+01, 3.1546e-01, 
  Elapsed time (stage 0): 6.1753e+01


Stage 1
  iterations = 1000x500x250x100
  convergence threshold = 1.0000e-08
  convergence window size = 10
  number of levels = 4
  using the Mattes MI metric (number of bins = 32, weight = 1.0000e+00, use gradient filter = 0)
  preprocessing:  winsorizing the image intensities
  preprocessing:  histogram matching the images
  Shrink factors (level 1 out of 4): [8, 8, 8]
  Shrink factors (level 2 out of 4): [4, 4, 4]
  Shrink factors (level 3 out of 4): [2, 2, 2]
  Shrink factors (level 4 out of 4): [1, 1, 1]
  smoothing sigmas per level: [4, 2, 1, 0]
  regular sampling (percentage = 2.5000e-01)

*** Running AffineTransform registration ***

DIAGNOSTIC,Iteration,metricValue,convergenceValue,ITERATION_TIME_INDEX,SINCE_LAST
 2DIAGNOSTIC,     1, -8.725096583366e-01, inf, 2.7893e-01, 2.7893e-01, 
 2DIAGNOSTIC,     2, -8.738569021225e-01, inf, 2.8141e-01, 2.4819e-03, 
 2DIAGNOSTIC,     3, -8.758674263954e-01, inf, 2.8420e-01, 2.7809e-03, 
 2DIAGNOSTIC,     4, -8.790039420128e-01, inf, 2.8675e-01, 2.5542e-03, 
 2DIAGNOSTIC,     5, -8.843725323677e-01, inf, 2.8925e-01, 2.5010e-03, 
 2DIAGNOSTIC,     6, -8.939598202705e-01, inf, 2.9168e-01, 2.4309e-03, 
 2DIAGNOSTIC,     7, -9.083411097527e-01, inf, 2.9423e-01, 2.5439e-03, 
 2DIAGNOSTIC,     8, -9.179093837738e-01, inf, 2.9800e-01, 3.7739e-03, 
 2DIAGNOSTIC,     9, -9.210501313210e-01, inf, 3.0047e-01, 2.4719e-03, 
 2DIAGNOSTIC,    10, -9.223927855492e-01, 4.319400526583e-03, 3.0318e-01, 2.7039e-03, 
 2DIAGNOSTIC,    11, -9.249318838120e-01, 4.011637996882e-03, 3.0629e-01, 3.1099e-03, 
 2DIAGNOSTIC,    12, -9.295218586922e-01, 3.546176245436e-03, 3.1030e-01, 4.0140e-03, 
 2DIAGNOSTIC,    13, -9.304693341255e-01, 2.902496606112e-03, 3.1294e-01, 2.6379e-03, 
 2DIAGNOSTIC,    14, -9.326888918877e-01, 2.214238513261e-03, 3.1581e-01, 2.8751e-03, 
 2DIAGNOSTIC,    15, -9.331800937653e-01, 1.541964942589e-03, 3.1887e-01, 3.0551e-03, 
 2DIAGNOSTIC,    16, -9.335085749626e-01, 1.003438024782e-03, 3.2146e-01, 2.5890e-03, 
 2DIAGNOSTIC,    17, -9.343955516815e-01, 7.133852341212e-04, 3.2482e-01, 3.3638e-03, 
 2DIAGNOSTIC,    18, -9.347650408745e-01, 5.614188266918e-04, 3.2743e-01, 2.6059e-03, 
 2DIAGNOSTIC,    19, -9.349494576454e-01, 4.290417418815e-04, 3.3036e-01, 2.9311e-03, 
 2DIAGNOSTIC,    20, -9.350717663765e-01, 2.932374191005e-04, 3.3336e-01, 2.9991e-03, 
 2DIAGNOSTIC,    21, -9.351909756660e-01, 1.815212599467e-04, 3.3603e-01, 2.6760e-03, 
 2DIAGNOSTIC,    22, -9.352740049362e-01, 1.291993394261e-04, 3.3862e-01, 2.5861e-03, 
 2DIAGNOSTIC,    23, -9.354299902916e-01, 8.362906373804e-05, 3.4309e-01, 4.4711e-03, 
 2DIAGNOSTIC,    24, -9.354325532913e-01, 6.289203156484e-05, 3.4560e-01, 2.5151e-03, 
 2DIAGNOSTIC,    25, -9.354721903801e-01, 4.473501030589e-05, 3.4815e-01, 2.5442e-03, 
 2DIAGNOSTIC,    26, -9.355048537254e-01, 2.798508830892e-05, 3.5075e-01, 2.6000e-03, 
 2DIAGNOSTIC,    27, -9.355313181877e-01, 2.033461532847e-05, 3.5343e-01, 2.6820e-03, 
 2DIAGNOSTIC,    28, -9.355639219284e-01, 1.582297772984e-05, 3.5629e-01, 2.8579e-03, 
 2DIAGNOSTIC,    29, -9.355763792992e-01, 1.232268459717e-05, 3.5965e-01, 3.3569e-03, 
 2DIAGNOSTIC,    30, -9.355935454369e-01, 9.432977094548e-06, 3.6256e-01, 2.9190e-03, 
 2DIAGNOSTIC,    31, -9.355970025063e-01, 7.151974386943e-06, 3.6514e-01, 2.5709e-03, 
 2DIAGNOSTIC,    32, -9.356651306152e-01, 5.853037237102e-06, 3.6800e-01, 2.8651e-03, 
 2DIAGNOSTIC,    33, -9.356802701950e-01, 5.759809937445e-06, 3.7055e-01, 2.5511e-03, 
 2DIAGNOSTIC,    34, -9.356919527054e-01, 5.345014415070e-06, 3.7347e-01, 2.9159e-03, 
 2DIAGNOSTIC,    35, -9.357345700264e-01, 5.264903393254e-06, 3.7603e-01, 2.5620e-03, 
 2DIAGNOSTIC,    36, -9.358580708504e-01, 6.099770871515e-06, 3.7981e-01, 3.7839e-03, 
 2DIAGNOSTIC,    37, -9.359132647514e-01, 7.034963346086e-06, 3.8330e-01, 3.4871e-03, 
 2DIAGNOSTIC,    38, -9.358874559402e-01, 7.388086942228e-06, 3.8747e-01, 4.1728e-03, 
 2DIAGNOSTIC,    39, -9.358952641487e-01, 7.288383585546e-06, 3.9103e-01, 3.5560e-03, 
 2DIAGNOSTIC,    40, -9.358971714973e-01, 6.724974355166e-06, 3.9508e-01, 4.0519e-03, 
 2DIAGNOSTIC,    41, -9.359337091446e-01, 5.891257842450e-06, 3.9960e-01, 4.5161e-03, 
 2DIAGNOSTIC,    42, -9.359053373337e-01, 4.887975592283e-06, 4.0366e-01, 4.0629e-03, 
 2DIAGNOSTIC,    43, -9.359062910080e-01, 3.679375367938e-06, 4.0771e-01, 4.0450e-03, 
 2DIAGNOSTIC,    44, -9.359080195427e-01, 2.349207989027e-06, 4.1175e-01, 4.0419e-03, 
 2DIAGNOSTIC,    45, -9.359096288681e-01, 1.198486188514e-06, 4.1532e-01, 3.5722e-03, 
 2DIAGNOSTIC,    46, -9.359097480774e-01, 8.614640023552e-07, 4.1925e-01, 3.9332e-03, 
 2DIAGNOSTIC,    47, -9.359148740768e-01, 9.252805739379e-07, 4.2295e-01, 3.6938e-03, 
 2DIAGNOSTIC,    48, -9.359179735184e-01, 8.204619916796e-07, 4.2695e-01, 4.0059e-03, 
 2DIAGNOSTIC,    49, -9.359532594681e-01, 9.743312148203e-07, 4.3213e-01, 5.1770e-03, 
 2DIAGNOSTIC,    50, -9.359263777733e-01, 9.242083365280e-07, 4.3610e-01, 3.9659e-03, 
 2DIAGNOSTIC,    51, -9.359275102615e-01, 1.087937562261e-06, 4.3958e-01, 3.4859e-03, 
 2DIAGNOSTIC,    52, -9.359295368195e-01, 1.046890133694e-06, 4.4309e-01, 3.5081e-03, 
 2DIAGNOSTIC,    53, -9.359334707260e-01, 9.903263844535e-07, 4.4809e-01, 4.9999e-03, 
 2DIAGNOSTIC,    54, -9.359344840050e-01, 9.114733074966e-07, 4.5211e-01, 4.0200e-03, 
 2DIAGNOSTIC,    55, -9.359368681908e-01, 8.299658134092e-07, 4.5618e-01, 4.0729e-03, 
 2DIAGNOSTIC,    56, -9.359376430511e-01, 7.356097739830e-07, 4.6021e-01, 4.0288e-03, 
 2DIAGNOSTIC,    57, -9.359394311905e-01, 6.654065032308e-07, 4.6418e-01, 3.9740e-03, 
 2DIAGNOSTIC,    58, -9.359403848648e-01, 6.018021281307e-07, 4.6783e-01, 3.6500e-03, 
 2DIAGNOSTIC,    59, -9.359430074692e-01, 7.364735097326e-07, 4.7126e-01, 3.4230e-03, 
 2DIAGNOSTIC,    60, -9.359466433525e-01, 7.293374437722e-07, 4.7528e-01, 4.0190e-03, 
 2DIAGNOSTIC,    61, -9.359489679337e-01, 7.206380701064e-07, 4.8030e-01, 5.0249e-03, 
 2DIAGNOSTIC,    62, -9.359502196312e-01, 7.092538680809e-07, 4.8476e-01, 4.4549e-03, 
 2DIAGNOSTIC,    63, -9.359508752823e-01, 7.021831152088e-07, 4.8874e-01, 3.9849e-03, 
 2DIAGNOSTIC,    64, -9.359523057938e-01, 6.881297736072e-07, 4.9279e-01, 4.0519e-03, 
 2DIAGNOSTIC,    65, -9.359532594681e-01, 6.718191798427e-07, 4.9687e-01, 4.0791e-03, 
 2DIAGNOSTIC,    66, -9.359536767006e-01, 6.440629931603e-07, 5.0034e-01, 3.4671e-03, 
 2DIAGNOSTIC,    67, -9.359530806541e-01, 6.075572400732e-07, 5.0380e-01, 3.4640e-03, 
 2DIAGNOSTIC,    68, -9.359555244446e-01, 5.750538321081e-07, 5.0731e-01, 3.5110e-03, 
 2DIAGNOSTIC,    69, -9.359575510025e-01, 5.533962621485e-07, 5.1078e-01, 3.4659e-03, 
 2DIAGNOSTIC,    70, -9.359833002090e-01, 6.516789881061e-07, 5.1422e-01, 3.4389e-03, 
 2DIAGNOSTIC,    71, -9.359883666039e-01, 7.573357265755e-07, 5.1827e-01, 4.0491e-03, 
 2DIAGNOSTIC,    72, -9.359925985336e-01, 8.546846856916e-07, 5.2226e-01, 3.9911e-03, 
 2DIAGNOSTIC,    73, -9.359879493713e-01, 8.943035822995e-07, 5.2830e-01, 6.0360e-03, 
 2DIAGNOSTIC,    74, -9.359934329987e-01, 9.178304480884e-07, 5.3236e-01, 4.0650e-03, 
 2DIAGNOSTIC,    75, -9.359948635101e-01, 9.012461532620e-07, 5.3640e-01, 4.0371e-03, 
 2DIAGNOSTIC,    76, -9.359959363937e-01, 8.446291985820e-07, 5.4040e-01, 3.9971e-03, 
 2DIAGNOSTIC,    77, -9.359959363937e-01, 7.477530061806e-07, 5.4389e-01, 3.4959e-03, 
 2DIAGNOSTIC,    78, -9.359965920448e-01, 6.350800845212e-07, 5.4786e-01, 3.9740e-03, 
 2DIAGNOSTIC,    79, -9.359971284866e-01, 5.108223604111e-07, 5.5179e-01, 3.9248e-03, 
 2DIAGNOSTIC,    80, -9.359975457191e-01, 4.785457008438e-07, 5.5636e-01, 4.5719e-03, 
 2DIAGNOSTIC,    81, -9.359971284866e-01, 4.566226721181e-07, 5.6089e-01, 4.5300e-03, 
 2DIAGNOSTIC,    82, -9.359977841377e-01, 4.484012663397e-07, 5.6545e-01, 4.5581e-03, 
 2DIAGNOSTIC,    83, -9.359976053238e-01, 4.164313907040e-07, 5.7093e-01, 5.4839e-03, 
 2DIAGNOSTIC,    84, -9.359977841377e-01, 4.027006070828e-07, 5.7483e-01, 3.9010e-03, 
 2DIAGNOSTIC,    85, -9.359974861145e-01, 3.911700048320e-07, 5.7931e-01, 4.4720e-03, 
 2DIAGNOSTIC,    86, -9.359978437424e-01, 3.836576070171e-07, 5.8343e-01, 4.1220e-03, 
 2DIAGNOSTIC,    87, -9.359977245331e-01, 3.746841059638e-07, 5.8745e-01, 4.0171e-03, 
 2DIAGNOSTIC,    88, -9.359979033470e-01, 3.680849545162e-07, 5.9139e-01, 3.9470e-03, 
 2DIAGNOSTIC,    89, -9.359976649284e-01, 3.621848350122e-07, 5.9541e-01, 4.0131e-03, 
 2DIAGNOSTIC,    90, -9.359975457191e-01, 3.572482398795e-07, 5.9953e-01, 4.1220e-03, 
 2DIAGNOSTIC,    91, -9.359977245331e-01, 3.513752631079e-07, 6.0506e-01, 5.5361e-03, 
 2DIAGNOSTIC,    92, -9.359975457191e-01, 3.471928664567e-07, 6.0904e-01, 3.9740e-03, 
 2DIAGNOSTIC,    93, -9.359976649284e-01, 3.429474304539e-07, 6.1304e-01, 4.0059e-03, 
 2DIAGNOSTIC,    94, -9.359975457191e-01, 3.391124892005e-07, 6.1709e-01, 4.0441e-03, 
 2DIAGNOSTIC,    95, -9.359972476959e-01, 3.335312044328e-07, 6.2049e-01, 3.4070e-03, 
 2DIAGNOSTIC,    96, -9.359971284866e-01, 3.291468999578e-07, 6.2449e-01, 3.9959e-03, 
 2DIAGNOSTIC,    97, -9.359970092773e-01, 3.244487345455e-07, 6.2843e-01, 3.9430e-03, 
 2DIAGNOSTIC,    98, -9.359970688820e-01, 3.211017087779e-07, 6.3243e-01, 3.9980e-03, 
 2DIAGNOSTIC,    99, -9.359967708588e-01, 3.166650515141e-07, 6.3649e-01, 4.0581e-03, 
 2DIAGNOSTIC,   100, -9.359972476959e-01, 3.140368676213e-07, 6.3995e-01, 3.4602e-03, 
 2DIAGNOSTIC,   101, -9.359980225563e-01, 3.148619498461e-07, 6.4411e-01, 4.1621e-03, 
 2DIAGNOSTIC,   102, -9.359972476959e-01, 3.128888010906e-07, 6.4817e-01, 4.0619e-03, 
 2DIAGNOSTIC,   103, -9.359975457191e-01, 3.123473391042e-07, 6.5276e-01, 4.5850e-03, 
 2DIAGNOSTIC,   104, -9.359974265099e-01, 3.109276747182e-07, 6.5684e-01, 4.0770e-03, 
 2DIAGNOSTIC,   105, -9.359971284866e-01, 3.074162577832e-07, 6.6047e-01, 3.6330e-03, 
 2DIAGNOSTIC,   106, -9.359975457191e-01, 3.045313974326e-07, 6.6438e-01, 3.9089e-03, 
 2DIAGNOSTIC,   107, -9.359976053238e-01, 3.012181934992e-07, 6.6940e-01, 5.0209e-03, 
 2DIAGNOSTIC,   108, -9.359975457191e-01, 2.977848794217e-07, 6.7343e-01, 4.0319e-03, 
 2DIAGNOSTIC,   109, -9.359975457191e-01, 2.933795144600e-07, 6.7760e-01, 4.1649e-03, 
 2DIAGNOSTIC,   110, -9.359974861145e-01, 2.901263371768e-07, 6.8262e-01, 5.0251e-03, 
 2DIAGNOSTIC,   111, -9.359974861145e-01, 2.891450492370e-07, 6.8668e-01, 4.0638e-03, 
 2DIAGNOSTIC,   112, -9.359974861145e-01, 2.858962204755e-07, 6.9082e-01, 4.1370e-03, 
 2DIAGNOSTIC,   113, -9.359974861145e-01, 2.834651127159e-07, 6.9491e-01, 4.0860e-03, 
 2DIAGNOSTIC,   114, -9.359974265099e-01, 2.805668373185e-07, 6.9903e-01, 4.1180e-03, 
 2DIAGNOSTIC,   115, -9.359974265099e-01, 2.768713613932e-07, 7.0311e-01, 4.0860e-03, 
 2DIAGNOSTIC,   116, -9.359974861145e-01, 2.745744041022e-07, 7.0719e-01, 4.0810e-03, 
 2DIAGNOSTIC,   117, -9.359974861145e-01, 2.725454066876e-07, 7.1127e-01, 4.0810e-03, 
 2DIAGNOSTIC,   118, -9.359974861145e-01, 2.704433654799e-07, 7.1528e-01, 4.0059e-03, 
 2DIAGNOSTIC,   119, -9.359974861145e-01, 2.684106163997e-07, 7.1935e-01, 4.0720e-03, 
 2DIAGNOSTIC,   120, -9.359974861145e-01, 2.662604288162e-07, 7.2333e-01, 3.9799e-03, 
 2DIAGNOSTIC,   121, -9.359974861145e-01, 2.641316712015e-07, 7.2738e-01, 4.0479e-03, 
 2DIAGNOSTIC,   122, -9.359974861145e-01, 2.620185455271e-07, 7.3090e-01, 3.5231e-03, 
 2DIAGNOSTIC,   123, -9.359974265099e-01, 2.597761010747e-07, 7.3498e-01, 4.0789e-03, 
 2DIAGNOSTIC,   124, -9.359974265099e-01, 2.574168433966e-07, 7.3910e-01, 4.1208e-03, 
 2DIAGNOSTIC,   125, -9.359974265099e-01, 2.551020088504e-07, 7.4318e-01, 4.0801e-03, 
 2DIAGNOSTIC,   126, -9.359974265099e-01, 2.530022129577e-07, 7.4726e-01, 4.0770e-03, 
 2DIAGNOSTIC,   127, -9.359975457191e-01, 2.512648507036e-07, 7.5137e-01, 4.1158e-03, 
 2DIAGNOSTIC,   128, -9.359975457191e-01, 2.495657724921e-07, 7.5554e-01, 4.1630e-03, 
 2DIAGNOSTIC,   129, -9.359976649284e-01, 2.481690160039e-07, 7.5965e-01, 4.1170e-03, 
 2DIAGNOSTIC,   130, -9.359976649284e-01, 2.467255626470e-07, 7.6372e-01, 4.0672e-03, 
 2DIAGNOSTIC,   131, -9.359977245331e-01, 2.453355705256e-07, 7.6780e-01, 4.0760e-03, 
 2DIAGNOSTIC,   132, -9.359979033470e-01, 2.442236848310e-07, 7.7185e-01, 4.0469e-03, 
 2DIAGNOSTIC,   133, -9.359978437424e-01, 2.426156413549e-07, 7.7593e-01, 4.0801e-03, 
 2DIAGNOSTIC,   134, -9.359978437424e-01, 2.407936960935e-07, 7.7996e-01, 4.0381e-03, 
 2DIAGNOSTIC,   135, -9.359978437424e-01, 2.387590711805e-07, 7.8407e-01, 4.1070e-03, 
 2DIAGNOSTIC,   136, -9.359977245331e-01, 2.362571933645e-07, 7.8809e-01, 4.0200e-03, 
 2DIAGNOSTIC,   137, -9.359977841377e-01, 2.340463112205e-07, 7.9235e-01, 4.2570e-03, 
 2DIAGNOSTIC,   138, -9.359977245331e-01, 2.316246252576e-07, 7.9652e-01, 4.1730e-03, 
 2DIAGNOSTIC,   139, -9.359977245331e-01, 2.294795962143e-07, 8.0060e-01, 4.0751e-03, 
 2DIAGNOSTIC,   140, -9.359976649284e-01, 2.272529684433e-07, 8.0463e-01, 4.0371e-03, 
 2DIAGNOSTIC,   141, -9.359976053238e-01, 2.251241966178e-07, 8.0873e-01, 4.1020e-03, 
 2DIAGNOSTIC,   142, -9.359976053238e-01, 2.235367730918e-07, 8.1279e-01, 4.0541e-03, 
 2DIAGNOSTIC,   143, -9.359976053238e-01, 2.219598798092e-07, 8.1698e-01, 4.1909e-03, 
 2DIAGNOSTIC,   144, -9.359976053238e-01, 2.205241429465e-07, 8.2127e-01, 4.2882e-03, 
 2DIAGNOSTIC,   145, -9.359976053238e-01, 2.192271892909e-07, 8.2538e-01, 4.1080e-03, 
 2DIAGNOSTIC,   146, -9.359976053238e-01, 2.177834659278e-07, 8.2956e-01, 4.1890e-03, 
 2DIAGNOSTIC,   147, -9.359976053238e-01, 2.165649419794e-07, 8.3360e-01, 4.0371e-03, 
 2DIAGNOSTIC,   148, -9.359976053238e-01, 2.152901714680e-07, 8.3777e-01, 4.1690e-03, 
 2DIAGNOSTIC,   149, -9.359976053238e-01, 2.140688337704e-07, 8.4202e-01, 4.2481e-03, 
 2DIAGNOSTIC,   150, -9.359974861145e-01, 2.125160136757e-07, 8.4613e-01, 4.1139e-03, 
 2DIAGNOSTIC,   151, -9.359974861145e-01, 2.108939867185e-07, 8.5019e-01, 4.0560e-03, 
 2DIAGNOSTIC,   152, -9.359974861145e-01, 2.093342601484e-07, 8.5419e-01, 4.0028e-03, 
 2DIAGNOSTIC,   153, -9.359974861145e-01, 2.078509169223e-07, 8.5820e-01, 4.0100e-03, 
 2DIAGNOSTIC,   154, -9.359974265099e-01, 2.063400756924e-07, 8.6222e-01, 4.0219e-03, 
 2DIAGNOSTIC,   155, -9.359973669052e-01, 2.048239196029e-07, 8.6632e-01, 4.1008e-03, 
 2DIAGNOSTIC,   156, -9.359973669052e-01, 2.034320374378e-07, 8.7044e-01, 4.1130e-03, 
 2DIAGNOSTIC,   157, -9.359973669052e-01, 2.021594980306e-07, 8.7444e-01, 4.0059e-03, 
 2DIAGNOSTIC,   158, -9.359973669052e-01, 2.010041555423e-07, 8.7852e-01, 4.0720e-03, 
 2DIAGNOSTIC,   159, -9.359973669052e-01, 1.999644467787e-07, 8.8256e-01, 4.0450e-03, 
 2DIAGNOSTIC,   160, -9.359973669052e-01, 1.987825442029e-07, 8.8663e-01, 4.0660e-03, 
 2DIAGNOSTIC,   161, -9.359973669052e-01, 1.976759307354e-07, 8.9069e-01, 4.0681e-03, 
 2DIAGNOSTIC,   162, -9.359973669052e-01, 1.966286049537e-07, 8.9473e-01, 4.0362e-03, 
 2DIAGNOSTIC,   163, -9.359974265099e-01, 1.957386785989e-07, 8.9885e-01, 4.1189e-03, 
 2DIAGNOSTIC,   164, -9.359974265099e-01, 1.947489636223e-07, 9.0297e-01, 4.1199e-03, 
 2DIAGNOSTIC,   165, -9.359974265099e-01, 1.936424354199e-07, 9.0701e-01, 4.0419e-03, 
 2DIAGNOSTIC,   166, -9.359974265099e-01, 1.925235153521e-07, 9.1108e-01, 4.0720e-03, 
 2DIAGNOSTIC,   167, -9.359974265099e-01, 1.913852685220e-07, 9.1512e-01, 4.0331e-03, 
 2DIAGNOSTIC,   168, -9.359974265099e-01, 1.902248953911e-07, 9.1926e-01, 4.1389e-03, 
 2DIAGNOSTIC,   169, -9.359974265099e-01, 1.890459202514e-07, 9.2325e-01, 3.9990e-03, 
 2DIAGNOSTIC,   170, -9.359974265099e-01, 1.878557043256e-07, 9.2728e-01, 4.0300e-03, 
 2DIAGNOSTIC,   171, -9.359973669052e-01, 1.865551411129e-07, 9.3137e-01, 4.0851e-03, 
 2DIAGNOSTIC,   172, -9.359973669052e-01, 1.852697266713e-07, 9.3553e-01, 4.1649e-03, 
 2DIAGNOSTIC,   173, -9.359973669052e-01, 1.841220864662e-07, 9.3955e-01, 4.0159e-03, 
 2DIAGNOSTIC,   174, -9.359973669052e-01, 1.830122613455e-07, 9.4354e-01, 3.9921e-03, 
 2DIAGNOSTIC,   175, -9.359973669052e-01, 1.819464046093e-07, 9.4744e-01, 3.9010e-03, 
 2DIAGNOSTIC,   176, -9.359973669052e-01, 1.809267899944e-07, 9.5150e-01, 4.0581e-03, 
 2DIAGNOSTIC,   177, -9.359973073006e-01, 1.798471060965e-07, 9.5559e-01, 4.0851e-03, 
 2DIAGNOSTIC,   178, -9.359973073006e-01, 1.788164922800e-07, 9.5967e-01, 4.0789e-03, 
 2DIAGNOSTIC,   179, -9.359973073006e-01, 1.778321347956e-07, 9.6360e-01, 3.9301e-03, 
 2DIAGNOSTIC,   180, -9.359973073006e-01, 1.768952699877e-07, 9.6770e-01, 4.1008e-03, 
 2DIAGNOSTIC,   181, -9.359973073006e-01, 1.758987195899e-07, 9.7172e-01, 4.0281e-03, 
 2DIAGNOSTIC,   182, -9.359971880913e-01, 1.747467166524e-07, 9.7583e-01, 4.1099e-03, 
 2DIAGNOSTIC,   183, -9.359971880913e-01, 1.736623005399e-07, 9.7994e-01, 4.1070e-03, 
 2DIAGNOSTIC,   184, -9.359971880913e-01, 1.726466933860e-07, 9.8392e-01, 3.9768e-03, 
 2DIAGNOSTIC,   185, -9.359971880913e-01, 1.717051389960e-07, 9.8792e-01, 4.0071e-03, 
 2DIAGNOSTIC,   186, -9.359971880913e-01, 1.708448564841e-07, 9.9197e-01, 4.0429e-03, 
 2DIAGNOSTIC,   187, -9.359973073006e-01, 1.701550047528e-07, 9.9592e-01, 3.9570e-03, 
 2DIAGNOSTIC,   188, -9.359973073006e-01, 1.695062934459e-07, 9.9998e-01, 4.0581e-03, 
 2DIAGNOSTIC,   189, -9.359973073006e-01, 1.688768236363e-07, 1.0041e+00, 4.0822e-03, 
 2DIAGNOSTIC,   190, -9.359973073006e-01, 1.682416979065e-07, 1.0081e+00, 4.0350e-03, 
 2DIAGNOSTIC,   191, -9.359973073006e-01, 1.675799978784e-07, 1.0121e+00, 3.9511e-03, 
 2DIAGNOSTIC,   192, -9.359973073006e-01, 1.666737290407e-07, 1.0161e+00, 4.0412e-03, 
 2DIAGNOSTIC,   193, -9.359973073006e-01, 1.657201949001e-07, 1.0202e+00, 4.0870e-03, 
 2DIAGNOSTIC,   194, -9.359973073006e-01, 1.647324410214e-07, 1.0243e+00, 4.0870e-03, 
 2DIAGNOSTIC,   195, -9.359973073006e-01, 1.637229871676e-07, 1.0283e+00, 3.9871e-03, 
 2DIAGNOSTIC,   196, -9.359973073006e-01, 1.627004451166e-07, 1.0321e+00, 3.8960e-03, 
 2DIAGNOSTIC,   197, -9.359973073006e-01, 1.618725065100e-07, 1.0363e+00, 4.1950e-03, 
 2DIAGNOSTIC,   198, -9.359973073006e-01, 1.610529523077e-07, 1.0404e+00, 4.0498e-03, 
 2DIAGNOSTIC,   199, -9.359973073006e-01, 1.602416546120e-07, 1.0443e+00, 3.9501e-03, 
 2DIAGNOSTIC,   200, -9.359973073006e-01, 1.594384855252e-07, 1.0484e+00, 4.0121e-03, 
 2DIAGNOSTIC,   201, -9.359973073006e-01, 1.586433313605e-07, 1.0524e+00, 4.0410e-03, 
 2DIAGNOSTIC,   202, -9.359973073006e-01, 1.578560642201e-07, 1.0564e+00, 4.0271e-03, 
 2DIAGNOSTIC,   203, -9.359973073006e-01, 1.570765704173e-07, 1.0605e+00, 4.0712e-03, 
 2DIAGNOSTIC,   204, -9.359973073006e-01, 1.563047504760e-07, 1.0646e+00, 4.0641e-03, 
 2DIAGNOSTIC,   205, -9.359973073006e-01, 1.555404622877e-07, 1.0686e+00, 4.0479e-03, 
 2DIAGNOSTIC,   206, -9.359974265099e-01, 1.549597499206e-07, 1.0726e+00, 3.9670e-03, 
 2DIAGNOSTIC,   207, -9.359974265099e-01, 1.543624961187e-07, 1.0766e+00, 4.0011e-03, 
 2DIAGNOSTIC,   208, -9.359974265099e-01, 1.537411407071e-07, 1.0806e+00, 4.0741e-03, 
 2DIAGNOSTIC,   209, -9.359974265099e-01, 1.530848265929e-07, 1.0847e+00, 4.0958e-03, 
 2DIAGNOSTIC,   210, -9.359974265099e-01, 1.523827251049e-07, 1.0887e+00, 3.9160e-03, 
 2DIAGNOSTIC,   211, -9.359974265099e-01, 1.516304308780e-07, 1.0927e+00, 4.0829e-03, 
 2DIAGNOSTIC,   212, -9.359974265099e-01, 1.508336850975e-07, 1.0968e+00, 4.0638e-03, 
 2DIAGNOSTIC,   213, -9.359974265099e-01, 1.500042969838e-07, 1.1009e+00, 4.0820e-03, 
 2DIAGNOSTIC,   214, -9.359974265099e-01, 1.491536494314e-07, 1.1051e+00, 4.1661e-03, 
 2DIAGNOSTIC,   215, -9.359974265099e-01, 1.482895868321e-07, 1.1091e+00, 4.0150e-03, 
 2DIAGNOSTIC,   216, -9.359974265099e-01, 1.476015114577e-07, 1.1131e+00, 4.0078e-03, 
 2DIAGNOSTIC,   217, -9.359974265099e-01, 1.469197883353e-07, 1.1171e+00, 3.9871e-03, 
 2DIAGNOSTIC,   218, -9.359974265099e-01, 1.462443321998e-07, 1.1211e+00, 4.0281e-03, 
 2DIAGNOSTIC,   219, -9.359974265099e-01, 1.455750577861e-07, 1.1251e+00, 4.0519e-03, 
 2DIAGNOSTIC,   220, -9.359974265099e-01, 1.449118798291e-07, 1.1295e+00, 4.3590e-03, 
 2DIAGNOSTIC,   221, -9.359974265099e-01, 1.442547272745e-07, 1.1335e+00, 3.9699e-03, 
 2DIAGNOSTIC,   222, -9.359973669052e-01, 1.435217882317e-07, 1.1376e+00, 4.1161e-03, 
 2DIAGNOSTIC,   223, -9.359973669052e-01, 1.428057316843e-07, 1.1415e+00, 3.9442e-03, 
 2DIAGNOSTIC,   224, -9.359973669052e-01, 1.421099398158e-07, 1.1455e+00, 4.0030e-03, 
 2DIAGNOSTIC,   225, -9.359973669052e-01, 1.414393580035e-07, 1.1495e+00, 3.9260e-03, 
 2DIAGNOSTIC,   226, -9.359973073006e-01, 1.407186402957e-07, 1.1535e+00, 4.0262e-03, 
 2DIAGNOSTIC,   227, -9.359972476959e-01, 1.399609175223e-07, 1.1576e+00, 4.0979e-03, 
 2DIAGNOSTIC,   228, -9.359972476959e-01, 1.392574944248e-07, 1.1616e+00, 4.0231e-03, 
 2DIAGNOSTIC,   229, -9.359972476959e-01, 1.386111136981e-07, 1.1655e+00, 3.8998e-03, 
 2DIAGNOSTIC,   230, -9.359972476959e-01, 1.380262233397e-07, 1.1696e+00, 4.0600e-03, 
 2DIAGNOSTIC,   231, -9.359972476959e-01, 1.375059497377e-07, 1.1735e+00, 3.9270e-03, 
 2DIAGNOSTIC,   232, -9.359972476959e-01, 1.369614039959e-07, 1.1775e+00, 3.9990e-03, 
 2DIAGNOSTIC,   233, -9.359973669052e-01, 1.366190218732e-07, 1.1816e+00, 4.1220e-03, 
 2DIAGNOSTIC,   234, -9.359973669052e-01, 1.362915043046e-07, 1.1857e+00, 4.1151e-03, 
 2DIAGNOSTIC,   235, -9.359973073006e-01, 1.358861680956e-07, 1.1898e+00, 4.0329e-03, 
 2DIAGNOSTIC,   236, -9.359973073006e-01, 1.353906213808e-07, 1.1937e+00, 3.9670e-03, 
 2DIAGNOSTIC,   237, -9.359973073006e-01, 1.347897438109e-07, 1.1978e+00, 4.0460e-03, 
 2DIAGNOSTIC,   238, -9.359973073006e-01, 1.341614819239e-07, 1.2018e+00, 4.0619e-03, 
 2DIAGNOSTIC,   239, -9.359973073006e-01, 1.335156127880e-07, 1.2059e+00, 4.0362e-03, 
 2DIAGNOSTIC,   240, -9.359973073006e-01, 1.328645140575e-07, 1.2099e+00, 4.0240e-03, 
 2DIAGNOSTIC,   241, -9.359973073006e-01, 1.322157459072e-07, 1.2139e+00, 4.0350e-03, 
 2DIAGNOSTIC,   242, -9.359973073006e-01, 1.315710562722e-07, 1.2179e+00, 3.9661e-03, 
 2DIAGNOSTIC,   243, -9.359973073006e-01, 1.310937136623e-07, 1.2221e+00, 4.1599e-03, 
 2DIAGNOSTIC,   244, -9.359973073006e-01, 1.306296866233e-07, 1.2261e+00, 4.0848e-03, 
 2DIAGNOSTIC,   245, -9.359972476959e-01, 1.300214194089e-07, 1.2301e+00, 3.9830e-03, 
 2DIAGNOSTIC,   246, -9.359972476959e-01, 1.294274341035e-07, 1.2341e+00, 4.0050e-03, 
 2DIAGNOSTIC,   247, -9.359972476959e-01, 1.288508286734e-07, 1.2381e+00, 4.0030e-03, 
 2DIAGNOSTIC,   248, -9.359972476959e-01, 1.282961221705e-07, 1.2422e+00, 4.0390e-03, 
 2DIAGNOSTIC,   249, -9.359972476959e-01, 1.277678336464e-07, 1.2463e+00, 4.1020e-03, 
 2DIAGNOSTIC,   250, -9.359972476959e-01, 1.272677536690e-07, 1.2503e+00, 4.0472e-03, 
 2DIAGNOSTIC,   251, -9.359972476959e-01, 1.267934379712e-07, 1.2545e+00, 4.1251e-03, 
 2DIAGNOSTIC,   252, -9.359972476959e-01, 1.263398416995e-07, 1.2585e+00, 4.0848e-03, 
 2DIAGNOSTIC,   253, -9.359972476959e-01, 1.259021189526e-07, 1.2626e+00, 4.0870e-03, 
 2DIAGNOSTIC,   254, -9.359972476959e-01, 1.254768875469e-07, 1.2667e+00, 4.1080e-03, 
 2DIAGNOSTIC,   255, -9.359972476959e-01, 1.249838703643e-07, 1.2709e+00, 4.1509e-03, 
 2DIAGNOSTIC,   256, -9.359972476959e-01, 1.244947185342e-07, 1.2748e+00, 3.9189e-03, 
 2DIAGNOSTIC,   257, -9.359972476959e-01, 1.240093894239e-07, 1.2788e+00, 3.9721e-03, 
 2DIAGNOSTIC,   258, -9.359972476959e-01, 1.235278119793e-07, 1.2829e+00, 4.1230e-03, 
 2DIAGNOSTIC,   259, -9.359972476959e-01, 1.230499719895e-07, 1.2870e+00, 4.0781e-03, 
 2DIAGNOSTIC,   260, -9.359972476959e-01, 1.225758126111e-07, 1.2909e+00, 3.9618e-03, 
 2DIAGNOSTIC,   261, -9.359972476959e-01, 1.221053054223e-07, 1.2949e+00, 3.9961e-03, 
 2DIAGNOSTIC,   262, -9.359972476959e-01, 1.216383793690e-07, 1.2990e+00, 4.0522e-03, 
 2DIAGNOSTIC,   263, -9.359972476959e-01, 1.211750202401e-07, 1.3030e+00, 3.9692e-03, 
 2DIAGNOSTIC,   264, -9.359972476959e-01, 1.207151711924e-07, 1.3069e+00, 3.9241e-03, 
 2DIAGNOSTIC,   265, -9.359972476959e-01, 1.202588038041e-07, 1.3109e+00, 3.9811e-03, 
 2DIAGNOSTIC,   266, -9.359974265099e-01, 1.200103554311e-07, 1.3148e+00, 3.9139e-03, 
 2DIAGNOSTIC,   267, -9.359974265099e-01, 1.197380186113e-07, 1.3189e+00, 4.1499e-03, 
 2DIAGNOSTIC,   268, -9.359974265099e-01, 1.194329826149e-07, 1.3231e+00, 4.1299e-03, 
 2DIAGNOSTIC,   269, -9.359974265099e-01, 1.190825571484e-07, 1.3272e+00, 4.1101e-03, 
 2DIAGNOSTIC,   270, -9.359974265099e-01, 1.186740163917e-07, 1.3312e+00, 4.0629e-03, 
 2DIAGNOSTIC,   271, -9.359974265099e-01, 1.182021378554e-07, 1.3351e+00, 3.9141e-03, 
 2DIAGNOSTIC,   272, -9.359974265099e-01, 1.176734656383e-07, 1.3391e+00, 3.9389e-03, 
 2DIAGNOSTIC,   273, -9.359974265099e-01, 1.171017274260e-07, 1.3431e+00, 4.0359e-03, 
 2DIAGNOSTIC,   274, -9.359974265099e-01, 1.165001890513e-07, 1.3472e+00, 4.0991e-03, 
 2DIAGNOSTIC,   275, -9.359974265099e-01, 1.158780094102e-07, 1.3516e+00, 4.4088e-03, 
 2DIAGNOSTIC,   276, -9.359974265099e-01, 1.154574178486e-07, 1.3555e+00, 3.9170e-03, 
 2DIAGNOSTIC,   277, -9.359974265099e-01, 1.150398674099e-07, 1.3595e+00, 3.9601e-03, 
 2DIAGNOSTIC,   278, -9.359974265099e-01, 1.146253225670e-07, 1.3634e+00, 3.8710e-03, 
 2DIAGNOSTIC,   279, -9.359974265099e-01, 1.142137620036e-07, 1.3674e+00, 4.0140e-03, 
 2DIAGNOSTIC,   280, -9.359974265099e-01, 1.138051430871e-07, 1.3714e+00, 4.0290e-03, 
 2DIAGNOSTIC,   281, -9.359974265099e-01, 1.133994373959e-07, 1.3754e+00, 3.9911e-03, 
 2DIAGNOSTIC,   282, -9.359974265099e-01, 1.129966165081e-07, 1.3794e+00, 4.0300e-03, 
 2DIAGNOSTIC,   283, -9.359974265099e-01, 1.125966448967e-07, 1.3833e+00, 3.8710e-03, 
 2DIAGNOSTIC,   284, -9.359974265099e-01, 1.121994941400e-07, 1.3872e+00, 3.9060e-03, 
 2DIAGNOSTIC,   285, -9.359974265099e-01, 1.118051429216e-07, 1.3912e+00, 3.9840e-03, 
 2DIAGNOSTIC,   286, -9.359974265099e-01, 1.114135415037e-07, 1.3954e+00, 4.1871e-03, 
 2DIAGNOSTIC,   287, -9.359974265099e-01, 1.110246827807e-07, 1.3995e+00, 4.1280e-03, 
 2DIAGNOSTIC,   288, -9.359974265099e-01, 1.106385241201e-07, 1.4036e+00, 4.0660e-03, 
 2DIAGNOSTIC,   289, -9.359974265099e-01, 1.102550442056e-07, 1.4075e+00, 3.9332e-03, 
 2DIAGNOSTIC,   290, -9.359974265099e-01, 1.098742146155e-07, 1.4115e+00, 4.0090e-03, 
 2DIAGNOSTIC,   291, -9.359974265099e-01, 1.094960069281e-07, 1.4154e+00, 3.8459e-03, 
 2DIAGNOSTIC,   292, -9.359974265099e-01, 1.091203927217e-07, 1.4194e+00, 4.0231e-03, 
 2DIAGNOSTIC,   293, -9.359974265099e-01, 1.087473506800e-07, 1.4234e+00, 4.0262e-03, 
 2DIAGNOSTIC,   294, -9.359974265099e-01, 1.083768452759e-07, 1.4273e+00, 3.8922e-03, 
 2DIAGNOSTIC,   295, -9.359974265099e-01, 1.080088551930e-07, 1.4324e+00, 5.1291e-03, 
 2DIAGNOSTIC,   296, -9.359974265099e-01, 1.076433591152e-07, 1.4370e+00, 4.5841e-03, 
 2DIAGNOSTIC,   297, -9.359974265099e-01, 1.072803286206e-07, 1.4415e+00, 4.4529e-03, 
 2DIAGNOSTIC,   298, -9.359974265099e-01, 1.069197352876e-07, 1.4455e+00, 3.9802e-03, 
 2DIAGNOSTIC,   299, -9.359974265099e-01, 1.065615649054e-07, 1.4495e+00, 4.0119e-03, 
 2DIAGNOSTIC,   300, -9.359974265099e-01, 1.062057748413e-07, 1.4535e+00, 4.0340e-03, 
 2DIAGNOSTIC,   301, -9.359974265099e-01, 1.058523650954e-07, 1.4575e+00, 3.9921e-03, 
 2DIAGNOSTIC,   302, -9.359974265099e-01, 1.055012930351e-07, 1.4615e+00, 3.9740e-03, 
 2DIAGNOSTIC,   303, -9.359974265099e-01, 1.051525373441e-07, 1.4655e+00, 4.0379e-03, 
 2DIAGNOSTIC,   304, -9.359974265099e-01, 1.048060838116e-07, 1.4695e+00, 3.9890e-03, 
 2DIAGNOSTIC,   305, -9.359974265099e-01, 1.044619111212e-07, 1.4734e+00, 3.9499e-03, 
 2DIAGNOSTIC,   306, -9.359974265099e-01, 1.041199837459e-07, 1.4774e+00, 4.0040e-03, 
 2DIAGNOSTIC,   307, -9.359974265099e-01, 1.037802945802e-07, 1.4814e+00, 3.9821e-03, 
 2DIAGNOSTIC,   308, -9.359974265099e-01, 1.034428080970e-07, 1.4853e+00, 3.8662e-03, 
 2DIAGNOSTIC,   309, -9.359974265099e-01, 1.031075171909e-07, 1.4892e+00, 3.9380e-03, 
 2DIAGNOSTIC,   310, -9.359974265099e-01, 1.027743863347e-07, 1.4932e+00, 4.0169e-03, 
 2DIAGNOSTIC,   311, -9.359974265099e-01, 1.024434013175e-07, 1.4973e+00, 4.0281e-03, 
 2DIAGNOSTIC,   312, -9.359974265099e-01, 1.021145408231e-07, 1.5012e+00, 3.9399e-03, 
 2DIAGNOSTIC,   313, -9.359974265099e-01, 1.017877906406e-07, 1.5051e+00, 3.8800e-03, 
 2DIAGNOSTIC,   314, -9.359974265099e-01, 1.014631223484e-07, 1.5091e+00, 4.0169e-03, 
 2DIAGNOSTIC,   315, -9.359974265099e-01, 1.011405146301e-07, 1.5130e+00, 3.9101e-03, 
 2DIAGNOSTIC,   316, -9.359974265099e-01, 1.008199532748e-07, 1.5170e+00, 4.0081e-03, 
 2DIAGNOSTIC,   317, -9.359974265099e-01, 1.005014240718e-07, 1.5210e+00, 3.9718e-03, 
 2DIAGNOSTIC,   318, -9.359974265099e-01, 1.001848914939e-07, 1.5251e+00, 4.0731e-03, 
 2DIAGNOSTIC,   319, -9.359974265099e-01, 9.987035554104e-08, 1.5290e+00, 3.9570e-03, 
 2DIAGNOSTIC,   320, -9.359974265099e-01, 9.955778068615e-08, 1.5329e+00, 3.9070e-03, 
 2DIAGNOSTIC,   321, -9.359973669052e-01, 9.919069299258e-08, 1.5370e+00, 4.0219e-03, 
 2DIAGNOSTIC,   322, -9.359973669052e-01, 9.883300577940e-08, 1.5410e+00, 4.0441e-03, 
 2DIAGNOSTIC,   323, -9.359973669052e-01, 9.848714910277e-08, 1.5449e+00, 3.9210e-03, 
 2DIAGNOSTIC,   324, -9.359973669052e-01, 9.815660462209e-08, 1.5489e+00, 3.9511e-03, 
 2DIAGNOSTIC,   325, -9.359973669052e-01, 9.784491084019e-08, 1.5528e+00, 3.8779e-03, 
 2DIAGNOSTIC,   326, -9.359973669052e-01, 9.755351726426e-08, 1.5568e+00, 4.0691e-03, 
 2DIAGNOSTIC,   327, -9.359973669052e-01, 9.728060490488e-08, 1.5608e+00, 3.9961e-03, 
 2DIAGNOSTIC,   328, -9.359973669052e-01, 9.702238656928e-08, 1.5648e+00, 3.9859e-03, 
 2DIAGNOSTIC,   329, -9.359973669052e-01, 9.677517454065e-08, 1.5688e+00, 4.0340e-03, 
 2DIAGNOSTIC,   330, -9.359973669052e-01, 9.653640375973e-08, 1.5728e+00, 3.9878e-03, 
 2DIAGNOSTIC,   331, -9.359973669052e-01, 9.624432806277e-08, 1.5769e+00, 4.0481e-03, 
 2DIAGNOSTIC,   332, -9.359973669052e-01, 9.595400740636e-08, 1.5808e+00, 3.9659e-03, 
 2DIAGNOSTIC,   333, -9.359973669052e-01, 9.566543468509e-08, 1.5848e+00, 3.9742e-03, 
 2DIAGNOSTIC,   334, -9.359973669052e-01, 9.537858858266e-08, 1.5889e+00, 4.0610e-03, 
 2DIAGNOSTIC,   335, -9.359973669052e-01, 9.509346199366e-08, 1.5930e+00, 4.0920e-03, 
 2DIAGNOSTIC,   336, -9.359973669052e-01, 9.481003360179e-08, 1.5973e+00, 4.2911e-03, 
 2DIAGNOSTIC,   337, -9.359973669052e-01, 9.452829630163e-08, 1.6014e+00, 4.1270e-03, 
 2DIAGNOSTIC,   338, -9.359973669052e-01, 9.424822167148e-08, 1.6053e+00, 3.9539e-03, 
 2DIAGNOSTIC,   339, -9.359973669052e-01, 9.396980260590e-08, 1.6094e+00, 4.0960e-03, 
 2DIAGNOSTIC,   340, -9.359973669052e-01, 9.369302489404e-08, 1.6134e+00, 4.0059e-03, 
 2DIAGNOSTIC,   341, -9.359973669052e-01, 9.341786721961e-08, 1.6174e+00, 4.0030e-03, 
 2DIAGNOSTIC,   342, -9.359973669052e-01, 9.314432958263e-08, 1.6214e+00, 3.9349e-03, 
 2DIAGNOSTIC,   343, -9.359973669052e-01, 9.287238356137e-08, 1.6254e+00, 3.9999e-03, 
 2DIAGNOSTIC,   344, -9.359973669052e-01, 9.260202205041e-08, 1.6293e+00, 3.9539e-03, 
 2DIAGNOSTIC,   345, -9.359973669052e-01, 9.233323083890e-08, 1.6333e+00, 4.0009e-03, 
 2DIAGNOSTIC,   346, -9.359973669052e-01, 9.206599571598e-08, 1.6374e+00, 4.1111e-03, 
 2DIAGNOSTIC,   347, -9.359973669052e-01, 9.180030247080e-08, 1.6415e+00, 4.0140e-03, 
 2DIAGNOSTIC,   348, -9.359973669052e-01, 9.153613689250e-08, 1.6455e+00, 4.0600e-03, 
 2DIAGNOSTIC,   349, -9.359973669052e-01, 9.127348477023e-08, 1.6495e+00, 3.9711e-03, 
 2DIAGNOSTIC,   350, -9.359973669052e-01, 9.101233899855e-08, 1.6535e+00, 4.0529e-03, 
 2DIAGNOSTIC,   351, -9.359973669052e-01, 9.075268536662e-08, 1.6576e+00, 4.0300e-03, 
 2DIAGNOSTIC,   352, -9.359973669052e-01, 9.049450966359e-08, 1.6616e+00, 4.0181e-03, 
 2DIAGNOSTIC,   353, -9.359973669052e-01, 9.023779767858e-08, 1.6656e+00, 3.9878e-03, 
 2DIAGNOSTIC,   354, -9.359973669052e-01, 8.998253520076e-08, 1.6695e+00, 3.9549e-03, 
 2DIAGNOSTIC,   355, -9.359973669052e-01, 8.972871512469e-08, 1.6736e+00, 4.0250e-03, 
 2DIAGNOSTIC,   356, -9.359973669052e-01, 8.947632323952e-08, 1.6777e+00, 4.1080e-03, 
 2DIAGNOSTIC,   357, -9.359973669052e-01, 8.922534533440e-08, 1.6817e+00, 3.9799e-03, 
 2DIAGNOSTIC,   358, -9.359973669052e-01, 8.897577430389e-08, 1.6856e+00, 3.9089e-03, 
 2DIAGNOSTIC,   359, -9.359973669052e-01, 8.872758883172e-08, 1.6896e+00, 4.0290e-03, 
 2DIAGNOSTIC,   360, -9.359973669052e-01, 8.848078891788e-08, 1.6936e+00, 4.0319e-03, 
 2DIAGNOSTIC,   361, -9.359973669052e-01, 8.823536035152e-08, 1.6977e+00, 4.0832e-03, 
 2DIAGNOSTIC,   362, -9.359973669052e-01, 8.799128892178e-08, 1.7016e+00, 3.9399e-03, 
 2DIAGNOSTIC,   363, -9.359973669052e-01, 8.774856041782e-08, 1.7057e+00, 4.1001e-03, 
 2DIAGNOSTIC,   364, -9.359973669052e-01, 8.750716773420e-08, 1.7098e+00, 4.0321e-03, 
 2DIAGNOSTIC,   365, -9.359973669052e-01, 8.726710376550e-08, 1.7137e+00, 3.9608e-03, 
 2DIAGNOSTIC,   366, -9.359973669052e-01, 8.702834719543e-08, 1.7177e+00, 4.0021e-03, 
 2DIAGNOSTIC,   367, -9.359973669052e-01, 8.679089802399e-08, 1.7218e+00, 4.0400e-03, 
 2DIAGNOSTIC,   368, -9.359973669052e-01, 8.655474204033e-08, 1.7257e+00, 3.9608e-03, 
 2DIAGNOSTIC,   369, -9.359973669052e-01, 8.631986503360e-08, 1.7297e+00, 3.9392e-03, 
 2DIAGNOSTIC,   370, -9.359973669052e-01, 8.608625989837e-08, 1.7336e+00, 3.9110e-03, 
 2DIAGNOSTIC,   371, -9.359973669052e-01, 8.585391952920e-08, 1.7377e+00, 4.1261e-03, 
 2DIAGNOSTIC,   372, -9.359973669052e-01, 8.562282260982e-08, 1.7417e+00, 3.9539e-03, 
 2DIAGNOSTIC,   373, -9.359973669052e-01, 8.539296914023e-08, 1.7456e+00, 3.9279e-03, 
 2DIAGNOSTIC,   374, -9.359973669052e-01, 8.516435201500e-08, 1.7496e+00, 3.9861e-03, 
 2DIAGNOSTIC,   375, -9.359974861145e-01, 8.503359794076e-08, 1.7536e+00, 4.0200e-03, 
 2DIAGNOSTIC,   376, -9.359974861145e-01, 8.489135439049e-08, 1.7577e+00, 4.0629e-03, 
 2DIAGNOSTIC,   377, -9.359974861145e-01, 8.473340784576e-08, 1.7617e+00, 4.0309e-03, 
 2DIAGNOSTIC,   378, -9.359973669052e-01, 8.445782384570e-08, 1.7658e+00, 4.0541e-03, 
 2DIAGNOSTIC,   379, -9.359973669052e-01, 8.416697028224e-08, 1.7697e+00, 3.9868e-03, 
 2DIAGNOSTIC,   380, -9.359973669052e-01, 8.386243877112e-08, 1.7738e+00, 4.0171e-03, 
 2DIAGNOSTIC,   381, -9.359973669052e-01, 8.355325320508e-08, 1.7778e+00, 4.0329e-03, 
 2DIAGNOSTIC,   382, -9.359973669052e-01, 8.325192624170e-08, 1.7818e+00, 3.9952e-03, 
 2DIAGNOSTIC,   383, -9.359973669052e-01, 8.296726861090e-08, 1.7858e+00, 4.0541e-03, 
 2DIAGNOSTIC,   384, -9.359973669052e-01, 8.270059481674e-08, 1.7899e+00, 4.0240e-03, 
 2DIAGNOSTIC,   385, -9.359973669052e-01, 8.255162953219e-08, 1.7940e+00, 4.0908e-03, 
 2DIAGNOSTIC,   386, -9.359973669052e-01, 8.241951121590e-08, 1.7980e+00, 4.0290e-03, 
 2DIAGNOSTIC,   387, -9.359973669052e-01, 8.229991976805e-08, 1.8020e+00, 4.0510e-03, 
 2DIAGNOSTIC,   388, -9.359973669052e-01, 8.208753854433e-08, 1.8061e+00, 4.0421e-03, 
 2DIAGNOSTIC,   389, -9.359974861145e-01, 8.196941791994e-08, 1.8100e+00, 3.9191e-03, 
 2DIAGNOSTIC,   390, -9.359974861145e-01, 8.184015598545e-08, 1.8140e+00, 4.0250e-03, 
 2DIAGNOSTIC,   391, -9.359974861145e-01, 8.169568843641e-08, 1.8181e+00, 4.1111e-03, 
 2DIAGNOSTIC,   392, -9.359974861145e-01, 8.153016750612e-08, 1.8221e+00, 4.0188e-03, 
 2DIAGNOSTIC,   393, -9.359974861145e-01, 8.133770279528e-08, 1.8261e+00, 3.9132e-03, 
 2DIAGNOSTIC,   394, -9.359974861145e-01, 8.111580029890e-08, 1.8301e+00, 4.0860e-03, 
 2DIAGNOSTIC,   395, -9.359974861145e-01, 8.086737324220e-08, 1.8342e+00, 4.0650e-03, 
 2DIAGNOSTIC,   396, -9.359974861145e-01, 8.059863176868e-08, 1.8382e+00, 4.0140e-03, 
 2DIAGNOSTIC,   397, -9.359974861145e-01, 8.031562259703e-08, 1.8423e+00, 4.0350e-03, 
 2DIAGNOSTIC,   398, -9.359974861145e-01, 8.002251661310e-08, 1.8463e+00, 4.0200e-03, 
 2DIAGNOSTIC,   399, -9.359974861145e-01, 7.982171723597e-08, 1.8502e+00, 3.9139e-03, 
 2DIAGNOSTIC,   400, -9.359974861145e-01, 7.962191972410e-08, 1.8543e+00, 4.0560e-03, 
 2DIAGNOSTIC,   401, -9.359974861145e-01, 7.942311697207e-08, 1.8582e+00, 3.9840e-03, 
 2DIAGNOSTIC,   402, -9.359974861145e-01, 7.922530897986e-08, 1.8622e+00, 3.9999e-03, 
 2DIAGNOSTIC,   403, -9.359973669052e-01, 7.893855524799e-08, 1.8663e+00, 4.0431e-03, 
 2DIAGNOSTIC,   404, -9.359973669052e-01, 7.866456286365e-08, 1.8703e+00, 3.9840e-03, 
 2DIAGNOSTIC,   405, -9.359973669052e-01, 7.840724691732e-08, 1.8744e+00, 4.1311e-03, 
 2DIAGNOSTIC,   406, -9.359973669052e-01, 7.817223490747e-08, 1.8784e+00, 4.0221e-03, 
 2DIAGNOSTIC,   407, -9.359973669052e-01, 7.796521117598e-08, 1.8824e+00, 3.9880e-03, 
 2DIAGNOSTIC,   408, -9.359973669052e-01, 7.778857735730e-08, 1.8865e+00, 4.0560e-03, 
 2DIAGNOSTIC,   409, -9.359973669052e-01, 7.763950549133e-08, 1.8904e+00, 3.9639e-03, 
 2DIAGNOSTIC,   410, -9.359973669052e-01, 7.751199859740e-08, 1.8945e+00, 4.0948e-03, 
 2DIAGNOSTIC,   411, -9.359973669052e-01, 7.740020180336e-08, 1.8986e+00, 4.0560e-03, 
 2DIAGNOSTIC,   412, -9.359973669052e-01, 7.730007212103e-08, 1.9026e+00, 4.0290e-03, 
 2DIAGNOSTIC,   413, -9.359973669052e-01, 7.711268779076e-08, 1.9066e+00, 3.9690e-03, 
 2DIAGNOSTIC,   414, -9.359973669052e-01, 7.692620584976e-08, 1.9107e+00, 4.0989e-03, 
 2DIAGNOSTIC,   415, -9.359973669052e-01, 7.674061919261e-08, 1.9147e+00, 3.9930e-03, 
 2DIAGNOSTIC,   416, -9.359973669052e-01, 7.655593492473e-08, 1.9187e+00, 3.9890e-03, 
 2DIAGNOSTIC,   417, -9.359973669052e-01, 7.637213172984e-08, 1.9227e+00, 4.0581e-03, 
 2DIAGNOSTIC,   418, -9.359973669052e-01, 7.618920960795e-08, 1.9267e+00, 3.9549e-03, 
 2DIAGNOSTIC,   419, -9.359973669052e-01, 7.600716145362e-08, 1.9309e+00, 4.2360e-03, 
 2DIAGNOSTIC,   420, -9.359973669052e-01, 7.582598016143e-08, 1.9350e+00, 4.0641e-03, 
 2DIAGNOSTIC,   421, -9.359973669052e-01, 7.564565862594e-08, 1.9391e+00, 4.1239e-03, 
 2DIAGNOSTIC,   422, -9.359973669052e-01, 7.546619684717e-08, 1.9432e+00, 4.0751e-03, 
 2DIAGNOSTIC,   423, -9.359973669052e-01, 7.528758771969e-08, 1.9473e+00, 4.1578e-03, 
 2DIAGNOSTIC,   424, -9.359973669052e-01, 7.510981703263e-08, 1.9513e+00, 4.0061e-03, 
 2DIAGNOSTIC,   425, -9.359973669052e-01, 7.493288478599e-08, 1.9554e+00, 4.0970e-03, 
 2DIAGNOSTIC,   426, -9.359973669052e-01, 7.475678387436e-08, 1.9595e+00, 4.0789e-03, 
 2DIAGNOSTIC,   427, -9.359973669052e-01, 7.458150719231e-08, 1.9635e+00, 3.9670e-03, 
 2DIAGNOSTIC,   428, -9.359973669052e-01, 7.440705473982e-08, 1.9675e+00, 4.0259e-03, 
 2DIAGNOSTIC,   429, -9.359973669052e-01, 7.423341230606e-08, 1.9715e+00, 4.0100e-03, 
 2DIAGNOSTIC,   430, -9.359973669052e-01, 7.406057989101e-08, 1.9755e+00, 3.9740e-03, 
 2DIAGNOSTIC,   431, -9.359973669052e-01, 7.388855038926e-08, 1.9795e+00, 4.0500e-03, 
 2DIAGNOSTIC,   432, -9.359973669052e-01, 7.371732380079e-08, 1.9836e+00, 4.0619e-03, 
 2DIAGNOSTIC,   433, -9.359973669052e-01, 7.354687880934e-08, 1.9876e+00, 4.0538e-03, 
 2DIAGNOSTIC,   434, -9.359973669052e-01, 7.337722962575e-08, 1.9917e+00, 4.0312e-03, 
 2DIAGNOSTIC,   435, -9.359973669052e-01, 7.320835493374e-08, 1.9957e+00, 3.9721e-03, 
 2DIAGNOSTIC,   436, -9.359973669052e-01, 7.304025473331e-08, 1.9996e+00, 3.9911e-03, 
 2DIAGNOSTIC,   437, -9.359973669052e-01, 7.287292902447e-08, 2.0037e+00, 4.0710e-03, 
 2DIAGNOSTIC,   438, -9.359973669052e-01, 7.270637070178e-08, 2.0078e+00, 4.1108e-03, 
 2DIAGNOSTIC,   439, -9.359973669052e-01, 7.254056555439e-08, 2.0118e+00, 3.9990e-03, 
 2DIAGNOSTIC,   440, -9.359973669052e-01, 7.237552068773e-08, 2.0159e+00, 4.1101e-03, 
 2DIAGNOSTIC,   441, -9.359973669052e-01, 7.221122189094e-08, 2.0200e+00, 4.0519e-03, 
 2DIAGNOSTIC,   442, -9.359973669052e-01, 7.204766916402e-08, 2.0240e+00, 4.0569e-03, 
 2DIAGNOSTIC,   443, -9.359973669052e-01, 7.188484829612e-08, 2.0283e+00, 4.2121e-03, 
 2DIAGNOSTIC,   444, -9.359974861145e-01, 7.180437933130e-08, 2.0323e+00, 4.0519e-03, 
 2DIAGNOSTIC,   445, -9.359974861145e-01, 7.171398408445e-08, 2.0363e+00, 4.0390e-03, 
 2DIAGNOSTIC,   446, -9.359974861145e-01, 7.161007431478e-08, 2.0404e+00, 4.0369e-03, 
 2DIAGNOSTIC,   447, -9.359974861145e-01, 7.148753411457e-08, 2.0444e+00, 4.0531e-03, 
 2DIAGNOSTIC,   448, -9.359974861145e-01, 7.134116231100e-08, 2.0484e+00, 3.9899e-03, 
 2DIAGNOSTIC,   449, -9.359973669052e-01, 7.108805988310e-08, 2.0526e+00, 4.1919e-03, 
 2DIAGNOSTIC,   450, -9.359973669052e-01, 7.082199005026e-08, 2.0567e+00, 4.1142e-03, 
 2DIAGNOSTIC,   451, -9.359973669052e-01, 7.055192696725e-08, 2.0608e+00, 4.0629e-03, 
 2DIAGNOSTIC,   452, -9.359974861145e-01, 7.036839377861e-08, 2.0648e+00, 4.0290e-03, 
 2DIAGNOSTIC,   453, -9.359974861145e-01, 7.018955017202e-08, 2.0689e+00, 4.0770e-03, 
 2DIAGNOSTIC,   454, -9.359974861145e-01, 7.010402924834e-08, 2.0731e+00, 4.1590e-03, 
 2DIAGNOSTIC,   455, -9.359974861145e-01, 7.002412161228e-08, 2.0772e+00, 4.1809e-03, 
 2DIAGNOSTIC,   456, -9.359974861145e-01, 6.993934675847e-08, 2.0813e+00, 4.0541e-03, 
 2DIAGNOSTIC,   457, -9.359974861145e-01, 6.984229372620e-08, 2.0853e+00, 3.9699e-03, 
 2DIAGNOSTIC,   458, -9.359974861145e-01, 6.973183275250e-08, 2.0893e+00, 4.0710e-03, 
 2DIAGNOSTIC,   459, -9.359974861145e-01, 6.952430453566e-08, 2.0935e+00, 4.1530e-03, 
 2DIAGNOSTIC,   460, -9.359974861145e-01, 6.930419971241e-08, 2.0975e+00, 4.0040e-03, 
 2DIAGNOSTIC,   461, -9.359974861145e-01, 6.907509941811e-08, 2.1015e+00, 4.0190e-03, 
 2DIAGNOSTIC,   462, -9.359974861145e-01, 6.892543069625e-08, 2.1056e+00, 4.0851e-03, 
 2DIAGNOSTIC,   463, -9.359974861145e-01, 6.877640856828e-08, 2.1097e+00, 4.1001e-03, 
 2DIAGNOSTIC,   464, -9.359974861145e-01, 6.862802592877e-08, 2.1138e+00, 4.0641e-03, 
 2DIAGNOSTIC,   465, -9.359974861145e-01, 6.848028277773e-08, 2.1179e+00, 4.1299e-03, 
 2DIAGNOSTIC,   466, -9.359974861145e-01, 6.833317911514e-08, 2.1219e+00, 4.0460e-03, 
 2DIAGNOSTIC,   467, -9.359974861145e-01, 6.818670073017e-08, 2.1260e+00, 4.1130e-03, 
 2DIAGNOSTIC,   468, -9.359974861145e-01, 6.804084762280e-08, 2.1302e+00, 4.1201e-03, 
 2DIAGNOSTIC,   469, -9.359974861145e-01, 6.789561979303e-08, 2.1344e+00, 4.2210e-03, 
 2DIAGNOSTIC,   470, -9.359974861145e-01, 6.775101013545e-08, 2.1385e+00, 4.1020e-03, 
 2DIAGNOSTIC,   471, -9.359974861145e-01, 6.760701865005e-08, 2.1426e+00, 4.1149e-03, 
 2DIAGNOSTIC,   472, -9.359974861145e-01, 6.746363823140e-08, 2.1467e+00, 4.1339e-03, 
 2DIAGNOSTIC,   473, -9.359974861145e-01, 6.732086177408e-08, 2.1508e+00, 4.0751e-03, 
 2DIAGNOSTIC,   474, -9.359974861145e-01, 6.717868217265e-08, 2.1549e+00, 4.0960e-03, 
 2DIAGNOSTIC,   475, -9.359974861145e-01, 6.703711363798e-08, 2.1591e+00, 4.2231e-03, 
 2DIAGNOSTIC,   476, -9.359974861145e-01, 6.689613485378e-08, 2.1631e+00, 3.9790e-03, 
 2DIAGNOSTIC,   477, -9.359974861145e-01, 6.675574582005e-08, 2.1673e+00, 4.1950e-03, 
 2DIAGNOSTIC,   478, -9.359974861145e-01, 6.661594653679e-08, 2.1715e+00, 4.1969e-03, 
 2DIAGNOSTIC,   479, -9.359974861145e-01, 6.647672989857e-08, 2.1756e+00, 4.0560e-03, 
 2DIAGNOSTIC,   480, -9.359974861145e-01, 6.633809590539e-08, 2.1797e+00, 4.1161e-03, 
 2DIAGNOSTIC,   481, -9.359974861145e-01, 6.620003745184e-08, 2.1839e+00, 4.2009e-03, 
 2DIAGNOSTIC,   482, -9.359974861145e-01, 6.606255453789e-08, 2.1881e+00, 4.2529e-03, 
 2DIAGNOSTIC,   483, -9.359974861145e-01, 6.592564005814e-08, 2.1922e+00, 4.1132e-03, 
 2DIAGNOSTIC,   484, -9.359973669052e-01, 6.571443833536e-08, 2.1963e+00, 4.0441e-03, 
 2DIAGNOSTIC,   485, -9.359973669052e-01, 6.551354658768e-08, 2.2003e+00, 4.0340e-03, 
 2DIAGNOSTIC,   486, -9.359973669052e-01, 6.532624041711e-08, 2.2044e+00, 4.0851e-03, 
 2DIAGNOSTIC,   487, -9.359973669052e-01, 6.515724493283e-08, 2.2085e+00, 4.0710e-03, 
 2DIAGNOSTIC,   488, -9.359973669052e-01, 6.501132077119e-08, 2.2125e+00, 4.0638e-03, 
 2DIAGNOSTIC,   489, -9.359973669052e-01, 6.489048587355e-08, 2.2166e+00, 4.0591e-03, 
 2DIAGNOSTIC,   490, -9.359973669052e-01, 6.479243097601e-08, 2.2208e+00, 4.1540e-03, 
 2DIAGNOSTIC,   491, -9.359973669052e-01, 6.471216806858e-08, 2.2248e+00, 4.0460e-03, 
 2DIAGNOSTIC,   492, -9.359973669052e-01, 6.464483703894e-08, 2.2289e+00, 4.0798e-03, 
 2DIAGNOSTIC,   493, -9.359973669052e-01, 6.458707701995e-08, 2.2329e+00, 4.0410e-03, 
 2DIAGNOSTIC,   494, -9.359973669052e-01, 6.445620215345e-08, 2.2370e+00, 4.1170e-03, 
 2DIAGNOSTIC,   495, -9.359973669052e-01, 6.432586019400e-08, 2.2411e+00, 4.0162e-03, 
 2DIAGNOSTIC,   496, -9.359973669052e-01, 6.419604403618e-08, 2.2451e+00, 4.0278e-03, 
 2DIAGNOSTIC,   497, -9.359973669052e-01, 6.406675367998e-08, 2.2491e+00, 3.9670e-03, 
 2DIAGNOSTIC,   498, -9.359973669052e-01, 6.393797491455e-08, 2.2531e+00, 4.0860e-03, 
 2DIAGNOSTIC,   499, -9.359973669052e-01, 6.380972195075e-08, 2.2571e+00, 4.0081e-03, 
 2DIAGNOSTIC,   500, -9.359973669052e-01, 6.368197347228e-08, 2.2611e+00, 3.9539e-03, 
 2DIAGNOSTIC,   501, -9.359973669052e-01, 6.355474369002e-08, 2.2651e+00, 4.0100e-03, 
 2DIAGNOSTIC,   502, -9.359973669052e-01, 6.342801128767e-08, 2.2693e+00, 4.1831e-03, 
 2DIAGNOSTIC,   503, -9.359973669052e-01, 6.330179047609e-08, 2.2733e+00, 3.9940e-03, 
 2DIAGNOSTIC,   504, -9.359973669052e-01, 6.317607414985e-08, 2.2773e+00, 4.0150e-03, 
 2DIAGNOSTIC,   505, -9.359973669052e-01, 6.305084809810e-08, 2.2813e+00, 4.0169e-03, 
 2DIAGNOSTIC,   506, -9.359973669052e-01, 6.292612653169e-08, 2.2854e+00, 4.0841e-03, 
 2DIAGNOSTIC,   507, -9.359973669052e-01, 6.280188813435e-08, 2.2895e+00, 4.0798e-03, 
 2DIAGNOSTIC,   508, -9.359973669052e-01, 6.267814711691e-08, 2.2935e+00, 4.0088e-03, 
 2DIAGNOSTIC,   509, -9.359973669052e-01, 6.255488926854e-08, 2.2976e+00, 4.0970e-03, 
 2DIAGNOSTIC,   510, -9.359973669052e-01, 6.243211458923e-08, 2.3016e+00, 4.0581e-03, 
 2DIAGNOSTIC,   511, -9.359973669052e-01, 6.230982307898e-08, 2.3056e+00, 4.0040e-03, 
 2DIAGNOSTIC,   512, -9.359973669052e-01, 6.218800763236e-08, 2.3097e+00, 4.0500e-03, 
 2DIAGNOSTIC,   513, -9.359973669052e-01, 6.206666824937e-08, 2.3137e+00, 4.0331e-03, 
 2DIAGNOSTIC,   514, -9.359973669052e-01, 6.194579782459e-08, 2.3178e+00, 4.0960e-03, 
 2DIAGNOSTIC,   515, -9.359973669052e-01, 6.182540346344e-08, 2.3220e+00, 4.1239e-03, 
 2DIAGNOSTIC,   516, -9.359973669052e-01, 6.170547095508e-08, 2.3260e+00, 4.0231e-03, 
 2DIAGNOSTIC,   517, -9.359973669052e-01, 6.158600740491e-08, 2.3300e+00, 4.0681e-03, 
 2DIAGNOSTIC,   518, -9.359973669052e-01, 6.146699860210e-08, 2.3341e+00, 4.0929e-03, 
 2DIAGNOSTIC,   519, -9.359973669052e-01, 6.134845875749e-08, 2.3382e+00, 4.0519e-03, 
 2DIAGNOSTIC,   520, -9.359973669052e-01, 6.123036655481e-08, 2.3423e+00, 4.0641e-03, 
 2DIAGNOSTIC,   521, -9.359973669052e-01, 6.111273620490e-08, 2.3462e+00, 3.9890e-03, 
 2DIAGNOSTIC,   522, -9.359973669052e-01, 6.099554639150e-08, 2.3504e+00, 4.1189e-03, 
 2DIAGNOSTIC,   523, -9.359973669052e-01, 6.087881132544e-08, 2.3544e+00, 4.0278e-03, 
 2DIAGNOSTIC,   524, -9.359973669052e-01, 6.076252390130e-08, 2.3584e+00, 3.9651e-03, 
 2DIAGNOSTIC,   525, -9.359973669052e-01, 6.064667701366e-08, 2.3625e+00, 4.1530e-03, 
 2DIAGNOSTIC,   526, -9.359973669052e-01, 6.053127776795e-08, 2.3666e+00, 4.0941e-03, 
 2DIAGNOSTIC,   527, -9.359973669052e-01, 6.041630484788e-08, 2.3706e+00, 4.0331e-03, 
 2DIAGNOSTIC,   528, -9.359973669052e-01, 6.030177956973e-08, 2.3746e+00, 3.9470e-03, 
 2DIAGNOSTIC,   529, -9.359973669052e-01, 6.018768061722e-08, 2.3786e+00, 4.0221e-03, 
 2DIAGNOSTIC,   530, -9.359973669052e-01, 6.007401509578e-08, 2.3827e+00, 4.0970e-03, 
 2DIAGNOSTIC,   531, -9.359973669052e-01, 5.996077589998e-08, 2.3867e+00, 4.0300e-03, 
 2DIAGNOSTIC,   532, -9.359973669052e-01, 5.984796302982e-08, 2.3908e+00, 4.0541e-03, 
 2DIAGNOSTIC,   533, -9.359973669052e-01, 5.973557648531e-08, 2.3949e+00, 4.1258e-03, 
 2DIAGNOSTIC,   534, -9.359974861145e-01, 5.969145178142e-08, 2.3990e+00, 4.0622e-03, 
 2DIAGNOSTIC,   535, -9.359974861145e-01, 5.963893556782e-08, 2.4031e+00, 4.1070e-03, 
 2DIAGNOSTIC,   536, -9.359974861145e-01, 5.957504356502e-08, 2.4072e+00, 4.0710e-03, 
 2DIAGNOSTIC,   537, -9.359974861145e-01, 5.949548764761e-08, 2.4113e+00, 4.1111e-03, 
 2DIAGNOSTIC,   538, -9.359974861145e-01, 5.939593350490e-08, 2.4153e+00, 4.0622e-03, 
 2DIAGNOSTIC,   539, -9.359974861145e-01, 5.927452662036e-08, 2.4194e+00, 4.0729e-03, 
 2DIAGNOSTIC,   540, -9.359974861145e-01, 5.913335243690e-08, 2.4235e+00, 4.0550e-03, 
 2DIAGNOSTIC,   541, -9.359974861145e-01, 5.897691579548e-08, 2.4275e+00, 4.0441e-03, 
 2DIAGNOSTIC,   542, -9.359974861145e-01, 5.880961495563e-08, 2.4315e+00, 3.9790e-03, 
 2DIAGNOSTIC,   543, -9.359974861145e-01, 5.863449104027e-08, 2.4355e+00, 3.9971e-03, 
 2DIAGNOSTIC,   544, -9.359974861145e-01, 5.852660933670e-08, 2.4395e+00, 4.0188e-03, 
 2DIAGNOSTIC,   545, -9.359974861145e-01, 5.841912553706e-08, 2.4436e+00, 4.0622e-03, 
 2DIAGNOSTIC,   546, -9.359974861145e-01, 5.831203608864e-08, 2.4477e+00, 4.1208e-03, 
 2DIAGNOSTIC,   547, -9.359974861145e-01, 5.820533743872e-08, 2.4517e+00, 3.9940e-03, 
 2DIAGNOSTIC,   548, -9.359974861145e-01, 5.809902958731e-08, 2.4558e+00, 4.1311e-03, 
 2DIAGNOSTIC,   549, -9.359974861145e-01, 5.799310898169e-08, 2.4598e+00, 4.0131e-03, 
 2DIAGNOSTIC,   550, -9.359974861145e-01, 5.788757206915e-08, 2.4638e+00, 3.9830e-03, 
 2DIAGNOSTIC,   551, -9.359974861145e-01, 5.778241884968e-08, 2.4680e+00, 4.1592e-03, 
 2DIAGNOSTIC,   552, -9.359974861145e-01, 5.767764932330e-08, 2.4720e+00, 4.0288e-03, 
 2DIAGNOSTIC,   553, -9.359974861145e-01, 5.757325638456e-08, 2.4760e+00, 4.0262e-03, 
 2DIAGNOSTIC,   554, -9.359974861145e-01, 5.746924358618e-08, 2.4802e+00, 4.1769e-03, 
 2DIAGNOSTIC,   555, -9.359974861145e-01, 5.736560382275e-08, 2.4843e+00, 4.1101e-03, 
 2DIAGNOSTIC,   556, -9.359974861145e-01, 5.726233709424e-08, 2.4883e+00, 4.0219e-03, 
 2DIAGNOSTIC,   557, -9.359974861145e-01, 5.715944340068e-08, 2.4924e+00, 4.1211e-03, 
 2DIAGNOSTIC,   558, -9.359974861145e-01, 5.705691563662e-08, 2.4965e+00, 4.0829e-03, 
 2DIAGNOSTIC,   559, -9.359974861145e-01, 5.695475735479e-08, 2.5005e+00, 3.9840e-03, 
 2DIAGNOSTIC,   560, -9.359974861145e-01, 5.685296500246e-08, 2.5047e+00, 4.1831e-03, 
 2DIAGNOSTIC,   561, -9.359974861145e-01, 5.675153502693e-08, 2.5088e+00, 4.1349e-03, 
 2DIAGNOSTIC,   562, -9.359974861145e-01, 5.665046387549e-08, 2.5130e+00, 4.1430e-03, 
 2DIAGNOSTIC,   563, -9.359974861145e-01, 5.654975510083e-08, 2.5172e+00, 4.2119e-03, 
 2DIAGNOSTIC,   564, -9.359974861145e-01, 5.644940159755e-08, 2.5212e+00, 4.0631e-03, 
 2DIAGNOSTIC,   565, -9.359974861145e-01, 5.634940691834e-08, 2.5254e+00, 4.1201e-03, 
 2DIAGNOSTIC,   566, -9.359974861145e-01, 5.624976395779e-08, 2.5295e+00, 4.1010e-03, 
 2DIAGNOSTIC,   567, -9.359974861145e-01, 5.615047271590e-08, 2.5335e+00, 4.0538e-03, 
 2DIAGNOSTIC,   568, -9.359974861145e-01, 5.605152963994e-08, 2.5376e+00, 4.1161e-03, 
 2DIAGNOSTIC,   569, -9.359974861145e-01, 5.595293472993e-08, 2.5416e+00, 3.9980e-03, 
 2DIAGNOSTIC,   570, -9.359974861145e-01, 5.585468798586e-08, 2.5457e+00, 4.0300e-03, 
 2DIAGNOSTIC,   571, -9.359974861145e-01, 5.575678585501e-08, 2.5497e+00, 4.0290e-03, 
 2DIAGNOSTIC,   572, -9.359974861145e-01, 5.565922478468e-08, 2.5537e+00, 4.0541e-03, 
 2DIAGNOSTIC,   573, -9.359974861145e-01, 5.556200832757e-08, 2.5579e+00, 4.1449e-03, 
 2DIAGNOSTIC,   574, -9.359973669052e-01, 5.540201541976e-08, 2.5620e+00, 4.1270e-03, 
 2DIAGNOSTIC,   575, -9.359973669052e-01, 5.525054191935e-08, 2.5661e+00, 4.0669e-03, 
 2DIAGNOSTIC,   576, -9.359973669052e-01, 5.511036604844e-08, 2.5701e+00, 4.0309e-03, 
 2DIAGNOSTIC,   577, -9.359973669052e-01, 5.498547039906e-08, 2.5742e+00, 4.0731e-03, 
 2DIAGNOSTIC,   578, -9.359974861145e-01, 5.494257138139e-08, 2.5783e+00, 4.1230e-03, 
 2DIAGNOSTIC,   579, -9.359974861145e-01, 5.491260068879e-08, 2.5823e+00, 3.9768e-03, 
 2DIAGNOSTIC,   580, -9.359974861145e-01, 5.489086163379e-08, 2.5864e+00, 4.0710e-03, 
 2DIAGNOSTIC,   581, -9.359974861145e-01, 5.486919718578e-08, 2.5904e+00, 4.0751e-03, 
 2DIAGNOSTIC,   582, -9.359974861145e-01, 5.483950715757e-08, 2.5945e+00, 4.0939e-03, 
 2DIAGNOSTIC,   583, -9.359974861145e-01, 5.479722986479e-08, 2.5985e+00, 3.9599e-03, 
 2DIAGNOSTIC,   584, -9.359974861145e-01, 5.467437347306e-08, 2.6025e+00, 4.0441e-03, 
 2DIAGNOSTIC,   585, -9.359974861145e-01, 5.453734175376e-08, 2.6067e+00, 4.1759e-03, 
 2DIAGNOSTIC,   586, -9.359974861145e-01, 5.439019901132e-08, 2.6108e+00, 4.0741e-03, 
 2DIAGNOSTIC,   587, -9.359974861145e-01, 5.423574478414e-08, 2.6150e+00, 4.2269e-03, 
 2DIAGNOSTIC,   588, -9.359974861145e-01, 5.414343107191e-08, 2.6191e+00, 4.0901e-03, 
 2DIAGNOSTIC,   589, -9.359974861145e-01, 5.405142999848e-08, 2.6231e+00, 4.0269e-03, 
 2DIAGNOSTIC,   590, -9.359974861145e-01, 5.395974156386e-08, 2.6271e+00, 4.0219e-03, 
 2DIAGNOSTIC,   591, -9.359974861145e-01, 5.386836576804e-08, 2.6311e+00, 4.0002e-03, 
 2DIAGNOSTIC,   592, -9.359974861145e-01, 5.377729550560e-08, 2.6352e+00, 4.0810e-03, 
 2DIAGNOSTIC,   593, -9.359974861145e-01, 5.368653432924e-08, 2.6394e+00, 4.1261e-03, 
 2DIAGNOSTIC,   594, -9.359974861145e-01, 5.359607868627e-08, 2.6434e+00, 4.0309e-03, 
 2DIAGNOSTIC,   595, -9.359974861145e-01, 5.350592857667e-08, 2.6476e+00, 4.2222e-03, 
 2DIAGNOSTIC,   596, -9.359973669052e-01, 5.335529706940e-08, 2.6520e+00, 4.4060e-03, 
 2DIAGNOSTIC,   597, -9.359973669052e-01, 5.321284390902e-08, 2.6561e+00, 4.1299e-03, 
 2DIAGNOSTIC,   598, -9.359973669052e-01, 5.308123718351e-08, 2.6602e+00, 4.0560e-03, 
 2DIAGNOSTIC,   599, -9.359974861145e-01, 5.302480232672e-08, 2.6642e+00, 3.9680e-03, 
 2DIAGNOSTIC,   600, -9.359974861145e-01, 5.297911442881e-08, 2.6682e+00, 4.0071e-03, 
 2DIAGNOSTIC,   601, -9.359974861145e-01, 5.294319294080e-08, 2.6722e+00, 4.0410e-03, 
 2DIAGNOSTIC,   602, -9.359974861145e-01, 5.291134286267e-08, 2.6763e+00, 4.0770e-03, 
 2DIAGNOSTIC,   603, -9.359974861145e-01, 5.287564874834e-08, 2.6805e+00, 4.2551e-03, 
 2DIAGNOSTIC,   604, -9.359974861145e-01, 5.283051152105e-08, 2.6847e+00, 4.1440e-03, 
 2DIAGNOSTIC,   605, -9.359974861145e-01, 5.277505366053e-08, 2.6887e+00, 4.0290e-03, 
 2DIAGNOSTIC,   606, -9.359974861145e-01, 5.264591251830e-08, 2.6928e+00, 4.0689e-03, 
 2DIAGNOSTIC,   607, -9.359974861145e-01, 5.250698009718e-08, 2.6968e+00, 4.0140e-03, 
 2DIAGNOSTIC,   608, -9.359974861145e-01, 5.236096711769e-08, 2.7009e+00, 4.1001e-03, 
 2DIAGNOSTIC,   609, -9.359974861145e-01, 5.227492039239e-08, 2.7049e+00, 4.0369e-03, 
 2DIAGNOSTIC,   610, -9.359974861145e-01, 5.218915433147e-08, 2.7090e+00, 4.0760e-03, 
 2DIAGNOSTIC,   611, -9.359973669052e-01, 5.204438480177e-08, 2.7132e+00, 4.1361e-03, 
 2DIAGNOSTIC,   612, -9.359973669052e-01, 5.190756624529e-08, 2.7172e+00, 4.0481e-03, 
 2DIAGNOSTIC,   613, -9.359973669052e-01, 5.178131701200e-08, 2.7213e+00, 4.1420e-03, 
 2DIAGNOSTIC,   614, -9.359973669052e-01, 5.166937810941e-08, 2.7254e+00, 4.0410e-03, 
 2DIAGNOSTIC,   615, -9.359973669052e-01, 5.157555804658e-08, 2.7294e+00, 4.0250e-03, 
 2DIAGNOSTIC,   616, -9.359974861145e-01, 5.156029203590e-08, 2.7335e+00, 4.0660e-03, 
 2DIAGNOSTIC,   617, -9.359974861145e-01, 5.155535021117e-08, 2.7376e+00, 4.0898e-03, 
 2DIAGNOSTIC,   618, -9.359973669052e-01, 5.149558290896e-08, 2.7416e+00, 4.0791e-03, 
 2DIAGNOSTIC,   619, -9.359973669052e-01, 5.143963477394e-08, 2.7456e+00, 3.9480e-03, 
 2DIAGNOSTIC,   620, -9.359973669052e-01, 5.138365466451e-08, 2.7496e+00, 4.0569e-03, 
 2DIAGNOSTIC,   621, -9.359973669052e-01, 5.126397795152e-08, 2.7538e+00, 4.1640e-03, 
 2DIAGNOSTIC,   622, -9.359973669052e-01, 5.114468848433e-08, 2.7580e+00, 4.1621e-03, 
 2DIAGNOSTIC,   623, -9.359973669052e-01, 5.103130362727e-08, 2.7621e+00, 4.1671e-03, 
 2DIAGNOSTIC,   624, -9.359973669052e-01, 5.092584132171e-08, 2.7662e+00, 4.1049e-03, 
 2DIAGNOSTIC,   625, -9.359973669052e-01, 5.082704035431e-08, 2.7702e+00, 3.9799e-03, 
 2DIAGNOSTIC,   626, -9.359973669052e-01, 5.079633069727e-08, 2.7742e+00, 4.0011e-03, 
 2DIAGNOSTIC,   627, -9.359973669052e-01, 5.077302844825e-08, 2.7783e+00, 4.1099e-03, 
 2DIAGNOSTIC,   628, -9.359973669052e-01, 5.069211894693e-08, 2.7825e+00, 4.2059e-03, 
 2DIAGNOSTIC,   629, -9.359973669052e-01, 5.061146524099e-08, 2.7868e+00, 4.2090e-03, 
 2DIAGNOSTIC,   630, -9.359973669052e-01, 5.053106733044e-08, 2.7909e+00, 4.1330e-03, 
 2DIAGNOSTIC,   631, -9.359974265099e-01, 5.047962758908e-08, 2.7950e+00, 4.1089e-03, 
 2DIAGNOSTIC,   632, -9.359974265099e-01, 5.042472750461e-08, 2.7991e+00, 4.0791e-03, 
 2DIAGNOSTIC,   633, -9.359974265099e-01, 5.036510231093e-08, 2.8031e+00, 4.0770e-03, 
 2DIAGNOSTIC,   634, -9.359974265099e-01, 5.029893301867e-08, 2.8073e+00, 4.1020e-03, 
 2DIAGNOSTIC,   635, -9.359974265099e-01, 5.022437932212e-08, 2.8113e+00, 4.0319e-03, 
 2DIAGNOSTIC,   636, -9.359974265099e-01, 5.014064186071e-08, 2.8153e+00, 4.0200e-03, 
 2DIAGNOSTIC,   637, -9.359974265099e-01, 5.004859815472e-08, 2.8195e+00, 4.1490e-03, 
 2DIAGNOSTIC,   638, -9.359974265099e-01, 4.995015245868e-08, 2.8235e+00, 4.0691e-03, 
 2DIAGNOSTIC,   639, -9.359974265099e-01, 4.984716639456e-08, 2.8276e+00, 4.0720e-03, 
 2DIAGNOSTIC,   640, -9.359974265099e-01, 4.974091893928e-08, 2.8317e+00, 4.1111e-03, 
 2DIAGNOSTIC,   641, -9.359974265099e-01, 4.966326017097e-08, 2.8357e+00, 4.0359e-03, 
 2DIAGNOSTIC,   642, -9.359974265099e-01, 4.958584653991e-08, 2.8397e+00, 3.9790e-03, 
 2DIAGNOSTIC,   643, -9.359974265099e-01, 4.950867094067e-08, 2.8438e+00, 4.0600e-03, 
 2DIAGNOSTIC,   644, -9.359974265099e-01, 4.943173337324e-08, 2.8478e+00, 4.0181e-03, 
 2DIAGNOSTIC,   645, -9.359974265099e-01, 4.935503739034e-08, 2.8519e+00, 4.1292e-03, 
 2DIAGNOSTIC,   646, -9.359974265099e-01, 4.927857943926e-08, 2.8559e+00, 4.0169e-03, 
 2DIAGNOSTIC,   647, -9.359974265099e-01, 4.920235952000e-08, 2.8600e+00, 4.0290e-03, 
 2DIAGNOSTIC,   648, -9.359974265099e-01, 4.912637052712e-08, 2.8641e+00, 4.1211e-03, 
 2DIAGNOSTIC,   649, -9.359974265099e-01, 4.905061956606e-08, 2.8681e+00, 4.0259e-03, 
 2DIAGNOSTIC,   650, -9.359974265099e-01, 4.897509953139e-08, 2.8722e+00, 4.0629e-03, 
 2DIAGNOSTIC,   651, -9.359973073006e-01, 4.884417137418e-08, 2.8763e+00, 4.1552e-03, 
 2DIAGNOSTIC,   652, -9.359973073006e-01, 4.872066483586e-08, 2.8803e+00, 3.9799e-03, 
 2DIAGNOSTIC,   653, -9.359973073006e-01, 4.860703839427e-08, 2.8843e+00, 4.0190e-03, 
 2DIAGNOSTIC,   654, -9.359973073006e-01, 4.850680923596e-08, 2.8886e+00, 4.2629e-03, 
 2DIAGNOSTIC,   655, -9.359973073006e-01, 4.842355494361e-08, 2.8928e+00, 4.1640e-03, 
 2DIAGNOSTIC,   656, -9.359973073006e-01, 4.835881384224e-08, 2.8969e+00, 4.1721e-03, 
 2DIAGNOSTIC,   657, -9.359973073006e-01, 4.831088062929e-08, 2.9010e+00, 4.0970e-03, 
 2DIAGNOSTIC,   658, -9.359973073006e-01, 4.827607114066e-08, 2.9051e+00, 4.0882e-03, 
 2DIAGNOSTIC,   659, -9.359973669052e-01, 4.827825605958e-08, 2.9092e+00, 4.0560e-03, 
 2DIAGNOSTIC,   660, -9.359973669052e-01, 4.828391197975e-08, 2.9133e+00, 4.1080e-03, 
 2DIAGNOSTIC,   661, -9.359973669052e-01, 4.823005639309e-08, 2.9173e+00, 4.0140e-03, 
 2DIAGNOSTIC,   662, -9.359973669052e-01, 4.816991605594e-08, 2.9213e+00, 4.0431e-03, 
 2DIAGNOSTIC,   663, -9.359973669052e-01, 4.810172526959e-08, 2.9255e+00, 4.1640e-03, 
 2DIAGNOSTIC,   664, -9.359973669052e-01, 4.802472020060e-08, 2.9295e+00, 4.0021e-03, 
 2DIAGNOSTIC,   665, -9.359973669052e-01, 4.793973928940e-08, 2.9336e+00, 4.1120e-03, 
 2DIAGNOSTIC,   666, -9.359973669052e-01, 4.784860507812e-08, 2.9378e+00, 4.1342e-03, 
 2DIAGNOSTIC,   667, -9.359973669052e-01, 4.775309747629e-08, 2.9419e+00, 4.1430e-03, 
 2DIAGNOSTIC,   668, -9.359973669052e-01, 4.765444217014e-08, 2.9460e+00, 4.0822e-03, 
 2DIAGNOSTIC,   669, -9.359973669052e-01, 4.758316052289e-08, 2.9500e+00, 4.0140e-03, 
 2DIAGNOSTIC,   670, -9.359973669052e-01, 4.751208848575e-08, 2.9541e+00, 4.1280e-03, 
 2DIAGNOSTIC,   671, -9.359973669052e-01, 4.744122961142e-08, 2.9582e+00, 4.0600e-03, 
 2DIAGNOSTIC,   672, -9.359973669052e-01, 4.737058034721e-08, 2.9622e+00, 4.0021e-03, 
 2DIAGNOSTIC,   673, -9.359973669052e-01, 4.730014069310e-08, 2.9663e+00, 4.1070e-03, 
 2DIAGNOSTIC,   674, -9.359973669052e-01, 4.722991420181e-08, 2.9704e+00, 4.0948e-03, 
 2DIAGNOSTIC,   675, -9.359973669052e-01, 4.715989376791e-08, 2.9744e+00, 3.9690e-03, 
 2DIAGNOSTIC,   676, -9.359973669052e-01, 4.709007939141e-08, 2.9784e+00, 4.0359e-03, 
 2DIAGNOSTIC,   677, -9.359973669052e-01, 4.702047107230e-08, 2.9825e+00, 4.1001e-03, 
 2DIAGNOSTIC,   678, -9.359973669052e-01, 4.695106881059e-08, 2.9865e+00, 4.0441e-03, 
 2DIAGNOSTIC,   679, -9.359973669052e-01, 4.688187260626e-08, 2.9905e+00, 4.0050e-03, 
 2DIAGNOSTIC,   680, -9.359974265099e-01, 4.683951360107e-08, 2.9946e+00, 4.0879e-03, 
 2DIAGNOSTIC,   681, -9.359974265099e-01, 4.679391452100e-08, 2.9987e+00, 4.0741e-03, 
 2DIAGNOSTIC,   682, -9.359974265099e-01, 4.674390652326e-08, 3.0028e+00, 4.0851e-03, 
 2DIAGNOSTIC,   683, -9.359974265099e-01, 4.668779496342e-08, 3.0068e+00, 4.0040e-03, 
 2DIAGNOSTIC,   684, -9.359974265099e-01, 4.662386388077e-08, 3.0108e+00, 3.9690e-03, 
 2DIAGNOSTIC,   685, -9.359974265099e-01, 4.655138141629e-08, 3.0149e+00, 4.1211e-03, 
 2DIAGNOSTIC,   686, -9.359974265099e-01, 4.647115403600e-08, 3.0189e+00, 4.0410e-03, 
 2DIAGNOSTIC,   687, -9.359974265099e-01, 4.638494743858e-08, 3.0229e+00, 3.9771e-03, 
 2DIAGNOSTIC,   688, -9.359974265099e-01, 4.629448469018e-08, 3.0269e+00, 4.0512e-03, 
 2DIAGNOSTIC,   689, -9.359974265099e-01, 4.620095950258e-08, 3.0309e+00, 3.9802e-03, 
 2DIAGNOSTIC,   690, -9.359974265099e-01, 4.613395532260e-08, 3.0350e+00, 4.0700e-03, 
 2DIAGNOSTIC,   691, -9.359974265099e-01, 4.606714298916e-08, 3.0390e+00, 3.9709e-03, 
 2DIAGNOSTIC,   692, -9.359974265099e-01, 4.600052605497e-08, 3.0431e+00, 4.1339e-03, 
 2DIAGNOSTIC,   693, -9.359974265099e-01, 4.593410096732e-08, 3.0472e+00, 4.0622e-03, 
 2DIAGNOSTIC,   694, -9.359974265099e-01, 4.586786417349e-08, 3.0511e+00, 3.9158e-03, 
 2DIAGNOSTIC,   695, -9.359974265099e-01, 4.580182277891e-08, 3.0552e+00, 4.1142e-03, 
 2DIAGNOSTIC,   696, -9.359974265099e-01, 4.573596967816e-08, 3.0592e+00, 3.9768e-03, 
 2DIAGNOSTIC,   697, -9.359974265099e-01, 4.567030487124e-08, 3.0632e+00, 4.0231e-03, 
 2DIAGNOSTIC,   698, -9.359974861145e-01, 4.563077382613e-08, 3.0672e+00, 4.0319e-03, 
 2DIAGNOSTIC,   699, -9.359974861145e-01, 4.558808441857e-08, 3.0713e+00, 4.1010e-03, 
 2DIAGNOSTIC,   700, -9.359974861145e-01, 4.554108556931e-08, 3.0753e+00, 3.9289e-03, 
 2DIAGNOSTIC,   701, -9.359974861145e-01, 4.548813237193e-08, 3.0792e+00, 3.9399e-03, 
 2DIAGNOSTIC,   702, -9.359974861145e-01, 4.542755505099e-08, 3.0833e+00, 4.0581e-03, 
 2DIAGNOSTIC,   703, -9.359975457191e-01, 4.538439313251e-08, 3.0874e+00, 4.1399e-03, 
 2DIAGNOSTIC,   704, -9.359975457191e-01, 4.533034925203e-08, 3.0914e+00, 4.0040e-03, 
 2DIAGNOSTIC,   705, -9.359975457191e-01, 4.526600605459e-08, 3.0955e+00, 4.0641e-03, 
 2DIAGNOSTIC,   706, -9.359975457191e-01, 4.519140972548e-08, 3.0995e+00, 4.0610e-03, 
 2DIAGNOSTIC,   707, -9.359975457191e-01, 4.510606288477e-08, 3.1035e+00, 4.0021e-03, 
 2DIAGNOSTIC,   708, -9.359975457191e-01, 4.503808170853e-08, 3.1076e+00, 4.0491e-03, 
 2DIAGNOSTIC,   709, -9.359975457191e-01, 4.496259364828e-08, 3.1116e+00, 3.9959e-03, 
 2DIAGNOSTIC,   710, -9.359975457191e-01, 4.488130755931e-08, 3.1155e+00, 3.9580e-03, 
 2DIAGNOSTIC,   711, -9.359975457191e-01, 4.479588966433e-08, 3.1196e+00, 4.0469e-03, 
 2DIAGNOSTIC,   712, -9.359975457191e-01, 4.470749459529e-08, 3.1236e+00, 3.9802e-03, 
 2DIAGNOSTIC,   713, -9.359975457191e-01, 4.464475011901e-08, 3.1276e+00, 4.0050e-03, 
 2DIAGNOSTIC,   714, -9.359975457191e-01, 4.458217972569e-08, 3.1316e+00, 4.0178e-03, 
 2DIAGNOSTIC,   715, -9.359975457191e-01, 4.451978341535e-08, 3.1356e+00, 4.0240e-03, 
 2DIAGNOSTIC,   716, -9.359975457191e-01, 4.445756118798e-08, 3.1396e+00, 4.0460e-03, 
 2DIAGNOSTIC,   717, -9.359975457191e-01, 4.439551659630e-08, 3.1438e+00, 4.1950e-03, 
 2DIAGNOSTIC,   718, -9.359975457191e-01, 4.433364253487e-08, 3.1479e+00, 4.0801e-03, 
 2DIAGNOSTIC,   719, -9.359975457191e-01, 4.427193900369e-08, 3.1519e+00, 3.9909e-03, 
 2DIAGNOSTIC,   720, -9.359975457191e-01, 4.421040955549e-08, 3.1559e+00, 3.9840e-03, 
 2DIAGNOSTIC,   721, -9.359975457191e-01, 4.414905063754e-08, 3.1600e+00, 4.0679e-03, 
 2DIAGNOSTIC,   722, -9.359975457191e-01, 4.408785869714e-08, 3.1640e+00, 4.0801e-03, 
 2DIAGNOSTIC,   723, -9.359975457191e-01, 4.402684083971e-08, 3.1681e+00, 4.1001e-03, 
 2DIAGNOSTIC,   724, -9.359974861145e-01, 4.394097530280e-08, 3.1722e+00, 4.0412e-03, 
 2DIAGNOSTIC,   725, -9.359974861145e-01, 4.385850260746e-08, 3.1762e+00, 3.9892e-03, 
 2DIAGNOSTIC,   726, -9.359974861145e-01, 4.378053120035e-08, 3.1802e+00, 4.0581e-03, 
 2DIAGNOSTIC,   727, -9.359974861145e-01, 4.370864203906e-08, 3.1843e+00, 4.0510e-03, 
 2DIAGNOSTIC,   728, -9.359974861145e-01, 4.364445160832e-08, 3.1884e+00, 4.1399e-03, 
 2DIAGNOSTIC,   729, -9.359974861145e-01, 4.358864913456e-08, 3.1926e+00, 4.1289e-03, 
 2DIAGNOSTIC,   730, -9.359974861145e-01, 4.354047433708e-08, 3.1966e+00, 4.0262e-03, 
 2DIAGNOSTIC,   731, -9.359974861145e-01, 4.349827165129e-08, 3.2006e+00, 4.0281e-03, 
 2DIAGNOSTIC,   732, -9.359974861145e-01, 4.346042103975e-08, 3.2048e+00, 4.1561e-03, 
 2DIAGNOSTIC,   733, -9.359974861145e-01, 4.342579629224e-08, 3.2089e+00, 4.1411e-03, 
 2DIAGNOSTIC,   734, -9.359974861145e-01, 4.336659387150e-08, 3.2129e+00, 3.9680e-03, 
 2DIAGNOSTIC,   735, -9.359974861145e-01, 4.330755487558e-08, 3.2170e+00, 4.1609e-03, 
 2DIAGNOSTIC,   736, -9.359974861145e-01, 4.324867219907e-08, 3.2209e+00, 3.9101e-03, 
 2DIAGNOSTIC,   737, -9.359974861145e-01, 4.318995294739e-08, 3.2250e+00, 4.0090e-03, 
 2DIAGNOSTIC,   738, -9.359974861145e-01, 4.313139001511e-08, 3.2290e+00, 4.0689e-03, 
 2DIAGNOSTIC,   739, -9.359974861145e-01, 4.307298695494e-08, 3.2331e+00, 4.0510e-03, 
 2DIAGNOSTIC,   740, -9.359974861145e-01, 4.301474021418e-08, 3.2371e+00, 4.0300e-03, 
 2DIAGNOSTIC,   741, -9.359974861145e-01, 4.295665334553e-08, 3.2411e+00, 4.0102e-03, 
 2DIAGNOSTIC,   742, -9.359974861145e-01, 4.289872279628e-08, 3.2452e+00, 4.1020e-03, 
 2DIAGNOSTIC,   743, -9.359974861145e-01, 4.284094856644e-08, 3.2492e+00, 3.9802e-03, 
 2DIAGNOSTIC,   744, -9.359974861145e-01, 4.278332710328e-08, 3.2533e+00, 4.1349e-03, 
 2DIAGNOSTIC,   745, -9.359974861145e-01, 4.272586195952e-08, 3.2574e+00, 4.0929e-03, 
 2DIAGNOSTIC,   746, -9.359974861145e-01, 4.266855313517e-08, 3.2614e+00, 3.9589e-03, 
 2DIAGNOSTIC,   747, -9.359974861145e-01, 4.261139352479e-08, 3.2654e+00, 3.9909e-03, 
 2DIAGNOSTIC,   748, -9.359974861145e-01, 4.255439023382e-08, 3.2693e+00, 3.9611e-03, 
 2DIAGNOSTIC,   749, -9.359974861145e-01, 4.249753970953e-08, 3.2734e+00, 4.0801e-03, 
 2DIAGNOSTIC,   750, -9.359974861145e-01, 4.244083839922e-08, 3.2775e+00, 4.0901e-03, 
 2DIAGNOSTIC,   751, -9.359974861145e-01, 4.238428985559e-08, 3.2815e+00, 4.0240e-03, 
 2DIAGNOSTIC,   752, -9.359974861145e-01, 4.232789052594e-08, 3.2856e+00, 4.0460e-03, 
 2DIAGNOSTIC,   753, -9.359974861145e-01, 4.227164041026e-08, 3.2898e+00, 4.2281e-03, 
 2DIAGNOSTIC,   754, -9.359974861145e-01, 4.221554306127e-08, 3.2938e+00, 4.0030e-03, 
 2DIAGNOSTIC,   755, -9.359974861145e-01, 4.215959137355e-08, 3.2979e+00, 4.0660e-03, 
 2DIAGNOSTIC,   756, -9.359974861145e-01, 4.210378889979e-08, 3.3018e+00, 3.9680e-03, 
 2DIAGNOSTIC,   757, -9.359974861145e-01, 4.204813208730e-08, 3.3059e+00, 4.0510e-03, 
 2DIAGNOSTIC,   758, -9.359974861145e-01, 4.199262448878e-08, 3.3098e+00, 3.9439e-03, 
 2DIAGNOSTIC,   759, -9.359974861145e-01, 4.193726255153e-08, 3.3139e+00, 4.0221e-03, 
 2DIAGNOSTIC,   760, -9.359974861145e-01, 4.188204627553e-08, 3.3179e+00, 4.0128e-03, 
 2DIAGNOSTIC,   761, -9.359974861145e-01, 4.182697566080e-08, 3.3219e+00, 4.0090e-03, 
 2DIAGNOSTIC,   762, -9.359974861145e-01, 4.177205070732e-08, 3.3258e+00, 3.9470e-03, 
 2DIAGNOSTIC,   763, -9.359974861145e-01, 4.171726786240e-08, 3.3300e+00, 4.1349e-03, 
 2DIAGNOSTIC,   764, -9.359974861145e-01, 4.166263067873e-08, 3.3340e+00, 4.0040e-03, 
 2DIAGNOSTIC,   765, -9.359974861145e-01, 4.160813560361e-08, 3.3379e+00, 3.9690e-03, 
 2DIAGNOSTIC,   766, -9.359974861145e-01, 4.155378263704e-08, 3.3419e+00, 3.9651e-03, 
 2DIAGNOSTIC,   767, -9.359974861145e-01, 4.149956822630e-08, 3.3461e+00, 4.1699e-03, 
 2DIAGNOSTIC,   768, -9.359974861145e-01, 4.144549947682e-08, 3.3500e+00, 3.9749e-03, 
 2DIAGNOSTIC,   769, -9.359974861145e-01, 4.139156928318e-08, 3.3539e+00, 3.8929e-03, 
 2DIAGNOSTIC,   770, -9.359974861145e-01, 4.133778119808e-08, 3.3580e+00, 4.0610e-03, 
 2DIAGNOSTIC,   771, -9.359974861145e-01, 4.128413166882e-08, 3.3620e+00, 3.9649e-03, 
 2DIAGNOSTIC,   772, -9.359974861145e-01, 4.123062069539e-08, 3.3659e+00, 3.9458e-03, 
 2DIAGNOSTIC,   773, -9.359974861145e-01, 4.117724827779e-08, 3.3700e+00, 4.0572e-03, 
 2DIAGNOSTIC,   774, -9.359974861145e-01, 4.112401441603e-08, 3.3741e+00, 4.0872e-03, 
 2DIAGNOSTIC,   775, -9.359974861145e-01, 4.107091555738e-08, 3.3781e+00, 4.0269e-03, 
 2DIAGNOSTIC,   776, -9.359974861145e-01, 4.101795880729e-08, 3.3820e+00, 3.9351e-03, 
 2DIAGNOSTIC,   777, -9.359974861145e-01, 4.096513350760e-08, 3.3860e+00, 4.0169e-03, 
 2DIAGNOSTIC,   778, -9.359974861145e-01, 4.091244676374e-08, 3.3901e+00, 4.0231e-03, 
 2DIAGNOSTIC,   779, -9.359974861145e-01, 4.085989502300e-08, 3.3941e+00, 4.0460e-03, 
 2DIAGNOSTIC,   780, -9.359974861145e-01, 4.080747828539e-08, 3.3982e+00, 4.0660e-03, 
 2DIAGNOSTIC,   781, -9.359974861145e-01, 4.075519299818e-08, 3.4022e+00, 3.9890e-03, 
 2DIAGNOSTIC,   782, -9.359974861145e-01, 4.070304626680e-08, 3.4062e+00, 4.0560e-03, 
 2DIAGNOSTIC,   783, -9.359974861145e-01, 4.065102743311e-08, 3.4102e+00, 3.9561e-03, 
 2DIAGNOSTIC,   784, -9.359974861145e-01, 4.059914715526e-08, 3.4142e+00, 3.9978e-03, 
 2DIAGNOSTIC,   785, -9.359974861145e-01, 4.054739477510e-08, 3.4182e+00, 4.0271e-03, 
 2DIAGNOSTIC,   786, -9.359974861145e-01, 4.049577739806e-08, 3.4222e+00, 4.0400e-03, 
 2DIAGNOSTIC,   787, -9.359974861145e-01, 4.044428791872e-08, 3.4265e+00, 4.2598e-03, 
 2DIAGNOSTIC,   788, -9.359974861145e-01, 4.039292988978e-08, 3.4312e+00, 4.7019e-03, 
 2DIAGNOSTIC,   789, -9.359974861145e-01, 4.034170331124e-08, 3.4359e+00, 4.7209e-03, 
 2DIAGNOSTIC,   790, -9.359974861145e-01, 4.029060818311e-08, 3.4402e+00, 4.3080e-03, 
 2DIAGNOSTIC,   791, -9.359974861145e-01, 4.023964095268e-08, 3.4443e+00, 4.0932e-03, 
 2DIAGNOSTIC,   792, -9.359974861145e-01, 4.018880161993e-08, 3.4484e+00, 4.1120e-03, 
 2DIAGNOSTIC,   793, -9.359974861145e-01, 4.013809018488e-08, 3.4525e+00, 4.0970e-03, 
 2DIAGNOSTIC,   794, -9.359974861145e-01, 4.008750664752e-08, 3.4565e+00, 3.9659e-03, 
 2DIAGNOSTIC,   795, -9.359974861145e-01, 4.003705100786e-08, 3.4605e+00, 3.9632e-03, 
 2DIAGNOSTIC,   796, -9.359974861145e-01, 3.998672326588e-08, 3.4645e+00, 4.0421e-03, 
 2DIAGNOSTIC,   797, -9.359974861145e-01, 3.993651986889e-08, 3.4686e+00, 4.0801e-03, 
 2DIAGNOSTIC,   798, -9.359974861145e-01, 3.988644436959e-08, 3.4728e+00, 4.1771e-03, 
 2DIAGNOSTIC,   799, -9.359974861145e-01, 3.983649321526e-08, 3.4767e+00, 3.9921e-03, 
 2DIAGNOSTIC,   800, -9.359974861145e-01, 3.978666640592e-08, 3.4807e+00, 3.9978e-03, 
 2DIAGNOSTIC,   801, -9.359974861145e-01, 3.973696749426e-08, 3.4848e+00, 4.0960e-03, 
 2DIAGNOSTIC,   802, -9.359974861145e-01, 3.968738937488e-08, 3.4889e+00, 4.0359e-03, 
 2DIAGNOSTIC,   803, -9.359974861145e-01, 3.963793560047e-08, 3.4928e+00, 3.9551e-03, 
 2DIAGNOSTIC,   804, -9.359974861145e-01, 3.958860261832e-08, 3.4969e+00, 4.0329e-03, 
 2DIAGNOSTIC,   805, -9.359974861145e-01, 3.953939398116e-08, 3.5010e+00, 4.0929e-03, 
 2DIAGNOSTIC,   806, -9.359974861145e-01, 3.949030968897e-08, 3.5050e+00, 4.0350e-03, 
 2DIAGNOSTIC,   807, -9.359974861145e-01, 3.944134618905e-08, 3.5090e+00, 4.0250e-03, 
 2DIAGNOSTIC,   808, -9.359974861145e-01, 3.939250348139e-08, 3.5130e+00, 4.0209e-03, 
 2DIAGNOSTIC,   809, -9.359974861145e-01, 3.934378156600e-08, 3.5169e+00, 3.8769e-03, 
 2DIAGNOSTIC,   810, -9.359974861145e-01, 3.929517689016e-08, 3.5210e+00, 4.0569e-03, 
 2DIAGNOSTIC,   811, -9.359974861145e-01, 3.924669655930e-08, 3.5250e+00, 4.0181e-03, 
 2DIAGNOSTIC,   812, -9.359974861145e-01, 3.919833346799e-08, 3.5290e+00, 3.9921e-03, 
 2DIAGNOSTIC,   813, -9.359974861145e-01, 3.915009116895e-08, 3.5330e+00, 3.9918e-03, 
 2DIAGNOSTIC,   814, -9.359974861145e-01, 3.910196610946e-08, 3.5369e+00, 3.9480e-03, 
 2DIAGNOSTIC,   815, -9.359974861145e-01, 3.905395828951e-08, 3.5411e+00, 4.1301e-03, 
 2DIAGNOSTIC,   816, -9.359974861145e-01, 3.900607126184e-08, 3.5452e+00, 4.1249e-03, 
 2DIAGNOSTIC,   817, -9.359974861145e-01, 3.895829792100e-08, 3.5493e+00, 4.1270e-03, 
 2DIAGNOSTIC,   818, -9.359974861145e-01, 3.891064537243e-08, 3.5534e+00, 4.1261e-03, 
 2DIAGNOSTIC,   819, -9.359974861145e-01, 3.886310651069e-08, 3.5574e+00, 3.9918e-03, 
 2DIAGNOSTIC,   820, -9.359974861145e-01, 3.881568488850e-08, 3.5614e+00, 3.9911e-03, 
 2DIAGNOSTIC,   821, -9.359974861145e-01, 3.876837695316e-08, 3.5654e+00, 3.9980e-03, 
 2DIAGNOSTIC,   822, -9.359974861145e-01, 3.872118625736e-08, 3.5695e+00, 4.1358e-03, 
 2DIAGNOSTIC,   823, -9.359974861145e-01, 3.867410924840e-08, 3.5737e+00, 4.1189e-03, 
 2DIAGNOSTIC,   824, -9.359974861145e-01, 3.862714592628e-08, 3.5778e+00, 4.1070e-03, 
 2DIAGNOSTIC,   825, -9.359974861145e-01, 3.858029629100e-08, 3.5820e+00, 4.2000e-03, 
 2DIAGNOSTIC,   826, -9.359974861145e-01, 3.853356389527e-08, 3.5860e+00, 4.0371e-03, 
 2DIAGNOSTIC,   827, -9.359974861145e-01, 3.848694163366e-08, 3.5901e+00, 4.0720e-03, 
 2DIAGNOSTIC,   828, -9.359974861145e-01, 3.844043305889e-08, 3.5941e+00, 4.0150e-03, 
 2DIAGNOSTIC,   829, -9.359974861145e-01, 3.839403461825e-08, 3.5981e+00, 3.9899e-03, 
 2DIAGNOSTIC,   830, -9.359974861145e-01, 3.834774986444e-08, 3.6021e+00, 4.0181e-03, 
 2DIAGNOSTIC,   831, -9.359974861145e-01, 3.830157524476e-08, 3.6061e+00, 3.9878e-03, 
 2DIAGNOSTIC,   832, -9.359974861145e-01, 3.825551431191e-08, 3.6101e+00, 4.0250e-03, 
 2DIAGNOSTIC,   833, -9.359974861145e-01, 3.820955996048e-08, 3.6144e+00, 4.2632e-03, 
 2DIAGNOSTIC,   834, -9.359974861145e-01, 3.816371929588e-08, 3.6185e+00, 4.1280e-03, 
 2DIAGNOSTIC,   835, -9.359974861145e-01, 3.811798876541e-08, 3.6226e+00, 4.1089e-03, 
 2DIAGNOSTIC,   836, -9.359974861145e-01, 3.807236481634e-08, 3.6269e+00, 4.2741e-03, 
 2DIAGNOSTIC,   837, -9.359974861145e-01, 3.802685100140e-08, 3.6309e+00, 4.0312e-03, 
 2DIAGNOSTIC,   838, -9.359974861145e-01, 3.798144732059e-08, 3.6351e+00, 4.1840e-03, 
 2DIAGNOSTIC,   839, -9.359974861145e-01, 3.793615022119e-08, 3.6393e+00, 4.1549e-03, 
 2DIAGNOSTIC,   840, -9.359974861145e-01, 3.789096325590e-08, 3.6433e+00, 4.0340e-03, 
 2DIAGNOSTIC,   841, -9.359974861145e-01, 3.784588287203e-08, 3.6473e+00, 4.0469e-03, 
 2DIAGNOSTIC,   842, -9.359974861145e-01, 3.780090906957e-08, 3.6515e+00, 4.1780e-03, 
 2DIAGNOSTIC,   843, -9.359974861145e-01, 3.775604184852e-08, 3.6556e+00, 4.1039e-03, 
 2DIAGNOSTIC,   844, -9.359974861145e-01, 3.771128120889e-08, 3.6596e+00, 4.0228e-03, 
 2DIAGNOSTIC,   845, -9.359974861145e-01, 3.766662715066e-08, 3.6638e+00, 4.1041e-03, 
 2DIAGNOSTIC,   846, -9.359974861145e-01, 3.762207967384e-08, 3.6678e+00, 4.0779e-03, 
 2DIAGNOSTIC,   847, -9.359974861145e-01, 3.757763522572e-08, 3.6720e+00, 4.1990e-03, 
 2DIAGNOSTIC,   848, -9.359974861145e-01, 3.753329380629e-08, 3.6761e+00, 4.0400e-03, 
 2DIAGNOSTIC,   849, -9.359974861145e-01, 3.748906252099e-08, 3.6801e+00, 4.0259e-03, 
 2DIAGNOSTIC,   850, -9.359974861145e-01, 3.744493071167e-08, 3.6842e+00, 4.0550e-03, 
 2DIAGNOSTIC,   851, -9.359974861145e-01, 3.740090548376e-08, 3.6883e+00, 4.1521e-03, 
 2DIAGNOSTIC,   852, -9.359974861145e-01, 3.735698328455e-08, 3.6923e+00, 4.0350e-03, 
 2DIAGNOSTIC,   853, -9.359974861145e-01, 3.731316056133e-08, 3.6963e+00, 4.0090e-03, 
 2DIAGNOSTIC,   854, -9.359974265099e-01, 3.724824182427e-08, 3.7004e+00, 4.0781e-03, 
 2DIAGNOSTIC,   855, -9.359974265099e-01, 3.718614749459e-08, 3.7044e+00, 4.0081e-03, 
 2DIAGNOSTIC,   856, -9.359974265099e-01, 3.712782259413e-08, 3.7085e+00, 4.0748e-03, 
 2DIAGNOSTIC,   857, -9.359974265099e-01, 3.707461360136e-08, 3.7125e+00, 4.0350e-03, 
 2DIAGNOSTIC,   858, -9.359974265099e-01, 3.702789186377e-08, 3.7166e+00, 4.0250e-03, 
 2DIAGNOSTIC,   859, -9.359974265099e-01, 3.698824357912e-08, 3.7206e+00, 3.9990e-03, 
 2DIAGNOSTIC,   860, -9.359974265099e-01, 3.695503636436e-08, 3.7246e+00, 4.0519e-03, 
 2DIAGNOSTIC,   861, -9.359974265099e-01, 3.692686334489e-08, 3.7287e+00, 4.1051e-03, 
 2DIAGNOSTIC,   862, -9.359974265099e-01, 3.690234962050e-08, 3.7328e+00, 4.0889e-03, 
 2DIAGNOSTIC,   863, -9.359974265099e-01, 3.688055016937e-08, 3.7369e+00, 4.0531e-03, 
 2DIAGNOSTIC,   864, -9.359974265099e-01, 3.683783944552e-08, 3.7410e+00, 4.1230e-03, 
 2DIAGNOSTIC,   865, -9.359974265099e-01, 3.679522819766e-08, 3.7451e+00, 4.0970e-03, 
 2DIAGNOSTIC,   866, -9.359974265099e-01, 3.675271642578e-08, 3.7492e+00, 4.1502e-03, 
 2DIAGNOSTIC,   867, -9.359974265099e-01, 3.671030057717e-08, 3.7533e+00, 4.0221e-03, 
 2DIAGNOSTIC,   868, -9.359974265099e-01, 3.666798420454e-08, 3.7574e+00, 4.1029e-03, 
 2DIAGNOSTIC,   869, -9.359974265099e-01, 3.662576375518e-08, 3.7615e+00, 4.1301e-03, 
 2DIAGNOSTIC,   870, -9.359974265099e-01, 3.658364278181e-08, 3.7655e+00, 3.9802e-03, 
 2DIAGNOSTIC,   871, -9.359974265099e-01, 3.654161773170e-08, 3.7694e+00, 3.9659e-03, 
 2DIAGNOSTIC,   872, -9.359974265099e-01, 3.649968860486e-08, 3.7735e+00, 4.0720e-03, 
 2DIAGNOSTIC,   873, -9.359974265099e-01, 3.645785540130e-08, 3.7776e+00, 4.0870e-03, 
 2DIAGNOSTIC,   874, -9.359974265099e-01, 3.641611812100e-08, 3.7817e+00, 4.0929e-03, 
 2DIAGNOSTIC,   875, -9.359974265099e-01, 3.637447676397e-08, 3.7858e+00, 4.1361e-03, 
 2DIAGNOSTIC,   876, -9.359974265099e-01, 3.633293133021e-08, 3.7899e+00, 4.1039e-03, 
 2DIAGNOSTIC,   877, -9.359974265099e-01, 3.629147826700e-08, 3.7939e+00, 3.9990e-03, 
 2DIAGNOSTIC,   878, -9.359974265099e-01, 3.625012112707e-08, 3.7981e+00, 4.1938e-03, 
 2DIAGNOSTIC,   879, -9.359974265099e-01, 3.620885991040e-08, 3.8021e+00, 3.9601e-03, 
 2DIAGNOSTIC,   880, -9.359974265099e-01, 3.616768751158e-08, 3.8061e+00, 4.0150e-03, 
 2DIAGNOSTIC,   881, -9.359974861145e-01, 3.614716703737e-08, 3.8101e+00, 4.0112e-03, 
 2DIAGNOSTIC,   882, -9.359974861145e-01, 3.612409571474e-08, 3.8142e+00, 4.0929e-03, 
 2DIAGNOSTIC,   883, -9.359974861145e-01, 3.609756760170e-08, 3.8182e+00, 4.0419e-03, 
 2DIAGNOSTIC,   884, -9.359974861145e-01, 3.606627174690e-08, 3.8223e+00, 4.0832e-03, 
 2DIAGNOSTIC,   885, -9.359974861145e-01, 3.602887943543e-08, 3.8264e+00, 4.0469e-03, 
 2DIAGNOSTIC,   886, -9.359974861145e-01, 3.598481157496e-08, 3.8305e+00, 4.1440e-03, 
 2DIAGNOSTIC,   887, -9.359974861145e-01, 3.593469344310e-08, 3.8345e+00, 3.9849e-03, 
 2DIAGNOSTIC,   888, -9.359974861145e-01, 3.587988217646e-08, 3.8385e+00, 4.0059e-03, 
 2DIAGNOSTIC,   889, -9.359974861145e-01, 3.582170648997e-08, 3.8426e+00, 4.1320e-03, 
 2DIAGNOSTIC,   890, -9.359974861145e-01, 3.576109008918e-08, 3.8468e+00, 4.1311e-03, 
 2DIAGNOSTIC,   891, -9.359974861145e-01, 3.572093376647e-08, 3.8508e+00, 4.0219e-03, 
 2DIAGNOSTIC,   892, -9.359974861145e-01, 3.568086270889e-08, 3.8549e+00, 4.0851e-03, 
 2DIAGNOSTIC,   893, -9.359974861145e-01, 3.564088757457e-08, 3.8590e+00, 4.1130e-03, 
 2DIAGNOSTIC,   894, -9.359974861145e-01, 3.560099770539e-08, 3.8631e+00, 4.1270e-03, 
 2DIAGNOSTIC,   895, -9.359974861145e-01, 3.556119665404e-08, 3.8671e+00, 3.9461e-03, 
 2DIAGNOSTIC,   896, -9.359974861145e-01, 3.552148797326e-08, 3.8711e+00, 3.9959e-03, 
 2DIAGNOSTIC,   897, -9.359974861145e-01, 3.548186455760e-08, 3.8751e+00, 4.0760e-03, 
 2DIAGNOSTIC,   898, -9.359974861145e-01, 3.544233351249e-08, 3.8791e+00, 4.0100e-03, 
 2DIAGNOSTIC,   899, -9.359974861145e-01, 3.540288773252e-08, 3.8831e+00, 3.9279e-03, 
 2DIAGNOSTIC,   900, -9.359974861145e-01, 3.536353077038e-08, 3.8870e+00, 3.9361e-03, 
 2DIAGNOSTIC,   901, -9.359974861145e-01, 3.532425907338e-08, 3.8911e+00, 4.0469e-03, 
 2DIAGNOSTIC,   902, -9.359974861145e-01, 3.528507619421e-08, 3.8953e+00, 4.1981e-03, 
 2DIAGNOSTIC,   903, -9.359974861145e-01, 3.524597858018e-08, 3.8994e+00, 4.1161e-03, 
 2DIAGNOSTIC,   904, -9.359974861145e-01, 3.520696978399e-08, 3.9034e+00, 4.0522e-03, 
 2DIAGNOSTIC,   905, -9.359974861145e-01, 3.516804625292e-08, 3.9076e+00, 4.2160e-03, 
 2DIAGNOSTIC,   906, -9.359974861145e-01, 3.512920798698e-08, 3.9117e+00, 4.0340e-03, 
 2DIAGNOSTIC,   907, -9.359974861145e-01, 3.509045498618e-08, 3.9157e+00, 4.0269e-03, 
 2DIAGNOSTIC,   908, -9.359974861145e-01, 3.505178725050e-08, 3.9196e+00, 3.8919e-03, 
 2DIAGNOSTIC,   909, -9.359974861145e-01, 3.501320833266e-08, 3.9236e+00, 4.0250e-03, 
 2DIAGNOSTIC,   910, -9.359974861145e-01, 3.497471112723e-08, 3.9278e+00, 4.1671e-03, 
 2DIAGNOSTIC,   911, -9.359974861145e-01, 3.493629918694e-08, 3.9317e+00, 3.9651e-03, 
 2DIAGNOSTIC,   912, -9.359974861145e-01, 3.489796895906e-08, 3.9358e+00, 4.0779e-03, 
 2DIAGNOSTIC,   913, -9.359974861145e-01, 3.485972754902e-08, 3.9399e+00, 4.1161e-03, 
 2DIAGNOSTIC,   914, -9.359974265099e-01, 3.480175436721e-08, 3.9441e+00, 4.1640e-03, 
 2DIAGNOSTIC,   915, -9.359974265099e-01, 3.474641374623e-08, 3.9481e+00, 4.0140e-03, 
 2DIAGNOSTIC,   916, -9.359974265099e-01, 3.469457610095e-08, 3.9521e+00, 3.9880e-03, 
 2DIAGNOSTIC,   917, -9.359974265099e-01, 3.464750264470e-08, 3.9561e+00, 3.9709e-03, 
 2DIAGNOSTIC,   918, -9.359974265099e-01, 3.460647945985e-08, 3.9601e+00, 4.0200e-03, 
 2DIAGNOSTIC,   919, -9.359974265099e-01, 3.457206076973e-08, 3.9640e+00, 3.9420e-03, 
 2DIAGNOSTIC,   920, -9.359974265099e-01, 3.454364616573e-08, 3.9680e+00, 4.0030e-03, 
 2DIAGNOSTIC,   921, -9.359974265099e-01, 3.451992824921e-08, 3.9721e+00, 4.0979e-03, 
 2DIAGNOSTIC,   922, -9.359974265099e-01, 3.449962449054e-08, 3.9762e+00, 4.0359e-03, 
 2DIAGNOSTIC,   923, -9.359974265099e-01, 3.448184671129e-08, 3.9802e+00, 4.0081e-03, 
 2DIAGNOSTIC,   924, -9.359973669052e-01, 3.442491092187e-08, 3.9841e+00, 3.9499e-03, 
 2DIAGNOSTIC,   925, -9.359973669052e-01, 3.437057571887e-08, 3.9881e+00, 3.9511e-03, 
 2DIAGNOSTIC,   926, -9.359973669052e-01, 3.431970441170e-08, 3.9922e+00, 4.0660e-03, 
 2DIAGNOSTIC,   927, -9.359973669052e-01, 3.427354400287e-08, 3.9961e+00, 3.9580e-03, 
 2DIAGNOSTIC,   928, -9.359973669052e-01, 3.423336636388e-08, 4.0002e+00, 4.1089e-03, 
 2DIAGNOSTIC,   929, -9.359973669052e-01, 3.419971861263e-08, 4.0042e+00, 3.9639e-03, 
 2DIAGNOSTIC,   930, -9.359973669052e-01, 3.417201455136e-08, 4.0084e+00, 4.1680e-03, 
 2DIAGNOSTIC,   931, -9.359973669052e-01, 3.414895033416e-08, 4.0128e+00, 4.4551e-03, 
 2DIAGNOSTIC,   932, -9.359973669052e-01, 3.412926119495e-08, 4.0168e+00, 4.0412e-03, 
 2DIAGNOSTIC,   933, -9.359973669052e-01, 3.411206961346e-08, 4.0210e+00, 4.1258e-03, 
 2DIAGNOSTIC,   934, -9.359973669052e-01, 3.407552995327e-08, 4.0251e+00, 4.0941e-03, 
 2DIAGNOSTIC,   935, -9.359974265099e-01, 3.405843074233e-08, 4.0291e+00, 4.0569e-03, 
 2DIAGNOSTIC,   936, -9.359974265099e-01, 3.403892634424e-08, 4.0331e+00, 4.0171e-03, 
 2DIAGNOSTIC,   937, -9.359974265099e-01, 3.401615344956e-08, 4.0373e+00, 4.1380e-03, 
 2DIAGNOSTIC,   938, -9.359974265099e-01, 3.398887926664e-08, 4.0415e+00, 4.1749e-03, 
 2DIAGNOSTIC,   939, -9.359974265099e-01, 3.395584968757e-08, 4.0455e+00, 4.0321e-03, 
 2DIAGNOSTIC,   940, -9.359974265099e-01, 3.391652469986e-08, 4.0496e+00, 4.1111e-03, 
 2DIAGNOSTIC,   941, -9.359974265099e-01, 3.387148339584e-08, 4.0536e+00, 4.0438e-03, 
 2DIAGNOSTIC,   942, -9.359974861145e-01, 3.384122848615e-08, 4.0578e+00, 4.1161e-03, 
 2DIAGNOSTIC,   943, -9.359974861145e-01, 3.380532476172e-08, 4.0619e+00, 4.1471e-03, 
 2DIAGNOSTIC,   944, -9.359974861145e-01, 3.376378643338e-08, 4.0659e+00, 4.0128e-03, 
 2DIAGNOSTIC,   945, -9.359974861145e-01, 3.373698120868e-08, 4.0700e+00, 4.0970e-03, 
 2DIAGNOSTIC,   946, -9.359974861145e-01, 3.370446322037e-08, 4.0740e+00, 4.0162e-03, 
 2DIAGNOSTIC,   947, -9.359974861145e-01, 3.366569245600e-08, 4.0781e+00, 4.0882e-03, 
 2DIAGNOSTIC,   948, -9.359974861145e-01, 3.362124800788e-08, 4.0821e+00, 3.9690e-03, 
 2DIAGNOSTIC,   949, -9.359974861145e-01, 3.357240174751e-08, 4.0862e+00, 4.0932e-03, 
 2DIAGNOSTIC,   950, -9.359974861145e-01, 3.352039712468e-08, 4.0902e+00, 4.0150e-03, 
 2DIAGNOSTIC,   951, -9.359974861145e-01, 3.346609034338e-08, 4.0943e+00, 4.0560e-03, 
 2DIAGNOSTIC,   952, -9.359974861145e-01, 3.343091847796e-08, 4.0982e+00, 3.9730e-03, 
 2DIAGNOSTIC,   953, -9.359974861145e-01, 3.339582121953e-08, 4.1023e+00, 4.0379e-03, 
 2DIAGNOSTIC,   954, -9.359974861145e-01, 3.336079501537e-08, 4.1064e+00, 4.1430e-03, 
 2DIAGNOSTIC,   955, -9.359974861145e-01, 3.332584341820e-08, 4.1105e+00, 4.0979e-03, 
 2DIAGNOSTIC,   956, -9.359974861145e-01, 3.329096642801e-08, 4.1146e+00, 4.0579e-03, 
 2DIAGNOSTIC,   957, -9.359974861145e-01, 3.325616404481e-08, 4.1187e+00, 4.0960e-03, 
 2DIAGNOSTIC,   958, -9.359974861145e-01, 3.322143271589e-08, 4.1227e+00, 4.0460e-03, 
 2DIAGNOSTIC,   959, -9.359974861145e-01, 3.318677244124e-08, 4.1268e+00, 4.0460e-03, 
 2DIAGNOSTIC,   960, -9.359974861145e-01, 3.315218322086e-08, 4.1308e+00, 4.0629e-03, 
 2DIAGNOSTIC,   961, -9.359974861145e-01, 3.311766860747e-08, 4.1349e+00, 4.0851e-03, 
 2DIAGNOSTIC,   962, -9.359974861145e-01, 3.308322504836e-08, 4.1391e+00, 4.1599e-03, 
 2DIAGNOSTIC,   963, -9.359974861145e-01, 3.304885609623e-08, 4.1432e+00, 4.1490e-03, 
 2DIAGNOSTIC,   964, -9.359974861145e-01, 3.301455464566e-08, 4.1473e+00, 4.1251e-03, 
 2DIAGNOSTIC,   965, -9.359974861145e-01, 3.298032424937e-08, 4.1514e+00, 4.0810e-03, 
 2DIAGNOSTIC,   966, -9.359974861145e-01, 3.294616490734e-08, 4.1555e+00, 4.0369e-03, 
 2DIAGNOSTIC,   967, -9.359974861145e-01, 3.291208017231e-08, 4.1595e+00, 4.0009e-03, 
 2DIAGNOSTIC,   968, -9.359974861145e-01, 3.287806293883e-08, 4.1635e+00, 4.0522e-03, 
 2DIAGNOSTIC,   969, -9.359974861145e-01, 3.284411320692e-08, 4.1675e+00, 3.9959e-03, 
 2DIAGNOSTIC,   970, -9.359974861145e-01, 3.281023808199e-08, 4.1715e+00, 4.0479e-03, 
 2DIAGNOSTIC,   971, -9.359974265099e-01, 3.275778226453e-08, 4.1756e+00, 4.0231e-03, 
 2DIAGNOSTIC,   972, -9.359974265099e-01, 3.270779203035e-08, 4.1796e+00, 3.9999e-03, 
 2DIAGNOSTIC,   973, -9.359973669052e-01, 3.264247894208e-08, 4.1836e+00, 4.0479e-03, 
 2DIAGNOSTIC,   974, -9.359973669052e-01, 3.258402969664e-08, 4.1876e+00, 3.9542e-03, 
 2DIAGNOSTIC,   975, -9.359973669052e-01, 3.253447999896e-08, 4.1916e+00, 3.9899e-03, 
 2DIAGNOSTIC,   976, -9.359973669052e-01, 3.249553870432e-08, 4.1957e+00, 4.1270e-03, 
 2DIAGNOSTIC,   977, -9.359973669052e-01, 3.246784530120e-08, 4.1998e+00, 4.1120e-03, 
 2DIAGNOSTIC,   978, -9.359973669052e-01, 3.245069279956e-08, 4.2038e+00, 3.9818e-03, 
 2DIAGNOSTIC,   979, -9.359973669052e-01, 3.244231905342e-08, 4.2078e+00, 4.0040e-03, 
 2DIAGNOSTIC,   980, -9.359973669052e-01, 3.244065283070e-08, 4.2118e+00, 3.9651e-03, 
 2DIAGNOSTIC,   981, -9.359973669052e-01, 3.242368862288e-08, 4.2158e+00, 4.0770e-03, 
 2DIAGNOSTIC,   982, -9.359973669052e-01, 3.240909407509e-08, 4.2199e+00, 4.1149e-03, 
 2DIAGNOSTIC,   983, -9.359973669052e-01, 3.237610712858e-08, 4.2240e+00, 4.0882e-03, 
 2DIAGNOSTIC,   984, -9.359973669052e-01, 3.234319123635e-08, 4.2281e+00, 4.0290e-03, 
 2DIAGNOSTIC,   985, -9.359973669052e-01, 3.231033929296e-08, 4.2322e+00, 4.1370e-03, 
 2DIAGNOSTIC,   986, -9.359973669052e-01, 3.227755129842e-08, 4.2364e+00, 4.1680e-03, 
 2DIAGNOSTIC,   987, -9.359973669052e-01, 3.224483435815e-08, 4.2404e+00, 4.0350e-03, 
 2DIAGNOSTIC,   988, -9.359973669052e-01, 3.221218136673e-08, 4.2444e+00, 4.0150e-03, 
 2DIAGNOSTIC,   989, -9.359973669052e-01, 3.217959587687e-08, 4.2484e+00, 3.9909e-03, 
 2DIAGNOSTIC,   990, -9.359973669052e-01, 3.214707433585e-08, 4.2524e+00, 3.9680e-03, 
 2DIAGNOSTIC,   991, -9.359973669052e-01, 3.211462029640e-08, 4.2564e+00, 4.0169e-03, 
 2DIAGNOSTIC,   992, -9.359973669052e-01, 3.208223020579e-08, 4.2604e+00, 4.0441e-03, 
 2DIAGNOSTIC,   993, -9.359974861145e-01, 3.208637266994e-08, 4.2645e+00, 4.0479e-03, 
 2DIAGNOSTIC,   994, -9.359974861145e-01, 3.208590371173e-08, 4.2686e+00, 4.0932e-03, 
 2DIAGNOSTIC,   995, -9.359974861145e-01, 3.207920329373e-08, 4.2725e+00, 3.9370e-03, 
 2DIAGNOSTIC,   996, -9.359974861145e-01, 3.206395149391e-08, 4.2765e+00, 3.9990e-03, 
 2DIAGNOSTIC,   997, -9.359974861145e-01, 3.203777865224e-08, 4.2805e+00, 4.0112e-03, 
 2DIAGNOSTIC,   998, -9.359974861145e-01, 3.199966513989e-08, 4.2846e+00, 4.0729e-03, 
 2DIAGNOSTIC,   999, -9.359974861145e-01, 3.195069808726e-08, 4.2885e+00, 3.9051e-03, 
 2DIAGNOSTIC,  1000, -9.359974861145e-01, 3.189330044506e-08, 4.2925e+00, 3.9940e-03, 
DIAGNOSTIC,Iteration,metricValue,convergenceValue,ITERATION_TIME_INDEX,SINCE_LAST
 2DIAGNOSTIC,     1, -6.979205012321e-01, inf, 4.6129e+00, 3.2040e-01, 
 2DIAGNOSTIC,     2, -6.998760104179e-01, inf, 4.6207e+00, 7.8192e-03, 
 2DIAGNOSTIC,     3, -7.025729417801e-01, inf, 4.6277e+00, 7.0012e-03, 
 2DIAGNOSTIC,     4, -7.058313488960e-01, inf, 4.6345e+00, 6.8302e-03, 
 2DIAGNOSTIC,     5, -7.097296118736e-01, inf, 4.6412e+00, 6.6969e-03, 
 2DIAGNOSTIC,     6, -7.136173844337e-01, inf, 4.6481e+00, 6.8710e-03, 
 2DIAGNOSTIC,     7, -7.171332240105e-01, inf, 4.6551e+00, 6.9492e-03, 
 2DIAGNOSTIC,     8, -7.243029475212e-01, inf, 4.6641e+00, 8.9979e-03, 
 2DIAGNOSTIC,     9, -7.262670993805e-01, inf, 4.6741e+00, 1.0067e-02, 
 2DIAGNOSTIC,    10, -7.264313697815e-01, 2.905349479988e-03, 4.6808e+00, 6.6481e-03, 
 2DIAGNOSTIC,    11, -7.271928787231e-01, 2.533078659326e-03, 4.6873e+00, 6.5250e-03, 
 2DIAGNOSTIC,    12, -7.275247573853e-01, 2.071031602100e-03, 4.6938e+00, 6.5050e-03, 
 2DIAGNOSTIC,    13, -7.277810573578e-01, 1.581148710102e-03, 4.7014e+00, 7.5831e-03, 
 2DIAGNOSTIC,    14, -7.279630899429e-01, 1.114865648560e-03, 4.7124e+00, 1.1006e-02, 
 2DIAGNOSTIC,    15, -7.279717326164e-01, 7.143792463467e-04, 4.7211e+00, 8.7168e-03, 
 2DIAGNOSTIC,    16, -7.279964089394e-01, 3.963857889175e-04, 4.7292e+00, 8.0652e-03, 
 2DIAGNOSTIC,    17, -7.280178070068e-01, 1.579561503604e-04, 4.7376e+00, 8.3880e-03, 
 2DIAGNOSTIC,    18, -7.280383110046e-01, 8.872296166373e-05, 4.7460e+00, 8.4291e-03, 
 2DIAGNOSTIC,    19, -7.280688285828e-01, 6.039157597115e-05, 4.7541e+00, 8.1549e-03, 
 2DIAGNOSTIC,    20, -7.281112074852e-01, 3.325791476527e-05, 4.7626e+00, 8.4331e-03, 
 2DIAGNOSTIC,    21, -7.281640172005e-01, 2.100041092490e-05, 4.7713e+00, 8.6911e-03, 
 2DIAGNOSTIC,    22, -7.282353043556e-01, 1.516835072835e-05, 4.7814e+00, 1.0135e-02, 
 2DIAGNOSTIC,    23, -7.282488346100e-01, 1.308758601226e-05, 4.7886e+00, 7.1421e-03, 
 2DIAGNOSTIC,    24, -7.282662987709e-01, 1.337695266557e-05, 4.7955e+00, 6.9959e-03, 
 2DIAGNOSTIC,    25, -7.282896637917e-01, 1.301200154558e-05, 4.8026e+00, 7.0641e-03, 
 2DIAGNOSTIC,    26, -7.283188104630e-01, 1.236597654497e-05, 4.8123e+00, 9.6478e-03, 
 2DIAGNOSTIC,    27, -7.283490896225e-01, 1.145496935351e-05, 4.8199e+00, 7.6280e-03, 
 2DIAGNOSTIC,    28, -7.283563613892e-01, 1.002891076496e-05, 4.8269e+00, 6.9659e-03, 
 2DIAGNOSTIC,    29, -7.285470962524e-01, 1.087417604140e-05, 4.8356e+00, 8.7090e-03, 
 2DIAGNOSTIC,    30, -7.287191152573e-01, 1.347188845102e-05, 4.8438e+00, 8.2450e-03, 
 2DIAGNOSTIC,    31, -7.287858128548e-01, 1.618136775505e-05, 4.8518e+00, 7.9901e-03, 
 2DIAGNOSTIC,    32, -7.289167046547e-01, 1.980262823054e-05, 4.8596e+00, 7.8099e-03, 
 2DIAGNOSTIC,    33, -7.289822101593e-01, 2.235079409729e-05, 4.8673e+00, 7.6571e-03, 
 2DIAGNOSTIC,    34, -7.289858460426e-01, 2.292861245223e-05, 4.8758e+00, 8.5001e-03, 
 2DIAGNOSTIC,    35, -7.289910316467e-01, 2.168907849409e-05, 4.8862e+00, 1.0428e-02, 
 2DIAGNOSTIC,    36, -7.289922833443e-01, 1.888650331239e-05, 4.8935e+00, 7.2720e-03, 
 2DIAGNOSTIC,    37, -7.289942502975e-01, 1.489030000812e-05, 4.9012e+00, 7.6962e-03, 
 2DIAGNOSTIC,    38, -7.289978861809e-01, 9.842975487118e-06, 4.9081e+00, 6.9540e-03, 
 2DIAGNOSTIC,    39, -7.290027737617e-01, 6.142885013105e-06, 4.9153e+00, 7.1368e-03, 
 2DIAGNOSTIC,    40, -7.290091514587e-01, 3.876870778186e-06, 4.9230e+00, 7.7870e-03, 
 2DIAGNOSTIC,    41, -7.290118336678e-01, 2.063484998871e-06, 4.9333e+00, 1.0295e-02, 
 2DIAGNOSTIC,    42, -7.290130853653e-01, 1.432473140994e-06, 4.9402e+00, 6.8440e-03, 
 2DIAGNOSTIC,    43, -7.290167808533e-01, 1.397991354679e-06, 4.9476e+00, 7.4379e-03, 
 2DIAGNOSTIC,    44, -7.290175557137e-01, 1.339506980003e-06, 4.9555e+00, 7.8728e-03, 
 2DIAGNOSTIC,    45, -7.290183305740e-01, 1.276606099054e-06, 4.9631e+00, 7.6041e-03, 
 2DIAGNOSTIC,    46, -7.290189266205e-01, 1.178422962766e-06, 4.9704e+00, 7.3569e-03, 
 2DIAGNOSTIC,    47, -7.290188670158e-01, 1.054261588251e-06, 4.9778e+00, 7.3049e-03, 
 2DIAGNOSTIC,    48, -7.290193438530e-01, 9.325319183517e-07, 4.9855e+00, 7.7820e-03, 
 2DIAGNOSTIC,    49, -7.290209531784e-01, 8.409256224695e-07, 4.9940e+00, 8.4200e-03, 
 2DIAGNOSTIC,    50, -7.290214896202e-01, 7.886553134995e-07, 5.0028e+00, 8.8050e-03, 
 2DIAGNOSTIC,    51, -7.290231585503e-01, 7.577215228594e-07, 5.0133e+00, 1.0506e-02, 
 2DIAGNOSTIC,    52, -7.290227413177e-01, 7.209474688352e-07, 5.0213e+00, 8.0779e-03, 
 2DIAGNOSTIC,    53, -7.290231585503e-01, 7.059488211780e-07, 5.0288e+00, 7.4580e-03, 
 2DIAGNOSTIC,    54, -7.290246486664e-01, 6.977960538279e-07, 5.0364e+00, 7.6220e-03, 
 2DIAGNOSTIC,    55, -7.290242910385e-01, 6.821998113082e-07, 5.0449e+00, 8.5039e-03, 
 2DIAGNOSTIC,    56, -7.290245890617e-01, 6.639795628871e-07, 5.0518e+00, 6.8431e-03, 
 2DIAGNOSTIC,    57, -7.290240526199e-01, 6.335090461107e-07, 5.0593e+00, 7.5541e-03, 
 2DIAGNOSTIC,    58, -7.290251255035e-01, 6.074745897422e-07, 5.0670e+00, 7.6289e-03, 
 2DIAGNOSTIC,    59, -7.290248274803e-01, 5.851894684383e-07, 5.0739e+00, 6.9060e-03, 
 2DIAGNOSTIC,    60, -7.290263772011e-01, 5.728368819291e-07, 5.0815e+00, 7.6158e-03, 
 2DIAGNOSTIC,    61, -7.290254235268e-01, 5.616529392682e-07, 5.0901e+00, 8.6420e-03, 
 2DIAGNOSTIC,    62, -7.290263175964e-01, 5.504705313797e-07, 5.0979e+00, 7.7980e-03, 
 2DIAGNOSTIC,    63, -7.290258407593e-01, 5.354489758247e-07, 5.1053e+00, 7.4210e-03, 
 2DIAGNOSTIC,    64, -7.290261387825e-01, 5.291480533742e-07, 5.1127e+00, 7.3509e-03, 
 2DIAGNOSTIC,    65, -7.290263175964e-01, 5.189509124648e-07, 5.1219e+00, 9.1801e-03, 
 2DIAGNOSTIC,    66, -7.290272116661e-01, 5.135946139490e-07, 5.1317e+00, 9.8488e-03, 
 2DIAGNOSTIC,    67, -7.290264964104e-01, 4.980026346857e-07, 5.1414e+00, 9.6440e-03, 
 2DIAGNOSTIC,    68, -7.290269732475e-01, 4.900091425952e-07, 5.1507e+00, 9.3701e-03, 
 2DIAGNOSTIC,    69, -7.290270328522e-01, 4.786239742316e-07, 5.1606e+00, 9.8321e-03, 
 2DIAGNOSTIC,    70, -7.290263772011e-01, 4.711148733350e-07, 5.1709e+00, 1.0329e-02, 
 2DIAGNOSTIC,    71, -7.290275096893e-01, 4.632859145204e-07, 5.1831e+00, 1.2233e-02, 
 2DIAGNOSTIC,    72, -7.290270328522e-01, 4.565599454054e-07, 5.1910e+00, 7.8499e-03, 
 2DIAGNOSTIC,    73, -7.290275692940e-01, 4.491689651331e-07, 5.1989e+00, 7.8859e-03, 
 2DIAGNOSTIC,    74, -7.290277481079e-01, 4.433044296093e-07, 5.2069e+00, 8.0891e-03, 
 2DIAGNOSTIC,    75, -7.290264368057e-01, 4.303991829602e-07, 5.2148e+00, 7.8039e-03, 
 2DIAGNOSTIC,    76, -7.290278673172e-01, 4.296461497688e-07, 5.2250e+00, 1.0280e-02, 
 2DIAGNOSTIC,    77, -7.290278673172e-01, 4.239598183631e-07, 5.2329e+00, 7.8681e-03, 
 2DIAGNOSTIC,    78, -7.290270328522e-01, 4.156958937074e-07, 5.2415e+00, 8.5580e-03, 
 2DIAGNOSTIC,    79, -7.290281653404e-01, 4.132671165280e-07, 5.2491e+00, 7.6799e-03, 
 2DIAGNOSTIC,    80, -7.290282249451e-01, 4.068133137025e-07, 5.2569e+00, 7.7460e-03, 
 2DIAGNOSTIC,    81, -7.290272712708e-01, 4.006285507785e-07, 5.2646e+00, 7.7260e-03, 
 2DIAGNOSTIC,    82, -7.290278673172e-01, 3.945644095893e-07, 5.2741e+00, 9.4552e-03, 
 2DIAGNOSTIC,    83, -7.290279269218e-01, 3.908580197276e-07, 5.2820e+00, 7.8969e-03, 
 2DIAGNOSTIC,    84, -7.290279865265e-01, 3.878621726017e-07, 5.2904e+00, 8.4131e-03, 
 2DIAGNOSTIC,    85, -7.290278673172e-01, 3.773621983783e-07, 5.2979e+00, 7.5321e-03, 
 2DIAGNOSTIC,    86, -7.290277481079e-01, 3.729988122814e-07, 5.3056e+00, 7.6869e-03, 
 2DIAGNOSTIC,    87, -7.290277481079e-01, 3.686975276196e-07, 5.3132e+00, 7.6070e-03, 
 2DIAGNOSTIC,    88, -7.290276885033e-01, 3.600886486765e-07, 5.3210e+00, 7.8459e-03, 
 2DIAGNOSTIC,    89, -7.290278077126e-01, 3.573883020636e-07, 5.3286e+00, 7.5181e-03, 
 2DIAGNOSTIC,    90, -7.290276885033e-01, 3.547370965862e-07, 5.3361e+00, 7.4980e-03, 
 2DIAGNOSTIC,    91, -7.290276885033e-01, 3.479802330730e-07, 5.3437e+00, 7.6809e-03, 
 2DIAGNOSTIC,    92, -7.290276288986e-01, 3.438904343511e-07, 5.3522e+00, 8.4801e-03, 
 2DIAGNOSTIC,    93, -7.290276288986e-01, 3.403931714274e-07, 5.3599e+00, 7.6580e-03, 
 2DIAGNOSTIC,    94, -7.290276288986e-01, 3.374685491053e-07, 5.3674e+00, 7.4692e-03, 
 2DIAGNOSTIC,    95, -7.290276288986e-01, 3.343071739437e-07, 5.3752e+00, 7.8042e-03, 
 2DIAGNOSTIC,    96, -7.290275692940e-01, 3.306303710815e-07, 5.3829e+00, 7.7682e-03, 
 2DIAGNOSTIC,    97, -7.290275692940e-01, 3.272006665611e-07, 5.3919e+00, 8.9760e-03, 
 2DIAGNOSTIC,    98, -7.290275692940e-01, 3.237369980980e-07, 5.4005e+00, 8.6470e-03, 
 2DIAGNOSTIC,    99, -7.290275692940e-01, 3.209845829133e-07, 5.4080e+00, 7.4911e-03, 
 2DIAGNOSTIC,   100, -7.290267944336e-01, 3.149031329031e-07, 5.4155e+00, 7.4999e-03, 
 2DIAGNOSTIC,   101, -7.290267348289e-01, 3.091962526014e-07, 5.4235e+00, 7.9448e-03, 
 2DIAGNOSTIC,   102, -7.290276288986e-01, 3.074047185692e-07, 5.4314e+00, 7.9260e-03, 
 2DIAGNOSTIC,   103, -7.290276288986e-01, 3.060041251501e-07, 5.4398e+00, 8.4250e-03, 
 2DIAGNOSTIC,   104, -7.290276288986e-01, 3.050239456570e-07, 5.4479e+00, 8.0891e-03, 
 2DIAGNOSTIC,   105, -7.290275692940e-01, 3.041049296826e-07, 5.4554e+00, 7.4649e-03, 
 2DIAGNOSTIC,   106, -7.290275692940e-01, 3.029515198705e-07, 5.4633e+00, 7.8969e-03, 
 2DIAGNOSTIC,   107, -7.290267944336e-01, 2.986800495819e-07, 5.4708e+00, 7.4801e-03, 
 2DIAGNOSTIC,   108, -7.290267348289e-01, 2.942333310330e-07, 5.4777e+00, 6.9301e-03, 
 2DIAGNOSTIC,   109, -7.290276288986e-01, 2.932731604233e-07, 5.4866e+00, 8.9219e-03, 
 2DIAGNOSTIC,   110, -7.290276288986e-01, 2.894144301990e-07, 5.4954e+00, 8.7531e-03, 
 2DIAGNOSTIC,   111, -7.290275692940e-01, 2.852034981515e-07, 5.5053e+00, 9.8879e-03, 
 2DIAGNOSTIC,   112, -7.290267944336e-01, 2.817806432631e-07, 5.5153e+00, 1.0014e-02, 
 2DIAGNOSTIC,   113, -7.290276288986e-01, 2.816569235620e-07, 5.5250e+00, 9.6920e-03, 
 2DIAGNOSTIC,   114, -7.290276288986e-01, 2.813767423504e-07, 5.5345e+00, 9.5370e-03, 
 2DIAGNOSTIC,   115, -7.290276885033e-01, 2.808804424603e-07, 5.5437e+00, 9.1629e-03, 
 2DIAGNOSTIC,   116, -7.290276885033e-01, 2.802128165058e-07, 5.5531e+00, 9.4671e-03, 
 2DIAGNOSTIC,   117, -7.290276885033e-01, 2.765248439118e-07, 5.5629e+00, 9.7320e-03, 
 2DIAGNOSTIC,   118, -7.290276885033e-01, 2.721873499922e-07, 5.5719e+00, 9.0280e-03, 
 2DIAGNOSTIC,   119, -7.290276885033e-01, 2.706065629354e-07, 5.5797e+00, 7.7691e-03, 
 2DIAGNOSTIC,   120, -7.290276885033e-01, 2.688042854970e-07, 5.5869e+00, 7.2770e-03, 
 2DIAGNOSTIC,   121, -7.290276885033e-01, 2.666366185622e-07, 5.5945e+00, 7.5450e-03, 
 2DIAGNOSTIC,   122, -7.290276885033e-01, 2.616403662614e-07, 5.6019e+00, 7.4291e-03, 
 2DIAGNOSTIC,   123, -7.290276885033e-01, 2.593434373921e-07, 5.6092e+00, 7.2808e-03, 
 2DIAGNOSTIC,   124, -7.290276885033e-01, 2.570598667262e-07, 5.6166e+00, 7.4451e-03, 
 2DIAGNOSTIC,   125, -7.290277481079e-01, 2.551854549893e-07, 5.6241e+00, 7.4770e-03, 
 2DIAGNOSTIC,   126, -7.290269136429e-01, 2.507304941446e-07, 5.6318e+00, 7.7291e-03, 
 2DIAGNOSTIC,   127, -7.290269136429e-01, 2.466389048550e-07, 5.6393e+00, 7.4930e-03, 
 2DIAGNOSTIC,   128, -7.290269136429e-01, 2.430045071833e-07, 5.6469e+00, 7.5979e-03, 
 2DIAGNOSTIC,   129, -7.290269136429e-01, 2.399675906872e-07, 5.6547e+00, 7.7209e-03, 
 2DIAGNOSTIC,   130, -7.290269136429e-01, 2.376739303145e-07, 5.6621e+00, 7.4301e-03, 
 2DIAGNOSTIC,   131, -7.290269136429e-01, 2.361844479992e-07, 5.6706e+00, 8.5239e-03, 
 2DIAGNOSTIC,   132, -7.290269136429e-01, 2.354201598109e-07, 5.6799e+00, 9.3191e-03, 
 2DIAGNOSTIC,   133, -7.290269136429e-01, 2.352149124363e-07, 5.6893e+00, 9.3470e-03, 
 2DIAGNOSTIC,   134, -7.290269136429e-01, 2.354071568789e-07, 5.6982e+00, 8.9262e-03, 
 2DIAGNOSTIC,   135, -7.290269136429e-01, 2.360743991403e-07, 5.7078e+00, 9.6080e-03, 
 2DIAGNOSTIC,   136, -7.290269136429e-01, 2.343353031620e-07, 5.7175e+00, 9.6920e-03, 
 2DIAGNOSTIC,   137, -7.290269136429e-01, 2.326216446136e-07, 5.7267e+00, 9.1841e-03, 
 2DIAGNOSTIC,   138, -7.290269136429e-01, 2.309328692718e-07, 5.7363e+00, 9.6600e-03, 
 2DIAGNOSTIC,   139, -7.290269136429e-01, 2.292684229133e-07, 5.7456e+00, 9.2618e-03, 
 2DIAGNOSTIC,   140, -7.290269136429e-01, 2.276278081581e-07, 5.7547e+00, 9.0771e-03, 
 2DIAGNOSTIC,   141, -7.290269136429e-01, 2.260105134155e-07, 5.7644e+00, 9.7201e-03, 
 2DIAGNOSTIC,   142, -7.290269136429e-01, 2.244160270948e-07, 5.7736e+00, 9.1920e-03, 
 2DIAGNOSTIC,   143, -7.290269136429e-01, 2.228438802376e-07, 5.7832e+00, 9.5661e-03, 
 2DIAGNOSTIC,   144, -7.290269136429e-01, 2.212936180968e-07, 5.7928e+00, 9.6841e-03, 
 2DIAGNOSTIC,   145, -7.290269136429e-01, 2.197647575031e-07, 5.8015e+00, 8.7020e-03, 
 2DIAGNOSTIC,   146, -7.290269136429e-01, 2.182569005527e-07, 5.8094e+00, 7.8509e-03, 
 2DIAGNOSTIC,   147, -7.290269136429e-01, 2.167695782873e-07, 5.8174e+00, 7.9851e-03, 
 2DIAGNOSTIC,   148, -7.290269136429e-01, 2.153023928031e-07, 5.8253e+00, 7.9472e-03, 
 2DIAGNOSTIC,   149, -7.290269136429e-01, 2.138549319852e-07, 5.8334e+00, 8.1089e-03, 
 2DIAGNOSTIC,   150, -7.290269136429e-01, 2.124268121406e-07, 5.8414e+00, 8.0061e-03, 
 2DIAGNOSTIC,   151, -7.290269136429e-01, 2.110176353654e-07, 5.8493e+00, 7.8640e-03, 
 2DIAGNOSTIC,   152, -7.290269136429e-01, 2.096270321772e-07, 5.8571e+00, 7.7620e-03, 
 2DIAGNOSTIC,   153, -7.290269136429e-01, 2.082546330939e-07, 5.8649e+00, 7.8039e-03, 
 2DIAGNOSTIC,   154, -7.290269136429e-01, 2.069000970550e-07, 5.8729e+00, 8.0690e-03, 
 2DIAGNOSTIC,   155, -7.290269136429e-01, 2.055630545783e-07, 5.8809e+00, 7.9179e-03, 
 2DIAGNOSTIC,   156, -7.290269136429e-01, 2.042431930249e-07, 5.8888e+00, 7.9141e-03, 
 2DIAGNOSTIC,   157, -7.290269136429e-01, 2.029401713344e-07, 5.8968e+00, 7.9980e-03, 
 2DIAGNOSTIC,   158, -7.290269136429e-01, 2.016536626570e-07, 5.9067e+00, 9.8870e-03, 
 2DIAGNOSTIC,   159, -7.290269136429e-01, 2.003833685649e-07, 5.9165e+00, 9.7902e-03, 
 2DIAGNOSTIC,   160, -7.290269136429e-01, 1.991289764192e-07, 5.9258e+00, 9.3479e-03, 
 2DIAGNOSTIC,   161, -7.290269136429e-01, 1.978901877919e-07, 5.9337e+00, 7.9370e-03, 
 2DIAGNOSTIC,   162, -7.290269136429e-01, 1.966667184661e-07, 5.9416e+00, 7.8630e-03, 
 2DIAGNOSTIC,   163, -7.290269136429e-01, 1.954582842245e-07, 5.9493e+00, 7.7000e-03, 
 2DIAGNOSTIC,   164, -7.290269136429e-01, 1.942646150610e-07, 5.9574e+00, 8.0860e-03, 
 2DIAGNOSTIC,   165, -7.290269136429e-01, 1.930854267584e-07, 5.9651e+00, 7.7572e-03, 
 2DIAGNOSTIC,   166, -7.290269136429e-01, 1.919204777323e-07, 5.9734e+00, 8.2490e-03, 
 2DIAGNOSTIC,   167, -7.290269136429e-01, 1.907694979764e-07, 5.9812e+00, 7.8361e-03, 
 2DIAGNOSTIC,   168, -7.290269136429e-01, 1.896322459061e-07, 5.9892e+00, 7.9551e-03, 
 2DIAGNOSTIC,   169, -7.290269136429e-01, 1.885084657260e-07, 5.9974e+00, 8.2181e-03, 
 2DIAGNOSTIC,   170, -7.290269136429e-01, 1.873979300626e-07, 6.0052e+00, 7.7889e-03, 
 2DIAGNOSTIC,   171, -7.290269136429e-01, 1.863003973313e-07, 6.0132e+00, 7.9770e-03, 
 2DIAGNOSTIC,   172, -7.290269136429e-01, 1.852156543691e-07, 6.0207e+00, 7.4930e-03, 
 2DIAGNOSTIC,   173, -7.290269136429e-01, 1.841434595917e-07, 6.0297e+00, 9.0132e-03, 
 2DIAGNOSTIC,   174, -7.290269136429e-01, 1.830836140471e-07, 6.0398e+00, 1.0142e-02, 
 2DIAGNOSTIC,   175, -7.290269136429e-01, 1.820359045723e-07, 6.0498e+00, 9.9730e-03, 
 2DIAGNOSTIC,   176, -7.290269136429e-01, 1.810001037938e-07, 6.0597e+00, 9.9349e-03, 
 2DIAGNOSTIC,   177, -7.290269136429e-01, 1.799760269705e-07, 6.0694e+00, 9.7229e-03, 
 2DIAGNOSTIC,   178, -7.290269136429e-01, 1.789634893612e-07, 6.0792e+00, 9.7668e-03, 
 2DIAGNOSTIC,   179, -7.290269136429e-01, 1.779622635922e-07, 6.0871e+00, 7.9181e-03, 
 2DIAGNOSTIC,   180, -7.290269136429e-01, 1.769721791334e-07, 6.0951e+00, 7.9679e-03, 
 2DIAGNOSTIC,   181, -7.290269136429e-01, 1.759930512435e-07, 6.1035e+00, 8.4240e-03, 
 2DIAGNOSTIC,   182, -7.290269136429e-01, 1.750247093923e-07, 6.1114e+00, 7.8740e-03, 
 2DIAGNOSTIC,   183, -7.290269136429e-01, 1.740669546280e-07, 6.1193e+00, 7.9000e-03, 
 2DIAGNOSTIC,   184, -7.290269136429e-01, 1.731196306309e-07, 6.1273e+00, 8.0221e-03, 
 2DIAGNOSTIC,   185, -7.290269136429e-01, 1.721825526602e-07, 6.1351e+00, 7.7350e-03, 
 2DIAGNOSTIC,   186, -7.290269136429e-01, 1.712555786071e-07, 6.1428e+00, 7.7469e-03, 
 2DIAGNOSTIC,   187, -7.290269136429e-01, 1.703385237306e-07, 6.1527e+00, 9.9342e-03, 
 2DIAGNOSTIC,   188, -7.290269136429e-01, 1.694312317113e-07, 6.1624e+00, 9.7098e-03, 
 2DIAGNOSTIC,   189, -7.290269136429e-01, 1.685335604407e-07, 6.1718e+00, 9.3942e-03, 
 2DIAGNOSTIC,   190, -7.290269136429e-01, 1.676453535993e-07, 6.1815e+00, 9.6881e-03, 
 2DIAGNOSTIC,   191, -7.290269136429e-01, 1.667664548677e-07, 6.1905e+00, 8.9922e-03, 
 2DIAGNOSTIC,   192, -7.290269136429e-01, 1.658967363483e-07, 6.1983e+00, 7.7310e-03, 
 2DIAGNOSTIC,   193, -7.290269136429e-01, 1.650360275107e-07, 6.2063e+00, 8.0030e-03, 
 2DIAGNOSTIC,   194, -7.290269136429e-01, 1.641842004574e-07, 6.2142e+00, 7.9072e-03, 
 2DIAGNOSTIC,   195, -7.290269136429e-01, 1.633411415014e-07, 6.2219e+00, 7.6900e-03, 
 2DIAGNOSTIC,   196, -7.290269136429e-01, 1.625066801125e-07, 6.2295e+00, 7.6630e-03, 
 2DIAGNOSTIC,   197, -7.290269136429e-01, 1.616807026039e-07, 6.2375e+00, 7.9560e-03, 
 2DIAGNOSTIC,   198, -7.290269136429e-01, 1.608630810779e-07, 6.2452e+00, 7.7090e-03, 
 2DIAGNOSTIC,   199, -7.290269136429e-01, 1.600536876367e-07, 6.2529e+00, 7.7231e-03, 
 2DIAGNOSTIC,   200, -7.290269136429e-01, 1.592523943827e-07, 6.2611e+00, 8.1618e-03, 
 2DIAGNOSTIC,   201, -7.290269136429e-01, 1.584590876291e-07, 6.2688e+00, 7.7519e-03, 
 2DIAGNOSTIC,   202, -7.290269136429e-01, 1.576736536890e-07, 6.2767e+00, 7.9010e-03, 
 2DIAGNOSTIC,   203, -7.290269136429e-01, 1.568959646647e-07, 6.2842e+00, 7.4320e-03, 
 2DIAGNOSTIC,   204, -7.290269136429e-01, 1.561259068694e-07, 6.2923e+00, 8.1980e-03, 
 2DIAGNOSTIC,   205, -7.290269136429e-01, 1.553633666163e-07, 6.2997e+00, 7.3361e-03, 
 2DIAGNOSTIC,   206, -7.290269136429e-01, 1.546082444293e-07, 6.3073e+00, 7.6051e-03, 
 2DIAGNOSTIC,   207, -7.290269136429e-01, 1.538604266216e-07, 6.3149e+00, 7.6439e-03, 
 2DIAGNOSTIC,   208, -7.290269136429e-01, 1.531197995064e-07, 6.3226e+00, 7.6449e-03, 
 2DIAGNOSTIC,   209, -7.290269136429e-01, 1.523862778186e-07, 6.3297e+00, 7.1650e-03, 
 2DIAGNOSTIC,   210, -7.290269136429e-01, 1.516597478712e-07, 6.3368e+00, 7.0581e-03, 
 2DIAGNOSTIC,   211, -7.290269136429e-01, 1.509401101885e-07, 6.3443e+00, 7.5200e-03, 
 2DIAGNOSTIC,   212, -7.290269136429e-01, 1.502272652942e-07, 6.3517e+00, 7.3600e-03, 
 2DIAGNOSTIC,   213, -7.290269136429e-01, 1.495211421343e-07, 6.3593e+00, 7.5829e-03, 
 2DIAGNOSTIC,   214, -7.290269136429e-01, 1.488215986001e-07, 6.3671e+00, 7.8170e-03, 
 2DIAGNOSTIC,   215, -7.290269136429e-01, 1.481285920590e-07, 6.3747e+00, 7.6580e-03, 
 2DIAGNOSTIC,   216, -7.290269136429e-01, 1.474419946135e-07, 6.3826e+00, 7.8380e-03, 
 2DIAGNOSTIC,   217, -7.290269136429e-01, 1.467617494200e-07, 6.3901e+00, 7.5209e-03, 
 2DIAGNOSTIC,   218, -7.290269136429e-01, 1.460877427917e-07, 6.3980e+00, 7.8740e-03, 
 2DIAGNOSTIC,   219, -7.290269136429e-01, 1.454198894635e-07, 6.4057e+00, 7.6849e-03, 
 2DIAGNOSTIC,   220, -7.290269136429e-01, 1.447581325920e-07, 6.4144e+00, 8.7769e-03, 
 2DIAGNOSTIC,   221, -7.290269136429e-01, 1.441023584903e-07, 6.4236e+00, 9.1221e-03, 
 2DIAGNOSTIC,   222, -7.290269136429e-01, 1.434525103150e-07, 6.4330e+00, 9.4821e-03, 
 2DIAGNOSTIC,   223, -7.290269136429e-01, 1.428084885902e-07, 6.4423e+00, 9.2299e-03, 
 2DIAGNOSTIC,   224, -7.290269136429e-01, 1.421702222615e-07, 6.4513e+00, 9.0380e-03, 
 2DIAGNOSTIC,   225, -7.290269136429e-01, 1.415376402747e-07, 6.4608e+00, 9.4922e-03, 
 2DIAGNOSTIC,   226, -7.290269136429e-01, 1.409106573647e-07, 6.4696e+00, 8.8401e-03, 
 2DIAGNOSTIC,   227, -7.290269136429e-01, 1.402892166880e-07, 6.4784e+00, 8.7209e-03, 
 2DIAGNOSTIC,   228, -7.290269136429e-01, 1.396732187686e-07, 6.4873e+00, 8.8949e-03, 
 2DIAGNOSTIC,   229, -7.290269136429e-01, 1.390626067632e-07, 6.4961e+00, 8.8658e-03, 
 2DIAGNOSTIC,   230, -7.290269136429e-01, 1.384573238283e-07, 6.5058e+00, 9.6650e-03, 
 2DIAGNOSTIC,   231, -7.290269136429e-01, 1.378572846988e-07, 6.5149e+00, 9.1231e-03, 
 2DIAGNOSTIC,   232, -7.290269136429e-01, 1.372624183205e-07, 6.5242e+00, 9.2549e-03, 
 2DIAGNOSTIC,   233, -7.290269136429e-01, 1.366726536389e-07, 6.5334e+00, 9.2311e-03, 
 2DIAGNOSTIC,   234, -7.290269136429e-01, 1.360879480217e-07, 6.5423e+00, 8.9378e-03, 
 2DIAGNOSTIC,   235, -7.290269136429e-01, 1.355082304144e-07, 6.5508e+00, 8.5151e-03, 
 2DIAGNOSTIC,   236, -7.290269136429e-01, 1.349334155520e-07, 6.5602e+00, 9.3348e-03, 
 2DIAGNOSTIC,   237, -7.290269136429e-01, 1.343634608020e-07, 6.5700e+00, 9.8419e-03, 
 2DIAGNOSTIC,   238, -7.290269136429e-01, 1.337983093208e-07, 6.5789e+00, 8.9030e-03, 
 2DIAGNOSTIC,   239, -7.290269136429e-01, 1.332378900543e-07, 6.5879e+00, 8.9440e-03, 
 2DIAGNOSTIC,   240, -7.290269136429e-01, 1.326821319481e-07, 6.5970e+00, 9.0930e-03, 
 2DIAGNOSTIC,   241, -7.290269136429e-01, 1.321310065805e-07, 6.6061e+00, 9.1188e-03, 
 2DIAGNOSTIC,   242, -7.290269136429e-01, 1.315844428973e-07, 6.6155e+00, 9.3892e-03, 
 2DIAGNOSTIC,   243, -7.290269136429e-01, 1.310423698442e-07, 6.6242e+00, 8.7650e-03, 
 2DIAGNOSTIC,   244, -7.290269136429e-01, 1.305047447886e-07, 6.6328e+00, 8.5881e-03, 
 2DIAGNOSTIC,   245, -7.290269136429e-01, 1.299715250980e-07, 6.6424e+00, 9.5391e-03, 
 2DIAGNOSTIC,   246, -7.290269136429e-01, 1.294426397180e-07, 6.6513e+00, 8.9149e-03, 
 2DIAGNOSTIC,   247, -7.290269136429e-01, 1.289180318054e-07, 6.6604e+00, 9.1610e-03, 
 2DIAGNOSTIC,   248, -7.290269136429e-01, 1.283976729383e-07, 6.6693e+00, 8.8322e-03, 
 2DIAGNOSTIC,   249, -7.290269136429e-01, 1.278814920624e-07, 6.6778e+00, 8.5020e-03, 
 2DIAGNOSTIC,   250, -7.290269136429e-01, 1.273694465453e-07, 6.6865e+00, 8.7430e-03, 
 2DIAGNOSTIC,   251, -7.290269136429e-01, 1.268614795435e-07, 6.6949e+00, 8.3830e-03, 
 2DIAGNOSTIC,   252, -7.290269136429e-01, 1.263575484245e-07, 6.7039e+00, 9.0179e-03, 
 2DIAGNOSTIC,   253, -7.290269136429e-01, 1.258576105556e-07, 6.7123e+00, 8.3840e-03, 
 2DIAGNOSTIC,   254, -7.290269136429e-01, 1.253616090935e-07, 6.7208e+00, 8.4980e-03, 
 2DIAGNOSTIC,   255, -7.290269136429e-01, 1.248695014056e-07, 6.7298e+00, 8.9781e-03, 
 2DIAGNOSTIC,   256, -7.290269136429e-01, 1.243812448593e-07, 6.7386e+00, 8.8351e-03, 
 2DIAGNOSTIC,   257, -7.290269136429e-01, 1.238967968220e-07, 6.7472e+00, 8.5509e-03, 
 2DIAGNOSTIC,   258, -7.290269136429e-01, 1.234161004504e-07, 6.7543e+00, 7.1819e-03, 
 2DIAGNOSTIC,   259, -7.290269136429e-01, 1.229391131119e-07, 6.7622e+00, 7.8502e-03, 
 2DIAGNOSTIC,   260, -7.290269136429e-01, 1.224658205956e-07, 6.7700e+00, 7.8201e-03, 
 2DIAGNOSTIC,   261, -7.290269136429e-01, 1.219961376364e-07, 6.7780e+00, 7.9360e-03, 
 2DIAGNOSTIC,   262, -7.290269136429e-01, 1.215300500235e-07, 6.7859e+00, 7.9961e-03, 
 2DIAGNOSTIC,   263, -7.290269136429e-01, 1.210675151242e-07, 6.7936e+00, 7.6771e-03, 
 2DIAGNOSTIC,   264, -7.290269136429e-01, 1.206084760952e-07, 6.8012e+00, 7.5321e-03, 
 2DIAGNOSTIC,   265, -7.290269136429e-01, 1.201529187256e-07, 6.8088e+00, 7.6530e-03, 
 2DIAGNOSTIC,   266, -7.290269136429e-01, 1.197007861720e-07, 6.8162e+00, 7.3540e-03, 
 2DIAGNOSTIC,   267, -7.290269136429e-01, 1.192520358018e-07, 6.8237e+00, 7.5500e-03, 
 2DIAGNOSTIC,   268, -7.290269136429e-01, 1.188066391933e-07, 6.8314e+00, 7.7310e-03, 
 2DIAGNOSTIC,   269, -7.290269136429e-01, 1.183645608194e-07, 6.8389e+00, 7.4241e-03, 
 2DIAGNOSTIC,   270, -7.290269136429e-01, 1.179257580475e-07, 6.8466e+00, 7.7140e-03, 
 2DIAGNOSTIC,   271, -7.290269136429e-01, 1.174902024559e-07, 6.8549e+00, 8.3489e-03, 
 2DIAGNOSTIC,   272, -7.290269136429e-01, 1.170578443066e-07, 6.8632e+00, 8.3129e-03, 
 2DIAGNOSTIC,   273, -7.290269136429e-01, 1.166286622833e-07, 6.8716e+00, 8.3692e-03, 
 2DIAGNOSTIC,   274, -7.290269136429e-01, 1.162026137536e-07, 6.8803e+00, 8.6410e-03, 
 2DIAGNOSTIC,   275, -7.290269136429e-01, 1.157796702955e-07, 6.8890e+00, 8.7380e-03, 
 2DIAGNOSTIC,   276, -7.290269136429e-01, 1.153597892767e-07, 6.8974e+00, 8.4510e-03, 
 2DIAGNOSTIC,   277, -7.290269136429e-01, 1.149429422753e-07, 6.9065e+00, 9.0082e-03, 
 2DIAGNOSTIC,   278, -7.290269136429e-01, 1.145291008697e-07, 6.9152e+00, 8.7228e-03, 
 2DIAGNOSTIC,   279, -7.290269136429e-01, 1.141182295328e-07, 6.9224e+00, 7.2351e-03, 
 2DIAGNOSTIC,   280, -7.290269136429e-01, 1.137102927373e-07, 6.9301e+00, 7.6809e-03, 
 2DIAGNOSTIC,   281, -7.290269136429e-01, 1.133052620617e-07, 6.9376e+00, 7.5431e-03, 
 2DIAGNOSTIC,   282, -7.290269136429e-01, 1.129031090841e-07, 6.9451e+00, 7.5002e-03, 
 2DIAGNOSTIC,   283, -7.290269136429e-01, 1.125037982774e-07, 6.9528e+00, 7.6628e-03, 
 2DIAGNOSTIC,   284, -7.290269136429e-01, 1.121073012200e-07, 6.9602e+00, 7.3998e-03, 
 2DIAGNOSTIC,   285, -7.290269136429e-01, 1.117135894901e-07, 6.9679e+00, 7.7181e-03, 
 2DIAGNOSTIC,   286, -7.290269136429e-01, 1.113226346661e-07, 6.9757e+00, 7.7419e-03, 
 2DIAGNOSTIC,   287, -7.290269136429e-01, 1.109344083261e-07, 6.9833e+00, 7.6592e-03, 
 2DIAGNOSTIC,   288, -7.290269136429e-01, 1.105488749431e-07, 6.9907e+00, 7.3411e-03, 
 2DIAGNOSTIC,   289, -7.290269136429e-01, 1.101660203062e-07, 6.9982e+00, 7.5021e-03, 
 2DIAGNOSTIC,   290, -7.290269136429e-01, 1.097858017829e-07, 7.0059e+00, 7.6900e-03, 
 2DIAGNOSTIC,   291, -7.290269136429e-01, 1.094081980568e-07, 7.0134e+00, 7.5002e-03, 
 2DIAGNOSTIC,   292, -7.290269136429e-01, 1.090331878117e-07, 7.0215e+00, 8.1351e-03, 
 2DIAGNOSTIC,   293, -7.290269136429e-01, 1.086607355205e-07, 7.0301e+00, 8.6589e-03, 
 2DIAGNOSTIC,   294, -7.290269136429e-01, 1.082908198669e-07, 7.0389e+00, 8.7569e-03, 
 2DIAGNOSTIC,   295, -7.290269136429e-01, 1.079234195345e-07, 7.0478e+00, 8.9271e-03, 
 2DIAGNOSTIC,   296, -7.290269136429e-01, 1.075584989962e-07, 7.0568e+00, 8.9378e-03, 
 2DIAGNOSTIC,   297, -7.290269136429e-01, 1.071960369359e-07, 7.0657e+00, 8.9521e-03, 
 2DIAGNOSTIC,   298, -7.290269136429e-01, 1.068360120371e-07, 7.0746e+00, 8.9140e-03, 
 2DIAGNOSTIC,   299, -7.290269136429e-01, 1.064783958782e-07, 7.0836e+00, 8.9190e-03, 
 2DIAGNOSTIC,   300, -7.290269136429e-01, 1.061231671429e-07, 7.0924e+00, 8.8511e-03, 
 2DIAGNOSTIC,   301, -7.290269136429e-01, 1.057702974094e-07, 7.1012e+00, 8.8270e-03, 
 2DIAGNOSTIC,   302, -7.290269136429e-01, 1.054197724670e-07, 7.1105e+00, 9.2340e-03, 
 2DIAGNOSTIC,   303, -7.290269136429e-01, 1.050715567885e-07, 7.1192e+00, 8.7800e-03, 
 2DIAGNOSTIC,   304, -7.290269136429e-01, 1.047256361630e-07, 7.1286e+00, 9.3992e-03, 
 2DIAGNOSTIC,   305, -7.290269136429e-01, 1.043819892743e-07, 7.1374e+00, 8.8019e-03, 
 2DIAGNOSTIC,   306, -7.290269136429e-01, 1.040405877006e-07, 7.1462e+00, 8.7800e-03, 
 2DIAGNOSTIC,   307, -7.290269136429e-01, 1.037014101257e-07, 7.1553e+00, 9.0652e-03, 
 2DIAGNOSTIC,   308, -7.290269136429e-01, 1.033644352333e-07, 7.1638e+00, 8.5549e-03, 
 2DIAGNOSTIC,   309, -7.290269136429e-01, 1.030296488125e-07, 7.1728e+00, 8.9130e-03, 
 2DIAGNOSTIC,   310, -7.290269136429e-01, 1.026970224416e-07, 7.1813e+00, 8.5599e-03, 
 2DIAGNOSTIC,   311, -7.290269136429e-01, 1.023665348043e-07, 7.1901e+00, 8.7721e-03, 
 2DIAGNOSTIC,   312, -7.290269136429e-01, 1.020381716899e-07, 7.1987e+00, 8.6579e-03, 
 2DIAGNOSTIC,   313, -7.290269136429e-01, 1.017119046764e-07, 7.2072e+00, 8.4510e-03, 
 2DIAGNOSTIC,   314, -7.290269136429e-01, 1.013877195533e-07, 7.2162e+00, 8.9562e-03, 
 2DIAGNOSTIC,   315, -7.290269136429e-01, 1.010655950040e-07, 7.2246e+00, 8.4791e-03, 
 2DIAGNOSTIC,   316, -7.290269136429e-01, 1.007455097124e-07, 7.2330e+00, 8.3821e-03, 
 2DIAGNOSTIC,   317, -7.290269136429e-01, 1.004274423622e-07, 7.2414e+00, 8.3859e-03, 
 2DIAGNOSTIC,   318, -7.290269136429e-01, 1.001113787424e-07, 7.2492e+00, 7.8030e-03, 
 2DIAGNOSTIC,   319, -7.290269136429e-01, 9.979729753695e-08, 7.2564e+00, 7.1568e-03, 
 2DIAGNOSTIC,   320, -7.290269136429e-01, 9.948518453484e-08, 7.2640e+00, 7.6139e-03, 
 2DIAGNOSTIC,   321, -7.290269136429e-01, 9.917501841983e-08, 7.2712e+00, 7.2260e-03, 
 2DIAGNOSTIC,   322, -7.290269136429e-01, 9.886677787563e-08, 7.2788e+00, 7.6189e-03, 
 2DIAGNOSTIC,   323, -7.290269136429e-01, 9.856044158596e-08, 7.2862e+00, 7.3609e-03, 
 2DIAGNOSTIC,   324, -7.290269136429e-01, 9.825600955082e-08, 7.2937e+00, 7.5629e-03, 
 2DIAGNOSTIC,   325, -7.290269136429e-01, 9.795344624308e-08, 7.3010e+00, 7.2601e-03, 
 2DIAGNOSTIC,   326, -7.290269136429e-01, 9.765273745188e-08, 7.3083e+00, 7.2920e-03, 
 2DIAGNOSTIC,   327, -7.290269136429e-01, 9.735386896637e-08, 7.3157e+00, 7.4351e-03, 
 2DIAGNOSTIC,   328, -7.290269136429e-01, 9.705683368111e-08, 7.3229e+00, 7.1261e-03, 
 2DIAGNOSTIC,   329, -7.290269136429e-01, 9.676159606897e-08, 7.3301e+00, 7.2460e-03, 
 2DIAGNOSTIC,   330, -7.290269136429e-01, 9.646815612996e-08, 7.3373e+00, 7.1681e-03, 
 2DIAGNOSTIC,   331, -7.290269136429e-01, 9.617648544236e-08, 7.3451e+00, 7.8318e-03, 
 2DIAGNOSTIC,   332, -7.290269136429e-01, 9.588657690074e-08, 7.3533e+00, 8.1990e-03, 
 2DIAGNOSTIC,   333, -7.290269136429e-01, 9.559840918882e-08, 7.3622e+00, 8.8570e-03, 
 2DIAGNOSTIC,   334, -7.290269136429e-01, 9.531196809576e-08, 7.3696e+00, 7.4270e-03, 
 2DIAGNOSTIC,   335, -7.290269136429e-01, 9.502723230526e-08, 7.3772e+00, 7.6051e-03, 
 2DIAGNOSTIC,   336, -7.290269136429e-01, 9.474420181732e-08, 7.3847e+00, 7.5221e-03, 
 2DIAGNOSTIC,   337, -7.290269136429e-01, 9.446284821024e-08, 7.3921e+00, 7.3960e-03, 
 2DIAGNOSTIC,   338, -7.290269136429e-01, 9.418316437859e-08, 7.3995e+00, 7.3609e-03, 
 2DIAGNOSTIC,   339, -7.290269136429e-01, 9.390512900609e-08, 7.4068e+00, 7.3688e-03, 
 2DIAGNOSTIC,   340, -7.290269136429e-01, 9.362872788188e-08, 7.4143e+00, 7.4201e-03, 
 2DIAGNOSTIC,   341, -7.290269136429e-01, 9.335395390053e-08, 7.4216e+00, 7.3230e-03, 
 2DIAGNOSTIC,   342, -7.290269136429e-01, 9.308078574577e-08, 7.4291e+00, 7.5259e-03, 
 2DIAGNOSTIC,   343, -7.290269136429e-01, 9.280920920673e-08, 7.4367e+00, 7.6261e-03, 
 2DIAGNOSTIC,   344, -7.290269136429e-01, 9.253921717800e-08, 7.4443e+00, 7.5321e-03, 
 2DIAGNOSTIC,   345, -7.290269136429e-01, 9.227078834328e-08, 7.4520e+00, 7.7229e-03, 
 2DIAGNOSTIC,   346, -7.290269136429e-01, 9.200391559716e-08, 7.4594e+00, 7.3869e-03, 
 2DIAGNOSTIC,   347, -7.290269136429e-01, 9.173857762335e-08, 7.4683e+00, 8.9731e-03, 
 2DIAGNOSTIC,   348, -7.290269136429e-01, 9.147476731641e-08, 7.4770e+00, 8.6761e-03, 
 2DIAGNOSTIC,   349, -7.290269136429e-01, 9.121247046551e-08, 7.4844e+00, 7.3640e-03, 
 2DIAGNOSTIC,   350, -7.290269136429e-01, 9.095167285977e-08, 7.4924e+00, 7.9770e-03, 
 2DIAGNOSTIC,   351, -7.290269136429e-01, 9.069236739379e-08, 7.5000e+00, 7.5948e-03, 
 2DIAGNOSTIC,   352, -7.290269136429e-01, 9.043452564583e-08, 7.5075e+00, 7.5181e-03, 
 2DIAGNOSTIC,   353, -7.290269136429e-01, 9.017815472134e-08, 7.5151e+00, 7.6439e-03, 
 2DIAGNOSTIC,   354, -7.290269136429e-01, 8.992323330403e-08, 7.5230e+00, 7.8540e-03, 
 2DIAGNOSTIC,   355, -7.290269136429e-01, 8.966974718305e-08, 7.5303e+00, 7.3309e-03, 
 2DIAGNOSTIC,   356, -7.290269136429e-01, 8.941768214754e-08, 7.5376e+00, 7.2899e-03, 
 2DIAGNOSTIC,   357, -7.290269136429e-01, 8.916703109207e-08, 7.5452e+00, 7.6020e-03, 
 2DIAGNOSTIC,   358, -7.290269136429e-01, 8.891778691122e-08, 7.5524e+00, 7.1590e-03, 
 2DIAGNOSTIC,   359, -7.290269136429e-01, 8.866992828871e-08, 7.5598e+00, 7.4670e-03, 
 2DIAGNOSTIC,   360, -7.290269136429e-01, 8.842344811910e-08, 7.5674e+00, 7.5328e-03, 
 2DIAGNOSTIC,   361, -7.290269136429e-01, 8.817833929697e-08, 7.5746e+00, 7.2498e-03, 
 2DIAGNOSTIC,   362, -7.290269136429e-01, 8.793458050604e-08, 7.5833e+00, 8.6911e-03, 
 2DIAGNOSTIC,   363, -7.290269136429e-01, 8.769216464088e-08, 7.5918e+00, 8.5361e-03, 
 2DIAGNOSTIC,   364, -7.290269136429e-01, 8.745108459607e-08, 7.6008e+00, 8.9400e-03, 
 2DIAGNOSTIC,   365, -7.290269136429e-01, 8.721132616074e-08, 7.6099e+00, 9.1648e-03, 
 2DIAGNOSTIC,   366, -7.290269136429e-01, 8.697287512405e-08, 7.6188e+00, 8.8730e-03, 
 2DIAGNOSTIC,   367, -7.290269136429e-01, 8.673572438056e-08, 7.6277e+00, 8.8799e-03, 
 2DIAGNOSTIC,   368, -7.290269136429e-01, 8.649986682485e-08, 7.6364e+00, 8.7509e-03, 
 2DIAGNOSTIC,   369, -7.290269136429e-01, 8.626528824607e-08, 7.6453e+00, 8.8918e-03, 
 2DIAGNOSTIC,   370, -7.290269136429e-01, 8.603198153878e-08, 7.6541e+00, 8.7321e-03, 
 2DIAGNOSTIC,   371, -7.290269136429e-01, 8.579993249214e-08, 7.6630e+00, 8.9009e-03, 
 2DIAGNOSTIC,   372, -7.290269136429e-01, 8.556912689528e-08, 7.6711e+00, 8.1310e-03, 
 2DIAGNOSTIC,   373, -7.290269136429e-01, 8.533956474821e-08, 7.6788e+00, 7.6768e-03, 
 2DIAGNOSTIC,   374, -7.290269136429e-01, 8.511122473465e-08, 7.6865e+00, 7.6959e-03, 
 2DIAGNOSTIC,   375, -7.290269136429e-01, 8.488410685459e-08, 7.6940e+00, 7.5469e-03, 
 2DIAGNOSTIC,   376, -7.290269136429e-01, 8.465819689718e-08, 7.7015e+00, 7.4351e-03, 
 2DIAGNOSTIC,   377, -7.290269136429e-01, 8.443348775700e-08, 7.7092e+00, 7.7400e-03, 
 2DIAGNOSTIC,   378, -7.290269136429e-01, 8.420997232861e-08, 7.7164e+00, 7.2210e-03, 
 2DIAGNOSTIC,   379, -7.290269136429e-01, 8.398762929573e-08, 7.7240e+00, 7.5562e-03, 
 2DIAGNOSTIC,   380, -7.290269136429e-01, 8.376646576380e-08, 7.7316e+00, 7.6408e-03, 
 2DIAGNOSTIC,   381, -7.290269136429e-01, 8.354645331110e-08, 7.7389e+00, 7.2410e-03, 
 2DIAGNOSTIC,   382, -7.290269136429e-01, 8.332759904306e-08, 7.7463e+00, 7.4859e-03, 
 2DIAGNOSTIC,   383, -7.290269136429e-01, 8.310988874882e-08, 7.7537e+00, 7.3879e-03, 
 2DIAGNOSTIC,   384, -7.290269136429e-01, 8.289331532296e-08, 7.7616e+00, 7.8900e-03, 
 2DIAGNOSTIC,   385, -7.290269136429e-01, 8.267786455463e-08, 7.7699e+00, 8.3051e-03, 
 2DIAGNOSTIC,   386, -7.290269136429e-01, 8.246353644381e-08, 7.7785e+00, 8.6210e-03, 
 2DIAGNOSTIC,   387, -7.290269136429e-01, 8.225030967424e-08, 7.7877e+00, 9.1412e-03, 
 2DIAGNOSTIC,   388, -7.290269136429e-01, 8.203818424590e-08, 7.7964e+00, 8.7471e-03, 
 2DIAGNOSTIC,   389, -7.290269136429e-01, 8.182715305338e-08, 7.8047e+00, 8.2979e-03, 
 2DIAGNOSTIC,   390, -7.290269136429e-01, 8.161720188582e-08, 7.8123e+00, 7.6122e-03, 
 2DIAGNOSTIC,   391, -7.290269136429e-01, 8.140832363779e-08, 7.8196e+00, 7.2181e-03, 
 2DIAGNOSTIC,   392, -7.290269136429e-01, 8.120051830929e-08, 7.8271e+00, 7.5810e-03, 
 2DIAGNOSTIC,   393, -7.290269136429e-01, 8.099376458404e-08, 7.8344e+00, 7.2460e-03, 
 2DIAGNOSTIC,   394, -7.290269136429e-01, 8.078806246203e-08, 7.8418e+00, 7.4301e-03, 
 2DIAGNOSTIC,   395, -7.290269136429e-01, 8.058340483785e-08, 7.8491e+00, 7.2670e-03, 
 2DIAGNOSTIC,   396, -7.290269136429e-01, 8.037978460607e-08, 7.8566e+00, 7.4859e-03, 
 2DIAGNOSTIC,   397, -7.290269136429e-01, 8.017718045039e-08, 7.8640e+00, 7.4520e-03, 
 2DIAGNOSTIC,   398, -7.290269136429e-01, 7.997560658168e-08, 7.8714e+00, 7.3731e-03, 
 2DIAGNOSTIC,   399, -7.290269136429e-01, 7.977503457823e-08, 7.8788e+00, 7.3588e-03, 
 2DIAGNOSTIC,   400, -7.290269136429e-01, 7.957547154547e-08, 7.8862e+00, 7.4320e-03, 
 2DIAGNOSTIC,   401, -7.290269136429e-01, 7.937690327253e-08, 7.8938e+00, 7.6010e-03, 
 2DIAGNOSTIC,   402, -7.290269136429e-01, 7.917932265400e-08, 7.9012e+00, 7.4120e-03, 
 2DIAGNOSTIC,   403, -7.290269136429e-01, 7.898272258444e-08, 7.9091e+00, 7.9179e-03, 
 2DIAGNOSTIC,   404, -7.290269136429e-01, 7.878709595843e-08, 7.9173e+00, 8.1871e-03, 
 2DIAGNOSTIC,   405, -7.290269136429e-01, 7.859244277597e-08, 7.9264e+00, 9.0771e-03, 
 2DIAGNOSTIC,   406, -7.290269136429e-01, 7.839874172078e-08, 7.9350e+00, 8.6410e-03, 
 2DIAGNOSTIC,   407, -7.290269136429e-01, 7.820599279285e-08, 7.9432e+00, 8.1770e-03, 
 2DIAGNOSTIC,   408, -7.290269136429e-01, 7.801419599218e-08, 7.9506e+00, 7.3569e-03, 
 2DIAGNOSTIC,   409, -7.290269136429e-01, 7.782333000250e-08, 7.9579e+00, 7.3180e-03, 
 2DIAGNOSTIC,   410, -7.290269136429e-01, 7.763340192923e-08, 7.9650e+00, 7.1661e-03, 
 2DIAGNOSTIC,   411, -7.290269136429e-01, 7.744439045609e-08, 7.9724e+00, 7.3512e-03, 
 2DIAGNOSTIC,   412, -7.290269136429e-01, 7.725630268851e-08, 7.9799e+00, 7.5331e-03, 
 2DIAGNOSTIC,   413, -7.290269136429e-01, 7.706913152106e-08, 7.9870e+00, 7.0930e-03, 
 2DIAGNOSTIC,   414, -7.290269136429e-01, 7.688285563745e-08, 7.9946e+00, 7.6170e-03, 
 2DIAGNOSTIC,   415, -7.290269136429e-01, 7.669748214312e-08, 8.0019e+00, 7.2908e-03, 
 2DIAGNOSTIC,   416, -7.290269136429e-01, 7.651300393263e-08, 8.0094e+00, 7.5099e-03, 
 2DIAGNOSTIC,   417, -7.290269136429e-01, 7.632940679514e-08, 8.0167e+00, 7.2570e-03, 
 2DIAGNOSTIC,   418, -7.290269136429e-01, 7.614669073064e-08, 8.0241e+00, 7.4031e-03, 
 2DIAGNOSTIC,   419, -7.290269136429e-01, 7.596484152828e-08, 8.0314e+00, 7.2870e-03, 
 2DIAGNOSTIC,   420, -7.290269136429e-01, 7.578386629348e-08, 8.0392e+00, 7.8650e-03, 
 2DIAGNOSTIC,   421, -7.290269136429e-01, 7.560374370996e-08, 8.0478e+00, 8.5180e-03, 
 2DIAGNOSTIC,   422, -7.290269136429e-01, 7.542448088316e-08, 8.0550e+00, 7.1859e-03, 
 2DIAGNOSTIC,   423, -7.290269136429e-01, 7.524606360221e-08, 8.0622e+00, 7.2911e-03, 
 2DIAGNOSTIC,   424, -7.290269136429e-01, 7.506849186711e-08, 8.0696e+00, 7.3771e-03, 
 2DIAGNOSTIC,   425, -7.290269136429e-01, 7.489175146702e-08, 8.0771e+00, 7.4730e-03, 
 2DIAGNOSTIC,   426, -7.290269136429e-01, 7.471584950736e-08, 8.0847e+00, 7.6501e-03, 
 2DIAGNOSTIC,   427, -7.290269136429e-01, 7.454076467184e-08, 8.0925e+00, 7.7231e-03, 
 2DIAGNOSTIC,   428, -7.290269136429e-01, 7.436649696047e-08, 8.0998e+00, 7.2868e-03, 
 2DIAGNOSTIC,   429, -7.290269136429e-01, 7.419304637324e-08, 8.1071e+00, 7.3361e-03, 
 2DIAGNOSTIC,   430, -7.290269136429e-01, 7.402040580473e-08, 8.1145e+00, 7.4201e-03, 
 2DIAGNOSTIC,   431, -7.290269136429e-01, 7.384856104409e-08, 8.1219e+00, 7.3659e-03, 
 2DIAGNOSTIC,   432, -7.290269136429e-01, 7.367751209131e-08, 8.1292e+00, 7.3528e-03, 
 2DIAGNOSTIC,   433, -7.290269136429e-01, 7.350725894639e-08, 8.1366e+00, 7.3571e-03, 
 2DIAGNOSTIC,   434, -7.290269136429e-01, 7.333778739849e-08, 8.1442e+00, 7.6220e-03, 
 2DIAGNOSTIC,   435, -7.290269136429e-01, 7.316909744759e-08, 8.1533e+00, 9.0580e-03, 
 2DIAGNOSTIC,   436, -7.290269136429e-01, 7.300118198827e-08, 8.1618e+00, 8.5609e-03, 
 2DIAGNOSTIC,   437, -7.290269136429e-01, 7.283403391511e-08, 8.1703e+00, 8.4991e-03, 
 2DIAGNOSTIC,   438, -7.290269136429e-01, 7.266764612268e-08, 8.1790e+00, 8.6401e-03, 
 2DIAGNOSTIC,   439, -7.290269136429e-01, 7.250201861098e-08, 8.1878e+00, 8.8100e-03, 
 2DIAGNOSTIC,   440, -7.290269136429e-01, 7.233715138000e-08, 8.1963e+00, 8.5189e-03, 
 2DIAGNOSTIC,   441, -7.290269136429e-01, 7.217302311346e-08, 8.2050e+00, 8.6799e-03, 
 2DIAGNOSTIC,   442, -7.290269136429e-01, 7.200964091680e-08, 8.2135e+00, 8.5561e-03, 
 2DIAGNOSTIC,   443, -7.290269136429e-01, 7.184699768459e-08, 8.2222e+00, 8.6608e-03, 
 2DIAGNOSTIC,   444, -7.290269136429e-01, 7.168508631139e-08, 8.2307e+00, 8.5490e-03, 
 2DIAGNOSTIC,   445, -7.290269136429e-01, 7.152390679721e-08, 8.2395e+00, 8.7922e-03, 
 2DIAGNOSTIC,   446, -7.290269136429e-01, 7.136344493119e-08, 8.2479e+00, 8.3661e-03, 
 2DIAGNOSTIC,   447, -7.290269136429e-01, 7.120370781877e-08, 8.2567e+00, 8.8241e-03, 
 2DIAGNOSTIC,   448, -7.290269136429e-01, 7.104468124908e-08, 8.2654e+00, 8.7118e-03, 
 2DIAGNOSTIC,   449, -7.290269136429e-01, 7.088635811670e-08, 8.2741e+00, 8.6970e-03, 
 2DIAGNOSTIC,   450, -7.290269136429e-01, 7.072874552705e-08, 8.2828e+00, 8.6830e-03, 
 2DIAGNOSTIC,   451, -7.290269136429e-01, 7.057182926928e-08, 8.2916e+00, 8.7950e-03, 
 2DIAGNOSTIC,   452, -7.290269136429e-01, 7.041560934340e-08, 8.2991e+00, 7.4770e-03, 
 2DIAGNOSTIC,   453, -7.290269136429e-01, 7.026007864397e-08, 8.3065e+00, 7.3822e-03, 
 2DIAGNOSTIC,   454, -7.290269136429e-01, 7.010523717099e-08, 8.3137e+00, 7.2651e-03, 
 2DIAGNOSTIC,   455, -7.290269136429e-01, 6.995107071361e-08, 8.3213e+00, 7.5412e-03, 
 2DIAGNOSTIC,   456, -7.290269136429e-01, 6.979758637726e-08, 8.3288e+00, 7.5040e-03, 
 2DIAGNOSTIC,   457, -7.290269136429e-01, 6.964476995108e-08, 8.3361e+00, 7.3481e-03, 
 2DIAGNOSTIC,   458, -7.290269136429e-01, 6.949262143507e-08, 8.3436e+00, 7.4470e-03, 
 2DIAGNOSTIC,   459, -7.290269136429e-01, 6.934114082924e-08, 8.3509e+00, 7.3380e-03, 
 2DIAGNOSTIC,   460, -7.290269136429e-01, 6.919031392272e-08, 8.3582e+00, 7.2691e-03, 
 2DIAGNOSTIC,   461, -7.290269136429e-01, 6.904014071552e-08, 8.3658e+00, 7.6091e-03, 
 2DIAGNOSTIC,   462, -7.290269136429e-01, 6.889062120763e-08, 8.3731e+00, 7.3180e-03, 
 2DIAGNOSTIC,   463, -7.290269136429e-01, 6.874174829363e-08, 8.3805e+00, 7.3910e-03, 
 2DIAGNOSTIC,   464, -7.290269136429e-01, 6.859351486810e-08, 8.3878e+00, 7.3280e-03, 
 2DIAGNOSTIC,   465, -7.290269136429e-01, 6.844592093103e-08, 8.3958e+00, 7.9291e-03, 
 2DIAGNOSTIC,   466, -7.290269136429e-01, 6.829896648242e-08, 8.4046e+00, 8.7960e-03, 
 2DIAGNOSTIC,   467, -7.290269136429e-01, 6.815263020599e-08, 8.4125e+00, 7.9539e-03, 
 2DIAGNOSTIC,   468, -7.290269136429e-01, 6.800692631259e-08, 8.4200e+00, 7.5219e-03, 
 2DIAGNOSTIC,   469, -7.290269136429e-01, 6.786184769680e-08, 8.4272e+00, 7.1559e-03, 
 2DIAGNOSTIC,   470, -7.290269136429e-01, 6.771738014777e-08, 8.4343e+00, 7.1101e-03, 
 2DIAGNOSTIC,   471, -7.290269136429e-01, 6.757353077091e-08, 8.4419e+00, 7.6520e-03, 
 2DIAGNOSTIC,   472, -7.290269136429e-01, 6.743028535539e-08, 8.4499e+00, 7.9160e-03, 
 2DIAGNOSTIC,   473, -7.290269136429e-01, 6.728765100661e-08, 8.4572e+00, 7.3838e-03, 
 2DIAGNOSTIC,   474, -7.290269136429e-01, 6.714562061916e-08, 8.4651e+00, 7.8309e-03, 
 2DIAGNOSTIC,   475, -7.290269136429e-01, 6.700417998218e-08, 8.4724e+00, 7.3280e-03, 
 2DIAGNOSTIC,   476, -7.290269136429e-01, 6.686334330652e-08, 8.4797e+00, 7.3280e-03, 
 2DIAGNOSTIC,   477, -7.290269136429e-01, 6.672309638134e-08, 8.4873e+00, 7.5510e-03, 
 2DIAGNOSTIC,   478, -7.290269136429e-01, 6.658343210120e-08, 8.4945e+00, 7.1981e-03, 
 2DIAGNOSTIC,   479, -7.290269136429e-01, 6.644435046610e-08, 8.5020e+00, 7.5240e-03, 
 2DIAGNOSTIC,   480, -7.290269136429e-01, 6.630585147605e-08, 8.5100e+00, 8.0421e-03, 
 2DIAGNOSTIC,   481, -7.290269136429e-01, 6.616792802561e-08, 8.5188e+00, 8.7681e-03, 
 2DIAGNOSTIC,   482, -7.290269136429e-01, 6.603058011478e-08, 8.5274e+00, 8.6050e-03, 
 2DIAGNOSTIC,   483, -7.290269136429e-01, 6.589380063815e-08, 8.5361e+00, 8.6381e-03, 
 2DIAGNOSTIC,   484, -7.290269136429e-01, 6.575758249028e-08, 8.5443e+00, 8.2009e-03, 
 2DIAGNOSTIC,   485, -7.290269136429e-01, 6.562192567117e-08, 8.5531e+00, 8.8041e-03, 
 2DIAGNOSTIC,   486, -7.290269136429e-01, 6.548683018082e-08, 8.5613e+00, 8.2359e-03, 
 2DIAGNOSTIC,   487, -7.290269136429e-01, 6.535228891380e-08, 8.5689e+00, 7.6470e-03, 
 2DIAGNOSTIC,   488, -7.290269136429e-01, 6.521830187012e-08, 8.5765e+00, 7.5500e-03, 
 2DIAGNOSTIC,   489, -7.290269136429e-01, 6.508486194434e-08, 8.5838e+00, 7.2980e-03, 
 2DIAGNOSTIC,   490, -7.290269136429e-01, 6.495196913647e-08, 8.5915e+00, 7.6652e-03, 
 2DIAGNOSTIC,   491, -7.290269136429e-01, 6.481961634108e-08, 8.5991e+00, 7.6001e-03, 
 2DIAGNOSTIC,   492, -7.290269136429e-01, 6.468779645274e-08, 8.6066e+00, 7.5369e-03, 
 2DIAGNOSTIC,   493, -7.290269136429e-01, 6.455651657689e-08, 8.6140e+00, 7.4389e-03, 
 2DIAGNOSTIC,   494, -7.290269136429e-01, 6.442576960808e-08, 8.6215e+00, 7.4999e-03, 
 2DIAGNOSTIC,   495, -7.290269136429e-01, 6.429554844090e-08, 8.6289e+00, 7.3240e-03, 
 2DIAGNOSTIC,   496, -7.290269136429e-01, 6.416585307534e-08, 8.6364e+00, 7.5252e-03, 
 2DIAGNOSTIC,   497, -7.290269136429e-01, 6.403668351140e-08, 8.6439e+00, 7.4792e-03, 
 2DIAGNOSTIC,   498, -7.290269136429e-01, 6.390803264367e-08, 8.6513e+00, 7.4720e-03, 
 2DIAGNOSTIC,   499, -7.290269136429e-01, 6.377989336670e-08, 8.6588e+00, 7.4840e-03, 
 2DIAGNOSTIC,   500, -7.290269136429e-01, 6.365226568050e-08, 8.6668e+00, 8.0118e-03, 
DIAGNOSTIC,Iteration,metricValue,convergenceValue,ITERATION_TIME_INDEX,SINCE_LAST
 2DIAGNOSTIC,     1, -6.099898815155e-01, inf, 9.1247e+00, 4.5784e-01, 
 2DIAGNOSTIC,     2, -6.105166077614e-01, inf, 9.1850e+00, 6.0304e-02, 
 2DIAGNOSTIC,     3, -6.109361052513e-01, inf, 9.2480e+00, 6.3031e-02, 
 2DIAGNOSTIC,     4, -6.111898422241e-01, inf, 9.3117e+00, 6.3709e-02, 
 2DIAGNOSTIC,     5, -6.114705801010e-01, inf, 9.4830e+00, 1.7129e-01, 
 2DIAGNOSTIC,     6, -6.114711165428e-01, inf, 9.5563e+00, 7.3322e-02, 
 2DIAGNOSTIC,     7, -6.114718317986e-01, inf, 9.6256e+00, 6.9285e-02, 
 2DIAGNOSTIC,     8, -6.114719510078e-01, inf, 9.6990e+00, 7.3416e-02, 
 2DIAGNOSTIC,     9, -6.114721894264e-01, inf, 9.7815e+00, 8.2503e-02, 
 2DIAGNOSTIC,    10, -6.114721298218e-01, 1.345561904600e-04, 9.8526e+00, 7.1029e-02, 
 2DIAGNOSTIC,    11, -6.114719510078e-01, 7.148888835218e-05, 9.9288e+00, 7.6225e-02, 
 2DIAGNOSTIC,    12, -6.114717721939e-01, 3.302058394183e-05, 1.0002e+01, 7.2712e-02, 
 2DIAGNOSTIC,    13, -6.114720106125e-01, 1.260519456991e-05, 1.0075e+01, 7.3671e-02, 
 2DIAGNOSTIC,    14, -6.114721894264e-01, 2.350672048124e-06, 1.0139e+01, 6.4293e-02, 
 2DIAGNOSTIC,    15, -6.114718914032e-01, 2.149463171008e-06, 1.0204e+01, 6.4898e-02, 
 2DIAGNOSTIC,    16, -6.114723682404e-01, 2.000381982725e-06, 1.0278e+01, 7.3873e-02, 
 2DIAGNOSTIC,    17, -6.114727854729e-01, 1.898393520605e-06, 1.0351e+01, 7.3084e-02, 
 2DIAGNOSTIC,    18, -6.114729642868e-01, 1.812317805161e-06, 1.0424e+01, 7.2625e-02, 
 2DIAGNOSTIC,    19, -6.114727258682e-01, 1.731212478262e-06, 1.0496e+01, 7.2470e-02, 
 2DIAGNOSTIC,    20, -6.114724874496e-01, 1.646624468776e-06, 1.0570e+01, 7.3678e-02, 
 2DIAGNOSTIC,    21, -6.114730834961e-01, 1.574347379574e-06, 1.0645e+01, 7.4602e-02, 
 2DIAGNOSTIC,    22, -6.114730834961e-01, 1.498430719948e-06, 1.0718e+01, 7.3185e-02, 
 2DIAGNOSTIC,    23, -6.114729642868e-01, 1.426618268852e-06, 1.0797e+01, 7.8982e-02, 
 2DIAGNOSTIC,    24, -6.114731431007e-01, 1.364409285998e-06, 1.0877e+01, 7.9967e-02, 
 2DIAGNOSTIC,    25, -6.114732623100e-01, 1.300040253227e-06, 1.0951e+01, 7.4234e-02, 
 2DIAGNOSTIC,    26, -6.114730238914e-01, 1.241846916855e-06, 1.1024e+01, 7.3182e-02, 
 2DIAGNOSTIC,    27, -6.114732027054e-01, 1.196475977849e-06, 1.1097e+01, 7.2307e-02, 
 2DIAGNOSTIC,    28, -6.114731431007e-01, 1.154768028755e-06, 1.1170e+01, 7.3610e-02, 
 2DIAGNOSTIC,    29, -6.114731431007e-01, 1.110545554184e-06, 1.1243e+01, 7.3021e-02, 
 2DIAGNOSTIC,    30, -6.114730834961e-01, 1.063093350240e-06, 1.1315e+01, 7.1850e-02, 
 2DIAGNOSTIC,    31, -6.114730238914e-01, 1.026580775942e-06, 1.1388e+01, 7.2808e-02, 
 2DIAGNOSTIC,    32, -6.114730238914e-01, 9.924203823175e-07, 1.1462e+01, 7.4536e-02, 
 2DIAGNOSTIC,    33, -6.114730238914e-01, 9.586968872100e-07, 1.1542e+01, 7.9136e-02, 
 2DIAGNOSTIC,    34, -6.114730238914e-01, 9.298611871600e-07, 1.1614e+01, 7.2568e-02, 
 2DIAGNOSTIC,    35, -6.114729642868e-01, 9.041460771186e-07, 1.1686e+01, 7.2077e-02, 
 2DIAGNOSTIC,    36, -6.114727258682e-01, 8.741259875933e-07, 1.1749e+01, 6.2770e-02, 
 2DIAGNOSTIC,    37, -6.114726066589e-01, 8.474814876536e-07, 1.1822e+01, 7.2665e-02, 
 2DIAGNOSTIC,    38, -6.114730238914e-01, 8.277664278467e-07, 1.1894e+01, 7.2832e-02, 
 2DIAGNOSTIC,    39, -6.114730238914e-01, 8.097724162326e-07, 1.1967e+01, 7.2808e-02, 
 2DIAGNOSTIC,    40, -6.114729642868e-01, 7.919408631096e-07, 1.2031e+01, 6.3827e-02, 
 2DIAGNOSTIC,    41, -6.114730238914e-01, 7.754546231808e-07, 1.2113e+01, 8.1544e-02, 
 2DIAGNOSTIC,    42, -6.114729642868e-01, 7.591186772515e-07, 1.2187e+01, 7.4369e-02, 
 2DIAGNOSTIC,    43, -6.114730834961e-01, 7.445689789165e-07, 1.2259e+01, 7.1698e-02, 
 2DIAGNOSTIC,    44, -6.114729642868e-01, 7.288905976566e-07, 1.2331e+01, 7.2249e-02, 
 2DIAGNOSTIC,    45, -6.114728450775e-01, 7.116767051230e-07, 1.2404e+01, 7.3344e-02, 
 2DIAGNOSTIC,    46, -6.114729046822e-01, 6.930733889021e-07, 1.2476e+01, 7.1295e-02, 
 2DIAGNOSTIC,    47, -6.114728450775e-01, 6.731772828061e-07, 1.2551e+01, 7.5684e-02, 
 2DIAGNOSTIC,    48, -6.114729642868e-01, 6.596544608328e-07, 1.2624e+01, 7.2719e-02, 
 2DIAGNOSTIC,    49, -6.114729046822e-01, 6.464207444878e-07, 1.2689e+01, 6.4886e-02, 
 2DIAGNOSTIC,    50, -6.114730238914e-01, 6.345784981932e-07, 1.2762e+01, 7.2909e-02, 
 2DIAGNOSTIC,    51, -6.114729642868e-01, 6.233505587261e-07, 1.2837e+01, 7.5214e-02, 
 2DIAGNOSTIC,    52, -6.114729642868e-01, 6.120253601694e-07, 1.2911e+01, 7.3864e-02, 
 2DIAGNOSTIC,    53, -6.114728450775e-01, 6.011282494001e-07, 1.2986e+01, 7.5008e-02, 
 2DIAGNOSTIC,    54, -6.114728450775e-01, 5.895731760575e-07, 1.3060e+01, 7.4148e-02, 
 2DIAGNOSTIC,    55, -6.114731431007e-01, 5.798776214760e-07, 1.3134e+01, 7.3599e-02, 
 2DIAGNOSTIC,    56, -6.114732027054e-01, 5.713135351471e-07, 1.3206e+01, 7.2635e-02, 
 2DIAGNOSTIC,    57, -6.114732623100e-01, 5.627429686683e-07, 1.3278e+01, 7.2147e-02, 
 2DIAGNOSTIC,    58, -6.114732027054e-01, 5.545660428652e-07, 1.3352e+01, 7.3845e-02, 
 2DIAGNOSTIC,    59, -6.114732027054e-01, 5.456020062411e-07, 1.3426e+01, 7.4275e-02, 
 2DIAGNOSTIC,    60, -6.114730834961e-01, 5.362805381992e-07, 1.3507e+01, 8.0783e-02, 
 2DIAGNOSTIC,    61, -6.114731431007e-01, 5.266706466500e-07, 1.3586e+01, 7.9199e-02, 
 2DIAGNOSTIC,    62, -6.114730834961e-01, 5.164592948859e-07, 1.3662e+01, 7.5834e-02, 
 2DIAGNOSTIC,    63, -6.114731431007e-01, 5.058526539869e-07, 1.3734e+01, 7.1245e-02, 
 2DIAGNOSTIC,    64, -6.114730834961e-01, 4.950034053763e-07, 1.3803e+01, 6.9505e-02, 
 2DIAGNOSTIC,    65, -6.114730834961e-01, 4.868276164416e-07, 1.3872e+01, 6.9324e-02, 
 2DIAGNOSTIC,    66, -6.114730238914e-01, 4.791320407094e-07, 1.3943e+01, 7.1076e-02, 
 2DIAGNOSTIC,    67, -6.114730834961e-01, 4.727776286018e-07, 1.4013e+01, 6.9752e-02, 
 2DIAGNOSTIC,    68, -6.114730834961e-01, 4.663753259138e-07, 1.4083e+01, 7.0020e-02, 
 2DIAGNOSTIC,    69, -6.114730834961e-01, 4.603236902767e-07, 1.4153e+01, 6.9381e-02, 
 2DIAGNOSTIC,    70, -6.114730834961e-01, 4.537230609003e-07, 1.4222e+01, 6.9254e-02, 
 2DIAGNOSTIC,    71, -6.114730834961e-01, 4.477845720885e-07, 1.4290e+01, 6.8373e-02, 
 2DIAGNOSTIC,    72, -6.114730834961e-01, 4.416321530698e-07, 1.4360e+01, 6.9709e-02, 
 2DIAGNOSTIC,    73, -6.114730238914e-01, 4.356714100595e-07, 1.4431e+01, 7.0667e-02, 
 2DIAGNOSTIC,    74, -6.114729642868e-01, 4.291461834782e-07, 1.4501e+01, 7.0183e-02, 
 2DIAGNOSTIC,    75, -6.114730238914e-01, 4.232577737184e-07, 1.4570e+01, 6.9508e-02, 
 2DIAGNOSTIC,    76, -6.114730834961e-01, 4.175804804163e-07, 1.4642e+01, 7.1303e-02, 
 2DIAGNOSTIC,    77, -6.114730834961e-01, 4.124966039853e-07, 1.4712e+01, 7.0605e-02, 
 2DIAGNOSTIC,    78, -6.114730238914e-01, 4.072678621014e-07, 1.4783e+01, 7.0471e-02, 
 2DIAGNOSTIC,    79, -6.114729642868e-01, 4.018984611776e-07, 1.4853e+01, 7.0704e-02, 
 2DIAGNOSTIC,    80, -6.114730238914e-01, 3.970797877173e-07, 1.4924e+01, 7.0549e-02, 
 2DIAGNOSTIC,    81, -6.114730238914e-01, 3.923990163912e-07, 1.4994e+01, 6.9883e-02, 
 2DIAGNOSTIC,    82, -6.114730238914e-01, 3.878751613229e-07, 1.5065e+01, 7.1359e-02, 
 2DIAGNOSTIC,    83, -6.114730834961e-01, 3.834990138785e-07, 1.5134e+01, 6.9155e-02, 
 2DIAGNOSTIC,    84, -6.114730834961e-01, 3.788664173499e-07, 1.5204e+01, 6.9887e-02, 
 2DIAGNOSTIC,    85, -6.114730238914e-01, 3.743130605471e-07, 1.5275e+01, 7.0401e-02, 
 2DIAGNOSTIC,    86, -6.114729642868e-01, 3.698644377437e-07, 1.5346e+01, 7.0988e-02, 
 2DIAGNOSTIC,    87, -6.114730238914e-01, 3.658550724595e-07, 1.5415e+01, 6.9089e-02, 
 2DIAGNOSTIC,    88, -6.114731431007e-01, 3.622217548127e-07, 1.5487e+01, 7.2078e-02, 
 2DIAGNOSTIC,    89, -6.114731431007e-01, 3.582607916996e-07, 1.5558e+01, 7.1236e-02, 
 2DIAGNOSTIC,    90, -6.114730834961e-01, 3.543319451182e-07, 1.5628e+01, 7.0437e-02, 
 2DIAGNOSTIC,    91, -6.114730834961e-01, 3.504329697535e-07, 1.5699e+01, 7.0393e-02, 
 2DIAGNOSTIC,    92, -6.114730238914e-01, 3.462117490471e-07, 1.5770e+01, 7.1302e-02, 
 2DIAGNOSTIC,    93, -6.114729046822e-01, 3.417256948524e-07, 1.5842e+01, 7.1970e-02, 
 2DIAGNOSTIC,    94, -6.114728450775e-01, 3.370948036263e-07, 1.5913e+01, 7.0769e-02, 
 2DIAGNOSTIC,    95, -6.114728450775e-01, 3.324211661493e-07, 1.5983e+01, 6.9938e-02, 
 2DIAGNOSTIC,    96, -6.114728450775e-01, 3.277803557467e-07, 1.6045e+01, 6.2081e-02, 
 2DIAGNOSTIC,    97, -6.114729642868e-01, 3.244210233788e-07, 1.6114e+01, 6.9456e-02, 
 2DIAGNOSTIC,    98, -6.114729642868e-01, 3.220299618079e-07, 1.6183e+01, 6.8229e-02, 
 2DIAGNOSTIC,    99, -6.114730238914e-01, 3.202337666153e-07, 1.6252e+01, 6.9608e-02, 
 2DIAGNOSTIC,   100, -6.114730238914e-01, 3.182923364875e-07, 1.6321e+01, 6.8714e-02, 
 2DIAGNOSTIC,   101, -6.114730834961e-01, 3.166446163050e-07, 1.6391e+01, 7.0233e-02, 
 2DIAGNOSTIC,   102, -6.114730238914e-01, 3.143232163438e-07, 1.6460e+01, 6.8757e-02, 
 2DIAGNOSTIC,   103, -6.114730834961e-01, 3.115567039913e-07, 1.6530e+01, 6.9744e-02, 
 2DIAGNOSTIC,   104, -6.114729642868e-01, 3.077797714468e-07, 1.6600e+01, 6.9927e-02, 
 2DIAGNOSTIC,   105, -6.114729642868e-01, 3.039090756829e-07, 1.6669e+01, 6.9348e-02, 
 2DIAGNOSTIC,   106, -6.114729046822e-01, 2.997426236107e-07, 1.6738e+01, 6.9536e-02, 
 2DIAGNOSTIC,   107, -6.114729642868e-01, 2.964708016862e-07, 1.6808e+01, 6.9620e-02, 
 2DIAGNOSTIC,   108, -6.114729642868e-01, 2.933252574167e-07, 1.6878e+01, 7.0171e-02, 
 2DIAGNOSTIC,   109, -6.114729642868e-01, 2.906158727001e-07, 1.6947e+01, 6.8395e-02, 
 2DIAGNOSTIC,   110, -6.114731431007e-01, 2.888315862037e-07, 1.7018e+01, 7.1343e-02, 
 2DIAGNOSTIC,   111, -6.114730238914e-01, 2.868490014407e-07, 1.7089e+01, 7.1146e-02, 
 2DIAGNOSTIC,   112, -6.114731431007e-01, 2.851307954188e-07, 1.7158e+01, 6.9015e-02, 
 2DIAGNOSTIC,   113, -6.114731431007e-01, 2.835827785930e-07, 1.7229e+01, 7.0791e-02, 
 2DIAGNOSTIC,   114, -6.114732623100e-01, 2.818578082042e-07, 1.7298e+01, 6.8779e-02, 
 2DIAGNOSTIC,   115, -6.114732623100e-01, 2.798838636409e-07, 1.7367e+01, 6.9379e-02, 
 2DIAGNOSTIC,   116, -6.114732623100e-01, 2.773911944587e-07, 1.7446e+01, 7.8992e-02, 
 2DIAGNOSTIC,   117, -6.114732623100e-01, 2.748850533862e-07, 1.7517e+01, 7.0775e-02, 
 2DIAGNOSTIC,   118, -6.114732027054e-01, 2.718936400470e-07, 1.7587e+01, 7.0477e-02, 
 2DIAGNOSTIC,   119, -6.114731431007e-01, 2.684768389827e-07, 1.7656e+01, 6.8679e-02, 
 2DIAGNOSTIC,   120, -6.114732027054e-01, 2.659493816282e-07, 1.7726e+01, 6.9548e-02, 
 2DIAGNOSTIC,   121, -6.114731431007e-01, 2.626751722801e-07, 1.7798e+01, 7.2834e-02, 
 2DIAGNOSTIC,   122, -6.114731431007e-01, 2.599428796657e-07, 1.7870e+01, 7.1236e-02, 
 2DIAGNOSTIC,   123, -6.114732027054e-01, 2.575510791303e-07, 1.7942e+01, 7.2473e-02, 
 2DIAGNOSTIC,   124, -6.114732027054e-01, 2.557430036632e-07, 1.8014e+01, 7.1616e-02, 
 2DIAGNOSTIC,   125, -6.114732027054e-01, 2.540384684835e-07, 1.8085e+01, 7.1369e-02, 
 2DIAGNOSTIC,   126, -6.114732623100e-01, 2.526249147650e-07, 1.8154e+01, 6.9133e-02, 
 2DIAGNOSTIC,   127, -6.114732623100e-01, 2.512196033422e-07, 1.8222e+01, 6.7381e-02, 
 2DIAGNOSTIC,   128, -6.114732623100e-01, 2.495524995538e-07, 1.8289e+01, 6.7845e-02, 
 2DIAGNOSTIC,   129, -6.114732623100e-01, 2.475907194821e-07, 1.8358e+01, 6.8173e-02, 
 2DIAGNOSTIC,   130, -6.114733815193e-01, 2.462109875978e-07, 1.8425e+01, 6.7060e-02, 
 2DIAGNOSTIC,   131, -6.114733815193e-01, 2.444812423619e-07, 1.8492e+01, 6.6844e-02, 
 2DIAGNOSTIC,   132, -6.114733815193e-01, 2.426160392588e-07, 1.8557e+01, 6.5759e-02, 
 2DIAGNOSTIC,   133, -6.114732623100e-01, 2.404233043762e-07, 1.8624e+01, 6.6312e-02, 
 2DIAGNOSTIC,   134, -6.114731431007e-01, 2.377420855737e-07, 1.8691e+01, 6.7538e-02, 
 2DIAGNOSTIC,   135, -6.114732623100e-01, 2.354715036290e-07, 1.8757e+01, 6.6271e-02, 
 2DIAGNOSTIC,   136, -6.114732623100e-01, 2.334295032824e-07, 1.8824e+01, 6.6180e-02, 
 2DIAGNOSTIC,   137, -6.114730238914e-01, 2.306610866754e-07, 1.8891e+01, 6.7449e-02, 
 2DIAGNOSTIC,   138, -6.114729642868e-01, 2.279239623704e-07, 1.8958e+01, 6.7287e-02, 
 2DIAGNOSTIC,   139, -6.114730238914e-01, 2.256685860402e-07, 1.9027e+01, 6.8193e-02, 
 2DIAGNOSTIC,   140, -6.114730238914e-01, 2.241182954776e-07, 1.9094e+01, 6.7684e-02, 
 2DIAGNOSTIC,   141, -6.114729642868e-01, 2.226844912911e-07, 1.9160e+01, 6.6243e-02, 
 2DIAGNOSTIC,   142, -6.114732027054e-01, 2.223710140470e-07, 1.9227e+01, 6.6602e-02, 
 2DIAGNOSTIC,   143, -6.114732623100e-01, 2.220252639518e-07, 1.9292e+01, 6.5070e-02, 
 2DIAGNOSTIC,   144, -6.114731431007e-01, 2.209310565604e-07, 1.9358e+01, 6.5976e-02, 
 2DIAGNOSTIC,   145, -6.114732027054e-01, 2.204364903946e-07, 1.9425e+01, 6.6766e-02, 
 2DIAGNOSTIC,   146, -6.114731431007e-01, 2.196730122250e-07, 1.9493e+01, 6.8112e-02, 
 2DIAGNOSTIC,   147, -6.114732027054e-01, 2.181771918686e-07, 1.9561e+01, 6.7587e-02, 
 2DIAGNOSTIC,   148, -6.114732027054e-01, 2.163243806308e-07, 1.9627e+01, 6.6523e-02, 
 2DIAGNOSTIC,   149, -6.114732623100e-01, 2.147477573544e-07, 1.9694e+01, 6.7223e-02, 
 2DIAGNOSTIC,   150, -6.114732027054e-01, 2.128998630724e-07, 1.9762e+01, 6.7782e-02, 
 2DIAGNOSTIC,   151, -6.114732623100e-01, 2.109805166128e-07, 1.9828e+01, 6.6409e-02, 
 2DIAGNOSTIC,   152, -6.114733815193e-01, 2.101363065776e-07, 1.9896e+01, 6.7890e-02, 
 2DIAGNOSTIC,   153, -6.114732027054e-01, 2.088552264468e-07, 1.9963e+01, 6.6921e-02, 
 2DIAGNOSTIC,   154, -6.114732027054e-01, 2.071555940120e-07, 2.0029e+01, 6.5690e-02, 
 2DIAGNOSTIC,   155, -6.114731431007e-01, 2.054288472664e-07, 2.0097e+01, 6.8001e-02, 
 2DIAGNOSTIC,   156, -6.114731431007e-01, 2.035180841631e-07, 2.0163e+01, 6.6198e-02, 
 2DIAGNOSTIC,   157, -6.114730834961e-01, 2.016629139234e-07, 2.0230e+01, 6.6522e-02, 
 2DIAGNOSTIC,   158, -6.114730834961e-01, 1.999294880761e-07, 2.0297e+01, 6.7038e-02, 
 2DIAGNOSTIC,   159, -6.114730238914e-01, 1.983678430406e-07, 2.0364e+01, 6.7412e-02, 
 2DIAGNOSTIC,   160, -6.114732027054e-01, 1.973331649197e-07, 2.0430e+01, 6.5633e-02, 
 2DIAGNOSTIC,   161, -6.114732027054e-01, 1.965961757833e-07, 2.0496e+01, 6.6613e-02, 
 2DIAGNOSTIC,   162, -6.114730834961e-01, 1.959825226550e-07, 2.0565e+01, 6.8573e-02, 
 2DIAGNOSTIC,   163, -6.114730834961e-01, 1.949208439100e-07, 2.0632e+01, 6.7029e-02, 
 2DIAGNOSTIC,   164, -6.114730834961e-01, 1.938942517654e-07, 2.0698e+01, 6.5668e-02, 
 2DIAGNOSTIC,   165, -6.114730834961e-01, 1.927041353156e-07, 2.0765e+01, 6.7303e-02, 
 2DIAGNOSTIC,   166, -6.114732027054e-01, 1.918722745131e-07, 2.0831e+01, 6.5892e-02, 
 2DIAGNOSTIC,   167, -6.114732027054e-01, 1.908633606718e-07, 2.0900e+01, 6.8863e-02, 
 2DIAGNOSTIC,   168, -6.114732027054e-01, 1.898455650462e-07, 2.0966e+01, 6.6659e-02, 
 2DIAGNOSTIC,   169, -6.114732027054e-01, 1.886136544726e-07, 2.1034e+01, 6.7143e-02, 
 2DIAGNOSTIC,   170, -6.114731431007e-01, 1.876797597333e-07, 2.1101e+01, 6.7381e-02, 
 2DIAGNOSTIC,   171, -6.114731431007e-01, 1.867111336651e-07, 2.1167e+01, 6.6370e-02, 
 2DIAGNOSTIC,   172, -6.114731431007e-01, 1.853620972270e-07, 2.1234e+01, 6.6784e-02, 
 2DIAGNOSTIC,   173, -6.114731431007e-01, 1.839909344881e-07, 2.1302e+01, 6.8290e-02, 
 2DIAGNOSTIC,   174, -6.114730834961e-01, 1.824697761776e-07, 2.1369e+01, 6.6533e-02, 
 2DIAGNOSTIC,   175, -6.114730834961e-01, 1.809982990153e-07, 2.1436e+01, 6.6962e-02, 
 2DIAGNOSTIC,   176, -6.114730834961e-01, 1.799327691288e-07, 2.1504e+01, 6.8431e-02, 
 2DIAGNOSTIC,   177, -6.114730834961e-01, 1.789530443830e-07, 2.1572e+01, 6.7446e-02, 
 2DIAGNOSTIC,   178, -6.114732027054e-01, 1.783691629953e-07, 2.1639e+01, 6.7491e-02, 
 2DIAGNOSTIC,   179, -6.114730834961e-01, 1.775138969151e-07, 2.1705e+01, 6.6077e-02, 
 2DIAGNOSTIC,   180, -6.114730834961e-01, 1.765468056192e-07, 2.1772e+01, 6.6439e-02, 
 2DIAGNOSTIC,   181, -6.114730834961e-01, 1.756067291581e-07, 2.1838e+01, 6.6054e-02, 
 2DIAGNOSTIC,   182, -6.114730834961e-01, 1.746830520233e-07, 2.1905e+01, 6.7019e-02, 
 2DIAGNOSTIC,   183, -6.114732027054e-01, 1.740825297247e-07, 2.1972e+01, 6.6710e-02, 
 2DIAGNOSTIC,   184, -6.114732027054e-01, 1.733087060529e-07, 2.2038e+01, 6.6909e-02, 
 2DIAGNOSTIC,   185, -6.114731431007e-01, 1.723619078575e-07, 2.2106e+01, 6.7283e-02, 
 2DIAGNOSTIC,   186, -6.114731431007e-01, 1.713931112590e-07, 2.2173e+01, 6.7658e-02, 
 2DIAGNOSTIC,   187, -6.114730238914e-01, 1.700877021449e-07, 2.2241e+01, 6.7403e-02, 
 2DIAGNOSTIC,   188, -6.114730834961e-01, 1.692500859463e-07, 2.2310e+01, 6.9085e-02, 
 2DIAGNOSTIC,   189, -6.114730834961e-01, 1.681156618361e-07, 2.2377e+01, 6.7279e-02, 
 2DIAGNOSTIC,   190, -6.114730834961e-01, 1.670164095913e-07, 2.2444e+01, 6.6511e-02, 
 2DIAGNOSTIC,   191, -6.114731431007e-01, 1.661210120574e-07, 2.2511e+01, 6.7162e-02, 
 2DIAGNOSTIC,   192, -6.114732027054e-01, 1.654104266890e-07, 2.2578e+01, 6.6868e-02, 
 2DIAGNOSTIC,   193, -6.114732027054e-01, 1.650152086086e-07, 2.2645e+01, 6.7186e-02, 
 2DIAGNOSTIC,   194, -6.114732623100e-01, 1.647510998737e-07, 2.2713e+01, 6.8049e-02, 
 2DIAGNOSTIC,   195, -6.114732623100e-01, 1.642685418801e-07, 2.2781e+01, 6.8336e-02, 
 2DIAGNOSTIC,   196, -6.114732027054e-01, 1.635475683770e-07, 2.2848e+01, 6.6434e-02, 
 2DIAGNOSTIC,   197, -6.114732623100e-01, 1.625712684472e-07, 2.2914e+01, 6.6581e-02, 
 2DIAGNOSTIC,   198, -6.114732027054e-01, 1.614937730210e-07, 2.2981e+01, 6.6250e-02, 
 2DIAGNOSTIC,   199, -6.114732027054e-01, 1.603510213499e-07, 2.3048e+01, 6.7013e-02, 
 2DIAGNOSTIC,   200, -6.114732027054e-01, 1.591695308889e-07, 2.3113e+01, 6.5042e-02, 
 2DIAGNOSTIC,   201, -6.114732027054e-01, 1.581242372595e-07, 2.3179e+01, 6.6630e-02, 
 2DIAGNOSTIC,   202, -6.114732027054e-01, 1.572402794636e-07, 2.3245e+01, 6.5866e-02, 
 2DIAGNOSTIC,   203, -6.114732027054e-01, 1.563839191476e-07, 2.3314e+01, 6.9224e-02, 
 2DIAGNOSTIC,   204, -6.114732027054e-01, 1.557039297495e-07, 2.3382e+01, 6.7347e-02, 
 2DIAGNOSTIC,   205, -6.114732623100e-01, 1.551915289610e-07, 2.3449e+01, 6.7097e-02, 
 2DIAGNOSTIC,   206, -6.114732027054e-01, 1.544041339230e-07, 2.3515e+01, 6.5941e-02, 
 2DIAGNOSTIC,   207, -6.114731431007e-01, 1.536352982612e-07, 2.3582e+01, 6.7323e-02, 
 2DIAGNOSTIC,   208, -6.114731431007e-01, 1.527489104092e-07, 2.3648e+01, 6.5890e-02, 
 2DIAGNOSTIC,   209, -6.114730834961e-01, 1.517524310657e-07, 2.3714e+01, 6.6116e-02, 
 2DIAGNOSTIC,   210, -6.114731431007e-01, 1.509412612677e-07, 2.3780e+01, 6.6047e-02, 
 2DIAGNOSTIC,   211, -6.114731431007e-01, 1.501870912080e-07, 2.3845e+01, 6.5246e-02, 
 2DIAGNOSTIC,   212, -6.114732027054e-01, 1.496309209870e-07, 2.3911e+01, 6.5831e-02, 
 2DIAGNOSTIC,   213, -6.114731431007e-01, 1.489895993245e-07, 2.3978e+01, 6.7206e-02, 
 2DIAGNOSTIC,   214, -6.114730834961e-01, 1.482590903379e-07, 2.4046e+01, 6.7729e-02, 
 2DIAGNOSTIC,   215, -6.114731431007e-01, 1.478356779216e-07, 2.4112e+01, 6.5905e-02, 
 2DIAGNOSTIC,   216, -6.114732027054e-01, 1.474212751873e-07, 2.4178e+01, 6.6229e-02, 
 2DIAGNOSTIC,   217, -6.114732027054e-01, 1.468631580792e-07, 2.4244e+01, 6.5663e-02, 
 2DIAGNOSTIC,   218, -6.114732027054e-01, 1.462947949449e-07, 2.4311e+01, 6.7167e-02, 
 2DIAGNOSTIC,   219, -6.114731431007e-01, 1.454448153027e-07, 2.4378e+01, 6.6531e-02, 
 2DIAGNOSTIC,   220, -6.114730834961e-01, 1.445849733273e-07, 2.4445e+01, 6.7014e-02, 
 2DIAGNOSTIC,   221, -6.114730834961e-01, 1.437261261117e-07, 2.4510e+01, 6.5400e-02, 
 2DIAGNOSTIC,   222, -6.114730834961e-01, 1.430207277053e-07, 2.4576e+01, 6.5843e-02, 
 2DIAGNOSTIC,   223, -6.114729642868e-01, 1.419808484115e-07, 2.4643e+01, 6.7306e-02, 
 2DIAGNOSTIC,   224, -6.114731431007e-01, 1.412702061998e-07, 2.4709e+01, 6.6234e-02, 
 2DIAGNOSTIC,   225, -6.114731431007e-01, 1.407467351555e-07, 2.4777e+01, 6.7218e-02, 
 2DIAGNOSTIC,   226, -6.114730238914e-01, 1.401659517342e-07, 2.4844e+01, 6.7685e-02, 
 2DIAGNOSTIC,   227, -6.114731431007e-01, 1.399021698489e-07, 2.4911e+01, 6.6503e-02, 
 2DIAGNOSTIC,   228, -6.114730834961e-01, 1.395367377199e-07, 2.4979e+01, 6.7756e-02, 
 2DIAGNOSTIC,   229, -6.114732027054e-01, 1.392945847556e-07, 2.5045e+01, 6.6877e-02, 
 2DIAGNOSTIC,   230, -6.114732027054e-01, 1.388879553588e-07, 2.5112e+01, 6.6938e-02, 
 2DIAGNOSTIC,   231, -6.114731431007e-01, 1.383154000223e-07, 2.5178e+01, 6.5856e-02, 
 2DIAGNOSTIC,   232, -6.114731431007e-01, 1.377044753781e-07, 2.5246e+01, 6.7536e-02, 
 2DIAGNOSTIC,   233, -6.114731431007e-01, 1.367882447312e-07, 2.5317e+01, 7.0985e-02, 
 2DIAGNOSTIC,   234, -6.114730834961e-01, 1.360866690447e-07, 2.5385e+01, 6.8616e-02, 
 2DIAGNOSTIC,   235, -6.114731431007e-01, 1.355055587737e-07, 2.5455e+01, 6.9317e-02, 
 2DIAGNOSTIC,   236, -6.114730238914e-01, 1.344389630731e-07, 2.5524e+01, 6.9134e-02, 
 2DIAGNOSTIC,   237, -6.114730834961e-01, 1.337791388778e-07, 2.5593e+01, 6.8872e-02, 
 2DIAGNOSTIC,   238, -6.114730834961e-01, 1.330392223053e-07, 2.5661e+01, 6.8833e-02, 
 2DIAGNOSTIC,   239, -6.114732027054e-01, 1.328271821421e-07, 2.5730e+01, 6.8252e-02, 
 2DIAGNOSTIC,   240, -6.114731431007e-01, 1.325258978113e-07, 2.5800e+01, 7.0048e-02, 
 2DIAGNOSTIC,   241, -6.114731431007e-01, 1.321211442473e-07, 2.5869e+01, 6.9187e-02, 
 2DIAGNOSTIC,   242, -6.114730834961e-01, 1.315946747127e-07, 2.5937e+01, 6.7749e-02, 
 2DIAGNOSTIC,   243, -6.114730834961e-01, 1.310593802373e-07, 2.6007e+01, 6.9857e-02, 
 2DIAGNOSTIC,   244, -6.114730834961e-01, 1.303912569028e-07, 2.6076e+01, 6.9186e-02, 
 2DIAGNOSTIC,   245, -6.114730834961e-01, 1.298467964261e-07, 2.6145e+01, 6.8975e-02, 
 2DIAGNOSTIC,   246, -6.114730834961e-01, 1.290820819122e-07, 2.6220e+01, 7.4916e-02, 
 2DIAGNOSTIC,   247, -6.114730238914e-01, 1.283486739112e-07, 2.6290e+01, 7.0274e-02, 
 2DIAGNOSTIC,   248, -6.114730238914e-01, 1.276598311506e-07, 2.6358e+01, 6.8415e-02, 
 2DIAGNOSTIC,   249, -6.114730834961e-01, 1.273696454973e-07, 2.6427e+01, 6.9036e-02, 
 2DIAGNOSTIC,   250, -6.114730238914e-01, 1.268912370733e-07, 2.6496e+01, 6.8975e-02, 
DIAGNOSTIC,Iteration,metricValue,convergenceValue,ITERATION_TIME_INDEX,SINCE_LAST
 2DIAGNOSTIC,     1, -5.265509486198e-01, inf, 2.7575e+01, 1.0782e+00, 
 2DIAGNOSTIC,     2, -5.269216895103e-01, inf, 2.7871e+01, 2.9651e-01, 
 2DIAGNOSTIC,     3, -5.272505879402e-01, inf, 2.8163e+01, 2.9200e-01, 
 2DIAGNOSTIC,     4, -5.274866223335e-01, inf, 2.8504e+01, 3.4096e-01, 
 2DIAGNOSTIC,     5, -5.279087424278e-01, inf, 2.8839e+01, 3.3522e-01, 
 2DIAGNOSTIC,     6, -5.281735062599e-01, inf, 2.9202e+01, 3.6301e-01, 
 2DIAGNOSTIC,     7, -5.282177329063e-01, inf, 2.9906e+01, 7.0364e-01, 
 2DIAGNOSTIC,     8, -5.282180309296e-01, inf, 3.0282e+01, 3.7649e-01, 
 2DIAGNOSTIC,     9, -5.282181501389e-01, inf, 3.0616e+01, 3.3339e-01, 
 2DIAGNOSTIC,    10, -5.282179117203e-01, 2.112762012985e-04, 3.0937e+01, 3.2167e-01, 
 2DIAGNOSTIC,    11, -5.282177329063e-01, 1.402857596986e-04, 3.1259e+01, 3.2164e-01, 
 2DIAGNOSTIC,    12, -5.282177329063e-01, 8.539004193153e-05, 3.1587e+01, 3.2834e-01, 
 2DIAGNOSTIC,    13, -5.282178521156e-01, 4.520559741650e-05, 3.1913e+01, 3.2540e-01, 
 2DIAGNOSTIC,    14, -5.282179117203e-01, 1.564678132127e-05, 3.2235e+01, 3.2220e-01, 
 2DIAGNOSTIC,    15, -5.282179713249e-01, 3.711041699717e-06, 3.2566e+01, 3.3118e-01, 
 2DIAGNOSTIC,    16, -5.282177925110e-01, 1.982984485949e-06, 3.2887e+01, 3.2102e-01, 
 2DIAGNOSTIC,    17, -5.282179117203e-01, 1.863141847025e-06, 3.3209e+01, 3.2225e-01, 
 2DIAGNOSTIC,    18, -5.282176733017e-01, 1.758764028637e-06, 3.3535e+01, 3.2507e-01, 
 2DIAGNOSTIC,    19, -5.282177329063e-01, 1.671551217441e-06, 3.3828e+01, 2.9391e-01, 
 2DIAGNOSTIC,    20, -5.282176136971e-01, 1.583867174304e-06, 3.4150e+01, 3.2187e-01, 
 2DIAGNOSTIC,    21, -5.282177329063e-01, 1.503825728832e-06, 3.4474e+01, 3.2361e-01, 
 2DIAGNOSTIC,    22, -5.282181501389e-01, 1.442208827029e-06, 3.4832e+01, 3.5799e-01, 
 2DIAGNOSTIC,    23, -5.282179713249e-01, 1.384657593917e-06, 3.5162e+01, 3.3001e-01, 
 2DIAGNOSTIC,    24, -5.282182693481e-01, 1.340062112831e-06, 3.5483e+01, 3.2137e-01, 
 2DIAGNOSTIC,    25, -5.282178521156e-01, 1.290012960453e-06, 3.5837e+01, 3.5328e-01, 
 2DIAGNOSTIC,    26, -5.282180905342e-01, 1.243523342964e-06, 3.6152e+01, 3.1530e-01, 
 2DIAGNOSTIC,    27, -5.282178521156e-01, 1.196091602651e-06, 3.6471e+01, 3.1909e-01, 
 2DIAGNOSTIC,    28, -5.282180905342e-01, 1.150433718067e-06, 3.6860e+01, 3.8929e-01, 
 2DIAGNOSTIC,    29, -5.282179713249e-01, 1.105556520997e-06, 3.7241e+01, 3.8058e-01, 
 2DIAGNOSTIC,    30, -5.282180309296e-01, 1.061927036972e-06, 3.7564e+01, 3.2359e-01, 
 2DIAGNOSTIC,    31, -5.282179713249e-01, 1.021854018290e-06, 3.7897e+01, 3.3241e-01, 
 2DIAGNOSTIC,    32, -5.282179117203e-01, 9.908138736137e-07, 3.8210e+01, 3.1353e-01, 
 2DIAGNOSTIC,    33, -5.282179117203e-01, 9.589051614967e-07, 3.8542e+01, 3.3181e-01, 
 2DIAGNOSTIC,    34, -5.282179117203e-01, 9.342564339931e-07, 3.8867e+01, 3.2483e-01, 
 2DIAGNOSTIC,    35, -5.282179117203e-01, 9.046422064785e-07, 3.9197e+01, 3.3005e-01, 
 2DIAGNOSTIC,    36, -5.282177925110e-01, 8.790112246970e-07, 3.9533e+01, 3.3645e-01, 
 2DIAGNOSTIC,    37, -5.282178521156e-01, 8.525859698238e-07, 3.9874e+01, 3.4096e-01, 
 2DIAGNOSTIC,    38, -5.282178521156e-01, 8.316332582581e-07, 4.0210e+01, 3.3595e-01, 
 2DIAGNOSTIC,    39, -5.282178521156e-01, 8.105877213893e-07, 4.0569e+01, 3.5906e-01, 
 2DIAGNOSTIC,    40, -5.282177925110e-01, 7.911278316897e-07, 4.0928e+01, 3.5891e-01, 
 2DIAGNOSTIC,    41, -5.282178521156e-01, 7.730968718533e-07, 4.1272e+01, 3.4359e-01, 
 2DIAGNOSTIC,    42, -5.282177925110e-01, 7.546393021585e-07, 4.1592e+01, 3.2015e-01, 
 2DIAGNOSTIC,    43, -5.282177329063e-01, 7.365635497081e-07, 4.1918e+01, 3.2638e-01, 
 2DIAGNOSTIC,    44, -5.282177329063e-01, 7.196522915365e-07, 4.2240e+01, 3.2125e-01, 
 2DIAGNOSTIC,    45, -5.282177329063e-01, 7.038619855848e-07, 4.2563e+01, 3.2277e-01, 
 2DIAGNOSTIC,    46, -5.282177329063e-01, 6.876296083647e-07, 4.2886e+01, 3.2354e-01, 
 2DIAGNOSTIC,    47, -5.282177329063e-01, 6.731570465490e-07, 4.3216e+01, 3.3017e-01, 
 2DIAGNOSTIC,    48, -5.282176733017e-01, 6.589986583094e-07, 4.3545e+01, 3.2858e-01, 
 2DIAGNOSTIC,    49, -5.282177329063e-01, 6.464778721238e-07, 4.3873e+01, 3.2817e-01, 
 2DIAGNOSTIC,    50, -5.282177329063e-01, 6.340251275105e-07, 4.4203e+01, 3.2980e-01, 
 2DIAGNOSTIC,    51, -5.282177329063e-01, 6.229174687178e-07, 4.4537e+01, 3.3383e-01, 
 2DIAGNOSTIC,    52, -5.282176733017e-01, 6.111220614002e-07, 4.4858e+01, 3.2122e-01, 
 2DIAGNOSTIC,    53, -5.282176733017e-01, 5.992607725602e-07, 4.5170e+01, 3.1182e-01, 
 2DIAGNOSTIC,    54, -5.282176733017e-01, 5.879232389816e-07, 4.5531e+01, 3.6099e-01, 
 2DIAGNOSTIC,    55, -5.282177925110e-01, 5.782634957541e-07, 4.5899e+01, 3.6847e-01, 
 2DIAGNOSTIC,    56, -5.282177329063e-01, 5.683669428436e-07, 4.6230e+01, 3.3125e-01, 
 2DIAGNOSTIC,    57, -5.282176136971e-01, 5.577315960181e-07, 4.6557e+01, 3.2695e-01, 
 2DIAGNOSTIC,    58, -5.282176136971e-01, 5.469805728353e-07, 4.6898e+01, 3.4052e-01, 
 2DIAGNOSTIC,    59, -5.282176733017e-01, 5.377960405895e-07, 4.7236e+01, 3.3846e-01, 
 2DIAGNOSTIC,    60, -5.282179117203e-01, 5.311395057106e-07, 4.7584e+01, 3.4726e-01, 
 2DIAGNOSTIC,    61, -5.282179713249e-01, 5.251115453575e-07, 4.7916e+01, 3.3214e-01, 
 2DIAGNOSTIC,    62, -5.282179713249e-01, 5.184732572161e-07, 4.8259e+01, 3.4304e-01, 
 2DIAGNOSTIC,    63, -5.282179713249e-01, 5.115778094478e-07, 4.8597e+01, 3.3845e-01, 
 2DIAGNOSTIC,    64, -5.282179117203e-01, 5.037039159106e-07, 4.8933e+01, 3.3567e-01, 
 2DIAGNOSTIC,    65, -5.282179713249e-01, 4.968964617547e-07, 4.9272e+01, 3.3918e-01, 
 2DIAGNOSTIC,    66, -5.282179713249e-01, 4.890929972134e-07, 4.9598e+01, 3.2586e-01, 
 2DIAGNOSTIC,    67, -5.282179117203e-01, 4.794397341357e-07, 4.9954e+01, 3.5604e-01, 
 2DIAGNOSTIC,    68, -5.282179117203e-01, 4.696671851434e-07, 5.0284e+01, 3.2994e-01, 
 2DIAGNOSTIC,    69, -5.282179117203e-01, 4.604212335835e-07, 5.0607e+01, 3.2345e-01, 
 2DIAGNOSTIC,    70, -5.282179117203e-01, 4.533088997505e-07, 5.0945e+01, 3.3776e-01, 
 2DIAGNOSTIC,    71, -5.282179117203e-01, 4.469551981856e-07, 5.1263e+01, 3.1838e-01, 
 2DIAGNOSTIC,    72, -5.282179713249e-01, 4.413420242599e-07, 5.1583e+01, 3.1990e-01, 
 2DIAGNOSTIC,    73, -5.282180309296e-01, 4.363792527329e-07, 5.1907e+01, 3.2391e-01, 
 2DIAGNOSTIC,    74, -5.282180309296e-01, 4.310355166126e-07, 5.2232e+01, 3.2495e-01, 
 2DIAGNOSTIC,    75, -5.282180309296e-01, 4.261611650236e-07, 5.2554e+01, 3.2187e-01, 
 2DIAGNOSTIC,    76, -5.282179713249e-01, 4.208198447486e-07, 5.2871e+01, 3.1679e-01, 
 2DIAGNOSTIC,    77, -5.282180309296e-01, 4.154066459705e-07, 5.3197e+01, 3.2572e-01, 
 2DIAGNOSTIC,    78, -5.282179713249e-01, 4.094795826859e-07, 5.3525e+01, 3.2872e-01, 
 2DIAGNOSTIC,    79, -5.282179713249e-01, 4.035620975174e-07, 5.3872e+01, 3.4669e-01, 
 2DIAGNOSTIC,    80, -5.282179713249e-01, 3.977243920872e-07, 5.4196e+01, 3.2383e-01, 
 2DIAGNOSTIC,    81, -5.282179713249e-01, 3.920179096895e-07, 5.4527e+01, 3.3086e-01, 
 2DIAGNOSTIC,    82, -5.282179713249e-01, 3.868987050737e-07, 5.4864e+01, 3.3709e-01, 
 2DIAGNOSTIC,    83, -5.282180309296e-01, 3.827780972188e-07, 5.5198e+01, 3.3426e-01, 
 2DIAGNOSTIC,    84, -5.282180309296e-01, 3.787978073433e-07, 5.5544e+01, 3.4615e-01, 
 2DIAGNOSTIC,    85, -5.282179713249e-01, 3.745413152956e-07, 5.5873e+01, 3.2900e-01, 
 2DIAGNOSTIC,    86, -5.282180309296e-01, 3.703597144522e-07, 5.6188e+01, 3.1501e-01, 
 2DIAGNOSTIC,    87, -5.282180309296e-01, 3.665949748211e-07, 5.6512e+01, 3.2415e-01, 
 2DIAGNOSTIC,    88, -5.282180309296e-01, 3.624543296610e-07, 5.6842e+01, 3.2996e-01, 
 2DIAGNOSTIC,    89, -5.282180309296e-01, 3.583217846881e-07, 5.7166e+01, 3.2402e-01, 
 2DIAGNOSTIC,    90, -5.282182097435e-01, 3.552766543180e-07, 5.7503e+01, 3.3697e-01, 
 2DIAGNOSTIC,    91, -5.282182097435e-01, 3.520941334045e-07, 5.7839e+01, 3.3572e-01, 
 2DIAGNOSTIC,    92, -5.282182097435e-01, 3.487347157716e-07, 5.8169e+01, 3.3011e-01, 
 2DIAGNOSTIC,    93, -5.282183289528e-01, 3.462161259904e-07, 5.8496e+01, 3.2652e-01, 
 2DIAGNOSTIC,    94, -5.282182693481e-01, 3.429999537730e-07, 5.8813e+01, 3.1698e-01, 
 2DIAGNOSTIC,    95, -5.282182693481e-01, 3.390633196432e-07, 5.9143e+01, 3.2984e-01, 
 2DIAGNOSTIC,    96, -5.282183289528e-01, 3.354745956585e-07, 5.9476e+01, 3.3357e-01, 
 2DIAGNOSTIC,    97, -5.282182693481e-01, 3.312323144655e-07, 5.9799e+01, 3.2245e-01, 
 2DIAGNOSTIC,    98, -5.282182693481e-01, 3.267760746439e-07, 6.0124e+01, 3.2591e-01, 
 2DIAGNOSTIC,    99, -5.282181501389e-01, 3.215299670956e-07, 6.0448e+01, 3.2318e-01, 
 2DIAGNOSTIC,   100, -5.282181501389e-01, 3.173565232828e-07, 6.0774e+01, 3.2660e-01, 
  Elapsed time (stage 1): 6.1862e+01


Stage 2
  iterations = 50x10x0
  convergence threshold = 1.0000e-09
  convergence window size = 15
  number of levels = 3
  using the CC metric (radius = 4, weight = 5.0000e-01, use gradient filter = 0)
  preprocessing:  winsorizing the image intensities
  preprocessing:  histogram matching the images
  using the CC metric (radius = 4, weight = 5.0000e-01, use gradient filter = 0)
  preprocessing:  winsorizing the image intensities
  preprocessing:  histogram matching the images
  Shrink factors (level 1 out of 3): [4, 4, 4]
  Shrink factors (level 2 out of 3): [2, 2, 2]
  Shrink factors (level 3 out of 3): [1, 1, 1]
  smoothing sigmas per level: [2, 1, 0]
  Using default NONE metricSamplingStrategy 

*** Running SyN registration (varianceForUpdateField = 3.0000e+00, varianceForTotalField = 0.0000e+00) ***

XXDIAGNOSTIC,Iteration,metricValue,convergenceValue,ITERATION_TIME_INDEX,SINCE_LAST
 1DIAGNOSTIC,     1, -6.141305565834e-01, inf, 1.3696e+00, 1.3696e+00, 
 1DIAGNOSTIC,     2, -6.321509480476e-01, inf, 2.4279e+00, 1.0583e+00, 
 1DIAGNOSTIC,     3, -6.466566324234e-01, inf, 3.4314e+00, 1.0035e+00, 
 1DIAGNOSTIC,     4, -6.588303446770e-01, inf, 4.4505e+00, 1.0192e+00, 
 1DIAGNOSTIC,     5, -6.685781478882e-01, inf, 5.4600e+00, 1.0095e+00, 
 1DIAGNOSTIC,     6, -6.757310628891e-01, inf, 6.4945e+00, 1.0345e+00, 
 1DIAGNOSTIC,     7, -6.815249323845e-01, inf, 7.4796e+00, 9.8503e-01, 
 1DIAGNOSTIC,     8, -6.861770153046e-01, inf, 8.5447e+00, 1.0652e+00, 
 1DIAGNOSTIC,     9, -6.904159784317e-01, inf, 9.5325e+00, 9.8772e-01, 
 1DIAGNOSTIC,    10, -6.942306160927e-01, inf, 1.0563e+01, 1.0308e+00, 
 1DIAGNOSTIC,    11, -6.978787779808e-01, inf, 1.1603e+01, 1.0400e+00, 
 1DIAGNOSTIC,    12, -7.012195587158e-01, inf, 1.2710e+01, 1.1070e+00, 
 1DIAGNOSTIC,    13, -7.043107748032e-01, inf, 1.3697e+01, 9.8717e-01, 
 1DIAGNOSTIC,    14, -7.072479724884e-01, inf, 1.4698e+01, 1.0002e+00, 
 1DIAGNOSTIC,    15, -7.099974155426e-01, 5.122616887093e-03, 1.5724e+01, 1.0263e+00, 
 1DIAGNOSTIC,    16, -7.125317454338e-01, 4.041554871947e-03, 1.6690e+01, 9.6614e-01, 
 1DIAGNOSTIC,    17, -7.149270772934e-01, 3.258696058765e-03, 1.7675e+01, 9.8464e-01, 
 1DIAGNOSTIC,    18, -7.170329093933e-01, 2.685940824449e-03, 1.8726e+01, 1.0515e+00, 
 1DIAGNOSTIC,    19, -7.189543247223e-01, 2.268767217174e-03, 1.9712e+01, 9.8584e-01, 
 1DIAGNOSTIC,    20, -7.206891775131e-01, 1.958725275472e-03, 2.0755e+01, 1.0428e+00, 
 1DIAGNOSTIC,    21, -7.223213911057e-01, 1.712594763376e-03, 2.1726e+01, 9.7167e-01, 
 1DIAGNOSTIC,    22, -7.236659526825e-01, 1.507102511823e-03, 2.2761e+01, 1.0350e+00, 
 1DIAGNOSTIC,    23, -7.249338030815e-01, 1.327395904809e-03, 2.3709e+01, 9.4772e-01, 
 1DIAGNOSTIC,    24, -7.261230945587e-01, 1.169252675027e-03, 2.4651e+01, 9.4199e-01, 
 1DIAGNOSTIC,    25, -7.272652387619e-01, 1.029029139318e-03, 2.5628e+01, 9.7717e-01, 
 1DIAGNOSTIC,    26, -7.281993627548e-01, 9.045369224623e-04, 2.6669e+01, 1.0402e+00, 
 1DIAGNOSTIC,    27, -7.293096780777e-01, 7.962314411998e-04, 2.7603e+01, 9.3408e-01, 
 1DIAGNOSTIC,    28, -7.301568984985e-01, 7.003376958892e-04, 2.8548e+01, 9.4575e-01, 
 1DIAGNOSTIC,    29, -7.314618825912e-01, 6.212920998223e-04, 2.9617e+01, 1.0688e+00, 
 1DIAGNOSTIC,    30, -7.324746847153e-01, 5.551416543312e-04, 3.0606e+01, 9.8908e-01, 
 1DIAGNOSTIC,    31, -7.337266206741e-01, 5.027614533901e-04, 3.1537e+01, 9.3058e-01, 
 1DIAGNOSTIC,    32, -7.346742153168e-01, 4.604700661730e-04, 3.2569e+01, 1.0326e+00, 
 1DIAGNOSTIC,    33, -7.358525991440e-01, 4.280392604414e-04, 3.3618e+01, 1.0485e+00, 
 1DIAGNOSTIC,    34, -7.368143200874e-01, 4.021011118311e-04, 3.4607e+01, 9.8899e-01, 
 1DIAGNOSTIC,    35, -7.379011511803e-01, 3.822029684670e-04, 3.5603e+01, 9.9564e-01, 
 1DIAGNOSTIC,    36, -7.387085556984e-01, 3.652906161733e-04, 3.6620e+01, 1.0175e+00, 
 1DIAGNOSTIC,    37, -7.397103309631e-01, 3.507274377625e-04, 3.7606e+01, 9.8613e-01, 
 1DIAGNOSTIC,    38, -7.405138015747e-01, 3.365172306076e-04, 3.8557e+01, 9.5052e-01, 
 1DIAGNOSTIC,    39, -7.412659525871e-01, 3.219800710212e-04, 3.9600e+01, 1.0435e+00, 
 1DIAGNOSTIC,    40, -7.421813011169e-01, 3.082311886828e-04, 4.0567e+01, 9.6648e-01, 
 1DIAGNOSTIC,    41, -7.427945137024e-01, 2.920079277828e-04, 4.1554e+01, 9.8697e-01, 
 1DIAGNOSTIC,    42, -7.434182763100e-01, 2.751344582066e-04, 4.2532e+01, 9.7861e-01, 
 1DIAGNOSTIC,    43, -7.442571520805e-01, 2.576978295110e-04, 4.3601e+01, 1.0688e+00, 
 1DIAGNOSTIC,    44, -7.447000145912e-01, 2.405794657534e-04, 4.4589e+01, 9.8812e-01, 
 1DIAGNOSTIC,    45, -7.453014254570e-01, 2.234483981738e-04, 4.5571e+01, 9.8155e-01, 
 1DIAGNOSTIC,    46, -7.458846569061e-01, 2.081275597448e-04, 4.6565e+01, 9.9415e-01, 
 1DIAGNOSTIC,    47, -7.463920712471e-01, 1.927064295160e-04, 4.7607e+01, 1.0423e+00, 
 1DIAGNOSTIC,    48, -7.466819286346e-01, 1.777689321898e-04, 4.8624e+01, 1.0168e+00, 
 1DIAGNOSTIC,    49, -7.471531629562e-01, 1.635789521970e-04, 4.9635e+01, 1.0114e+00, 
 1DIAGNOSTIC,    50, -7.474454641342e-01, 1.502588565927e-04, 5.0663e+01, 1.0279e+00, 
XXDIAGNOSTIC,Iteration,metricValue,convergenceValue,ITERATION_TIME_INDEX,SINCE_LAST
 1DIAGNOSTIC,     1, -5.022440552711e-01, inf, 5.8414e+01, 7.7511e+00, 
 1DIAGNOSTIC,     2, -5.074332952499e-01, inf, 6.6587e+01, 8.1728e+00, 
 1DIAGNOSTIC,     3, -5.129386186600e-01, inf, 7.4684e+01, 8.0965e+00, 
 1DIAGNOSTIC,     4, -5.176209211349e-01, inf, 8.2926e+01, 8.2422e+00, 
 1DIAGNOSTIC,     5, -5.213408470154e-01, inf, 9.1420e+01, 8.4944e+00, 
 1DIAGNOSTIC,     6, -5.245252847672e-01, inf, 9.9831e+01, 8.4103e+00, 
 1DIAGNOSTIC,     7, -5.272283554077e-01, inf, 1.0806e+02, 8.2272e+00, 
 1DIAGNOSTIC,     8, -5.296059846878e-01, inf, 1.1584e+02, 7.7793e+00, 
 1DIAGNOSTIC,     9, -5.317406654358e-01, inf, 1.2380e+02, 7.9645e+00, 
 1DIAGNOSTIC,    10, -5.336973667145e-01, inf, 1.3212e+02, 8.3162e+00, 
  Elapsed time (stage 2): 134.9


Total elapsed time: 258.6


Terminal - standard error
~~~~~~~~~~~~~~~~~~~~~~~~~


  file NULL does not exist . 
 file NULL does not exist . 
 file NULL does not exist . 


Environment
~~~~~~~~~~~


* AFNI_IMSAVE_WARNINGS : NO
* AFNI_PLUGINPATH : /opt/afni-latest
* ANTS_RANDOM_SEED : 3954
* APPTAINER_BINDPATH : /gs10,/gs11,/gs12,/gs8,/gs9,/vf,/spin1,/data,/fdb,/gpfs,/lscratch
* BASH_ENV : /usr/local/lmod/lmod/8.7/init/bash
* BASH_FUNC_i2proxyoff%% : () {  echo "[-] Disabling I2 web proxy ...";
 unset https_proxy
}
* BASH_FUNC_i2proxyon%% : () {  echo "[+] Enabling I2 web proxy ...";
 export https_proxy=http://dtn${I2HOSTNUM}-e0:${SQUID_PORT}
}
* BASH_FUNC_ml%% : () {  eval "$($LMOD_DIR/ml_cmd "$@")"
}
* BASH_FUNC_module%% : () {  local __lmod_my_status;
 local __lmod_sh_dbg;
 if [ -z "${LMOD_SH_DBG_ON+x}" ]; then
 case "$-" in 
 *v*x*)
 __lmod_sh_dbg='vx'
 ;;
 *v*)
 __lmod_sh_dbg='v'
 ;;
 *x*)
 __lmod_sh_dbg='x'
 ;;
 esac;
 fi;
 if [ -n "${__lmod_sh_dbg:-}" ]; then
 set +$__lmod_sh_dbg;
 echo "Shell debugging temporarily silenced: export LMOD_SH_DBG_ON=1 for Lmod's output" 1>&2;
 fi;
 eval "$($LMOD_CMD bash "$@")" && eval $(${LMOD_SETTARG_CMD:-:} -s sh);
 __lmod_my_status=$?;
 if [ -n "${__lmod_sh_dbg:-}" ]; then
 echo "Shell debugging restarted" 1>&2;
 set -$__lmod_sh_dbg;
 fi;
 return $__lmod_my_status
}
* BASH_FUNC_proxyoff%% : () {  echo "[-] Disabling web proxy ...";
 unset http_proxy;
 unset https_proxy;
 unset ftp_proxy;
 unset RSYNC_PROXY
}
* BASH_FUNC_proxyon%% : () {  echo "[+] Enabling web proxy ...";
 export http_proxy=http://dtn${HOSTNUM}-e0:${SQUID_PORT};
 export https_proxy=http://dtn${HOSTNUM}-e0:${SQUID_PORT};
 export ftp_proxy=http://dtn${HOSTNUM}-e0:${SQUID_PORT};
 export RSYNC_PROXY=dtn${HOSTNUM}-e0:${SQUID_PORT}
}
* BASH_FUNC_which%% : () {  ( alias;
 eval ${which_declare} ) | /usr/bin/which --tty-only --read-alias --read-functions --show-tilde --show-dot $@
}
* COBBLER_SERVER : 10.1.201.7
* COLORTERM : truecolor
* CPATH : /opt/conda/envs/fmriprep/include:
* DBUS_SESSION_BUS_ADDRESS : unix:abstract=/tmp/dbus-WZtSKKMrMB,guid=7b7a335263cd424c185763c66509beb4
* DEBIAN_FRONTEND : noninteractive
* DEBUGINFOD_URLS : https://debuginfod.centos.org/ 
* DESKTOP_SESSION : xfce
* DISPLAY : :11.0
* ENVIRONMENT : BATCH
* FIX_VERTEX_AREA : 
* FREESURFER_HOME : /opt/freesurfer
* FSF_OUTPUT_FORMAT : nii.gz
* FSLDIR : /opt/conda/envs/fmriprep
* FSLGECUDAQ : cuda.q
* FSLLOCKDIR : 
* FSLMACHINELIST : 
* FSLMULTIFILEQUIT : TRUE
* FSLOUTPUTTYPE : NIFTI_GZ
* FSLREMOTECALL : 
* FS_LICENSE : /data/EDB/TMSpilot/code/license.txt
* FS_OVERRIDE : 0
* FUNCTIONALS_DIR : /opt/freesurfer/sessions
* GLOBAL_ENV : set
* HISTFILE : /home/zugmana2/.bash_history_biowulf
* HISTFILESIZE : 1000
* HISTSIZE : 1000
* HISTTIMEFORMAT : %H:%M  
* HOME : /home/zugmana2
* HOSTNAME : cn4271
* HOSTNUM : 04
* I2HOSTNUM : 13
* IS_DOCKER_8395080871 : 1
* KMP_DUPLICATE_LIB_OK : True
* KMP_INIT_AT_FORK : FALSE
* LANG : C.UTF-8
* LC_ALL : C.UTF-8
* LD_LIBRARY_PATH : /opt/conda/envs/fmriprep/lib:/usr/lib/x86_64-linux-gnu:/opt/workbench/lib_linux64::/.singularity.d/libs
* LESSOPEN : ||/usr/bin/lesspipe.sh %s
* LMOD_CMD : /usr/local/lmod/lmod/8.7/libexec/lmod
* LMOD_DIR : /usr/local/lmod/lmod/8.7/libexec
* LMOD_FAMILY_SINGULARITY : singularity
* LMOD_FAMILY_SINGULARITY_VERSION : 3.10.5
* LMOD_PKG : /usr/local/lmod/lmod/8.7
* LMOD_ROOT : /usr/local/lmod/lmod
* LMOD_SETTARG_FULL_SUPPORT : no
* LMOD_VERSION : 8.7
* LMOD_sys : Linux
* LM_LICENSE_FILE : /usr/local/pgi/license.dat
* LOADEDMODULES : turbovnc:singularity/3.10.5
* LOCAL_DIR : /opt/freesurfer/local
* LOGNAME : zugmana2
* LS_COLORS : rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:cd=40;33;01:or=40;31;01:mi=00:su=37;41:sg=30;43:ca=30;41:tw=30;42:ow=34;42:st=37;44:ex=01;32:*.tar=01;31:*.tgz=01;31:*.arc=01;31:*.arj=01;31:*.taz=01;31:*.lha=01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.tlz=01;31:*.txz=01;31:*.tzo=01;31:*.t7z=01;31:*.zip=01;31:*.z=01;31:*.dz=01;31:*.gz=01;31:*.lrz=01;31:*.lz=01;31:*.lzo=01;31:*.xz=01;31:*.zst=01;31:*.tzst=01;31:*.bz2=01;31:*.bz=01;31:*.tbz=01;31:*.tbz2=01;31:*.tz=01;31:*.deb=01;31:*.rpm=01;31:*.jar=01;31:*.war=01;31:*.ear=01;31:*.sar=01;31:*.rar=01;31:*.alz=01;31:*.ace=01;31:*.zoo=01;31:*.cpio=01;31:*.7z=01;31:*.rz=01;31:*.cab=01;31:*.wim=01;31:*.swm=01;31:*.dwm=01;31:*.esd=01;31:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.tif=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fli=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=00;36:*.au=00;36:*.flac=00;36:*.m4a=00;36:*.mid=00;36:*.midi=00;36:*.mka=00;36:*.mp3=00;36:*.mpc=00;36:*.ogg=00;36:*.ra=00;36:*.wav=00;36:*.oga=00;36:*.opus=00;36:*.spx=00;36:*.xspf=00;36:
* MAIL : /var/spool/mail/zugmana2
* MAMBA_ROOT_PREFIX : /opt/conda
* MANPATH : /usr/local/current/singularity/3.10.5/share/man:/usr/local/slurm/share/man:/usr/local/lmod/lmod/8.7/share/man:/usr/local/current/turbovnc/share/man::
* MINC_BIN_DIR : /opt/freesurfer/mni/bin
* MINC_LIB_DIR : /opt/freesurfer/mni/lib
* MKL_NUM_THREADS : 1
* MNI_DATAPATH : /opt/freesurfer/mni/data
* MNI_DIR : /opt/freesurfer/mni
* MNI_PERL5LIB : /opt/freesurfer/mni/lib/perl5/5.8.5
* MODULEPATH : /usr/local/lmod/modulefiles
* MODULEPATH_ROOT : /usr/local/lmod/modulefiles
* MODULESHOME : /usr/local/lmod/lmod/8.7
* NIPYPE_NO_ET : 1
* NO_ET : 1
* NSLOTS : 16
* OLDPWD : /data/EDB/TMSpilot
* OMP_NUM_THREADS : 1
* OS : Linux
* PANEL_GDK_CORE_DEVICE_EVENTS : 0
* PATH : /opt/conda/envs/fmriprep/bin:/opt/workbench/bin_linux64:/opt/afni-latest:/opt/freesurfer/bin:/opt/freesurfer/tktools:/opt/freesurfer/mni/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
* PERL5LIB : /opt/freesurfer/mni/lib/perl5/5.8.5
* PRINTER : unknown_printer
* PROMPT_COMMAND : PS1="Singularity> "; unset PROMPT_COMMAND
* PS1 : Singularity> 
* PVFSTAB_FILE : /usr/local/etc/pvfstab
* PWD : /vf/users/EDB/TMSpilot/code
* PYTHONNOUSERSITE : 1
* ROOTDIR : /data/EDB/TMSpilot
* RSYNC_PROXY : dtn04-e0:3128
* SELINUX_LEVEL_REQUESTED : 
* SELINUX_ROLE_REQUESTED : 
* SELINUX_USE_CURRENT_RANGE : 
* SESSION_MANAGER : local/unix:@/tmp/.ICE-unix/1941614,unix/unix:/tmp/.ICE-unix/1941614
* SHELL : /bin/bash
* SHLVL : 10
* SINGULARITY_BIND : /gs10,/gs11,/gs12,/gs8,/gs9,/vf,/spin1,/data,/fdb,/gpfs,/lscratch
* SINGULARITY_COMMAND : run
* SINGULARITY_CONTAINER : /data/EDB/TMSpilot/code/fmriprep_msmsulc.simg
* SINGULARITY_ENVIRONMENT : /.singularity.d/env/91-environment.sh
* SINGULARITY_NAME : fmriprep_msmsulc.simg
* SLURMD_NODENAME : cn4271
* SLURM_ARRAY_JOB_ID : 8535870
* SLURM_ARRAY_TASK_COUNT : 9
* SLURM_ARRAY_TASK_ID : 1
* SLURM_ARRAY_TASK_MAX : 8
* SLURM_ARRAY_TASK_MIN : 0
* SLURM_ARRAY_TASK_STEP : 1
* SLURM_CLUSTER_NAME : biowulf
* SLURM_CONF : /usr/local/slurm-21.08/slurm-21.08.8-2-patched2/etc/slurm.conf
* SLURM_CPUS_ON_NODE : 16
* SLURM_CPUS_PER_TASK : 16
* SLURM_GTIDS : 0
* SLURM_JOBID : 8536404
* SLURM_JOB_ACCOUNT : pined
* SLURM_JOB_CPUS_PER_NODE : 16
* SLURM_JOB_CPUS_PER_NODE_PACK_GROUP_0 : 32
* SLURM_JOB_GID : 39592
* SLURM_JOB_ID : 8536404
* SLURM_JOB_NAME : fmriprep23-1-3
* SLURM_JOB_NODELIST : cn4271
* SLURM_JOB_NUM_NODES : 1
* SLURM_JOB_PARTITION : norm
* SLURM_JOB_QOS : global
* SLURM_JOB_UID : 39592
* SLURM_JOB_USER : zugmana2
* SLURM_LOCALID : 0
* SLURM_MEM_PER_NODE : 40960
* SLURM_NNODES : 1
* SLURM_NODEID : 0
* SLURM_NODELIST : cn4271
* SLURM_NODE_ALIASES : (null)
* SLURM_PRIO_PROCESS : 0
* SLURM_PROCID : 0
* SLURM_SUBMIT_DIR : /vf/users/EDB/TMSpilot/code
* SLURM_SUBMIT_HOST : cn2882
* SLURM_TASKS_PER_NODE : 1
* SLURM_TASK_PID : 3230551
* SLURM_TOPOLOGY_ADDR : cn4271
* SLURM_TOPOLOGY_ADDR_PATTERN : node
* SLURM_WORKING_CLUSTER : biowulf:slurmctl:6802:9472:109
* SQUID_PORT : 3128
* SRUN_DEBUG : 3
* SSH_AGENT_PID : 1941656
* SSH_AUTH_SOCK : /tmp/ssh-VO2hYPWEBcYx/agent.1941655
* SSH_CLIENT : 165.112.206.151 51655 22
* SSH_CONNECTION : 165.112.206.151 51655 128.231.2.9 22
* SSH_TTY : /dev/pts/625
* STY : 542651.tun1
* SUBJECTS_DIR : /opt/freesurfer/subjects
* SWARM_PROC_ID : 0
* S_COLORS : auto
* TERM : xterm-256color
* TERMCAP : SC|screen.xterm-256color|VT 100/ANSI X3.64 virtual terminal:\
	:DO=\E[%dB:LE=\E[%dD:RI=\E[%dC:UP=\E[%dA:bs:bt=\E[Z:\
	:cd=\E[J:ce=\E[K:cl=\E[H\E[J:cm=\E[%i%d;%dH:ct=\E[3g:\
	:do=^J:nd=\E[C:pt:rc=\E8:rs=\Ec:sc=\E7:st=\EH:up=\EM:\
	:le=^H:bl=^G:cr=^M:it#8:ho=\E[H:nw=\EE:ta=^I:is=\E)0:\
	:li#24:co#80:am:xn:xv:LP:sr=\EM:al=\E[L:AL=\E[%dL:\
	:cs=\E[%i%d;%dr:dl=\E[M:DL=\E[%dM:dc=\E[P:DC=\E[%dP:\
	:im=\E[4h:ei=\E[4l:mi:IC=\E[%d@:ks=\E[?1h\E=:\
	:ke=\E[?1l\E>:vi=\E[?25l:ve=\E[34h\E[?25h:vs=\E[34l:\
	:ti=\E[?1049h:te=\E[?1049l:us=\E[4m:ue=\E[24m:so=\E[3m:\
	:se=\E[23m:mb=\E[5m:md=\E[1m:mh=\E[2m:mr=\E[7m:\
	:me=\E[m:ms:\
	:Co#8:pa#64:AF=\E[3%dm:AB=\E[4%dm:op=\E[39;49m:AX:\
	:vb=\Eg:G0:as=\E(0:ae=\E(B:\
	:ac=\140\140aaffggjjkkllmmnnooppqqrrssttuuvvwwxxyyzz{{||}}~~..--++,,hhII00:\
	:po=\E[5i:pf=\E[4i:Km=\E[M:k0=\E[10~:k1=\EOP:k2=\EOQ:\
	:k3=\EOR:k4=\EOS:k5=\E[15~:k6=\E[17~:k7=\E[18~:\
	:k8=\E[19~:k9=\E[20~:k;=\E[21~:F1=\E[23~:F2=\E[24~:\
	:F3=\E[1;2P:F4=\E[1;2Q:F5=\E[1;2R:F6=\E[1;2S:\
	:F7=\E[15;2~:F8=\E[17;2~:F9=\E[18;2~:FA=\E[19;2~:\
	:FB=\E[20;2~:FC=\E[21;2~:FD=\E[23;2~:FE=\E[24;2~:kb=:\
	:K2=\EOE:kB=\E[Z:kF=\E[1;2B:kR=\E[1;2A:*4=\E[3;2~:\
	:*7=\E[1;2F:#2=\E[1;2H:#3=\E[2;2~:#4=\E[1;2D:%c=\E[6;2~:\
	:%e=\E[5;2~:%i=\E[1;2C:kh=\E[1~:@1=\E[1~:kH=\E[4~:\
	:@7=\E[4~:kN=\E[6~:kP=\E[5~:kI=\E[2~:kD=\E[3~:ku=\EOA:\
	:kd=\EOB:kr=\EOC:kl=\EOD:km:
* TMPDIR : /lscratch/8536404
* USER : zugmana2
* USER_PATH : /usr/local/current/singularity/3.10.5/bin:/usr/local/slurm/bin:/usr/local/current/turbovnc/bin:/usr/local/bin:/usr/X11R6/bin:/usr/local/jdk/bin:/usr/bin:/usr/local/sbin:/usr/sbin:/usr/local/mysql/bin:/home/zugmana2/.local/bin:/home/zugmana2/bin:/bin:/usr/bin:/sbin:/usr/sbin:/usr/local/bin:/usr/local/sbin
* VGL_COMPRESS : 0
* VGL_PROBEGLX : 0
* VNCDESKTOP : TurboVNC: cn2882:11 (zugmana2)
* VTE_VERSION : 5204
* WINDOW : 0
* WINDOWID : 27262979
* XDG_CONFIG_DIRS : /etc/xdg
* XDG_CURRENT_DESKTOP : XFCE
* XDG_DATA_DIRS : /usr/local/share:/usr/share
* XDG_MENU_PREFIX : xfce-
* XDG_RUNTIME_DIR : /data/zugmana2/.xdgdir
* XDG_SESSION_ID : 4008
* _ : /usr/local/current/singularity/3.10.5/bin/singularity
* _LMFILES_ : /usr/local/lmod/modulefiles/turbovnc.lua:/usr/local/lmod/modulefiles/singularity/3.10.5.lua
* _ModuleTable001_ : X01vZHVsZVRhYmxlXyA9IHsKTVR2ZXJzaW9uID0gMywKY19yZWJ1aWxkVGltZSA9IDg2NDAwLApjX3Nob3J0VGltZSA9IGZhbHNlLApkZXB0aFQgPSB7fSwKZmFtaWx5ID0gewpzaW5ndWxhcml0eSA9ICJzaW5ndWxhcml0eSIsCn0sCm1UID0gewpzaW5ndWxhcml0eSA9IHsKZm4gPSAiL3Vzci9sb2NhbC9sbW9kL21vZHVsZWZpbGVzL3Npbmd1bGFyaXR5LzMuMTAuNS5sdWEiLApmdWxsTmFtZSA9ICJzaW5ndWxhcml0eS8zLjEwLjUiLApsb2FkT3JkZXIgPSAyLApwcm9wVCA9IHt9LApzdGFja0RlcHRoID0gMCwKc3RhdHVzID0gImFjdGl2ZSIsCnVzZXJOYW1lID0gInNpbmd1bGFyaXR5IiwKd1YgPSAiXjAwMDAwMDAzLjAwMDAwMDAxMC4wMDAwMDAwMDUuKnpmaW5hbCIsCn0s
* _ModuleTable002_ : CnR1cmJvdm5jID0gewpmbiA9ICIvdXNyL2xvY2FsL2xtb2QvbW9kdWxlZmlsZXMvdHVyYm92bmMubHVhIiwKZnVsbE5hbWUgPSAidHVyYm92bmMiLApsb2FkT3JkZXIgPSAxLApwcm9wVCA9IHt9LApzdGFja0RlcHRoID0gMCwKc3RhdHVzID0gImFjdGl2ZSIsCnVzZXJOYW1lID0gInR1cmJvdm5jIiwKd1YgPSAiTS4qemZpbmFsIiwKfSwKfSwKbXBhdGhBID0gewoiL3Vzci9sb2NhbC9sbW9kL21vZHVsZWZpbGVzIiwKfSwKc3lzdGVtQmFzZU1QQVRIID0gIi91c3IvbG9jYWwvbG1vZC9tb2R1bGVmaWxlcyIsCn0K
* _ModuleTable_Sz_ : 2
* __LMOD_REF_COUNT_MANPATH : /usr/local/current/singularity/3.10.5/share/man:1;/usr/local/slurm/share/man:3;/usr/local/lmod/lmod/8.7/share/man:1;/usr/local/current/turbovnc/share/man:1
* __LMOD_REF_COUNT_MODULEPATH : /usr/local/lmod/modulefiles:1
* __LMOD_REF_COUNT_PATH : /usr/local/current/singularity/3.10.5/bin:1;/usr/local/slurm/bin:3;/usr/local/current/turbovnc/bin:1;/usr/local/bin:2;/usr/X11R6/bin:1;/usr/local/jdk/bin:1;/usr/bin:1;/usr/local/sbin:1;/usr/sbin:1;/usr/local/mysql/bin:1;/home/zugmana2/.local/bin:1;/home/zugmana2/bin:1
* biowulf_FAMILY_SINGULARITY : singularity
* biowulf_FAMILY_SINGULARITY_VERSION : 3.10.5
* ftp_proxy : http://dtn04-e0:3128
* http_proxy : http://dtn04-e0:3128
* https_proxy : http://dtn04-e0:3128
* which_declare : declare -f

