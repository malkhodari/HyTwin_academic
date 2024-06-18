### HyTwin: AI-enabled tool for estimating hypertension severity and progression trajectory using multi-modality measurements

#### Mohanad Alkhodari, Winok Lapidaire, Turkay Kart, Abhirup Banerjee, Paul Leeson
##### Cardiovascular Clinical Research Facility (CCRF), Division of Cardiovascular Medicine, University of Oxford, United Kingdom
##### Institute of Biomedical Engineering (IBME), Department of Engineering Science, University of Oxford, United Kingdom

###### Publication: https://ieeexplore.ieee.org/document/10385558

Version: 1.1 Release date: 2024-06-18

###### Contact: mohanad.alkhodari@rdm.ox.ac.uk, winok.lapidaire@cardiov.ox.ac.uk, turkay.kart@cardiov.ox.ac.uk, abhirup.banerjee@eng.ox.ac.uk, paul.leeson@cardiov.ox.ac.uk

<img src="https://github.com/malkhodari/HyTwin_academic/assets/62998803/4ef672ac-0dcd-4178-bfe6-e68c0f46a601" width="80%" height="80%">

<img src="https://github.com/malkhodari/HyTwin_academic/assets/62998803/40c72a40-66d1-4d9f-9018-ebf3badedbf5" width="90%" height="90%">

## Details on hypertension modelling
```
- Hypertension is a serious medical condition that affects over a billion people worldwide
- The proper management of disease progression requires an extended knowledge on the functional/structural changes in the whole body in response to hypertension
- We developed the HyperScore; an integrative and unified measure of hypertension progression relative to multi-modality measurements
- The HyperScore reflects the proximity of a participant from the healthy state and towards the diseased state [score range: 0 (low risk) – 1 (high risk)]
- We provide another level of characterization of the progression mechanism by locating the participant on a disease progression trajectory map
- Each trajectory within the map reflects distinct hypertension-related end-organ progression pathway
- Trajectory 1: liver disease, Trajectory 2: brain diseases, Trajectory 3: heart diseases
- Trajectory 4: low survival (death from circulatory diseases), Trajectory 5: Metabolic diseases, Trajectory 6: Kidney diseases
- The built-in model was developed using a large participating cohort from the UK Biobank database (n=27,099) with over 500 imaging/non-imaging variables from multiple modalities.
- It is based on a semi-supervised machine learning approach; the contrastive trajectory inference (cTI)
```

## Usage instructions
```
- Input dataset should be arranged to match the data provided in this example (demographics.csv and multimodality.csv)
- Once loading the demographics.csv file, the tool will arrange the multimodality.csv based on Patient IDs (row-wise)
- Ensure the inclusion of at least the UK Biobank variable id, i.e., 12338, in the name of each variable
- Variable names will be edited automatically to match with the built-in names within the tool, i.e., X12338_2_0
- The tool checks for missing variables in the dataset (please make sure to have all variables available!)
- The tool runs with missing variables, however, it would be more accurate if all variables were provided!
- Missing values will be imputed automatically using the big data (UKBiobank) at the back-end of the tool
- Run the trajectory inference to estimate HyperScores and predict the proper trajectory for each patient
- The overall analysis of the input dataset will be visualized on the right panel
- The user has the option to visualize the analysis for each patient separately as well
- Once done, the user can export all results (table and figures) as .csv and .png, respectively
```

## For online installation
[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=malkhodari/HyTwin_academic&file=HyTwin_academic.mlappinstall)

```
- Create a free MathWorks account or use an existing account (no license required)
- Sign-in with your account at MATLAB Online
- The link above will automatically obtain the files from the online repository
- Once MATLAB Online is open, select the tick box and click "Save and Open"
- The app will automatically download and ask you to install
- Once installed, click on the "Apps" tab on the top toolbar
- Click once on "HyTwin_academic" to open the online app
- Drag-drop patient files (in .csv) to the current path then hit browse
- You can manually adjust screen size based on your screen resolution (zoom out)
- You can add the app to favourites for faster access by clicking on the star
```

## For stand-alone installation (.exe)
[<img src="hyperlink2.png" width="16.35%" height="16.35%">
](https://kudrive.ku.ac.ae/no-shib/index.php/s/rpcGYZheu5TdXax/download)

```
- Download HyTwin_academic.exe on your Windows computer and run the installer (no MATLAB required)
- Select the location, create desktop shortcut, and proceed with downloading the app 
- Launch the app from the desktop shortcut or from the download location
- You can manually adjust screen size based on your screen resolution
```

## Learn more about us
https://www.rdm.ox.ac.uk/study-with-us/supervisor-profiles/leeson-group
https://eng.ox.ac.uk/multimedia/multimedia-people/
