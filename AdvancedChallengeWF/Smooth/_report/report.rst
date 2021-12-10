Node: Smooth (fsl)
==================


 Hierarchy : AdvancedChallengeWF.Smooth
 Exec ID : Smooth


Original Inputs
---------------


* args : <undefined>
* environ : {'FSLOUTPUTTYPE': 'NIFTI_GZ'}
* fwhm : <undefined>
* in_file : /home/jupyter-david.ellis/ReproNimWorkshop/data/T1w_acpc_dc_restore_1mm.nii.gz
* output_type : NIFTI_GZ
* sigma : 4.0
* smoothed_file : <undefined>


Execution Inputs
----------------


* args : <undefined>
* environ : {'FSLOUTPUTTYPE': 'NIFTI_GZ'}
* fwhm : <undefined>
* in_file : /home/jupyter-david.ellis/ReproNimWorkshop/data/T1w_acpc_dc_restore_1mm.nii.gz
* output_type : NIFTI_GZ
* sigma : 4.0
* smoothed_file : <undefined>


Execution Outputs
-----------------


* smoothed_file : /home/jupyter-david.ellis/ReproNimWorkshop/AdvancedChallengeWF/Smooth/T1w_acpc_dc_restore_1mm_smooth.nii.gz


Runtime info
------------


* cmdline : fslmaths /home/jupyter-david.ellis/ReproNimWorkshop/data/T1w_acpc_dc_restore_1mm.nii.gz -kernel gauss 4.000 -fmean T1w_acpc_dc_restore_1mm_smooth.nii.gz
* duration : 8.414575
* hostname : inbrehub
* prev_wd : /home/jupyter-david.ellis/ReproNimWorkshop
* working_dir : /home/jupyter-david.ellis/ReproNimWorkshop/AdvancedChallengeWF/Smooth


Terminal output
~~~~~~~~~~~~~~~


 


Terminal - standard output
~~~~~~~~~~~~~~~~~~~~~~~~~~


 


Terminal - standard error
~~~~~~~~~~~~~~~~~~~~~~~~~


 


Environment
~~~~~~~~~~~


* CLICOLOR : 1
* FSLOUTPUTTYPE : NIFTI_GZ
* GIT_PAGER : cat
* HOME : /home/jupyter-david.ellis
* INVOCATION_ID : d229775b62ae4f9d957e29efb53af60e
* JOURNAL_STREAM : 9:55021
* JPY_API_TOKEN : f40cf05962ca4ed382f94c3c96ed121c
* JPY_PARENT_PID : 3727
* JUPYTERHUB_ACTIVITY_URL : http://127.0.0.1:15001/hub/api/users/david.ellis/activity
* JUPYTERHUB_API_TOKEN : f40cf05962ca4ed382f94c3c96ed121c
* JUPYTERHUB_API_URL : http://127.0.0.1:15001/hub/api
* JUPYTERHUB_BASE_URL : /
* JUPYTERHUB_CLIENT_ID : jupyterhub-user-david.ellis
* JUPYTERHUB_HOST : 
* JUPYTERHUB_OAUTH_CALLBACK_URL : /user/david.ellis/oauth_callback
* JUPYTERHUB_SERVER_NAME : 
* JUPYTERHUB_SERVICE_PREFIX : /user/david.ellis/
* JUPYTERHUB_USER : david.ellis
* KMP_DUPLICATE_LIB_OK : True
* KMP_INIT_AT_FORK : FALSE
* LANG : en_US.UTF-8
* LOGNAME : jupyter-david.ellis
* MPLBACKEND : module://matplotlib_inline.backend_inline
* OLDPWD : /
* PAGER : cat
* PATH : /opt/tljh/user/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin
* PWD : /home/jupyter-david.ellis
* PYDEVD_USE_FRAME_EVAL : NO
* SHELL : /bin/bash
* SHLVL : 0
* TERM : xterm-color
* USER : jupyter-david.ellis

