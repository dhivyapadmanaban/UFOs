# UFOs
## Project Overview

In this project, UFO data is built using data stored in JavaScript array. Create multiple filters to make this table fully dynamic to provide a more in-depth analysis of UFO sightings and then place the table into an HTML file for easy viewing. Customize the web page using Bootstrap, and equip the table with several fully functional filters that will allow users to interact with our visualizations.


## Results
 
Below is the UFO sightings webpage at the end of project deliverable. Web page will load with all avaialbe UFO table data during initial page load. Also search filters are independent of each other, we can use any one filter or multiple filter of any order to view the data. 

![image](https://user-images.githubusercontent.com/83181834/125538105-cd93ab2c-5817-4277-acd7-6bf6af3e659b.png)

**- Date search:**

    The search filters are designed to be dynamic so when we enter the data (sample date format is provided in the text box), the table data is filtered by just moving the mouse pointer from the text box i.e the code detects the change in the text box and filters the data accordingly. In this example, we have 8 UFO sightings for 1/2/2010. 
    ![image](https://user-images.githubusercontent.com/83181834/125538279-0fde8d3c-f3e2-4e99-b4f9-f9246ca01b7e.png)

**- City search**

    City search is used to filter the data based on any US cities. Sample format is given in the text box and below the city search results. In this example, there is only one UFO sightings in "Bakersfield" city.
    ![image](https://user-images.githubusercontent.com/83181834/125538453-29904e24-f88a-4dbd-b580-4fae1e18f62a.png)

**- State search**

    State search is used to filter the data to view any UFO sightings within any US states. Note: Filteration data is case sensitive. In this example, we have only 3 UFO sightings in Arizona state.
    ![image](https://user-images.githubusercontent.com/83181834/125538589-edd86858-1bef-4a43-b0a5-95c31b35cdd5.png)
   
**- Country search**

    Country search is provided to filter UFO sightings in each country. Although we are dealing with US only data for our project, this search will be helpful if we expand our dataset. In this example, all the data is shown for the country "US".
    ![image](https://user-images.githubusercontent.com/83181834/125538689-d270c3a2-e645-4a62-a9c4-1e64a76d013b.png)

**- Shape search**

    Shape search helps in finding UFO sightings according to the shapes of the sightings. In this example, there is no "square" shaped UFO sightings so the table returned no data.
    ![image](https://user-images.githubusercontent.com/83181834/125538831-315cb196-ea87-4477-b12d-1d166a34fa48.png)


## Summary
###Drawback
-Filter data is case sensitive. Either change filter to accept only lower case or convert upper case to lower case in code. 

###Recommendations
