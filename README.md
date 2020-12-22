# Google-Colab
This Python script code was developed by dr. F. Brandolini and G. Domingo-Ribas to accompany the paper: *Brandolini F., Domingo-Ribas G., 
Zerboni A. & Turner S. "A Google Earth Engine-enabled Python approach to improve identification of anthropogenic palaeo-landscape features"*, 
submitted to *Open Research Europe*, 20XX.

The Sentinel 2 (S2) satellite data were accessed through the Python [1] module geemap [2] in Colab [3], a serverless Jupyter notebook computational environment 
for interactive development [4]. The native GEE Python API has relatively limited functionality for visualizing results but the geemap Python module was created 
specifically to fill this gap. Finally, the python code developed enables the analysis of the S2 filtered image collection through Spectral Index (SI) and 
Spectral Decomposition (SD) techniques. Each image was exported in Geo.TIFF format in QGIS [4] where the Min/Max values were adjusted with the Cumulative 
Count Cut tool. Finally, the figures presented in this paper were generated in the QGIS Layout Editor. The Python modules rasterio [5] and matplotlib [6] 
were used respectively to create individual plots for each band of the raster and histograms of their values.

Refernces

1. Python Software Foundation. Python Language Reference. 2020. Available: http://www.python.org
2. Wu Q. geemap: A Python package for interactive mapping with Google Earth Engine. Journal of Open Source Software. 2020;5: 2305.
3. Bisong E. Google Colaboratory. In: Bisong E, editor. Building Machine Learning and Deep Learning Models on Google Cloud Platform: 
   A Comprehensive Guide for Beginners. Berkeley, CA: Apress; 2019. pp. 59–64
4. Project Jupyter. Jupyter Notebook. 2020. Available: https://jupyter.org/
5. QGIS Development Team. QGIS Geographic Information System. Open Source Geospatial Foundation Project. 2019. 
   Available: https://www.qgis.org/en/site/index.html
6. Gillies S et al. Rasterio: geospatial raster I/O for Python programmers. Mapbox; 2013. Available: https://github.com/mapbox/rasterio
7. Hunter JD. Matplotlib: A 2D Graphics Environment. Comput Sci Eng. 2007;9: 90–95.


Acknowledgments
The authors thank Dr Hector Orengo (Catalan Institute of Classical Archaeology, Tarragona - Spain) and Prof. Qiusheng Wu (The University of Tennessee, 
Knoxville - USA) for their suggestions during the development of the script code.
