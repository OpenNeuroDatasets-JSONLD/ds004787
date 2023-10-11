Node: single_subject_24563_wf (anat_preproc_wf (surface_recon_wf (autorecon_resume_wf (autorecon2_vol (freesurfer)
==================================================================================================================


 Hierarchy : fmriprep_23_2_wf.single_subject_24563_wf.anat_preproc_wf.surface_recon_wf.autorecon_resume_wf.autorecon2_vol
 Exec ID : autorecon2_vol


Original Inputs
---------------


* FLAIR_file : <undefined>
* T1_files : <undefined>
* T2_file : <undefined>
* args : <undefined>
* big_ventricles : <undefined>
* brainstem : <undefined>
* directive : autorecon2-volonly
* environ : {}
* expert : <undefined>
* flags : <undefined>
* hemi : <undefined>
* hippocampal_subfields_T1 : <undefined>
* hippocampal_subfields_T2 : <undefined>
* hires : <undefined>
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
* mris_inflate : <undefined>
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
* T1_files : <undefined>
* T2_file : <undefined>
* args : <undefined>
* big_ventricles : <undefined>
* brainstem : <undefined>
* directive : autorecon2-volonly
* environ : {}
* expert : <undefined>
* flags : <undefined>
* hemi : <undefined>
* hippocampal_subfields_T1 : <undefined>
* hippocampal_subfields_T2 : <undefined>
* hires : <undefined>
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
* mris_inflate : <undefined>
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
* T1 : <undefined>
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


* cmdline : recon-all -autorecon2-volonly -openmp 16 -subjid sub-24563 -sd /lscratch/8536404/24563.out/sourcedata/freesurfer -nogcareg
* duration : 7168.565366
* hostname : cn4271
* prev_wd : /vf/users/EDB/TMSpilot/code
* working_dir : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/autorecon_resume_wf/autorecon2_vol


Terminal output
~~~~~~~~~~~~~~~


 


Terminal - standard output
~~~~~~~~~~~~~~~~~~~~~~~~~~


 fs-check-version --s sub-24563 --o /lscratch/8536404/tmp.j5rLbD
Wed Sep 20 16:10:37 EDT 2023

setenv SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
cd /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/autorecon_resume_wf/autorecon2_vol
/opt/freesurfer/bin/fs-check-version --s sub-24563 --o /lscratch/8536404/tmp.j5rLbD
-rwxrwxr-x 1 root root 18565 Aug  4  2022 /opt/freesurfer/bin/fs-check-version

freesurfer-linux-ubuntu22_x86_64-7.3.2-20220804-6354275
$Id$
Linux cn4271 4.18.0-425.19.2.el8_7.x86_64 #1 SMP Tue Apr 4 22:38:11 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
pid 3814078
Current FS Version freesurfer-linux-ubuntu22_x86_64-7.3.2-20220804-6354275
bstampfile exists /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/scripts/build-stamp.txt
Subject FS Version: freesurfer-linux-ubuntu22_x86_64-7.3.2-20220804-6354275
No constraints on version because REQ=UnSet and FsVerFile=NotThere
#@#% fs-check-version match = 1
fs-check-version Done
INFO: SUBJECTS_DIR is /lscratch/8536404/24563.out/sourcedata/freesurfer
Actual FREESURFER_HOME /opt/freesurfer
-rw-rw-r-- 1 zugmana2 zugmana2 83100 Sep 20 16:10 /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/scripts/recon-all.log
Linux cn4271 4.18.0-425.19.2.el8_7.x86_64 #1 SMP Tue Apr 4 22:38:11 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563 
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563 
#--------------------------------------
#@# CA Normalize Wed Sep 20 16:10:37 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri

 mri_ca_normalize -c ctrl_pts.mgz -mask brainmask.mgz nu.mgz /opt/freesurfer/average/RB_all_2020-01-02.gca transforms/talairach.lta norm.mgz 

writing control point volume to ctrl_pts.mgz
using MR volume brainmask.mgz to mask input volume...
reading 1 input volume
reading atlas from '/opt/freesurfer/average/RB_all_2020-01-02.gca'...
reading transform from 'transforms/talairach.lta'...
reading input volume from nu.mgz...
resetting wm mean[0]: 98 --> 107
resetting gm mean[0]: 61 --> 61
input volume #1 is the most T1-like
using real data threshold=25.0
skull bounding box = (72, 66, 41) --> (244, 225, 246)
finding center of left hemi white matter
using (129, 119, 144) as brain centroid of Right_Cerebral_White_Matter...
mean wm in atlas = 107, using box (108,99,119) --> (150, 138,169) to find MRI wm
before smoothing, mri peak at 98
robust fit to distribution - 99 +- 4.8
after smoothing, mri peak at 99, scaling input intensities by 1.081
scaling channel 0 by 1.08081
using 246437 sample points...
INFO: compute sample coordinates transform
 0.81210  -0.03872  -0.03150   6.16665;
 0.04105   0.89806   0.14667  -37.92062;
 0.02526  -0.13865   0.81605   10.89387;
 0.00000   0.00000   0.00000   1.00000;
INFO: transform used
finding control points in Left_Cerebral_White_Matter....
found 40230 control points for structure...
bounding box (157, 71, 42) --> (242, 196, 243)
Left_Cerebral_White_Matter: limiting intensities to 93.0 --> 131.0
8 of 4265 (0.2%) samples deleted
finding control points in Right_Cerebral_White_Matter....
found 39478 control points for structure...
bounding box (80, 74, 42) --> (163, 201, 245)
Right_Cerebral_White_Matter: limiting intensities to 92.0 --> 132.0
1 of 4057 (0.0%) samples deleted
finding control points in Left_Cerebellum_White_Matter....
found 3105 control points for structure...
bounding box (162, 167, 73) --> (223, 217, 139)
Left_Cerebellum_White_Matter: limiting intensities to 120.0 --> 132.0
32 of 97 (33.0%) samples deleted
finding control points in Right_Cerebellum_White_Matter....
found 2710 control points for structure...
bounding box (108, 167, 72) --> (161, 218, 142)
Right_Cerebellum_White_Matter: limiting intensities to 116.0 --> 132.0
3 of 31 (9.7%) samples deleted
finding control points in Brain_Stem....
found 3475 control points for structure...
bounding box (141, 158, 118) --> (185, 234, 154)
Brain_Stem: limiting intensities to 118.0 --> 132.0
34 of 83 (41.0%) samples deleted
using 8533 total control points for intensity normalization...
bias field = 0.980 +- 0.069
125 of 8455 control points discarded
finding control points in Left_Cerebral_White_Matter....
found 40230 control points for structure...
bounding box (157, 71, 42) --> (242, 196, 243)
Left_Cerebral_White_Matter: limiting intensities to 88.0 --> 118.0
112 of 4861 (2.3%) samples deleted
finding control points in Right_Cerebral_White_Matter....
found 39478 control points for structure...
bounding box (80, 74, 42) --> (163, 201, 245)
Right_Cerebral_White_Matter: limiting intensities to 88.0 --> 124.0
38 of 4951 (0.8%) samples deleted
finding control points in Left_Cerebellum_White_Matter....
found 3105 control points for structure...
bounding box (162, 167, 73) --> (223, 217, 139)
Left_Cerebellum_White_Matter: limiting intensities to 88.0 --> 132.0
0 of 166 (0.0%) samples deleted
finding control points in Right_Cerebellum_White_Matter....
found 2710 control points for structure...
bounding box (108, 167, 72) --> (161, 218, 142)
Right_Cerebellum_White_Matter: limiting intensities to 88.0 --> 132.0
6 of 67 (9.0%) samples deleted
finding control points in Brain_Stem....
found 3475 control points for structure...
bounding box (141, 158, 118) --> (185, 234, 154)
Brain_Stem: limiting intensities to 88.0 --> 132.0
27 of 195 (13.8%) samples deleted
using 10240 total control points for intensity normalization...
bias field = 1.072 +- 0.079
29 of 9987 control points discarded
finding control points in Left_Cerebral_White_Matter....
found 40230 control points for structure...
bounding box (157, 71, 42) --> (242, 196, 243)
Left_Cerebral_White_Matter: limiting intensities to 88.0 --> 128.0
59 of 5117 (1.2%) samples deleted
finding control points in Right_Cerebral_White_Matter....
found 39478 control points for structure...
bounding box (80, 74, 42) --> (163, 201, 245)
Right_Cerebral_White_Matter: limiting intensities to 88.0 --> 119.0
67 of 5021 (1.3%) samples deleted
finding control points in Left_Cerebellum_White_Matter....
found 3105 control points for structure...
bounding box (162, 167, 73) --> (223, 217, 139)
Left_Cerebellum_White_Matter: limiting intensities to 88.0 --> 132.0
12 of 202 (5.9%) samples deleted
finding control points in Right_Cerebellum_White_Matter....
found 2710 control points for structure...
bounding box (108, 167, 72) --> (161, 218, 142)
Right_Cerebellum_White_Matter: limiting intensities to 88.0 --> 132.0
36 of 67 (53.7%) samples deleted
finding control points in Brain_Stem....
found 3475 control points for structure...
bounding box (141, 158, 118) --> (185, 234, 154)
Brain_Stem: limiting intensities to 88.0 --> 132.0
38 of 219 (17.4%) samples deleted
using 10626 total control points for intensity normalization...
bias field = 1.078 +- 0.077
25 of 10293 control points discarded
writing normalized volume to norm.mgz...
writing control points to ctrl_pts.mgz
freeing GCA...done.
normalization took 1 minutes and 32 seconds.
#--------------------------------------
#@# CA Reg Wed Sep 20 16:12:09 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri

 mri_ca_register -nobigventricles -T transforms/talairach.lta -align-after -mask brainmask.mgz norm.mgz /opt/freesurfer/average/RB_all_2020-01-02.gca transforms/talairach.m3z 

not handling expanded ventricles...
using previously computed transform transforms/talairach.lta
renormalizing sequences with structure alignment, equivalent to:
	-renormalize
	-regularize_mean 0.500
	-regularize 0.500
using MR volume brainmask.mgz to mask input volume...

== Number of threads available to mri_ca_register for OpenMP = 16 == 
reading 1 input volumes...
logging results to talairach.log
reading input volume 'norm.mgz'...
reading GCA '/opt/freesurfer/average/RB_all_2020-01-02.gca'...
label assignment complete, 0 changed (0.00%)
freeing gibbs priors...done.
average std[0] = 5.0
Starting GCAMregister()
label assignment complete, 0 changed (0.00%)
npasses = 1, nlevels = 6
#pass# 1 of 1 ************************
enabling zero nodes
setting smoothness cost coefficient to 0.156

#GCAMreg# pass 0 level1 5 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.16 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=256, sigma=2.0,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 1.10681
#FOTS# QuadFit found better minimum quadopt=(dt=326.21,rms=1.02102) vs oldopt=(dt=369.92,rms=1.0232)
#GCMRL#    0 dt 326.209517 rms  1.021  7.752% neg 0  invalid 762 tFOTS 5.9890 tGradient 3.6230 tsec 9.9990
#FOTS# QuadFit found better minimum quadopt=(dt=277.373,rms=0.99039) vs oldopt=(dt=369.92,rms=0.992592)
#GCMRL#    1 dt 277.373358 rms  0.990  3.000% neg 0  invalid 762 tFOTS 5.4960 tGradient 3.5800 tsec 9.5030
#FOTS# QuadFit found better minimum quadopt=(dt=234.56,rms=0.974594) vs oldopt=(dt=369.92,rms=0.977458)
#GCMRL#    2 dt 234.559771 rms  0.975  1.595% neg 0  invalid 762 tFOTS 6.0840 tGradient 3.5150 tsec 9.9790
#FOTS# QuadFit found better minimum quadopt=(dt=295.936,rms=0.965122) vs oldopt=(dt=369.92,rms=0.965472)
#GCMRL#    3 dt 295.936000 rms  0.965  0.972% neg 0  invalid 762 tFOTS 4.8830 tGradient 3.3150 tsec 8.7100
#FOTS# QuadFit found better minimum quadopt=(dt=177.349,rms=0.959079) vs oldopt=(dt=92.48,rms=0.960981)
#GCMRL#    4 dt 177.349398 rms  0.959  0.626% neg 0  invalid 762 tFOTS 7.3370 tGradient 3.4070 tsec 11.1950
#FOTS# QuadFit found better minimum quadopt=(dt=517.888,rms=0.952225) vs oldopt=(dt=369.92,rms=0.953471)
#GCMRL#    5 dt 517.888000 rms  0.952  0.715% neg 0  invalid 762 tFOTS 6.0300 tGradient 3.0420 tsec 9.5480
#FOTS# QuadFit found better minimum quadopt=(dt=129.472,rms=0.949594) vs oldopt=(dt=92.48,rms=0.950072)
#GCMRL#    6 dt 129.472000 rms  0.950  0.276% neg 0  invalid 762 tFOTS 6.1400 tGradient 3.3550 tsec 9.9780
#FOTS# QuadFit found better minimum quadopt=(dt=3551.23,rms=0.934246) vs oldopt=(dt=5918.72,rms=0.939051)
#GCMRL#    7 dt 3551.232000 rms  0.934  1.616% neg 0  invalid 762 tFOTS 5.3790 tGradient 2.7930 tsec 8.6510
#FOTS# QuadFit found better minimum quadopt=(dt=129.472,rms=0.932165) vs oldopt=(dt=92.48,rms=0.932503)
#GCMRL#    8 dt 129.472000 rms  0.932  0.000% neg 0  invalid 762 tFOTS 6.1040 tGradient 3.4310 tsec 10.1470
#GCMRL#    9 dt 129.472000 rms  0.932  0.052% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.7290 tsec 4.1920
#GCMRL#   10 dt 129.472000 rms  0.931  0.063% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.4850 tsec 4.0730
#GCMRL#   11 dt 129.472000 rms  0.931  0.055% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.5260 tsec 3.9340
#GCMRL#   12 dt 129.472000 rms  0.930  0.051% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0070 tsec 3.4110
#GCMRL#   13 dt 1479.680000 rms  0.928  0.205% neg 0  invalid 762 tFOTS 6.9560 tGradient 3.2580 tsec 10.6540
#FOTS# QuadFit found better minimum quadopt=(dt=129.472,rms=0.927069) vs oldopt=(dt=92.48,rms=0.927276)

#GCAMreg# pass 0 level1 5 level2 1 tsec 128.287 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.16 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=256, sigma=0.5,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.927576
#GCMRL#   15 dt   0.000000 rms  0.927  0.057% neg 0  invalid 762 tFOTS 6.8220 tGradient 3.6060 tsec 10.8910
setting smoothness cost coefficient to 0.615

#GCAMreg# pass 0 level1 4 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.62 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=64, sigma=2.0,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.93807
#FOTS# QuadFit found better minimum quadopt=(dt=98.7234,rms=0.933571) vs oldopt=(dt=103.68,rms=0.933599)
#GCMRL#   17 dt  98.723404 rms  0.934  0.480% neg 0  invalid 762 tFOTS 5.5270 tGradient 3.5150 tsec 9.5300
#GCMRL#   18 dt 414.720000 rms  0.922  1.230% neg 0  invalid 762 tFOTS 5.7960 tGradient 2.7690 tsec 9.0360
#FOTS# QuadFit found better minimum quadopt=(dt=98.2943,rms=0.917443) vs oldopt=(dt=103.68,rms=0.91746)
#GCMRL#   19 dt  98.294340 rms  0.917  0.503% neg 0  invalid 762 tFOTS 5.7060 tGradient 3.1300 tsec 9.2620
#FOTS# QuadFit found better minimum quadopt=(dt=124.416,rms=0.91474) vs oldopt=(dt=103.68,rms=0.91487)
#GCMRL#   20 dt 124.416000 rms  0.915  0.295% neg 0  invalid 762 tFOTS 8.7920 tGradient 2.8250 tsec 12.1130
#FOTS# QuadFit found better minimum quadopt=(dt=82.944,rms=0.913615) vs oldopt=(dt=103.68,rms=0.913699)
#GCMRL#   21 dt  82.944000 rms  0.914  0.000% neg 0  invalid 762 tFOTS 7.2700 tGradient 3.0910 tsec 10.9800
#GCMRL#   22 dt  82.944000 rms  0.913  0.096% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.2860 tsec 3.8760
#GCMRL#   23 dt  82.944000 rms  0.911  0.167% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.6180 tsec 3.0740
#GCMRL#   24 dt  82.944000 rms  0.909  0.239% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.2500 tsec 3.6780
#GCMRL#   25 dt  82.944000 rms  0.907  0.237% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.7020 tsec 3.4290
#GCMRL#   26 dt  82.944000 rms  0.904  0.281% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.1290 tsec 3.5920
#GCMRL#   27 dt  82.944000 rms  0.902  0.270% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.7420 tsec 3.1800
#GCMRL#   28 dt  82.944000 rms  0.900  0.245% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0040 tsec 3.5340
#GCMRL#   29 dt  82.944000 rms  0.898  0.210% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.7700 tsec 3.2180
#GCMRL#   30 dt  82.944000 rms  0.896  0.202% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.7600 tsec 3.2640
#GCMRL#   31 dt  82.944000 rms  0.895  0.164% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0950 tsec 3.7770
#GCMRL#   32 dt  82.944000 rms  0.893  0.141% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0180 tsec 3.5250
#GCMRL#   33 dt  82.944000 rms  0.892  0.109% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.5090 tsec 2.9160
#GCMRL#   34 dt  82.944000 rms  0.892  0.075% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0190 tsec 3.7320
#FOTS# QuadFit found better minimum quadopt=(dt=31.104,rms=0.891549) vs oldopt=(dt=25.92,rms=0.89155)
#GCMRL#   35 dt  31.104000 rms  0.892  0.000% neg 0  invalid 762 tFOTS 7.1090 tGradient 3.3340 tsec 11.0850

#GCAMreg# pass 0 level1 4 level2 1 tsec 115.084 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.62 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=64, sigma=0.5,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.891982
#GCMRL#   37 dt   0.000000 rms  0.892  0.048% neg 0  invalid 762 tFOTS 6.9740 tGradient 3.3300 tsec 10.7090
setting smoothness cost coefficient to 2.353

#GCAMreg# pass 0 level1 3 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=2.35 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=16, sigma=2.0,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.925858
#GCMRL#   39 dt   0.000000 rms  0.925  0.044% neg 0  invalid 762 tFOTS 6.6550 tGradient 2.9460 tsec 10.1730

#GCAMreg# pass 0 level1 3 level2 1 tsec 24.102 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=2.35 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=16, sigma=0.5,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.925858
#GCMRL#   41 dt   0.000000 rms  0.925  0.044% neg 0  invalid 762 tFOTS 6.1610 tGradient 2.7890 tsec 9.4950
setting smoothness cost coefficient to 8.000

#GCAMreg# pass 0 level1 2 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=8.00 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=4, sigma=2.0,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 1.02828
#FOTS# QuadFit found better minimum quadopt=(dt=2.84134,rms=0.994138) vs oldopt=(dt=2.88,rms=0.994147)
#GCMRL#   43 dt   2.841342 rms  0.994  3.320% neg 0  invalid 762 tFOTS 6.6960 tGradient 2.3420 tsec 9.6880
#FOTS# QuadFit found better minimum quadopt=(dt=2.21439,rms=0.987685) vs oldopt=(dt=2.88,rms=0.988285)
#GCMRL#   44 dt   2.214391 rms  0.988  0.649% neg 0  invalid 762 tFOTS 6.1280 tGradient 2.6190 tsec 9.2530
#FOTS# QuadFit found better minimum quadopt=(dt=1.52941,rms=0.986602) vs oldopt=(dt=0.72,rms=0.986859)
#GCMRL#   45 dt   1.529412 rms  0.987  0.000% neg 0  invalid 762 tFOTS 5.6540 tGradient 2.3420 tsec 8.5560

#GCAMreg# pass 0 level1 2 level2 1 tsec 34.464 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=8.00 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=4, sigma=0.5,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.987003
#GCMRL#   47 dt   0.000000 rms  0.987  0.041% neg 0  invalid 762 tFOTS 6.0380 tGradient 2.0500 tsec 8.5830
setting smoothness cost coefficient to 20.000

#GCAMreg# pass 0 level1 1 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=20.00 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=1, sigma=2.0,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 1.054
#FOTS# QuadFit found better minimum quadopt=(dt=0.448,rms=1.05184) vs oldopt=(dt=0.32,rms=1.05196)
#GCMRL#   49 dt   0.448000 rms  1.052  0.205% neg 0  invalid 762 tFOTS 7.7260 tGradient 2.0110 tsec 10.3080
#FOTS# QuadFit found better minimum quadopt=(dt=0.857914,rms=1.04502) vs oldopt=(dt=1.28,rms=1.04625)
#GCMRL#   50 dt   0.857914 rms  1.045  0.649% neg 0  invalid 762 tFOTS 7.1300 tGradient 1.9610 tsec 9.5790
#FOTS# QuadFit found better minimum quadopt=(dt=0.192,rms=1.04348) vs oldopt=(dt=0.32,rms=1.04391)
#GCMRL#   51 dt   0.192000 rms  1.043  0.000% neg 0  invalid 762 tFOTS 6.8590 tGradient 1.8490 tsec 9.1550
#GCMRL#   52 dt   0.192000 rms  1.043  0.059% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.9840 tsec 2.5380
#GCMRL#   53 dt   0.192000 rms  1.042  0.069% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.2710 tsec 2.7230
#GCMRL#   54 dt   0.192000 rms  1.040  0.185% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.7920 tsec 2.2370
#GCMRL#   55 dt   0.192000 rms  1.037  0.266% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.6630 tsec 2.1210
#GCMRL#   56 dt   0.192000 rms  1.036  0.184% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.9540 tsec 2.4540
#GCMRL#   57 dt   0.192000 rms  1.035  0.049% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.1130 tsec 2.6160
#GCMRL#   58 dt   0.192000 rms  1.035 -0.059% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.9110 tsec 2.8400
#FOTS# QuadFit found better minimum quadopt=(dt=0.112,rms=1.03493) vs oldopt=(dt=0.08,rms=1.03494)
#GCMRL#   59 dt   0.112000 rms  1.035  0.010% neg 0  invalid 762 tFOTS 7.5090 tGradient 2.5590 tsec 10.6540
#FOTS# QuadFit found better minimum quadopt=(dt=0.448,rms=1.03434) vs oldopt=(dt=0.32,rms=1.03445)
#GCMRL#   60 dt   0.448000 rms  1.034  0.057% neg 0  invalid 762 tFOTS 5.7510 tGradient 2.6000 tsec 8.8710
#GCMRL#   61 dt   1.280000 rms  1.031  0.293% neg 0  invalid 762 tFOTS 5.2500 tGradient 2.1280 tsec 7.8430
#FOTS# QuadFit found better minimum quadopt=(dt=0.112,rms=1.03105) vs oldopt=(dt=0.08,rms=1.03109)
#GCMRL#   62 dt   0.112000 rms  1.031  0.000% neg 0  invalid 762 tFOTS 7.6680 tGradient 2.1300 tsec 10.4220

#GCAMreg# pass 0 level1 1 level2 1 tsec 91.233 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=20.00 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=1, sigma=0.5,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 1.03144
#FOTS# QuadFit found better minimum quadopt=(dt=0.028,rms=1.03103) vs oldopt=(dt=0.02,rms=1.03104)
#GCMRL#   64 dt   0.028000 rms  1.031  0.039% neg 0  invalid 762 tFOTS 6.2130 tGradient 2.0190 tsec 8.9490
#FOTS# QuadFit found better minimum quadopt=(dt=0.024,rms=1.03103) vs oldopt=(dt=0.02,rms=1.03103)
resetting metric properties...
setting smoothness cost coefficient to 40.000

#GCAMreg# pass 0 level1 0 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=40.00 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=0, sigma=2.0,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.992086
#FOTS# QuadFit found better minimum quadopt=(dt=0.290842,rms=0.982764) vs oldopt=(dt=0.32,rms=0.982765)
#GCMRL#   66 dt   0.290842 rms  0.983  0.940% neg 0  invalid 762 tFOTS 6.2950 tGradient 1.5040 tsec 8.3950
#FOTS# QuadFit found better minimum quadopt=(dt=0.028,rms=0.982474) vs oldopt=(dt=0.02,rms=0.982489)
#GCMRL#   67 dt   0.028000 rms  0.982  0.000% neg 0  invalid 762 tFOTS 6.3560 tGradient 1.4190 tsec 8.5870

#GCAMreg# pass 0 level1 0 level2 1 tsec 23.823 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=40.00 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=0, sigma=0.5,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.982879
#FOTS# QuadFit found better minimum quadopt=(dt=0.007,rms=0.982464) vs oldopt=(dt=0.005,rms=0.982466)
#GCMRL#   69 dt   0.007000 rms  0.982  0.042% neg 0  invalid 762 tFOTS 5.8760 tGradient 1.3350 tsec 7.6560
#GCMRL#   70 dt   0.050000 rms  0.982  0.000% neg 0  invalid 762 tFOTS 5.7260 tGradient 1.2640 tsec 7.5840
GCAMregister done in 9.21467 min
Starting GCAmapRenormalizeWithAlignment() without scales
renormalizing by structure alignment....
renormalizing input #0
gca peak = 0.10253 (16)
mri peak = 0.09869 ( 6)
Left_Lateral_Ventricle (4): linear fit = 0.31 x + 0.0 (1594 voxels, overlap=0.123)
Left_Lateral_Ventricle (4): linear fit = 0.40 x + 0.0 (1594 voxels, peak =  5), gca=6.4
gca peak = 0.17690 (16)
mri peak = 0.08913 ( 6)
Right_Lateral_Ventricle (43): linear fit = 0.31 x + 0.0 (1350 voxels, overlap=0.042)
Right_Lateral_Ventricle (43): linear fit = 0.40 x + 0.0 (1350 voxels, peak =  5), gca=6.4
gca peak = 0.28275 (96)
mri peak = 0.05553 (99)
Right_Pallidum (52): linear fit = 1.04 x + 0.0 (2106 voxels, overlap=1.012)
Right_Pallidum (52): linear fit = 1.04 x + 0.0 (2106 voxels, peak = 100), gca=100.3
gca peak = 0.18948 (93)
mri peak = 0.05257 (89)
Left_Pallidum (13): linear fit = 0.93 x + 0.0 (1881 voxels, overlap=0.824)
Left_Pallidum (13): linear fit = 0.93 x + 0.0 (1881 voxels, peak = 86), gca=86.0
gca peak = 0.20755 (55)
mri peak = 0.08097 (67)
Right_Hippocampus (53): linear fit = 1.15 x + 0.0 (2156 voxels, overlap=0.373)
Right_Hippocampus (53): linear fit = 1.15 x + 0.0 (2156 voxels, peak = 64), gca=63.5
gca peak = 0.31831 (58)
mri peak = 0.08933 (66)
Left_Hippocampus (17): linear fit = 1.12 x + 0.0 (2201 voxels, overlap=0.978)
Left_Hippocampus (17): linear fit = 1.12 x + 0.0 (2201 voxels, peak = 65), gca=64.7
gca peak = 0.11957 (102)
mri peak = 0.07935 (98)
Right_Cerebral_White_Matter (41): linear fit = 0.98 x + 0.0 (151875 voxels, overlap=0.951)
Right_Cerebral_White_Matter (41): linear fit = 0.98 x + 0.0 (151875 voxels, peak = 99), gca=99.5
gca peak = 0.11429 (102)
mri peak = 0.07494 (100)
Left_Cerebral_White_Matter (2): linear fit = 0.99 x + 0.0 (154790 voxels, overlap=0.948)
Left_Cerebral_White_Matter (2): linear fit = 0.99 x + 0.0 (154790 voxels, peak = 100), gca=100.5
gca peak = 0.14521 (59)
mri peak = 0.02951 (64)
Left_Cerebral_Cortex (3): linear fit = 1.12 x + 0.0 (59478 voxels, overlap=0.150)
Left_Cerebral_Cortex (3): linear fit = 1.12 x + 0.0 (59478 voxels, peak = 66), gca=66.4
gca peak = 0.14336 (58)
mri peak = 0.02845 (61)
Right_Cerebral_Cortex (42): linear fit = 1.02 x + 0.0 (60677 voxels, overlap=0.771)
Right_Cerebral_Cortex (42): linear fit = 1.02 x + 0.0 (60677 voxels, peak = 59), gca=59.4
gca peak = 0.13305 (70)
mri peak = 0.11861 (68)
Right_Caudate (50): linear fit = 0.98 x + 0.0 (2345 voxels, overlap=0.948)
Right_Caudate (50): linear fit = 0.98 x + 0.0 (2345 voxels, peak = 68), gca=68.2
gca peak = 0.15761 (71)
mri peak = 0.08672 (69)
Left_Caudate (11): linear fit = 0.92 x + 0.0 (2421 voxels, overlap=0.436)
Left_Caudate (11): linear fit = 0.92 x + 0.0 (2421 voxels, peak = 65), gca=65.0
gca peak = 0.13537 (57)
mri peak = 0.03039 (64)
Left_Cerebellum_Cortex (8): linear fit = 1.12 x + 0.0 (40764 voxels, overlap=0.325)
Left_Cerebellum_Cortex (8): linear fit = 1.12 x + 0.0 (40764 voxels, peak = 64), gca=63.6
gca peak = 0.13487 (56)
mri peak = 0.02091 (71)
Right_Cerebellum_Cortex (47): linear fit = 1.26 x + 0.0 (39925 voxels, overlap=0.000)
Right_Cerebellum_Cortex (47): linear fit = 1.26 x + 0.0 (39925 voxels, peak = 71), gca=70.8
gca peak = 0.19040 (84)
mri peak = 0.07875 (89)
Left_Cerebellum_White_Matter (7): linear fit = 1.07 x + 0.0 (16950 voxels, overlap=0.542)
Left_Cerebellum_White_Matter (7): linear fit = 1.07 x + 0.0 (16950 voxels, peak = 89), gca=89.5
gca peak = 0.18871 (83)
mri peak = 0.04955 (88)
Right_Cerebellum_White_Matter (46): linear fit = 1.03 x + 0.0 (14290 voxels, overlap=0.826)
Right_Cerebellum_White_Matter (46): linear fit = 1.03 x + 0.0 (14290 voxels, peak = 86), gca=85.9
gca peak = 0.24248 (57)
mri peak = 0.07996 (68)
Left_Amygdala (18): linear fit = 1.17 x + 0.0 (1098 voxels, overlap=0.059)
Left_Amygdala (18): linear fit = 1.17 x + 0.0 (1098 voxels, peak = 67), gca=67.0
gca peak = 0.35833 (56)
mri peak = 0.10858 (68)
Right_Amygdala (54): linear fit = 1.21 x + 0.0 (1314 voxels, overlap=0.063)
Right_Amygdala (54): linear fit = 1.21 x + 0.0 (1314 voxels, peak = 67), gca=67.5
gca peak = 0.12897 (85)
mri peak = 0.05465 (100)
Left_Thalamus (10): linear fit = 1.13 x + 0.0 (12176 voxels, overlap=0.431)
Left_Thalamus (10): linear fit = 1.13 x + 0.0 (12176 voxels, peak = 96), gca=96.5
gca peak = 0.13127 (83)
mri peak = 0.04389 (95)
Right_Thalamus (49): linear fit = 1.15 x + 0.0 (9802 voxels, overlap=0.475)
Right_Thalamus (49): linear fit = 1.15 x + 0.0 (9802 voxels, peak = 96), gca=95.9
gca peak = 0.12974 (78)
mri peak = 0.06208 (81)
Left_Putamen (12): linear fit = 1.04 x + 0.0 (5251 voxels, overlap=1.000)
Left_Putamen (12): linear fit = 1.04 x + 0.0 (5251 voxels, peak = 82), gca=81.5
gca peak = 0.17796 (79)
mri peak = 0.04858 (74)
Right_Putamen (51): linear fit = 0.98 x + 0.0 (5401 voxels, overlap=1.000)
Right_Putamen (51): linear fit = 0.98 x + 0.0 (5401 voxels, peak = 77), gca=77.0
gca peak = 0.10999 (80)
mri peak = 0.07463 (90)
Brain_Stem (16): linear fit = 1.14 x + 0.0 (22612 voxels, overlap=0.416)
Brain_Stem (16): linear fit = 1.14 x + 0.0 (22612 voxels, peak = 92), gca=91.6
gca peak = 0.13215 (88)
mri peak = 0.08117 (103)
Right_VentralDC (60): linear fit = 1.17 x + 0.0 (2523 voxels, overlap=0.019)
Right_VentralDC (60): linear fit = 1.17 x + 0.0 (2523 voxels, peak = 103), gca=103.4
gca peak = 0.11941 (89)
mri peak = 0.07841 (100)
Left_VentralDC (28): linear fit = 1.18 x + 0.0 (3209 voxels, overlap=0.015)
Left_VentralDC (28): linear fit = 1.18 x + 0.0 (3209 voxels, peak = 105), gca=105.5
gca peak = 0.20775 (25)
uniform distribution in MR - rejecting arbitrary fit
gca peak = 0.13297 (21)
mri peak = 0.19049 ( 9)
Fourth_Ventricle (15): linear fit = 0.44 x + 0.0 (1554 voxels, overlap=0.016)
Fourth_Ventricle (15): linear fit = 0.44 x + 0.0 (1554 voxels, peak =  9), gca=9.1
gca peak Unknown = 0.94777 ( 0)
gca peak Left_Inf_Lat_Vent = 0.19087 (28)
gca peak Third_Ventricle = 0.20775 (25)
gca peak Fourth_Ventricle = 0.13297 (21)
gca peak CSF = 0.16821 (33)
gca peak Left_Accumbens_area = 0.32850 (63)
gca peak Left_undetermined = 0.98480 (28)
gca peak Left_vessel = 0.40887 (53)
gca peak Left_choroid_plexus = 0.10898 (46)
gca peak Right_Inf_Lat_Vent = 0.17798 (26)
gca peak Right_Accumbens_area = 0.30137 (64)
gca peak Right_vessel = 0.47828 (52)
gca peak Right_choroid_plexus = 0.11612 (45)
gca peak Fifth_Ventricle = 0.59466 (35)
gca peak WM_hypointensities = 0.10053 (78)
gca peak non_WM_hypointensities = 0.07253 (60)
gca peak Optic_Chiasm = 0.25330 (73)
not using caudate to estimate GM means
estimating mean gm scale to be 1.13 x + 0.0
estimating mean wm scale to be 0.98 x + 0.0
estimating mean csf scale to be 0.40 x + 0.0
Right_Pallidum too bright - rescaling by 0.967 (from 1.045) to 97.0 (was 100.3)
saving intensity scales to talairach.label_intensities.txt
GCAmapRenormalizeWithAlignment() took 4.6202 min
noneg pre
Starting GCAMregister()
label assignment complete, 0 changed (0.00%)
npasses = 1, nlevels = 6
#pass# 1 of 1 ************************
enabling zero nodes
setting smoothness cost coefficient to 0.008

#GCAMreg# pass 0 level1 5 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.01 
tol=5.00e-02, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=256, sigma=2.0,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.962823
#FOTS# QuadFit found better minimum quadopt=(dt=399.152,rms=0.92925) vs oldopt=(dt=369.92,rms=0.929377)
#GCMRL#   72 dt 399.152387 rms  0.929  3.487% neg 0  invalid 762 tFOTS 5.6760 tGradient 2.8570 tsec 8.9290
#FOTS# QuadFit found better minimum quadopt=(dt=295.936,rms=0.918351) vs oldopt=(dt=369.92,rms=0.918413)
#GCMRL#   73 dt 295.936000 rms  0.918  1.173% neg 0  invalid 762 tFOTS 5.0570 tGradient 2.4980 tsec 7.9880
#FOTS# QuadFit found better minimum quadopt=(dt=295.936,rms=0.912249) vs oldopt=(dt=369.92,rms=0.912461)
#GCMRL#   74 dt 295.936000 rms  0.912  0.664% neg 0  invalid 762 tFOTS 5.2850 tGradient 2.9460 tsec 8.6750
#FOTS# QuadFit found better minimum quadopt=(dt=129.472,rms=0.909385) vs oldopt=(dt=92.48,rms=0.909956)
#GCMRL#   75 dt 129.472000 rms  0.909  0.314% neg 0  invalid 762 tFOTS 5.5100 tGradient 3.0130 tsec 8.9290
#FOTS# QuadFit found better minimum quadopt=(dt=2071.55,rms=0.896115) vs oldopt=(dt=1479.68,rms=0.89715)
#GCMRL#   76 dt 2071.552000 rms  0.896  1.459% neg 0  invalid 762 tFOTS 4.8610 tGradient 2.4140 tsec 7.6840
#FOTS# QuadFit found better minimum quadopt=(dt=129.472,rms=0.89323) vs oldopt=(dt=92.48,rms=0.893542)
#GCMRL#   77 dt 129.472000 rms  0.893  0.322% neg 0  invalid 762 tFOTS 5.5050 tGradient 2.6490 tsec 8.5590
#FOTS# QuadFit found better minimum quadopt=(dt=517.888,rms=0.892395) vs oldopt=(dt=369.92,rms=0.892451)
#GCMRL#   78 dt 517.888000 rms  0.892  0.094% neg 0  invalid 762 tFOTS 4.9490 tGradient 2.3920 tsec 7.7500
#FOTS# QuadFit found better minimum quadopt=(dt=517.888,rms=0.890145) vs oldopt=(dt=369.92,rms=0.890437)
#GCMRL#   79 dt 517.888000 rms  0.890  0.252% neg 0  invalid 762 tFOTS 5.5810 tGradient 2.4780 tsec 8.4680
#FOTS# QuadFit found better minimum quadopt=(dt=129.472,rms=0.889506) vs oldopt=(dt=92.48,rms=0.889543)
#GCMRL#   80 dt 129.472000 rms  0.890  0.072% neg 0  invalid 762 tFOTS 5.2950 tGradient 2.7390 tsec 8.4230
#FOTS# QuadFit found better minimum quadopt=(dt=1183.74,rms=0.88854) vs oldopt=(dt=1479.68,rms=0.88863)
#GCMRL#   81 dt 1183.744000 rms  0.889  0.109% neg 0  invalid 762 tFOTS 5.4050 tGradient 2.5290 tsec 8.3270
#FOTS# QuadFit found better minimum quadopt=(dt=295.936,rms=0.886057) vs oldopt=(dt=369.92,rms=0.886118)
#GCMRL#   82 dt 295.936000 rms  0.886  0.279% neg 0  invalid 762 tFOTS 5.5830 tGradient 2.5360 tsec 8.5020
#FOTS# QuadFit found better minimum quadopt=(dt=129.472,rms=0.885656) vs oldopt=(dt=92.48,rms=0.885683)
#GCMRL#   83 dt 129.472000 rms  0.886  0.000% neg 0  invalid 762 tFOTS 5.3870 tGradient 2.6250 tsec 8.4310
#GCMRL#   84 dt 129.472000 rms  0.885  0.023% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.4360 tsec 2.7710
#GCMRL#   85 dt 129.472000 rms  0.885  0.048% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.4730 tsec 2.8080
#GCMRL#   86 dt 129.472000 rms  0.884  0.084% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.6090 tsec 2.9630
#GCMRL#   87 dt 129.472000 rms  0.883  0.115% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.4460 tsec 2.7960
#GCMRL#   88 dt 129.472000 rms  0.882  0.139% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.5530 tsec 2.9790
#GCMRL#   89 dt 129.472000 rms  0.881  0.152% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.7450 tsec 3.0710
#GCMRL#   90 dt 129.472000 rms  0.879  0.142% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.7440 tsec 3.0950
#GCMRL#   91 dt 129.472000 rms  0.878  0.133% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.8390 tsec 3.2280
#GCMRL#   92 dt 129.472000 rms  0.877  0.144% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.4770 tsec 2.8330
#GCMRL#   93 dt 129.472000 rms  0.876  0.159% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.8320 tsec 3.2050
#GCMRL#   94 dt 129.472000 rms  0.874  0.151% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.4610 tsec 2.7700
#GCMRL#   95 dt 129.472000 rms  0.873  0.158% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.2110 tsec 3.5740
#GCMRL#   96 dt 129.472000 rms  0.872  0.144% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.5950 tsec 3.0200
#GCMRL#   97 dt 129.472000 rms  0.870  0.160% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.7690 tsec 3.1380
#GCMRL#   98 dt 129.472000 rms  0.869  0.151% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.2700 tsec 3.6810
#GCMRL#   99 dt 129.472000 rms  0.868  0.142% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.7010 tsec 3.1590
#GCMRL#  100 dt 129.472000 rms  0.867  0.134% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.1710 tsec 3.5450
#GCMRL#  101 dt 129.472000 rms  0.866  0.121% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.9000 tsec 3.2340
#GCMRL#  102 dt 129.472000 rms  0.865  0.117% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.7890 tsec 3.1840
#GCMRL#  103 dt 129.472000 rms  0.863  0.118% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.7010 tsec 3.0700
#GCMRL#  104 dt 129.472000 rms  0.863  0.107% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.5550 tsec 2.9660
#GCMRL#  105 dt 129.472000 rms  0.862  0.107% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.8710 tsec 3.2000
#GCMRL#  106 dt 129.472000 rms  0.861  0.109% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.5210 tsec 2.8340
#GCMRL#  107 dt 129.472000 rms  0.860  0.114% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.8190 tsec 3.2110
#GCMRL#  108 dt 129.472000 rms  0.859  0.109% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.8560 tsec 3.2390
#GCMRL#  109 dt 129.472000 rms  0.858  0.111% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.5110 tsec 2.8740
#GCMRL#  110 dt 129.472000 rms  0.857  0.099% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.7320 tsec 3.1510
#GCMRL#  111 dt 129.472000 rms  0.856  0.087% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.7160 tsec 3.0830
#GCMRL#  112 dt 129.472000 rms  0.855  0.087% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.8560 tsec 3.2600
#GCMRL#  113 dt 129.472000 rms  0.855  0.091% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0510 tsec 3.4570
#GCMRL#  114 dt 129.472000 rms  0.854  0.088% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.9220 tsec 3.3240
#GCMRL#  115 dt 129.472000 rms  0.853  0.087% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.9280 tsec 3.3260
#GCMRL#  116 dt 129.472000 rms  0.853  0.076% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.8240 tsec 3.2000
#GCMRL#  117 dt 129.472000 rms  0.852  0.065% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.1620 tsec 3.5530
#GCMRL#  118 dt 129.472000 rms  0.852  0.055% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.7350 tsec 3.1230
#GCMRL#  119 dt 129.472000 rms  0.851  0.049% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.8060 tsec 3.1510
#GCMRL#  120 dt 129.472000 rms  0.851  0.047% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.1310 tsec 3.6710
#GCMRL#  121 dt 129.472000 rms  0.850  0.049% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.2520 tsec 3.6550
#GCMRL#  122 dt 129.472000 rms  0.850  0.053% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.5520 tsec 2.8900
#GCMRL#  123 dt 129.472000 rms  0.849  0.060% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0500 tsec 3.4360
#GCMRL#  124 dt 129.472000 rms  0.849  0.060% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.7840 tsec 3.1060
#GCMRL#  125 dt 129.472000 rms  0.848  0.061% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.5710 tsec 2.9460
#GCMRL#  126 dt 129.472000 rms  0.848  0.059% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.5480 tsec 2.9160
#GCMRL#  127 dt 129.472000 rms  0.847  0.053% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.5440 tsec 2.9490
#GCMRL#  128 dt 129.472000 rms  0.847  0.049% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.4940 tsec 2.9000
#GCMRL#  129 dt 129.472000 rms  0.847  0.040% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.8310 tsec 3.1610
#GCMRL#  130 dt 129.472000 rms  0.846  0.038% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.5670 tsec 2.9760
#GCMRL#  131 dt 129.472000 rms  0.846  0.035% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.4560 tsec 2.7870
#GCMRL#  132 dt 129.472000 rms  0.846  0.030% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.9300 tsec 3.2690
#GCMRL#  133 dt 129.472000 rms  0.845  0.037% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0900 tsec 3.4890
#GCMRL#  134 dt 129.472000 rms  0.845  0.041% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.3210 tsec 3.7380
#GCMRL#  135 dt 129.472000 rms  0.845  0.045% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.1040 tsec 3.5250
#GCMRL#  136 dt 129.472000 rms  0.844  0.045% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.6920 tsec 3.0360
#GCMRL#  137 dt 129.472000 rms  0.844  0.049% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.6080 tsec 2.9450
#GCMRL#  138 dt 129.472000 rms  0.844  0.042% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.5470 tsec 2.9220
#GCMRL#  139 dt 129.472000 rms  0.843  0.044% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.3190 tsec 3.7020
#GCMRL#  140 dt 129.472000 rms  0.843  0.043% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.4700 tsec 2.8300
#GCMRL#  141 dt 129.472000 rms  0.842  0.044% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.3810 tsec 3.7890
#GCMRL#  142 dt 129.472000 rms  0.842  0.049% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.7720 tsec 3.2350
#GCMRL#  143 dt 129.472000 rms  0.842  0.046% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0600 tsec 3.4500
#GCMRL#  144 dt 129.472000 rms  0.841  0.049% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.1560 tsec 3.5140
#GCMRL#  145 dt 129.472000 rms  0.841  0.050% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.2540 tsec 3.7280
#GCMRL#  146 dt 129.472000 rms  0.840  0.049% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.6310 tsec 3.0570
#GCMRL#  147 dt 129.472000 rms  0.840  0.052% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.7230 tsec 3.1690
#GCMRL#  148 dt 129.472000 rms  0.840  0.047% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.2950 tsec 3.6770
#GCMRL#  149 dt 129.472000 rms  0.839  0.046% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.6170 tsec 3.0170
#GCMRL#  150 dt 129.472000 rms  0.839  0.033% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.5450 tsec 4.0640
#GCMRL#  151 dt 129.472000 rms  0.839  0.034% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.9640 tsec 3.4910
#GCMRL#  152 dt 129.472000 rms  0.838  0.036% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.8600 tsec 3.3290
#GCMRL#  153 dt 129.472000 rms  0.838  0.040% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.8750 tsec 3.2280
#GCMRL#  154 dt 129.472000 rms  0.838  0.036% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.8150 tsec 3.2830
#GCMRL#  155 dt 129.472000 rms  0.837  0.033% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0290 tsec 3.5640
#GCMRL#  156 dt 129.472000 rms  0.837  0.039% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0930 tsec 3.5880
#GCMRL#  157 dt 129.472000 rms  0.837  0.044% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0830 tsec 3.5210
#GCMRL#  158 dt 129.472000 rms  0.836  0.039% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0780 tsec 3.5660
#GCMRL#  159 dt 129.472000 rms  0.836  0.040% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.8590 tsec 3.3420
#GCMRL#  160 dt 129.472000 rms  0.836  0.039% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.9830 tsec 3.5260
#GCMRL#  161 dt 129.472000 rms  0.835  0.039% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.9960 tsec 3.5520
#GCMRL#  162 dt 129.472000 rms  0.835  0.035% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.5020 tsec 3.9690
#GCMRL#  163 dt 129.472000 rms  0.835  0.031% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0410 tsec 3.4620
#GCMRL#  164 dt 129.472000 rms  0.835  0.030% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0600 tsec 3.5900
#GCMRL#  165 dt 129.472000 rms  0.834  0.031% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0190 tsec 3.5460
#GCMRL#  166 dt 129.472000 rms  0.834  0.029% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0260 tsec 3.5830
#GCMRL#  167 dt 129.472000 rms  0.834  0.032% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0240 tsec 3.5060
#GCMRL#  168 dt 129.472000 rms  0.834  0.029% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.3100 tsec 3.7410
#GCMRL#  169 dt 129.472000 rms  0.833  0.027% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.1350 tsec 3.6380
#GCMRL#  170 dt 129.472000 rms  0.833  0.035% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0380 tsec 3.4970
#GCMRL#  171 dt 129.472000 rms  0.833  0.033% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.0870 tsec 3.5500
#GCMRL#  172 dt 129.472000 rms  0.833  0.037% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.8770 tsec 3.3620
#GCMRL#  173 dt 129.472000 rms  0.832  0.036% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.5230 tsec 2.9500
#GCMRL#  174 dt 129.472000 rms  0.832  0.034% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.7140 tsec 3.1190
#GCMRL#  175 dt 129.472000 rms  0.832  0.033% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.3000 tsec 3.8260
#GCMRL#  176 dt 129.472000 rms  0.831  0.033% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.6260 tsec 4.0500
#GCMRL#  177 dt 129.472000 rms  0.831  0.032% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.2410 tsec 3.6880
#GCMRL#  178 dt 129.472000 rms  0.831  0.034% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.3120 tsec 3.9400
#GCMRL#  179 dt 129.472000 rms  0.831  0.027% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.5590 tsec 4.2050
#GCMRL#  180 dt 129.472000 rms  0.830  0.025% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.2450 tsec 3.7590
#GCMRL#  181 dt 129.472000 rms  0.830  0.018% neg 0  invalid 762 tFOTS 0.0000 tGradient 3.2610 tsec 3.6590
#FOTS# QuadFit found better minimum quadopt=(dt=517.888,rms=0.830183) vs oldopt=(dt=369.92,rms=0.83019)
#GCMRL#  182 dt 517.888000 rms  0.830  0.000% neg 0  invalid 762 tFOTS 6.0890 tGradient 2.9460 tsec 9.5730

#GCAMreg# pass 0 level1 5 level2 1 tsec 443.081 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.01 
tol=5.00e-02, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=256, sigma=0.5,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.830436
#GCMRL#  184 dt   0.000000 rms  0.830  0.031% neg 0  invalid 762 tFOTS 6.6530 tGradient 3.0260 tsec 10.1490
setting smoothness cost coefficient to 0.031

#GCAMreg# pass 0 level1 4 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.03 
tol=5.00e-02, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=64, sigma=2.0,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.834664
#FOTS# QuadFit found better minimum quadopt=(dt=580.608,rms=0.811055) vs oldopt=(dt=414.72,rms=0.815366)
#GCMRL#  186 dt 580.608000 rms  0.811  2.829% neg 0  invalid 762 tFOTS 5.5200 tGradient 2.5420 tsec 8.5590
#FOTS# QuadFit found better minimum quadopt=(dt=98.4373,rms=0.806704) vs oldopt=(dt=103.68,rms=0.806727)
#GCMRL#  187 dt  98.437346 rms  0.807  0.537% neg 0  invalid 762 tFOTS 5.7110 tGradient 2.3580 tsec 8.5070
#FOTS# QuadFit found better minimum quadopt=(dt=145.152,rms=0.803023) vs oldopt=(dt=103.68,rms=0.803393)
#GCMRL#  188 dt 145.152000 rms  0.803  0.456% neg 0  invalid 762 tFOTS 6.1530 tGradient 2.4060 tsec 9.0560
#FOTS# QuadFit found better minimum quadopt=(dt=90.7907,rms=0.800404) vs oldopt=(dt=103.68,rms=0.800454)
#GCMRL#  189 dt  90.790698 rms  0.800  0.326% neg 0  invalid 762 tFOTS 5.4640 tGradient 2.7820 tsec 8.7260
#FOTS# QuadFit found better minimum quadopt=(dt=145.152,rms=0.797254) vs oldopt=(dt=103.68,rms=0.797656)
#GCMRL#  190 dt 145.152000 rms  0.797  0.393% neg 0  invalid 762 tFOTS 5.2130 tGradient 2.6950 tsec 8.4100
#FOTS# QuadFit found better minimum quadopt=(dt=96.724,rms=0.794931) vs oldopt=(dt=103.68,rms=0.794953)
#GCMRL#  191 dt  96.723982 rms  0.795  0.291% neg 0  invalid 762 tFOTS 6.0780 tGradient 2.6320 tsec 9.1850
#FOTS# QuadFit found better minimum quadopt=(dt=145.152,rms=0.792375) vs oldopt=(dt=103.68,rms=0.792543)
#GCMRL#  192 dt 145.152000 rms  0.792  0.321% neg 0  invalid 762 tFOTS 6.1320 tGradient 2.8000 tsec 9.4100
#FOTS# QuadFit found better minimum quadopt=(dt=84.6693,rms=0.790189) vs oldopt=(dt=103.68,rms=0.790297)
#GCMRL#  193 dt  84.669261 rms  0.790  0.276% neg 0  invalid 762 tFOTS 6.4910 tGradient 2.5380 tsec 9.5340
#FOTS# QuadFit found better minimum quadopt=(dt=145.152,rms=0.787756) vs oldopt=(dt=103.68,rms=0.788117)
#GCMRL#  194 dt 145.152000 rms  0.788  0.308% neg 0  invalid 762 tFOTS 5.7070 tGradient 2.6670 tsec 8.9830
#GCMRL#  195 dt 103.680000 rms  0.786  0.240% neg 0  invalid 762 tFOTS 6.3230 tGradient 2.4980 tsec 9.3200
#FOTS# QuadFit found better minimum quadopt=(dt=124.416,rms=0.783743) vs oldopt=(dt=103.68,rms=0.783827)
#GCMRL#  196 dt 124.416000 rms  0.784  0.270% neg 0  invalid 762 tFOTS 6.2220 tGradient 2.6430 tsec 9.3730
#GCMRL#  197 dt 103.680000 rms  0.782  0.224% neg 0  invalid 762 tFOTS 5.4570 tGradient 2.3550 tsec 8.2300
#FOTS# QuadFit found better minimum quadopt=(dt=124.416,rms=0.780056) vs oldopt=(dt=103.68,rms=0.780124)
#GCMRL#  198 dt 124.416000 rms  0.780  0.247% neg 0  invalid 762 tFOTS 4.9920 tGradient 1.9720 tsec 7.3410
#GCMRL#  199 dt 103.680000 rms  0.778  0.203% neg 0  invalid 762 tFOTS 5.0330 tGradient 1.8970 tsec 7.3010
#FOTS# QuadFit found better minimum quadopt=(dt=124.416,rms=0.776886) vs oldopt=(dt=103.68,rms=0.776923)
#GCMRL#  200 dt 124.416000 rms  0.777  0.204% neg 0  invalid 762 tFOTS 4.3020 tGradient 1.8580 tsec 6.5420
#FOTS# QuadFit found better minimum quadopt=(dt=101.839,rms=0.775493) vs oldopt=(dt=103.68,rms=0.775496)
#GCMRL#  201 dt 101.839416 rms  0.775  0.179% neg 0  invalid 762 tFOTS 5.6240 tGradient 1.8880 tsec 8.0340
#FOTS# QuadFit found better minimum quadopt=(dt=124.416,rms=0.773991) vs oldopt=(dt=103.68,rms=0.774035)
#GCMRL#  202 dt 124.416000 rms  0.774  0.194% neg 0  invalid 762 tFOTS 5.4000 tGradient 2.3360 tsec 8.2660
#GCMRL#  203 dt 103.680000 rms  0.773  0.157% neg 0  invalid 762 tFOTS 5.3090 tGradient 2.1190 tsec 7.8670
#FOTS# QuadFit found better minimum quadopt=(dt=124.416,rms=0.771309) vs oldopt=(dt=103.68,rms=0.771336)
#GCMRL#  204 dt 124.416000 rms  0.771  0.189% neg 0  invalid 762 tFOTS 5.1710 tGradient 2.1290 tsec 7.6990
#FOTS# QuadFit found better minimum quadopt=(dt=79.4771,rms=0.770267) vs oldopt=(dt=103.68,rms=0.770351)
#GCMRL#  205 dt  79.477124 rms  0.770  0.135% neg 0  invalid 762 tFOTS 5.5120 tGradient 2.4700 tsec 8.4720
#FOTS# QuadFit found better minimum quadopt=(dt=36.288,rms=0.769699) vs oldopt=(dt=25.92,rms=0.769846)
#GCMRL#  206 dt  36.288000 rms  0.770  0.074% neg 0  invalid 762 tFOTS 4.7540 tGradient 2.0280 tsec 7.2120
#FOTS# QuadFit found better minimum quadopt=(dt=7.776,rms=0.769616) vs oldopt=(dt=6.48,rms=0.76963)
#GCMRL#  207 dt   7.776000 rms  0.770  0.000% neg 0  invalid 762 tFOTS 4.4580 tGradient 2.1020 tsec 7.0670

#GCAMreg# pass 0 level1 4 level2 1 tsec 193.158 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.03 
tol=5.00e-02, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=64, sigma=0.5,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.769887
#FOTS# QuadFit found better minimum quadopt=(dt=36.288,rms=0.768414) vs oldopt=(dt=25.92,rms=0.768648)
#GCMRL#  209 dt  36.288000 rms  0.768  0.191% neg 0  invalid 762 tFOTS 4.7890 tGradient 2.4670 tsec 7.8370
#FOTS# QuadFit found better minimum quadopt=(dt=36.288,rms=0.767967) vs oldopt=(dt=25.92,rms=0.768053)
#GCMRL#  210 dt  36.288000 rms  0.768  0.058% neg 0  invalid 762 tFOTS 5.9630 tGradient 2.3330 tsec 8.7690
#FOTS# QuadFit found better minimum quadopt=(dt=82.944,rms=0.767584) vs oldopt=(dt=103.68,rms=0.767611)
#GCMRL#  211 dt  82.944000 rms  0.768  0.000% neg 0  invalid 762 tFOTS 4.6480 tGradient 2.4480 tsec 7.5310
#GCMRL#  212 dt  82.944000 rms  0.767  0.083% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.1380 tsec 2.5090
#GCMRL#  213 dt  82.944000 rms  0.766  0.114% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.4100 tsec 2.7670
#GCMRL#  214 dt  82.944000 rms  0.765  0.104% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.2420 tsec 2.8540
#GCMRL#  215 dt  82.944000 rms  0.764  0.183% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.1830 tsec 2.5130
#GCMRL#  216 dt  20.736000 rms  0.764  0.024% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.3040 tsec 3.3390
#GCMRL#  217 dt  10.368000 rms  0.764  0.013% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.3030 tsec 3.0990
#FOTS# QuadFit found better minimum quadopt=(dt=2.268,rms=0.76356) vs oldopt=(dt=1.62,rms=0.763566)
#GCMRL#  218 dt   2.268000 rms  0.764  0.000% neg 0  invalid 762 tFOTS 3.5830 tGradient 2.1910 tsec 6.1880
#GCMRL#  219 dt   2.268000 rms  0.764  0.003% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.2070 tsec 2.5430
#GCMRL#  220 dt   0.567000 rms  0.764  0.001% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.1790 tsec 3.3770
setting smoothness cost coefficient to 0.118

#GCAMreg# pass 0 level1 3 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.12 
tol=5.00e-02, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=16, sigma=2.0,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.780996
#FOTS# QuadFit found better minimum quadopt=(dt=44.8,rms=0.760958) vs oldopt=(dt=32,rms=0.765211)
#GCMRL#  222 dt  44.800000 rms  0.761  2.566% neg 0  invalid 762 tFOTS 5.4320 tGradient 2.0570 tsec 7.9100
#FOTS# QuadFit found better minimum quadopt=(dt=44.8,rms=0.74524) vs oldopt=(dt=32,rms=0.749037)
#GCMRL#  223 dt  44.800000 rms  0.745  2.066% neg 0  invalid 762 tFOTS 5.5040 tGradient 2.0120 tsec 7.9550
#FOTS# QuadFit found better minimum quadopt=(dt=11.2,rms=0.742174) vs oldopt=(dt=8,rms=0.742957)
#GCMRL#  224 dt  11.200000 rms  0.742  0.411% neg 0  invalid 762 tFOTS 4.9460 tGradient 1.9180 tsec 7.3990
#FOTS# QuadFit found better minimum quadopt=(dt=11.2,rms=0.739625) vs oldopt=(dt=8,rms=0.74034)
#GCMRL#  225 dt  11.200000 rms  0.740  0.343% neg 0  invalid 762 tFOTS 5.0950 tGradient 2.2200 tsec 7.7130
#GCMRL#  226 dt   8.000000 rms  0.738  0.239% neg 0  invalid 762 tFOTS 4.9030 tGradient 1.9160 tsec 7.2670
#FOTS# QuadFit found better minimum quadopt=(dt=0.04375,rms=0.737852) vs oldopt=(dt=0.03125,rms=0.737855)
#GCMRL#  227 dt   0.043750 rms  0.738  0.000% neg 0  invalid 762 tFOTS 3.5000 tGradient 1.7650 tsec 5.7710
#GCMRL#  228 dt   0.043750 rms  0.738  0.001% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.0270 tsec 2.4160
#GCMRL#  229 dt   0.005469 rms  0.738  0.000% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.9760 tsec 3.4690
#GCMRL#  230 dt   0.000171 rms  0.738  0.000% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.8290 tsec 3.6170

#GCAMreg# pass 0 level1 3 level2 1 tsec 62.486 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.12 
tol=5.00e-02, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=16, sigma=0.5,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.738194
#GCMRL#  232 dt   0.000000 rms  0.738  0.048% neg 0  invalid 762 tFOTS 1.9540 tGradient 1.7150 tsec 4.0450
setting smoothness cost coefficient to 0.400

#GCAMreg# pass 0 level1 2 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.40 
tol=5.00e-02, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=4, sigma=2.0,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.791214
#FOTS# QuadFit found better minimum quadopt=(dt=4.032,rms=0.781569) vs oldopt=(dt=2.88,rms=0.784061)
#GCMRL#  234 dt   4.032000 rms  0.782  1.219% neg 0  invalid 762 tFOTS 5.3610 tGradient 1.6340 tsec 7.4740
#FOTS# QuadFit found better minimum quadopt=(dt=4.032,rms=0.773427) vs oldopt=(dt=2.88,rms=0.775674)
#GCMRL#  235 dt   4.032000 rms  0.773  1.042% neg 0  invalid 762 tFOTS 5.4640 tGradient 1.9400 tsec 7.8850
#GCMRL#  236 dt   2.880000 rms  0.769  0.625% neg 0  invalid 762 tFOTS 5.3770 tGradient 1.9560 tsec 7.8330
#GCMRL#  237 dt   0.720000 rms  0.768  0.141% neg 0  invalid 762 tFOTS 4.7370 tGradient 1.7060 tsec 6.8860
#FOTS# QuadFit found better minimum quadopt=(dt=0.063,rms=0.76742) vs oldopt=(dt=0.045,rms=0.767446)
#GCMRL#  238 dt   0.063000 rms  0.767  0.000% neg 0  invalid 762 tFOTS 3.7450 tGradient 1.7390 tsec 5.9860
#GCMRL#  239 dt   0.063000 rms  0.767  0.012% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.8980 tsec 2.2920
#GCMRL#  240 dt   0.007875 rms  0.767  0.002% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.7610 tsec 3.0740
#GCMRL#  241 dt   0.003938 rms  0.767  0.001% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.5040 tsec 2.3410
#FOTS# QuadFit found better minimum quadopt=(dt=0.003375,rms=0.767307) vs oldopt=(dt=0.0028125,rms=0.767307)

#GCAMreg# pass 0 level1 2 level2 1 tsec 51.868 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.40 
tol=5.00e-02, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=4, sigma=0.5,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.767641
#FOTS# QuadFit found better minimum quadopt=(dt=4.032,rms=0.763419) vs oldopt=(dt=2.88,rms=0.764432)
#GCMRL#  243 dt   4.032000 rms  0.763  0.550% neg 0  invalid 762 tFOTS 4.2450 tGradient 1.5360 tsec 6.1850
#FOTS# QuadFit found better minimum quadopt=(dt=1.008,rms=0.762559) vs oldopt=(dt=0.72,rms=0.762803)
#GCMRL#  244 dt   1.008000 rms  0.763  0.113% neg 0  invalid 762 tFOTS 3.7200 tGradient 1.6480 tsec 5.7630
#FOTS# QuadFit found better minimum quadopt=(dt=0.063,rms=0.762511) vs oldopt=(dt=0.045,rms=0.762526)
#GCMRL#  245 dt   0.063000 rms  0.763  0.000% neg 0  invalid 762 tFOTS 3.2750 tGradient 1.6280 tsec 5.3210
#GCMRL#  246 dt   0.031500 rms  0.762  0.004% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.5870 tsec 2.3810
#GCMRL#  247 dt   0.015750 rms  0.762  0.002% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.6490 tsec 2.4430
#GCMRL#  248 dt   0.007875 rms  0.762  0.001% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.6040 tsec 2.4450
#FOTS# QuadFit found better minimum quadopt=(dt=0.003375,rms=0.762464) vs oldopt=(dt=0.0028125,rms=0.762464)
setting smoothness cost coefficient to 1.000

#GCAMreg# pass 0 level1 1 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=1.00 
tol=5.00e-02, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=1, sigma=2.0,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.854739
#FOTS# QuadFit found better minimum quadopt=(dt=3.53418,rms=0.848551) vs oldopt=(dt=5.12,rms=0.849314)
#GCMRL#  250 dt   3.534177 rms  0.849  0.724% neg 0  invalid 762 tFOTS 5.3430 tGradient 1.7440 tsec 7.6050
#FOTS# QuadFit found better minimum quadopt=(dt=1.792,rms=0.844519) vs oldopt=(dt=1.28,rms=0.845611)
#GCMRL#  251 dt   1.792000 rms  0.845  0.475% neg 0  invalid 762 tFOTS 5.0280 tGradient 1.8070 tsec 7.2540
#GCMRL#  252 dt   5.120000 rms  0.839  0.674% neg 0  invalid 762 tFOTS 4.7610 tGradient 1.5880 tsec 6.7350
#FOTS# QuadFit found better minimum quadopt=(dt=1.792,rms=0.837691) vs oldopt=(dt=1.28,rms=0.838014)
#GCMRL#  253 dt   1.792000 rms  0.838  0.136% neg 0  invalid 762 tFOTS 4.6830 tGradient 1.4750 tsec 6.5570
#FOTS# QuadFit found better minimum quadopt=(dt=7.168,rms=0.832677) vs oldopt=(dt=5.12,rms=0.833988)
#GCMRL#  254 dt   7.168000 rms  0.833  0.599% neg 0  invalid 762 tFOTS 4.7070 tGradient 1.5160 tsec 6.6540
#FOTS# QuadFit found better minimum quadopt=(dt=6.144,rms=0.829606) vs oldopt=(dt=5.12,rms=0.830052)
#GCMRL#  255 dt   6.144000 rms  0.830  0.369% neg 0  invalid 762 tFOTS 4.6930 tGradient 1.5340 tsec 6.6140
#FOTS# QuadFit found better minimum quadopt=(dt=6.144,rms=0.827083) vs oldopt=(dt=5.12,rms=0.827328)
#GCMRL#  256 dt   6.144000 rms  0.827  0.304% neg 0  invalid 762 tFOTS 4.7180 tGradient 1.3890 tsec 6.5260
#FOTS# QuadFit found better minimum quadopt=(dt=5.632,rms=0.824512) vs oldopt=(dt=5.12,rms=0.8246)
#GCMRL#  257 dt   5.632000 rms  0.825  0.311% neg 0  invalid 762 tFOTS 5.5120 tGradient 1.4730 tsec 7.4660
#FOTS# QuadFit found better minimum quadopt=(dt=4.096,rms=0.823202) vs oldopt=(dt=5.12,rms=0.823283)
#GCMRL#  258 dt   4.096000 rms  0.823  0.159% neg 0  invalid 762 tFOTS 5.0700 tGradient 1.6940 tsec 7.2160
#GCMRL#  259 dt   5.120000 rms  0.820  0.329% neg 0  invalid 762 tFOTS 5.2230 tGradient 1.4060 tsec 7.1150
#FOTS# QuadFit found better minimum quadopt=(dt=1.792,rms=0.819844) vs oldopt=(dt=1.28,rms=0.81998)
#GCMRL#  260 dt   1.792000 rms  0.820  0.079% neg 0  invalid 762 tFOTS 5.1080 tGradient 1.6200 tsec 7.1830
#FOTS# QuadFit found better minimum quadopt=(dt=7.168,rms=0.81748) vs oldopt=(dt=5.12,rms=0.818104)
#GCMRL#  261 dt   7.168000 rms  0.817  0.288% neg 0  invalid 762 tFOTS 5.2480 tGradient 1.5040 tsec 7.2370
#FOTS# QuadFit found better minimum quadopt=(dt=7.168,rms=0.815604) vs oldopt=(dt=5.12,rms=0.815835)
#GCMRL#  262 dt   7.168000 rms  0.816  0.230% neg 0  invalid 762 tFOTS 5.3150 tGradient 1.6440 tsec 7.3820
#FOTS# QuadFit found better minimum quadopt=(dt=4.096,rms=0.814498) vs oldopt=(dt=5.12,rms=0.814684)
#GCMRL#  263 dt   4.096000 rms  0.814  0.136% neg 0  invalid 762 tFOTS 5.5230 tGradient 1.5750 tsec 7.5480
#FOTS# QuadFit found better minimum quadopt=(dt=7.168,rms=0.812534) vs oldopt=(dt=5.12,rms=0.812652)
#GCMRL#  264 dt   7.168000 rms  0.813  0.241% neg 0  invalid 762 tFOTS 4.9260 tGradient 1.4770 tsec 6.8150
#FOTS# QuadFit found better minimum quadopt=(dt=1.792,rms=0.811784) vs oldopt=(dt=1.28,rms=0.811907)
#GCMRL#  265 dt   1.792000 rms  0.812  0.092% neg 0  invalid 762 tFOTS 5.4650 tGradient 1.6450 tsec 7.5560
#GCMRL#  266 dt   5.120000 rms  0.811  0.081% neg 0  invalid 762 tFOTS 5.3640 tGradient 1.5210 tsec 7.4010
#GCMRL#  267 dt   5.120000 rms  0.810  0.152% neg 0  invalid 762 tFOTS 5.4840 tGradient 1.9710 tsec 7.9140
#FOTS# QuadFit found better minimum quadopt=(dt=1.792,rms=0.809364) vs oldopt=(dt=1.28,rms=0.809465)
#GCMRL#  268 dt   1.792000 rms  0.809  0.065% neg 0  invalid 762 tFOTS 5.2540 tGradient 1.6240 tsec 7.3050
#FOTS# QuadFit found better minimum quadopt=(dt=7.168,rms=0.808278) vs oldopt=(dt=5.12,rms=0.808521)
#GCMRL#  269 dt   7.168000 rms  0.808  0.134% neg 0  invalid 762 tFOTS 4.9990 tGradient 1.8100 tsec 7.1840
#GCMRL#  270 dt   5.120000 rms  0.807  0.101% neg 0  invalid 762 tFOTS 5.1260 tGradient 1.5440 tsec 7.0830
#FOTS# QuadFit found better minimum quadopt=(dt=1.792,rms=0.806978) vs oldopt=(dt=1.28,rms=0.807076)
#GCMRL#  271 dt   1.792000 rms  0.807  0.060% neg 0  invalid 762 tFOTS 5.6700 tGradient 1.5920 tsec 7.7310
#FOTS# QuadFit found better minimum quadopt=(dt=7.168,rms=0.805995) vs oldopt=(dt=5.12,rms=0.806232)
#GCMRL#  272 dt   7.168000 rms  0.806  0.122% neg 0  invalid 762 tFOTS 6.1140 tGradient 1.8780 tsec 8.4800
#GCMRL#  273 dt   5.120000 rms  0.805  0.077% neg 0  invalid 762 tFOTS 5.3060 tGradient 1.6050 tsec 7.3060
#FOTS# QuadFit found better minimum quadopt=(dt=4.096,rms=0.804772) vs oldopt=(dt=5.12,rms=0.804839)
#GCMRL#  274 dt   4.096000 rms  0.805  0.074% neg 0  invalid 762 tFOTS 4.9750 tGradient 1.5100 tsec 6.9180
#GCMRL#  275 dt   5.120000 rms  0.804  0.093% neg 0  invalid 762 tFOTS 5.8200 tGradient 1.5790 tsec 7.8750
#FOTS# QuadFit found better minimum quadopt=(dt=1.792,rms=0.80359) vs oldopt=(dt=1.28,rms=0.803679)
#GCMRL#  276 dt   1.792000 rms  0.804  0.054% neg 0  invalid 762 tFOTS 5.5720 tGradient 1.7670 tsec 7.7960
#FOTS# QuadFit found better minimum quadopt=(dt=7.168,rms=0.802765) vs oldopt=(dt=5.12,rms=0.802951)
#GCMRL#  277 dt   7.168000 rms  0.803  0.103% neg 0  invalid 762 tFOTS 5.1050 tGradient 1.6250 tsec 7.1540
#GCMRL#  278 dt   5.120000 rms  0.802  0.074% neg 0  invalid 762 tFOTS 5.6040 tGradient 1.4610 tsec 7.5580
#FOTS# QuadFit found better minimum quadopt=(dt=3.072,rms=0.801688) vs oldopt=(dt=5.12,rms=0.80177)
#GCMRL#  279 dt   3.072000 rms  0.802  0.060% neg 0  invalid 762 tFOTS 5.3170 tGradient 1.5920 tsec 7.4090
#FOTS# QuadFit found better minimum quadopt=(dt=7.168,rms=0.800811) vs oldopt=(dt=5.12,rms=0.800985)
#GCMRL#  280 dt   7.168000 rms  0.801  0.109% neg 0  invalid 762 tFOTS 5.4020 tGradient 1.7190 tsec 7.6410
#FOTS# QuadFit found better minimum quadopt=(dt=1.792,rms=0.800548) vs oldopt=(dt=1.28,rms=0.800598)
#GCMRL#  281 dt   1.792000 rms  0.801  0.000% neg 0  invalid 762 tFOTS 5.5120 tGradient 1.5520 tsec 7.5770
#GCMRL#  282 dt   1.792000 rms  0.800  0.026% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.7260 tsec 2.0980
#GCMRL#  283 dt   1.792000 rms  0.800  0.042% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.7140 tsec 2.1210
#GCMRL#  284 dt   1.792000 rms  0.799  0.068% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.7160 tsec 2.1290
#GCMRL#  285 dt   1.792000 rms  0.799  0.089% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.7450 tsec 2.1090
#GCMRL#  286 dt   1.792000 rms  0.798  0.094% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.6190 tsec 2.0510
#GCMRL#  287 dt   1.792000 rms  0.797  0.100% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.5110 tsec 1.9190
#GCMRL#  288 dt   1.792000 rms  0.796  0.098% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.5380 tsec 1.9190
#GCMRL#  289 dt   1.792000 rms  0.796  0.094% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.4930 tsec 1.8800
#GCMRL#  290 dt   1.792000 rms  0.795  0.084% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.4410 tsec 1.8310
#GCMRL#  291 dt   1.792000 rms  0.794  0.078% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.4410 tsec 1.8360
#GCMRL#  292 dt   1.792000 rms  0.794  0.068% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.4430 tsec 1.8170
#GCMRL#  293 dt   1.792000 rms  0.793  0.060% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.5210 tsec 1.9290
#GCMRL#  294 dt   1.792000 rms  0.793  0.057% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.4400 tsec 1.8690
#GCMRL#  295 dt   1.792000 rms  0.792  0.052% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.7040 tsec 2.1910
#GCMRL#  296 dt   1.792000 rms  0.792  0.058% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.5190 tsec 1.9060
#GCMRL#  297 dt   1.792000 rms  0.792  0.062% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.6370 tsec 2.0370
#GCMRL#  298 dt   1.792000 rms  0.791  0.060% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.4990 tsec 1.8700
#GCMRL#  299 dt   1.792000 rms  0.791  0.061% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.7590 tsec 2.2130
#GCMRL#  300 dt   1.792000 rms  0.790  0.056% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.6580 tsec 2.0950
#GCMRL#  301 dt   1.792000 rms  0.790  0.043% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.7040 tsec 2.0770
#GCMRL#  302 dt   1.792000 rms  0.790  0.031% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.6140 tsec 1.9730
#GCMRL#  303 dt   1.792000 rms  0.789  0.030% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.4810 tsec 1.8220
#GCMRL#  304 dt   1.792000 rms  0.789  0.028% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.3860 tsec 1.7390
#GCMRL#  305 dt   1.792000 rms  0.789  0.028% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.4150 tsec 1.7810
#GCMRL#  306 dt   1.792000 rms  0.789  0.032% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.3950 tsec 1.7680
#GCMRL#  307 dt   1.792000 rms  0.788  0.030% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.3960 tsec 1.7540
#GCMRL#  308 dt   1.792000 rms  0.788  0.031% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.3770 tsec 1.7500
#GCMRL#  309 dt   1.792000 rms  0.788  0.032% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.6000 tsec 1.9730
#GCMRL#  310 dt   1.792000 rms  0.788  0.025% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.3270 tsec 1.6470
#GCMRL#  311 dt   1.792000 rms  0.788  0.027% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.3630 tsec 1.6780
#GCMRL#  312 dt   1.792000 rms  0.787  0.024% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.3960 tsec 1.7320
#GCMRL#  313 dt   1.792000 rms  0.787  0.019% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.4130 tsec 1.8190
#FOTS# QuadFit found better minimum quadopt=(dt=0.00175,rms=0.787168) vs oldopt=(dt=0.00125,rms=0.787168)

#GCAMreg# pass 0 level1 1 level2 1 tsec 305.062 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=1.00 
tol=5.00e-02, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=1, sigma=0.5,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.787441
#GCMRL#  315 dt   0.000000 rms  0.787  0.035% neg 0  invalid 762 tFOTS 3.9430 tGradient 1.3420 tsec 5.6390
resetting metric properties...
setting smoothness cost coefficient to 2.000

#GCAMreg# pass 0 level1 0 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=2.00 
tol=5.00e-02, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=0, sigma=2.0,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.765747
#FOTS# QuadFit found better minimum quadopt=(dt=0.448,rms=0.738711) vs oldopt=(dt=0.32,rms=0.746167)
#GCMRL#  317 dt   0.448000 rms  0.739  3.531% neg 0  invalid 762 tFOTS 4.3580 tGradient 0.9980 tsec 5.7380
#GCMRL#  318 dt   1.280000 rms  0.706  4.379% neg 0  invalid 762 tFOTS 4.8250 tGradient 0.9850 tsec 6.2420
#GCMRL#  319 dt   0.050000 rms  0.706  0.000% neg 0  invalid 762 tFOTS 4.1760 tGradient 0.8590 tsec 5.4570

#GCAMreg# pass 0 level1 0 level2 1 tsec 22.743 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=2.00 
tol=5.00e-02, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=0, sigma=0.5,type=2, relabel=0, neg=no

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.706676
#GCMRL#  321 dt   0.320000 rms  0.706  0.123% neg 0  invalid 762 tFOTS 4.4780 tGradient 0.8770 tsec 5.7990
#FOTS# QuadFit found better minimum quadopt=(dt=0.448,rms=0.705642) vs oldopt=(dt=0.32,rms=0.705658)
#GCMRL#  322 dt   0.448000 rms  0.706  0.000% neg 0  invalid 762 tFOTS 4.0670 tGradient 0.9380 tsec 5.3780
#GCMRL#  323 dt   0.448000 rms  0.705  0.088% neg 0  invalid 762 tFOTS 0.0000 tGradient 0.8380 tsec 1.1620
#GCMRL#  324 dt   0.448000 rms  0.704  0.150% neg 0  invalid 762 tFOTS 0.0000 tGradient 0.8920 tsec 1.2820
#GCMRL#  325 dt   0.448000 rms  0.703  0.188% neg 0  invalid 762 tFOTS 0.0000 tGradient 0.8830 tsec 1.2970
#GCMRL#  326 dt   0.448000 rms  0.701  0.214% neg 0  invalid 762 tFOTS 0.0000 tGradient 0.8930 tsec 1.3120
#GCMRL#  327 dt   0.448000 rms  0.699  0.247% neg 0  invalid 762 tFOTS 0.0000 tGradient 0.8800 tsec 1.2760
#GCMRL#  328 dt   0.448000 rms  0.697  0.276% neg 0  invalid 762 tFOTS 0.0000 tGradient 0.9040 tsec 1.3110
#GCMRL#  329 dt   0.448000 rms  0.696  0.255% neg 0  invalid 762 tFOTS 0.0000 tGradient 0.8820 tsec 1.2790
#GCMRL#  330 dt   0.448000 rms  0.695  0.167% neg 0  invalid 762 tFOTS 0.0000 tGradient 0.8450 tsec 1.2370
#GCMRL#  331 dt   0.448000 rms  0.694  0.054% neg 0  invalid 762 tFOTS 0.0000 tGradient 0.8810 tsec 1.3160
#GCMRL#  332 dt   0.448000 rms  0.694 -0.030% neg 0  invalid 762 tFOTS 0.0000 tGradient 0.9100 tsec 1.5840
GCAMregister done in 20.8086 min
********************* ALLOWING NEGATIVE NODES IN DEFORMATION********************************
noneg post
Starting GCAMregister()
label assignment complete, 0 changed (0.00%)
npasses = 1, nlevels = 6
#pass# 1 of 1 ************************
enabling zero nodes
setting smoothness cost coefficient to 0.008

#GCAMreg# pass 0 level1 5 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.01 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=256, sigma=2.0,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.689659
#FOTS# QuadFit found better minimum quadopt=(dt=32.368,rms=0.68916) vs oldopt=(dt=23.12,rms=0.689183)
#GCMRL#  334 dt  32.368000 rms  0.689  0.072% neg 0  invalid 762 tFOTS 6.0900 tGradient 2.6210 tsec 9.1520
#GCMRL#  335 dt  23.120000 rms  0.689  0.000% neg 0  invalid 762 tFOTS 6.3520 tGradient 2.6400 tsec 9.4370
#GCMRL#  336 dt  23.120000 rms  0.689  0.001% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.3320 tsec 2.6870

#GCAMreg# pass 0 level1 5 level2 1 tsec 27.856 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.01 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=256, sigma=0.5,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.689436
#GCMRL#  338 dt   0.000000 rms  0.689  0.046% neg 0  invalid 762 tFOTS 5.8750 tGradient 2.7580 tsec 9.0540
setting smoothness cost coefficient to 0.031

#GCAMreg# pass 0 level1 4 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.03 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=64, sigma=2.0,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.689493
#FOTS# QuadFit found better minimum quadopt=(dt=76.973,rms=0.686535) vs oldopt=(dt=25.92,rms=0.687254)
#GCMRL#  340 dt  76.972973 rms  0.687  0.429% neg 0  invalid 762 tFOTS 6.5410 tGradient 2.1100 tsec 9.0720
#FOTS# QuadFit found better minimum quadopt=(dt=93.8392,rms=0.683948) vs oldopt=(dt=103.68,rms=0.683983)
#GCMRL#  341 dt  93.839228 rms  0.684  0.377% neg 0  invalid 762 tFOTS 5.5150 tGradient 2.2940 tsec 8.2070
#FOTS# QuadFit found better minimum quadopt=(dt=36.288,rms=0.682987) vs oldopt=(dt=25.92,rms=0.683077)
#GCMRL#  342 dt  36.288000 rms  0.683  0.000% neg 0  invalid 762 tFOTS 5.9560 tGradient 1.8380 tsec 8.2890
#GCMRL#  343 dt  36.288000 rms  0.682  0.074% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.1990 tsec 2.5450
#GCMRL#  344 dt  36.288000 rms  0.682  0.100% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.8160 tsec 2.1630
#GCMRL#  345 dt  36.288000 rms  0.681  0.126% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.8060 tsec 2.1450
#GCMRL#  346 dt  36.288000 rms  0.680  0.093% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.0400 tsec 2.4650
iter 0, gcam->neg = 2
after 0 iterations, nbhd size=0, neg = 0
#GCMRL#  347 dt  36.288000 rms  0.680  0.049% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.0320 tsec 3.0700
#FOTS# QuadFit found better minimum quadopt=(dt=145.152,rms=0.679075) vs oldopt=(dt=103.68,rms=0.679193)
iter 0, gcam->neg = 1
after 0 iterations, nbhd size=0, neg = 0
#GCMRL#  348 dt 145.152000 rms  0.679  0.131% neg 0  invalid 762 tFOTS 6.1200 tGradient 1.9510 tsec 9.1530
#FOTS# QuadFit found better minimum quadopt=(dt=36.288,rms=0.67861) vs oldopt=(dt=25.92,rms=0.678656)
iter 0, gcam->neg = 1
after 0 iterations, nbhd size=0, neg = 0
#GCMRL#  349 dt  36.288000 rms  0.679  0.000% neg 0  invalid 762 tFOTS 6.1230 tGradient 2.0410 tsec 9.1610
#GCMRL#  350 dt  36.288000 rms  0.678  0.039% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.1230 tsec 2.4530
#GCMRL#  351 dt  36.288000 rms  0.678  0.056% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.9010 tsec 2.2470
iter 0, gcam->neg = 1
after 1 iterations, nbhd size=0, neg = 0
#GCMRL#  352 dt  36.288000 rms  0.678  0.067% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.8400 tsec 3.0470
iter 0, gcam->neg = 2
after 0 iterations, nbhd size=0, neg = 0
#GCMRL#  353 dt  36.288000 rms  0.677  0.061% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.8480 tsec 2.7500
iter 0, gcam->neg = 10
after 9 iterations, nbhd size=1, neg = 0

#GCAMreg# pass 0 level1 4 level2 1 tsec 75.887 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.03 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=64, sigma=0.5,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.677015
#FOTS# QuadFit found better minimum quadopt=(dt=30.6667,rms=0.675655) vs oldopt=(dt=25.92,rms=0.675658)
#GCMRL#  355 dt  30.666667 rms  0.676  0.201% neg 0  invalid 762 tFOTS 5.5290 tGradient 1.7950 tsec 7.7050
#FOTS# QuadFit found better minimum quadopt=(dt=88.6797,rms=0.674492) vs oldopt=(dt=103.68,rms=0.674525)
#GCMRL#  356 dt  88.679739 rms  0.674  0.000% neg 0  invalid 762 tFOTS 5.7110 tGradient 1.9130 tsec 8.0620
#GCMRL#  357 dt  88.679739 rms  0.672  0.367% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.0650 tsec 2.4350
#GCMRL#  358 dt  88.679739 rms  0.671  0.168% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.1580 tsec 2.5360
#GCMRL#  359 dt  88.679739 rms  0.671  0.027% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.1340 tsec 2.5290
#GCMRL#  360 dt  88.679739 rms  0.669  0.234% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.0840 tsec 2.4400
#GCMRL#  361 dt  88.679739 rms  0.668  0.152% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.0820 tsec 2.4300
#GCMRL#  362 dt  88.679739 rms  0.668  0.014% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.4700 tsec 2.8490
iter 0, gcam->neg = 3
after 0 iterations, nbhd size=0, neg = 0
#GCMRL#  363 dt  88.679739 rms  0.667  0.096% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.4870 tsec 3.5350
iter 0, gcam->neg = 3
after 0 iterations, nbhd size=0, neg = 0
#GCMRL#  364 dt  88.679739 rms  0.666  0.192% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.0880 tsec 3.0330
iter 0, gcam->neg = 4
after 8 iterations, nbhd size=1, neg = 0
#GCMRL#  365 dt  88.679739 rms  0.665  0.125% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.0510 tsec 5.5270
iter 0, gcam->neg = 6
after 7 iterations, nbhd size=1, neg = 0
#GCMRL#  366 dt  88.679739 rms  0.665  0.092% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.1750 tsec 5.5460
iter 0, gcam->neg = 5
after 8 iterations, nbhd size=1, neg = 0
#GCMRL#  367 dt  88.679739 rms  0.664  0.118% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.3370 tsec 6.2540
iter 0, gcam->neg = 6
after 2 iterations, nbhd size=0, neg = 0
#GCMRL#  368 dt  88.679739 rms  0.663  0.118% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.3170 tsec 4.2220
iter 0, gcam->neg = 6
after 2 iterations, nbhd size=0, neg = 0
#GCMRL#  369 dt  88.679739 rms  0.662  0.095% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.3220 tsec 4.0860
#FOTS# QuadFit found better minimum quadopt=(dt=82.944,rms=0.662267) vs oldopt=(dt=103.68,rms=0.662284)
#GCMRL#  370 dt  82.944000 rms  0.662  0.000% neg 0  invalid 762 tFOTS 6.6520 tGradient 2.2550 tsec 9.4810
#GCMRL#  371 dt  82.944000 rms  0.662  0.026% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.4420 tsec 2.8430
#GCMRL#  372 dt  82.944000 rms  0.662  0.046% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.2920 tsec 2.6970
iter 0, gcam->neg = 2
after 0 iterations, nbhd size=0, neg = 0
#GCMRL#  373 dt  82.944000 rms  0.661  0.051% neg 0  invalid 762 tFOTS 0.0000 tGradient 2.4450 tsec 3.5890
#GCMRL#  374 dt  82.944000 rms  0.661  0.048% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.9530 tsec 2.2930
setting smoothness cost coefficient to 0.118

#GCAMreg# pass 0 level1 3 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.12 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=16, sigma=2.0,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.665177
#FOTS# QuadFit found better minimum quadopt=(dt=25.6,rms=0.659913) vs oldopt=(dt=32,rms=0.660169)
iter 0, gcam->neg = 36
after 9 iterations, nbhd size=1, neg = 0
#GCMRL#  376 dt  25.600000 rms  0.660  0.770% neg 0  invalid 762 tFOTS 7.1400 tGradient 1.9770 tsec 13.0810
#FOTS# QuadFit found better minimum quadopt=(dt=44.8,rms=0.655093) vs oldopt=(dt=32,rms=0.655637)
iter 0, gcam->neg = 103
after 11 iterations, nbhd size=1, neg = 0
#GCMRL#  377 dt  44.800000 rms  0.655  0.740% neg 0  invalid 762 tFOTS 6.5210 tGradient 2.0740 tsec 13.2950
#FOTS# QuadFit found better minimum quadopt=(dt=19.4114,rms=0.652333) vs oldopt=(dt=32,rms=0.653212)
iter 0, gcam->neg = 54
after 9 iterations, nbhd size=1, neg = 0
#GCMRL#  378 dt  19.411411 rms  0.652  0.424% neg 0  invalid 762 tFOTS 6.9720 tGradient 1.9730 tsec 12.9230
#FOTS# QuadFit found better minimum quadopt=(dt=44.8,rms=0.649208) vs oldopt=(dt=32,rms=0.649714)
iter 0, gcam->neg = 107
after 10 iterations, nbhd size=1, neg = 0
#GCMRL#  379 dt  44.800000 rms  0.650  0.416% neg 0  invalid 762 tFOTS 7.1820 tGradient 1.9320 tsec 13.3730
#FOTS# QuadFit found better minimum quadopt=(dt=22,rms=0.647805) vs oldopt=(dt=32,rms=0.648197)
iter 0, gcam->neg = 58
after 10 iterations, nbhd size=1, neg = 0
#GCMRL#  380 dt  22.000000 rms  0.648  0.268% neg 0  invalid 762 tFOTS 6.2450 tGradient 2.0700 tsec 12.8570
#FOTS# QuadFit found better minimum quadopt=(dt=38.4,rms=0.646178) vs oldopt=(dt=32,rms=0.646207)
iter 0, gcam->neg = 80
after 10 iterations, nbhd size=1, neg = 0
#GCMRL#  381 dt  38.400000 rms  0.646  0.000% neg 0  invalid 762 tFOTS 6.0520 tGradient 2.0280 tsec 12.1020
iter 0, gcam->neg = 90
after 10 iterations, nbhd size=1, neg = 0

#GCAMreg# pass 0 level1 3 level2 1 tsec 87.62 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.12 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=16, sigma=0.5,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.646658
#FOTS# QuadFit found better minimum quadopt=(dt=31.4921,rms=0.641801) vs oldopt=(dt=32,rms=0.64181)
#GCMRL#  383 dt  31.492063 rms  0.642  0.751% neg 0  invalid 762 tFOTS 6.3470 tGradient 2.1720 tsec 8.9830
#FOTS# QuadFit found better minimum quadopt=(dt=25.6,rms=0.639617) vs oldopt=(dt=32,rms=0.639787)
iter 0, gcam->neg = 2
after 2 iterations, nbhd size=0, neg = 0
#GCMRL#  384 dt  25.600000 rms  0.640  0.342% neg 0  invalid 762 tFOTS 6.3650 tGradient 1.9220 tsec 10.2230
#FOTS# QuadFit found better minimum quadopt=(dt=25.6,rms=0.637746) vs oldopt=(dt=32,rms=0.637769)
iter 0, gcam->neg = 1
after 1 iterations, nbhd size=0, neg = 0
#GCMRL#  385 dt  25.600000 rms  0.638  0.289% neg 0  invalid 762 tFOTS 6.8070 tGradient 2.0090 tsec 10.3780
#FOTS# QuadFit found better minimum quadopt=(dt=11.2,rms=0.637059) vs oldopt=(dt=8,rms=0.637208)
#GCMRL#  386 dt  11.200000 rms  0.637  0.000% neg 0  invalid 762 tFOTS 6.1240 tGradient 1.6840 tsec 8.3050
iter 0, gcam->neg = 1
after 0 iterations, nbhd size=0, neg = 0
#GCMRL#  387 dt  11.200000 rms  0.637  0.077% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.8670 tsec 2.8750
iter 0, gcam->neg = 4
after 1 iterations, nbhd size=0, neg = 0
#GCMRL#  388 dt  11.200000 rms  0.636  0.133% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.8490 tsec 3.1490
iter 0, gcam->neg = 3
after 0 iterations, nbhd size=0, neg = 0
#GCMRL#  389 dt  11.200000 rms  0.635  0.180% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.8160 tsec 2.7610
iter 0, gcam->neg = 2
after 2 iterations, nbhd size=0, neg = 0
#GCMRL#  390 dt  11.200000 rms  0.633  0.204% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.8840 tsec 3.4540
iter 0, gcam->neg = 5
after 0 iterations, nbhd size=0, neg = 0
#GCMRL#  391 dt  11.200000 rms  0.632  0.217% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.9950 tsec 3.1800
iter 0, gcam->neg = 4
after 0 iterations, nbhd size=0, neg = 0
#GCMRL#  392 dt  11.200000 rms  0.631  0.221% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.8590 tsec 2.8700
iter 0, gcam->neg = 4
after 0 iterations, nbhd size=0, neg = 0
#GCMRL#  393 dt  11.200000 rms  0.629  0.223% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.9220 tsec 2.9330
iter 0, gcam->neg = 10
after 1 iterations, nbhd size=0, neg = 0
#GCMRL#  394 dt  11.200000 rms  0.628  0.215% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.8510 tsec 3.0540
iter 0, gcam->neg = 11
after 2 iterations, nbhd size=0, neg = 0
#GCMRL#  395 dt  11.200000 rms  0.626  0.216% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.7240 tsec 3.3480
iter 0, gcam->neg = 5
after 10 iterations, nbhd size=1, neg = 0
#GCMRL#  396 dt  11.200000 rms  0.625  0.216% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.6680 tsec 6.2300
iter 0, gcam->neg = 9
after 8 iterations, nbhd size=1, neg = 0
#GCMRL#  397 dt  11.200000 rms  0.624  0.224% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.8910 tsec 5.3650
iter 0, gcam->neg = 14
after 3 iterations, nbhd size=0, neg = 0
#GCMRL#  398 dt  11.200000 rms  0.622  0.216% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.5900 tsec 3.3890
iter 0, gcam->neg = 15
after 9 iterations, nbhd size=1, neg = 0
#GCMRL#  399 dt  11.200000 rms  0.621  0.205% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.8920 tsec 5.4840
iter 0, gcam->neg = 15
after 8 iterations, nbhd size=1, neg = 0
#GCMRL#  400 dt  11.200000 rms  0.620  0.181% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.5930 tsec 4.8350
iter 0, gcam->neg = 8
after 8 iterations, nbhd size=1, neg = 0
#GCMRL#  401 dt  11.200000 rms  0.619  0.176% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.5950 tsec 5.3130
iter 0, gcam->neg = 14
after 1 iterations, nbhd size=0, neg = 0
#GCMRL#  402 dt  11.200000 rms  0.618  0.164% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.9050 tsec 3.1580
iter 0, gcam->neg = 5
after 1 iterations, nbhd size=0, neg = 0
#GCMRL#  403 dt  11.200000 rms  0.617  0.149% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.8650 tsec 3.1120
iter 0, gcam->neg = 16
after 10 iterations, nbhd size=1, neg = 0
#GCMRL#  404 dt  11.200000 rms  0.616  0.109% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.9530 tsec 6.3020
iter 0, gcam->neg = 15
after 8 iterations, nbhd size=1, neg = 0
#GCMRL#  405 dt  11.200000 rms  0.616  0.097% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.9870 tsec 5.9070
#FOTS# QuadFit found better minimum quadopt=(dt=44.8,rms=0.615202) vs oldopt=(dt=32,rms=0.615259)
iter 0, gcam->neg = 7
after 2 iterations, nbhd size=0, neg = 0
#GCMRL#  406 dt  44.800000 rms  0.615  0.000% neg 0  invalid 762 tFOTS 6.5490 tGradient 1.9110 tsec 10.2000
iter 0, gcam->neg = 3
after 2 iterations, nbhd size=0, neg = 0
setting smoothness cost coefficient to 0.400

#GCAMreg# pass 0 level1 2 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.40 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=4, sigma=2.0,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.631811
#GCMRL#  408 dt   2.880000 rms  0.631  0.110% neg 0  invalid 762 tFOTS 6.8720 tGradient 1.9960 tsec 9.3250
#FOTS# QuadFit found better minimum quadopt=(dt=2.70588,rms=0.630887) vs oldopt=(dt=2.88,rms=0.630888)
#GCMRL#  409 dt   2.705882 rms  0.631  0.000% neg 0  invalid 762 tFOTS 6.5000 tGradient 1.8070 tsec 8.7900
iter 0, gcam->neg = 1
after 6 iterations, nbhd size=1, neg = 0
#GCMRL#  410 dt   2.705882 rms  0.631  0.027% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.8040 tsec 4.9220

#GCAMreg# pass 0 level1 2 level2 1 tsec 29.246 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=0.40 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=4, sigma=0.5,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.631047
#FOTS# QuadFit found better minimum quadopt=(dt=0.000140625,rms=0.630715) vs oldopt=(dt=0.000175781,rms=0.630715)
#GCMRL#  412 dt   0.000141 rms  0.631  0.053% neg 0  invalid 762 tFOTS 7.8240 tGradient 1.7830 tsec 10.0010
setting smoothness cost coefficient to 1.000

#GCAMreg# pass 0 level1 1 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=1.00 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=1, sigma=2.0,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.658179
#FOTS# QuadFit found better minimum quadopt=(dt=0.384,rms=0.657645) vs oldopt=(dt=0.32,rms=0.657651)
#GCMRL#  414 dt   0.384000 rms  0.658  0.081% neg 0  invalid 762 tFOTS 5.9560 tGradient 1.3960 tsec 7.7660
#FOTS# QuadFit found better minimum quadopt=(dt=0.112,rms=0.657624) vs oldopt=(dt=0.08,rms=0.657631)
#GCMRL#  415 dt   0.112000 rms  0.658  0.000% neg 0  invalid 762 tFOTS 5.9910 tGradient 1.3790 tsec 7.7970
#GCMRL#  416 dt   0.112000 rms  0.658  0.003% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.4480 tsec 1.8240

#GCAMreg# pass 0 level1 1 level2 1 tsec 23.207 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=1.00 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=1, sigma=0.5,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.657911
#FOTS# QuadFit found better minimum quadopt=(dt=0.384,rms=0.657458) vs oldopt=(dt=0.32,rms=0.657459)
#GCMRL#  418 dt   0.384000 rms  0.657  0.069% neg 0  invalid 762 tFOTS 6.2940 tGradient 1.8140 tsec 8.5690
#FOTS# QuadFit found better minimum quadopt=(dt=0.112,rms=0.657426) vs oldopt=(dt=0.08,rms=0.657432)
#GCMRL#  419 dt   0.112000 rms  0.657  0.000% neg 0  invalid 762 tFOTS 6.8420 tGradient 1.7510 tsec 9.1160
#GCMRL#  420 dt   0.112000 rms  0.657  0.002% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.7830 tsec 2.2040
resetting metric properties...
setting smoothness cost coefficient to 2.000

#GCAMreg# pass 0 level1 0 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=2.00 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=0, sigma=2.0,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.619313
#FOTS# QuadFit found better minimum quadopt=(dt=2.30368,rms=0.561947) vs oldopt=(dt=1.28,rms=0.573144)
iter 0, gcam->neg = 2748
after 16 iterations, nbhd size=1, neg = 0
#GCMRL#  422 dt   2.303679 rms  0.576  7.045% neg 0  invalid 762 tFOTS 6.5580 tGradient 1.1120 tsec 14.5540
#FOTS# QuadFit found better minimum quadopt=(dt=0.112,rms=0.574645) vs oldopt=(dt=0.08,rms=0.574826)
#GCMRL#  423 dt   0.112000 rms  0.575  0.000% neg 0  invalid 762 tFOTS 7.2000 tGradient 1.0490 tsec 8.7830
#GCMRL#  424 dt   0.112000 rms  0.575  0.007% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.0070 tsec 1.4480

#GCAMreg# pass 0 level1 0 level2 1 tsec 30.197 sigma 0.5
l_jacobian=1.00 l_label=1.00 l_log_likelihood=0.20 l_smoothness=2.00 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=0, sigma=0.5,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.574996
#FOTS# QuadFit found better minimum quadopt=(dt=0.028,rms=0.574548) vs oldopt=(dt=0.02,rms=0.574559)
#GCMRL#  426 dt   0.028000 rms  0.575  0.078% neg 0  invalid 762 tFOTS 5.8980 tGradient 1.2010 tsec 7.5500
#FOTS# QuadFit found better minimum quadopt=(dt=0.024,rms=0.574529) vs oldopt=(dt=0.02,rms=0.574529)
#GCMRL#  427 dt   0.024000 rms  0.575  0.000% neg 0  invalid 762 tFOTS 6.0510 tGradient 0.9170 tsec 7.4090
label assignment complete, 0 changed (0.00%)
GCAMregister done in 9.60347 min
Starting GCAMcomputeMaxPriorLabels()
Morphing with label term set to 0 *******************************
Starting GCAMregister()
label assignment complete, 0 changed (0.00%)
npasses = 1, nlevels = 6
#pass# 1 of 1 ************************
enabling zero nodes
setting smoothness cost coefficient to 0.008

#GCAMreg# pass 0 level1 5 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_log_likelihood=0.20 l_smoothness=0.01 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=256, sigma=2.0,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.555463
#FOTS# QuadFit found better minimum quadopt=(dt=32.368,rms=0.555186) vs oldopt=(dt=23.12,rms=0.555202)
#GCMRL#  429 dt  32.368000 rms  0.555  0.050% neg 0  invalid 762 tFOTS 5.3510 tGradient 1.7800 tsec 7.5680

#GCAMreg# pass 0 level1 5 level2 1 tsec 19.138 sigma 0.5
l_jacobian=1.00 l_log_likelihood=0.20 l_smoothness=0.01 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=256, sigma=0.5,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.555186
#FOTS# QuadFit found better minimum quadopt=(dt=18.496,rms=0.555159) vs oldopt=(dt=23.12,rms=0.555159)
#GCMRL#  431 dt  18.496000 rms  0.555  0.005% neg 0  invalid 762 tFOTS 5.6490 tGradient 2.2840 tsec 8.3370
#FOTS# QuadFit found better minimum quadopt=(dt=6.936,rms=0.555157) vs oldopt=(dt=5.78,rms=0.555157)
#GCMRL#  432 dt   6.936000 rms  0.555  0.000% neg 0  invalid 762 tFOTS 5.8370 tGradient 2.2130 tsec 8.5320
setting smoothness cost coefficient to 0.031

#GCAMreg# pass 0 level1 4 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_log_likelihood=0.20 l_smoothness=0.03 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=64, sigma=2.0,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.555386
#FOTS# QuadFit found better minimum quadopt=(dt=9.072,rms=0.555291) vs oldopt=(dt=6.48,rms=0.555303)
#GCMRL#  434 dt   9.072000 rms  0.555  0.017% neg 0  invalid 762 tFOTS 6.9050 tGradient 1.6320 tsec 9.1030
#FOTS# QuadFit found better minimum quadopt=(dt=2.268,rms=0.555285) vs oldopt=(dt=1.62,rms=0.555286)
#GCMRL#  435 dt   2.268000 rms  0.555  0.000% neg 0  invalid 762 tFOTS 6.5270 tGradient 1.8560 tsec 8.8930
#GCMRL#  436 dt   2.268000 rms  0.555  0.001% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.7760 tsec 2.1420

#GCAMreg# pass 0 level1 4 level2 1 tsec 25.897 sigma 0.5
l_jacobian=1.00 l_log_likelihood=0.20 l_smoothness=0.03 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=64, sigma=0.5,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.555282
#FOTS# QuadFit found better minimum quadopt=(dt=20.736,rms=0.555051) vs oldopt=(dt=25.92,rms=0.555058)
#GCMRL#  438 dt  20.736000 rms  0.555  0.042% neg 0  invalid 762 tFOTS 6.5480 tGradient 1.6190 tsec 8.5990
#FOTS# QuadFit found better minimum quadopt=(dt=36.288,rms=0.554918) vs oldopt=(dt=25.92,rms=0.554933)
#GCMRL#  439 dt  36.288000 rms  0.555  0.000% neg 0  invalid 762 tFOTS 5.1010 tGradient 1.7400 tsec 7.2880
#GCMRL#  440 dt  36.288000 rms  0.555  0.037% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.3530 tsec 1.6950
#GCMRL#  441 dt  36.288000 rms  0.554  0.039% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.4750 tsec 1.7960
#GCMRL#  442 dt  36.288000 rms  0.554  0.016% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.6310 tsec 2.0270
setting smoothness cost coefficient to 0.118

#GCAMreg# pass 0 level1 3 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_log_likelihood=0.20 l_smoothness=0.12 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=16, sigma=2.0,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.5553
#FOTS# QuadFit found better minimum quadopt=(dt=11.2,rms=0.553611) vs oldopt=(dt=8,rms=0.553799)
#GCMRL#  444 dt  11.200000 rms  0.554  0.304% neg 0  invalid 762 tFOTS 6.9520 tGradient 1.4250 tsec 8.8460
#FOTS# QuadFit found better minimum quadopt=(dt=25.6,rms=0.552131) vs oldopt=(dt=32,rms=0.552181)
#GCMRL#  445 dt  25.600000 rms  0.552  0.267% neg 0  invalid 762 tFOTS 5.9660 tGradient 1.2180 tsec 7.6350
#FOTS# QuadFit found better minimum quadopt=(dt=38.4,rms=0.551047) vs oldopt=(dt=32,rms=0.551072)
iter 0, gcam->neg = 14
after 9 iterations, nbhd size=1, neg = 0
#GCMRL#  446 dt  38.400000 rms  0.551  0.000% neg 0  invalid 762 tFOTS 5.5310 tGradient 1.3020 tsec 10.8050
iter 0, gcam->neg = 33
after 10 iterations, nbhd size=1, neg = 0

#GCAMreg# pass 0 level1 3 level2 1 tsec 36.644 sigma 0.5
l_jacobian=1.00 l_log_likelihood=0.20 l_smoothness=0.12 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=16, sigma=0.5,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.551306
#FOTS# QuadFit found better minimum quadopt=(dt=27.1036,rms=0.548009) vs oldopt=(dt=32,rms=0.548166)
#GCMRL#  448 dt  27.103555 rms  0.548  0.598% neg 0  invalid 762 tFOTS 5.5070 tGradient 1.1480 tsec 7.0590
#FOTS# QuadFit found better minimum quadopt=(dt=11.2,rms=0.547179) vs oldopt=(dt=8,rms=0.547293)
#GCMRL#  449 dt  11.200000 rms  0.547  0.000% neg 0  invalid 762 tFOTS 5.9160 tGradient 1.2170 tsec 7.6510
#GCMRL#  450 dt  11.200000 rms  0.547  0.070% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.6900 tsec 2.1390
iter 0, gcam->neg = 2
after 0 iterations, nbhd size=0, neg = 0
#GCMRL#  451 dt  11.200000 rms  0.546  0.100% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.7970 tsec 3.0060
iter 0, gcam->neg = 2
after 7 iterations, nbhd size=1, neg = 0
#GCMRL#  452 dt  11.200000 rms  0.546  0.091% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.7180 tsec 5.3780
iter 0, gcam->neg = 4
after 8 iterations, nbhd size=1, neg = 0
#GCMRL#  453 dt  11.200000 rms  0.545  0.064% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.5830 tsec 5.2540
iter 0, gcam->neg = 18
after 11 iterations, nbhd size=1, neg = 0
#GCMRL#  454 dt 128.000000 rms  0.544  0.190% neg 0  invalid 762 tFOTS 6.2910 tGradient 1.3210 tsec 12.5360
#FOTS# QuadFit found better minimum quadopt=(dt=11.2,rms=0.543996) vs oldopt=(dt=8,rms=0.544071)
setting smoothness cost coefficient to 0.400

#GCAMreg# pass 0 level1 2 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_log_likelihood=0.20 l_smoothness=0.40 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=4, sigma=2.0,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.548808
#FOTS# QuadFit found better minimum quadopt=(dt=9.62712,rms=0.546834) vs oldopt=(dt=11.52,rms=0.546912)
iter 0, gcam->neg = 10
after 11 iterations, nbhd size=1, neg = 0
#GCMRL#  456 dt   9.627119 rms  0.547  0.335% neg 0  invalid 762 tFOTS 6.0950 tGradient 1.3890 tsec 12.7590
#FOTS# QuadFit found better minimum quadopt=(dt=19.9604,rms=0.54461) vs oldopt=(dt=11.52,rms=0.545041)
iter 0, gcam->neg = 48
after 10 iterations, nbhd size=1, neg = 0
#GCMRL#  457 dt  19.960396 rms  0.545  0.368% neg 0  invalid 762 tFOTS 5.7710 tGradient 1.4270 tsec 11.3920
#FOTS# QuadFit found better minimum quadopt=(dt=4.88889,rms=0.544785) vs oldopt=(dt=2.88,rms=0.544816)
iter 0, gcam->neg = 11
after 13 iterations, nbhd size=1, neg = 0
#GCMRL#  458 dt   4.888889 rms  0.545  0.000% neg 0  invalid 762 tFOTS 5.5840 tGradient 1.0400 tsec 12.1260
iter 0, gcam->neg = 11
after 13 iterations, nbhd size=1, neg = 0

#GCAMreg# pass 0 level1 2 level2 1 tsec 46.405 sigma 0.5
l_jacobian=1.00 l_log_likelihood=0.20 l_smoothness=0.40 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=4, sigma=0.5,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.544958
#FOTS# QuadFit found better minimum quadopt=(dt=7.18841,rms=0.543806) vs oldopt=(dt=11.52,rms=0.544199)
#GCMRL#  460 dt   7.188406 rms  0.544  0.211% neg 0  invalid 762 tFOTS 6.4200 tGradient 1.5610 tsec 8.4500
#FOTS# QuadFit found better minimum quadopt=(dt=13.7895,rms=0.542142) vs oldopt=(dt=11.52,rms=0.542187)
iter 0, gcam->neg = 3
after 4 iterations, nbhd size=0, neg = 0
#GCMRL#  461 dt  13.789474 rms  0.542  0.298% neg 0  invalid 762 tFOTS 5.6120 tGradient 1.5330 tsec 9.7180
#FOTS# QuadFit found better minimum quadopt=(dt=13.6119,rms=0.541369) vs oldopt=(dt=11.52,rms=0.541388)
iter 0, gcam->neg = 3
after 6 iterations, nbhd size=0, neg = 0
#GCMRL#  462 dt  13.611940 rms  0.541  0.000% neg 0  invalid 762 tFOTS 5.6620 tGradient 1.1040 tsec 9.5370
iter 0, gcam->neg = 3
after 2 iterations, nbhd size=0, neg = 0
#GCMRL#  463 dt  13.611940 rms  0.541  0.047% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.1030 tsec 2.6640
iter 0, gcam->neg = 8
after 9 iterations, nbhd size=1, neg = 0
#GCMRL#  464 dt  13.611940 rms  0.540  0.170% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.1780 tsec 4.8640
iter 0, gcam->neg = 9
after 2 iterations, nbhd size=0, neg = 0
#GCMRL#  465 dt  13.611940 rms  0.539  0.151% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.0310 tsec 2.4370
iter 0, gcam->neg = 20
after 3 iterations, nbhd size=0, neg = 0
#GCMRL#  466 dt  13.611940 rms  0.538  0.193% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.0080 tsec 2.7060
iter 0, gcam->neg = 24
after 11 iterations, nbhd size=1, neg = 0
#GCMRL#  467 dt  13.611940 rms  0.538  0.123% neg 0  invalid 762 tFOTS 0.0000 tGradient 0.9810 tsec 5.0240
iter 0, gcam->neg = 26
after 11 iterations, nbhd size=1, neg = 0
#GCMRL#  468 dt  13.611940 rms  0.537  0.080% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.0050 tsec 5.1050
#FOTS# QuadFit found better minimum quadopt=(dt=9.71429,rms=0.53693) vs oldopt=(dt=2.88,rms=0.537041)
iter 0, gcam->neg = 6
after 1 iterations, nbhd size=0, neg = 0
#GCMRL#  469 dt   9.714286 rms  0.537  0.000% neg 0  invalid 762 tFOTS 5.3930 tGradient 1.0200 tsec 7.8500
iter 0, gcam->neg = 5
after 1 iterations, nbhd size=0, neg = 0
#GCMRL#  470 dt   9.714286 rms  0.536  0.101% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.1690 tsec 2.6390
iter 0, gcam->neg = 14
after 1 iterations, nbhd size=0, neg = 0
#GCMRL#  471 dt   9.714286 rms  0.536  0.020% neg 0  invalid 762 tFOTS 0.0000 tGradient 1.4070 tsec 2.9070
iter 0, gcam->neg = 11
after 6 iterations, nbhd size=0, neg = 0
setting smoothness cost coefficient to 1.000

#GCAMreg# pass 0 level1 1 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_log_likelihood=0.20 l_smoothness=1.00 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=1, sigma=2.0,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.545698
#FOTS# QuadFit found better minimum quadopt=(dt=4e-05,rms=0.545698) vs oldopt=(dt=5e-05,rms=0.545698)
#GCMRL#  473 dt   0.000040 rms  0.546  0.000% neg 0  invalid 762 tFOTS 8.4760 tGradient 1.2990 tsec 10.2390

#GCAMreg# pass 0 level1 1 level2 1 tsec 21.089 sigma 0.5
l_jacobian=1.00 l_log_likelihood=0.20 l_smoothness=1.00 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=1, sigma=0.5,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.545698
resetting metric properties...
setting smoothness cost coefficient to 2.000

#GCAMreg# pass 0 level1 0 level2 0 tsec 0 sigma 2
l_jacobian=1.00 l_log_likelihood=0.20 l_smoothness=2.00 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=0, sigma=2.0,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=2.000...
GCAMRegisterLevel(): init RMS 0.529893
iter 0, gcam->neg = 1152
after 14 iterations, nbhd size=1, neg = 0
#GCMRL#  476 dt   1.280000 rms  0.516  2.674% neg 0  invalid 762 tFOTS 5.6960 tGradient 0.3390 tsec 11.5060
#FOTS# QuadFit found better minimum quadopt=(dt=0.064,rms=0.515609) vs oldopt=(dt=0.08,rms=0.515623)
#GCMRL#  477 dt   0.064000 rms  0.516  0.000% neg 0  invalid 762 tFOTS 5.6350 tGradient 0.3660 tsec 6.3900

#GCAMreg# pass 0 level1 0 level2 1 tsec 22.497 sigma 0.5
l_jacobian=1.00 l_log_likelihood=0.20 l_smoothness=2.00 
tol=2.50e-01, dt=5.00e-02, exp_k=20.0, momentum=0.90, levels=6, niter=500, lbl_dist=10.00, avgs=0, sigma=0.5,type=2, relabel=0, neg=yes

blurring input image with Gaussian with sigma=0.500...
GCAMRegisterLevel(): init RMS 0.515609
#FOTS# QuadFit found better minimum quadopt=(dt=0.112,rms=0.515039) vs oldopt=(dt=0.08,rms=0.515132)
#GCMRL#  479 dt   0.112000 rms  0.515  0.111% neg 0  invalid 762 tFOTS 5.0100 tGradient 0.4880 tsec 5.8790
#FOTS# QuadFit found better minimum quadopt=(dt=0.112,rms=0.514747) vs oldopt=(dt=0.08,rms=0.514781)
#GCMRL#  480 dt   0.112000 rms  0.515  0.000% neg 0  invalid 762 tFOTS 5.7750 tGradient 0.4000 tsec 6.6440
#GCMRL#  481 dt   0.112000 rms  0.515  0.042% neg 0  invalid 762 tFOTS 0.0000 tGradient 0.4020 tsec 0.7620
GCAMregister done in 6.13898 min
writing output transformation to transforms/talairach.m3z...
GCAMwrite
Calls to gcamLogLikelihoodEnergy 4137 tmin = 1.82737
Calls to gcamLabelEnergy         3484 tmin = 1.2616
Calls to gcamJacobianEnergy      4137 tmin = 1.4084
Calls to gcamSmoothnessEnergy    4137 tmin = 4.59867
Calls to gcamLogLikelihoodTerm 483 tmin = 0.630933
Calls to gcamLabelTerm         429 tmin = 4.80578
Calls to gcamJacobianTerm      483 tmin = 1.33405
Calls to gcamSmoothnessTerm    483 tmin = 0.69625
Calls to gcamComputeGradient    483 tmin = 17.1294
Calls to gcamComputeMetricProperties    5965 tmin = 5.01822
mri_ca_register took 0 hours, 50 minutes and 38 seconds.
#VMPC# mri_ca_register VmPeak  3428680
FSRUNTIME@ mri_ca_register  0.8438 hours 16 threads
#--------------------------------------
#@# SubCort Seg Wed Sep 20 17:02:47 EDT 2023

 mri_ca_label -relabel_unlikely 9 .3 -prior 0.5 -align norm.mgz transforms/talairach.m3z /opt/freesurfer/average/RB_all_2020-01-02.gca aseg.auto_noCCseg.mgz 

sysname  Linux
hostname cn4271
machine  x86_64

setenv SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mri_ca_label -relabel_unlikely 9 .3 -prior 0.5 -align norm.mgz transforms/talairach.m3z /opt/freesurfer/average/RB_all_2020-01-02.gca aseg.auto_noCCseg.mgz 

relabeling unlikely voxels with window_size = 9 and prior threshold 0.30
using Gibbs prior factor = 0.500
renormalizing sequences with structure alignment, equivalent to:
	-renormalize
	-renormalize_mean 0.500
	-regularize 0.500

== Number of threads available to for OpenMP = 16 == 
reading 1 input volumes
reading classifier array from /opt/freesurfer/average/RB_all_2020-01-02.gca
reading input volume from norm.mgz
average std[0] = 7.2
reading transform from transforms/talairach.m3z
setting orig areas to linear transform determinant scaled 13.04
Atlas used for the 3D morph was /opt/freesurfer/average/RB_all_2020-01-02.gca
average std = 7.2   using min determinant for regularization = 5.2
0 singular and 0 ill-conditioned covariance matrices regularized
labeling volume...
renormalizing by structure alignment....
renormalizing input #0
gca peak = 0.15521 (20)
mri peak = 0.09575 ( 3)
Left_Lateral_Ventricle (4): linear fit = 0.09 x + 0.0 (681 voxels, overlap=0.043)
Left_Lateral_Ventricle (4): linear fit = 0.40 x + 0.0 (681 voxels, peak =  2), gca=8.0
gca peak = 0.20380 (13)
mri peak = 0.11987 ( 3)
Right_Lateral_Ventricle (43): linear fit = 0.08 x + 0.0 (689 voxels, overlap=0.066)
Right_Lateral_Ventricle (43): linear fit = 0.40 x + 0.0 (689 voxels, peak =  1), gca=5.2
gca peak = 0.26283 (96)
mri peak = 0.08870 (99)
Right_Pallidum (52): linear fit = 1.04 x + 0.0 (2340 voxels, overlap=1.017)
Right_Pallidum (52): linear fit = 1.04 x + 0.0 (2340 voxels, peak = 100), gca=100.3
gca peak = 0.15814 (97)
mri peak = 0.07159 (97)
Left_Pallidum (13): linear fit = 1.02 x + 0.0 (1768 voxels, overlap=1.013)
Left_Pallidum (13): linear fit = 1.02 x + 0.0 (1768 voxels, peak = 99), gca=99.4
gca peak = 0.27624 (56)
mri peak = 0.07323 (67)
Right_Hippocampus (53): linear fit = 1.08 x + 0.0 (2251 voxels, overlap=0.972)
Right_Hippocampus (53): linear fit = 1.08 x + 0.0 (2251 voxels, peak = 60), gca=60.2
gca peak = 0.28723 (59)
mri peak = 0.08241 (65)
Left_Hippocampus (17): linear fit = 1.13 x + 0.0 (2263 voxels, overlap=1.012)
Left_Hippocampus (17): linear fit = 1.13 x + 0.0 (2263 voxels, peak = 67), gca=67.0
gca peak = 0.07623 (103)
mri peak = 0.07659 (98)
Right_Cerebral_White_Matter (41): linear fit = 0.96 x + 0.0 (127041 voxels, overlap=0.795)
Right_Cerebral_White_Matter (41): linear fit = 0.96 x + 0.0 (127041 voxels, peak = 99), gca=99.4
gca peak = 0.07837 (105)
mri peak = 0.07633 (100)
Left_Cerebral_White_Matter (2): linear fit = 0.96 x + 0.0 (119481 voxels, overlap=0.693)
Left_Cerebral_White_Matter (2): linear fit = 0.96 x + 0.0 (119481 voxels, peak = 101), gca=101.3
gca peak = 0.10165 (58)
mri peak = 0.03782 (61)
Left_Cerebral_Cortex (3): linear fit = 1.04 x + 0.0 (69812 voxels, overlap=0.864)
Left_Cerebral_Cortex (3): linear fit = 1.04 x + 0.0 (69812 voxels, peak = 61), gca=60.6
gca peak = 0.11113 (58)
mri peak = 0.03394 (56)
Right_Cerebral_Cortex (42): linear fit = 1.02 x + 0.0 (66804 voxels, overlap=0.942)
Right_Cerebral_Cortex (42): linear fit = 1.02 x + 0.0 (66804 voxels, peak = 59), gca=59.4
gca peak = 0.27796 (67)
mri peak = 0.13132 (68)
Right_Caudate (50): linear fit = 0.99 x + 0.0 (2688 voxels, overlap=1.002)
Right_Caudate (50): linear fit = 0.99 x + 0.0 (2688 voxels, peak = 66), gca=66.0
gca peak = 0.14473 (69)
mri peak = 0.13304 (69)
Left_Caudate (11): linear fit = 0.89 x + 0.0 (2751 voxels, overlap=0.449)
Left_Caudate (11): linear fit = 0.89 x + 0.0 (2751 voxels, peak = 62), gca=61.8
gca peak = 0.14301 (56)
mri peak = 0.03740 (62)
Left_Cerebellum_Cortex (8): linear fit = 1.13 x + 0.0 (42347 voxels, overlap=0.807)
Left_Cerebellum_Cortex (8): linear fit = 1.13 x + 0.0 (42347 voxels, peak = 64), gca=63.6
gca peak = 0.14610 (55)
mri peak = 0.03283 (68)
Right_Cerebellum_Cortex (47): linear fit = 1.21 x + 0.0 (38959 voxels, overlap=0.358)
Right_Cerebellum_Cortex (47): linear fit = 1.21 x + 0.0 (38959 voxels, peak = 66), gca=66.3
gca peak = 0.16309 (85)
mri peak = 0.10210 (89)
Left_Cerebellum_White_Matter (7): linear fit = 1.07 x + 0.0 (13438 voxels, overlap=0.661)
Left_Cerebellum_White_Matter (7): linear fit = 1.07 x + 0.0 (13438 voxels, peak = 91), gca=90.5
gca peak = 0.15172 (84)
mri peak = 0.10475 (91)
Right_Cerebellum_White_Matter (46): linear fit = 1.08 x + 0.0 (10851 voxels, overlap=0.589)
Right_Cerebellum_White_Matter (46): linear fit = 1.08 x + 0.0 (10851 voxels, peak = 90), gca=90.3
gca peak = 0.30461 (58)
mri peak = 0.10987 (66)
Left_Amygdala (18): linear fit = 1.14 x + 0.0 (1206 voxels, overlap=0.218)
Left_Amygdala (18): linear fit = 1.14 x + 0.0 (1206 voxels, peak = 66), gca=66.4
gca peak = 0.32293 (57)
mri peak = 0.12025 (69)
Right_Amygdala (54): linear fit = 1.22 x + 0.0 (1447 voxels, overlap=0.043)
Right_Amygdala (54): linear fit = 1.22 x + 0.0 (1447 voxels, peak = 69), gca=69.3
gca peak = 0.11083 (90)
mri peak = 0.05927 (94)
Left_Thalamus (10): linear fit = 1.09 x + 0.0 (11379 voxels, overlap=0.632)
Left_Thalamus (10): linear fit = 1.09 x + 0.0 (11379 voxels, peak = 98), gca=97.7
gca peak = 0.11393 (83)
mri peak = 0.05560 (93)
Right_Thalamus (49): linear fit = 1.12 x + 0.0 (9793 voxels, overlap=0.612)
Right_Thalamus (49): linear fit = 1.12 x + 0.0 (9793 voxels, peak = 93), gca=92.5
gca peak = 0.08575 (81)
mri peak = 0.06188 (81)
Left_Putamen (12): linear fit = 1.01 x + 0.0 (4954 voxels, overlap=0.967)
Left_Putamen (12): linear fit = 1.01 x + 0.0 (4954 voxels, peak = 82), gca=82.2
gca peak = 0.08618 (78)
mri peak = 0.05809 (76)
Right_Putamen (51): linear fit = 1.00 x + 0.0 (6026 voxels, overlap=1.000)
Right_Putamen (51): linear fit = 1.00 x + 0.0 (6026 voxels, peak = 78), gca=78.0
gca peak = 0.08005 (78)
mri peak = 0.07365 (90)
Brain_Stem (16): linear fit = 1.12 x + 0.0 (24152 voxels, overlap=0.492)
Brain_Stem (16): linear fit = 1.12 x + 0.0 (24152 voxels, peak = 88), gca=87.8
gca peak = 0.12854 (88)
mri peak = 0.07240 (103)
Right_VentralDC (60): linear fit = 1.20 x + 0.0 (3494 voxels, overlap=0.017)
Right_VentralDC (60): linear fit = 1.20 x + 0.0 (3494 voxels, peak = 105), gca=105.2
gca peak = 0.15703 (87)
mri peak = 0.07404 (100)
Left_VentralDC (28): linear fit = 1.15 x + 0.0 (3752 voxels, overlap=0.014)
Left_VentralDC (28): linear fit = 1.15 x + 0.0 (3752 voxels, peak = 100), gca=100.5
gca peak = 0.17522 (25)
mri peak = 0.16137 (10)
Third_Ventricle (14): linear fit = 0.35 x + 0.0 (53 voxels, overlap=0.109)
Third_Ventricle (14): linear fit = 0.35 x + 0.0 (53 voxels, peak =  9), gca=8.9
gca peak = 0.17113 (14)
mri peak = 0.24390 ( 9)
Fourth_Ventricle (15): linear fit = 0.51 x + 0.0 (856 voxels, overlap=0.247)
Fourth_Ventricle (15): linear fit = 0.51 x + 0.0 (856 voxels, peak =  7), gca=7.2
gca peak Unknown = 0.94777 ( 0)
gca peak Left_Inf_Lat_Vent = 0.16627 (28)
gca peak Third_Ventricle = 0.17522 (25)
gca peak Fourth_Ventricle = 0.17113 (14)
gca peak CSF = 0.20346 (36)
gca peak Left_Accumbens_area = 0.70646 (62)
gca peak Left_undetermined = 1.00000 (28)
gca peak Left_vessel = 0.89917 (53)
gca peak Left_choroid_plexus = 0.11689 (35)
gca peak Right_Inf_Lat_Vent = 0.25504 (23)
gca peak Right_Accumbens_area = 0.31650 (65)
gca peak Right_vessel = 0.77268 (52)
gca peak Right_choroid_plexus = 0.13275 (38)
gca peak Fifth_Ventricle = 0.60973 (33)
gca peak WM_hypointensities = 0.11013 (77)
gca peak non_WM_hypointensities = 0.11354 (41)
gca peak Optic_Chiasm = 0.51646 (76)
not using caudate to estimate GM means
estimating mean gm scale to be 1.11 x + 0.0
estimating mean wm scale to be 0.96 x + 0.0
estimating mean csf scale to be 0.40 x + 0.0
Left_Pallidum too bright - rescaling by 0.979 (from 1.025) to 97.3 (was 99.4)
Right_Pallidum too bright - rescaling by 0.970 (from 1.045) to 97.3 (was 100.3)
saving intensity scales to aseg.auto_noCCseg.label_intensities.txt
renormalizing by structure alignment....
renormalizing input #0
gca peak = 0.31706 ( 7)
mri peak = 0.09575 ( 3)
Left_Lateral_Ventricle (4): linear fit = 0.28 x + 0.0 (681 voxels, overlap=0.630)
Left_Lateral_Ventricle (4): linear fit = 0.40 x + 0.0 (681 voxels, peak =  2), gca=2.8
gca peak = 0.29334 ( 5)
mri peak = 0.11987 ( 3)
Right_Lateral_Ventricle (43): linear fit = 0.22 x + 0.0 (689 voxels, overlap=0.301)
Right_Lateral_Ventricle (43): linear fit = 0.40 x + 0.0 (689 voxels, peak =  1), gca=2.0
gca peak = 0.22185 (94)
mri peak = 0.08870 (99)
Right_Pallidum (52): linear fit = 1.03 x + 0.0 (2340 voxels, overlap=1.004)
Right_Pallidum (52): linear fit = 1.03 x + 0.0 (2340 voxels, peak = 97), gca=97.3
gca peak = 0.16415 (94)
mri peak = 0.07159 (97)
Left_Pallidum (13): linear fit = 1.01 x + 0.0 (1768 voxels, overlap=1.007)
Left_Pallidum (13): linear fit = 1.01 x + 0.0 (1768 voxels, peak = 95), gca=95.4
gca peak = 0.24808 (60)
mri peak = 0.07323 (67)
Right_Hippocampus (53): linear fit = 1.02 x + 0.0 (2251 voxels, overlap=1.005)
Right_Hippocampus (53): linear fit = 1.02 x + 0.0 (2251 voxels, peak = 62), gca=61.5
gca peak = 0.32671 (64)
mri peak = 0.08241 (65)
Left_Hippocampus (17): linear fit = 1.00 x + 0.0 (2263 voxels, overlap=1.006)
Left_Hippocampus (17): linear fit = 1.00 x + 0.0 (2263 voxels, peak = 64), gca=64.0
gca peak = 0.08321 (100)
mri peak = 0.07659 (98)
Right_Cerebral_White_Matter (41): linear fit = 1.00 x + 0.0 (127041 voxels, overlap=0.789)
Right_Cerebral_White_Matter (41): linear fit = 1.00 x + 0.0 (127041 voxels, peak = 100), gca=100.5
gca peak = 0.08128 (101)
mri peak = 0.07633 (100)
Left_Cerebral_White_Matter (2): linear fit = 1.00 x + 0.0 (119481 voxels, overlap=0.786)
Left_Cerebral_White_Matter (2): linear fit = 1.00 x + 0.0 (119481 voxels, peak = 101), gca=101.0
gca peak = 0.09145 (61)
mri peak = 0.03782 (61)
Left_Cerebral_Cortex (3): linear fit = 1.02 x + 0.0 (69812 voxels, overlap=0.937)
Left_Cerebral_Cortex (3): linear fit = 1.02 x + 0.0 (69812 voxels, peak = 63), gca=62.5
gca peak = 0.11101 (60)
mri peak = 0.03394 (56)
Right_Cerebral_Cortex (42): linear fit = 1.02 x + 0.0 (66804 voxels, overlap=0.934)
Right_Cerebral_Cortex (42): linear fit = 1.02 x + 0.0 (66804 voxels, peak = 62), gca=61.5
gca peak = 0.27797 (66)
mri peak = 0.13132 (68)
Right_Caudate (50): linear fit = 1.00 x + 0.0 (2688 voxels, overlap=1.002)
Right_Caudate (50): linear fit = 1.00 x + 0.0 (2688 voxels, peak = 66), gca=66.0
gca peak = 0.13581 (62)
mri peak = 0.13304 (69)
Left_Caudate (11): linear fit = 1.00 x + 0.0 (2751 voxels, overlap=1.000)
Left_Caudate (11): linear fit = 1.00 x + 0.0 (2751 voxels, peak = 62), gca=62.0
gca peak = 0.12251 (64)
mri peak = 0.03740 (62)
Left_Cerebellum_Cortex (8): linear fit = 0.99 x + 0.0 (42347 voxels, overlap=0.997)
Left_Cerebellum_Cortex (8): linear fit = 0.99 x + 0.0 (42347 voxels, peak = 63), gca=63.0
gca peak = 0.12666 (67)
mri peak = 0.03283 (68)
Right_Cerebellum_Cortex (47): linear fit = 0.99 x + 0.0 (38959 voxels, overlap=0.961)
Right_Cerebellum_Cortex (47): linear fit = 0.99 x + 0.0 (38959 voxels, peak = 66), gca=66.0
gca peak = 0.15314 (90)
mri peak = 0.10210 (89)
Left_Cerebellum_White_Matter (7): linear fit = 0.99 x + 0.0 (13438 voxels, overlap=0.953)
Left_Cerebellum_White_Matter (7): linear fit = 0.99 x + 0.0 (13438 voxels, peak = 89), gca=88.7
gca peak = 0.15349 (91)
mri peak = 0.10475 (91)
Right_Cerebellum_White_Matter (46): linear fit = 1.00 x + 0.0 (10851 voxels, overlap=0.940)
Right_Cerebellum_White_Matter (46): linear fit = 1.00 x + 0.0 (10851 voxels, peak = 91), gca=90.5
gca peak = 0.27863 (65)
mri peak = 0.10987 (66)
Left_Amygdala (18): linear fit = 1.00 x + 0.0 (1206 voxels, overlap=1.020)
Left_Amygdala (18): linear fit = 1.00 x + 0.0 (1206 voxels, peak = 65), gca=65.0
gca peak = 0.27101 (69)
mri peak = 0.12025 (69)
Right_Amygdala (54): linear fit = 0.99 x + 0.0 (1447 voxels, overlap=0.989)
Right_Amygdala (54): linear fit = 0.99 x + 0.0 (1447 voxels, peak = 68), gca=68.0
gca peak = 0.10287 (96)
mri peak = 0.05927 (94)
Left_Thalamus (10): linear fit = 1.00 x + 0.0 (11379 voxels, overlap=0.946)
Left_Thalamus (10): linear fit = 1.00 x + 0.0 (11379 voxels, peak = 96), gca=96.5
gca peak = 0.10160 (90)
mri peak = 0.05560 (93)
Right_Thalamus (49): linear fit = 1.01 x + 0.0 (9793 voxels, overlap=0.995)
Right_Thalamus (49): linear fit = 1.01 x + 0.0 (9793 voxels, peak = 91), gca=91.3
gca peak = 0.08292 (82)
mri peak = 0.06188 (81)
Left_Putamen (12): linear fit = 1.00 x + 0.0 (4954 voxels, overlap=0.974)
Left_Putamen (12): linear fit = 1.00 x + 0.0 (4954 voxels, peak = 82), gca=82.0
gca peak = 0.08618 (78)
mri peak = 0.05809 (76)
Right_Putamen (51): linear fit = 1.00 x + 0.0 (6026 voxels, overlap=1.000)
Right_Putamen (51): linear fit = 1.00 x + 0.0 (6026 voxels, peak = 78), gca=78.0
gca peak = 0.07662 (88)
mri peak = 0.07365 (90)
Brain_Stem (16): linear fit = 0.99 x + 0.0 (24152 voxels, overlap=0.816)
Brain_Stem (16): linear fit = 0.99 x + 0.0 (24152 voxels, peak = 87), gca=86.7
gca peak = 0.14835 (105)
mri peak = 0.07240 (103)
Right_VentralDC (60): linear fit = 1.00 x + 0.0 (3494 voxels, overlap=0.859)
Right_VentralDC (60): linear fit = 1.00 x + 0.0 (3494 voxels, peak = 106), gca=105.5
gca peak = 0.16771 (99)
mri peak = 0.07404 (100)
Left_VentralDC (28): linear fit = 1.00 x + 0.0 (3752 voxels, overlap=0.879)
Left_VentralDC (28): linear fit = 1.00 x + 0.0 (3752 voxels, peak = 99), gca=99.5
gca peak = 0.32031 (10)
mri peak = 0.16137 (10)
Third_Ventricle (14): linear fit = 1.15 x + 0.0 (53 voxels, overlap=0.872)
Third_Ventricle (14): linear fit = 1.15 x + 0.0 (53 voxels, peak = 12), gca=11.5
gca peak = 0.46125 ( 6)
mri peak = 0.24390 ( 9)
Fourth_Ventricle (15): linear fit = 1.26 x + 0.0 (856 voxels, overlap=0.830)
Fourth_Ventricle (15): linear fit = 1.26 x + 0.0 (856 voxels, peak =  8), gca=7.6
gca peak Unknown = 0.94777 ( 0)
gca peak Left_Inf_Lat_Vent = 0.19610 (32)
gca peak CSF = 0.27810 (15)
gca peak Left_Accumbens_area = 0.70441 (56)
gca peak Left_undetermined = 1.00000 (28)
gca peak Left_vessel = 0.89837 (53)
gca peak Left_choroid_plexus = 0.11689 (35)
gca peak Right_Inf_Lat_Vent = 0.28947 (25)
gca peak Right_Accumbens_area = 0.31657 (64)
gca peak Right_vessel = 0.77268 (52)
gca peak Right_choroid_plexus = 0.13275 (38)
gca peak Fifth_Ventricle = 0.92085 (13)
gca peak WM_hypointensities = 0.10517 (74)
gca peak non_WM_hypointensities = 0.14031 (39)
gca peak Optic_Chiasm = 0.53534 (76)
not using caudate to estimate GM means
estimating mean gm scale to be 1.01 x + 0.0
estimating mean wm scale to be 1.00 x + 0.0
estimating mean csf scale to be 0.80 x + 0.0
saving intensity scales to aseg.auto_noCCseg.label_intensities.txt
saving sequentially combined intensity scales to aseg.auto_noCCseg.label_intensities.txt
147700 voxels changed in iteration 0 of unlikely voxel relabeling
936 voxels changed in iteration 1 of unlikely voxel relabeling
43 voxels changed in iteration 2 of unlikely voxel relabeling
18 voxels changed in iteration 3 of unlikely voxel relabeling
0 voxels changed in iteration 4 of unlikely voxel relabeling
107446 gm and wm labels changed (%26 to gray, %74 to white out of all changed labels)
672 hippocampal voxels changed.
1 amygdala voxels changed.
Reclassifying using Gibbs Priors
pass 1: 131189 changed. image ll: -2.260, PF=0.500
pass 2: 40094 changed. image ll: -2.259, PF=0.500
pass 3: 14690 changed.
pass 4: 6448 changed.
pass 5: 3359 changed.
112890 voxels changed in iteration 0 of unlikely voxel relabeling
659 voxels changed in iteration 1 of unlikely voxel relabeling
16 voxels changed in iteration 2 of unlikely voxel relabeling
0 voxels changed in iteration 3 of unlikely voxel relabeling
17298 voxels changed in iteration 0 of unlikely voxel relabeling
275 voxels changed in iteration 1 of unlikely voxel relabeling
6 voxels changed in iteration 2 of unlikely voxel relabeling
0 voxels changed in iteration 3 of unlikely voxel relabeling
19479 voxels changed in iteration 0 of unlikely voxel relabeling
182 voxels changed in iteration 1 of unlikely voxel relabeling
26 voxels changed in iteration 2 of unlikely voxel relabeling
0 voxels changed in iteration 3 of unlikely voxel relabeling
20220 voxels changed in iteration 0 of unlikely voxel relabeling
56 voxels changed in iteration 1 of unlikely voxel relabeling
2 voxels changed in iteration 2 of unlikely voxel relabeling
0 voxels changed in iteration 3 of unlikely voxel relabeling
 !!!!!!!!! ventricle segment 1 with volume 3968 above threshold 100 - not erasing !!!!!!!!!!
 !!!!!!!!! ventricle segment 0 with volume 101 above threshold 100 - not erasing !!!!!!!!!!
 !!!!!!!!! ventricle segment 1 with volume 163 above threshold 100 - not erasing !!!!!!!!!!
 !!!!!!!!! ventricle segment 2 with volume 110 above threshold 100 - not erasing !!!!!!!!!!
 !!!!!!!!! ventricle segment 2 with volume 3288 above threshold 100 - not erasing !!!!!!!!!!
 !!!!!!!!! ventricle segment 2 with volume 113 above threshold 100 - not erasing !!!!!!!!!!
 !!!!!!!!! ventricle segment 3 with volume 261 above threshold 100 - not erasing !!!!!!!!!!
writing labeled volume to aseg.auto_noCCseg.mgz
mri_ca_label utimesec    3798.476801
mri_ca_label stimesec    22.640498
mri_ca_label ru_maxrss   3254544
mri_ca_label ru_ixrss    0
mri_ca_label ru_idrss    0
mri_ca_label ru_isrss    0
mri_ca_label ru_minflt   21743613
mri_ca_label ru_majflt   7
mri_ca_label ru_nswap    0
mri_ca_label ru_inblock  964
mri_ca_label ru_oublock  1160
mri_ca_label ru_msgsnd   0
mri_ca_label ru_msgrcv   0
mri_ca_label ru_nsignals 0
mri_ca_label ru_nvcsw    1340
mri_ca_label ru_nivcsw   1935304
auto-labeling took 56 minutes and 34 seconds.
#--------------------------------------
#@# CC Seg Wed Sep 20 17:59:21 EDT 2023

 mri_cc -aseg aseg.auto_noCCseg.mgz -o aseg.auto.mgz -lta /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/cc_up.lta sub-24563 

will read input aseg from aseg.auto_noCCseg.mgz
writing aseg with cc labels to aseg.auto.mgz
will write lta as /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/cc_up.lta
reading aseg from /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/aseg.auto_noCCseg.mgz
reading norm from /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/norm.mgz
67834 voxels in left wm, 185979 in right wm, xrange [146, 165]
searching rotation angles z=[-8  6], y=[-10  4]

searching scale 1 Z rot -8.2  
searching scale 1 Z rot -7.9  
searching scale 1 Z rot -7.7  
searching scale 1 Z rot -7.4  
searching scale 1 Z rot -7.2  
searching scale 1 Z rot -6.9  
searching scale 1 Z rot -6.7  
searching scale 1 Z rot -6.4  
searching scale 1 Z rot -6.2  
searching scale 1 Z rot -5.9  
searching scale 1 Z rot -5.7  
searching scale 1 Z rot -5.4  
searching scale 1 Z rot -5.2  
searching scale 1 Z rot -4.9  
searching scale 1 Z rot -4.7  
searching scale 1 Z rot -4.4  
searching scale 1 Z rot -4.2  
searching scale 1 Z rot -3.9  
searching scale 1 Z rot -3.7  
searching scale 1 Z rot -3.4  
searching scale 1 Z rot -3.2  
searching scale 1 Z rot -2.9  
searching scale 1 Z rot -2.7  
searching scale 1 Z rot -2.4  
searching scale 1 Z rot -2.2  
searching scale 1 Z rot -1.9  
searching scale 1 Z rot -1.7  
searching scale 1 Z rot -1.4  
searching scale 1 Z rot -1.2  
searching scale 1 Z rot -0.9  
searching scale 1 Z rot -0.7  
searching scale 1 Z rot -0.4  
searching scale 1 Z rot -0.2  
searching scale 1 Z rot 0.1  
searching scale 1 Z rot 0.3  
searching scale 1 Z rot 0.6  
searching scale 1 Z rot 0.8  
searching scale 1 Z rot 1.1  
searching scale 1 Z rot 1.3  
searching scale 1 Z rot 1.6  
searching scale 1 Z rot 1.8  
searching scale 1 Z rot 2.1  
searching scale 1 Z rot 2.3  
searching scale 1 Z rot 2.6  
searching scale 1 Z rot 2.8  
searching scale 1 Z rot 3.1  
searching scale 1 Z rot 3.3  
searching scale 1 Z rot 3.6  
searching scale 1 Z rot 3.8  
searching scale 1 Z rot 4.1  
searching scale 1 Z rot 4.3  
searching scale 1 Z rot 4.6  
searching scale 1 Z rot 4.8  
searching scale 1 Z rot 5.1  
searching scale 1 Z rot 5.3  
searching scale 1 Z rot 5.6  
searching scale 1 Z rot 5.8  
searching scale 1 Z rot 6.1  
searching scale 1 Z rot 6.3  
searching scale 1 Z rot 6.6  global minimum found at slice 159.0, rotations (-2.13, -0.15)
final transformation (x=159.0, yr=-2.130, zr=-0.152):
 0.99931   0.00265  -0.03717  -26.50846;
-0.00265   1.00000   0.00010   0.40872;
 0.03717   0.00000   0.99931  -4.82168;
 0.00000   0.00000   0.00000   1.00000;
updating x range to be [120, 132] in xformed coordinates
best xformed slice 128
min_x_fornix = 149
min_x_fornix = 156
min_x_fornix = 164
min_x_fornix = 164
min_x_fornix = 151
cc center is found at 128 128 127
eigenvectors:
-0.00007  -0.00023   1.00000;
-0.01687  -0.99986  -0.00023;
 0.99986  -0.01687   0.00007;
writing aseg with callosum to /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/aseg.auto.mgz...
corpus callosum segmentation took 1.2 minutes
#VMPC# mri_cc VmPeak  1937088
mri_cc done
#--------------------------------------
#@# Merge ASeg Wed Sep 20 18:00:31 EDT 2023

 cp aseg.auto.mgz aseg.presurf.mgz 

#--------------------------------------------
#@# Intensity Normalization2 Wed Sep 20 18:00:31 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri

 mri_normalize -seed 1234 -mprage -aseg aseg.presurf.mgz -mask brainmask.mgz norm.mgz brain.mgz 

setting seed for random number genererator to 1234
assuming input volume is MGH (Van der Kouwe) MP-RAGE
using segmentation for initial intensity normalization
using MR volume brainmask.mgz to mask input volume...
reading mri_src from norm.mgz...
Reading aseg aseg.presurf.mgz
normalizing image...
NOT doing gentle normalization with control points/label
processing with aseg
removing outliers in the aseg WM...
1369 control points removed
Building bias image
building Voronoi diagram...
performing soap bubble smoothing, sigma = 0...
Smoothing with sigma 8
Applying bias correction
building Voronoi diagram...
performing soap bubble smoothing, sigma = 8...

Iterating 2 times
---------------------------------
3d normalization pass 1 of 2
white matter peak found at 110
white matter peak found at 109
gm peak at 68 (68), valley at 21 (21)
csf peak at 35, setting threshold to 57
building Voronoi diagram...
performing soap bubble smoothing, sigma = 8...
---------------------------------
3d normalization pass 2 of 2
white matter peak found at 109
white matter peak found at 110
gm peak at 66 (66), valley at 20 (20)
csf peak at 33, setting threshold to 55
building Voronoi diagram...
performing soap bubble smoothing, sigma = 8...
Done iterating ---------------------------------
writing output to brain.mgz
3D bias adjustment took 4 minutes and 30 seconds.
#--------------------------------------------
#@# Mask BFS Wed Sep 20 18:05:02 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri

 mri_mask -T 5 brain.mgz brainmask.mgz brain.finalsurfs.mgz 

threshold mask volume at 5
DoAbs = 0
Found 2860409 voxels in mask (pct=  8.73)
Writing masked volume to brain.finalsurfs.mgz...done.
#--------------------------------------------
#@# WM Segmentation Wed Sep 20 18:05:04 EDT 2023

 AntsDenoiseImageFs -i brain.mgz -o antsdn.brain.mgz 


 mri_segment -wsizemm 13 -mprage antsdn.brain.mgz wm.seg.mgz 

wsizemm = 13, voxres = 0.799995, wsize = 16
Widening wm low from 89 to 79
assuming input volume is MGH (Van der Kouwe) MP-RAGE
wm mean:  110
wsize:    16
wm low:   79
wm hi:    125
gray low: 30
gray hi:  99
Doing initial trinary intensity segmentation 
Using local statistics to label ambiguous voxels
Autodetecting stats
Computing class statistics for intensity windows...
CCS WM (105.0): 104.6 +- 5.7 [79.0 --> 125.0]
CCS GM (74.0) : 73.4 +- 10.1 [30.0 --> 95.0]
 white_mean 104.556
 white_sigma 5.68649
 gray_mean 73.3788
 gray_sigma 10.0633
setting bottom of white matter range wm_low to 83.4
setting top of gray matter range gray_hi to 93.5
 wm_low 83.4421
 wm_hi  125
 gray_low 30
 gray_hi  93.5053
Redoing initial intensity segmentation...
Recomputing local statistics to label ambiguous voxels...
 wm_low 83.4421
 wm_hi  125
 gray_low 30
 gray_hi  93.5053
using local geometry to label remaining ambiguous voxels...
polvwsize = 5, polvlen = 3, gray_hi = 93.5053, wm_low = 83.4421
MRIcpolvMedianCurveSegment(): wsize=5, len=3, gmhi=93.5053, wmlow=83.4421
    258712 voxels processed (0.79%)
    114498 voxels white (0.35%)
    144214 voxels non-white (0.44%)

Reclassifying voxels using Gaussian border classifier niter=1
MRIreclassify(): wm_low=78.4421, gray_hi=93.5053, wsize=16
    452813 voxels tested (1.38%)
     90551 voxels changed (0.28%)
    110599 multi-scale searches  (0.34%)
Recovering bright white
MRIrecoverBrightWhite()
 wm_low 83.4421
 wm_hi 125
 slack 5.68649
 pct_thresh 0.33
 intensity_thresh 130.686
 nvox_thresh 8.58
      657 voxels tested (0.00%)
      633 voxels changed (0.00%)

removing voxels with positive offset direction...
MRIremoveWrongDirection() wsize=3, lowthr=78.4421, hithr=93.5053
  smoothing input volume with sigma = 0.250
   149817 voxels tested (0.46%)
    29321 voxels changed (0.09%)
thicken = 1
removing 1-dimensional structures...
MRIremove1dStructures(): max_iter=10000, thresh=2, WM_MIN_VAL=5
 5613 sparsely connected voxels removed in 1 iterations
thickening thin strands....
thickness 4
nsegments 20
wm_hi 125
3852 diagonally connected voxels added...
MRIthickenThinWMStrands(): thickness=4, nsegments=20
  20 segments, 4790 filled
MRIfindBrightNonWM(): 171 bright non-wm voxels segmented.
MRIfilterMorphology() WM_MIN_VAL=5, DIAGONAL_FILL=230
white matter segmentation took 1.9 minutes
writing output to wm.seg.mgz...

 mri_edit_wm_with_aseg -keep-in wm.seg.mgz brain.mgz aseg.presurf.mgz wm.asegedit.mgz 

preserving editing changes in input volume...
auto filling took 0.74 minutes
reading wm segmentation from wm.seg.mgz...
0 voxels added to wm to prevent paths from MTL structures to cortex
8309 additional wm voxels added
0 additional wm voxels added
SEG EDIT: 77377 voxels turned on, 82451 voxels turned off.
propagating editing to output volume from wm.seg.mgz
writing edited volume to wm.asegedit.mgz....

 mri_pretess wm.asegedit.mgz wm norm.mgz wm.mgz 


Iteration Number : 1
pass   1 (xy+):  52 found -  52 modified     |    TOTAL:  52
pass   2 (xy+):   0 found -  52 modified     |    TOTAL:  52
pass   1 (xy-):  39 found -  39 modified     |    TOTAL:  91
pass   2 (xy-):   0 found -  39 modified     |    TOTAL:  91
pass   1 (yz+):  46 found -  46 modified     |    TOTAL: 137
pass   2 (yz+):   0 found -  46 modified     |    TOTAL: 137
pass   1 (yz-):  40 found -  40 modified     |    TOTAL: 177
pass   2 (yz-):   0 found -  40 modified     |    TOTAL: 177
pass   1 (xz+):  44 found -  44 modified     |    TOTAL: 221
pass   2 (xz+):   0 found -  44 modified     |    TOTAL: 221
pass   1 (xz-):  32 found -  32 modified     |    TOTAL: 253
pass   2 (xz-):   0 found -  32 modified     |    TOTAL: 253
Iteration Number : 1
pass   1 (+++):  21 found -  21 modified     |    TOTAL:  21
pass   2 (+++):   0 found -  21 modified     |    TOTAL:  21
pass   1 (+++):  34 found -  34 modified     |    TOTAL:  55
pass   2 (+++):   0 found -  34 modified     |    TOTAL:  55
pass   1 (+++):  47 found -  47 modified     |    TOTAL: 102
pass   2 (+++):   0 found -  47 modified     |    TOTAL: 102
pass   1 (+++):  32 found -  32 modified     |    TOTAL: 134
pass   2 (+++):   0 found -  32 modified     |    TOTAL: 134
Iteration Number : 1
pass   1 (++): 134 found - 134 modified     |    TOTAL: 134
pass   2 (++):   0 found - 134 modified     |    TOTAL: 134
pass   1 (+-): 155 found - 155 modified     |    TOTAL: 289
pass   2 (+-):   0 found - 155 modified     |    TOTAL: 289
pass   1 (--): 125 found - 125 modified     |    TOTAL: 414
pass   2 (--):   1 found - 126 modified     |    TOTAL: 415
pass   3 (--):   0 found - 126 modified     |    TOTAL: 415
pass   1 (-+): 137 found - 137 modified     |    TOTAL: 552
pass   2 (-+):   0 found - 137 modified     |    TOTAL: 552
Iteration Number : 2
pass   1 (xy+):  18 found -  18 modified     |    TOTAL:  18
pass   2 (xy+):   0 found -  18 modified     |    TOTAL:  18
pass   1 (xy-):  16 found -  16 modified     |    TOTAL:  34
pass   2 (xy-):   0 found -  16 modified     |    TOTAL:  34
pass   1 (yz+):   8 found -   8 modified     |    TOTAL:  42
pass   2 (yz+):   0 found -   8 modified     |    TOTAL:  42
pass   1 (yz-):   7 found -   7 modified     |    TOTAL:  49
pass   2 (yz-):   0 found -   7 modified     |    TOTAL:  49
pass   1 (xz+):   9 found -   9 modified     |    TOTAL:  58
pass   2 (xz+):   0 found -   9 modified     |    TOTAL:  58
pass   1 (xz-):  14 found -  14 modified     |    TOTAL:  72
pass   2 (xz-):   0 found -  14 modified     |    TOTAL:  72
Iteration Number : 2
pass   1 (+++):   0 found -   0 modified     |    TOTAL:   0
pass   1 (+++):   6 found -   6 modified     |    TOTAL:   6
pass   2 (+++):   0 found -   6 modified     |    TOTAL:   6
pass   1 (+++):   2 found -   2 modified     |    TOTAL:   8
pass   2 (+++):   0 found -   2 modified     |    TOTAL:   8
pass   1 (+++):   6 found -   6 modified     |    TOTAL:  14
pass   2 (+++):   0 found -   6 modified     |    TOTAL:  14
Iteration Number : 2
pass   1 (++):   9 found -   9 modified     |    TOTAL:   9
pass   2 (++):   0 found -   9 modified     |    TOTAL:   9
pass   1 (+-):   5 found -   5 modified     |    TOTAL:  14
pass   2 (+-):   0 found -   5 modified     |    TOTAL:  14
pass   1 (--):   8 found -   8 modified     |    TOTAL:  22
pass   2 (--):   0 found -   8 modified     |    TOTAL:  22
pass   1 (-+):   4 found -   4 modified     |    TOTAL:  26
pass   2 (-+):   0 found -   4 modified     |    TOTAL:  26
Iteration Number : 3
pass   1 (xy+):   1 found -   1 modified     |    TOTAL:   1
pass   2 (xy+):   0 found -   1 modified     |    TOTAL:   1
pass   1 (xy-):   0 found -   0 modified     |    TOTAL:   1
pass   1 (yz+):   0 found -   0 modified     |    TOTAL:   1
pass   1 (yz-):   1 found -   1 modified     |    TOTAL:   2
pass   2 (yz-):   0 found -   1 modified     |    TOTAL:   2
pass   1 (xz+):   0 found -   0 modified     |    TOTAL:   2
pass   1 (xz-):   1 found -   1 modified     |    TOTAL:   3
pass   2 (xz-):   0 found -   1 modified     |    TOTAL:   3
Iteration Number : 3
pass   1 (+++):   0 found -   0 modified     |    TOTAL:   0
pass   1 (+++):   0 found -   0 modified     |    TOTAL:   0
pass   1 (+++):   0 found -   0 modified     |    TOTAL:   0
pass   1 (+++):   0 found -   0 modified     |    TOTAL:   0
Iteration Number : 3
pass   1 (++):   0 found -   0 modified     |    TOTAL:   0
pass   1 (+-):   0 found -   0 modified     |    TOTAL:   0
pass   1 (--):   0 found -   0 modified     |    TOTAL:   0
pass   1 (-+):   0 found -   0 modified     |    TOTAL:   0
Iteration Number : 4
pass   1 (xy+):   0 found -   0 modified     |    TOTAL:   0
pass   1 (xy-):   0 found -   0 modified     |    TOTAL:   0
pass   1 (yz+):   0 found -   0 modified     |    TOTAL:   0
pass   1 (yz-):   0 found -   0 modified     |    TOTAL:   0
pass   1 (xz+):   0 found -   0 modified     |    TOTAL:   0
pass   1 (xz-):   0 found -   0 modified     |    TOTAL:   0
Iteration Number : 4
pass   1 (+++):   0 found -   0 modified     |    TOTAL:   0
pass   1 (+++):   0 found -   0 modified     |    TOTAL:   0
pass   1 (+++):   0 found -   0 modified     |    TOTAL:   0
pass   1 (+++):   0 found -   0 modified     |    TOTAL:   0
Iteration Number : 4
pass   1 (++):   0 found -   0 modified     |    TOTAL:   0
pass   1 (+-):   0 found -   0 modified     |    TOTAL:   0
pass   1 (--):   0 found -   0 modified     |    TOTAL:   0
pass   1 (-+):   0 found -   0 modified     |    TOTAL:   0

Total Number of Modified Voxels = 1054 (out of 1126907: 0.093530)
binarizing input wm segmentation...
Ambiguous edge configurations... 

mri_pretess done

#--------------------------------------------
#@# Fill Wed Sep 20 18:08:41 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri

 mri_fill -a ../scripts/ponscc.cut.log -xform transforms/talairach.lta -segmentation aseg.presurf.mgz -ctab /opt/freesurfer/SubCorticalMassLUT.txt wm.mgz filled.mgz 

logging cutting plane coordinates to ../scripts/ponscc.cut.log...
INFO: Using transforms/talairach.lta and its offset for Talairach volume ...
using segmentation aseg.presurf.mgz...
reading input volume...done.
searching for cutting planes...voxel to talairach voxel transform
 1.01514  -0.04840  -0.03938   7.70747;
 0.05132   1.12258   0.18334  -47.40198;
 0.03158  -0.17332   1.02006   13.61655;
 0.00000   0.00000   0.00000   1.00000;
voxel to talairach voxel transform
 1.01514  -0.04840  -0.03938   7.70747;
 0.05132   1.12258   0.18334  -47.40198;
 0.03158  -0.17332   1.02006   13.61655;
 0.00000   0.00000   0.00000   1.00000;
reading segmented volume aseg.presurf.mgz
removing CC from segmentation
Looking for area (min, max) = (546, 2188)
area[0] = 1679 (min = 546, max = 2188), aspect = 0.50 (min = 0.10, max = 0.75)
no need to search
using seed (157, 150, 186), TAL = (2.4, 20.8, 8.0)
talairach voxel to voxel transform
 0.98180   0.04688   0.02948  -5.74643;
-0.03884   0.86490  -0.15695   43.43430;
-0.03699   0.14550   0.95275  -5.79089;
 0.00000   0.00000   0.00000   1.00000;
segmentation indicates cc at (157,  150,  186) --> (2.4, 20.8, 8.0)
done.
filling took 1.4 minutes
talairach cc position changed to (2.40, 20.80, 8.00)
Erasing brainstem...done.
seed_search_size = 12, min_neighbors = 5
search rh wm seed point around talairach space:(20.40, 20.80, 8.00) SRC: (138.82, 138.75, 188.27)
search lh wm seed point around talairach space (-15.60, 20.80, 8.00), SRC: (183.00, 137.00, 186.61)
compute mri_fill using aseg
Erasing Brain Stem and Cerebellum ...
Define left and right masks using aseg:
Building Voronoi diagram ...
Using the Voronoi diagram for separating WM into two hemispheres ...
Find the largest connected component for each hemisphere ...
Embedding colortable
mri_fill done, writing output to filled.mgz...
 cp filled.mgz filled.auto.mgz

Started at Wed Sep 20 16:10:37 EDT 2023 
Ended   at Wed Sep 20 18:10:05 EDT 2023
#@#%# recon-all-run-time-hours 1.991
recon-all -s sub-24563 finished without error at Wed Sep 20 18:10:05 EDT 2023
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

