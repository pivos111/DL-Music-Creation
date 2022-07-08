# DL-Music-Creation

# Music Creation
Generating Music using Deep Learning

Project by Konstantinos Skourogiannis and Iraklis Pallikaris

# Files needed

Dataset: lpd_5_cleansed: 
https://drive.google.com/uc?id=11rxrGaQbfTW-WC0k2GlR9YDAT-UxIb4O

Metadata: lmd_matched_h5: 
http://hog.ee.columbia.edu/craffel/lmd/lmd_matched_h5.tar.gz

A subset of 45,129 files from LMD-full: lmd_matched: 
http://hog.ee.columbia.edu/craffel/lmd/lmd_matched.tar.gz

A list of all file IDs and the matched MSD IDs: cleansed_ids.txt: 
https://drive.google.com/uc?id=1EmCZQvc5Yqtz4y8TO5Ms_JpzDT6WRPEO

Genre labels: msd_tagtraum_cd1.cls: 
https://www.tagtraum.com/msd_genre_datasets.html

The File system should look like this:
ProjectMusic
|->Lakh Piano Dataset
| |->Genre/msd_tagtraum_cd1.cls
| |->Metadata/lmd_matched_h5
| |->LPD-5/lpd_5/lpd_5_cleansed
| |->cleansed_ids.txt
|
|->Music Dataset/midis/lmd_matched

# Notebooks

Use each notebook to generate the corresponding type of midi

The names that aren't self explanatory are:
Melody-Generation: Generate new midi using CNN
VAE-Generation: Generate new midi using VAE
VAE_Application: Apply VAE to generate "remixed" midi
