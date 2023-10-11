Node: single_subject_24563_wf (anat_preproc_wf (surface_recon_wf (autorecon_resume_wf (autorecon3 (freesurfer)
==============================================================================================================


 Hierarchy : fmriprep_23_2_wf.single_subject_24563_wf.anat_preproc_wf.surface_recon_wf.autorecon_resume_wf.autorecon3
 Exec ID : autorecon3


Original Inputs
---------------


* FLAIR_file : <undefined>
* T1_files : <undefined>
* T2_file : <undefined>
* args : <undefined>
* big_ventricles : <undefined>
* brainstem : <undefined>
* directive : autorecon3
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
* directive : autorecon3
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


* cmdline : recon-all -autorecon3 -openmp 16 -subjid sub-24563 -sd /lscratch/8536404/24563.out/sourcedata/freesurfer -nosphere -nosurfreg -nojacobian_white -noavgcurv -nocortparc -nopial -noparcstats -nocortparc2 -noparcstats2 -nocortparc3 -noparcstats3 -nopctsurfcon -nocortribbon -nobalabels
* duration : 677.763459
* hostname : cn4271
* prev_wd : /vf/users/EDB/TMSpilot/code
* working_dir : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/autorecon_resume_wf/autorecon3


Terminal output
~~~~~~~~~~~~~~~


 


Terminal - standard output
~~~~~~~~~~~~~~~~~~~~~~~~~~


 fs-check-version --s sub-24563 --o /lscratch/8536404/tmp.ZbI3Fu
Thu Sep 21 00:17:38 EDT 2023

setenv SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
cd /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/autorecon_resume_wf/autorecon3
/opt/freesurfer/bin/fs-check-version --s sub-24563 --o /lscratch/8536404/tmp.ZbI3Fu
-rwxrwxr-x 1 root root 18565 Aug  4  2022 /opt/freesurfer/bin/fs-check-version

freesurfer-linux-ubuntu22_x86_64-7.3.2-20220804-6354275
$Id$
Linux cn4271 4.18.0-425.19.2.el8_7.x86_64 #1 SMP Tue Apr 4 22:38:11 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
pid 941224
Current FS Version freesurfer-linux-ubuntu22_x86_64-7.3.2-20220804-6354275
bstampfile exists /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/scripts/build-stamp.txt
Subject FS Version: freesurfer-linux-ubuntu22_x86_64-7.3.2-20220804-6354275
No constraints on version because REQ=UnSet and FsVerFile=NotThere
#@#% fs-check-version match = 1
fs-check-version Done
INFO: SUBJECTS_DIR is /lscratch/8536404/24563.out/sourcedata/freesurfer
Actual FREESURFER_HOME /opt/freesurfer
-rw-rw-r-- 1 zugmana2 zugmana2 353595 Sep 21 00:05 /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/scripts/recon-all.log
Linux cn4271 4.18.0-425.19.2.el8_7.x86_64 #1 SMP Tue Apr 4 22:38:11 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/transforms /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563 
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563 
#--------------------------------------------
#@# WhiteSurfs lh Thu Sep 21 00:17:38 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --adgws-in ../surf/autodet.gw.stats.lh.dat --seg aseg.presurf.mgz --threads 16 --wm wm.mgz --invol brain.finalsurfs.mgz --lh --i ../surf/lh.white.preaparc --o ../surf/lh.white --white --nsmooth 0 --rip-label ../label/lh.cortex.label --rip-bg --rip-surf ../surf/lh.white.preaparc --aparc ../label/lh.aparc.annot
   Update not needed
#--------------------------------------------
#@# WhiteSurfs rh Thu Sep 21 00:17:38 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --adgws-in ../surf/autodet.gw.stats.rh.dat --seg aseg.presurf.mgz --threads 16 --wm wm.mgz --invol brain.finalsurfs.mgz --rh --i ../surf/rh.white.preaparc --o ../surf/rh.white --white --nsmooth 0 --rip-label ../label/rh.cortex.label --rip-bg --rip-surf ../surf/rh.white.preaparc --aparc ../label/rh.aparc.annot
   Update not needed
#@# white curv lh Thu Sep 21 00:17:38 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --curv-map ../surf/lh.white 2 10 ../surf/lh.curv
   Update not needed
#@# white area lh Thu Sep 21 00:17:38 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --area-map ../surf/lh.white ../surf/lh.area
   Update not needed
#@# pial curv lh Thu Sep 21 00:17:38 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --curv-map ../surf/lh.pial 2 10 ../surf/lh.curv.pial
   Update not needed
#@# pial area lh Thu Sep 21 00:17:38 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --area-map ../surf/lh.pial ../surf/lh.area.pial
   Update not needed
#@# thickness lh Thu Sep 21 00:17:38 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --thickness ../surf/lh.white ../surf/lh.pial 20 5 ../surf/lh.thickness
   Update not needed
#@# area and vertex vol lh Thu Sep 21 00:17:38 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --thickness ../surf/lh.white ../surf/lh.pial 20 5 ../surf/lh.thickness
   Update not needed
#@# white curv rh Thu Sep 21 00:17:38 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --curv-map ../surf/rh.white 2 10 ../surf/rh.curv
   Update not needed
#@# white area rh Thu Sep 21 00:17:38 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --area-map ../surf/rh.white ../surf/rh.area
   Update not needed
#@# pial curv rh Thu Sep 21 00:17:38 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --curv-map ../surf/rh.pial 2 10 ../surf/rh.curv.pial
   Update not needed
#@# pial area rh Thu Sep 21 00:17:38 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --area-map ../surf/rh.pial ../surf/rh.area.pial
   Update not needed
#@# thickness rh Thu Sep 21 00:17:38 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --thickness ../surf/rh.white ../surf/rh.pial 20 5 ../surf/rh.thickness
   Update not needed
#@# area and vertex vol rh Thu Sep 21 00:17:38 EDT 2023
cd /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri
mris_place_surface --thickness ../surf/rh.white ../surf/rh.pial 20 5 ../surf/rh.thickness
   Update not needed

#-----------------------------------------
#@# Curvature Stats lh Thu Sep 21 00:17:38 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf

 mris_curvature_stats -m --writeCurvatureFiles -G -o ../stats/lh.curv.stats -F smoothwm sub-24563 lh curv sulc 

             Toggling save flag on curvature files                       [ ok ]
                 Outputting results using filestem   [ ../stats/lh.curv.stats ]
             Toggling save flag on curvature files                       [ ok ]
                                   Setting surface    [ sub-24563/lh.smoothwm ]
                                Reading surface...                       [ ok ]
                                   Setting texture                     [ curv ]
                                Reading texture...                       [ ok ]
                                   Setting texture                     [ sulc ]
                                Reading texture...Gb_filter = 0
                       [ ok ]
      Calculating Discrete Principal Curvatures...
      Determining geometric order for vno faces... [####################] [ ok ]
                      Determining KH curvatures... [####################] [ ok ]
                    Determining k1k2 curvatures... [####################] [ ok ]
                                   deltaViolations                      [ 527 ]
Gb_filter = 0

#-----------------------------------------
#@# Curvature Stats rh Thu Sep 21 00:17:42 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf

 mris_curvature_stats -m --writeCurvatureFiles -G -o ../stats/rh.curv.stats -F smoothwm sub-24563 rh curv sulc 

             Toggling save flag on curvature files                       [ ok ]
                 Outputting results using filestem   [ ../stats/rh.curv.stats ]
             Toggling save flag on curvature files                       [ ok ]
                                   Setting surface    [ sub-24563/rh.smoothwm ]
                                Reading surface...                       [ ok ]
                                   Setting texture                     [ curv ]
                                Reading texture...                       [ ok ]
                                   Setting texture                     [ sulc ]
                                Reading texture...Gb_filter = 0
                       [ ok ]
      Calculating Discrete Principal Curvatures...
      Determining geometric order for vno faces... [####################] [ ok ]
                      Determining KH curvatures... [####################] [ ok ]
                    Determining k1k2 curvatures... [####################] [ ok ]
                                   deltaViolations                      [ 472 ]
Gb_filter = 0
#-----------------------------------------
#@# Relabel Hypointensities Thu Sep 21 00:17:45 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri

 mri_relabel_hypointensities aseg.presurf.mgz ../surf aseg.presurf.hypos.mgz 

reading input surface ../surf/lh.white...
relabeling lh hypointensities...
1761 voxels changed to hypointensity...
reading input surface ../surf/rh.white...
relabeling rh hypointensities...
2411 voxels changed to hypointensity...
3509 hypointense voxels neighboring cortex changed
#-----------------------------------------
#@# APas-to-ASeg Thu Sep 21 00:18:09 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri

 mri_surf2volseg --o aseg.mgz --i aseg.presurf.hypos.mgz --fix-presurf-with-ribbon /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/ribbon.mgz --threads 16 --lh-cortex-mask /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.cortex.label --lh-white /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.white --lh-pial /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.pial --rh-cortex-mask /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.cortex.label --rh-white /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.white --rh-pial /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.pial 

SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
outvol aseg.mgz
16 avail.processors, using 16
Loading aseg.presurf.hypos.mgz
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri/ribbon.mgz
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.white
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.pial
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.cortex.label
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.white
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.pial
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.cortex.label
Done loading
  0  60  80 280 240 200 260 120 100 300 140 160 220 180  20  40 301  21  61   1 281 261  41 302 282  62  22   2 262 303 283  42  63 304 284  23   3 263 305 285  64 306  24   4 286 264  65  43 307 287  25   5 265 308  66 288 309   6 266  26  67 289 310  44   7 290 267 311  68  27 291 312   8  69 268  28  45 313 292   9  70 269 314 293  46  29  10  71 315 294  47 270  11  30  72 316 295  12  48 271  31 317 296  49 318 297 272  73  32  13 319 
298  50 273  33 299 
 14  74  51 274  34  15  52 275  35  16  53 276  36  17  54 277  37  18  55 278  38  19 
279 
 56  39 
 81  75  57  58  59 
 76  77 241  78 121 101  79 
221  82 242 201  83 243 244 245 246 102 247 248  84 249 250 222 251 252 253 254 255 256 257 258 122 259 
 85 223 202 103  86 181 123 224  87 182 104 203  88 225 124  89 183 161  90 125 204 105 141 184 126 226 205 127  91 185 162 106 128 206 186 129  92 227 107 130 187 207 131 163  93 188 108 132 208 133 189  94 134 209 228 164 135 190 109 136 142 191  95 210 137 165 192 138 193 110  96 229 166 139 
211 194 195 167  97 111 212 196 230 168 112  98 197 213  99 
198 143 169 214 231 113 232 199 
215 233 170 114 234 216 144 235 217 171 115 236 218 145 237 219 
116 238 146 172 239 
117 147 118 119 
173 148 149 174 150 175 151 176 152 177 153 154 178 155 179 
156 157 158 159 

nrelabeled = 685651
ndotcheck = 0
Starting Surf2VolSeg free
free done
#VMPC# mri_surf2volseg VmPeak  2543444
mri_surf2volseg done

 mri_brainvol_stats sub-24563 

ComputeBrainVolumeStats2 VoxelVol=0.511991, KeepCSF=1
  #CBVS2 MaskVol              1470145.4
  #CBVS2 BrainSegVol          1199699.3
  #CBVS2 BrainSegVolNotVent   1187224.1
  #CBVS2 SupraTentVol         1059831.0
  #CBVS2 SupraTentVolNotVent  1047355.8
  #CBVS2 lhCtxGM               244017.3
  #CBVS2 rhCtxGM               250117.2
  #CBVS2 lhCerebralWM          241655.8
  #CBVS2 rhCerebralWM          247436.6
  #CBVS2 SubCortGMVol           63887.3
  #CBVS2 CerebellumVol         139868.3
  #CBVS2 CerebellumGMVol       111047.8
  #CBVS2 VentChorVol             9483.1
  #CBVS2 3rd4th5thCSF            2992.1
  #CBVS2 AllCSF                 12475.2
  #CBVS2 CCVol                   3218.4
#-----------------------------------------
#@# AParc-to-ASeg aparc Thu Sep 21 00:18:27 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri

 mri_surf2volseg --o aparc+aseg.mgz --label-cortex --i aseg.mgz --threads 16 --lh-annot /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.aparc.annot 1000 --lh-cortex-mask /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.cortex.label --lh-white /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.white --lh-pial /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.pial --rh-annot /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.aparc.annot 2000 --rh-cortex-mask /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.cortex.label --rh-white /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.white --rh-pial /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.pial 

SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
outvol aparc+aseg.mgz
16 avail.processors, using 16
Loading aseg.mgz
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.white
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.pial
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.cortex.label
Ripping lh vertices labeled not in lh.cortex.label
  ripped 13332 vertices from lh hemi
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.aparc.annot
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.white
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.pial
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.cortex.label
Ripping rh vertices labeled not in rh.cortex.label
  ripped 13549 vertices from rh hemi
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.aparc.annot
Done loading
  0 180  60  40 300 280 260 200 160 140 120  20 220  80 240 100  21 301 261  41   1 281  61 262 282  42  22 302  62   2 263 283  43  63  23 284 264 303  44   3  64  24 265 285  45 304   4  25  65 266 286  46  26  66   5 305 267 287  47  27  67   6 268 288 306  48  28  68 269 289   7  49 307  69 290 270  29  50  70   8 308 291 271  30  51  71 292 272 309  52  31  72 293 273   9  53 310  32 294 274  54 295  33 275 311  55  73 296 276  34  10  56 312 297 277  35  57  36 298 278 313  58  37 299 
279 
 59 
 38 314  39 
 11 315 316  12 317 318  13 319 
 14  15  74  16  17  18  19 
 75 241 242 243 244 245 246 247 248 249 250 251 252 253 254 255 256 257 258 259 
 76 161  77  81  78 162  79 
141  82 181 201 221 163 121  83 101 182 142 164 202 222  84 183 143  85 165 122 203 102 184 223  86 166 144 185 204 123  87 103 167 224 186 145 205 124 187  88 168 225 206 146 188 125 104  89 169 226 189 126 147 207 227 170  90 190 105 228 171 127 148 208  91 191 172 229 149 128  92 106 192 209 230 173  93 129 150 193 210 231 107 130  94 174 232 151 211 194 233 131  95 152 108 234 175 195 132 212 235  96 236 133 196 153 176 237 109 238 239 
213 197  97 134 177 154 135 198 110  98 178 214 136 155 199 
179 
 99 
137 156 111 215 138 157 216 158 139 
159 
112 217 218 113 219 
114 115 116 117 118 119 

nrelabeled = 965529
ndotcheck = 66419
Starting Surf2VolSeg free
free done
#VMPC# mri_surf2volseg VmPeak  2512648
mri_surf2volseg done
#-----------------------------------------
#@# AParc-to-ASeg aparc.a2009s Thu Sep 21 00:20:35 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri

 mri_surf2volseg --o aparc.a2009s+aseg.mgz --label-cortex --i aseg.mgz --threads 16 --lh-annot /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.aparc.a2009s.annot 11100 --lh-cortex-mask /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.cortex.label --lh-white /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.white --lh-pial /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.pial --rh-annot /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.aparc.a2009s.annot 12100 --rh-cortex-mask /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.cortex.label --rh-white /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.white --rh-pial /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.pial 

SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
outvol aparc.a2009s+aseg.mgz
16 avail.processors, using 16
Loading aseg.mgz
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.white
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.pial
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.cortex.label
Ripping lh vertices labeled not in lh.cortex.label
  ripped 13332 vertices from lh hemi
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.aparc.a2009s.annot
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.white
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.pial
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.cortex.label
Ripping rh vertices labeled not in rh.cortex.label
  ripped 13549 vertices from rh hemi
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.aparc.a2009s.annot
Done loading
  0  60  80 100 240 180  20 160 120 300 260  40 140 220 200 280  61  41 301 281  21   1 261  62 302  42   2 282 303 262  63  43   3  64 263 304 283   4  44 305  65 264  22 284  45 306  66 265 307  67 285   5 266 308  68 286   6 309 267  69  23  46 310 287 268  70  24 311  47 288   7  71 269 312  48  72 289 270 313  25  49 271 314  26 290   8 315  50   9  73 272 291 316 273  51 292  27 317 274  52  28 318 293 275 319 
 10  53 294 276  11  54  12 295 277  29  55  13 296 278  30  56 279 
297  31  57  14 298  32  58 299 
 33  59 
 15  34  74  35  16  36  37  17  38  39 
 18  19 
241  75 242 243 244 245 246 247 248 249 250 251 252 253 254 255 256 257 258 259 
 76 161  77  81  78  79 
181 162  82 221 201 141 121 182 163  83 101 222 142 183 202 164 223 143  84 165 203 122 184 224 144 166 204 225 102  85 145 167 185 123 226  86 205 146 186 168 227 124 103  87 187 169 125 228 147 206  88 229 170 188 126 104 148 189  89 127 230 207 171 149 190 105 128 191  90 231 150 172 208 192 129 232 106 151  91 193 130 173 209 152 233 107 131 194 174 234 153 108 132  92 210 235 133 154 109 175 195 236 211  93 134 110 176 237  94 155 238 212 196 177 239 
111 135  95 178 156 197 213 179 
112 157 136  96 158 159 
214 198 113 215 137 199 
114  97 216 138 139 
217  98 115 218 116 219 
 99 
117 118 119 

nrelabeled = 965529
ndotcheck = 66419
Starting Surf2VolSeg free
free done
#VMPC# mri_surf2volseg VmPeak  2512748
mri_surf2volseg done
#-----------------------------------------
#@# AParc-to-ASeg aparc.DKTatlas Thu Sep 21 00:22:45 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri

 mri_surf2volseg --o aparc.DKTatlas+aseg.mgz --label-cortex --i aseg.mgz --threads 16 --lh-annot /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.aparc.DKTatlas.annot 1000 --lh-cortex-mask /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.cortex.label --lh-white /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.white --lh-pial /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.pial --rh-annot /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.aparc.DKTatlas.annot 2000 --rh-cortex-mask /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.cortex.label --rh-white /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.white --rh-pial /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.pial 

SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
outvol aparc.DKTatlas+aseg.mgz
16 avail.processors, using 16
Loading aseg.mgz
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.white
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.pial
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.cortex.label
Ripping lh vertices labeled not in lh.cortex.label
  ripped 13332 vertices from lh hemi
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.aparc.DKTatlas.annot
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.white
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.pial
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.cortex.label
Ripping rh vertices labeled not in rh.cortex.label
  ripped 13549 vertices from rh hemi
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.aparc.DKTatlas.annot
Done loading
  0  20 280  60 100  80 120 260  40 300 240 180 200 220 160 140  21   1  41 301 261 281  61  62 262  42 302  22 282   2  63 263  43  64 264 303  23 283   3  65 265  44 304  66 266  24 284   4 267  67  45 305  25 285 268  68   5 306  46 269  69  26 286 307 270  70  47   6  27 271 287  71 308 272  72  48   7  28 288 273 309 274  49   8 310  29 289 275  73  50 276 311  30 290   9 277 312  51 278  31 291  10 279 
313  52  11 314  32 292  53 315  12  54  33 293 316  13  55 317  34 294  56 318  14  35 295 319 
 57  15 296  36  58  16  59 
297  37  74 298  38  17 299 
 39 
 18  19 
 75  76 241 242 243 244 245 246 247 248 249 250 251 252 253 254 255 256 257 258 259 
 77 161  81  78  79 
162 181 141  82 121 201 221 163 182 101  83 142 122  84 183 164 202 222  85 102 123 143  86 184 165 203 124 223  87 144 103 185 166 204  88 145 125 224 186 104 146  89 205 187 126 167 147 105 225 188  90 206 148 106 127 189 149 168 107  91 207 226 150 190 128 151 108  92 129 191 152 208 169 227 109  93 153 130 192 110 154 209  94 228 170 131 193 155 229 111 210  95 171 156 132 194 230 112 157 158 211  96 172 231 159 
195 133 113 232 196 212 173 134 233 197  97 114 174 213 234 135 198 235 175 115 214 236 136 199 
237  98 176 238 215 239 
116 137 177 216 138 178  99 
117 179 
217 139 
218 118 219 
119 

nrelabeled = 965529
ndotcheck = 66419
Starting Surf2VolSeg free
free done
#VMPC# mri_surf2volseg VmPeak  2512656
mri_surf2volseg done
#-----------------------------------------
#@# WMParc Thu Sep 21 00:24:40 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/mri

 mri_surf2volseg --o wmparc.mgz --label-wm --i aparc+aseg.mgz --threads 16 --lh-annot /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.aparc.annot 3000 --lh-cortex-mask /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.cortex.label --lh-white /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.white --lh-pial /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.pial --rh-annot /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.aparc.annot 4000 --rh-cortex-mask /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.cortex.label --rh-white /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.white --rh-pial /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.pial 

SUBJECTS_DIR /lscratch/8536404/24563.out/sourcedata/freesurfer
outvol wmparc.mgz
16 avail.processors, using 16
Loading aparc+aseg.mgz
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.white
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/lh.pial
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.cortex.label
Ripping lh vertices labeled not in lh.cortex.label
  ripped 13332 vertices from lh hemi
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/lh.aparc.annot
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.white
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/surf/rh.pial
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.cortex.label
Ripping rh vertices labeled not in rh.cortex.label
  ripped 13549 vertices from rh hemi
Loading /lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563/label/rh.aparc.annot
Done loading
  0 180  60  40  20 300 160 260 100 220 240 140  80 200 280 120 241  21  41 261 301   1  61 281  42  22 262 302  62   2 282  43  23 242 263 303  63   3  44  24 243 283 264 304  64   4  25  45 244 284 265 305  65   5  26  46 245 285 266 306  66   6  27  47 246 267 307 286  67   7 268 308  28  48 247 287  68   8  29 309 269  49 248   9 288  69 310  30 270  50 249  10  70 289 311 271  31  71  11  81 250  51  32 272 312 290  12  72 251  52  33 273 313 291  13  73 252  53  34 274 314 292  14 253  54  35 275  15  74 315 293 254  55  16  36 276 316 255 294  56  17  37 277 256 317  18 295  57  38 278 257  19 
318  58 296 258 279 
 39 
 75 319 
259 
297  59 
298 299 
161  76  82  77  83 162  78 101  84  79 
 85 221 121 102  86 163  87 141 103  88 222 164 122  89  90 104 181 201  91 165 105 223 142  92 166 106  93 224 167  94 107 143 123  95 108 225 202 168  96 109 144  97 182 110 226 169  98 111 124 227 145 203 170 112  99 
228 146 113 171 229 125 204 230 114 147 183 172 231 232 115 148 233 173 205 234 149 235 116 126 236 237 174 150 184 238 239 
206 117 151 207 175 127 185 152 208 118 176 186 153 128 209 119 
177 187 154 210 155 156 188 211 129 178 157 158 212 159 
179 
189 213 130 214 215 190 216 131 217 218 191 219 
132 192 193 133 194 134 195 196 135 197 136 198 199 
137 138 139 

nrelabeled = 948989
ndotcheck = 9310
Starting Surf2VolSeg free
free done
#VMPC# mri_surf2volseg VmPeak  2512648
mri_surf2volseg done

 mri_segstats --seed 1234 --seg mri/wmparc.mgz --sum stats/wmparc.stats --pv mri/norm.mgz --excludeid 0 --brainmask mri/brainmask.mgz --in mri/norm.mgz --in-intensity-name norm --in-intensity-units MR --subject sub-24563 --surf-wm-vol --ctab /opt/freesurfer/WMParcStatsLUT.txt --etiv 

setting seed for random number genererator to 1234

7.3.2
cwd 
cmdline mri_segstats --seed 1234 --seg mri/wmparc.mgz --sum stats/wmparc.stats --pv mri/norm.mgz --excludeid 0 --brainmask mri/brainmask.mgz --in mri/norm.mgz --in-intensity-name norm --in-intensity-units MR --subject sub-24563 --surf-wm-vol --ctab /opt/freesurfer/WMParcStatsLUT.txt --etiv 
sysname  Linux
hostname cn4271
machine  x86_64
user     zugmana2
whitesurfname  white
UseRobust  0
atlas_icv (eTIV) = 1642690 mm^3    (det: 1.185924 )
Loading mri/wmparc.mgz
Getting Brain Volume Statistics
Loading mri/norm.mgz
Loading mri/norm.mgz
Voxel Volume is 0.511991 mm^3
Generating list of segmentation ids
Found 390 segmentations
Computing statistics for each segmentation

Reporting on  70 segmentations
Using PrintSegStat
mri_segstats done
#--------------------------------------------
#@# ASeg Stats Thu Sep 21 00:28:04 EDT 2023
/lscratch/8536404/24563.out/sourcedata/freesurfer/sub-24563

 mri_segstats --seed 1234 --seg mri/aseg.mgz --sum stats/aseg.stats --pv mri/norm.mgz --empty --brainmask mri/brainmask.mgz --brain-vol-from-seg --excludeid 0 --excl-ctxgmwm --supratent --subcortgray --in mri/norm.mgz --in-intensity-name norm --in-intensity-units MR --etiv --surf-wm-vol --surf-ctx-vol --totalgray --euler --ctab /opt/freesurfer/ASegStatsLUT.txt --subject sub-24563 

setting seed for random number genererator to 1234

7.3.2
cwd 
cmdline mri_segstats --seed 1234 --seg mri/aseg.mgz --sum stats/aseg.stats --pv mri/norm.mgz --empty --brainmask mri/brainmask.mgz --brain-vol-from-seg --excludeid 0 --excl-ctxgmwm --supratent --subcortgray --in mri/norm.mgz --in-intensity-name norm --in-intensity-units MR --etiv --surf-wm-vol --surf-ctx-vol --totalgray --euler --ctab /opt/freesurfer/ASegStatsLUT.txt --subject sub-24563 
sysname  Linux
hostname cn4271
machine  x86_64
user     zugmana2
whitesurfname  white
UseRobust  0
atlas_icv (eTIV) = 1642690 mm^3    (det: 1.185924 )
Computing euler number
orig.nofix lheno =  -88, rheno = -68
orig.nofix lhholes =   45, rhholes = 35
Loading mri/aseg.mgz
Getting Brain Volume Statistics
Loading mri/norm.mgz
Loading mri/norm.mgz
Voxel Volume is 0.511991 mm^3
Generating list of segmentation ids
Found  50 segmentations
Computing statistics for each segmentation

Reporting on  45 segmentations
Using PrintSegStat
mri_segstats done

Started at Thu Sep 21 00:17:38 EDT 2023 
Ended   at Thu Sep 21 00:28:55 EDT 2023
#@#%# recon-all-run-time-hours 0.188
recon-all -s sub-24563 finished without error at Thu Sep 21 00:28:55 EDT 2023
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

