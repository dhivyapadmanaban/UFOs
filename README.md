# UFOs
## Project Overview

In this project, UFO data is built using data stored in JavaScript array. Create multiple filters to make this table fully dynamic to provide a more in-depth analysis of UFO sightings and then place the table into an HTML file for easy viewing. Customize the web page using Bootstrap, and equip the table with several fully functional filters that will allow users to interact with our visualizations.


## Results
 
Below is the UFO sightings webpage at the end of project deliverable. Web page will load with all avaialbe UFO table data during initial page load. Also search filters are independent of each other, we can use any one filter or multiple filter of any order to view the data. 

![image](https://user-images.githubusercontent.com/83181834/125538105-cd93ab2c-5817-4277-acd7-6bf6af3e659b.png)

**- Date search:**

 The search filters are designed to be dynamic so when we enter the data (sample date format is provided in the text box), the table data is filtered by just moving the mouse pointer from the text box i.e the code detects the change in the text box and filters the data accordingly. In this example, we have 8 UFO sightings for 1/2/2010.

![image](https://user-images.githubusercontent.com/83181834/126022704-722c3cb2-e8ae-48b0-8f27-c8ded8ef85ce.png)

**- City search**

 City search is used to filter the data based on any US cities. Sample format is given in the text box and below the city search results. In this example, there is only one UFO sightings in "Bakersfield" city.
 
 ![image](https://user-images.githubusercontent.com/83181834/126022762-6d308b92-9cbf-4cda-83fa-69f512dcd1a3.png)

**- State search**

  State search is used to filter the data to view any UFO sightings within any US states. Note: Filteration data is case sensitive. In this example, we have only 3 UFO sightings in Arizona state.
  
  <img width="1067" alt="state search" src="https://user-images.githubusercontent.com/83181834/126022809-0bfff578-0f88-4312-b994-22d50dda4783.png">
  
 **- Country search**

   Country search is provided to filter UFO sightings in each country. Although we are dealing with US only data for our project, this search will be helpful if we expand our dataset. In this example, all the data is shown for the country "US".
   
   <img width="1063" alt="country search" src="https://user-images.githubusercontent.com/83181834/126022870-97396e65-db53-4c4c-8743-9634a79d7bfc.PNG">
   
**- Shape search**

   Shape search helps in finding UFO sightings according to the shapes of the sightings. In this example, there is no "square" shaped UFO sightings so the table returned no data.
   
   ![image](https://user-images.githubusercontent.com/83181834/126022897-e19a19c7-e62a-466c-9900-a0af6da5e174.png)

## Summary

### Drawback

**Data filters :**  Current web page's search filters are entered manual and its case sensitive. Ideally in a real world environment, common users are not trained to use web page like developers. In this scenario, if the user entered "US" or "USA" or "usa" the data won't be displayed. 
<img width="1063" alt="Drawback" src="https://user-images.githubusercontent.com/83181834/126051304-31a39da8-de7f-4641-a3bc-72053c44452b.PNG">

### Recommendations

Below recommendations helps in further development and fix the drawback of the current deisgn:

- Improving User friendly interface : Search filters can be converted to drop downs filters which provide better user interaction.
 -  Date Filter : Provide calendar to pick the date. This avoid the user confusion about entering the date manually in the required format (MM/DD/YYYY).
 -  City Filter : Select the unique city names from the sample dataset and provide as dropdown filters.
 -  State Filter : Select the unique state name from the sample dataset and list down as dropdown entries. We can make both these filters auto fill depending on each other selection.
 -  Country Filter : Selet unique county name from the dataset and list down as dropdown.
 -  Shape Filter : Unqiue shapes from dataset are listed as dropdowns.
- Button click is always better option and easy on users to complete their search. 

- With the current design the data is loaded when the page is loaded. This works just fine if we have limited data but in the case of handling huge data this makes the webpage longer and definitely not user friendly. No loading table data during page load and use filter options to view the data. If design demands provide additional button "All data" to get whole data on request. This speeds up the page loading.

