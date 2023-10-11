Node: single_subject_24563_wf (anat_preproc_wf (anat_derivatives_wf (ds_cifti_morph)
====================================================================================


 Hierarchy : fmriprep_23_2_wf.single_subject_24563_wf.anat_preproc_wf.anat_derivatives_wf.ds_cifti_morph
 Exec ID : ds_cifti_morph


Original Inputs
---------------


* acquisition : <undefined>
* atlas : <undefined>
* base_directory : /lscratch/8536404/24563.out
* ceagent : <undefined>
* check_hdr : True
* cohort : <undefined>
* compress : [False]
* data_dtype : <undefined>
* datatype : <undefined>
* density : <undefined>
* desc : <undefined>
* direction : <undefined>
* dismiss_entities : <undefined>
* echo : <undefined>
* extension : <undefined>
* flip : <undefined>
* fmap : <undefined>
* fmapid : <undefined>
* from : <undefined>
* hemi : <undefined>
* in_file : [['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/gen_cifti/mapflow/_gen_cifti0/space-fsLR_den-91k_curv.dscalar.nii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/gen_cifti/mapflow/_gen_cifti1/space-fsLR_den-91k_sulc.dscalar.nii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/gen_cifti/mapflow/_gen_cifti2/space-fsLR_den-91k_thickness.dscalar.nii']]
* inv : <undefined>
* label : <undefined>
* meta_dict : [{'Density': '91,282 grayordinates corresponding to all of the grey matter sampled at a 2mm average vertex spacing on the surface', 'SpatialReference': {'CIFTI_STRUCTURE_CORTEX_LEFT': 'https://templateflow.s3.amazonaws.com/tpl-fsLR/tpl-fsLR_den-32k_hemi-L_midthickness.surf.gii', 'CIFTI_STRUCTURE_CORTEX_RIGHT': 'https://templateflow.s3.amazonaws.com/tpl-fsLR/tpl-fsLR_den-32k_hemi-R_midthickness.surf.gii'}}, {'Density': '91,282 grayordinates corresponding to all of the grey matter sampled at a 2mm average vertex spacing on the surface', 'SpatialReference': {'CIFTI_STRUCTURE_CORTEX_LEFT': 'https://templateflow.s3.amazonaws.com/tpl-fsLR/tpl-fsLR_den-32k_hemi-L_midthickness.surf.gii', 'CIFTI_STRUCTURE_CORTEX_RIGHT': 'https://templateflow.s3.amazonaws.com/tpl-fsLR/tpl-fsLR_den-32k_hemi-R_midthickness.surf.gii'}}, {'Density': '91,282 grayordinates corresponding to all of the grey matter sampled at a 2mm average vertex spacing on the surface', 'SpatialReference': {'CIFTI_STRUCTURE_CORTEX_LEFT': 'https://templateflow.s3.amazonaws.com/tpl-fsLR/tpl-fsLR_den-32k_hemi-L_midthickness.surf.gii', 'CIFTI_STRUCTURE_CORTEX_RIGHT': 'https://templateflow.s3.amazonaws.com/tpl-fsLR/tpl-fsLR_den-32k_hemi-R_midthickness.surf.gii'}}]
* modality : <undefined>
* mode : <undefined>
* model : <undefined>
* mt : <undefined>
* part : <undefined>
* proc : <undefined>
* reconstruction : <undefined>
* recording : <undefined>
* resolution : <undefined>
* roi : <undefined>
* run : <undefined>
* scans : <undefined>
* session : <undefined>
* source_file : <undefined>
* space : fsLR
* subject : <undefined>
* subset : <undefined>
* suffix : ['curv', 'sulc', 'thickness']
* task : <undefined>
* to : <undefined>


Execution Inputs
----------------


* acquisition : <undefined>
* atlas : <undefined>
* base_directory : /lscratch/8536404/24563.out
* ceagent : <undefined>
* check_hdr : True
* cohort : <undefined>
* compress : [False]
* data_dtype : <undefined>
* datatype : <undefined>
* density : <undefined>
* desc : <undefined>
* direction : <undefined>
* dismiss_entities : <undefined>
* echo : <undefined>
* extension : <undefined>
* flip : <undefined>
* fmap : <undefined>
* fmapid : <undefined>
* from : <undefined>
* hemi : <undefined>
* in_file : [['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/gen_cifti/mapflow/_gen_cifti0/space-fsLR_den-91k_curv.dscalar.nii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/gen_cifti/mapflow/_gen_cifti1/space-fsLR_den-91k_sulc.dscalar.nii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/gen_cifti/mapflow/_gen_cifti2/space-fsLR_den-91k_thickness.dscalar.nii']]
* inv : <undefined>
* label : <undefined>
* meta_dict : [{'Density': '91,282 grayordinates corresponding to all of the grey matter sampled at a 2mm average vertex spacing on the surface', 'SpatialReference': {'CIFTI_STRUCTURE_CORTEX_LEFT': 'https://templateflow.s3.amazonaws.com/tpl-fsLR/tpl-fsLR_den-32k_hemi-L_midthickness.surf.gii', 'CIFTI_STRUCTURE_CORTEX_RIGHT': 'https://templateflow.s3.amazonaws.com/tpl-fsLR/tpl-fsLR_den-32k_hemi-R_midthickness.surf.gii'}}, {'Density': '91,282 grayordinates corresponding to all of the grey matter sampled at a 2mm average vertex spacing on the surface', 'SpatialReference': {'CIFTI_STRUCTURE_CORTEX_LEFT': 'https://templateflow.s3.amazonaws.com/tpl-fsLR/tpl-fsLR_den-32k_hemi-L_midthickness.surf.gii', 'CIFTI_STRUCTURE_CORTEX_RIGHT': 'https://templateflow.s3.amazonaws.com/tpl-fsLR/tpl-fsLR_den-32k_hemi-R_midthickness.surf.gii'}}, {'Density': '91,282 grayordinates corresponding to all of the grey matter sampled at a 2mm average vertex spacing on the surface', 'SpatialReference': {'CIFTI_STRUCTURE_CORTEX_LEFT': 'https://templateflow.s3.amazonaws.com/tpl-fsLR/tpl-fsLR_den-32k_hemi-L_midthickness.surf.gii', 'CIFTI_STRUCTURE_CORTEX_RIGHT': 'https://templateflow.s3.amazonaws.com/tpl-fsLR/tpl-fsLR_den-32k_hemi-R_midthickness.surf.gii'}}]
* modality : <undefined>
* mode : <undefined>
* model : <undefined>
* mt : <undefined>
* part : <undefined>
* proc : <undefined>
* reconstruction : <undefined>
* recording : <undefined>
* resolution : <undefined>
* roi : <undefined>
* run : <undefined>
* scans : <undefined>
* session : <undefined>
* source_file : <undefined>
* space : fsLR
* subject : <undefined>
* subset : <undefined>
* suffix : ['curv', 'sulc', 'thickness']
* task : <undefined>
* to : <undefined>


Execution Outputs
-----------------


* compression : [False, False, False]
* fixed_hdr : [[False], [False], [False]]
* out_file : ['/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_space-fsLR_den-91k_curv.dscalar.nii', '/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_space-fsLR_den-91k_sulc.dscalar.nii', '/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_space-fsLR_den-91k_thickness.dscalar.nii']
* out_meta : ['/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_space-fsLR_den-91k_curv.json', '/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_space-fsLR_den-91k_sulc.json', '/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_space-fsLR_den-91k_thickness.json']


Subnode reports
---------------


 subnode 0 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_derivatives_wf/ds_cifti_morph/mapflow/_ds_cifti_morph0/_report/report.rst
 subnode 1 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_derivatives_wf/ds_cifti_morph/mapflow/_ds_cifti_morph1/_report/report.rst
 subnode 2 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_derivatives_wf/ds_cifti_morph/mapflow/_ds_cifti_morph2/_report/report.rst

