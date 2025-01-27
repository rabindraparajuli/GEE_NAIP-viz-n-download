# GEE_NAIP-viz-n-download
The Python (Jupyter Notebook) codes in this repo basically help to search and display high-resolution imageries from the National Agriculture Imagery Program (NAIP) in Google Earth Engine (GEE) using the _geemap()_ package using Visual Studio Code interface to the area of interest (AOI) defined with a centroid. Such visualization aids in inspecting the imageries for quality control, and the functionalities of _geemap()_ are so simple that someone with minimal Python coding skills can also efficiently perform these steps and successfully complete the operations.

Also, the code includes ways to download 4-band NAIP imageries into a local drive (folder) of interest. Usually, NAIP imageries, downloaded directly from the USDA Geospatial Data Gateway, consist of 3 bands, especially for years before 2024. Using VS Code, where one can define the working directory, the downloaded NAIP will be saved in the designated folder. 

And, of course, thanks to Dr. Qiusheng Wu for such an illustrative book - **Earth Engine and Geemap - Geospatial Data Science with Python** - it immensely helped to learn and perform these steps in GEE.

**References**

Wu, Q. 2023. _Earth Engine and Geemap - Geospatial Data Science with Python_. Locate Press. https://locatepress.com/book/gee
