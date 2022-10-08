Yeo 7 RSN parcellation applied to whole brain (7RSN whole brain atlas)

We merged multiple functional community theory-based atlases estimated by intrinsic functional connectivity, including cortical parcellations (Schaefer et al. 2018), cerebellar parcellations (Buckner, et al. 2011), striatal parcellations (Choi et al. 2012), and thalamic parcellations (Horn et al. 2015). 

The orignial image of thalamic parcellations could be found in lead\templates\space\MNI_ICBM_2009b_NLIN_ASYM\atlases\Thalamic Functional Networks (https://www.lead-dbs.org/).

Although the Schaefer atlas provides various versions such as 100, 200, 400 and 1000 parcellations, we recommend using 1000 parcellations version since the size of the cortical regions is similar to the size of the subcortical regions.

Our 1X1X1 atlas has a resolution of 181X217X181 and contains a total of 1,042 brain regions. When 3X3X3 resampling was performed for BOLD analysis, the three brain regions (No.1015, No.1017, No.1022) from Choi's striatum were removed because they were too small, so there were only 1,039 brain regions left on the 3X3X3 atlas.

We are also aware of similar work by other researchers, such as the thalamic segmentation studies from Raut, which can be found in detail at https://github.com/ryraut/thalamic-parcellation.

We have made the detailed process of our atlas construction public for other researchers to examine.

Relevant citations:

Schaefer A, Kong R, Gordon EM, et al. Local-Global Parcellation of the Human Cerebral Cortex from Intrinsic Functional Connectivity MRI. Cerebral cortex (New York, NY : 1991) 2018;28:3095-3114.

Buckner RL, Krienen FM, Castellanos A, Diaz JC, Yeo BT. The organization of the human cerebellum estimated by intrinsic functional connectivity. Journal of neurophysiology 2011;106:2322-2345.

Choi EY, Yeo BT, Buckner RL. The organization of the human striatum estimated by intrinsic functional connectivity. Journal of neurophysiology 2012;108:2242-2263.

Horn A, Kühn AA. Lead-DBS: a toolbox for deep brain stimulation electrode localizations and visualizations. NeuroImage 2015;107:127-135.


