Node: single_subject_24563_wf (anat_preproc_wf (anat_derivatives_wf (ds_surfs)
==============================================================================


 Hierarchy : fmriprep_23_2_wf.single_subject_24563_wf.anat_preproc_wf.anat_derivatives_wf.ds_surfs
 Exec ID : ds_surfs


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
* extension : .surf.gii
* flip : <undefined>
* fmap : <undefined>
* fmapid : <undefined>
* from : <undefined>
* hemi : ['L', 'R', 'L', 'R', 'L', 'R', 'L', 'R']
* in_file : [['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs0/lh.white_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs1/rh.white_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs2/lh.pial_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs3/rh.pial_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs4/lh.inflated_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs5/rh.inflated_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs6/lh.midthickness_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs7/rh.midthickness_converted.gii']]
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
* suffix : ['white', 'white', 'pial', 'pial', 'inflated', 'inflated', 'midthickness', 'midthickness']
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
* extension : .surf.gii
* flip : <undefined>
* fmap : <undefined>
* fmapid : <undefined>
* from : <undefined>
* hemi : ['L', 'R', 'L', 'R', 'L', 'R', 'L', 'R']
* in_file : [['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs0/lh.white_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs1/rh.white_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs2/lh.pial_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs3/rh.pial_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs4/lh.inflated_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs5/rh.inflated_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs6/lh.midthickness_converted.gii'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs7/rh.midthickness_converted.gii']]
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
* suffix : ['white', 'white', 'pial', 'pial', 'inflated', 'inflated', 'midthickness', 'midthickness']
* task : <undefined>
* to : <undefined>


Execution Outputs
-----------------


* compression : [False, False, False, False, False, False, False, False]
* fixed_hdr : [[False], [False], [False], [False], [False], [False], [False], [False]]
* out_file : ['/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_hemi-L_white.surf.gii', '/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_hemi-R_white.surf.gii', '/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_hemi-L_pial.surf.gii', '/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_hemi-R_pial.surf.gii', '/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_hemi-L_inflated.surf.gii', '/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_hemi-R_inflated.surf.gii', '/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_hemi-L_midthickness.surf.gii', '/lscratch/8536404/24563.out/sub-24563/anat/sub-24563_rec-orig_run-1_hemi-R_midthickness.surf.gii']
* out_meta : <undefined>


Subnode reports
---------------


 subnode 0 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_derivatives_wf/ds_surfs/mapflow/_ds_surfs0/_report/report.rst
 subnode 1 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_derivatives_wf/ds_surfs/mapflow/_ds_surfs1/_report/report.rst
 subnode 2 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_derivatives_wf/ds_surfs/mapflow/_ds_surfs2/_report/report.rst
 subnode 3 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_derivatives_wf/ds_surfs/mapflow/_ds_surfs3/_report/report.rst
 subnode 4 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_derivatives_wf/ds_surfs/mapflow/_ds_surfs4/_report/report.rst
 subnode 5 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_derivatives_wf/ds_surfs/mapflow/_ds_surfs5/_report/report.rst
 subnode 6 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_derivatives_wf/ds_surfs/mapflow/_ds_surfs6/_report/report.rst
 subnode 7 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_derivatives_wf/ds_surfs/mapflow/_ds_surfs7/_report/report.rst

