# DL-Music-Creation
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

The File system should look like this: <br />
ProjectMusic <br />
|->Lakh Piano Dataset <br />
| |->Genre/msd_tagtraum_cd1.cls <br />
| |->Metadata/lmd_matched_h5 <br />
| |->LPD-5/lpd_5/lpd_5_cleansed <br />
| |->cleansed_ids.txt <br />
| <br />
|->Music Dataset/midis/lmd_matched <br />

# Notebooks

Use each notebook to generate the corresponding type of midi

The names that aren't self explanatory are:
Melody-Generation: Generate new midi using CNN
VAE-Generation: Generate new midi using VAE
VAE_Application: Apply VAE to generate "remixed" midi
