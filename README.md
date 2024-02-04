# NLGEM_CGM_Gaze

This directory contains compressed csv files of the data used for the analyses of HarPaz et al. (2024) in Applied Sciences (DOI and full citation to be added when accepted)


Each file contains data for one subject, with the following fields:

id - subject indetification number for this analysis.
sex -           male / female
age -           rounded age (HIPAA requirement) and any age above 79 is given a NaN value (HIPAA requierment)
needs_glasses - boolean variable indicates whether the subject uses glasses for optical correction
timestamp	-     sample timestamps (ms)
NLGEM_hor	-     NLGEM model: horizontal location of estimated gaze
withCGM_hor - 	NLGEM+CGM model: horizontal location of estimated gaze
IR_hor -        Tobii IR eye tracker: horizontal measurement of gaze
NLGEM_ver	-     NLGEM model: vertical location of estimated gaze      
withCGM_ver	-   NLGEM+CGM model: vertical location of estimated gaze
IR_ver -        Tobii IR eye tracker: vertical measurement of gaze
