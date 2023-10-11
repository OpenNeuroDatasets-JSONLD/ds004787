Node: single_subject_24563_wf (anat_preproc_wf (bbreg (freesurfer)
==================================================================


 Hierarchy : fmriprep_23_2_wf.single_subject_24563_wf.anat_preproc_wf.bbreg
 Exec ID : bbreg


Original Inputs
---------------


* args : --gm-proj-abs 2 --wm-proj-abs 1
* contrast_type : t2
* dof : 6
* environ : {'SUBJECTS_DIR': '/lscratch/8536404/24563.out/sourcedata/freesurfer'}
* epi_mask : <undefined>
* fsldof : <undefined>
* init : coreg
* init_cost_file : <undefined>
* init_reg_file : <undefined>
* intermediate_file : <undefined>
* out_fsl_file : <undefined>
* out_lta_file : True
* out_reg_file : <undefined>
* reg_frame : <undefined>
* reg_middle_frame : <undefined>
* registered_file : <undefined>
* source_file : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template.nii.gz
* spm_nifti : <undefined>
* subject_id : sub-24563
* subjects_dir : /lscratch/8536404/24563.out/sourcedata/freesurfer


Execution Inputs
----------------


* args : --gm-proj-abs 2 --wm-proj-abs 1
* contrast_type : t2
* dof : 6
* environ : {'SUBJECTS_DIR': '/lscratch/8536404/24563.out/sourcedata/freesurfer'}
* epi_mask : <undefined>
* fsldof : <undefined>
* init : coreg
* init_cost_file : <undefined>
* init_reg_file : <undefined>
* intermediate_file : <undefined>
* out_fsl_file : <undefined>
* out_lta_file : True
* out_reg_file : <undefined>
* reg_frame : <undefined>
* reg_middle_frame : <undefined>
* registered_file : <undefined>
* source_file : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template.nii.gz
* spm_nifti : <undefined>
* subject_id : sub-24563
* subjects_dir : /lscratch/8536404/24563.out/sourcedata/freesurfer


Execution Outputs
-----------------


* init_cost_file : <undefined>
* min_cost_file : <undefined>
* out_fsl_file : <undefined>
* out_lta_file : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.lta
* out_reg_file : <undefined>
* registered_file : <undefined>


Runtime info
------------


* cmdline : bbregister --gm-proj-abs 2 --wm-proj-abs 1 --t2 --6 --init-coreg --lta /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.lta --reg /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.dat --mov /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template.nii.gz --s sub-24563
* duration : 289.698564
* hostname : cn4271
* prev_wd : /vf/users/EDB/TMSpilot/code
* working_dir : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg


Terminal output
~~~~~~~~~~~~~~~


 


Terminal - standard output
~~~~~~~~~~~~~~~~~~~~~~~~~~


 tmp /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778
Log file is /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.log
Thu Sep 21 00:29:02 EDT 2023

setenv SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
cd /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg
/opt/freesurfer/bin/bbregister --gm-proj-abs 2 --wm-proj-abs 1 --t2 --6 --init-coreg --lta /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.lta --reg /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.dat --mov /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template.nii.gz --s sub-24563

bbregister 7.3.2
Linux cn4271 4.18.0-425.19.2.el8_7.x86_64 #1 SMP Tue Apr 4 22:38:11 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
FREESURFER_HOME /opt/freesurfer
mri_convert /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template.nii.gz /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/template.nii
mri_convert /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template.nii.gz /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/template.nii 
reading from /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template.nii.gz...
TR=0.00, TE=0.00, TI=0.00, flip angle=0.00
i_ras = (1, 0, 0)
j_ras = (0, 1, 0)
k_ras = (-0, -0, 1)
writing to /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/template.nii...
mri_coreg --s sub-24563 --mov /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/template.nii --regdat /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/reg.init.dat --reg /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/mri_coreg.lta --nthreads 1 --dof 6 --sep 4 --ftol .0001 --linmintol .01

$Id: mri_coreg.c,v 1.27 2016/04/30 15:11:49 greve Exp $
cwd /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg
cmdline mri_coreg --s sub-24563 --mov /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/template.nii --regdat /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/reg.init.dat --reg /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/mri_coreg.lta --nthreads 1 --dof 6 --sep 4 --ftol .0001 --linmintol .01 
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
Reading in mov /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/template.nii
Reading in ref /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/brainmask.mgz
Reading in and applying refmask /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/aparc+aseg.mgz
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
nthreads 1
movsat = 427.2698
mov gstd 1.9140 1.9381 1.9381
Smoothing mov
refsat = 144.0000
ref gstd 1.9140 1.9140 1.9140
Smoothing ref
COREGpreproc() done
Testing if mov and target overlap
Init cost   -1.0466768934
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
#BF# sep= 4 iter=0 lim=30.0 delta=2.00  -1.74604  -4.96501   2.05701  -2.00000   0.00000   4.00000   -1.0457266
Turning  MovOOB back off after brute force search


---------------------------------
Init Powel Params dof = 6: -1.746040 -4.965012 2.057007 -2.000000 0.000000 4.000000 
Starting OpenPowel2(), sep = 4
InitialCost        -1.0538153648 
#@#  4  188  -1.74604 -4.96501 2.05701 -2.00000 0.00000 4.00000   -1.0538154
fs_powell::minimize
  nparams 6
  maxfev 4
  ftol   0.000100
  linmin_xtol_   0.010000
  powell nthiter 0: fret = -1.053815
#@#  4  194  -1.36407 -4.96501 2.05701 -2.00000 0.00000 4.00000   -1.0539289
#@#  4  195  -1.25765 -4.96501 2.05701 -2.00000 0.00000 4.00000   -1.0539325
#@#  4  196  -1.27855 -4.96501 2.05701 -2.00000 0.00000 4.00000   -1.0539328
#@#  4  198  -1.29855 -4.96501 2.05701 -2.00000 0.00000 4.00000   -1.0539329
#@#  4  203  -1.29855 -6.58305 2.05701 -2.00000 0.00000 4.00000   -1.0544530
#@#  4  204  -1.29855 -6.41761 2.05701 -2.00000 0.00000 4.00000   -1.0544821
#@#  4  207  -1.29855 -6.20568 2.05701 -2.00000 0.00000 4.00000   -1.0544887
#@#  4  208  -1.29855 -6.26893 2.05701 -2.00000 0.00000 4.00000   -1.0544895
#@#  4  210  -1.29855 -6.24893 2.05701 -2.00000 0.00000 4.00000   -1.0544897
#@#  4  217  -1.29855 -6.24893 2.43897 -2.00000 0.00000 4.00000   -1.0545912
#@#  4  218  -1.29855 -6.24893 2.56467 -2.00000 0.00000 4.00000   -1.0545982
#@#  4  223  -1.29855 -6.24893 2.56467 -3.61803 0.00000 4.00000   -1.0548054
#@#  4  224  -1.29855 -6.24893 2.56467 -3.15139 0.00000 4.00000   -1.0548700
#@#  4  233  -1.29855 -6.24893 2.56467 -3.15139 -1.61803 4.00000   -1.0554063
#@#  4  237  -1.29855 -6.24893 2.56467 -3.15139 -1.38197 4.00000   -1.0554223
#@#  4  246  -1.29855 -6.24893 2.56467 -3.15139 -1.38197 4.38197   -1.0554647
#@#  4  247  -1.29855 -6.24893 2.56467 -3.15139 -1.38197 4.35603   -1.0554651
  powell nthiter 1: fret = -1.055465
#@#  4  257  -1.21205 -6.24893 2.56467 -3.15139 -1.38197 4.35603   -1.0554707
#@#  4  259  -1.23421 -6.24893 2.56467 -3.15139 -1.38197 4.35603   -1.0554714
#@#  4  273  -1.23421 -6.18776 2.56467 -3.15139 -1.38197 4.35603   -1.0554715
#@#  4  281  -1.23421 -6.18776 2.42204 -3.15139 -1.38197 4.35603   -1.0554838
#@#  4  283  -1.23421 -6.18776 2.43204 -3.15139 -1.38197 4.35603   -1.0554839
#@#  4  291  -1.23421 -6.18776 2.43204 -2.76942 -1.38197 4.35603   -1.0554872
#@#  4  292  -1.23421 -6.18776 2.43204 -2.94480 -1.38197 4.35603   -1.0554988
#@#  4  294  -1.23421 -6.18776 2.43204 -2.92537 -1.38197 4.35603   -1.0554994
#@#  4  304  -1.23421 -6.18776 2.43204 -2.92537 -1.50745 4.35603   -1.0555016
#@#  4  318  -1.23421 -6.18776 2.43204 -2.92537 -1.50745 4.38098   -1.0555021
Powell done niters total = 1
OptTimeSec 20.3 sec
OptTimeMin  0.34 min
nEvals 320
Final optimized parameters  -1.23421359  -6.18776083   2.43204403  -2.92536616  -1.50744748   4.38098431 
Final matrix parameters -1.2342 -6.1878  2.4320 -2.9254 -1.5074  4.3910  1.0000  1.0000  1.0000  0.0000  0.0000  0.0000 
Final cost   -1.055502010414254
 

---------------------------------
Final  RefRAS-to-MovRAS
 0.99673   0.07636  -0.02631  -1.23421;
-0.07763   0.99568  -0.05102  -6.18776;
 0.02230   0.05289   0.99835   2.43204;
 0.00000   0.00000   0.00000   1.00000;
Final  RefVox-to-MovVox
-0.99673   0.02631   0.07636   265.19611;
 0.12420   0.08163   1.59307  -25.53609;
-0.03568  -1.59735   0.08463   497.22388;
 0.00000   0.00000   0.00000   1.00000;
Final matrix parameters -1.2342 -6.1878  2.4320 -2.9254 -1.5074  4.3810  0.0000  0.0000  0.0000  0.0000  0.0000  0.0000 
Final opt parameters -1.2342 -6.1878  2.4320 -2.9254 -1.5074  4.3810 
nhits = 377623 out of 32768000, Percent Overlap:  73.8
mri_coreg RunTimeSec 197.3 sec
To check run:
   tkregisterfv --mov /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/template.nii --targ /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/brainmask.mgz --reg /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/mri_coreg.lta --s sub-24563 --surfs 

mri_coreg done

mri_segreg --mov /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/template.nii --init-reg /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/reg.init.dat --out-reg /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/bbr.pass1.dat --subsamp-brute 100 --subsamp 100 --tol 1e-4 --tol1d 1e-3 --brute -4 4 4 --surf white --gm-proj-abs 2 --gm-gt-wm 0.5
7.3.2
setenv SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
cd /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg
mri_segreg --mov /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/template.nii --init-reg /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/reg.init.dat --out-reg /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/bbr.pass1.dat --subsamp-brute 100 --subsamp 100 --tol 1e-4 --tol1d 1e-3 --brute -4 4 4 --surf white --gm-proj-abs 2 --gm-gt-wm 0.5 
sysname  Linux
hostname cn4271
machine  x86_64
user     zugmana2
movvol /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/template.nii
regfile /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/reg.init.dat
subject sub-24563
dof 6
outregfile /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/bbr.pass1.dat
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
SynthSeed 1695556775
TransRandMax 0.000000
RotRandMax 0.000000
Translations 0.000000 0.000000 0.000000
Rotations   0.000000 0.000000 0.000000
Input reg
-0.99673  -0.07636   0.02631   0.68271;
 0.02230   0.05289   0.99835  -3.26009;
 0.07763  -0.99568   0.05102  -3.14421;
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
 0  -25.0 -25.0 -25.0   0.990967
 1  -25.0 -25.0  25.0   1.006654
 2  -25.0  25.0 -25.0   1.018222
 3  -25.0  25.0  25.0   0.993857
 4   25.0 -25.0 -25.0   1.000111
 5   25.0 -25.0  25.0   0.975538
 6   25.0  25.0 -25.0   1.000911
 7   25.0  25.0  25.0   0.982813
REL:  8  0.319824    7.969074  0.996134 rel = 0.321065 
Initial costs ----------------
Number of surface hits 4817
WM  Intensity   150.5950 +/-  19.0240
Ctx Intensity   178.9145 +/-  33.3007
Pct Contrast     15.7649 +/-  26.1067
Cost   0.3198
RelCost   0.3211

------------------------------------
Brute force preopt -4 4 4, n = 729
     0  -4.0000  -4.0000  -4.0000  -4.0000  -4.0000  -4.0000      0.9833   0.9833  0.0
     3  -4.0000  -4.0000  -4.0000  -4.0000   0.0000  -4.0000      0.9743   0.9743  0.0
     4  -4.0000  -4.0000  -4.0000  -4.0000   0.0000   0.0000      0.9552   0.9552  0.0
     6  -4.0000  -4.0000  -4.0000  -4.0000   4.0000  -4.0000      0.9527   0.9527  0.0
     7  -4.0000  -4.0000  -4.0000  -4.0000   4.0000   0.0000      0.8922   0.8922  0.0
    15  -4.0000  -4.0000  -4.0000   0.0000   4.0000  -4.0000      0.8783   0.8783  0.0
    33  -4.0000  -4.0000   0.0000  -4.0000   4.0000  -4.0000      0.8706   0.8706  0.0
    57  -4.0000  -4.0000   4.0000  -4.0000   0.0000  -4.0000      0.8515   0.8515  0.0
   118  -4.0000   0.0000   0.0000   0.0000  -4.0000   0.0000      0.8431   0.8431  0.0
   120  -4.0000   0.0000   0.0000   0.0000   0.0000  -4.0000      0.7859   0.7859  0.0
   361   0.0000   0.0000   0.0000   0.0000  -4.0000   0.0000      0.7833   0.7833  0.0
   363   0.0000   0.0000   0.0000   0.0000   0.0000  -4.0000      0.7499   0.7499  0.0
   364   0.0000   0.0000   0.0000   0.0000   0.0000   0.0000      0.3198   0.3198  0.0
Brute Force --------------------------
Min cost was 0.319824
Number of iterations   729
Search time 1.452985 sec
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
  powell nthiter 0: fret = 0.319824
   8  0.063  0.000  0.000  0.000  0.000  0.000   0.3171710154
  10  0.099  0.000  0.000  0.000  0.000  0.000   0.3171187935
  12  0.132  0.000  0.000  0.000  0.000  0.000   0.3170582826
  15  0.128  0.000  0.000  0.000  0.000  0.000   0.3170523682
  22  0.128 -0.618  0.000  0.000  0.000  0.000   0.3168713021
  26  0.128 -0.502  0.000  0.000  0.000  0.000   0.3148477421
  28  0.128 -0.516  0.000  0.000  0.000  0.000   0.3147075637
  30  0.128 -0.526  0.000  0.000  0.000  0.000   0.3146258775
  31  0.128 -0.537  0.000  0.000  0.000  0.000   0.3146056971
  32  0.128 -0.535  0.000  0.000  0.000  0.000   0.3145990360
  33  0.128 -0.533  0.000  0.000  0.000  0.000   0.3145986191
  36  0.128 -0.533  1.000  0.000  0.000  0.000   0.3112305807
  40  0.128 -0.533  0.618  0.000  0.000  0.000   0.3021161113
  41  0.128 -0.533  0.334  0.000  0.000  0.000   0.2995372945
  43  0.128 -0.533  0.412  0.000  0.000  0.000   0.2990813453
  44  0.128 -0.533  0.415  0.000  0.000  0.000   0.2990780409
  46  0.128 -0.533  0.416  0.000  0.000  0.000   0.2990776892
  54  0.128 -0.533  0.416 -0.159  0.000  0.000   0.2968761261
  56  0.128 -0.533  0.416 -0.124  0.000  0.000   0.2964611577
  60  0.128 -0.533  0.416 -0.119  0.000  0.000   0.2964466871
  62  0.128 -0.533  0.416 -0.120  0.000  0.000   0.2964459417
  75  0.128 -0.533  0.416 -0.120  0.009  0.000   0.2963874825
  76  0.128 -0.533  0.416 -0.120  0.010  0.000   0.2963870199
  82  0.128 -0.533  0.416 -0.120  0.010 -0.618   0.2956545446
  84  0.128 -0.533  0.416 -0.120  0.010 -0.319   0.2926740082
  87  0.128 -0.533  0.416 -0.120  0.010 -0.294   0.2924949675
  89  0.128 -0.533  0.416 -0.120  0.010 -0.273   0.2923704581
  91  0.128 -0.533  0.416 -0.120  0.010 -0.271   0.2923675159
  92  0.128 -0.533  0.416 -0.120  0.010 -0.270   0.2923660479
  94  0.128 -0.533  0.416 -0.120  0.010 -0.269   0.2923659512
  powell nthiter 1: fret = 0.292366
 104  0.232 -0.533  0.416 -0.120  0.010 -0.269   0.2903393962
 108  0.247 -0.533  0.416 -0.120  0.010 -0.269   0.2902888894
 109  0.242 -0.533  0.416 -0.120  0.010 -0.269   0.2902858616
 110  0.244 -0.533  0.416 -0.120  0.010 -0.269   0.2902850068
 120  0.244 -0.536  0.416 -0.120  0.010 -0.269   0.2902705431
 122  0.244 -0.541  0.416 -0.120  0.010 -0.269   0.2902534857
 132  0.244 -0.541  0.506 -0.120  0.010 -0.269   0.2882634230
 135  0.244 -0.541  0.516 -0.120  0.010 -0.269   0.2881855492
 146  0.244 -0.541  0.516 -0.107  0.010 -0.269   0.2880933962
 148  0.244 -0.541  0.516 -0.104  0.010 -0.269   0.2880914466
 149  0.244 -0.541  0.516 -0.103  0.010 -0.269   0.2880911163
 150  0.244 -0.541  0.516 -0.102  0.010 -0.269   0.2880905478
 162  0.244 -0.541  0.516 -0.102 -0.013 -0.269   0.2877316365
 176  0.244 -0.541  0.516 -0.102 -0.013 -0.227   0.2865874335
 177  0.244 -0.541  0.516 -0.102 -0.013 -0.218   0.2865367354
 179  0.244 -0.541  0.516 -0.102 -0.013 -0.219   0.2865365663
  powell nthiter 2: fret = 0.286537
 191  0.256 -0.541  0.516 -0.102 -0.013 -0.219   0.2864155576
 193  0.255 -0.541  0.516 -0.102 -0.013 -0.219   0.2864111854
 201  0.255 -0.539  0.516 -0.102 -0.013 -0.219   0.2863563130
 203  0.255 -0.505  0.516 -0.102 -0.013 -0.219   0.2861955711
 204  0.255 -0.519  0.516 -0.102 -0.013 -0.219   0.2860575015
 205  0.255 -0.520  0.516 -0.102 -0.013 -0.219   0.2860569277
 215  0.255 -0.520  0.512 -0.102 -0.013 -0.219   0.2860471160
 216  0.255 -0.520  0.513 -0.102 -0.013 -0.219   0.2860467698
 238  0.255 -0.520  0.513 -0.102 -0.014 -0.219   0.2860436334
 248  0.255 -0.520  0.513 -0.102 -0.014 -0.213   0.2860079466
  powell nthiter 3: fret = 0.286008
 273  0.255 -0.517  0.513 -0.102 -0.014 -0.213   0.2860068196
 275  0.255 -0.518  0.513 -0.102 -0.014 -0.213   0.2860057116
Powell done niters = 3
Computing relative cost
 0  -25.0 -25.0 -25.0   0.990633
 1  -25.0 -25.0  25.0   1.013784
 2  -25.0  25.0 -25.0   1.025054
 3  -25.0  25.0  25.0   0.981001
 4   25.0 -25.0 -25.0   1.013545
 5   25.0 -25.0  25.0   0.980029
 6   25.0  25.0 -25.0   0.997207
 7   25.0  25.0  25.0   0.984327
REL:  8  0.286006    7.985579  0.998197 rel = 0.286522 
Number of iterations     3
Min cost was 0.286006
Number of FunctionCalls   318
TolPowell 0.000100
nMaxItersPowell 36
OptimizationTime 0.552039 sec
Parameters at optimum (transmm)  0.25468 -0.51776  0.51301
Parameters at optimum (rotdeg) -0.10244 -0.01425 -0.21251 
Final costs ----------------
Number of surface hits 4817
WM  Intensity   150.2277 +/-  18.4839
Ctx Intensity   178.2026 +/-  35.0471
Pct Contrast     15.2448 +/-  28.7035
Cost   0.2860
RelCost   0.3211
Reg at min cost was 
-0.99666  -0.07592   0.03000   0.92605;
 0.02613   0.05139   0.99834  -3.78597;
 0.07734  -0.99579   0.04924  -2.62519;
 0.00000   0.00000   0.00000   1.00000;

Writing optimal reg to /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/bbr.pass1.dat, type = 14 
Original Reg 
-0.99673  -0.07636   0.02631   0.68271;
 0.02230   0.05289   0.99835  -3.26009;
 0.07763  -0.99568   0.05102  -3.14421;
 0.00000   0.00000   0.00000   1.00000;

Original Reg - Optimal Reg
-0.00007  -0.00044  -0.00369  -0.24334;
-0.00384   0.00150   0.00001   0.52589;
 0.00029   0.00011   0.00178  -0.51902;
 0.00000   0.00000   0.00000   0.00000;

Computing change in lh position
LH rmsDiffMean 0.843193
Computing change in rh position
Surface-RMS-Diff-mm 0.769698 0.098033 0.973367
mri_segreg done
mri_segreg --mov /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/template.nii --init-reg /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/bbr.pass1.dat --out-reg /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.dat --interp trilinear --wm-proj-abs 1 --tol 1e-8 --tol1d 1e-3 --c0 0 --mincost /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.dat.mincost --dof 6 --nmax 36 --param /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.dat.param --surf white --brute -0.1 0.1 0.1 --cur-reg /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/reg.curopt.dat --gm-proj-abs 2 --nsub 1 --gm-gt-wm 0.5
7.3.2
setenv SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
cd /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg
mri_segreg --mov /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/template.nii --init-reg /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/bbr.pass1.dat --out-reg /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.dat --interp trilinear --wm-proj-abs 1 --tol 1e-8 --tol1d 1e-3 --c0 0 --mincost /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.dat.mincost --dof 6 --nmax 36 --param /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.dat.param --surf white --brute -0.1 0.1 0.1 --cur-reg /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/reg.curopt.dat --gm-proj-abs 2 --nsub 1 --gm-gt-wm 0.5 
sysname  Linux
hostname cn4271
machine  x86_64
user     zugmana2
movvol /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/template.nii
regfile /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/tmp.bbregister.942778/bbr.pass1.dat
subject sub-24563
dof 6
outregfile /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.dat
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
SynthSeed 1695709390
TransRandMax 0.000000
RotRandMax 0.000000
Translations 0.000000 0.000000 0.000000
Rotations   0.000000 0.000000 0.000000
Input reg
-0.99666  -0.07592   0.03000   0.92605;
 0.02613   0.05139   0.99834  -3.78597;
 0.07734  -0.99579   0.04924  -2.62519;
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
 0  -25.0 -25.0 -25.0   0.984461
 1  -25.0 -25.0  25.0   0.985454
 2  -25.0  25.0 -25.0   1.006190
 3  -25.0  25.0  25.0   0.975036
 4   25.0 -25.0 -25.0   0.998878
 5   25.0 -25.0  25.0   0.986829
 6   25.0  25.0 -25.0   1.001344
 7   25.0  25.0  25.0   0.998564
REL:  8  0.264503    7.936755  0.992094 rel = 0.26661 
Initial costs ----------------
Number of surface hits 481472
WM  Intensity   149.1419 +/-  16.2466
Ctx Intensity   177.4742 +/-  34.7635
Pct Contrast     15.4723 +/-  28.4515
Cost   0.2645
RelCost   0.2666

------------------------------------
Brute force preopt -0.1 0.1 0.1, n = 729
     0  -0.1000  -0.1000  -0.1000  -0.1000  -0.1000  -0.1000      0.2524   0.2524  0.0
    27  -0.1000  -0.1000   0.0000  -0.1000  -0.1000  -0.1000      0.2498   0.2498  0.0
    30  -0.1000  -0.1000   0.0000  -0.1000   0.0000  -0.1000      0.2480   0.2480  0.0
    54  -0.1000  -0.1000   0.1000  -0.1000  -0.1000  -0.1000      0.2474   0.2474  0.0
    57  -0.1000  -0.1000   0.1000  -0.1000   0.0000  -0.1000      0.2453   0.2453  0.0
Brute Force --------------------------
Min cost was 0.245276
Number of iterations   729
Search time 1.338603 sec
Parameters at best (transmm, rotdeg)
 -0.100  -0.100   0.100 -0.100  0.000 -0.100 
--------------------------------------------

Starting Powell Minimization
Init Powel Params dof = 6
0 -0.1
1 -0.1
2 0.1
3 -0.1
4 0
5 -0.1
fs_powell::minimize
  nparams 6
  maxfev 36
  ftol   0.000000
  linmin_xtol_   0.001000
  powell nthiter 0: fret = 0.262919
   7 -0.148 -0.100  0.100 -0.100  0.000 -0.100   0.2628465665
  10 -0.171 -0.100  0.100 -0.100  0.000 -0.100   0.2628350646
  22 -0.171  0.023  0.100 -0.100  0.000 -0.100   0.2626108688
  23 -0.171 -0.013  0.100 -0.100  0.000 -0.100   0.2625283408
  24 -0.171 -0.019  0.100 -0.100  0.000 -0.100   0.2625283347
  28 -0.171 -0.024  0.100 -0.100  0.000 -0.100   0.2625281386
  31 -0.171 -0.022  0.100 -0.100  0.000 -0.100   0.2625280500
  38 -0.171 -0.022  0.482 -0.100  0.000 -0.100   0.2619115786
  39 -0.171 -0.022  0.319 -0.100  0.000 -0.100   0.2614599072
  40 -0.171 -0.022  0.331 -0.100  0.000 -0.100   0.2614572681
  43 -0.171 -0.022  0.353 -0.100  0.000 -0.100   0.2614337110
  44 -0.171 -0.022  0.367 -0.100  0.000 -0.100   0.2614303801
  45 -0.171 -0.022  0.365 -0.100  0.000 -0.100   0.2614291070
  46 -0.171 -0.022  0.361 -0.100  0.000 -0.100   0.2614285479
  48 -0.171 -0.022  0.362 -0.100  0.000 -0.100   0.2614283657
  56 -0.171 -0.022  0.363 -0.250  0.000 -0.100   0.2611465856
  58 -0.171 -0.022  0.363 -0.231  0.000 -0.100   0.2611443647
  59 -0.171 -0.022  0.363 -0.232  0.000 -0.100   0.2611443544
  67 -0.171 -0.022  0.363 -0.232 -0.176 -0.100   0.2600099290
  69 -0.171 -0.022  0.363 -0.232 -0.177 -0.100   0.2600091673
  71 -0.171 -0.022  0.363 -0.232 -0.178 -0.100   0.2600089476
  81 -0.171 -0.022  0.363 -0.232 -0.178 -0.165   0.2599406113
  82 -0.171 -0.022  0.363 -0.232 -0.178 -0.141   0.2599180044
  83 -0.171 -0.022  0.363 -0.232 -0.178 -0.143   0.2599171276
  84 -0.171 -0.022  0.363 -0.232 -0.178 -0.146   0.2599165428
  85 -0.171 -0.022  0.363 -0.232 -0.178 -0.145   0.2599165015
  powell nthiter 1: fret = 0.259917
  92  0.211 -0.022  0.363 -0.232 -0.178 -0.145   0.2595478220
  93  0.065 -0.022  0.363 -0.232 -0.178 -0.145   0.2591633029
  95  0.104 -0.022  0.363 -0.232 -0.178 -0.145   0.2590714171
  97  0.108 -0.022  0.363 -0.232 -0.178 -0.145   0.2590689026
  98  0.111 -0.022  0.363 -0.232 -0.178 -0.145   0.2590668985
 103  0.112 -0.022  0.363 -0.232 -0.178 -0.145   0.2590667104
 104  0.113 -0.022  0.363 -0.232 -0.178 -0.145   0.2590665669
 111  0.113  0.099  0.363 -0.232 -0.178 -0.145   0.2589010672
 126  0.113  0.099  0.357 -0.232 -0.178 -0.145   0.2588996960
 127  0.113  0.099  0.356 -0.232 -0.178 -0.145   0.2588994810
 131  0.113  0.099  0.355 -0.232 -0.178 -0.145   0.2588994556
 138  0.113  0.099  0.355 -0.149 -0.178 -0.145   0.2586697397
 140  0.113  0.099  0.355 -0.143 -0.178 -0.145   0.2586679061
 143  0.113  0.099  0.355 -0.140 -0.178 -0.145   0.2586675306
 145  0.113  0.099  0.355 -0.138 -0.178 -0.145   0.2586674359
 153  0.113  0.099  0.355 -0.138 -0.261 -0.145   0.2581031372
 154  0.113  0.099  0.355 -0.138 -0.361 -0.145   0.2579455829
 155  0.113  0.099  0.355 -0.138 -0.338 -0.145   0.2579354898
 156  0.113  0.099  0.355 -0.138 -0.341 -0.145   0.2579333845
 157  0.113  0.099  0.355 -0.138 -0.346 -0.145   0.2579317751
 159  0.113  0.099  0.355 -0.138 -0.345 -0.145   0.2579317281
 169  0.113  0.099  0.355 -0.138 -0.345 -0.201   0.2578082779
 171  0.113  0.099  0.355 -0.138 -0.345 -0.193   0.2578034456
 174  0.113  0.099  0.355 -0.138 -0.345 -0.194   0.2578033204
 176  0.113  0.099  0.355 -0.138 -0.345 -0.195   0.2578032991
  powell nthiter 2: fret = 0.257803
 186  0.128  0.099  0.355 -0.138 -0.345 -0.195   0.2577846520
 191  0.134  0.099  0.355 -0.138 -0.345 -0.195   0.2577809601
 192  0.135  0.099  0.355 -0.138 -0.345 -0.195   0.2577808744
 201  0.135  0.111  0.355 -0.138 -0.345 -0.195   0.2577753208
 202  0.135  0.110  0.355 -0.138 -0.345 -0.195   0.2577751706
 203  0.135  0.109  0.355 -0.138 -0.345 -0.195   0.2577751481
 213  0.135  0.109  0.354 -0.138 -0.345 -0.195   0.2577751335
 214  0.135  0.109  0.353 -0.138 -0.345 -0.195   0.2577750504
 217  0.135  0.109  0.319 -0.138 -0.345 -0.195   0.2577671133
 222  0.135  0.109  0.318 -0.138 -0.345 -0.195   0.2577669934
 232  0.135  0.109  0.318 -0.140 -0.345 -0.195   0.2577669175
 233  0.135  0.109  0.318 -0.141 -0.345 -0.195   0.2577669009
 242  0.135  0.109  0.318 -0.141 -0.310 -0.195   0.2577554184
 244  0.135  0.109  0.318 -0.141 -0.291 -0.195   0.2577526637
 245  0.135  0.109  0.318 -0.141 -0.299 -0.195   0.2577498916
 259  0.135  0.109  0.318 -0.141 -0.299 -0.192   0.2577474385
 261  0.135  0.109  0.318 -0.141 -0.299 -0.189   0.2577459082
 262  0.135  0.109  0.318 -0.141 -0.299 -0.188   0.2577457323
  powell nthiter 3: fret = 0.257746
 275  0.140  0.109  0.318 -0.141 -0.299 -0.188   0.2577437631
 276  0.139  0.109  0.318 -0.141 -0.299 -0.188   0.2577435462
 285  0.139  0.097  0.318 -0.141 -0.299 -0.188   0.2577410875
 286  0.139  0.101  0.318 -0.141 -0.299 -0.188   0.2577407001
 296  0.139  0.101  0.326 -0.141 -0.299 -0.188   0.2577406022
 299  0.139  0.101  0.329 -0.141 -0.299 -0.188   0.2577405256
 309  0.139  0.101  0.329 -0.147 -0.299 -0.188   0.2577393644
 316  0.139  0.101  0.329 -0.149 -0.299 -0.188   0.2577389996
 338  0.139  0.101  0.329 -0.149 -0.299 -0.186   0.2577382532
 340  0.139  0.101  0.329 -0.149 -0.299 -0.185   0.2577380999
 341  0.139  0.101  0.329 -0.149 -0.299 -0.184   0.2577379963
  powell nthiter 4: fret = 0.257738
 355  0.141  0.101  0.329 -0.149 -0.299 -0.184   0.2577377597
 357  0.140  0.101  0.329 -0.149 -0.299 -0.184   0.2577376873
 375  0.140  0.101  0.331 -0.149 -0.299 -0.184   0.2577375305
 379  0.140  0.101  0.332 -0.149 -0.299 -0.184   0.2577374894
  powell nthiter 5: fret = 0.257737
 426  0.139  0.101  0.332 -0.149 -0.299 -0.184   0.2577374681
 445  0.139  0.101  0.333 -0.149 -0.299 -0.184   0.2577374313
 446  0.139  0.101  0.334 -0.149 -0.299 -0.184   0.2577374162
 467  0.139  0.101  0.334 -0.149 -0.301 -0.184   0.2577370053
 468  0.139  0.101  0.334 -0.149 -0.302 -0.184   0.2577369520
 469  0.139  0.101  0.334 -0.149 -0.303 -0.184   0.2577369416
 482  0.139  0.101  0.334 -0.149 -0.303 -0.185   0.2577365318
  powell nthiter 6: fret = 0.257737
 497  0.138  0.101  0.334 -0.149 -0.303 -0.185   0.2577362579
 516  0.138  0.100  0.340 -0.149 -0.303 -0.185   0.2577344334
 517  0.138  0.100  0.341 -0.149 -0.303 -0.185   0.2577343940
 527  0.138  0.100  0.341 -0.152 -0.303 -0.185   0.2577342677
 538  0.138  0.100  0.341 -0.152 -0.304 -0.185   0.2577340937
 539  0.138  0.100  0.341 -0.152 -0.305 -0.185   0.2577339902
 552  0.138  0.100  0.341 -0.152 -0.305 -0.189   0.2577337583
 553  0.138  0.100  0.341 -0.152 -0.305 -0.187   0.2577332883
 555  0.137  0.099  0.347 -0.154 -0.307 -0.190   0.2577317716
 560  0.136  0.098  0.351 -0.156 -0.308 -0.191   0.2577317235
 562  0.136  0.099  0.349 -0.155 -0.308 -0.190   0.2577315472
  powell nthiter 7: fret = 0.257732
 592  0.136  0.104  0.349 -0.155 -0.308 -0.190   0.2577287131
 594  0.136  0.106  0.349 -0.155 -0.308 -0.190   0.2577283331
 595  0.136  0.107  0.349 -0.155 -0.308 -0.190   0.2577283307
 606  0.136  0.107  0.349 -0.155 -0.308 -0.193   0.2577278437
 617  0.136  0.107  0.349 -0.158 -0.308 -0.193   0.2577264373
 618  0.136  0.107  0.349 -0.159 -0.308 -0.193   0.2577261535
 629  0.136  0.107  0.349 -0.159 -0.309 -0.193   0.2577261339
 632  0.135  0.106  0.355 -0.162 -0.311 -0.195   0.2577261140
 636  0.136  0.106  0.353 -0.161 -0.310 -0.194   0.2577255154
 644  0.136  0.106  0.353 -0.161 -0.310 -0.194   0.2577255108
 645  0.136  0.106  0.353 -0.161 -0.310 -0.194   0.2577254931
  powell nthiter 8: fret = 0.257726
 657  0.137  0.106  0.353 -0.161 -0.310 -0.194   0.2577254616
 700  0.137  0.106  0.353 -0.161 -0.309 -0.194   0.2577251156
 702  0.137  0.106  0.353 -0.161 -0.307 -0.194   0.2577249842
 714  0.137  0.106  0.353 -0.161 -0.307 -0.194   0.2577249723
 715  0.137  0.106  0.353 -0.161 -0.307 -0.194   0.2577249646
  powell nthiter 9: fret = 0.257725
 732  0.135  0.106  0.353 -0.161 -0.308 -0.194   0.2577246655
 786  0.135  0.106  0.353 -0.161 -0.308 -0.194   0.2577245009
 787  0.135  0.106  0.353 -0.161 -0.308 -0.194   0.2577244937
  powell nthiter 10: fret = 0.257724
 859  0.135  0.106  0.353 -0.161 -0.308 -0.194   0.2577244735
  powell nthiter 11: fret = 0.257724
Powell done niters = 11
Computing relative cost
 0  -25.0 -25.0 -25.0   0.982083
 1  -25.0 -25.0  25.0   0.991901
 2  -25.0  25.0 -25.0   1.003243
 3  -25.0  25.0  25.0   0.977929
 4   25.0 -25.0 -25.0   1.003245
 5   25.0 -25.0  25.0   0.988447
 6   25.0  25.0 -25.0   1.001799
 7   25.0  25.0  25.0   1.000820
REL:  8  0.257724    7.949467  0.993683 rel = 0.259363 
Number of iterations    11
Min cost was 0.257724
Number of FunctionCalls   933
TolPowell 0.000000
nMaxItersPowell 36
OptimizationTime 75.106374 sec
Parameters at optimum (transmm)  0.13541  0.10607  0.35337
Parameters at optimum (rotdeg) -0.16094 -0.30759 -0.19437 
Final costs ----------------
Number of surface hits 481472
WM  Intensity   149.4248 +/-  16.5391
Ctx Intensity   177.5897 +/-  36.5907
Pct Contrast     15.0783 +/-  30.6302
Cost   0.2577
RelCost   0.2666
Reg at min cost was 
-0.99697  -0.07041   0.03313   1.06261;
 0.02973   0.04884   0.99836  -3.69043;
 0.07191  -0.99632   0.04659  -2.25617;
 0.00000   0.00000   0.00000   1.00000;

Writing optimal reg to /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.dat, type = 14 
Original Reg 
-0.99666  -0.07592   0.03000   0.92605;
 0.02613   0.05139   0.99834  -3.78597;
 0.07734  -0.99579   0.04924  -2.62519;
 0.00000   0.00000   0.00000   1.00000;

Original Reg - Optimal Reg
 0.00031  -0.00551  -0.00314  -0.13655;
-0.00360   0.00256  -0.00003  -0.09554;
 0.00543   0.00053   0.00264  -0.36903;
 0.00000   0.00000   0.00000   0.00000;

Computing change in lh position
LH rmsDiffMean 0.570917
Computing change in rh position
Surface-RMS-Diff-mm 0.492157 0.122831 0.781859
mri_segreg done
MinCost: 0.257724 149.424835 177.589676 15.078255 
tkregister2_cmdl --mov /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template.nii.gz --reg /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.dat --noedit --ltaout /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.lta
INFO: no target volume specified, assuming FreeSurfer orig volume.
target  volume orig
movable volume /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template.nii.gz
reg file       /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.dat
LoadVol        0
ZeroCRAS       0
7.3.2
Diagnostic Level -1
---- Input registration matrix --------
-0.99697  -0.07041   0.03313   1.06261;
 0.02973   0.04884   0.99836  -3.69043;
 0.07191  -0.99632   0.04659  -2.25617;
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
INFO: loading movable /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template.nii.gz
Tmov: --------------------
-0.80000   0.00000   0.00000   98.40000;
 0.00000   0.00000   0.50000  -128.00000;
 0.00000  -0.50000   0.00000   128.00000;
 0.00000   0.00000   0.00000   1.00000;
mkheaderreg = 0, float2int = 0
---- Input registration matrix --------
-0.99697  -0.07041   0.03313   1.06259;
 0.02973   0.04884   0.99836  -3.69042;
 0.07191  -0.99632   0.04659  -2.25615;
 0.00000   0.00000   0.00000   1.00000;
Determinant -1
subject = sub-24563
RegMat ---------------------------
-0.99697  -0.07041   0.03313   1.06261;
 0.02973   0.04884   0.99836  -3.69043;
 0.07191  -0.99632   0.04659  -2.25617;
 0.00000   0.00000   0.00000   1.00000;
Cleaning up
 
Started at Thu Sep 21 00:29:02 EDT 2023 
Ended   at Thu Sep 21 00:33:52 EDT 2023
BBR-Run-Time-Sec 290
 
bbregister Done
To check results, run:
tkregisterfv --mov /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template.nii.gz --reg /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/bbreg/sub-24563_ses-2_rec-norm_run-1_T2w_noise_corrected_template_bbreg_sub-24563.lta --surfs  --sd /lscratch/8536404/24563.out/sourcedata/freesurfer
 


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
* SUBJECTS_DIR : /lscratch/8536404/24563.out/sourcedata/freesurfer
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

