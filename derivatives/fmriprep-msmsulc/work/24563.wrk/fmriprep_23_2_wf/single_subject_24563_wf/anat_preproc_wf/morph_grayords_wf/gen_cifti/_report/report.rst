Node: single_subject_24563_wf (anat_preproc_wf (morph_grayords_wf (gen_cifti (cifti)
====================================================================================


 Hierarchy : fmriprep_23_2_wf.single_subject_24563_wf.anat_preproc_wf.morph_grayords_wf.gen_cifti
 Exec ID : gen_cifti


Original Inputs
---------------


* grayordinates : 91k
* scalar_name : ['curv', 'sulc', 'thickness']
* scalar_surfs : [['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample0/space-fsLR_hemi-L_den-91k_curv.shape.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample1/space-fsLR_hemi-R_den-91k_curv.shape.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample2/space-fsLR_hemi-L_den-91k_sulc.shape.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample3/space-fsLR_hemi-R_den-91k_sulc.shape.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample4/space-fsLR_hemi-L_den-91k_thickness.shape.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample5/space-fsLR_hemi-R_den-91k_thickness.shape.gii']]
* surface_target : fsLR


Execution Inputs
----------------


* grayordinates : 91k
* scalar_name : ['curv', 'sulc', 'thickness']
* scalar_surfs : [['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample0/space-fsLR_hemi-L_den-91k_curv.shape.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample1/space-fsLR_hemi-R_den-91k_curv.shape.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample2/space-fsLR_hemi-L_den-91k_sulc.shape.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample3/space-fsLR_hemi-R_den-91k_sulc.shape.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample4/space-fsLR_hemi-L_den-91k_thickness.shape.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample5/space-fsLR_hemi-R_den-91k_thickness.shape.gii']]
* surface_target : fsLR


Execution Outputs
-----------------


* out_file : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/gen_cifti/mapflow/_gen_cifti0/space-fsLR_den-91k_curv.dscalar.nii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/gen_cifti/mapflow/_gen_cifti1/space-fsLR_den-91k_sulc.dscalar.nii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/gen_cifti/mapflow/_gen_cifti2/space-fsLR_den-91k_thickness.dscalar.nii']
* out_metadata : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/gen_cifti/mapflow/_gen_cifti0/dscalar.json', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/gen_cifti/mapflow/_gen_cifti1/dscalar.json', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/gen_cifti/mapflow/_gen_cifti2/dscalar.json']


Subnode reports
---------------


 subnode 0 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/gen_cifti/mapflow/_gen_cifti0/_report/report.rst
 subnode 1 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/gen_cifti/mapflow/_gen_cifti1/_report/report.rst
 subnode 2 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/gen_cifti/mapflow/_gen_cifti2/_report/report.rst

