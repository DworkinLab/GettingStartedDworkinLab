Getting started on the HPCC
===========================

Written: 05/31/12    Last Revised: 06/01/12 - I will let you know if it changes.

Dear Dworkin labbies, 
 
Welcome to the DworkinLab Project Space, which is hosted by the HPCC. Before you start using this for storing data, please read this file first. 
 
Seriously. If you are new to using Unix, please DO NOT USE THIS PLACE TO
PRACTICE, YOU COULD ERASE ALL OF OUR DATA!!!

The general practice that I recommend to avoid any accidental file deletions
or overwrites is to copy (using cp, not mv) the files you need to your own home directory, do
your analyses in your home directory, and save it to your directory or scratch space. Then you
can copy the analysis or output back to this Project Folder. Before you erase anything in the RawData directory, please speak with me, and explain why! 

##Folder structure:
While things may change in the future, I have currently set this up with a couple of very specific directories:
  
###RawData: This is the raw data such as images of wings (for morphometrics), or wing imaginal discs (antibody staining), raw sequence reads (trace files, .sff, .fastq), data right from the Q_RT_PCR machine, videos of behavioural sequences, etc.. In other words, data that has not been altered in any way. 

###IntermediateData: 
This would be "cleaned-up" data, such as landmark
co-ordinates (with seperate files for the splines, landmarks, and
super-imposed landmarks), Genome or transcriptome assemblies, counts of RNA
reads, JWatcher ethograms, spreadsheets of data (behavioural, morphological or whatever) that
can be used to initiate your analyses.

###AnalysisOutput: 
These are the output files from your analyses, that will be
used for publication. In general, if the outputs are easily re-generated from
your scripts and the IntermediateData file, then you do not need to store the outputs in
AnalysisOutput. If it requires more than an hour or so to regenerate the
output (or it is using some software that you think may be difficult to use),
feel free to keep the output. For the moment err on the side of storing the
output. 

Within each of these directories you will see sub-directories like "Sequences" or "wings" which I hope are self-explanatory. You can then generate folders within these for your particular data sets. 

###Manuscripts:
For any manuscripts you are currently working on.

###Scripts: For scripts associated with your analysis (until we set up version control). Scripts and Manuscripts are the only folders that can have a sub-folder with your name (but I would prefer sub-folders be by project)

###readme files for each project folder. 
For each project there should be a readme file associated with raw data and another readme file associated with the intermediate data (and one for the analysis if necessary). For instance in the RawData/Wings  directory there might be a folder called DGRP_Wings for all of the images associated with the wings from the DGRP study. In this folder there will be the images (which might be organized into folders by lines, blocks or whatever), but there will also be a readme file named something like:
DGRP_WingImages_ReadMe.txt

####Inside this readme (which should be a few sentences plus bullet points) will include:
A) a brief description of the project (1-2 sentences) 
B) the naming conventions for the files (ie how were the images named), 
C) who collected the data (if there were multiple people there names should all be there if possible)
D) Start and completion date for collecting the data.
E) If possible some basic info on how it was collected (i.e. For images what microscope, camera, magnification of the objective. For Sequences, 454, Illumina GAII, HiSeq, Paired end?). 
F) I am sure there are other important things to include.

For the readme associated with IntermediateData (in the appropriate folder, i.e. IntermediateData/Wings/DGRP_Wings). The name could be DGRP_WingLandmarks_ReadMe.txt
A) Same project description as above, plus anything more if necessary (i.e. if you are using the data to address something very different and had to extract different data (i.e. anew way to extract landmarks, or a new way to assemble the sequences).
B) The directory of the raw Data (/RawData/Wings/DGRP_Wings) associated with the IntermediateData
C) What intermediate data files have been generated (i.e., raw splines, extracted landmarks, superimposed landmarks might be three files all in this directory).
D) Some short information (or link to script) on how the intermediate data was generated from the rawData.
E) Other important things you can think of
F) Date that the intermediate data was generated, and if and when it has been last modified (and why). 

It is very possible (and perhaps likely) that there will multiple Intermediate files linked to a particular RawData folder/file, and possibly multiple raw Data sources (i.e. genotype + phenotype info) linked to a particular intermediate data file. This is ok, as long as all of these connections are clear.

For the AnalysisOutput folder, (i.e. DGRP), the readme can be very short
A) project description,
B) Link to script that generates the analysis. 
C) a link to the intermediate data
D) Date Generated, or last revised (and maybe a note on why there was a revision).


##Version Control
The lab uses git and github (github.com/DworkinLab). Create your own github account.

