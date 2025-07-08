# Sunshining Analysis for Hong Kong Public Buses (Geoprocessing Toolbox for ArcGIS Pro)
Welcome to use the Sunshining Analysis tool for Hong Kong buses.
ArcGIS Pro and Python environment are required.
This Tool Version: 1.3

Updated for 1.3 (as at 3 March 2025)
- Added terrain influence option in Analysis.
- Fixed bug for generating the route layer.

Instructions

1. Go to ArcGIS Pro, create a cloned Python environment.
2. Install following required packages with PIP.
suntime>=1.3.0
pysolar>=0.11
dateutils>=0.6.12
zipp>=3.16.0
urllib3>=2.2.0
rasterio>=1.4.3
3. Add this toolbox (TBX) to ArcGIS Pro and expand it on Catalog Pane.
4. If it is your first time to use the tool for analysis, run the "Ready data for calculation" tool and download necessary datasets.
5. Then, click into "Sunshining Analysis for Hong Kong Buses" tool, input parameters, and run it.

Dataset is last updated at Dec 2024 (i.e., the URLs listed in the tool).
