Node: single_subject_24563_wf (anat_preproc_wf (surface_recon_wf (autorecon1 (freesurfer)
=========================================================================================


 Hierarchy : fmriprep_23_2_wf.single_subject_24563_wf.anat_preproc_wf.surface_recon_wf.autorecon1
 Exec ID : autorecon1


Original Inputs
---------------


* FLAIR_file : <undefined>
* T1_files : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_template_wf/anat_merge/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template.nii.gz']
* T2_file : /data/EDB/TMSpilot/BIDS/sub-24563/ses-2/anat/sub-24563_ses-2_rec-norm_run-1_T2w.nii.gz
* args : <undefined>
* big_ventricles : <undefined>
* brainstem : <undefined>
* directive : autorecon1
* environ : {}
* expert : <undefined>
* flags : ['-noskullstrip', '-noT2pial', '-noFLAIRpial', '-cw256']
* hemi : <undefined>
* hippocampal_subfields_T1 : <undefined>
* hippocampal_subfields_T2 : <undefined>
* hires : True
* mprage : <undefined>
* mri_aparc2aseg : <undefined>
* mri_ca_label : <undefined>
* mri_ca_normalize : <undefined>
* mri_ca_register : <undefined>
* mri_edit_wm_with_aseg : <undefined>
* mri_em_register : <undefined>
* mri_fill : <undefined>
* mri_mask : <undefined>
* mri_normalize : <undefined>
* mri_pretess : <undefined>
* mri_remove_neck : <undefined>
* mri_segment : <undefined>
* mri_segstats : <undefined>
* mri_tessellate : <undefined>
* mri_watershed : <undefined>
* mris_anatomical_stats : <undefined>
* mris_ca_label : <undefined>
* mris_fix_topology : <undefined>
* mris_inflate : -n 50
* mris_make_surfaces : <undefined>
* mris_register : <undefined>
* mris_smooth : <undefined>
* mris_sphere : <undefined>
* mris_surf2vol : <undefined>
* mrisp_paint : <undefined>
* openmp : 16
* parallel : <undefined>
* steps : <undefined>
* subject_id : sub-24563
* subjects_dir : /lscratch/8536404/24563.out/sourcedata/freesurfer
* talairach : <undefined>
* use_FLAIR : <undefined>
* use_T2 : <undefined>
* xopts : <undefined>


Execution Inputs
----------------


* FLAIR_file : <undefined>
* T1_files : ['/lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_template_wf/anat_merge/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template.nii.gz']
* T2_file : /data/EDB/TMSpilot/BIDS/sub-24563/ses-2/anat/sub-24563_ses-2_rec-norm_run-1_T2w.nii.gz
* args : <undefined>
* big_ventricles : <undefined>
* brainstem : <undefined>
* directive : autorecon1
* environ : {}
* expert : <undefined>
* flags : ['-noskullstrip', '-noT2pial', '-noFLAIRpial', '-cw256']
* hemi : <undefined>
* hippocampal_subfields_T1 : <undefined>
* hippocampal_subfields_T2 : <undefined>
* hires : True
* mprage : <undefined>
* mri_aparc2aseg : <undefined>
* mri_ca_label : <undefined>
* mri_ca_normalize : <undefined>
* mri_ca_register : <undefined>
* mri_edit_wm_with_aseg : <undefined>
* mri_em_register : <undefined>
* mri_fill : <undefined>
* mri_mask : <undefined>
* mri_normalize : <undefined>
* mri_pretess : <undefined>
* mri_remove_neck : <undefined>
* mri_segment : <undefined>
* mri_segstats : <undefined>
* mri_tessellate : <undefined>
* mri_watershed : <undefined>
* mris_anatomical_stats : <undefined>
* mris_ca_label : <undefined>
* mris_fix_topology : <undefined>
* mris_inflate : -n 50
* mris_make_surfaces : <undefined>
* mris_register : <undefined>
* mris_smooth : <undefined>
* mris_sphere : <undefined>
* mris_surf2vol : <undefined>
* mrisp_paint : <undefined>
* openmp : 16
* parallel : <undefined>
* steps : <undefined>
* subject_id : sub-24563
* subjects_dir : /lscratch/8536404/24563.out/sourcedata/freesurfer
* talairach : <undefined>
* use_FLAIR : <undefined>
* use_T2 : <undefined>
* xopts : <undefined>


Execution Outputs
-----------------


* BA_stats : <undefined>
* T1 : /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/T1.mgz
* annot : <undefined>
* aparc_a2009s_stats : <undefined>
* aparc_aseg : <undefined>
* aparc_stats : <undefined>
* area_pial : <undefined>
* aseg : <undefined>
* aseg_stats : <undefined>
* avg_curv : <undefined>
* brain : <undefined>
* brainmask : <undefined>
* curv : <undefined>
* curv_pial : <undefined>
* curv_stats : <undefined>
* entorhinal_exvivo_stats : <undefined>
* filled : <undefined>
* graymid : <undefined>
* inflated : <undefined>
* jacobian_white : <undefined>
* label : <undefined>
* norm : <undefined>
* nu : <undefined>
* orig : <undefined>
* pial : <undefined>
* rawavg : <undefined>
* ribbon : <undefined>
* smoothwm : <undefined>
* sphere : <undefined>
* sphere_reg : <undefined>
* subject_id : sub-24563
* subjects_dir : /lscratch/8536404/24563.out/sourcedata/freesurfer
* sulc : <undefined>
* thickness : <undefined>
* volume : <undefined>
* white : <undefined>
* wm : <undefined>
* wmparc : <undefined>
* wmparc_stats : <undefined>


Runtime info
------------


* cmdline : recon-all -autorecon1 -i /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_template_wf/anat_merge/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template.nii.gz -T2 /data/EDB/TMSpilot/BIDS/sub-24563/ses-2/anat/sub-24563_ses-2_rec-norm_run-1_T2w.nii.gz -noskullstrip -noT2pial -noFLAIRpial -cw256 -hires -openmp 16 -subjid sub-24563 -sd /lscratch/8536404/24563.out/sourcedata/freesurfer -expert /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/autorecon1/expert.opts
* duration : 1034.661724
* hostname : cn4271
* prev_wd : /vf/users/EDB/TMSpilot/code
* working_dir : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/autorecon1


Terminal output
~~~~~~~~~~~~~~~


 


Terminal - standard output
~~~~~~~~~~~~~~~~~~~~~~~~~~


 INFO: hi-res volumes are conformed to the min voxel size
fs-check-version --s sub-24563 --o /lscratch/8536404/tmp.lRjyWE
Wed Sep 20 15:22:40 EDT 2023

setenv SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
cd /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/autorecon1
/opt/freesurfer/bin/fs-check-version --s sub-24563 --o /lscratch/8536404/tmp.lRjyWE
-rwxrwxr-x 1 root root 18565 Aug  4  2022 /opt/freesurfer/bin/fs-check-version

freesurfer-linux-ubuntu22_x86_64-7.3.2-20220804-6354275
$Id$
Linux cn4271 4.18.0-425.19.2.el8_7.x86_64 #1 SMP Tue Apr 4 22:38:11 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
pid 3785772
Current FS Version freesurfer-linux-ubuntu22_x86_64-7.3.2-20220804-6354275
Subject does not have a bstampfile, copying /opt/freesurfer/build-stamp.txt
Subject FS Version: freesurfer-linux-ubuntu22_x86_64-7.3.2-20220804-6354275
No constraints on version because REQ=UnSet and FsVerFile=NotThere
#@#% fs-check-version match = 1
fs-check-version Done
INFO: SUBJECTS_DIR is /lscratch/8536404/24563.out/sourcedata/freesurfer
Actual FREESURFER_HOME /opt/freesurfer
Linux cn4271 4.18.0-425.19.2.el8_7.x86_64 #1 SMP Tue Apr 4 22:38:11 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
-cw256 option is now persistent (remove with -clean-cw256)
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563

 mri_convert /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_template_wf/anat_merge/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template.nii.gz /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/001.mgz 

mri_convert /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_template_wf/anat_merge/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template.nii.gz /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/001.mgz 
reading from /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/anat_template_wf/anat_merge/sub-24563_ses-1_rec-orig_run-1_T1w_noise_corrected_template.nii.gz...
TR=0.00, TE=0.00, TI=0.00, flip angle=0.00
i_ras = (1, 0, 0)
j_ras = (0, 1, 0)
k_ras = (-0, -0, 1)
writing to /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/001.mgz...
#--------------------------------------------
#@# T2/FLAIR Input Wed Sep 20 15:22:51 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563

 mri_convert --no_scale 1 /vf/users/EDB/TMSpilot/BIDS/sub-24563/ses-2/anat/sub-24563_ses-2_rec-norm_run-1_T2w.nii.gz /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/T2raw.mgz 

mri_convert --no_scale 1 /vf/users/EDB/TMSpilot/BIDS/sub-24563/ses-2/anat/sub-24563_ses-2_rec-norm_run-1_T2w.nii.gz /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/T2raw.mgz 
reading from /vf/users/EDB/TMSpilot/BIDS/sub-24563/ses-2/anat/sub-24563_ses-2_rec-norm_run-1_T2w.nii.gz...
TR=3206.00, TE=0.00, TI=0.00, flip angle=0.00
i_ras = (1, 0, 0)
j_ras = (0, 1, 0)
k_ras = (0, 0, 1)
writing to /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/T2raw.mgz...
#--------------------------------------------
#@# MotionCor Wed Sep 20 15:23:00 EDT 2023
Found 1 runs
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/001.mgz
Checking for (invalid) multi-frame inputs...
Only one run found so motion
correction will not be performed. I'll
copy the run to rawavg and continue.

 cp /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/001.mgz /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/rawavg.mgz 


 mri_info /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/rawavg.mgz 

rawavg.mgz ========================================
Volume information for /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/rawavg.mgz
          type: MGH
    dimensions: 250 x 320 x 320
   voxel sizes: 0.799995, 0.800000, 0.800000
          type: FLOAT (3)
           fov: 256.000
           dof: 1
        xstart: -100.0, xend: 100.0
        ystart: -128.0, yend: 128.0
        zstart: -128.0, zend: 128.0
            TR: 0.00 msec, TE: 0.00 msec, TI: 0.00 msec, flip angle: 0.00 degrees
       nframes: 1
       PhEncDir: UNKNOWN
       FieldStrength: 0.000000
ras xform present
    xform info: x_r =   1.0000, y_r =   0.0000, z_r =  -0.0000, c_r =     0.4006
              : x_a =   0.0000, y_a =   1.0000, z_a =  -0.0000, c_a =    18.8170
              : x_s =   0.0000, y_s =   0.0000, z_s =   1.0000, c_s =    -6.4570

talairach xfm : 
Orientation   : RAS
Primary Slice Direction: axial

voxel to ras transform:
                0.8000   0.0000  -0.0000   -99.5989
                0.0000   0.8000  -0.0000  -109.1830
                0.0000   0.0000   0.8000  -134.4570
                0.0000   0.0000   0.0000     1.0000

voxel-to-ras determinant 0.511997

ras to voxel transform:
                1.2500   0.0000   0.0000   124.4993
                0.0000   1.2500   0.0000   136.4787
                0.0000   0.0000   1.2500   168.0712
                0.0000   0.0000   0.0000     1.0000
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563

 mri_convert /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/rawavg.mgz /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig.mgz --conform_min 

mri_convert /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/rawavg.mgz /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig.mgz --conform_min 
reading from /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/rawavg.mgz...
TR=0.00, TE=0.00, TI=0.00, flip angle=0.00
i_ras = (1, 0, 0)
j_ras = (0, 1, 0)
k_ras = (-0, -0, 1)
changing data type from float to uchar (noscale = 0)...
MRIchangeType: Building histogram -431.451 4780.11 1000, flo=0, fhi=0.999, dest_type=0
Reslicing using trilinear interpolation 
writing to /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig.mgz...

 mri_add_xform_to_header -c /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/talairach.xfm /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig.mgz /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig.mgz 

INFO: extension is mgz

 mri_info /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig.mgz 

orig.mgz ========================================
Volume information for /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig.mgz
          type: MGH
    dimensions: 320 x 320 x 320
   voxel sizes: 0.799995, 0.799995, 0.799995
          type: UCHAR (0)
           fov: 255.999
           dof: 1
        xstart: -128.0, xend: 128.0
        ystart: -128.0, yend: 128.0
        zstart: -128.0, zend: 128.0
            TR: 0.00 msec, TE: 0.00 msec, TI: 0.00 msec, flip angle: 0.00 degrees
       nframes: 1
       PhEncDir: UNKNOWN
       FieldStrength: 0.000000
ras xform present
    xform info: x_r =  -1.0000, y_r =   0.0000, z_r =   0.0000, c_r =     0.4006
              : x_a =   0.0000, y_a =   0.0000, z_a =   1.0000, c_a =    18.8170
              : x_s =   0.0000, y_s =  -1.0000, z_s =   0.0000, c_s =    -6.4570

talairach xfm : /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/talairach.xfm
Orientation   : LIA
Primary Slice Direction: coronal

voxel to ras transform:
               -0.8000   0.0000   0.0000   128.3998
                0.0000   0.0000   0.8000  -109.1823
                0.0000  -0.8000   0.0000   121.5423
                0.0000   0.0000   0.0000     1.0000

voxel-to-ras determinant -0.511991

ras to voxel transform:
               -1.2500  -0.0000  -0.0000   160.5007
               -0.0000  -0.0000  -1.2500   151.9287
               -0.0000   1.2500  -0.0000   136.4786
               -0.0000  -0.0000  -0.0000     1.0000
#--------------------------------------------
#@# Talairach Wed Sep 20 15:23:12 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri

 mri_nu_correct.mni --no-rescale --i orig.mgz --o orig_nu.mgz --ants-n4 --n 1 --proto-iters 1000 --distance 50 

/usr/bin/bc
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
/opt/freesurfer/bin/mri_nu_correct.mni
--no-rescale --i orig.mgz --o orig_nu.mgz --ants-n4 --n 1 --proto-iters 1000 --distance 50
nIters 1
mri_nu_correct.mni 7.3.2
Linux cn4271 4.18.0-425.19.2.el8_7.x86_64 #1 SMP Tue Apr 4 22:38:11 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
Wed Sep 20 15:23:12 EDT 2023
tmpdir is ./tmp.mri_nu_correct.mni.3786538
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
AntsN4BiasFieldCorrectionFs -i orig.mgz -o ./tmp.mri_nu_correct.mni.3786538/nu0.mgz --dtype uchar
AntsN4BiasFieldCorrectionFs done
mri_convert ./tmp.mri_nu_correct.mni.3786538/nu0.mgz orig_nu.mgz --like orig.mgz --conform
mri_convert ./tmp.mri_nu_correct.mni.3786538/nu0.mgz orig_nu.mgz --like orig.mgz --conform 
reading from ./tmp.mri_nu_correct.mni.3786538/nu0.mgz...
TR=0.00, TE=0.00, TI=0.00, flip angle=0.00
i_ras = (-1, 0, 0)
j_ras = (0, 0, -1)
k_ras = (0, 1, 0)
INFO: transform src into the like-volume: orig.mgz
writing to orig_nu.mgz...
 
 
Wed Sep 20 15:28:45 EDT 2023
mri_nu_correct.mni done

 talairach_avi --i orig_nu.mgz --xfm transforms/talairach.auto.xfm 

talairach_avi log file is transforms/talairach_avi.log...
mv -f /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/talsrcimg_to_711-2C_as_mni_average_305_t4_vox2vox.txt /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/talsrcimg_to_711-2C_as_mni_average_305_t4_vox2vox.txt
Started at Wed Sep 20 15:28:45 EDT 2023
Ended   at Wed Sep 20 15:29:07 EDT 2023
talairach_avi done

 cp transforms/talairach.auto.xfm transforms/talairach.xfm 

lta_convert --src orig.mgz --trg /opt/freesurfer/average/mni305.cor.mgz --inxfm transforms/talairach.xfm --outlta transforms/talairach.xfm.lta --subject fsaverage --ltavox2vox
7.3.2

--src: orig.mgz src image (geometry).
--trg: /opt/freesurfer/average/mni305.cor.mgz trg image (geometry).
--inmni: transforms/talairach.xfm input MNI/XFM transform.
--outlta: transforms/talairach.xfm.lta output LTA.
--s: fsaverage subject name
--ltavox2vox: output LTA as VOX_TO_VOX transform.
 LTA read, type : 1
 1.04356   0.02943  -0.00808  -0.73665;
-0.05483   1.00331   0.19394  -22.36795;
 0.00882  -0.15924   1.10014   0.39276;
 0.00000   0.00000   0.00000   1.00000;
setting subject to fsaverage
Writing  LTA to file transforms/talairach.xfm.lta...
lta_convert successful.
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri 
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri 
#--------------------------------------------
#@# Talairach Failure Detection Wed Sep 20 15:29:10 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri

 talairach_afd -T 0.005 -xfm transforms/talairach.xfm 

talairach_afd: Talairach Transform: transforms/talairach.xfm OK (p=0.7725, pval=0.6675 >= threshold=0.0050)

 awk -f /opt/freesurfer/bin/extract_talairach_avi_QA.awk /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/talairach_avi.log 


 tal_QC_AZS /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/talairach_avi.log 

TalAviQA: 0.96800
z-score: -2
#--------------------------------------------
#@# Nu Intensity Correction Wed Sep 20 15:29:10 EDT 2023

 mri_nu_correct.mni --i orig.mgz --o nu.mgz --uchar transforms/talairach.xfm --cm --n 2 --ants-n4 

/usr/bin/bc
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
/opt/freesurfer/bin/mri_nu_correct.mni
--i orig.mgz --o nu.mgz --uchar transforms/talairach.xfm --cm --n 2 --ants-n4
nIters 2
mri_nu_correct.mni 7.3.2
Linux cn4271 4.18.0-425.19.2.el8_7.x86_64 #1 SMP Tue Apr 4 22:38:11 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
Wed Sep 20 15:29:10 EDT 2023
tmpdir is ./tmp.mri_nu_correct.mni.3789918
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
AntsN4BiasFieldCorrectionFs -i orig.mgz -o ./tmp.mri_nu_correct.mni.3789918/nu0.mgz --dtype uchar
AntsN4BiasFieldCorrectionFs done
mri_binarize --i ./tmp.mri_nu_correct.mni.3789918/nu0.mgz --min -1 --o ./tmp.mri_nu_correct.mni.3789918/ones.mgz

7.3.2
cwd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
cmdline mri_binarize --i ./tmp.mri_nu_correct.mni.3789918/nu0.mgz --min -1 --o ./tmp.mri_nu_correct.mni.3789918/ones.mgz 
sysname  Linux
hostname cn4271
machine  x86_64
user     zugmana2

input      ./tmp.mri_nu_correct.mni.3789918/nu0.mgz
frame      0
nErode3d   0
nErode2d   0
output     ./tmp.mri_nu_correct.mni.3789918/ones.mgz
Binarizing based on threshold
min        -1
max        +infinity
binval        1
binvalnot     0
fstart = 0, fend = 0, nframes = 1
Starting parallel 1
Found 32768000 values in range
Counting number of voxels in first frame
Found 32767999 voxels in final mask
Writing output to ./tmp.mri_nu_correct.mni.3789918/ones.mgz
Count: 32767999 16776927.222384 32768000 99.999997
mri_binarize done
mri_segstats --id 1 --seg ./tmp.mri_nu_correct.mni.3789918/ones.mgz --i orig.mgz --sum ./tmp.mri_nu_correct.mni.3789918/sum.junk --avgwf ./tmp.mri_nu_correct.mni.3789918/input.mean.dat

7.3.2
cwd 
cmdline mri_segstats --id 1 --seg ./tmp.mri_nu_correct.mni.3789918/ones.mgz --i orig.mgz --sum ./tmp.mri_nu_correct.mni.3789918/sum.junk --avgwf ./tmp.mri_nu_correct.mni.3789918/input.mean.dat 
sysname  Linux
hostname cn4271
machine  x86_64
user     zugmana2
whitesurfname  white
UseRobust  0
Loading ./tmp.mri_nu_correct.mni.3789918/ones.mgz
Loading orig.mgz
Voxel Volume is 0.511991 mm^3
Generating list of segmentation ids
Found   1 segmentations
Computing statistics for each segmentation

Reporting on   1 segmentations
Using PrintSegStat
Computing spatial average of each frame

Writing to ./tmp.mri_nu_correct.mni.3789918/input.mean.dat
mri_segstats done
mri_segstats --id 1 --seg ./tmp.mri_nu_correct.mni.3789918/ones.mgz --i ./tmp.mri_nu_correct.mni.3789918/nu0.mgz --sum ./tmp.mri_nu_correct.mni.3789918/sum.junk --avgwf ./tmp.mri_nu_correct.mni.3789918/output.mean.dat

7.3.2
cwd 
cmdline mri_segstats --id 1 --seg ./tmp.mri_nu_correct.mni.3789918/ones.mgz --i ./tmp.mri_nu_correct.mni.3789918/nu0.mgz --sum ./tmp.mri_nu_correct.mni.3789918/sum.junk --avgwf ./tmp.mri_nu_correct.mni.3789918/output.mean.dat 
sysname  Linux
hostname cn4271
machine  x86_64
user     zugmana2
whitesurfname  white
UseRobust  0
Loading ./tmp.mri_nu_correct.mni.3789918/ones.mgz
Loading ./tmp.mri_nu_correct.mni.3789918/nu0.mgz
Voxel Volume is 0.511991 mm^3
Generating list of segmentation ids
Found   1 segmentations
Computing statistics for each segmentation

Reporting on   1 segmentations
Using PrintSegStat
Computing spatial average of each frame

Writing to ./tmp.mri_nu_correct.mni.3789918/output.mean.dat
mri_segstats done
mris_calc -o ./tmp.mri_nu_correct.mni.3789918/nu0.mgz ./tmp.mri_nu_correct.mni.3789918/nu0.mgz mul .64677256176071420662
Saving result to './tmp.mri_nu_correct.mni.3789918/nu0.mgz' (type = MGH )                       [ ok ]
mri_convert ./tmp.mri_nu_correct.mni.3789918/nu0.mgz nu.mgz --like orig.mgz
mri_convert ./tmp.mri_nu_correct.mni.3789918/nu0.mgz nu.mgz --like orig.mgz 
reading from ./tmp.mri_nu_correct.mni.3789918/nu0.mgz...
TR=0.00, TE=0.00, TI=0.00, flip angle=0.00
i_ras = (-1, 0, 0)
j_ras = (0, 0, -1)
k_ras = (0, 1, 0)
INFO: transform src into the like-volume: orig.mgz
writing to nu.mgz...
mri_make_uchar nu.mgz transforms/talairach.xfm nu.mgz
type change took 0 minutes and 9 seconds.
FIRST_PERCENTILE 0.010000
WM_PERCENTILE    0.900000
MAX_R 50.000000
i1 = 27, i2 = 69
#mri_make_uchar# mapping 45 115 to  3 110  :  b -66.525 m 1.535 : thresh 43.3388 maxsat 209.463 : nzero 8900576 nsat 0
 
 
Wed Sep 20 15:35:09 EDT 2023
mri_nu_correct.mni done

 mri_add_xform_to_header -c /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/talairach.xfm nu.mgz nu.mgz 

INFO: extension is mgz
#--------------------------------------------
#@# Intensity Normalization Wed Sep 20 15:35:11 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri

 mri_normalize -g 1 -seed 1234 -mprage -noconform nu.mgz T1.mgz 

using max gradient = 1.000
setting seed for random number genererator to 1234
assuming input volume is MGH (Van der Kouwe) MP-RAGE
not interpolating and embedding volume to be 256^3...
reading mri_src from nu.mgz...
normalizing image...
NOT doing gentle normalization with control points/label
talairach transform
 1.04356   0.02943  -0.00808  -0.73665;
-0.05483   1.00331   0.19394  -22.36795;
 0.00882  -0.15924   1.10014   0.39276;
 0.00000   0.00000   0.00000   1.00000;
processing without aseg, no1d=0
MRInormInit(): 
INFO: Modifying talairach volume c_(r,a,s) based on average_305
MRInormalize(): 
MRIsplineNormalize(): npeaks = 15
Starting OpenSpline(): npoints = 15
building Voronoi diagram...
performing soap bubble smoothing, sigma = 8...

Iterating 2 times
---------------------------------
3d normalization pass 1 of 2
white matter peak found at 110
white matter peak found at 110
gm peak at 70 (70), valley at 43 (43)
csf peak at 25, setting threshold to 55
building Voronoi diagram...
performing soap bubble smoothing, sigma = 8...
---------------------------------
3d normalization pass 2 of 2
white matter peak found at 110
white matter peak found at 110
gm peak at 65 (65), valley at 41 (41)
csf peak at 21, setting threshold to 50
building Voronoi diagram...
performing soap bubble smoothing, sigma = 8...
Done iterating ---------------------------------
writing output to T1.mgz
3D bias adjustment took 4 minutes and 42 seconds.

Started at Wed Sep 20 15:22:40 EDT 2023 
Ended   at Wed Sep 20 15:39:54 EDT 2023
#@#%# recon-all-run-time-hours 0.287
recon-all -s sub-24563 finished without error at Wed Sep 20 15:39:54 EDT 2023
done


Terminal - standard error
~~~~~~~~~~~~~~~~~~~~~~~~~


 


Environment
~~~~~~~~~~~


* AFNI_IMSAVE_WARNINGS : NO
* AFNI_PLUGINPATH : /opt/afni-latest
* ANTS_RANDOM_SEED : 3954
* APPTAINER_BINDPATH : /gs10,/gs11,/gs12,/gs8,/gs9,/vf,/spin1,/data,/fdb,/gpfs,/lscratch
* BASH_ENV : /usr/local/lmod/lmod/8.7/init/bash
* BASH_FUNC_i2proxyoff%% : () {  echo "[-] Disabling I2 web proxy ...";
 unset https_proxy
}
* BASH_FUNC_i2proxyon%% : () {  echo "[+] Enabling I2 web proxy ...";
 export https_proxy=http://dtn${I2HOSTNUM}-e0:${SQUID_PORT}
}
* BASH_FUNC_ml%% : () {  eval "$($LMOD_DIR/ml_cmd "$@")"
}
* BASH_FUNC_module%% : () {  local __lmod_my_status;
 local __lmod_sh_dbg;
 if [ -z "${LMOD_SH_DBG_ON+x}" ]; then
 case "$-" in 
 *v*x*)
 __lmod_sh_dbg='vx'
 ;;
 *v*)
 __lmod_sh_dbg='v'
 ;;
 *x*)
 __lmod_sh_dbg='x'
 ;;
 esac;
 fi;
 if [ -n "${__lmod_sh_dbg:-}" ]; then
 set +$__lmod_sh_dbg;
 echo "Shell debugging temporarily silenced: export LMOD_SH_DBG_ON=1 for Lmod's output" 1>&2;
 fi;
 eval "$($LMOD_CMD bash "$@")" && eval $(${LMOD_SETTARG_CMD:-:} -s sh);
 __lmod_my_status=$?;
 if [ -n "${__lmod_sh_dbg:-}" ]; then
 echo "Shell debugging restarted" 1>&2;
 set -$__lmod_sh_dbg;
 fi;
 return $__lmod_my_status
}
* BASH_FUNC_proxyoff%% : () {  echo "[-] Disabling web proxy ...";
 unset http_proxy;
 unset https_proxy;
 unset ftp_proxy;
 unset RSYNC_PROXY
}
* BASH_FUNC_proxyon%% : () {  echo "[+] Enabling web proxy ...";
 export http_proxy=http://dtn${HOSTNUM}-e0:${SQUID_PORT};
 export https_proxy=http://dtn${HOSTNUM}-e0:${SQUID_PORT};
 export ftp_proxy=http://dtn${HOSTNUM}-e0:${SQUID_PORT};
 export RSYNC_PROXY=dtn${HOSTNUM}-e0:${SQUID_PORT}
}
* BASH_FUNC_which%% : () {  ( alias;
 eval ${which_declare} ) | /usr/bin/which --tty-only --read-alias --read-functions --show-tilde --show-dot $@
}
* COBBLER_SERVER : 10.1.201.7
* COLORTERM : truecolor
* CPATH : /opt/conda/envs/fmriprep/include:
* DBUS_SESSION_BUS_ADDRESS : unix:abstract=/tmp/dbus-WZtSKKMrMB,guid=7b7a335263cd424c185763c66509beb4
* DEBIAN_FRONTEND : noninteractive
* DEBUGINFOD_URLS : https://debuginfod.centos.org/ 
* DESKTOP_SESSION : xfce
* DISPLAY : :11.0
* ENVIRONMENT : BATCH
* FIX_VERTEX_AREA : 
* FREESURFER_HOME : /opt/freesurfer
* FSF_OUTPUT_FORMAT : nii.gz
* FSLDIR : /opt/conda/envs/fmriprep
* FSLGECUDAQ : cuda.q
* FSLLOCKDIR : 
* FSLMACHINELIST : 
* FSLMULTIFILEQUIT : TRUE
* FSLOUTPUTTYPE : NIFTI_GZ
* FSLREMOTECALL : 
* FS_LICENSE : /data/EDB/TMSpilot/code/license.txt
* FS_OVERRIDE : 0
* FUNCTIONALS_DIR : /opt/freesurfer/sessions
* GLOBAL_ENV : set
* HISTFILE : /home/zugmana2/.bash_history_biowulf
* HISTFILESIZE : 1000
* HISTSIZE : 1000
* HISTTIMEFORMAT : %H:%M  
* HOME : /home/zugmana2
* HOSTNAME : cn4271
* HOSTNUM : 04
* I2HOSTNUM : 13
* IS_DOCKER_8395080871 : 1
* KMP_DUPLICATE_LIB_OK : True
* KMP_INIT_AT_FORK : FALSE
* LANG : C.UTF-8
* LC_ALL : C.UTF-8
* LD_LIBRARY_PATH : /opt/conda/envs/fmriprep/lib:/usr/lib/x86_64-linux-gnu:/opt/workbench/lib_linux64::/.singularity.d/libs
* LESSOPEN : ||/usr/bin/lesspipe.sh %s
* LMOD_CMD : /usr/local/lmod/lmod/8.7/libexec/lmod
* LMOD_DIR : /usr/local/lmod/lmod/8.7/libexec
* LMOD_FAMILY_SINGULARITY : singularity
* LMOD_FAMILY_SINGULARITY_VERSION : 3.10.5
* LMOD_PKG : /usr/local/lmod/lmod/8.7
* LMOD_ROOT : /usr/local/lmod/lmod
* LMOD_SETTARG_FULL_SUPPORT : no
* LMOD_VERSION : 8.7
* LMOD_sys : Linux
* LM_LICENSE_FILE : /usr/local/pgi/license.dat
* LOADEDMODULES : turbovnc:singularity/3.10.5
* LOCAL_DIR : /opt/freesurfer/local
* LOGNAME : zugmana2
* LS_COLORS : rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:cd=40;33;01:or=40;31;01:mi=00:su=37;41:sg=30;43:ca=30;41:tw=30;42:ow=34;42:st=37;44:ex=01;32:*.tar=01;31:*.tgz=01;31:*.arc=01;31:*.arj=01;31:*.taz=01;31:*.lha=01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.tlz=01;31:*.txz=01;31:*.tzo=01;31:*.t7z=01;31:*.zip=01;31:*.z=01;31:*.dz=01;31:*.gz=01;31:*.lrz=01;31:*.lz=01;31:*.lzo=01;31:*.xz=01;31:*.zst=01;31:*.tzst=01;31:*.bz2=01;31:*.bz=01;31:*.tbz=01;31:*.tbz2=01;31:*.tz=01;31:*.deb=01;31:*.rpm=01;31:*.jar=01;31:*.war=01;31:*.ear=01;31:*.sar=01;31:*.rar=01;31:*.alz=01;31:*.ace=01;31:*.zoo=01;31:*.cpio=01;31:*.7z=01;31:*.rz=01;31:*.cab=01;31:*.wim=01;31:*.swm=01;31:*.dwm=01;31:*.esd=01;31:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.tif=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fli=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=00;36:*.au=00;36:*.flac=00;36:*.m4a=00;36:*.mid=00;36:*.midi=00;36:*.mka=00;36:*.mp3=00;36:*.mpc=00;36:*.ogg=00;36:*.ra=00;36:*.wav=00;36:*.oga=00;36:*.opus=00;36:*.spx=00;36:*.xspf=00;36:
* MAIL : /var/spool/mail/zugmana2
* MAMBA_ROOT_PREFIX : /opt/conda
* MANPATH : /usr/local/current/singularity/3.10.5/share/man:/usr/local/slurm/share/man:/usr/local/lmod/lmod/8.7/share/man:/usr/local/current/turbovnc/share/man::
* MINC_BIN_DIR : /opt/freesurfer/mni/bin
* MINC_LIB_DIR : /opt/freesurfer/mni/lib
* MKL_NUM_THREADS : 1
* MNI_DATAPATH : /opt/freesurfer/mni/data
* MNI_DIR : /opt/freesurfer/mni
* MNI_PERL5LIB : /opt/freesurfer/mni/lib/perl5/5.8.5
* MODULEPATH : /usr/local/lmod/modulefiles
* MODULEPATH_ROOT : /usr/local/lmod/modulefiles
* MODULESHOME : /usr/local/lmod/lmod/8.7
* NIPYPE_NO_ET : 1
* NO_ET : 1
* OLDPWD : /data/EDB/TMSpilot
* OMP_NUM_THREADS : 1
* OS : Linux
* PANEL_GDK_CORE_DEVICE_EVENTS : 0
* PATH : /opt/conda/envs/fmriprep/bin:/opt/workbench/bin_linux64:/opt/afni-latest:/opt/freesurfer/bin:/opt/freesurfer/tktools:/opt/freesurfer/mni/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
* PERL5LIB : /opt/freesurfer/mni/lib/perl5/5.8.5
* PRINTER : unknown_printer
* PROMPT_COMMAND : PS1="Singularity> "; unset PROMPT_COMMAND
* PS1 : Singularity> 
* PVFSTAB_FILE : /usr/local/etc/pvfstab
* PWD : /vf/users/EDB/TMSpilot/code
* PYTHONNOUSERSITE : 1
* ROOTDIR : /data/EDB/TMSpilot
* RSYNC_PROXY : dtn04-e0:3128
* SELINUX_LEVEL_REQUESTED : 
* SELINUX_ROLE_REQUESTED : 
* SELINUX_USE_CURRENT_RANGE : 
* SESSION_MANAGER : local/unix:@/tmp/.ICE-unix/1941614,unix/unix:/tmp/.ICE-unix/1941614
* SHELL : /bin/bash
* SHLVL : 10
* SINGULARITY_BIND : /gs10,/gs11,/gs12,/gs8,/gs9,/vf,/spin1,/data,/fdb,/gpfs,/lscratch
* SINGULARITY_COMMAND : run
* SINGULARITY_CONTAINER : /data/EDB/TMSpilot/code/fmriprep_msmsulc.simg
* SINGULARITY_ENVIRONMENT : /.singularity.d/env/91-environment.sh
* SINGULARITY_NAME : fmriprep_msmsulc.simg
* SLURMD_NODENAME : cn4271
* SLURM_ARRAY_JOB_ID : 8535870
* SLURM_ARRAY_TASK_COUNT : 9
* SLURM_ARRAY_TASK_ID : 1
* SLURM_ARRAY_TASK_MAX : 8
* SLURM_ARRAY_TASK_MIN : 0
* SLURM_ARRAY_TASK_STEP : 1
* SLURM_CLUSTER_NAME : biowulf
* SLURM_CONF : /usr/local/slurm-21.08/slurm-21.08.8-2-patched2/etc/slurm.conf
* SLURM_CPUS_ON_NODE : 16
* SLURM_CPUS_PER_TASK : 16
* SLURM_GTIDS : 0
* SLURM_JOBID : 8536404
* SLURM_JOB_ACCOUNT : pined
* SLURM_JOB_CPUS_PER_NODE : 16
* SLURM_JOB_CPUS_PER_NODE_PACK_GROUP_0 : 32
* SLURM_JOB_GID : 39592
* SLURM_JOB_ID : 8536404
* SLURM_JOB_NAME : fmriprep23-1-3
* SLURM_JOB_NODELIST : cn4271
* SLURM_JOB_NUM_NODES : 1
* SLURM_JOB_PARTITION : norm
* SLURM_JOB_QOS : global
* SLURM_JOB_UID : 39592
* SLURM_JOB_USER : zugmana2
* SLURM_LOCALID : 0
* SLURM_MEM_PER_NODE : 40960
* SLURM_NNODES : 1
* SLURM_NODEID : 0
* SLURM_NODELIST : cn4271
* SLURM_NODE_ALIASES : (null)
* SLURM_PRIO_PROCESS : 0
* SLURM_PROCID : 0
* SLURM_SUBMIT_DIR : /vf/users/EDB/TMSpilot/code
* SLURM_SUBMIT_HOST : cn2882
* SLURM_TASKS_PER_NODE : 1
* SLURM_TASK_PID : 3230551
* SLURM_TOPOLOGY_ADDR : cn4271
* SLURM_TOPOLOGY_ADDR_PATTERN : node
* SLURM_WORKING_CLUSTER : biowulf:slurmctl:6802:9472:109
* SQUID_PORT : 3128
* SRUN_DEBUG : 3
* SSH_AGENT_PID : 1941656
* SSH_AUTH_SOCK : /tmp/ssh-VO2hYPWEBcYx/agent.1941655
* SSH_CLIENT : 165.112.206.151 51655 22
* SSH_CONNECTION : 165.112.206.151 51655 128.231.2.9 22
* SSH_TTY : /dev/pts/625
* STY : 542651.tun1
* SUBJECTS_DIR : /opt/freesurfer/subjects
* SWARM_PROC_ID : 0
* S_COLORS : auto
* TERM : xterm-256color
* TERMCAP : SC|screen.xterm-256color|VT 100/ANSI X3.64 virtual terminal:\
	:DO=\E[%dB:LE=\E[%dD:RI=\E[%dC:UP=\E[%dA:bs:bt=\E[Z:\
	:cd=\E[J:ce=\E[K:cl=\E[H\E[J:cm=\E[%i%d;%dH:ct=\E[3g:\
	:do=^J:nd=\E[C:pt:rc=\E8:rs=\Ec:sc=\E7:st=\EH:up=\EM:\
	:le=^H:bl=^G:cr=^M:it#8:ho=\E[H:nw=\EE:ta=^I:is=\E)0:\
	:li#24:co#80:am:xn:xv:LP:sr=\EM:al=\E[L:AL=\E[%dL:\
	:cs=\E[%i%d;%dr:dl=\E[M:DL=\E[%dM:dc=\E[P:DC=\E[%dP:\
	:im=\E[4h:ei=\E[4l:mi:IC=\E[%d@:ks=\E[?1h\E=:\
	:ke=\E[?1l\E>:vi=\E[?25l:ve=\E[34h\E[?25h:vs=\E[34l:\
	:ti=\E[?1049h:te=\E[?1049l:us=\E[4m:ue=\E[24m:so=\E[3m:\
	:se=\E[23m:mb=\E[5m:md=\E[1m:mh=\E[2m:mr=\E[7m:\
	:me=\E[m:ms:\
	:Co#8:pa#64:AF=\E[3%dm:AB=\E[4%dm:op=\E[39;49m:AX:\
	:vb=\Eg:G0:as=\E(0:ae=\E(B:\
	:ac=\140\140aaffggjjkkllmmnnooppqqrrssttuuvvwwxxyyzz{{||}}~~..--++,,hhII00:\
	:po=\E[5i:pf=\E[4i:Km=\E[M:k0=\E[10~:k1=\EOP:k2=\EOQ:\
	:k3=\EOR:k4=\EOS:k5=\E[15~:k6=\E[17~:k7=\E[18~:\
	:k8=\E[19~:k9=\E[20~:k;=\E[21~:F1=\E[23~:F2=\E[24~:\
	:F3=\E[1;2P:F4=\E[1;2Q:F5=\E[1;2R:F6=\E[1;2S:\
	:F7=\E[15;2~:F8=\E[17;2~:F9=\E[18;2~:FA=\E[19;2~:\
	:FB=\E[20;2~:FC=\E[21;2~:FD=\E[23;2~:FE=\E[24;2~:kb=:\
	:K2=\EOE:kB=\E[Z:kF=\E[1;2B:kR=\E[1;2A:*4=\E[3;2~:\
	:*7=\E[1;2F:#2=\E[1;2H:#3=\E[2;2~:#4=\E[1;2D:%c=\E[6;2~:\
	:%e=\E[5;2~:%i=\E[1;2C:kh=\E[1~:@1=\E[1~:kH=\E[4~:\
	:@7=\E[4~:kN=\E[6~:kP=\E[5~:kI=\E[2~:kD=\E[3~:ku=\EOA:\
	:kd=\EOB:kr=\EOC:kl=\EOD:km:
* TMPDIR : /lscratch/8536404
* USER : zugmana2
* USER_PATH : /usr/local/current/singularity/3.10.5/bin:/usr/local/slurm/bin:/usr/local/current/turbovnc/bin:/usr/local/bin:/usr/X11R6/bin:/usr/local/jdk/bin:/usr/bin:/usr/local/sbin:/usr/sbin:/usr/local/mysql/bin:/home/zugmana2/.local/bin:/home/zugmana2/bin:/bin:/usr/bin:/sbin:/usr/sbin:/usr/local/bin:/usr/local/sbin
* VGL_COMPRESS : 0
* VGL_PROBEGLX : 0
* VNCDESKTOP : TurboVNC: cn2882:11 (zugmana2)
* VTE_VERSION : 5204
* WINDOW : 0
* WINDOWID : 27262979
* XDG_CONFIG_DIRS : /etc/xdg
* XDG_CURRENT_DESKTOP : XFCE
* XDG_DATA_DIRS : /usr/local/share:/usr/share
* XDG_MENU_PREFIX : xfce-
* XDG_RUNTIME_DIR : /data/zugmana2/.xdgdir
* XDG_SESSION_ID : 4008
* _ : /usr/local/current/singularity/3.10.5/bin/singularity
* _LMFILES_ : /usr/local/lmod/modulefiles/turbovnc.lua:/usr/local/lmod/modulefiles/singularity/3.10.5.lua
* _ModuleTable001_ : X01vZHVsZVRhYmxlXyA9IHsKTVR2ZXJzaW9uID0gMywKY19yZWJ1aWxkVGltZSA9IDg2NDAwLApjX3Nob3J0VGltZSA9IGZhbHNlLApkZXB0aFQgPSB7fSwKZmFtaWx5ID0gewpzaW5ndWxhcml0eSA9ICJzaW5ndWxhcml0eSIsCn0sCm1UID0gewpzaW5ndWxhcml0eSA9IHsKZm4gPSAiL3Vzci9sb2NhbC9sbW9kL21vZHVsZWZpbGVzL3Npbmd1bGFyaXR5LzMuMTAuNS5sdWEiLApmdWxsTmFtZSA9ICJzaW5ndWxhcml0eS8zLjEwLjUiLApsb2FkT3JkZXIgPSAyLApwcm9wVCA9IHt9LApzdGFja0RlcHRoID0gMCwKc3RhdHVzID0gImFjdGl2ZSIsCnVzZXJOYW1lID0gInNpbmd1bGFyaXR5IiwKd1YgPSAiXjAwMDAwMDAzLjAwMDAwMDAxMC4wMDAwMDAwMDUuKnpmaW5hbCIsCn0s
* _ModuleTable002_ : CnR1cmJvdm5jID0gewpmbiA9ICIvdXNyL2xvY2FsL2xtb2QvbW9kdWxlZmlsZXMvdHVyYm92bmMubHVhIiwKZnVsbE5hbWUgPSAidHVyYm92bmMiLApsb2FkT3JkZXIgPSAxLApwcm9wVCA9IHt9LApzdGFja0RlcHRoID0gMCwKc3RhdHVzID0gImFjdGl2ZSIsCnVzZXJOYW1lID0gInR1cmJvdm5jIiwKd1YgPSAiTS4qemZpbmFsIiwKfSwKfSwKbXBhdGhBID0gewoiL3Vzci9sb2NhbC9sbW9kL21vZHVsZWZpbGVzIiwKfSwKc3lzdGVtQmFzZU1QQVRIID0gIi91c3IvbG9jYWwvbG1vZC9tb2R1bGVmaWxlcyIsCn0K
* _ModuleTable_Sz_ : 2
* __LMOD_REF_COUNT_MANPATH : /usr/local/current/singularity/3.10.5/share/man:1;/usr/local/slurm/share/man:3;/usr/local/lmod/lmod/8.7/share/man:1;/usr/local/current/turbovnc/share/man:1
* __LMOD_REF_COUNT_MODULEPATH : /usr/local/lmod/modulefiles:1
* __LMOD_REF_COUNT_PATH : /usr/local/current/singularity/3.10.5/bin:1;/usr/local/slurm/bin:3;/usr/local/current/turbovnc/bin:1;/usr/local/bin:2;/usr/X11R6/bin:1;/usr/local/jdk/bin:1;/usr/bin:1;/usr/local/sbin:1;/usr/sbin:1;/usr/local/mysql/bin:1;/home/zugmana2/.local/bin:1;/home/zugmana2/bin:1
* biowulf_FAMILY_SINGULARITY : singularity
* biowulf_FAMILY_SINGULARITY_VERSION : 3.10.5
* ftp_proxy : http://dtn04-e0:3128
* http_proxy : http://dtn04-e0:3128
* https_proxy : http://dtn04-e0:3128
* which_declare : declare -f

