# Scripted-LeadField-Pipeline
Scripted from the brainstorm toolbox ver. Feb. 24 2019 and OpenMEEG-2.4.9999-Win64.tar.gz
1. Download the Brainstorm ver. Feb. 24 2019.rar from the link below and unzip outside of 'example data' folder
2. Download the example data from https://lstneuro-my.sharepoint.com/:f:/g/personal/andy_neuroinformatics-collaboratory_org/EjIH-Do76hZKtvPGRuOfAP8BfXCz7ysQWEbjB1E5_g95bw?e=B7I8np 

   Example data includes: 
                      
                      1) 113922_MEG_anatomy 
                      2) 113922_MEG_Restin_unproc 
                      3) MC0000010_EEG_anatomy_t13d_anatVOL_20060115002658_2.nii_out 
                      4) MC0000010_EEG_data.mat
                      5) Brainstorm ver. Feb. 24 2019.rar
                      
3. Set the database folder as the Brainstorm_db if it is the first time to run brainstorm on your PC
4. Run scripted_fs_lf_ppl.m for Freesurfer anatomy files
5. Run scripted_hcp_lf_ppl.m for HCP (Human Connectome Project) anatomy files
6. You will see Gain.mat and patch.mat when the calculation is finished.
