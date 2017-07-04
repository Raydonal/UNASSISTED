%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%  M Estimator (homogeneity, ENL, Mean)
%  Reproducible research for article: 
%  L. Gomez, R. Ospina, A. C. Frery
%  "Unassisted quantitative evaluation of despeckling filters"
%  Work by  L. Gomez, R. Ospina, A. C. Frery; codified to Matlab by L. Gomez 
%  Run well on Matlab 2014a (only tested on Windows 7 Enterprise 64 bits)
%  February 2017
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%  Please use it freely and cite the reference paper mentioned above.
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
Some technical issues:
The program has been tested only on a Windows-7 Enterprise 64Bits.

There is a complete front-ed written in Matlab. So, Matlab is required to execute the codes.

Matlab version recommended: 2014a (64 bits).THe program may run on older Matlab versions but FANS filter requires an updated version.


FANS filter files are icluded in the zip file (this is a software freely available from Authors of FANS filter;please, also cite them if you use this  program).

Take care that FANS filter requires some pre-compiled executable files. The ones included in our implementation work exclusively on Windows 64 bits.
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
Program instalation:
To use the program, unzip the file Detect_Structure_Matlab.7z in a folder.

A folder is created: \data. This folder contains the data to use with the program.
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
Running the program:

In the folder, just click on the file "ENL_Mean_Estimator.m", or open Matlab and load the "ENL_Mean_Estimator.m file" and execute it as any Matlab file.
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
Using the program:

The natural flow is the following:

- Select Data: load data,
- leave the default input parameters (except the ENL one: it must be fitted to the ENL of the data to test; it is supposed the user know the ENL of the data).
- select the mode of data: Intensity or Amplitude.
- Push "Calculate" and see the results for H1 instance on the corresponding fields.
- Generate a H0 instance: Push "Build H0".
- Push "Calculate" and see the results for H0 instance on the corresponding fields.

Get the standard estimators: Mean, Std, and ENL:
- From a previous data loaded, just select the image (Noisy, Filtered or Ratio) and a ROI can be selected. The measured values (Mean, Std., ENL) will appear in the related fields.
- The same may be done also for H0 random generated data.

Running the optimizer:
- leave the default input parameters.
- Push "Calculate" and then, push "FANS Optimum" to see the optimal filtered result. 

Notice that images can be enlarged (push "Enlarge") for a better visual inspection.

Feel free to "play" with the program and, please, report any problem to luis.gomez@ulpgc.es

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%  M Estimator (homogeneity, ENL, Mean)
%  Reproducible research for article: 
%  L. Gomez, R. Ospina, A. C. Frery
%  "Unassisted quantitative evaluation of despeckling filters"
%  Work by  L. Gomez, R. Ospina, A. C. Frery; codified to Matlab by L. Gomez 
%  Run well on Matlab 2014a (only tested on Windows 7 Enterprise 64 bits)
%  February 2017
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%  Please use it freely and cite the reference paper mentioned above.
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

