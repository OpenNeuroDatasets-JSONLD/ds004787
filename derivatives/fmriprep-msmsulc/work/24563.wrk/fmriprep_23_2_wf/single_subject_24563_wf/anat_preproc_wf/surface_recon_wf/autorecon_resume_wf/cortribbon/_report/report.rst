Node: single_subject_24563_wf (anat_preproc_wf (surface_recon_wf (autorecon_resume_wf (cortribbon (freesurfer)
==============================================================================================================


 Hierarchy : fmriprep_23_2_wf.single_subject_24563_wf.anat_preproc_wf.surface_recon_wf.autorecon_resume_wf.cortribbon
 Exec ID : cortribbon


Original Inputs
---------------


* FLAIR_file : <undefined>
* T1_files : <undefined>
* T2_file : <undefined>
* args : <undefined>
* big_ventricles : <undefined>
* brainstem : <undefined>
* directive : <undefined>
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
* openmp : <undefined>
* parallel : True
* steps : ['cortribbon']
* subject_id : sub-24563
* subjects_dir : /lscratch/8536404/24563.out/sourcedata/freesurfer
* talairach : <undefined>
* use_FLAIR : False
* use_T2 : True
* xopts : <undefined>


Execution Inputs
----------------


* FLAIR_file : <undefined>
* T1_files : <undefined>
* T2_file : <undefined>
* args : <undefined>
* big_ventricles : <undefined>
* brainstem : <undefined>
* directive : <undefined>
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
* openmp : <undefined>
* parallel : True
* steps : ['cortribbon']
* subject_id : sub-24563
* subjects_dir : /lscratch/8536404/24563.out/sourcedata/freesurfer
* talairach : <undefined>
* use_FLAIR : False
* use_T2 : True
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


* cmdline : recon-all -parallel -subjid sub-24563 -sd /lscratch/8536404/24563.out/sourcedata/freesurfer -T2pial -cortribbon
* duration : 5888.289494
* hostname : cn4271
* prev_wd : /vf/users/EDB/TMSpilot/code
* working_dir : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/autorecon_resume_wf/cortribbon


Terminal output
~~~~~~~~~~~~~~~


 


Terminal - standard output
~~~~~~~~~~~~~~~~~~~~~~~~~~


 fs-check-version --s sub-24563 --o /lscratch/8536404/tmp.b8Ly3U
Wed Sep 20 22:27:39 EDT 2023

setenv SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
cd /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/autorecon_resume_wf/cortribbon
/opt/freesurfer/bin/fs-check-version --s sub-24563 --o /lscratch/8536404/tmp.b8Ly3U
-rwxrwxr-x 1 root root 18565 Aug  4  2022 /opt/freesurfer/bin/fs-check-version

freesurfer-linux-ubuntu22_x86_64-7.3.2-20220804-6354275
$Id$
Linux cn4271 4.18.0-425.19.2.el8_7.x86_64 #1 SMP Tue Apr 4 22:38:11 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
pid 886443
Current FS Version freesurfer-linux-ubuntu22_x86_64-7.3.2-20220804-6354275
bstampfile exists /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/scripts/build-stamp.txt
Subject FS Version: freesurfer-linux-ubuntu22_x86_64-7.3.2-20220804-6354275
No constraints on version because REQ=UnSet and FsVerFile=NotThere
#@#% fs-check-version match = 1
fs-check-version Done
INFO: SUBJECTS_DIR is /lscratch/8536404/24563.out/sourcedata/freesurfer
Actual FREESURFER_HOME /opt/freesurfer
-rw-rw-r-- 1 zugmana2 zugmana2 247234 Sep 20 18:10 /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/scripts/recon-all.log
Linux cn4271 4.18.0-425.19.2.el8_7.x86_64 #1 SMP Tue Apr 4 22:38:11 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563 
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563 
#--------------------------------------------
#@# Refine Pial Surfs w/ T2/FLAIR Wed Sep 20 22:27:40 EDT 2023

 bbregister --s sub-24563 --mov /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/T2raw.mgz --lta /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.auto.lta --init-coreg --T2 --gm-proj-abs 2 --wm-proj-abs 1 --no-coreg-ref-mask 

tmp /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663
Log file is /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.auto.log
Wed Sep 20 22:27:40 EDT 2023

setenv SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/scripts
/opt/freesurfer/bin/bbregister --s sub-24563 --mov /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/T2raw.mgz --lta /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.auto.lta --init-coreg --T2 --gm-proj-abs 2 --wm-proj-abs 1 --no-coreg-ref-mask

bbregister 7.3.2
Linux cn4271 4.18.0-425.19.2.el8_7.x86_64 #1 SMP Tue Apr 4 22:38:11 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
FREESURFER_HOME /opt/freesurfer
mri_convert /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/T2raw.mgz /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/template.nii
mri_convert /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/T2raw.mgz /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/template.nii 
reading from /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/T2raw.mgz...
TR=3206.00, TE=0.00, TI=0.00, flip angle=0.00
i_ras = (1, 0, 0)
j_ras = (0, 1, 0)
k_ras = (0, 0, 1)
writing to /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/template.nii...
mri_coreg --s sub-24563 --mov /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/template.nii --regdat /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/reg.init.dat --reg /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/mri_coreg.lta --nthreads 4 --dof 6 --sep 4 --ftol .0001 --linmintol .01 --no-ref-mask

$Id: mri_coreg.c,v 1.27 2016/04/30 15:11:49 greve Exp $
cwd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/scripts
cmdline mri_coreg --s sub-24563 --mov /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/template.nii --regdat /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/reg.init.dat --reg /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/mri_coreg.lta --nthreads 4 --dof 6 --sep 4 --ftol .0001 --linmintol .01 --no-ref-mask 
sysname  Linux
hostname cn4271
machine  x86_64
user     zugmana2
dof    6
nsep    1
cras0    1
ftol    0.000100
linmintol    0.010000
bf       1
bflim    30.000000
bfnsamp    30
SmoothRef 0
SatPct    99.990000
MovOOB 0
optschema 1
Seed 53
Reading in mov /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/template.nii
Reading in ref /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/brainmask.mgz
Setting cras translation parameters to align volume centers
Creating random numbers for coordinate dithering
Performing intensity dithering
Performing intensity dithering on mov with computed dither
Init matrix params  0.2540 -8.9650  6.0570  0.0000  0.0000  0.0000  1.0000  1.0000  1.0000  0.0000  0.0000  0.0000 
Initial parameters to be opt  0.2540 -8.9650  6.0570  0.0000  0.0000  0.0000 
Separation list (1):  4   min = 4
DoSmoothing 1
DoCoordDither 1
DoIntensityDither 1
nitersmax 4
ftol 1.000e-04
linmintol 1.000e-02
SatPct 99.990000
Hist FWHM 7.000000 7.000000
nthreads 4
movsat = 604.0000
mov gstd 1.9140 1.9381 1.9381
Smoothing mov
refsat = 145.0000
ref gstd 1.9140 1.9140 1.9140
Smoothing ref
COREGpreproc() done
Testing if mov and target overlap
Init cost   -1.0476466376
nhits = 392018 out of 32768000, Percent Overlap:  76.6
Initial  RefRAS-to-MovRAS
 1.00000   0.00000   0.00000   0.25396;
 0.00000   1.00000   0.00000  -8.96501;
 0.00000   0.00000   1.00000   6.05701;
 0.00000   0.00000   0.00000   1.00000;
Initial  RefVox-to-MovVox
-0.99999   0.00000   0.00000   281.99908;
 0.00000   0.00000   1.59999   0.30145;
 0.00000  -1.59999   0.00000   510.69855;
 0.00000   0.00000   0.00000   1.00000;
sep = 4 -----------------------------------
COREGoptBruteForce() 30 1 30
Turning on MovOOB for BruteForce Search
#BF# sep= 4 iter=0 lim=30.0 delta=2.00  -1.74604  -4.96501   2.05701  -2.00000   0.00000   4.00000   -1.0469261
Turning  MovOOB back off after brute force search


---------------------------------
Init Powel Params dof = 6: -1.746040 -4.965012 2.057007 -2.000000 0.000000 4.000000 
Starting OpenPowel2(), sep = 4
InitialCost        -1.0540767908 
#@#  4  188  -1.74604 -4.96501 2.05701 -2.00000 0.00000 4.00000   -1.0540768
fs_powell::minimize
  nparams 6
  maxfev 4
  ftol   0.000100
  linmin_xtol_   0.010000
  powell nthiter 0: fret = -1.054077
#@#  4  190  -0.74604 -4.96501 2.05701 -2.00000 0.00000 4.00000   -1.0541424
#@#  4  194  -1.12801 -4.96501 2.05701 -2.00000 0.00000 4.00000   -1.0542389
#@#  4  196  -1.15869 -4.96501 2.05701 -2.00000 0.00000 4.00000   -1.0542395
#@#  4  197  -1.16869 -4.96501 2.05701 -2.00000 0.00000 4.00000   -1.0542400
#@#  4  201  -1.16869 -6.58305 2.05701 -2.00000 0.00000 4.00000   -1.0549183
#@#  4  205  -1.16869 -6.34698 2.05701 -2.00000 0.00000 4.00000   -1.0549476
#@#  4  206  -1.16869 -6.32820 2.05701 -2.00000 0.00000 4.00000   -1.0549479
#@#  4  207  -1.16869 -6.31820 2.05701 -2.00000 0.00000 4.00000   -1.0549480
#@#  4  212  -1.16869 -6.31820 3.05701 -2.00000 0.00000 4.00000   -1.0550674
#@#  4  216  -1.16869 -6.31820 2.67504 -2.00000 0.00000 4.00000   -1.0551503
#@#  4  218  -1.16869 -6.31820 2.69312 -2.00000 0.00000 4.00000   -1.0551505
#@#  4  222  -1.16869 -6.31820 2.69312 -3.61803 0.00000 4.00000   -1.0553051
#@#  4  223  -1.16869 -6.31820 2.69312 -3.05589 0.00000 4.00000   -1.0553856
#@#  4  228  -1.16869 -6.31820 2.69312 -3.02424 0.00000 4.00000   -1.0553858
#@#  4  230  -1.16869 -6.31820 2.69312 -2.97002 0.00000 4.00000   -1.0553862
#@#  4  231  -1.16869 -6.31820 2.69312 -2.98485 0.00000 4.00000   -1.0553865
#@#  4  232  -1.16869 -6.31820 2.69312 -2.99485 0.00000 4.00000   -1.0553868
#@#  4  236  -1.16869 -6.31820 2.69312 -2.99485 -1.61803 4.00000   -1.0559467
#@#  4  240  -1.16869 -6.31820 2.69312 -2.99485 -1.38197 4.00000   -1.0559506
#@#  4  241  -1.16869 -6.31820 2.69312 -2.99485 -1.46980 4.00000   -1.0559546
#@#  4  249  -1.16869 -6.31820 2.69312 -2.99485 -1.46980 4.38197   -1.0560154
#@#  4  251  -1.16869 -6.31820 2.69312 -2.99485 -1.46980 4.40157   -1.0560160
  powell nthiter 1: fret = -1.056016
#@#  4  260  -1.12671 -6.31820 2.69312 -2.99485 -1.46980 4.40157   -1.0560170
#@#  4  262  -1.11671 -6.31820 2.69312 -2.99485 -1.46980 4.40157   -1.0560174
#@#  4  272  -1.11671 -6.38235 2.69312 -2.99485 -1.46980 4.40157   -1.0560187
#@#  4  274  -1.11671 -6.39432 2.69312 -2.99485 -1.46980 4.40157   -1.0560189
#@#  4  285  -1.11671 -6.39432 2.56274 -2.99485 -1.46980 4.40157   -1.0560311
#@#  4  294  -1.11671 -6.39432 2.56274 -2.96285 -1.46980 4.40157   -1.0560323
#@#  4  295  -1.11671 -6.39432 2.56274 -2.92576 -1.46980 4.40157   -1.0560324
#@#  4  296  -1.11671 -6.39432 2.56274 -2.94104 -1.46980 4.40157   -1.0560334
#@#  4  304  -1.11671 -6.39432 2.56274 -2.94104 -1.54522 4.40157   -1.0560360
Powell done niters total = 1
OptTimeSec 11.6 sec
OptTimeMin  0.19 min
nEvals 317
Final optimized parameters  -1.11671412  -6.39431620   2.56274414  -2.94103956  -1.54521883   4.40156794 
Final matrix parameters -1.1167 -6.3943  2.5627 -2.9410 -1.5452  4.4116  1.0000  1.0000  1.0000  0.0000  0.0000  0.0000 
Final cost   -1.056036017828111
 

---------------------------------
Final  RefRAS-to-MovRAS
 0.99669   0.07672  -0.02697  -1.11671;
-0.07802   0.99563  -0.05129  -6.39432;
 0.02291   0.05322   0.99832   2.56274;
 0.00000   0.00000   0.00000   1.00000;
Final  RefVox-to-MovVox
-0.99668   0.02697   0.07672   265.18695;
 0.12484   0.08206   1.59300  -26.10761;
-0.03666  -1.59730   0.08516   497.56348;
 0.00000   0.00000   0.00000   1.00000;
Final matrix parameters -1.1167 -6.3943  2.5627 -2.9410 -1.5452  4.4016  0.0000  0.0000  0.0000  0.0000  0.0000  0.0000 
Final opt parameters -1.1167 -6.3943  2.5627 -2.9410 -1.5452  4.4016 
nhits = 377777 out of 32768000, Percent Overlap:  73.8
mri_coreg RunTimeSec 170.7 sec
To check run:
   tkregisterfv --mov /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/template.nii --targ /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/brainmask.mgz --reg /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/mri_coreg.lta --s sub-24563 --surfs 

mri_coreg done

mri_segreg --mov /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/template.nii --init-reg /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/reg.init.dat --out-reg /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/bbr.pass1.dat --subsamp-brute 100 --subsamp 100 --tol 1e-4 --tol1d 1e-3 --brute -4 4 4 --surf white --gm-proj-abs 2 --gm-gt-wm 0.5
7.3.2
setenv SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/scripts
mri_segreg --mov /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/template.nii --init-reg /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/reg.init.dat --out-reg /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/bbr.pass1.dat --subsamp-brute 100 --subsamp 100 --tol 1e-4 --tol1d 1e-3 --brute -4 4 4 --surf white --gm-proj-abs 2 --gm-gt-wm 0.5 
sysname  Linux
hostname cn4271
machine  x86_64
user     zugmana2
movvol /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/template.nii
regfile /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/reg.init.dat
subject sub-24563
dof 6
outregfile /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/bbr.pass1.dat
UseMask 0
UseLH 1
UseRH 1
nsubsamp 100
PenaltySign  -1
PenaltySlope 0.500000
PenaltyCenter 0.000000
surfname white
GMProjAbs 2.000000
WMProjAbs 2.000000
lhcostfile (null)
rhcostfile (null)
interp  trilinear (1)
frame  0
TolPowell 0.000100
nMaxItersPowell 36
n1dmin  3
Profile   0
Gdiag_no  -1
AddNoise  0 (0)
SynthSeed 1696193779
TransRandMax 0.000000
RotRandMax 0.000000
Translations 0.000000 0.000000 0.000000
Rotations   0.000000 0.000000 0.000000
Input reg
-0.99669  -0.07672   0.02697   0.55428;
 0.02291   0.05322   0.99832  -3.12273;
 0.07802  -0.99563   0.05129  -2.93842;
 0.00000   0.00000   0.00000   1.00000;

Loading mov
ExcludeZeroVoxels 1
Reading in targ vol /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig.mgz
Projecting LH Surfs
Loading lh.white surf
GM Proj: 0 0.500000 2.000000
WM Proj: 0 0.500000 2.000000
Projecting RH Surfs
Loading rh.white surf
Projecting RH Surfs
Using lh.cortex.label
Using rh.cortex.label
Computing relative cost
 0  -25.0 -25.0 -25.0   0.996855
 1  -25.0 -25.0  25.0   1.006301
 2  -25.0  25.0 -25.0   1.030100
 3  -25.0  25.0  25.0   1.003302
 4   25.0 -25.0 -25.0   1.015099
 5   25.0 -25.0  25.0   0.992864
 6   25.0  25.0 -25.0   1.020793
 7   25.0  25.0  25.0   1.005074
REL:  8  0.349316    8.070388  1.008799 rel = 0.34627 
Initial costs ----------------
Number of surface hits 4817
WM  Intensity   191.6571 +/-  26.6281
Ctx Intensity   229.4312 +/-  46.0945
Pct Contrast     16.1877 +/-  27.5039
Cost   0.3493
RelCost   0.3463

------------------------------------
Brute force preopt -4 4 4, n = 729
     0  -4.0000  -4.0000  -4.0000  -4.0000  -4.0000  -4.0000      1.0054   1.0054  0.0
     2  -4.0000  -4.0000  -4.0000  -4.0000  -4.0000   4.0000      0.9953   0.9953  0.0
     3  -4.0000  -4.0000  -4.0000  -4.0000   0.0000  -4.0000      0.9946   0.9946  0.0
     4  -4.0000  -4.0000  -4.0000  -4.0000   0.0000   0.0000      0.9759   0.9759  0.0
     7  -4.0000  -4.0000  -4.0000  -4.0000   4.0000   0.0000      0.9101   0.9101  0.0
    15  -4.0000  -4.0000  -4.0000   0.0000   4.0000  -4.0000      0.8953   0.8953  0.0
    33  -4.0000  -4.0000   0.0000  -4.0000   4.0000  -4.0000      0.8808   0.8808  0.0
    57  -4.0000  -4.0000   4.0000  -4.0000   0.0000  -4.0000      0.8668   0.8668  0.0
   105  -4.0000   0.0000  -4.0000   4.0000   4.0000  -4.0000      0.8664   0.8664  0.0
   120  -4.0000   0.0000   0.0000   0.0000   0.0000  -4.0000      0.8163   0.8163  0.0
   274   0.0000  -4.0000   0.0000  -4.0000   0.0000   0.0000      0.7972   0.7972  0.0
   363   0.0000   0.0000   0.0000   0.0000   0.0000  -4.0000      0.7597   0.7597  0.0
   364   0.0000   0.0000   0.0000   0.0000   0.0000   0.0000      0.3493   0.3493  0.0
Brute Force --------------------------
Min cost was 0.349316
Number of iterations   729
Search time 2.139863 sec
Parameters at best (transmm, rotdeg)
  0.000   0.000   0.000  0.000  0.000  0.000 
--------------------------------------------

Starting Powell Minimization
Init Powel Params dof = 6
0 0
1 0
2 0
3 0
4 0
5 0
fs_powell::minimize
  nparams 6
  maxfev 36
  ftol   0.000100
  linmin_xtol_   0.001000
  powell nthiter 0: fret = 0.349316
   6  0.382  0.000  0.000  0.000  0.000  0.000   0.3411498826
  10  0.365  0.000  0.000  0.000  0.000  0.000   0.3411059800
  11  0.369  0.000  0.000  0.000  0.000  0.000   0.3411005482
  12  0.368  0.000  0.000  0.000  0.000  0.000   0.3410963845
  18  0.368 -0.618  0.000  0.000  0.000  0.000   0.3351783283
  20  0.368 -0.396  0.000  0.000  0.000  0.000   0.3304752871
  21  0.368 -0.371  0.000  0.000  0.000  0.000   0.3297286255
  24  0.368 -0.349  0.000  0.000  0.000  0.000   0.3296589152
  25  0.368 -0.357  0.000  0.000  0.000  0.000   0.3295834374
  34  0.368 -0.357  0.163  0.000  0.000  0.000   0.3281873811
  35  0.368 -0.357  0.153  0.000  0.000  0.000   0.3281751705
  37  0.368 -0.357  0.157  0.000  0.000  0.000   0.3281711922
  38  0.368 -0.357  0.156  0.000  0.000  0.000   0.3281709924
  46  0.368 -0.357  0.156 -0.107  0.000  0.000   0.3277555813
  47  0.368 -0.357  0.156 -0.076  0.000  0.000   0.3277048556
  49  0.368 -0.357  0.156 -0.047  0.000  0.000   0.3276751877
  51  0.368 -0.357  0.156 -0.060  0.000  0.000   0.3276194787
  53  0.368 -0.357  0.156 -0.058  0.000  0.000   0.3276139026
  54  0.368 -0.357  0.156 -0.057  0.000  0.000   0.3276137648
  63  0.368 -0.357  0.156 -0.057 -0.067  0.000   0.3266253392
  64  0.368 -0.357  0.156 -0.057 -0.071  0.000   0.3265808783
  66  0.368 -0.357  0.156 -0.057 -0.076  0.000   0.3265586473
  78  0.368 -0.357  0.156 -0.057 -0.076  0.036   0.3265070019
  80  0.368 -0.357  0.156 -0.057 -0.076  0.019   0.3264663893
  81  0.368 -0.357  0.156 -0.057 -0.076  0.022   0.3264518989
  82  0.368 -0.357  0.156 -0.057 -0.076  0.026   0.3264349470
  83  0.368 -0.357  0.156 -0.057 -0.076  0.030   0.3264328693
  84  0.368 -0.357  0.156 -0.057 -0.076  0.028   0.3264303478
  powell nthiter 1: fret = 0.326430
  95  0.282 -0.357  0.156 -0.057 -0.076  0.028   0.3251751045
  96  0.308 -0.357  0.156 -0.057 -0.076  0.028   0.3251729254
  97  0.295 -0.357  0.156 -0.057 -0.076  0.028   0.3250348934
  98  0.294 -0.357  0.156 -0.057 -0.076  0.028   0.3250325074
 106  0.294 -0.464  0.156 -0.057 -0.076  0.028   0.3248753693
 107  0.294 -0.419  0.156 -0.057 -0.076  0.028   0.3245359179
 109  0.294 -0.428  0.156 -0.057 -0.076  0.028   0.3245020301
 111  0.294 -0.430  0.156 -0.057 -0.076  0.028   0.3245000623
 112  0.294 -0.431  0.156 -0.057 -0.076  0.028   0.3244999163
 120  0.294 -0.431  0.192 -0.057 -0.076  0.028   0.3237767205
 122  0.294 -0.431  0.191 -0.057 -0.076  0.028   0.3237760323
 134  0.294 -0.431  0.191 -0.060 -0.076  0.028   0.3237525404
 136  0.294 -0.431  0.191 -0.059 -0.076  0.028   0.3237525073
 145  0.294 -0.431  0.191 -0.059 -0.064  0.028   0.3236142321
 149  0.294 -0.431  0.191 -0.059 -0.057  0.028   0.3235766702
 150  0.294 -0.431  0.191 -0.059 -0.053  0.028   0.3235749463
 151  0.294 -0.431  0.191 -0.059 -0.055  0.028   0.3235735379
 152  0.294 -0.431  0.191 -0.059 -0.056  0.028   0.3235733950
 161  0.294 -0.431  0.191 -0.059 -0.056 -0.061   0.3230885299
 162  0.294 -0.431  0.191 -0.059 -0.056 -0.040   0.3227472241
 164  0.294 -0.431  0.191 -0.059 -0.056 -0.032   0.3227220644
 166  0.294 -0.431  0.191 -0.059 -0.056 -0.033   0.3227216035
  powell nthiter 2: fret = 0.322722
 176  0.309 -0.431  0.191 -0.059 -0.056 -0.033   0.3225750112
 178  0.306 -0.431  0.191 -0.059 -0.056 -0.033   0.3225375435
 179  0.305 -0.431  0.191 -0.059 -0.056 -0.033   0.3225371044
 187  0.305 -0.482  0.191 -0.059 -0.056 -0.033   0.3222932012
 189  0.305 -0.461  0.191 -0.059 -0.056 -0.033   0.3222091139
 191  0.305 -0.464  0.191 -0.059 -0.056 -0.033   0.3221988260
 192  0.305 -0.471  0.191 -0.059 -0.056 -0.033   0.3221838743
 194  0.305 -0.470  0.191 -0.059 -0.056 -0.033   0.3221835536
 205  0.305 -0.470  0.180 -0.059 -0.056 -0.033   0.3220781984
 229  0.305 -0.470  0.180 -0.059 -0.054 -0.033   0.3220725463
 239  0.305 -0.470  0.180 -0.059 -0.054 -0.050   0.3219734541
 241  0.305 -0.470  0.180 -0.059 -0.054 -0.045   0.3219286402
  powell nthiter 3: fret = 0.321929
 265  0.305 -0.468  0.180 -0.059 -0.054 -0.045   0.3219264934
 289  0.305 -0.468  0.180 -0.061 -0.054 -0.045   0.3219257374
 301  0.305 -0.468  0.180 -0.061 -0.056 -0.045   0.3219107420
 314  0.305 -0.468  0.180 -0.061 -0.056 -0.046   0.3219094762
Powell done niters = 3
Computing relative cost
 0  -25.0 -25.0 -25.0   0.999201
 1  -25.0 -25.0  25.0   1.024660
 2  -25.0  25.0 -25.0   1.037162
 3  -25.0  25.0  25.0   0.995725
 4   25.0 -25.0 -25.0   1.017994
 5   25.0 -25.0  25.0   0.980880
 6   25.0  25.0 -25.0   1.011123
 7   25.0  25.0  25.0   1.015448
REL:  8  0.321909    8.082193  1.010274 rel = 0.318636 
Number of iterations     3
Min cost was 0.321909
Number of FunctionCalls   316
TolPowell 0.000100
nMaxItersPowell 36
OptimizationTime 0.703447 sec
Parameters at optimum (transmm)  0.30451 -0.46830  0.18015
Parameters at optimum (rotdeg) -0.06142 -0.05635 -0.04563 
Final costs ----------------
Number of surface hits 4817
WM  Intensity   191.3136 +/-  25.5537
Ctx Intensity   229.3055 +/-  46.7482
Pct Contrast     16.1724 +/-  28.1370
Cost   0.3219
RelCost   0.3463
Reg at min cost was 
-0.99675  -0.07570   0.02771   0.85919;
 0.02379   0.05222   0.99835  -3.59462;
 0.07702  -0.99576   0.05025  -2.75437;
 0.00000   0.00000   0.00000   1.00000;

Writing optimal reg to /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/bbr.pass1.dat, type = 14 
Original Reg 
-0.99669  -0.07672   0.02697   0.55428;
 0.02291   0.05322   0.99832  -3.12273;
 0.07802  -0.99563   0.05129  -2.93842;
 0.00000   0.00000   0.00000   1.00000;

Original Reg - Optimal Reg
 0.00006  -0.00102  -0.00075  -0.30491;
-0.00088   0.00101  -0.00003   0.47189;
 0.00100   0.00013   0.00104  -0.18404;
 0.00000   0.00000   0.00000   0.00000;

Computing change in lh position
LH rmsDiffMean 0.592511
Computing change in rh position
Surface-RMS-Diff-mm 0.565852 0.062007 0.701269
mri_segreg done
mri_segreg --mov /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/template.nii --init-reg /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/bbr.pass1.dat --out-reg /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.auto.dat --interp trilinear --wm-proj-abs 1 --tol 1e-8 --tol1d 1e-3 --c0 0 --mincost /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.auto.dat.mincost --dof 6 --nmax 36 --param /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.auto.dat.param --surf white --brute -0.1 0.1 0.1 --cur-reg /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/reg.curopt.dat --gm-proj-abs 2 --nsub 1 --gm-gt-wm 0.5
7.3.2
setenv SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/scripts
mri_segreg --mov /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/template.nii --init-reg /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/bbr.pass1.dat --out-reg /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.auto.dat --interp trilinear --wm-proj-abs 1 --tol 1e-8 --tol1d 1e-3 --c0 0 --mincost /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.auto.dat.mincost --dof 6 --nmax 36 --param /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.auto.dat.param --surf white --brute -0.1 0.1 0.1 --cur-reg /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/reg.curopt.dat --gm-proj-abs 2 --nsub 1 --gm-gt-wm 0.5 
sysname  Linux
hostname cn4271
machine  x86_64
user     zugmana2
movvol /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/template.nii
regfile /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/tmp.bbregister.886663/bbr.pass1.dat
subject sub-24563
dof 6
outregfile /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.auto.dat
UseMask 0
UseLH 1
UseRH 1
nsubsamp 1
PenaltySign  -1
PenaltySlope 0.500000
PenaltyCenter 0.000000
surfname white
GMProjAbs 2.000000
WMProjAbs 1.000000
lhcostfile (null)
rhcostfile (null)
interp  trilinear (1)
frame  0
TolPowell 0.000000
nMaxItersPowell 36
n1dmin  3
Profile   0
Gdiag_no  -1
AddNoise  0 (0)
SynthSeed 1696036667
TransRandMax 0.000000
RotRandMax 0.000000
Translations 0.000000 0.000000 0.000000
Rotations   0.000000 0.000000 0.000000
Input reg
-0.99675  -0.07570   0.02771   0.85919;
 0.02379   0.05222   0.99835  -3.59462;
 0.07702  -0.99576   0.05025  -2.75437;
 0.00000   0.00000   0.00000   1.00000;

Loading mov
ExcludeZeroVoxels 1
Reading in targ vol /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig.mgz
Projecting LH Surfs
Loading lh.white surf
GM Proj: 0 0.500000 2.000000
WM Proj: 0 0.500000 1.000000
Projecting RH Surfs
Loading rh.white surf
Projecting RH Surfs
Using lh.cortex.label
Using rh.cortex.label
Computing relative cost
 0  -25.0 -25.0 -25.0   0.997608
 1  -25.0 -25.0  25.0   0.995108
 2  -25.0  25.0 -25.0   1.021077
 3  -25.0  25.0  25.0   0.987878
 4   25.0 -25.0 -25.0   1.010218
 5   25.0 -25.0  25.0   0.999284
 6   25.0  25.0 -25.0   1.014763
 7   25.0  25.0  25.0   1.012922
REL:  8  0.289442    8.038858  1.004857 rel = 0.288043 
Initial costs ----------------
Number of surface hits 481472
WM  Intensity   188.7318 +/-  21.0671
Ctx Intensity   228.0462 +/-  46.7863
Pct Contrast     16.7951 +/-  27.7611
Cost   0.2894
RelCost   0.2880

------------------------------------
Brute force preopt -0.1 0.1 0.1, n = 729
     0  -0.1000  -0.1000  -0.1000  -0.1000  -0.1000  -0.1000      0.2821   0.2821  0.0
     3  -0.1000  -0.1000  -0.1000  -0.1000   0.0000  -0.1000      0.2811   0.2811  0.0
    27  -0.1000  -0.1000   0.0000  -0.1000  -0.1000  -0.1000      0.2781   0.2781  0.0
    54  -0.1000  -0.1000   0.1000  -0.1000  -0.1000  -0.1000      0.2750   0.2750  0.0
   135  -0.1000   0.0000   0.1000  -0.1000  -0.1000  -0.1000      0.2739   0.2739  0.0
   297   0.0000  -0.1000   0.1000  -0.1000  -0.1000  -0.1000      0.2709   0.2709  0.0
   540   0.1000  -0.1000   0.1000  -0.1000  -0.1000  -0.1000      0.2683   0.2683  0.0
Brute Force --------------------------
Min cost was 0.268324
Number of iterations   729
Search time 1.347176 sec
Parameters at best (transmm, rotdeg)
  0.100  -0.100   0.100 -0.100 -0.100 -0.100 
--------------------------------------------

Starting Powell Minimization
Init Powel Params dof = 6
0 0.1
1 -0.1
2 0.1
3 -0.1
4 -0.1
5 -0.1
fs_powell::minimize
  nparams 6
  maxfev 36
  ftol   0.000000
  linmin_xtol_   0.001000
  powell nthiter 0: fret = 0.284035
  11  0.106 -0.100  0.100 -0.100 -0.100 -0.100   0.2840310443
  21  0.106 -0.088  0.100 -0.100 -0.100 -0.100   0.2840269299
  22  0.106 -0.089  0.100 -0.100 -0.100 -0.100   0.2840268585
  29  0.106 -0.089  0.482 -0.100 -0.100 -0.100   0.2808426993
  32  0.106 -0.089  0.472 -0.100 -0.100 -0.100   0.2808406765
  33  0.106 -0.089  0.474 -0.100 -0.100 -0.100   0.2808406327
  34  0.106 -0.089  0.475 -0.100 -0.100 -0.100   0.2808405424
  47  0.106 -0.089  0.475 -0.096 -0.100 -0.100   0.2808359907
  49  0.106 -0.089  0.475 -0.088 -0.100 -0.100   0.2808353981
  50  0.106 -0.089  0.475 -0.092 -0.100 -0.100   0.2808346469
  59  0.106 -0.089  0.475 -0.092 -0.213 -0.100   0.2807188889
  64  0.106 -0.089  0.475 -0.092 -0.219 -0.100   0.2807152239
  65  0.106 -0.089  0.475 -0.092 -0.222 -0.100   0.2807147668
  67  0.106 -0.089  0.475 -0.092 -0.221 -0.100   0.2807146770
  74  0.106 -0.089  0.475 -0.092 -0.221 -0.186   0.2801366967
  75  0.106 -0.089  0.475 -0.092 -0.221 -0.354   0.2799502999
  77  0.106 -0.089  0.475 -0.092 -0.221 -0.295   0.2797948426
  78  0.106 -0.089  0.475 -0.092 -0.221 -0.286   0.2797882275
  80  0.106 -0.089  0.475 -0.092 -0.221 -0.284   0.2797877996
  81  0.106 -0.089  0.475 -0.092 -0.221 -0.283   0.2797877335
  powell nthiter 1: fret = 0.279788
  91  0.182 -0.089  0.475 -0.092 -0.221 -0.283   0.2795528286
  92  0.181 -0.089  0.475 -0.092 -0.221 -0.283   0.2795524200
  94  0.180 -0.089  0.475 -0.092 -0.221 -0.283   0.2795523652
 101  0.180 -0.035  0.475 -0.092 -0.221 -0.283   0.2794802320
 102  0.180 -0.049  0.475 -0.092 -0.221 -0.283   0.2794573323
 103  0.180 -0.053  0.475 -0.092 -0.221 -0.283   0.2794533597
 105  0.180 -0.057  0.475 -0.092 -0.221 -0.283   0.2794518625
 106  0.180 -0.058  0.475 -0.092 -0.221 -0.283   0.2794517919
 114  0.180 -0.058  0.469 -0.092 -0.221 -0.283   0.2794304708
 115  0.180 -0.058  0.414 -0.092 -0.221 -0.283   0.2794221553
 117  0.180 -0.058  0.440 -0.092 -0.221 -0.283   0.2793814793
 126  0.180 -0.058  0.440 -0.163 -0.221 -0.283   0.2792843074
 127  0.180 -0.058  0.440 -0.143 -0.221 -0.283   0.2792699328
 128  0.180 -0.058  0.440 -0.144 -0.221 -0.283   0.2792693038
 129  0.180 -0.058  0.440 -0.147 -0.221 -0.283   0.2792691171
 132  0.180 -0.058  0.440 -0.146 -0.221 -0.283   0.2792689456
 140  0.180 -0.058  0.440 -0.146 -0.257 -0.283   0.2792632653
 141  0.180 -0.058  0.440 -0.146 -0.241 -0.283   0.2792521207
 143  0.180 -0.058  0.440 -0.146 -0.245 -0.283   0.2792514165
 155  0.180 -0.058  0.440 -0.146 -0.244 -0.290   0.2792462881
 159  0.180 -0.058  0.440 -0.146 -0.244 -0.303   0.2792445280
 160  0.180 -0.058  0.440 -0.146 -0.244 -0.299   0.2792431916
 161  0.180 -0.058  0.440 -0.146 -0.244 -0.298   0.2792429616
  powell nthiter 2: fret = 0.279243
 172  0.192 -0.058  0.440 -0.146 -0.244 -0.298   0.2792353850
 174  0.195 -0.058  0.440 -0.146 -0.244 -0.298   0.2792347611
 177  0.202 -0.058  0.440 -0.146 -0.244 -0.298   0.2792320758
 181  0.201 -0.058  0.440 -0.146 -0.244 -0.298   0.2792320246
 189  0.201 -0.053  0.440 -0.146 -0.244 -0.298   0.2792270543
 190  0.201 -0.051  0.440 -0.146 -0.244 -0.298   0.2792266098
 206  0.201 -0.051  0.439 -0.146 -0.244 -0.298   0.2792264884
 217  0.201 -0.051  0.439 -0.145 -0.244 -0.298   0.2792262288
 226  0.201 -0.051  0.439 -0.145 -0.255 -0.298   0.2792184560
 227  0.201 -0.051  0.439 -0.145 -0.266 -0.298   0.2792107654
 233  0.201 -0.051  0.439 -0.145 -0.265 -0.298   0.2792106940
 247  0.201 -0.051  0.439 -0.145 -0.265 -0.300   0.2792102432
  powell nthiter 3: fret = 0.279210
 259  0.220 -0.051  0.439 -0.145 -0.265 -0.300   0.2792077060
 260  0.213 -0.051  0.439 -0.145 -0.265 -0.300   0.2792007163
 261  0.211 -0.051  0.439 -0.145 -0.265 -0.300   0.2792003835
 271  0.211 -0.048  0.439 -0.145 -0.265 -0.300   0.2791996177
 282  0.211 -0.048  0.444 -0.145 -0.265 -0.300   0.2791995291
 283  0.211 -0.048  0.442 -0.145 -0.265 -0.300   0.2791988493
 292  0.211 -0.048  0.442 -0.147 -0.265 -0.300   0.2791976948
 294  0.211 -0.048  0.442 -0.149 -0.265 -0.300   0.2791971700
 295  0.211 -0.048  0.442 -0.148 -0.265 -0.300   0.2791970982
 306  0.211 -0.048  0.442 -0.148 -0.270 -0.300   0.2791938223
 307  0.211 -0.048  0.442 -0.148 -0.272 -0.300   0.2791936631
 309  0.211 -0.048  0.442 -0.148 -0.271 -0.300   0.2791935760
 317  0.211 -0.048  0.442 -0.148 -0.271 -0.292   0.2791916493
 319  0.211 -0.048  0.442 -0.148 -0.271 -0.294   0.2791914730
 323  0.222 -0.045  0.444 -0.152 -0.278 -0.288   0.2791883444
 329  0.218 -0.046  0.443 -0.150 -0.275 -0.290   0.2791878020
 331  0.218 -0.046  0.443 -0.150 -0.276 -0.290   0.2791877316
 334  0.218 -0.046  0.443 -0.150 -0.275 -0.290   0.2791876355
 335  0.218 -0.046  0.443 -0.150 -0.275 -0.290   0.2791876113
 336  0.218 -0.046  0.443 -0.150 -0.275 -0.290   0.2791874534
  powell nthiter 4: fret = 0.279187
 359  0.218 -0.054  0.443 -0.150 -0.275 -0.290   0.2791864107
 360  0.218 -0.051  0.443 -0.150 -0.275 -0.290   0.2791858916
 372  0.218 -0.051  0.447 -0.150 -0.275 -0.290   0.2791844600
 384  0.218 -0.051  0.447 -0.153 -0.275 -0.290   0.2791834678
 385  0.218 -0.051  0.447 -0.154 -0.275 -0.290   0.2791831459
 415  0.224 -0.054  0.453 -0.161 -0.279 -0.287   0.2791826008
  powell nthiter 5: fret = 0.279183
 425  0.218 -0.051  0.447 -0.154 -0.275 -0.287   0.2791825863
 435  0.218 -0.055  0.447 -0.154 -0.275 -0.287   0.2791813330
 436  0.218 -0.056  0.447 -0.154 -0.275 -0.287   0.2791813324
 448  0.218 -0.056  0.451 -0.154 -0.275 -0.287   0.2791809055
 449  0.218 -0.056  0.450 -0.154 -0.275 -0.287   0.2791808302
 459  0.218 -0.056  0.450 -0.156 -0.275 -0.287   0.2791805922
 473  0.228 -0.053  0.453 -0.160 -0.282 -0.281   0.2791791926
 476  0.234 -0.051  0.454 -0.162 -0.286 -0.278   0.2791773319
 479  0.236 -0.051  0.455 -0.162 -0.287 -0.277   0.2791772955
 483  0.236 -0.051  0.455 -0.162 -0.286 -0.277   0.2791771885
 488  0.236 -0.051  0.455 -0.162 -0.286 -0.277   0.2791771848
  powell nthiter 6: fret = 0.279177
 499  0.236 -0.051  0.455 -0.162 -0.286 -0.272   0.2791730691
 502  0.236 -0.051  0.455 -0.162 -0.286 -0.271   0.2791727898
 511  0.236 -0.060  0.455 -0.162 -0.286 -0.271   0.2791708924
 512  0.236 -0.057  0.455 -0.162 -0.286 -0.271   0.2791704162
 513  0.236 -0.058  0.455 -0.162 -0.286 -0.271   0.2791703834
 522  0.236 -0.058  0.468 -0.162 -0.286 -0.271   0.2791596796
 523  0.236 -0.058  0.470 -0.162 -0.286 -0.271   0.2791585627
 524  0.236 -0.058  0.480 -0.162 -0.286 -0.271   0.2791585293
 525  0.236 -0.058  0.475 -0.162 -0.286 -0.271   0.2791570215
 536  0.236 -0.058  0.475 -0.174 -0.286 -0.271   0.2791462528
 537  0.236 -0.058  0.475 -0.175 -0.286 -0.271   0.2791461599
 547  0.236 -0.058  0.475 -0.175 -0.267 -0.271   0.2791417483
 548  0.236 -0.058  0.475 -0.175 -0.275 -0.271   0.2791406471
 549  0.236 -0.058  0.475 -0.175 -0.273 -0.271   0.2791396139
 550  0.236 -0.058  0.475 -0.175 -0.272 -0.271   0.2791391810
 558  0.237 -0.058  0.475 -0.175 -0.273 -0.270   0.2791389747
 559  0.237 -0.058  0.475 -0.175 -0.273 -0.270   0.2791389315
 561  0.237 -0.058  0.475 -0.175 -0.273 -0.270   0.2791388396
  powell nthiter 7: fret = 0.279139
 574  0.237 -0.058  0.475 -0.175 -0.273 -0.266   0.2791367705
 576  0.237 -0.058  0.475 -0.175 -0.273 -0.265   0.2791367544
 587  0.237 -0.059  0.475 -0.175 -0.273 -0.265   0.2791364163
 597  0.237 -0.059  0.481 -0.175 -0.273 -0.265   0.2791345288
 599  0.237 -0.059  0.485 -0.175 -0.273 -0.265   0.2791338895
 600  0.237 -0.059  0.486 -0.175 -0.273 -0.265   0.2791338364
 610  0.237 -0.059  0.486 -0.173 -0.273 -0.265   0.2791338181
 630  0.235 -0.060  0.485 -0.173 -0.272 -0.266   0.2791332707
  powell nthiter 8: fret = 0.279133
 660  0.235 -0.062  0.485 -0.173 -0.272 -0.266   0.2791331593
 662  0.235 -0.061  0.485 -0.173 -0.272 -0.266   0.2791330550
 683  0.235 -0.061  0.485 -0.174 -0.272 -0.266   0.2791330191
 703  0.235 -0.061  0.485 -0.174 -0.272 -0.266   0.2791330000
 705  0.234 -0.061  0.485 -0.173 -0.271 -0.267   0.2791329381
 710  0.234 -0.061  0.485 -0.173 -0.271 -0.267   0.2791328813
 714  0.234 -0.061  0.485 -0.173 -0.271 -0.267   0.2791328459
  powell nthiter 9: fret = 0.279133
 738  0.234 -0.060  0.485 -0.173 -0.271 -0.267   0.2791328269
 751  0.234 -0.060  0.486 -0.173 -0.271 -0.267   0.2791327476
 762  0.234 -0.060  0.486 -0.174 -0.271 -0.267   0.2791327336
 791  0.234 -0.060  0.486 -0.174 -0.271 -0.267   0.2791327050
  powell nthiter 10: fret = 0.279133
 849  0.234 -0.060  0.486 -0.174 -0.272 -0.267   0.2791326670
  powell nthiter 11: fret = 0.279133
Powell done niters = 11
Computing relative cost
 0  -25.0 -25.0 -25.0   0.996544
 1  -25.0 -25.0  25.0   1.001532
 2  -25.0  25.0 -25.0   1.017521
 3  -25.0  25.0  25.0   0.991659
 4   25.0 -25.0 -25.0   1.016104
 5   25.0 -25.0  25.0   0.998890
 6   25.0  25.0 -25.0   1.015300
 7   25.0  25.0  25.0   1.014214
REL:  8  0.279133    8.051764  1.006470 rel = 0.277338 
Number of iterations    11
Min cost was 0.279133
Number of FunctionCalls   940
TolPowell 0.000000
nMaxItersPowell 36
OptimizationTime 104.544854 sec
Parameters at optimum (transmm)  0.23441 -0.06021  0.48602
Parameters at optimum (rotdeg) -0.17440 -0.27233 -0.26677 
Final costs ----------------
Number of surface hits 481472
WM  Intensity   188.9893 +/-  21.0613
Ctx Intensity   227.8653 +/-  49.2615
Pct Contrast     16.2021 +/-  30.3554
Cost   0.2791
RelCost   0.2880
Reg at min cost was 
-0.99698  -0.07073   0.03214   1.08984;
 0.02867   0.04952   0.99836  -3.66722;
 0.07221  -0.99627   0.04734  -2.25328;
 0.00000   0.00000   0.00000   1.00000;

Writing optimal reg to /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.auto.dat, type = 14 
Original Reg 
-0.99675  -0.07570   0.02771   0.85919;
 0.02379   0.05222   0.99835  -3.59462;
 0.07702  -0.99576   0.05025  -2.75437;
 0.00000   0.00000   0.00000   1.00000;

Original Reg - Optimal Reg
 0.00023  -0.00496  -0.00442  -0.23066;
-0.00488   0.00270  -0.00001   0.07260;
 0.00481   0.00050   0.00291  -0.50109;
 0.00000   0.00000   0.00000   0.00000;

Computing change in lh position
LH rmsDiffMean 0.704331
Computing change in rh position
Surface-RMS-Diff-mm 0.591565 0.156463 0.942742
mri_segreg done
MinCost: 0.279133 188.989319 227.865345 16.202127 
tkregister2_cmdl --mov /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/T2raw.mgz --reg /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.auto.dat --noedit --ltaout /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.auto.lta
INFO: no target volume specified, assuming FreeSurfer orig volume.
target  volume orig
movable volume /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/T2raw.mgz
reg file       /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.auto.dat
LoadVol        0
ZeroCRAS       0
7.3.2
Diagnostic Level -1
---- Input registration matrix --------
-0.99698  -0.07073   0.03214   1.08984;
 0.02867   0.04952   0.99836  -3.66722;
 0.07221  -0.99627   0.04734  -2.25328;
 0.00000   0.00000   0.00000   1.00000;
float2int = 0
---------------------------------------
INFO: loading target /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig.mgz
INFO: target does not conform to COR format, so I'm going to
reslice to COR. This will not affect the final registration.
Ttarg: --------------------
-1.00000   0.00000   0.00000   128.00000;
 0.00000   0.00000   1.00000  -128.00000;
 0.00000  -1.00000   0.00000   128.00000;
 0.00000   0.00000   0.00000   1.00000;
INFO: loading movable /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/T2raw.mgz
Tmov: --------------------
-0.80000   0.00000   0.00000   98.40000;
 0.00000   0.00000   0.50000  -128.00000;
 0.00000  -0.50000   0.00000   128.00000;
 0.00000   0.00000   0.00000   1.00000;
mkheaderreg = 0, float2int = 0
---- Input registration matrix --------
-0.99698  -0.07073   0.03214   1.08983;
 0.02867   0.04952   0.99836  -3.66721;
 0.07221  -0.99627   0.04734  -2.25326;
 0.00000   0.00000   0.00000   1.00000;
Determinant -1
subject = sub-24563
RegMat ---------------------------
-0.99698  -0.07073   0.03214   1.08984;
 0.02867   0.04952   0.99836  -3.66722;
 0.07221  -0.99627   0.04734  -2.25328;
 0.00000   0.00000   0.00000   1.00000;
Cleaning up
 
Started at Wed Sep 20 22:27:40 EDT 2023 
Ended   at Wed Sep 20 22:32:35 EDT 2023
BBR-Run-Time-Sec 295
 
bbregister Done
To check results, run:
tkregisterfv --mov /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/T2raw.mgz --reg /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.auto.lta --surfs  --sd /lscratch/8536404/24563.out/sourcedata/freesurfer
 

 cp /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.auto.lta /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.lta 

mri_convert -odt float -at /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.lta -rl /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig.mgz /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/T2raw.mgz /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/T2.prenorm.mgz 
reading from /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig/T2raw.mgz...
TR=3206.00, TE=0.00, TI=0.00, flip angle=0.00
i_ras = (1, 0, 0)
j_ras = (0, 1, 0)
k_ras = (0, 0, 1)
INFO: Reading transformation from file /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.lta...
Reading transform with LTAreadEx()
reading template info from volume /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/orig.mgz...
INFO: Applying transformation from file /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms/T2raw.lta...
---------------------------------
INFO: Transform Matrix (linear_ras_to_ras)
 0.99698  -0.07221   0.02867   0.99825;
 0.07073   0.99627   0.04952   7.04977;
-0.03214  -0.04734   0.99836  -2.46772;
 0.00000   0.00000   0.00000   1.00000;
---------------------------------
Applying LTAtransformInterp (resample_type 1)
changing data type from short to float (noscale = 0)...
writing to /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/T2.prenorm.mgz...

 mri_normalize -seed 1234 -sigma 0.5 -nonmax_suppress 0 -min_dist 1 -aseg /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/aseg.presurf.mgz -surface /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.white identity.nofile -surface /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.white identity.nofile /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/T2.prenorm.mgz /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/T2.norm.mgz 

setting seed for random number genererator to 1234
using Gaussian smoothing of bias field, sigma=0.500
disabling nonmaximum suppression
retaining  points that are at least 1.000mm from the boundary
using segmentation for initial intensity normalization
reading mri_src from /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/T2.prenorm.mgz...
Copying mri_dst from mri_src
computing distance transform
computing distance transform
min_dist = 1
Erasing Border planes 4
Removing non-wm voxels
100141 non wm control points removed
Building bias image
building Voronoi diagram...
performing soap bubble smoothing, sigma = 0...
smoothing bias field with sigma=0.500
MRIapplyBiasCorrectionSameGeometry()
writing normalized volume to /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/T2.norm.mgz
#VMPC# mri_normalize VmPeak  1822588
mri_normalize done

 mri_mask -transfer 255 -keep_mask_deletion_edits /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/T2.norm.mgz /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/brain.finalsurfs.mgz /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/T2.mgz 

transfer mask voxels=255 to dst vol
Transferring mask edits ('1' voxels) to dst vol
DoAbs = 0
Writing masked volume to /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/T2.mgz...done.
#--------------------------------------------
#@# MMPialSurf lh Wed Sep 20 22:33:48 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --adgws-in ../surf/autodet.gw.stats.lh.dat --seg aseg.presurf.mgz --wm wm.mgz --threads 4 --invol brain.finalsurfs.mgz --lh --i ../surf/lh.pial.T1 --o ../surf/lh.pial.T2 --pial --nsmooth 0 --rip-label ../label/lh.cortex+hipamyg.label --pin-medial-wall ../label/lh.cortex.label --white-surf ../surf/lh.white --aparc ../label/lh.aparc.annot --repulse-surf ../surf/lh.white --mmvol T2.mgz T2
7.3.2
7.3.2

cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
setenv SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
mris_place_surface --adgws-in ../surf/autodet.gw.stats.lh.dat --seg aseg.presurf.mgz --wm wm.mgz --threads 4 --invol brain.finalsurfs.mgz --lh --i ../surf/lh.pial.T1 --o ../surf/lh.pial.T2 --pial --nsmooth 0 --rip-label ../label/lh.cortex+hipamyg.label --pin-medial-wall ../label/lh.cortex.label --white-surf ../surf/lh.white --aparc ../label/lh.aparc.annot --repulse-surf ../surf/lh.white --mmvol T2.mgz T2 

Reading in input surface ../surf/lh.pial.T1
Not smoothing input surface
Area    509248  0.25290  0.20677 0.000039   8.4654
Corner 1527744 60.00000 31.82944 0.017827 179.9119
Edge    763872  0.80796  0.38284 0.005503   7.4060
Hinge   763872 18.35248 25.93065 0.000005 180.0000
Reading white surface coordinates from ../surf/lh.white
Reading repulsion surface coordinates from ../surf/lh.white
Reading in aparc ../label/lh.aparc.annot
Reading in input volume brain.finalsurfs.mgz
Reading in wm volume wm.mgz
MRIclipBrightWM(): nthresh=46344, wmmin=5, clip=110 
MRIfindBrightNonWM(): 472 bright non-wm voxels segmented.
Masking bright non-wm for pial surface mid_gray = 67.2825
MRImask(): AllowDiffGeom = 1
MRImask(): AllowDiffGeom = 1
MRImask(): AllowDiffGeom = 1
Reading in seg volume aseg.presurf.mgz
Ripping frozen voxels
Ripping vertices not in label ../label/lh.cortex+hipamyg.label
MRISripNotLabel() ripped 10489/254626 vertices (244137 unripped)
INFO: rip surface needed but not specified, so using input surface
Ripping segs (eg, WMSA, BG, frozen)
Starting MRISripSegs() d = (-2 2 0.5) segnos: 247 
MRISripSegs(): -2 2 0.5 ripped 0
Reading in multimodal volume T2.mgz
 using multi modal weights 
vertex 127313: xyz = (-26.7301,-11.7913,69.3821) oxyz = (-26.8164,-11.6244,66.2439) wxzy = (-26.8164,-11.6244,66.2439) pxyz = (-26.7301,-11.7913,69.3821) 
CBVO Creating mask 254626
n_averages 4
Iteration 0 =========================================
n_averages=4, current_sigma=2
Computing pial target locations using multimodal (1)
starting MRIScomputePialTargetLocationsMultiModal()
max_outward_dist = 3, sample_dist = 0.1, pix_size = 0.799995, whalf = 9
T2_min_inside = 110, T2_max_inside 300, T2_min_outside = 130, T2_max_outside 300
inside_peak_pct = 0.1, 0.01, outside_peak_pct = 0.5, 0.5
wm_weight = 3, nlabels=0, contrast_type=1
Changed 41813 aseg cortex voxels to 0
Creating lowres distance volumes t=0.0110812
Creating white distance volumes t=0.924905
(box.dx, box.dy, box.dz) = (180, 276, 416)
(region->dx, region->dy, region->dz) = (180, 276, 416)
(region->dx, region->dy, region->dz) = (180, 276, 416)
Creating pial distance volumes t=1.86945
(box.dx, box.dy, box.dz) = (190, 288, 426)
(region->dx, region->dy, region->dz) = (190, 288, 426)
(region->dx, region->dy, region->dz) = (190, 288, 426)
locating cortical regions not in interior range [110.0 --> 300.0], and not in exterior range [130.0 --> 300.0]
t = 2.94585
Starting loop over 254626 vertices
   vno = 0, t = 2.94585
   vno = 20000, t = 3.77295
   vno = 40000, t = 4.66016
   vno = 60000, t = 5.5234
   vno = 80000, t = 6.42319
   vno = 100000, t = 7.22521
   vno = 120000, t = 7.96448
   vno = 140000, t = 8.71528
   vno = 160000, t = 9.5566
   vno = 180000, t = 10.3832
   vno = 200000, t = 11.3535
   vno = 220000, t = 12.3497
   vno = 240000, t = 13.1931
CPTL: t = 13.818
186368 surface locations found to contain inconsistent values (44198 in, 142170 out)
Positioning Surface: tspring = 0.3, nspring = 1, spring = 0, niters = 100 l_repulse = 0.025, l_surf_repulse = 5, checktol = 1
Positioning pial surface
Entering MRISpositionSurface()
  max_mm = 0.3
  MAX_REDUCTIONS = 2, REDUCTION_PCT = 0.5
  parms->check_tol = 1, niterations = 100
tol=1.0e-04, sigma=2.0, host=cn427, nav=4, nbrs=2, l_repulse=0.025, l_surf_repulse=5.000, l_tspring=0.300, l_nspring=1.000, l_location=0.500, l_curv=0.500
mom=0.00, dt=0.50
complete_dist_mat 0
rms 0
smooth_averages 0
remove_neg 0
ico_order 0
which_surface 0
target_radius 0.000000
nfields 0
scale 0.000000
desired_rms_height 0.000000
momentum 0.000000
nbhd_size 0
max_nbrs 0
niterations 100
nsurfaces 0
SURFACES 3
flags 0 (0)
use curv 0
no sulc 0
no rigid align 0
mris->nsize 2
mris->hemisphere 0
randomSeed 0

000: dt: 0.0000, sse=788295.0, rms=0.795
#@%  0 loc cost weight=0.5, cost = 0.791482711344
001: dt: 0.5000, sse=592292.4, rms=0.791 (0.469%)
#@%  1 loc cost weight=0.5, cost = 0.777538827639
002: dt: 0.5000, sse=521986.7, rms=0.778 (1.762%)
#@%  2 loc cost weight=0.5, cost = 0.763420256423
003: dt: 0.5000, sse=494831.4, rms=0.763 (1.816%)
#@%  3 loc cost weight=0.5, cost = 0.749514280511
004: dt: 0.5000, sse=479728.7, rms=0.750 (1.822%)
#@%  4 loc cost weight=0.5, cost = 0.737485778185
005: dt: 0.5000, sse=471083.3, rms=0.737 (1.605%)
#@%  5 loc cost weight=0.5, cost = 0.727829638813
006: dt: 0.5000, sse=466913.2, rms=0.728 (1.309%)
#@%  6 loc cost weight=0.5, cost = 0.720237016994
007: dt: 0.5000, sse=464540.1, rms=0.720 (1.043%)
#@%  7 loc cost weight=0.5, cost = 0.714014613629
008: dt: 0.5000, sse=461803.0, rms=0.714 (0.864%)
#@%  8 loc cost weight=0.5, cost = 0.709236368122
009: dt: 0.5000, sse=461659.0, rms=0.709 (0.669%)
#@%  9 loc cost weight=0.5, cost = 0.705504688560
010: dt: 0.5000, sse=461291.1, rms=0.706 (0.526%)
#@% 10 loc cost weight=0.5, cost = 0.702805218260
011: dt: 0.5000, sse=460141.2, rms=0.703 (0.383%)
#@% 11 loc cost weight=0.5, cost = 0.701000839367
012: dt: 0.5000, sse=459217.2, rms=0.701 (0.257%)
#@% 12 loc cost weight=0.5, cost = 0.699806888779
013: dt: 0.5000, sse=458884.2, rms=0.700 (0.170%)
#@% 13 loc cost weight=0.5, cost = 0.699178947393
014: dt: 0.5000, sse=459011.6, rms=0.699 (0.090%)
#@% 14 loc cost weight=0.5, cost = 0.698982887327
015: dt: 0.5000, sse=458447.7, rms=0.699 (0.028%)
#@% 15 loc cost weight=0.5, cost = 0.699107383308
rms = 0.6991/0.6990, sse=460259.5/458447.6, time step reduction 1 of 3 to 0.250  1 0 0
016: dt: 0.5000, sse=460259.5, rms=0.699 (-0.018%)
#@% 16 loc cost weight=0.5, cost = 0.699601078670
rms = 0.6996/0.6991, sse=457719.9/460259.5, time step reduction 2 of 3 to 0.125  1 0 0
017: dt: 0.2500, sse=457719.8, rms=0.700 (-0.071%)
#@% 17 loc cost weight=0.5, cost = 0.699090607114
018: dt: 0.1250, sse=456298.0, rms=0.699 (0.073%)
#@% 18 loc cost weight=0.5, cost = 0.698210708901
019: dt: 0.1250, sse=456380.7, rms=0.698 (0.126%)
#@% 19 loc cost weight=0.5, cost = 0.697496881821
020: dt: 0.1250, sse=456286.2, rms=0.697 (0.102%)
#@% 20 loc cost weight=0.5, cost = 0.696949601125
021: dt: 0.1250, sse=456136.4, rms=0.697 (0.078%)
#@% 21 loc cost weight=0.5, cost = 0.696523116176
022: dt: 0.1250, sse=457535.2, rms=0.697 (0.061%)
#@% 22 loc cost weight=0.5, cost = 0.696227851291
023: dt: 0.1250, sse=459074.6, rms=0.696 (0.042%)
#@% 23 loc cost weight=0.5, cost = 0.696031057736
024: dt: 0.1250, sse=460054.2, rms=0.696 (0.028%)
#@% 24 loc cost weight=0.5, cost = 0.695975545428
rms = 0.6960/0.6960, sse=461121.4/460054.2, time step reduction 3 of 3 to 0.062  1 0 0
025: dt: 0.1250, sse=461121.4, rms=0.696 (0.008%)
  maximum number of reductions reached, breaking from loop
positioning took 4.0 minutes
Iteration 1 =========================================
n_averages=2, current_sigma=1
Computing pial target locations using multimodal (1)
starting MRIScomputePialTargetLocationsMultiModal()
max_outward_dist = 3, sample_dist = 0.1, pix_size = 0.799995, whalf = 9
T2_min_inside = 110, T2_max_inside 300, T2_min_outside = 130, T2_max_outside 300
inside_peak_pct = 0.1, 0.01, outside_peak_pct = 0.5, 0.5
wm_weight = 3, nlabels=0, contrast_type=1
Changed 41813 aseg cortex voxels to 0
Creating lowres distance volumes t=0.012716
Creating white distance volumes t=0.629457
(box.dx, box.dy, box.dz) = (180, 276, 416)
(region->dx, region->dy, region->dz) = (180, 276, 416)
(region->dx, region->dy, region->dz) = (180, 276, 416)
Creating pial distance volumes t=1.43922
(box.dx, box.dy, box.dz) = (184, 284, 424)
(region->dx, region->dy, region->dz) = (184, 284, 424)
(region->dx, region->dy, region->dz) = (184, 284, 424)
locating cortical regions not in interior range [110.0 --> 300.0], and not in exterior range [130.0 --> 300.0]
t = 2.4303
Starting loop over 254626 vertices
   vno = 0, t = 2.4303
   vno = 20000, t = 3.27825
   vno = 40000, t = 4.18357
   vno = 60000, t = 5.06981
   vno = 80000, t = 5.97652
   vno = 100000, t = 6.78797
   vno = 120000, t = 7.54988
   vno = 140000, t = 8.32716
   vno = 160000, t = 9.20758
   vno = 180000, t = 10.0702
   vno = 200000, t = 11.0748
   vno = 220000, t = 12.1021
   vno = 240000, t = 12.9724
CPTL: t = 13.6177
190603 surface locations found to contain inconsistent values (26158 in, 164445 out)
Positioning Surface: tspring = 0.3, nspring = 1, spring = 0, niters = 100 l_repulse = 0.025, l_surf_repulse = 5, checktol = 1
Positioning pial surface
Entering MRISpositionSurface()
  max_mm = 0.3
  MAX_REDUCTIONS = 2, REDUCTION_PCT = 0.5
  parms->check_tol = 1, niterations = 100
tol=1.0e-04, sigma=1.0, host=cn427, nav=2, nbrs=2, l_repulse=0.025, l_surf_repulse=5.000, l_tspring=0.300, l_nspring=1.000, l_location=0.500, l_curv=0.500
mom=0.00, dt=0.50
000: dt: 0.0000, sse=410415.0, rms=0.665
#@% 25 loc cost weight=0.5, cost = 0.654166053752
026: dt: 0.5000, sse=420650.2, rms=0.654 (1.630%)
#@% 26 loc cost weight=0.5, cost = 0.652574918453
027: dt: 0.5000, sse=416919.0, rms=0.653 (0.243%)
#@% 27 loc cost weight=0.5, cost = 0.650287289103
028: dt: 0.5000, sse=414750.6, rms=0.650 (0.351%)
#@% 28 loc cost weight=0.5, cost = 0.647880819838
029: dt: 0.5000, sse=414577.4, rms=0.648 (0.370%)
#@% 29 loc cost weight=0.5, cost = 0.646455833614
030: dt: 0.5000, sse=414416.2, rms=0.646 (0.220%)
#@% 30 loc cost weight=0.5, cost = 0.645391447176
031: dt: 0.5000, sse=415058.5, rms=0.645 (0.165%)
#@% 31 loc cost weight=0.5, cost = 0.644773263565
032: dt: 0.5000, sse=415117.9, rms=0.645 (0.096%)
#@% 32 loc cost weight=0.5, cost = 0.644520223092
033: dt: 0.5000, sse=415712.4, rms=0.645 (0.039%)
#@% 33 loc cost weight=0.5, cost = 0.644420315240
034: dt: 0.5000, sse=415898.7, rms=0.644 (0.016%)
#@% 34 loc cost weight=0.5, cost = 0.644489547592
rms = 0.6445/0.6444, sse=416335.5/415898.7, time step reduction 1 of 3 to 0.250  1 0 0
035: dt: 0.5000, sse=416335.5, rms=0.644 (-0.011%)
#@% 35 loc cost weight=0.5, cost = 0.644754676728
rms = 0.6448/0.6445, sse=414301.9/416335.5, time step reduction 2 of 3 to 0.125  1 0 0
036: dt: 0.2500, sse=414301.9, rms=0.645 (-0.041%)
#@% 36 loc cost weight=0.5, cost = 0.644210326197
037: dt: 0.1250, sse=412267.5, rms=0.644 (0.084%)
#@% 37 loc cost weight=0.5, cost = 0.643306569575
038: dt: 0.1250, sse=412385.0, rms=0.643 (0.140%)
#@% 38 loc cost weight=0.5, cost = 0.642494250490
039: dt: 0.1250, sse=413352.8, rms=0.642 (0.126%)
#@% 39 loc cost weight=0.5, cost = 0.641854969976
040: dt: 0.1250, sse=413436.5, rms=0.642 (0.099%)
#@% 40 loc cost weight=0.5, cost = 0.641364418521
041: dt: 0.1250, sse=414139.5, rms=0.641 (0.076%)
#@% 41 loc cost weight=0.5, cost = 0.640961924149
042: dt: 0.1250, sse=414350.0, rms=0.641 (0.063%)
#@% 42 loc cost weight=0.5, cost = 0.640649585531
043: dt: 0.1250, sse=415120.8, rms=0.641 (0.049%)
#@% 43 loc cost weight=0.5, cost = 0.640410857314
044: dt: 0.1250, sse=416204.4, rms=0.640 (0.037%)
#@% 44 loc cost weight=0.5, cost = 0.640222756234
045: dt: 0.1250, sse=417154.2, rms=0.640 (0.029%)
#@% 45 loc cost weight=0.5, cost = 0.640038395022
046: dt: 0.1250, sse=418123.5, rms=0.640 (0.029%)
#@% 46 loc cost weight=0.5, cost = 0.639910189035
047: dt: 0.1250, sse=418793.1, rms=0.640 (0.020%)
#@% 47 loc cost weight=0.5, cost = 0.639800085879
048: dt: 0.1250, sse=419650.6, rms=0.640 (0.017%)
#@% 48 loc cost weight=0.5, cost = 0.639681664215
049: dt: 0.1250, sse=420398.2, rms=0.640 (0.019%)
#@% 49 loc cost weight=0.5, cost = 0.639650039698
rms = 0.6397/0.6397, sse=421384.7/420398.2, time step reduction 3 of 3 to 0.062  1 0 0
050: dt: 0.1250, sse=421384.7, rms=0.640 (0.005%)
  maximum number of reductions reached, breaking from loop
positioning took 3.8 minutes
Pinning medial wall to white surface
removing intersecting faces
000: 12 intersecting
terminating search with 0 intersecting


Writing output to ../surf/lh.pial.T2
#ET# mris_place_surface 35.46 minutes
#VMPC# mris_place_surfaces VmPeak  4954328
mris_place_surface done
#--------------------------------------------
#@# MMPialSurf rh Wed Sep 20 23:09:30 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --adgws-in ../surf/autodet.gw.stats.rh.dat --seg aseg.presurf.mgz --wm wm.mgz --threads 4 --invol brain.finalsurfs.mgz --rh --i ../surf/rh.pial.T1 --o ../surf/rh.pial.T2 --pial --nsmooth 0 --rip-label ../label/rh.cortex+hipamyg.label --pin-medial-wall ../label/rh.cortex.label --white-surf ../surf/rh.white --aparc ../label/rh.aparc.annot --repulse-surf ../surf/rh.white --mmvol T2.mgz T2
7.3.2
7.3.2

cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
setenv SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
mris_place_surface --adgws-in ../surf/autodet.gw.stats.rh.dat --seg aseg.presurf.mgz --wm wm.mgz --threads 4 --invol brain.finalsurfs.mgz --rh --i ../surf/rh.pial.T1 --o ../surf/rh.pial.T2 --pial --nsmooth 0 --rip-label ../label/rh.cortex+hipamyg.label --pin-medial-wall ../label/rh.cortex.label --white-surf ../surf/rh.white --aparc ../label/rh.aparc.annot --repulse-surf ../surf/rh.white --mmvol T2.mgz T2 

Reading in input surface ../surf/rh.pial.T1
Not smoothing input surface
Area    507450  0.25110  0.20324 0.000044   8.1784
Corner 1522350 60.00000 32.06599 0.034719 179.7788
Edge    761175  0.80548  0.38290 0.005083   6.9357
Hinge   761175 18.91352 26.15177 0.000007 179.9973
Reading white surface coordinates from ../surf/rh.white
Reading repulsion surface coordinates from ../surf/rh.white
Reading in aparc ../label/rh.aparc.annot
Reading in input volume brain.finalsurfs.mgz
Reading in wm volume wm.mgz
MRIclipBrightWM(): nthresh=46344, wmmin=5, clip=110 
MRIfindBrightNonWM(): 472 bright non-wm voxels segmented.
Masking bright non-wm for pial surface mid_gray = 66.7825
MRImask(): AllowDiffGeom = 1
MRImask(): AllowDiffGeom = 1
MRImask(): AllowDiffGeom = 1
Reading in seg volume aseg.presurf.mgz
Ripping frozen voxels
Ripping vertices not in label ../label/rh.cortex+hipamyg.label
MRISripNotLabel() ripped 10437/253727 vertices (243290 unripped)
INFO: rip surface needed but not specified, so using input surface
Ripping segs (eg, WMSA, BG, frozen)
Starting MRISripSegs() d = (-2 2 0.5) segnos: 247 
MRISripSegs(): -2 2 0.5 ripped 0
Reading in multimodal volume T2.mgz
 using multi modal weights 
vertex 126864: xyz = (4.13919,-3.33266,52.0626) oxyz = (6.38792,-5.6732,53.7385) wxzy = (6.38792,-5.6732,53.7385) pxyz = (4.13919,-3.33266,52.0626) 
CBVO Creating mask 253727
n_averages 4
Iteration 0 =========================================
n_averages=4, current_sigma=2
Computing pial target locations using multimodal (1)
starting MRIScomputePialTargetLocationsMultiModal()
max_outward_dist = 3, sample_dist = 0.1, pix_size = 0.799995, whalf = 9
T2_min_inside = 110, T2_max_inside 300, T2_min_outside = 130, T2_max_outside 300
inside_peak_pct = 0.1, 0.01, outside_peak_pct = 0.5, 0.5
wm_weight = 3, nlabels=0, contrast_type=1
Changed 41813 aseg cortex voxels to 0
Creating lowres distance volumes t=0.012031
Creating white distance volumes t=0.7017
(box.dx, box.dy, box.dz) = (182, 272, 412)
(region->dx, region->dy, region->dz) = (182, 272, 412)
(region->dx, region->dy, region->dz) = (182, 272, 412)
Creating pial distance volumes t=1.51112
(box.dx, box.dy, box.dz) = (190, 290, 423)
(region->dx, region->dy, region->dz) = (190, 290, 423)
(region->dx, region->dy, region->dz) = (190, 290, 423)
locating cortical regions not in interior range [110.0 --> 300.0], and not in exterior range [130.0 --> 300.0]
t = 2.46433
Starting loop over 253727 vertices
   vno = 0, t = 2.46433
   vno = 20000, t = 3.24185
   vno = 40000, t = 4.02891
   vno = 60000, t = 4.77259
   vno = 80000, t = 5.51958
   vno = 100000, t = 6.15937
   vno = 120000, t = 6.81013
   vno = 140000, t = 7.50885
   vno = 160000, t = 8.28641
   vno = 180000, t = 9.16976
   vno = 200000, t = 10.2364
   vno = 220000, t = 11.1932
   vno = 240000, t = 11.9631
CPTL: t = 12.5023
188940 surface locations found to contain inconsistent values (38970 in, 149970 out)
Positioning Surface: tspring = 0.3, nspring = 1, spring = 0, niters = 100 l_repulse = 0.025, l_surf_repulse = 5, checktol = 1
Positioning pial surface
Entering MRISpositionSurface()
  max_mm = 0.3
  MAX_REDUCTIONS = 2, REDUCTION_PCT = 0.5
  parms->check_tol = 1, niterations = 100
tol=1.0e-04, sigma=2.0, host=cn427, nav=4, nbrs=2, l_repulse=0.025, l_surf_repulse=5.000, l_tspring=0.300, l_nspring=1.000, l_location=0.500, l_curv=0.500
mom=0.00, dt=0.50
complete_dist_mat 0
rms 0
smooth_averages 0
remove_neg 0
ico_order 0
which_surface 0
target_radius 0.000000
nfields 0
scale 0.000000
desired_rms_height 0.000000
momentum 0.000000
nbhd_size 0
max_nbrs 0
niterations 100
nsurfaces 0
SURFACES 3
flags 0 (0)
use curv 0
no sulc 0
no rigid align 0
mris->nsize 2
mris->hemisphere 1
randomSeed 0

000: dt: 0.0000, sse=792619.4, rms=0.743
#@%  0 loc cost weight=0.5, cost = 0.746773331326
rms = 0.7468/0.7430, sse=589540.5/792619.4, time step reduction 1 of 3 to 0.250  1 0 0
001: dt: 0.5000, sse=589540.4, rms=0.747 (-0.513%)
#@%  1 loc cost weight=0.5, cost = 0.747337512514
rms = 0.7473/0.7468, sse=518393.6/589540.5, time step reduction 2 of 3 to 0.125  1 0 0
002: dt: 0.2500, sse=518393.6, rms=0.747 (-0.076%)
#@%  2 loc cost weight=0.5, cost = 0.745302250887
003: dt: 0.1250, sse=492034.1, rms=0.745 (0.272%)
#@%  3 loc cost weight=0.5, cost = 0.740515236008
004: dt: 0.1250, sse=481667.5, rms=0.741 (0.642%)
#@%  4 loc cost weight=0.5, cost = 0.735631468558
005: dt: 0.1250, sse=476495.2, rms=0.736 (0.660%)
#@%  5 loc cost weight=0.5, cost = 0.731098634153
006: dt: 0.1250, sse=474560.6, rms=0.731 (0.616%)
#@%  6 loc cost weight=0.5, cost = 0.727016245266
007: dt: 0.1250, sse=471686.0, rms=0.727 (0.558%)
#@%  7 loc cost weight=0.5, cost = 0.723260914102
008: dt: 0.1250, sse=469786.3, rms=0.723 (0.517%)
#@%  8 loc cost weight=0.5, cost = 0.719742013799
009: dt: 0.1250, sse=470875.3, rms=0.720 (0.487%)
#@%  9 loc cost weight=0.5, cost = 0.716574343762
010: dt: 0.1250, sse=469296.3, rms=0.717 (0.440%)
#@% 10 loc cost weight=0.5, cost = 0.713684128853
011: dt: 0.1250, sse=468250.0, rms=0.714 (0.403%)
#@% 11 loc cost weight=0.5, cost = 0.711007024542
012: dt: 0.1250, sse=467869.4, rms=0.711 (0.375%)
#@% 12 loc cost weight=0.5, cost = 0.708469736123
013: dt: 0.1250, sse=468123.7, rms=0.708 (0.357%)
#@% 13 loc cost weight=0.5, cost = 0.706164946594
014: dt: 0.1250, sse=467718.0, rms=0.706 (0.325%)
#@% 14 loc cost weight=0.5, cost = 0.704083081718
015: dt: 0.1250, sse=467605.4, rms=0.704 (0.295%)
#@% 15 loc cost weight=0.5, cost = 0.702069385295
016: dt: 0.1250, sse=467315.8, rms=0.702 (0.286%)
#@% 16 loc cost weight=0.5, cost = 0.700268274981
017: dt: 0.1250, sse=467890.9, rms=0.700 (0.257%)
#@% 17 loc cost weight=0.5, cost = 0.698534017878
018: dt: 0.1250, sse=467206.2, rms=0.699 (0.248%)
#@% 18 loc cost weight=0.5, cost = 0.696990003979
019: dt: 0.1250, sse=467375.9, rms=0.697 (0.221%)
#@% 19 loc cost weight=0.5, cost = 0.695587483349
020: dt: 0.1250, sse=467850.9, rms=0.696 (0.201%)
#@% 20 loc cost weight=0.5, cost = 0.694234590018
021: dt: 0.1250, sse=468254.1, rms=0.694 (0.194%)
#@% 21 loc cost weight=0.5, cost = 0.692972196739
022: dt: 0.1250, sse=468926.8, rms=0.693 (0.182%)
#@% 22 loc cost weight=0.5, cost = 0.691836085768
023: dt: 0.1250, sse=468999.6, rms=0.692 (0.164%)
#@% 23 loc cost weight=0.5, cost = 0.690763113306
024: dt: 0.1250, sse=468946.2, rms=0.691 (0.155%)
#@% 24 loc cost weight=0.5, cost = 0.689846540163
025: dt: 0.1250, sse=469108.7, rms=0.690 (0.133%)
#@% 25 loc cost weight=0.5, cost = 0.688904058256
026: dt: 0.1250, sse=468665.4, rms=0.689 (0.137%)
#@% 26 loc cost weight=0.5, cost = 0.688096989824
027: dt: 0.1250, sse=468953.8, rms=0.688 (0.117%)
#@% 27 loc cost weight=0.5, cost = 0.687379980869
028: dt: 0.1250, sse=469219.8, rms=0.687 (0.104%)
#@% 28 loc cost weight=0.5, cost = 0.686657551272
029: dt: 0.1250, sse=469328.5, rms=0.687 (0.105%)
#@% 29 loc cost weight=0.5, cost = 0.686058072605
030: dt: 0.1250, sse=470069.5, rms=0.686 (0.087%)
#@% 30 loc cost weight=0.5, cost = 0.685510572661
031: dt: 0.1250, sse=471118.0, rms=0.686 (0.080%)
#@% 31 loc cost weight=0.5, cost = 0.684991128738
032: dt: 0.1250, sse=471806.1, rms=0.685 (0.076%)
#@% 32 loc cost weight=0.5, cost = 0.684507872554
033: dt: 0.1250, sse=471747.5, rms=0.685 (0.071%)
#@% 33 loc cost weight=0.5, cost = 0.684151282746
034: dt: 0.1250, sse=471576.0, rms=0.684 (0.052%)
#@% 34 loc cost weight=0.5, cost = 0.683839632706
035: dt: 0.1250, sse=472420.0, rms=0.684 (0.046%)
#@% 35 loc cost weight=0.5, cost = 0.683520166979
036: dt: 0.1250, sse=472423.0, rms=0.684 (0.047%)
#@% 36 loc cost weight=0.5, cost = 0.683232317557
037: dt: 0.1250, sse=472910.7, rms=0.683 (0.042%)
#@% 37 loc cost weight=0.5, cost = 0.682992853878
038: dt: 0.1250, sse=473405.9, rms=0.683 (0.035%)
#@% 38 loc cost weight=0.5, cost = 0.682808828306
039: dt: 0.1250, sse=473633.9, rms=0.683 (0.027%)
#@% 39 loc cost weight=0.5, cost = 0.682645623913
040: dt: 0.1250, sse=474289.7, rms=0.683 (0.024%)
#@% 40 loc cost weight=0.5, cost = 0.682505892226
041: dt: 0.1250, sse=474025.3, rms=0.683 (0.020%)
#@% 41 loc cost weight=0.5, cost = 0.682431037013
042: dt: 0.1250, sse=473745.7, rms=0.682 (0.011%)
#@% 42 loc cost weight=0.5, cost = 0.682384949478
rms = 0.6824/0.6824, sse=475118.7/473745.6, time step reduction 3 of 3 to 0.062  1 0 0
043: dt: 0.1250, sse=475118.7, rms=0.682 (0.007%)
  maximum number of reductions reached, breaking from loop
positioning took 6.2 minutes
Iteration 1 =========================================
n_averages=2, current_sigma=1
Computing pial target locations using multimodal (1)
starting MRIScomputePialTargetLocationsMultiModal()
max_outward_dist = 3, sample_dist = 0.1, pix_size = 0.799995, whalf = 9
T2_min_inside = 110, T2_max_inside 300, T2_min_outside = 130, T2_max_outside 300
inside_peak_pct = 0.1, 0.01, outside_peak_pct = 0.5, 0.5
wm_weight = 3, nlabels=0, contrast_type=1
Changed 41813 aseg cortex voxels to 0
Creating lowres distance volumes t=0.0122301
Creating white distance volumes t=0.684145
(box.dx, box.dy, box.dz) = (182, 272, 412)
(region->dx, region->dy, region->dz) = (182, 272, 412)
(region->dx, region->dy, region->dz) = (182, 272, 412)
Creating pial distance volumes t=1.4626
(box.dx, box.dy, box.dz) = (188, 284, 420)
(region->dx, region->dy, region->dz) = (188, 284, 420)
(region->dx, region->dy, region->dz) = (188, 284, 420)
locating cortical regions not in interior range [110.0 --> 300.0], and not in exterior range [130.0 --> 300.0]
t = 2.49882
Starting loop over 253727 vertices
   vno = 0, t = 2.49882
   vno = 20000, t = 3.33748
   vno = 40000, t = 4.17815
   vno = 60000, t = 4.98086
   vno = 80000, t = 5.80474
   vno = 100000, t = 6.48058
   vno = 120000, t = 7.167
   vno = 140000, t = 7.89831
   vno = 160000, t = 8.71003
   vno = 180000, t = 9.62408
   vno = 200000, t = 10.7215
   vno = 220000, t = 11.7104
   vno = 240000, t = 12.5149
CPTL: t = 13.0845
193206 surface locations found to contain inconsistent values (26911 in, 166295 out)
Positioning Surface: tspring = 0.3, nspring = 1, spring = 0, niters = 100 l_repulse = 0.025, l_surf_repulse = 5, checktol = 1
Positioning pial surface
Entering MRISpositionSurface()
  max_mm = 0.3
  MAX_REDUCTIONS = 2, REDUCTION_PCT = 0.5
  parms->check_tol = 1, niterations = 100
tol=1.0e-04, sigma=1.0, host=cn427, nav=2, nbrs=2, l_repulse=0.025, l_surf_repulse=5.000, l_tspring=0.300, l_nspring=1.000, l_location=0.500, l_curv=0.500
mom=0.00, dt=0.50
000: dt: 0.0000, sse=436732.1, rms=0.667
#@% 43 loc cost weight=0.5, cost = 0.656671739520
044: dt: 0.5000, sse=447180.3, rms=0.657 (1.525%)
#@% 44 loc cost weight=0.5, cost = 0.655761793128
045: dt: 0.5000, sse=442941.5, rms=0.656 (0.139%)
#@% 45 loc cost weight=0.5, cost = 0.653891491435
046: dt: 0.5000, sse=439436.0, rms=0.654 (0.285%)
#@% 46 loc cost weight=0.5, cost = 0.651647370293
047: dt: 0.5000, sse=436373.1, rms=0.652 (0.343%)
#@% 47 loc cost weight=0.5, cost = 0.650334225303
048: dt: 0.5000, sse=437129.0, rms=0.650 (0.202%)
#@% 48 loc cost weight=0.5, cost = 0.649354490623
049: dt: 0.5000, sse=435967.3, rms=0.649 (0.151%)
#@% 49 loc cost weight=0.5, cost = 0.648977853700
050: dt: 0.5000, sse=436265.8, rms=0.649 (0.058%)
#@% 50 loc cost weight=0.5, cost = 0.648636183562
051: dt: 0.5000, sse=437539.1, rms=0.649 (0.053%)
#@% 51 loc cost weight=0.5, cost = 0.648702940308
rms = 0.6487/0.6486, sse=436479.6/437539.1, time step reduction 1 of 3 to 0.250  1 0 0
052: dt: 0.5000, sse=436479.6, rms=0.649 (-0.010%)
#@% 52 loc cost weight=0.5, cost = 0.648971543775
rms = 0.6490/0.6487, sse=433253.1/436479.6, time step reduction 2 of 3 to 0.125  1 0 0
053: dt: 0.2500, sse=433253.1, rms=0.649 (-0.041%)
#@% 53 loc cost weight=0.5, cost = 0.648386957241
054: dt: 0.1250, sse=430503.4, rms=0.648 (0.090%)
#@% 54 loc cost weight=0.5, cost = 0.647400113081
055: dt: 0.1250, sse=428211.6, rms=0.647 (0.152%)
#@% 55 loc cost weight=0.5, cost = 0.646544054014
056: dt: 0.1250, sse=428057.6, rms=0.647 (0.132%)
#@% 56 loc cost weight=0.5, cost = 0.645801175482
057: dt: 0.1250, sse=430189.8, rms=0.646 (0.115%)
#@% 57 loc cost weight=0.5, cost = 0.645271365762
058: dt: 0.1250, sse=432130.2, rms=0.645 (0.082%)
#@% 58 loc cost weight=0.5, cost = 0.644830501942
059: dt: 0.1250, sse=432782.2, rms=0.645 (0.068%)
#@% 59 loc cost weight=0.5, cost = 0.644496250989
060: dt: 0.1250, sse=434215.9, rms=0.644 (0.052%)
#@% 60 loc cost weight=0.5, cost = 0.644265950948
061: dt: 0.1250, sse=435215.9, rms=0.644 (0.036%)
#@% 61 loc cost weight=0.5, cost = 0.644037077065
062: dt: 0.1250, sse=436436.6, rms=0.644 (0.036%)
#@% 62 loc cost weight=0.5, cost = 0.643893641868
063: dt: 0.1250, sse=437109.6, rms=0.644 (0.022%)
#@% 63 loc cost weight=0.5, cost = 0.643794759827
064: dt: 0.1250, sse=438438.5, rms=0.644 (0.015%)
#@% 64 loc cost weight=0.5, cost = 0.643724559324
065: dt: 0.1250, sse=439544.2, rms=0.644 (0.011%)
#@% 65 loc cost weight=0.5, cost = 0.643654671552
066: dt: 0.1250, sse=440392.2, rms=0.644 (0.011%)
#@% 66 loc cost weight=0.5, cost = 0.643650626736
rms = 0.6437/0.6437, sse=441172.9/440392.2, time step reduction 3 of 3 to 0.062  1 0 0
067: dt: 0.1250, sse=441172.9, rms=0.644 (0.001%)
  maximum number of reductions reached, breaking from loop
positioning took 6.9 minutes
Pinning medial wall to white surface
removing intersecting faces
000: 16 intersecting
001: 11 intersecting
002: 4 intersecting
step 1 with no progress (num=4, old_num=4)
003: 4 intersecting
step 2 with no progress (num=4, old_num=4)
004: 4 intersecting
step 3 with no progress (num=4, old_num=4)
005: 4 intersecting
step 4 with no progress (num=4, old_num=4)
006: 4 intersecting
step 5 with no progress (num=4, old_num=4)
007: 4 intersecting
step 6 with no progress (num=4, old_num=4)
008: 4 intersecting
step 7 with no progress (num=4, old_num=4)
009: 4 intersecting
step 8 with no progress (num=4, old_num=4)
010: 4 intersecting
step 9 with no progress (num=4, old_num=4)
011: 4 intersecting
step 10 with no progress (num=4, old_num=4)
012: 4 intersecting
step 11 with no progress (num=4, old_num=4)
013: 4 intersecting
step 12 with no progress (num=4, old_num=4)
014: 4 intersecting
step 13 with no progress (num=4, old_num=4)
015: 4 intersecting
step 14 with no progress (num=4, old_num=4)
016: 4 intersecting
step 15 with no progress (num=4, old_num=4)
017: 4 intersecting
step 16 with no progress (num=4, old_num=4)
terminating search with 4 intersecting


Writing output to ../surf/rh.pial.T2
#ET# mris_place_surface 40.11 minutes
#VMPC# mris_place_surfaces VmPeak  5484836
mris_place_surface done
#@# white curv lh Wed Sep 20 23:49:50 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --curv-map ../surf/lh.white 2 10 ../surf/lh.curv
   Update not needed
#@# white area lh Wed Sep 20 23:49:50 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --area-map ../surf/lh.white ../surf/lh.area
   Update not needed
#@# pial curv lh Wed Sep 20 23:49:50 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --curv-map ../surf/lh.pial 2 10 ../surf/lh.curv.pial
insurf  ../surf/lh.pial, nbrs 2, curvature_avgs 10
writing curvature file ../surf/lh.curv.pial
#@# pial area lh Wed Sep 20 23:49:53 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --area-map ../surf/lh.pial ../surf/lh.area.pial
writing curvature file ../surf/lh.area.pial
#@# thickness lh Wed Sep 20 23:49:54 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --thickness ../surf/lh.white ../surf/lh.pial 20 5 ../surf/lh.thickness
0 of 254626 vertices processed
25000 of 254626 vertices processed
50000 of 254626 vertices processed
75000 of 254626 vertices processed
100000 of 254626 vertices processed
125000 of 254626 vertices processed
150000 of 254626 vertices processed
175000 of 254626 vertices processed
200000 of 254626 vertices processed
225000 of 254626 vertices processed
250000 of 254626 vertices processed
0 of 254626 vertices processed
25000 of 254626 vertices processed
50000 of 254626 vertices processed
75000 of 254626 vertices processed
100000 of 254626 vertices processed
125000 of 254626 vertices processed
150000 of 254626 vertices processed
175000 of 254626 vertices processed
200000 of 254626 vertices processed
225000 of 254626 vertices processed
250000 of 254626 vertices processed
thickness calculation complete, 214:405 truncations.
100698 vertices at 0 distance
186538 vertices at 1 distance
115692 vertices at 2 distance
54490 vertices at 3 distance
27628 vertices at 4 distance
13428 vertices at 5 distance
6014 vertices at 6 distance
2552 vertices at 7 distance
1100 vertices at 8 distance
498 vertices at 9 distance
229 vertices at 10 distance
116 vertices at 11 distance
76 vertices at 12 distance
60 vertices at 13 distance
42 vertices at 14 distance
37 vertices at 15 distance
19 vertices at 16 distance
10 vertices at 17 distance
5 vertices at 18 distance
8 vertices at 19 distance
12 vertices at 20 distance
writing curvature file ../surf/lh.thickness
#@# area and vertex vol lh Wed Sep 20 23:50:41 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --thickness ../surf/lh.white ../surf/lh.pial 20 5 ../surf/lh.thickness
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf
mris_calc -o lh.area.mid lh.area add lh.area.pial
Saving result to 'lh.area.mid' (type = MRI_CURV_FILE)                       [ ok ]
mris_calc -o lh.area.mid lh.area.mid div 2
Saving result to 'lh.area.mid' (type = MRI_CURV_FILE)                       [ ok ]
mris_convert --volume sub-24563 lh /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.volume
masking with /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.cortex.label
Total face volume 244998
Total vertex volume 244850 (mask=0)
#@# sub-24563 lh 244850
 
vertexvol Done
#@# white curv rh Wed Sep 20 23:50:43 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --curv-map ../surf/rh.white 2 10 ../surf/rh.curv
   Update not needed
#@# white area rh Wed Sep 20 23:50:43 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --area-map ../surf/rh.white ../surf/rh.area
   Update not needed
#@# pial curv rh Wed Sep 20 23:50:43 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --curv-map ../surf/rh.pial 2 10 ../surf/rh.curv.pial
insurf  ../surf/rh.pial, nbrs 2, curvature_avgs 10
writing curvature file ../surf/rh.curv.pial
#@# pial area rh Wed Sep 20 23:50:46 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --area-map ../surf/rh.pial ../surf/rh.area.pial
writing curvature file ../surf/rh.area.pial
#@# thickness rh Wed Sep 20 23:50:47 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --thickness ../surf/rh.white ../surf/rh.pial 20 5 ../surf/rh.thickness
0 of 253727 vertices processed
25000 of 253727 vertices processed
50000 of 253727 vertices processed
75000 of 253727 vertices processed
100000 of 253727 vertices processed
125000 of 253727 vertices processed
150000 of 253727 vertices processed
175000 of 253727 vertices processed
200000 of 253727 vertices processed
225000 of 253727 vertices processed
250000 of 253727 vertices processed
0 of 253727 vertices processed
25000 of 253727 vertices processed
50000 of 253727 vertices processed
75000 of 253727 vertices processed
100000 of 253727 vertices processed
125000 of 253727 vertices processed
150000 of 253727 vertices processed
175000 of 253727 vertices processed
200000 of 253727 vertices processed
225000 of 253727 vertices processed
250000 of 253727 vertices processed
thickness calculation complete, 105:362 truncations.
101283 vertices at 0 distance
185651 vertices at 1 distance
115704 vertices at 2 distance
54197 vertices at 3 distance
27112 vertices at 4 distance
13061 vertices at 5 distance
5825 vertices at 6 distance
2502 vertices at 7 distance
1078 vertices at 8 distance
478 vertices at 9 distance
221 vertices at 10 distance
115 vertices at 11 distance
69 vertices at 12 distance
31 vertices at 13 distance
29 vertices at 14 distance
29 vertices at 15 distance
14 vertices at 16 distance
18 vertices at 17 distance
8 vertices at 18 distance
11 vertices at 19 distance
18 vertices at 20 distance
writing curvature file ../surf/rh.thickness
#@# area and vertex vol rh Wed Sep 20 23:51:35 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --thickness ../surf/rh.white ../surf/rh.pial 20 5 ../surf/rh.thickness
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf
mris_calc -o rh.area.mid rh.area add rh.area.pial
Saving result to 'rh.area.mid' (type = MRI_CURV_FILE)                       [ ok ]
mris_calc -o rh.area.mid rh.area.mid div 2
Saving result to 'rh.area.mid' (type = MRI_CURV_FILE)                       [ ok ]
mris_convert --volume sub-24563 rh /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.volume
masking with /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.cortex.label
Total face volume 250732
Total vertex volume 250572 (mask=0)
#@# sub-24563 rh 250572
 
vertexvol Done
#--------------------------------------------
#@# Cortical ribbon mask Wed Sep 20 23:51:38 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri

 mris_volmask --aseg_name aseg.presurf --label_left_white 2 --label_left_ribbon 3 --label_right_white 41 --label_right_ribbon 42 --save_ribbon sub-24563 

SUBJECTS_DIR is /lscratch/8536404/24563.out/sourcedata/freesurfer
loading input data...
Running hemis serially
Processing left hemi
computing distance to left white surface 
computing distance to left pial surface 
Processing right hemi
computing distance to right white surface 
computing distance to right pial surface 
 hemi masks overlap voxels = 11
writing volume /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/ribbon.mgz
mris_volmask took 14.15 minutes
 writing ribbon files

Started at Wed Sep 20 22:27:39 EDT 2023 
Ended   at Thu Sep 21 00:05:47 EDT 2023
#@#%# recon-all-run-time-hours 1.636
recon-all -s sub-24563 finished without error at Thu Sep 21 00:05:47 EDT 2023
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

