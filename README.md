# Covid-Cases-India-Map-with-Folium
A python script using pandas and folium to plot a map which will display all the states of India with the number of confirmed Covid-19 cases till.  

### covid-19 India state cases.xlsx:
This is the dataset file in excel in which I have collected data of the States in India, Confirmed Cases, Deaths, Latitude and Longitude of the states.  

### Covid Cases India.ipynb:  
This is a python script in which the pandas is used to retrieve data from dataset file *covid-19 India state cases.xlsx* and then folium is used to create map of India in which all the states are displayed with a colored marker and with Label "State_name Confirmed Cases".  

__Color of State Marker : Stage : States having range of Confirmed Cases__  
darkred : Alert : Greater than 2000  
red : High risk : Greater than 1000 and less than or equal to 2000  
lightred : Risk : Greater than 500 and less than or equal to 1000  
orange : Average : Greater than 100 and less than or equal to 500  
green : Below Average : Greater than 0 and less than or equal to 100  

### Covid Map India.html:  
This is the html file of the map which has the visual data of the python script.
