Node: single_subject_24563_wf (anat_preproc_wf (morph_grayords_wf (resample (workbench)
=======================================================================================


 Hierarchy : fmriprep_23_2_wf.single_subject_24563_wf.anat_preproc_wf.morph_grayords_wf.resample
 Exec ID : resample


Original Inputs
---------------


* area_metrics : True
* area_surfs : <undefined>
* args : <undefined>
* current_area : ['/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-L_den-164k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-R_den-164k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-L_den-164k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-R_den-164k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-L_den-164k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-R_den-164k_desc-vaavg_midthickness.shape.gii']
* current_sphere : ['/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-L_den-164k_desc-std_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-R_den-164k_desc-std_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-L_den-164k_desc-std_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-R_den-164k_desc-std_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-L_den-164k_desc-std_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-R_den-164k_desc-std_sphere.surf.gii']
* environ : {}
* in_file : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/surf2surf/mapflow/_surf2surf0/lh.curv.fsaverage.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/surf2surf/mapflow/_surf2surf1/rh.curv.fsaverage.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/surf2surf/mapflow/_surf2surf2/lh.sulc.fsaverage.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/surf2surf/mapflow/_surf2surf3/rh.sulc.fsaverage.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/surf2surf/mapflow/_surf2surf4/lh.thickness.fsaverage.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/surf2surf/mapflow/_surf2surf5/rh.thickness.fsaverage.gii']
* largest : <undefined>
* method : ADAP_BARY_AREA
* new_area : ['/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_hemi-L_den-32k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_hemi-R_den-32k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_hemi-L_den-32k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_hemi-R_den-32k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_hemi-L_den-32k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_hemi-R_den-32k_desc-vaavg_midthickness.shape.gii']
* new_sphere : ['/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_space-fsaverage_hemi-L_den-32k_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_space-fsaverage_hemi-R_den-32k_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_space-fsaverage_hemi-L_den-32k_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_space-fsaverage_hemi-R_den-32k_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_space-fsaverage_hemi-L_den-32k_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_space-fsaverage_hemi-R_den-32k_sphere.surf.gii']
* out_file : ['space-fsLR_hemi-L_den-91k_curv.shape.gii', 'space-fsLR_hemi-R_den-91k_curv.shape.gii', 'space-fsLR_hemi-L_den-91k_sulc.shape.gii', 'space-fsLR_hemi-R_den-91k_sulc.shape.gii', 'space-fsLR_hemi-L_den-91k_thickness.shape.gii', 'space-fsLR_hemi-R_den-91k_thickness.shape.gii']
* roi_metric : <undefined>
* valid_roi_out : <undefined>


Execution Inputs
----------------


* area_metrics : True
* area_surfs : <undefined>
* args : <undefined>
* current_area : ['/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-L_den-164k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-R_den-164k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-L_den-164k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-R_den-164k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-L_den-164k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-R_den-164k_desc-vaavg_midthickness.shape.gii']
* current_sphere : ['/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-L_den-164k_desc-std_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-R_den-164k_desc-std_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-L_den-164k_desc-std_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-R_den-164k_desc-std_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-L_den-164k_desc-std_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsaverage/tpl-fsaverage_hemi-R_den-164k_desc-std_sphere.surf.gii']
* environ : {}
* in_file : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/surf2surf/mapflow/_surf2surf0/lh.curv.fsaverage.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/surf2surf/mapflow/_surf2surf1/rh.curv.fsaverage.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/surf2surf/mapflow/_surf2surf2/lh.sulc.fsaverage.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/surf2surf/mapflow/_surf2surf3/rh.sulc.fsaverage.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/surf2surf/mapflow/_surf2surf4/lh.thickness.fsaverage.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/surf2surf/mapflow/_surf2surf5/rh.thickness.fsaverage.gii']
* largest : <undefined>
* method : ADAP_BARY_AREA
* new_area : ['/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_hemi-L_den-32k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_hemi-R_den-32k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_hemi-L_den-32k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_hemi-R_den-32k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_hemi-L_den-32k_desc-vaavg_midthickness.shape.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_hemi-R_den-32k_desc-vaavg_midthickness.shape.gii']
* new_sphere : ['/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_space-fsaverage_hemi-L_den-32k_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_space-fsaverage_hemi-R_den-32k_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_space-fsaverage_hemi-L_den-32k_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_space-fsaverage_hemi-R_den-32k_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_space-fsaverage_hemi-L_den-32k_sphere.surf.gii', '/home/zugmana2/.cache/templateflow/tpl-fsLR/tpl-fsLR_space-fsaverage_hemi-R_den-32k_sphere.surf.gii']
* out_file : ['space-fsLR_hemi-L_den-91k_curv.shape.gii', 'space-fsLR_hemi-R_den-91k_curv.shape.gii', 'space-fsLR_hemi-L_den-91k_sulc.shape.gii', 'space-fsLR_hemi-R_den-91k_sulc.shape.gii', 'space-fsLR_hemi-L_den-91k_thickness.shape.gii', 'space-fsLR_hemi-R_den-91k_thickness.shape.gii']
* roi_metric : <undefined>
* valid_roi_out : <undefined>


Execution Outputs
-----------------


* out_file : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample0/space-fsLR_hemi-L_den-91k_curv.shape.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample1/space-fsLR_hemi-R_den-91k_curv.shape.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample2/space-fsLR_hemi-L_den-91k_sulc.shape.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample3/space-fsLR_hemi-R_den-91k_sulc.shape.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample4/space-fsLR_hemi-L_den-91k_thickness.shape.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample5/space-fsLR_hemi-R_den-91k_thickness.shape.gii']
* roi_file : <undefined>


Subnode reports
---------------


 subnode 0 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample0/_report/report.rst
 subnode 1 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample1/_report/report.rst
 subnode 2 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample2/_report/report.rst
 subnode 3 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample3/_report/report.rst
 subnode 4 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample4/_report/report.rst
 subnode 5 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/morph_grayords_wf/resample/mapflow/_resample5/_report/report.rst

