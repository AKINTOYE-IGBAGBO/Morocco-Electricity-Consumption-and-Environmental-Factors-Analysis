# Morocco-Electricity-Consumption-and-Environmental-Factors-Analysis

Week 6 AnalaystLab Project Analysis to electricity consumption patterns across three different geographical zones using  electricity

consumption readings every 10 minutes, alongside environmental measurements such as temperature, humidity, wind speed and 

diffuse flow measurements.


### Objectives

1. To understand how electricity consumption changes over time.
   
2. To check whether environmental conditions are associated with changes in consumption.
   
3. To analyze how the three zones differ.
   
4. To provide analytical and technological solutionscan support better energy management decisions.


### Scope and Tools

Electric consumption records - 52,416

Zones - 3

Year - 2017

Reading Time - 10 minutes

Environmental Measurements - 5


**Tools** - Jupyter Note book

Pandas- Data Cleaning and Analysis

Matplotlib, Seaborn and Plotly - Data Visualization

### Definition of Columns for analysis

1. Power - rate which electrical energy transferred or consumed  measured kW for this project.

2. Energy - column generated to calculate the total energy used/ consumed for every 10 min readings.

3. Month, Day, Hour, Day of the week columns generated to analyze time based electric consumption.


### Importance of Environmental Measurements to Electric Consumption

1. Temperature - provides seasonal insights and electric demands during the season. A  very hot season  may increase electric

   consumption through cooling appliances while extreme cold day may also increase electric demands from heating methods.

2. Humidity -The relative humidity (RH) range spans 0% to 100%, which represents the percentage of water vapor currently

   in the air compared to the maximum amount the air can hold at that temperature.Low humidity can increase cooling demand

   while electric consumption is during high humidity is influenced by temperature.

4. Wind of Speed - measures how fast air moves horizontally across the Earth's surface recorded in kilometers per hour (km/h)

   for this project. Steady outdoor breezes allow for natural cross-ventilation, reducing the need to run air conditioners.

5. General Diffuse Flows -measures  how much emissions gases diffuse into the broader atmosphere. Poor 
 
   atmospheric dispersion may increase electricity consumption.

5. DiffuseFlows- measures how much emissions gases diffuse into the local atmosphere.



### Project Analysis Steps

1. Importing data into notebook using Panda

2. Converting to a data frame

3. Data cleaning

4. Generating calculated columns for further analysis

5. Consumption analysis

6. Time-based Analysis

7. Environmental Analysis

8. Data Visualization 

[All steps and visuals](https://github.com/AKINTOYE-IGBAGBO/Morocco-Electricity-Consumption-and-Environmental-Factors-Analysis/blob/main/Power_Consumption.ipynb)



### Data Cleaning 

Missing Values : None

Duplicate Value : None

Inconsistent Data : No negative value, Exact 10 mins datetime diffference.

About 50 % Diffuse flows> General diffuse flows which could be caused by a lot of factor like leakages and environmental factors.

Records not changed.

Date time Validation: String type converted to datetime type.



### Insights

1.	Zone 1 consumes about 45.41 % of the total power consumption.

2.About 1,191 records a very high consumption in zone 3 during summer periods.

3.	Total power consumption peak from June to august (> 54GWh) while Off-Peak demand occurs in February and December (<46 GWh).

4.	Peak hours for all zones occur during 8 pm while off peak hours are between 6 to 7 am.

5.	Temperature has the highest positive correlation to power consumption, with zone 3 being the most sensitive.

6.	Humidity has a negative correlation with electric consumption.

7.	Windspeed has a low positive correlation with electric consumption.

8.	Peak days of the week for electric consumption is from Tuesday to Thursday.


### Authur

www.linkedin.com/in/igbagbo-akintoye-5344a7ba



