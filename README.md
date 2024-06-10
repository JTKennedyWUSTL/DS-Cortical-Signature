# DS-Cortical-Signature
Down syndrome cortical signature thickness calculation

Files needed to extract cortical signatues from FreeSurfer surfaces. Label files must be placed in fsaverage/label. A csv with a list of FreeSurfer subject folders of interest is needed.Run scripts using python3 with the following code:

python3 ./cs_main.py 'cortical signature of interest' 'absolute path to freesurfer_list.csv' 'absolute path to output folder'

e.g. python3 ./cs_main.py Amyloid /data/FreeSurferSubjects/Thickness/freesurfer_list.csv /data/FreeSurferSubjects/Thickness/Amyloid

Python scripts adapted from Aylin Dincer's ADAD and LOAD cortical signatures: https://github.com/benzinger-icl/ADcortsig-roi
