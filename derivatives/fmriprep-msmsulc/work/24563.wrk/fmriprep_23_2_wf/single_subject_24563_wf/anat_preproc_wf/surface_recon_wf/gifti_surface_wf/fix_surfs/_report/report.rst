Node: single_subject_24563_wf (anat_preproc_wf (surface_recon_wf (gifti_surface_wf (fix_surfs (surf)
====================================================================================================


 Hierarchy : fmriprep_23_2_wf.single_subject_24563_wf.anat_preproc_wf.surface_recon_wf.gifti_surface_wf.fix_surfs
 Exec ID : fix_surfs


Original Inputs
---------------


* in_file : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fs2gii/mapflow/_fs2gii0/lh.white_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fs2gii/mapflow/_fs2gii1/rh.white_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fs2gii/mapflow/_fs2gii2/lh.pial_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fs2gii/mapflow/_fs2gii3/rh.pial_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fs2gii/mapflow/_fs2gii4/lh.inflated_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fs2gii/mapflow/_fs2gii5/rh.inflated_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fs2gii/mapflow/_fs2gii6/lh.midthickness_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fs2gii/mapflow/_fs2gii7/rh.midthickness_converted.gii']
* transform_file : <undefined>


Execution Inputs
----------------


* in_file : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fs2gii/mapflow/_fs2gii0/lh.white_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fs2gii/mapflow/_fs2gii1/rh.white_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fs2gii/mapflow/_fs2gii2/lh.pial_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fs2gii/mapflow/_fs2gii3/rh.pial_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fs2gii/mapflow/_fs2gii4/lh.inflated_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fs2gii/mapflow/_fs2gii5/rh.inflated_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fs2gii/mapflow/_fs2gii6/lh.midthickness_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fs2gii/mapflow/_fs2gii7/rh.midthickness_converted.gii']
* transform_file : <undefined>


Execution Outputs
-----------------


* out_file : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs0/lh.white_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs1/rh.white_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs2/lh.pial_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs3/rh.pial_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs4/lh.inflated_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs5/rh.inflated_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs6/lh.midthickness_converted.gii', '/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs7/rh.midthickness_converted.gii']


Subnode reports
---------------


 subnode 0 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs0/_report/report.rst
 subnode 1 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs1/_report/report.rst
 subnode 2 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs2/_report/report.rst
 subnode 3 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs3/_report/report.rst
 subnode 4 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs4/_report/report.rst
 subnode 5 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs5/_report/report.rst
 subnode 6 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs6/_report/report.rst
 subnode 7 : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/fix_surfs/mapflow/_fix_surfs7/_report/report.rst

