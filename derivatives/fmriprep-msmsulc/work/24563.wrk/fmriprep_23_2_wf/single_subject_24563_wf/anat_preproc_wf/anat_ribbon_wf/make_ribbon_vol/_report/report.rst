Node: single_subject_24563_wf (anat_preproc_wf (anat_ribbon_wf (make_ribbon_vol (fsl)
=====================================================================================


 Hierarchy : fmriprep_23_2_wf.single_subject_24563_wf.anat_preproc_wf.anat_ribbon_wf.make_ribbon_vol
 Exec ID : make_ribbon_vol


Original Inputs
---------------


* args : <undefined>
* environ : {'FSLOUTPUTTYPE': 'NIFTI_GZ'}
* in_file : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_ribbon_wf/bin_pial_distvol/mapflow/_bin_pial_distvol0/lh.pial_converted_distvol_maths_bin.nii.gz', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_ribbon_wf/bin_pial_distvol/mapflow/_bin_pial_distvol1/rh.pial_converted_distvol_maths_bin.nii.gz']
* internal_datatype : <undefined>
* nan2zeros : <undefined>
* op_string : -mas %s -mul 255
* operand_files : [['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_ribbon_wf/bin_wm_distvol/mapflow/_bin_wm_distvol0/lh.white_converted_distvol_maths_bin.nii.gz'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_ribbon_wf/bin_wm_distvol/mapflow/_bin_wm_distvol1/rh.white_converted_distvol_maths_bin.nii.gz']]
* out_file : <undefined>
* output_datatype : <undefined>
* output_type : NIFTI_GZ


Execution Inputs
----------------


* args : <undefined>
* environ : {'FSLOUTPUTTYPE': 'NIFTI_GZ'}
* in_file : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_ribbon_wf/bin_pial_distvol/mapflow/_bin_pial_distvol0/lh.pial_converted_distvol_maths_bin.nii.gz', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_ribbon_wf/bin_pial_distvol/mapflow/_bin_pial_distvol1/rh.pial_converted_distvol_maths_bin.nii.gz']
* internal_datatype : <undefined>
* nan2zeros : <undefined>
* op_string : -mas %s -mul 255
* operand_files : [['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_ribbon_wf/bin_wm_distvol/mapflow/_bin_wm_distvol0/lh.white_converted_distvol_maths_bin.nii.gz'], ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_ribbon_wf/bin_wm_distvol/mapflow/_bin_wm_distvol1/rh.white_converted_distvol_maths_bin.nii.gz']]
* out_file : <undefined>
* output_datatype : <undefined>
* output_type : NIFTI_GZ


Execution Outputs
-----------------


* out_file : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_ribbon_wf/make_ribbon_vol/mapflow/_make_ribbon_vol0/lh.pial_converted_distvol_maths_bin_maths.nii.gz', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_ribbon_wf/make_ribbon_vol/mapflow/_make_ribbon_vol1/rh.pial_converted_distvol_maths_bin_maths.nii.gz']


Subnode reports
---------------


 subnode 0 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_ribbon_wf/make_ribbon_vol/mapflow/_make_ribbon_vol0/_report/report.rst
 subnode 1 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_ribbon_wf/make_ribbon_vol/mapflow/_make_ribbon_vol1/_report/report.rst

