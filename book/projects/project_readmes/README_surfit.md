# Surfit 🏄‍♂️

## Team Members

The following people contributed to our project throughout the week:
* Project lead: Ben Purinton
* Project lead: David Clemens-Sewall
* Project lead: Jessica Badgeley
* Helper: Nathan Kurtz
* Helper: YoungHyun Koo
* Team member: 'Ana Fonongava'inga Stringer
* Team member: Chancelor Roberts
* Team member: Emma Robertson
* Team member: Karina Zikan

## Project Goals
Our main goal for this project was to see if we could assess surface roughness along track-length scales comparing ATL03 and ATL06 ICESat-2 data, across two regions of interest. 

Our motivating question is: 
* Are surface roughness signals hiding in ATL03 at shorter along-track length scales compared with ATL06?

Some personal goals that were shared coming into this project were:
* To familiarize ourselves with accessing ICESat-2 data via cloud (e.g., SlideRule, earthaccess, etc.).
* Learn more about the tools we've been introduced to in the tutorials. 
* Learn how to access and subset ICESat-2 data. 
* Become more comfortable learning and sharing work in a collaborative environment - team science! 

### Regions of Interest 
We compared tracks from Black Rock Desert, Nevada and Utqiagvik, Alaska, our two regions of interest for this project. 

## Project Outcomes
* Ben created visualizations to assess ICESat-2 its limitations over short along-track length scale, supporting understanding of data noise and limitations. 
* Karina provided a SlideRule tutorial that was adapted for the use of this project. 
* Chance, Emma, and Jessica worked on accessing ATL06 photon data using SlideRule and created a [Jupyter Notebook] (link to notebook). 
* YoungHyun obtained a geodataframe of the ATL03 data for the region of interest & analyzed how surface roughness varies with different yapc values. 
* Nathan wrote code that takes photon clouds and attempts to retrieve the associated surface height distribution. This code assumes the surface height distribution follows a Gaussian or log-normal distribution, convolves this with the ICESat-2 transmit pulse, and attempts to find the distribution parameters (mean height and width or roughness). This version of the code runs over a granule near Utqiagvik.
* David worked on extracting surface roughness on flat surfaces from ICESat-2 ATL03 data.
* Jessica provided support in project vision and bringing pieces together, identified a test track for the Black Rock ROI, and provided Git support for several group members.
* Team members worked on increasing their familiarity with accessing ICESat-2 data from the cloud.

Links to our main notebooks (some are still in progress):
* Project summary: https://github.com/ICESAT-2HackWeek/surfit/blob/main/contributors/emma/ProjectSummary.ipynb
* ROI visualization: https://github.com/ICESAT-2HackWeek/surfit/blob/main/shared_code/DataViz.ipynb
* Data retrieval ATL03: https://github.com/ICESAT-2HackWeek/surfit/blob/main/shared_code/ATL03_Retrieval.ipynb
* Data retrieval ATL06: https://github.com/ICESAT-2HackWeek/surfit/blob/main/shared_code/ATL06_Retrieval.ipynb
* Data visualization: https://github.com/ICESAT-2HackWeek/surfit/blob/main/contributors/chance/ATL06_Viewer.ipynb
* Surface height distributions: https://github.com/ICESAT-2HackWeek/surfit/blob/main/shared_code/curvefit_lognormal_roughness.ipynb
* Roughness from height distributions: https://github.com/ICESAT-2HackWeek/surfit/blob/main/contributors/david/roughness_example.ipynb
* DEM Comparison: https://github.com/ICESAT-2HackWeek/surfit/blob/main/contributors/ben/DEM_Comparison_01_prepare.ipynb,
                  https://github.com/ICESAT-2HackWeek/surfit/blob/main/contributors/ben/DEM_Comparison_02_plot.ipynb
* YAPC influence on roughness results: https://github.com/ICESAT-2HackWeek/surfit/blob/main/contributors/Young/sliderule_test.ipynb
  
## Future Efforts
* Our team is considering expanding the regions of interest to include more diverse terrains to further validate our findings.
* This work can potentially support future proposals for the contributors.  



