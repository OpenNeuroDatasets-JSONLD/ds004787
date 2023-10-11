Node: single_subject_24563_wf (anat_preproc_wf (anat_derivatives_wf (ds_morphs)
===============================================================================


 Hierarchy : fmriprep_23_2_wf.single_subject_24563_wf.anat_preproc_wf.anat_derivatives_wf.ds_morphs
 Exec ID : ds_morphs


Original Inputs
---------------


* acquisition : <undefined>
* atlas : <undefined>
* base_directory : /lscratch/8536404/24563.out
* ceagent : <undefined>
* check_hdr : True
* cohort : <undefined>
* compress : <undefined>
* data_dtype : <undefined>
* datatype : <undefined>
* density : <undefined>
* desc : <undefined>
* direction : <undefined>
* dismiss_entities : <undefined>
* echo : <undefined>
* extension : .shape.gii
* flip : <undefined>
* fmap : <undefined>
* fmapid : <undefined>
* from : <undefined>
* hemi : ['L', 'R', 'L', 'R', 'L', 'R']
* in_file : [['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/morphs2gii/mapflow/_morphs2gii0/lh.thickness_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/morphs2gii/mapflow/_morphs2gii1/rh.thickness_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/morphs2gii/mapflow/_morphs2gii2/lh.sulc_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/morphs2gii/mapflow/_morphs2gii3/rh.sulc_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/morphs2gii/mapflow/_morphs2gii4/lh.curv_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/morphs2gii/mapflow/_morphs2gii5/rh.curv_converted.gii']]
* inv : <undefined>
* label : <undefined>
* meta_dict : <undefined>
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
* space : <undefined>
* subject : <undefined>
* subset : <undefined>
* suffix : ['thickness', 'thickness', 'sulc', 'sulc', 'curv', 'curv']
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
* compress : <undefined>
* data_dtype : <undefined>
* datatype : <undefined>
* density : <undefined>
* desc : <undefined>
* direction : <undefined>
* dismiss_entities : <undefined>
* echo : <undefined>
* extension : .shape.gii
* flip : <undefined>
* fmap : <undefined>
* fmapid : <undefined>
* from : <undefined>
* hemi : ['L', 'R', 'L', 'R', 'L', 'R']
* in_file : [['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/morphs2gii/mapflow/_morphs2gii0/lh.thickness_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/morphs2gii/mapflow/_morphs2gii1/rh.thickness_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/morphs2gii/mapflow/_morphs2gii2/lh.sulc_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/morphs2gii/mapflow/_morphs2gii3/rh.sulc_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/morphs2gii/mapflow/_morphs2gii4/lh.curv_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/morphs2gii/mapflow/_morphs2gii5/rh.curv_converted.gii']]
* inv : <undefined>
* label : <undefined>
* meta_dict : <undefined>
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
* space : <undefined>
* subject : <undefined>
* subset : <undefined>
* suffix : ['thickness', 'thickness', 'sulc', 'sulc', 'curv', 'curv']
* task : <undefined>
* to : <undefined>


Execution Outputs
-----------------


* compression : [False, False, False, False, False, False]
* fixed_hdr : [[False], [False], [False], [False], [False], [False]]
* out_file : ['/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_hemi-L_thickness.shape.gii', '/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_hemi-R_thickness.shape.gii', '/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_hemi-L_sulc.shape.gii', '/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_hemi-R_sulc.shape.gii', '/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_hemi-L_curv.shape.gii', '/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_hemi-R_curv.shape.gii']
* out_meta : <undefined>


Subnode reports
---------------


 subnode 0 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_derivatives_wf/ds_morphs/mapflow/_ds_morphs0/_report/report.rst
 subnode 1 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_derivatives_wf/ds_morphs/mapflow/_ds_morphs1/_report/report.rst
 subnode 2 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_derivatives_wf/ds_morphs/mapflow/_ds_morphs2/_report/report.rst
 subnode 3 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_derivatives_wf/ds_morphs/mapflow/_ds_morphs3/_report/report.rst
 subnode 4 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_derivatives_wf/ds_morphs/mapflow/_ds_morphs4/_report/report.rst
 subnode 5 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_derivatives_wf/ds_morphs/mapflow/_ds_morphs5/_report/report.rst

