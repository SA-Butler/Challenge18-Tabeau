## Analysis

*** Please read the Readme file before this analysis ***

The data set explored was downloaded from the citibike website in the form of monthly csv files. The data chosen to meet the challenge was data from January and July of 2022. The data was read into pandas dataframes, understood, cleaned and analysed in a jupyter notebook in this repositry called "transform.jpny".


![JC-NYC](https://user-images.githubusercontent.com/113118793/224563239-534edeb8-6d70-4905-94ff-d0e3044c5f4a.jpg)


## Analysis
The first question to answer was the differences in the number of Citibike trips originating during January and July 2022 from Jersey city. This is detailed in the table in the tab Seasonal Variation Breakdown. 

The difference is significant, with around 27 thousand trips in January as opposed to 107 thousand in July. (see Seasonal Variation Breakdown, and seasonal variation Graphical tab.)

The winter destinations were then plotted in the tab "Winter destinations". Summer Destinations were plotted in the appropriately named "Summer destinations" tab. 
Comparing the two, there is a noticable difference with the destinations onto Manhatten Island. THis then served as the basis for further investigation. 

There is a total of 110 trips to NYC during July to 58 different station locations. It should be noted that 110 trips is only 0.1% of the total trips taken from Jersey City in July. The stations are plotted in Summer Destinations NYC tab map. This map has user interaction if required, with locations shown, suitably sized in proportion to the number of bikes docked in the station location. The stations are plotted using a horizontal bar in the tab "Summer Destinations Stations".
The location information was attached to the marker and is displayed along with location co-ordinates, when the mouse moves on to the marker. The total number of hires is also diaplayed. It can be seen that the larger number visited stations are in the southeast corner of manhatten. This is the location of the crossings by ferry and rail (PATH) connections. This is likely to be the favourite location to enter and leave NYC from Jersey City. 

A scatter diagram was calculated by plotting the ride duration versus distance. There is an increase in scatter as duration and distance increases due to variation in cycling speeds and the nature of the journey (e.g. direct point to point or touring) make an impact. 

The analysis therefore gives a clear indication of the seasonal variations expereinced in trips fro Jersy City. The summer increase in trips to manhatten is significant by comparison but is only a small percentage of the overal summer trips from Jersey City. 



