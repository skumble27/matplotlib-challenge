# matplotlib-challenge

### Drug Efficacy Studies in Mouse Models of Squamous Cell Carcinoma

##### Sumukh Kumble

#### Introduction

Pymaceuticals have commissioned a study to investigate a number of lead candidates for their efficacy in reducing tumor volumes in mouse models of squamous cell carcinoma. The data sets obtained from this study have been analysed in great detail to determine which of the list of drug candidates indeed shows the most promise that warrant further clinical investigations based on the analyses that has been witnessed in these murine models. 



#### Data Analysis

##### Data cleaning

Due to the presence of duplicate data within the set, the mouse with the ID of g989 has been dropped from the dataset for subsequent data analysis. The data for this mouse is available within the supplementary 'data folder' in this repository. 

##### Summary Statistics

![Summary Statistics](https://raw.githubusercontent.com/skumble27/matplotlib-challenge/master/Pymaceuticals/Images/1Summary_Statistics.png)

###### Table 1: Summary Statistics for the ten lead candidate drugs. 

Of all the drugs assessed in this study, Capomulin appears to have the lowest mean tumour volume compared to all other drugs assessed in this study. 

![Bar Graph](https://raw.githubusercontent.com/skumble27/matplotlib-challenge/master/Pymaceuticals/Images/3Bar_chart_pyplot.png)

###### Figure 1: Number of mice used for the assessment of each drug as well as the placebo.



![Pie Chart Gender Distribution](https://raw.githubusercontent.com/skumble27/matplotlib-challenge/master/Pymaceuticals/Images/5Pie_Chart_Pyplot.png)

###### Figure 2: Mouse gender distribution across the entire study. Amongst the 248 mice that were assessed, approximately 50% of the mice were female whilst the remainder were male.



![Drug Efficacy summary](https://raw.githubusercontent.com/skumble27/matplotlib-challenge/master/Pymaceuticals/Images/6Drug_efficacy_summary.png)

###### Figure 6: Drug efficacy against mouse models of squamous cell carcinoma.

![Capomulin Treatment for Mouse s185](https://raw.githubusercontent.com/skumble27/matplotlib-challenge/master/Pymaceuticals/Images/7capomulin_treatment.png)

###### Figure 7: Tumor regression in Mouse s185 when treated with capomulin over a period of 45 days.



![Weight vs Volume](https://raw.githubusercontent.com/skumble27/matplotlib-challenge/master/Pymaceuticals/Images/8mouse_weightvs_tumor_vol.png)

###### Figure 8: Mouse Weight vs Tumor Volume.

![Weight vs Tumor Volume Regression](https://raw.githubusercontent.com/skumble27/matplotlib-challenge/master/Pymaceuticals/Images/9mouse_weightvs_tumor_vol.png)

###### Figure 9: Linear Regression equation for mouse weight against tumor volume (mm3)



### General Discussion

The objectives of this project were to assess the efficacy of ten leading drug candidates in murine tumor models of squamous cell carcinoma to determine if the drugs are effective in reducing the overall tumor volume over a period of forty-five days. As seen in Figure 6, it is evident that capomulin and ramicane show the most promise in the efficacy in reducing tumor volumes in several mice, which is further supported by the data shown in Figure 7, where mouse s185, treated with capomulin, demonstrated a steady decrease in the overall tumor burden. Upon further analyses of the data set, further investigations were conducted to determine the correlation between the weight of mice and tumor volume. The data, as shown in Figure 8, was fitted with a linear regression model to provide insight as to whether there is a correlation between weight and tumor volume (Figure 9). Based on the R-squared value (0.708) there does indeed appear to be a correlation between mouse weight and tumor volume, however, it should be taken into consideration that the weights of the mice are possibly not a true causation in the increase in tumor volume. 

 







