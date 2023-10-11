Node: single_subject_24563_wf (anat_preproc_wf (sphere_reg_wf (msm_sulc_wf (msmsulc (msm)
=========================================================================================


 Hierarchy : fmriprep_23_2_wf.single_subject_24563_wf.anat_preproc_wf.sphere_reg_wf.msm_sulc_wf.msmsulc
 Exec ID : msmsulc


Original Inputs
---------------


* args : <undefined>
* config_file : /opt/conda/envs/fmriprep/lib/python3.10/site-packages/smriprep/data/msm/MSMSulcStrainFinalconf
* environ : {}
* in_data : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/morphs2gii/mapflow/_morphs2gii2/lh.sulc_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/morphs2gii/mapflow/_morphs2gii3/rh.sulc_converted.gii']
* in_mesh : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/sphere_reg_wf/msm_sulc_wf/apply_surface_affine/mapflow/_apply_surface_affine0/lh.sphere_converted_xformed.surf.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/sphere_reg_wf/msm_sulc_wf/apply_surface_affine/mapflow/_apply_surface_affine1/rh.sphere_converted_xformed.surf.gii']
* in_register : <undefined>
* in_weight : <undefined>
* levels : <undefined>
* out_base : ['lh.', 'rh.']
* output_format : <undefined>
* reference_data : ['/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-L_den-164k_sulc.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-R_den-164k_sulc.shape.gii']
* reference_mesh : ['/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-L_den-164k_desc-std_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-R_den-164k_desc-std_sphere.surf.gii']
* reference_weight : <undefined>
* smooth_output_sigma : <undefined>
* transformed_mesh : <undefined>
* verbose : True


Execution Inputs
----------------


* args : <undefined>
* config_file : /opt/conda/envs/fmriprep/lib/python3.10/site-packages/smriprep/data/msm/MSMSulcStrainFinalconf
* environ : {}
* in_data : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/morphs2gii/mapflow/_morphs2gii2/lh.sulc_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/morphs2gii/mapflow/_morphs2gii3/rh.sulc_converted.gii']
* in_mesh : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/sphere_reg_wf/msm_sulc_wf/apply_surface_affine/mapflow/_apply_surface_affine0/lh.sphere_converted_xformed.surf.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/sphere_reg_wf/msm_sulc_wf/apply_surface_affine/mapflow/_apply_surface_affine1/rh.sphere_converted_xformed.surf.gii']
* in_register : <undefined>
* in_weight : <undefined>
* levels : <undefined>
* out_base : ['lh.', 'rh.']
* output_format : <undefined>
* reference_data : ['/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-L_den-164k_sulc.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-R_den-164k_sulc.shape.gii']
* reference_mesh : ['/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-L_den-164k_desc-std_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-R_den-164k_desc-std_sphere.surf.gii']
* reference_weight : <undefined>
* smooth_output_sigma : <undefined>
* transformed_mesh : <undefined>
* verbose : True


Execution Outputs
-----------------


* downsampled_warped_mesh : <undefined>
* warped_data : <undefined>
* warped_mesh : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/sphere_reg_wf/msm_sulc_wf/msmsulc/mapflow/_msmsulc0/lh.sphere.reg.surf.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/sphere_reg_wf/msm_sulc_wf/msmsulc/mapflow/_msmsulc1/rh.sphere.reg.surf.gii']


Subnode reports
---------------


 subnode 0 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/sphere_reg_wf/msm_sulc_wf/msmsulc/mapflow/_msmsulc0/_report/report.rst
 subnode 1 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/sphere_reg_wf/msm_sulc_wf/msmsulc/mapflow/_msmsulc1/_report/report.rst

