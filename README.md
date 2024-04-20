### HyTwin: AI-enabled tool for estimating hypertension severity and progression trajectory using multi-modality measurements

#### Mohanad Alkhodari, Winok Lapidaire, Turkay Kart, Abhirup Banerjee, Paul Leeson
##### Cardiovascular Clinical Research Facility (CCRF), Division of Cardiovascular Medicine, University of Oxford, United Kingdom
##### Institute of Biomedical Engineering (IBME), Department of Engineering Science, University of Oxford, United Kingdom

###### Publication: doi.org/10.10.10.10 (pending)

Version: 1.0 Release date: 2024-XX-XX

###### Contact: mohanad.alkhodari@rdm.ox.ac.uk, winok.lapidaire@cardiov.ox.ac.uk, turkay.kart@cardiov.ox.ac.uk, abhirup.banerjee@eng.ox.ac.uk, paul.leeson@cardiov.ox.ac.uk

<img src="https://github.com/malkhodari/HyTwin_academic/assets/62998803/4ef672ac-0dcd-4178-bfe6-e68c0f46a601" width="80%" height="80%">

## Usage instructions
```
- Input dataset should be arranged to match the data provided in this example (demographics.csv and multimodality.csv)
- Once loading the demographics.csv file, the tool will arrange the multimodality.csv based on Patient ID (row-wise)
- The tool checks for missing variables in the dataset (please make sure to have all variables available)
- Missing values will be imputed automatically using the big data (UKBiobank) at te back-end of the tool
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
