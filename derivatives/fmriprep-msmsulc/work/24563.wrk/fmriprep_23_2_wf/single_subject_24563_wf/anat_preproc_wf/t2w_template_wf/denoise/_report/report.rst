Node: single_subject_24563_wf (anat_preproc_wf (t2w_template_wf (denoise (ants)
===============================================================================


 Hierarchy : fmriprep_23_2_wf.single_subject_24563_wf.anat_preproc_wf.t2w_template_wf.denoise
 Exec ID : denoise


Original Inputs
---------------


* args : <undefined>
* dimension : <undefined>
* environ : {'NSLOTS': '16'}
* input_image : ['/data/EDB/TMSpilot/BIDS/sub-24563/ses-2/anat/sub-24563_ses-2_rec-norm_run-1_T2w.nii.gz', '/data/EDB/TMSpilot/BIDS/sub-24563/ses-2/anat/sub-24563_ses-2_rec-orig_run-1_T2w.nii.gz']
* noise_image : <undefined>
* noise_model : Rician
* num_threads : 16
* output_image : <undefined>
* save_noise : False
* shrink_factor : 1
* verbose : <undefined>


Execution Inputs
----------------


* args : <undefined>
* dimension : <undefined>
* environ : {'NSLOTS': '16'}
* input_image : ['/data/EDB/TMSpilot/BIDS/sub-24563/ses-2/anat/sub-24563_ses-2_rec-norm_run-1_T2w.nii.gz', '/data/EDB/TMSpilot/BIDS/sub-24563/ses-2/anat/sub-24563_ses-2_rec-orig_run-1_T2w.nii.gz']
* noise_image : <undefined>
* noise_model : Rician
* num_threads : 16
* output_image : <undefined>
* save_noise : False
* shrink_factor : 1
* verbose : <undefined>


Execution Outputs
-----------------


* noise_image : <undefined>
* output_image : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/t2w_template_wf/denoise/mapflow/_denoise0/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected.nii.gz', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/t2w_template_wf/denoise/mapflow/_denoise1/sub-24563_ses-2_rec-orig_run-1_T2w_noise_corrected.nii.gz']


Subnode reports
---------------


 subnode 0 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/t2w_template_wf/denoise/mapflow/_denoise0/_report/report.rst
 subnode 1 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/t2w_template_wf/denoise/mapflow/_denoise1/_report/report.rst

