# A Data-Driven Method for Water Quality Analysis and Prediction for Localized Irrigation
## Description
This repository contains the code, and the final dataset used for the paper <b>A Data-Driven Method for Water Quality Analysis and Prediction for Localized Irrigation</b>, by Roberto F Silva, Marcos R Benso, Fernando E Corrêa, Tamara G Messias, Fernando C Mendonça, Patrícia A A Marques, Sergio N Duarte, Eduardo M Mendiondo, Alexandre C B Delbem, and Antonio M Saraiva. We implemented the proposed methodology for
evaluating water quality considering different variables in an important river basin in Brazil. We have used the standard scaling to scale data, and the k-means clustering and sci-kit learn library. Geopandas library was used to build maps, and matplotlib and seaborn to build charts. Pandas library was used to manipulate tabular data. This paper was accepted at MDPI Agriengineering, Agricultural Irrigation Systems
section. Descriptions of the implementation and the dataset used are contained in the paper (link: [URL](https://www.mdpi.com/2624-7402/6/2/103)). The code is composed of 1 Colab notebook.

The main dataset used was the Water quality data from different stations in the river basin: Infoáguas Online System (https: //sistemainfoaguas.cetesb.sp.gov.br/)

The data processing code (not included in this repository) was developed by Marcos R. Benso. The methodology implementation code was developed by Roberto F. Silva.

Reference of the paper and to cite this repository: 
- The reference will be inserted after the final version of the paper is accepted

## To Do (further research, out of the scope of this paper):
- explore other data processing techniques (e.g., PCA and t-SNE)
- explore other unsupervised learning models (e.g., DBSCAN, SOM)
- consider the flow measured at the time of collection and the size of the sub-basins
- evaluate additional water quality metrics (e.g., SAR, aluminum, and manganese)
- develop a web app based on the code implemented
- evaluate the use of spatiotemporal clustering models
- optimize code for deployment in production
- better integrate the data processing and clustering implementation codes
- automate data collection

## Credits for the code:
The code was implemented using Google Colab to improve replicability (https://colab.research.google.com/)

The authors would like to thank the authors of the libraries used and their tutorials for providing important codes, functions, and examples. 

The authors would also like to thank all the developers that were and are involved on the development of the following Python libraries: 
- Pandas: https://pandas.pydata.org/
- Scikit-Learn: https://scikit-learn.org/
- Matplotlib: https://matplotlib.org/
- NumPy: https://numpy.org/
- Seaborn: https://seaborn.pydata.org/
- SciPy: https://www.scipy.org/
- Geopandas: https://geopandas.org/

The authors would also like to thank all the developers that were and are involved on the development of the following R packages: 
- dplyr: https://cran.r-project.org/web/packages/dplyr/index.html
- reshape: https://www.rdocumentation.org/packages/stats/versions/3.6.2/topics/reshape
- tidyr: https://cran.r-project.org/web/packages/tidyr/index.html
- lubridate: https://cran.r-project.org/web/packages/lubridate/index.html

## Credits for the dataset:
The authors would like to thank the following institutions for providing the data collected: CETESB, ANA, and the Infoáguas Online System

## Acknowledgements:
This work was carried out at the Center for Artificial Intelligence (C4AI-USP) and the Department of Biosystems Engineering (LEB-ESALQ-USP) of the University of São Paulo, with support from the following institutions: the Sao Paulo Research Foundation (FAPESP grant 2019/07665-4), IBM Corporation, and the National Council for Scientific and Technological Development (CNPq). We also acknowledge the support from the Coordenacão de Aperfeiçoamento de Pessoal de Nível Superior (CAPES, finance code 001).
