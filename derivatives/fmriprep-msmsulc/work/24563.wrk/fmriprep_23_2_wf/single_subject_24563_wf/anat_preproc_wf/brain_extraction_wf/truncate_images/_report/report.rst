Node: single_subject_24563_wf (anat_preproc_wf (brain_extraction_wf (truncate_images (ants)
===========================================================================================


 Hierarchy : fmriprep_23_2_wf.single_subject_24563_wf.anat_preproc_wf.brain_extraction_wf.truncate_images
 Exec ID : truncate_images


Original Inputs
---------------


* args : <undefined>
* copy_header : True
* dimension : 3
* environ : {'NSLOTS': '1'}
* num_threads : 1
* op1 : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_template_wf/anat_merge/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template.nii.gz']
* op2 : 0.01 0.999 256
* operation : TruncateImageIntensity
* output_image : <undefined>


Execution Inputs
----------------


* args : <undefined>
* copy_header : True
* dimension : 3
* environ : {'NSLOTS': '1'}
* num_threads : 1
* op1 : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_template_wf/anat_merge/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template.nii.gz']
* op2 : 0.01 0.999 256
* operation : TruncateImageIntensity
* output_image : <undefined>


Execution Outputs
-----------------


* output_image : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/truncate_images/mapflow/_truncate_images0/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template_maths.nii.gz']


Subnode reports
---------------


 subnode 0 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/brain_extraction_wf/truncate_images/mapflow/_truncate_images0/_report/report.rst

