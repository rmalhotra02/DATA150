<p align="center">
## Methodological Investigation: Poverty Assessment and Analysis in Africa
#### Rhea Malhotra
#### Professor. Brewer
#### Human Development and Data Science
#### 11/21/2021
#### Word count: 1283

Poverty is one of the most urgent concerns regarding human development. It forces millions to live in negative conditions such as homelessness, food insecurity, inadequate nutrition, inadequate childcare, lack of access to healthcare or education, which all adversely impact our nations. Globally, poverty is a significant force of health and welfare challenges faced by humans today. While many institutions aim to alleviate poverty through donations and construction of infrastructure, they are often set back due to the difficulty of not knowing where exactly those that are affected live (Bill and Melinda Gates Foundation). With the inaccessibility of this information, developing countries are further set back from developing as they continue to struggle with the same unfreedoms. Researchers now using data science methods such as geospatial and satellite data can spatially target and produce accurate high-resolution maps of poverty indicators in developing countries.

Most developing countries have fewer sources of robust data. To combat poverty and aid developmental effort, scientists and engineers use data science methods such as analyzing and observing poverty maps from satellite imagery and geospatial data, as can be seen in the articles I have researched for poverty assessment in Africa. From traditional census data to satellite imagery and geospatial techniques, there is one shared goal: to eradicate poverty. Satellite imagery and data can be used to gather information and efficiently find and track impoverished zones across developing countries. New methods, such as combining traditional household survey data with non-traditional data sources (satellite imagery and mobile phone data), are allowing researchers to map poverty at a higher scale and resolution and hopefully, helping countries continue to reduce poverty. Overall, I believe that the digital economy is transforming how data is collected, processed, and used to make decisions. 

In Amartya Sen’s “Development as Freedom,” Sen states that human development is the process of expanding human freedoms to allow people to lead the lives they have reason to live (Sen). Freedom is important because it leads to a higher quality of life. By targeting poverty-stricken areas and gathering data, we can use our freedoms to eradicate the unfreedoms of poverty in developing nations. Through this data, researchers can better understand poverty and its determinants in order to better design programs that reduce inequality and improve public service delivery among those who are extremely poor (Castelán). In this literature review, I will be assessing data science methods that are being used to indicate poverty-stricken regions and how the data can be used to eradicate poverty in Africa.

There are several data science methods I have found to be significant during my assessment of poverty in Africa. There are a various number of data science methods that go hand in hand when producing poverty maps. These methods include remote sensing (RS) data, call data record (CDR) data, geospatial data, and satellite data. These methods are used to analyze and assess poverty in various datasets. It is difficult to obtain reliable data from developing countries. Often, underdeveloped countries are highly data-deprived, so data science methods such as utilizing satellite imagery allow researchers to collect accurate and reliable data. Traditionally, methods used to target and analyze poverty rely on census data, which are often unavailable or out of date in most low- and middle-income countries (Steele). Alternative measures are needed to update estimates between censuses. Now, researchers use powerful machine learning technology to extract information about poverty through satellite imagery (Horton). 

<p align="center">
<img width="726" alt="Screen Shot 2021-11-22 at 4 52 20 AM" src="https://user-images.githubusercontent.com/89988140/142840020-29f3a04b-18d8-4ffa-abd4-e1a9f13ea4c0.png">

The use of satellite imagery and remote sensing (RS) data has played a valuable role in the production of poverty maps. The article, “How to Understand Global Poverty from Outer Space,” details a study conducted in Rwanda by Asmi Kumar used neural networks and satellite imagery to predict asset wealth and predict poverty in Rwanda, Africa. He did this in 5 steps: beginning by downloading the Demographic and Health Surveys (DHS), nightlight satellite imagery, and  daytime satellite imagery. The DHS are surveys that provide household data for health, nutrition, and assets. Using the Google Maps Platform,  daytime satellite images were obtained, containing valuable features of landscapes (conditions of roads and homes and activity). Lastly, nightlights were obtained from satellite imagery based on the locations from the DHS (Kumar).

<p align="center">
<img width="683" alt="Screen Shot 2021-11-22 at 4 54 39 AM" src="https://user-images.githubusercontent.com/89988140/142840378-eaf853c5-6afa-43c2-9ed2-6d23a80a3c4c.png">

After the data is collected, the DHS and nightlight data is merged to understand whether nightlight data can be used to predict poverty. The first image to the left shows a map of asset scores that are modeled by nightlight luminosity. The author explains how nightlight luminosity is a great indicator of wealth and lower poverty with cool colored dots representing higher asset wealth. The figure on the right shows a linear regression model illustrating the relationship between wealth and nightlight luminosity. The results of this study shows that we can use CNNs with daytime and nighttime satellite imagery and combine it with survey data to accurately and efficiently track impoverished areas in specific places. 


Another important geospatial data science method includes CDR data, or call detail records, which collects a detailed record of all telephonic calls produced by a telephone exchange. On the other hand, RS data or remote sensing data collects physical properties of the earth. RS data and CDR data are a complementary pair when combined having the ability to capture human living conditions and behaviors. Jessica Steele, author of “Mapping poverty using mobile phone and satellite data,” dives into how cell phone data is collected and paired with satellite information. Steele mentions using hierarchical Bayesian geostatistical models (BGMs) to create high resolution maps  of poverty. She started out by approximating the mobile tower coverage areas using Voronoi polygons.

<p align="center">
<img width="506" alt="Screen Shot 2021-11-22 at 4 53 50 AM" src="https://user-images.githubusercontent.com/89988140/142840438-7633250f-6188-4d00-a167-4b49dcd725e4.png">

The image above shows the spatial detail of Dhaka, Bangladesh and the spatial structure of the Voronoi polygons based on the mobile cellphone towers. Each polygon was then assigned RS and CDR values that represented the data collected from the DHS WI, PPI, and income surveys.  The DHS WI, or Demographic and Health Surveys Wealth Index, uses assets and housing characteristics to assign a WI score. PPI, or the Progress out of Poverty index, measures household expenditures and uses satellite data to identify whether a household falls below the below or above the poverty line. Finally, income surveys provide individual information such as household income, gender, age, profession, and education. This information combined provides a value for each polygon, giving information on each section of land in Bangladesh. 

The results of this study found that models with the combination of RS and CDR data provide an advantage over models with just the data source. The data showed that when RS data and CDR data were combined, they produced a higher R-squared value in urban areas compared to RS-only or CDR-only data. However, the results also demonstrate that CDR-only and RS-only data models perform comparably in their ability to map poverty indicators. These findings address my research question regarding utilizing these data science techniques to predict poverty in regions where it is not as evident. However, Steele does take into account a gap in data such as the fact that the models do exhibit higher uncertainty where less data is available.

In conclusion, I have learned a lot about how data science techniques such as satellite imagery and CDR and RS data can be used to eradicate poverty. Poverty assessment and analysis have grown considerably with the utilization of CDR and RS data and satellite data. I believe that all the articles detailed poverty mapping and prediction of poverty.  However, they failed to address how the information was used. I am interested to know whether these methods and techniques of poverty assessment can be used in areas and regions where poverty is not as evident. Although the results show real promise, there are still gaps in data.



### Citations:

Bill and Melinda Gates Foundation, World Bank, Grameen Foundation. “High Resolution Progress out of Poverty Mapping.” WorldPop, https://www.worldpop.org/portfolio/project?id=22. Accessed 30 Sept. 2021.

Castelán, Carlos Rodríguez, et al. “Making a Better Poverty Map.” World Bank Blogs, blogs.worldbank.org/opendata/making-better-poverty-map. 

Horton, Michelle. “Stanford Scientists Combine Satellite Data, Machine Learning to Map Poverty.” Stanford School of Earth, Energy & Environmental Sciences, pangea.stanford.edu/news/stanford-scientists-combine-satellite-data-machine-learning-map-poverty. 

Kumar, Asmi. “How to Understand Global Poverty from Outer Space.” Medium, Towards Data Science, 6 July 2020, towardsdatascience.com/how-to-understand-global-poverty-from-outer-space-442e2a5c3666. 

Sen, Amartya Kumar. Development as Freedom. Oxford University Press, 2001. 

Steele, Jessica E., et al. “Mapping Poverty Using Mobile Phone and Satellite Data.” Journal of The Royal Society Interface, vol. 14, no. 127, 2017, p. 20160690., doi:10.1098/rsif.2016.0690. 
