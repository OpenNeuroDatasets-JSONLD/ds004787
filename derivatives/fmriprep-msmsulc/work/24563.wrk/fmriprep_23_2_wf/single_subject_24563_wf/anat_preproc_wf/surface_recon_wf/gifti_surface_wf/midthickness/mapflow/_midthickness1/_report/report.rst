Node: freesurfer
================


 Hierarchy : _midthickness1
 Exec ID : _midthickness1


Original Inputs
---------------


* args : <undefined>
* distance : 0.5
* dt : <undefined>
* environ : {'SUBJECTS_DIR': '/opt/freesurfer/subjects'}
* graymid : <undefined>
* in_file : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.white
* nsurfaces : <undefined>
* out_name : midthickness
* pial : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.pial
* smooth_averages : <undefined>
* sphere : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.sphere
* spring : <undefined>
* subjects_dir : /opt/freesurfer/subjects
* thickness : True
* thickness_name : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.thickness
* write_iterations : <undefined>


Execution Inputs
----------------


* args : <undefined>
* distance : 0.5
* dt : <undefined>
* environ : {'SUBJECTS_DIR': '/opt/freesurfer/subjects'}
* graymid : <undefined>
* in_file : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.white
* nsurfaces : <undefined>
* out_name : midthickness
* pial : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.pial
* smooth_averages : <undefined>
* sphere : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.sphere
* spring : <undefined>
* subjects_dir : /opt/freesurfer/subjects
* thickness : True
* thickness_name : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.thickness
* write_iterations : <undefined>


Execution Outputs
-----------------


* out_file : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.midthickness


Runtime info
------------


* cmdline : mris_expand -pial /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.pial -thickness -thickness_name /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.thickness /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.white 0.5 /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.midthickness
* duration : 1541.58238
* hostname : cn4271
* prev_wd : /vf/users/EDB/TMSpilot/code
* working_dir : /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1


Terminal output
~~~~~~~~~~~~~~~


 


Terminal - standard output
~~~~~~~~~~~~~~~~~~~~~~~~~~


 reading pial surface from /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.pial
using distance as a % of thickness
using thickness file /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.thickness
expanding surface /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.white by 50.0% of thickness and writing it to /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.midthickness
reading thickness...
min=0.000, parallel=0.0092, normal=0.0000, spring=0.0000, ashburner=0.000, tsmooth=0.000
min=0.000, parallel=0.0090, normal=0.0000, spring=0.0000, ashburner=0.000, tsmooth=0.000
min=0.000, parallel=0.0308, normal=0.0000, spring=0.0000, ashburner=0.000, tsmooth=0.000
min=0.000, parallel=0.0305, normal=0.0000, spring=0.0000, ashburner=0.000, tsmooth=0.000
min=0.000, parallel=0.0339, normal=0.0000, spring=0.0000, ashburner=0.000, tsmooth=0.000
min=0.000, parallel=0.1060, normal=0.0000, spring=0.0000, ashburner=0.000, tsmooth=0.000
min=0.000, parallel=0.2796, normal=0.0000, spring=0.0000, ashburner=0.000, tsmooth=0.000
min=0.000, parallel=0.0303, normal=0.0000, spring=0.0000, ashburner=0.000, tsmooth=0.000
min=0.000, parallel=0.0295, normal=0.0000, spring=0.0000, ashburner=0.000, tsmooth=0.000
min=0.000, parallel=0.0305, normal=0.0000, spring=0.0000, ashburner=0.000, tsmooth=0.000
min=0.000, parallel=0.0305, normal=0.0000, spring=0.0000, ashburner=0.000, tsmooth=0.000
min=0.000, parallel=0.0081, normal=0.0000, spring=0.0000, ashburner=0.000, tsmooth=0.000
min=0.000, parallel=0.0090, normal=0.0000, spring=0.0000, ashburner=0.000, tsmooth=0.000
-01: dt=0.0000,   0 negative triangles  VmPeak 1724292
min=0.000, parallel=0.0080, normal=0.0000, spring=0.0000, ashburner=0.000, tsmooth=0.000
ending sse = 9390.659109
nrounds = 6
***************** integrating with averages = 16, niter = 40, l_spring = 0.000 ***********************

step 1 of 240     
step 2 of 240     
step 3 of 240     
step 4 of 240     
step 5 of 240     
step 6 of 240     
step 7 of 240     
step 8 of 240     
step 9 of 240     
step 10 of 240     
step 11 of 240     
step 12 of 240     
step 13 of 240     
step 14 of 240     
step 15 of 240     
step 16 of 240     
step 17 of 240     
step 18 of 240     
step 19 of 240     
step 20 of 240     
step 21 of 240     
step 22 of 240     
step 23 of 240     
step 24 of 240     
step 25 of 240     
step 26 of 240     
step 27 of 240     
step 28 of 240     
step 29 of 240     
step 30 of 240     
step 31 of 240     
step 32 of 240     
step 33 of 240     
step 34 of 240     
step 35 of 240     
step 36 of 240     
step 37 of 240     
step 38 of 240     
step 39 of 240     
step 40 of 240     ***************** integrating with averages = 8, niter = 40, l_spring = 0.000 ***********************

step 41 of 240     
step 42 of 240     
step 43 of 240     
step 44 of 240     
step 45 of 240     
step 46 of 240     
step 47 of 240     
step 48 of 240     
step 49 of 240     
step 50 of 240     
step 51 of 240     
step 52 of 240     
step 53 of 240     
step 54 of 240     
step 55 of 240     
step 56 of 240     
step 57 of 240     
step 58 of 240     
step 59 of 240     
step 60 of 240     
step 61 of 240     
step 62 of 240     
step 63 of 240     
step 64 of 240     
step 65 of 240     
step 66 of 240     
step 67 of 240     
step 68 of 240     
step 69 of 240     
step 70 of 240     
step 71 of 240     
step 72 of 240     
step 73 of 240     
step 74 of 240     
step 75 of 240     
step 76 of 240     
step 77 of 240     
step 78 of 240     
step 79 of 240     
step 80 of 240     ***************** integrating with averages = 4, niter = 40, l_spring = 0.000 ***********************

step 81 of 240     
step 82 of 240     
step 83 of 240     
step 84 of 240     
step 85 of 240     
step 86 of 240     
step 87 of 240     
step 88 of 240     
step 89 of 240     
step 90 of 240     
step 91 of 240     
step 92 of 240     
step 93 of 240     
step 94 of 240     
step 95 of 240     
step 96 of 240     
step 97 of 240     
step 98 of 240     
step 99 of 240     
step 100 of 240     
step 101 of 240     
step 102 of 240     
step 103 of 240     
step 104 of 240     
step 105 of 240     
step 106 of 240     
step 107 of 240     
step 108 of 240     
step 109 of 240     
step 110 of 240     
step 111 of 240     
step 112 of 240     
step 113 of 240     
step 114 of 240     
step 115 of 240     
step 116 of 240     
step 117 of 240     
step 118 of 240     
step 119 of 240     
step 120 of 240     ***************** integrating with averages = 2, niter = 40, l_spring = 0.000 ***********************

step 121 of 240     
step 122 of 240     
step 123 of 240     
step 124 of 240     
step 125 of 240     
step 126 of 240     
step 127 of 240     
step 128 of 240     
step 129 of 240     
step 130 of 240     
step 131 of 240     
step 132 of 240     
step 133 of 240     
step 134 of 240     
step 135 of 240     
step 136 of 240     
step 137 of 240     
step 138 of 240     
step 139 of 240     
step 140 of 240     
step 141 of 240     
step 142 of 240     
step 143 of 240     
step 144 of 240     
step 145 of 240     
step 146 of 240     
step 147 of 240     
step 148 of 240     
step 149 of 240     
step 150 of 240     
step 151 of 240     
step 152 of 240     
step 153 of 240     
step 154 of 240     
step 155 of 240     
step 156 of 240     
step 157 of 240     
step 158 of 240     
step 159 of 240     
step 160 of 240     ***************** integrating with averages = 1, niter = 40, l_spring = 0.000 ***********************

step 161 of 240     
step 162 of 240     
step 163 of 240     
step 164 of 240     
step 165 of 240     
step 166 of 240     
step 167 of 240     
step 168 of 240     
step 169 of 240     
step 170 of 240     
step 171 of 240     
step 172 of 240     
step 173 of 240     
step 174 of 240     
step 175 of 240     
step 176 of 240     
step 177 of 240     
step 178 of 240     
step 179 of 240     
step 180 of 240     
step 181 of 240     
step 182 of 240     
step 183 of 240     
step 184 of 240     
step 185 of 240     
step 186 of 240     
step 187 of 240     
step 188 of 240     
step 189 of 240     
step 190 of 240     
step 191 of 240     
step 192 of 240     
step 193 of 240     
step 194 of 240     
step 195 of 240     
step 196 of 240     
step 197 of 240     
step 198 of 240     
step 199 of 240     
step 200 of 240     ***************** integrating with averages = 0, niter = 40, l_spring = 0.000 ***********************

step 201 of 240     
step 202 of 240     
step 203 of 240     
step 204 of 240     
step 205 of 240     
step 206 of 240     
step 207 of 240     
step 208 of 240     
step 209 of 240     
step 210 of 240     
step 211 of 240     
step 212 of 240     
step 213 of 240     
step 214 of 240     
step 215 of 240     
step 216 of 240     
step 217 of 240     
step 218 of 240     
step 219 of 240     
step 220 of 240     
step 221 of 240     
step 222 of 240     
step 223 of 240     
step 224 of 240     
step 225 of 240     
step 226 of 240     
step 227 of 240     
step 228 of 240     
step 229 of 240     
step 230 of 240     
step 231 of 240     
step 232 of 240     
step 233 of 240     
step 234 of 240     
step 235 of 240     
step 236 of 240     
step 237 of 240     
step 238 of 240     
step 239 of 240     
step 240 of 240     
writing expanded surface to /lscratch/8536404/24563.wrk/fmriprep_23_2_wf/single_subject_24563_wf/anat_preproc_wf/surface_recon_wf/gifti_surface_wf/midthickness/mapflow/_midthickness1/rh.midthickness...
surface expansion took 25 minutes and 41 seconds.


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

