# Module 11 Challenge: UFOs
![Webpage](https://github.com/mbroad1/Module-11-UFOs/blob/main/Analysis_Images/Webpage.png)
## Purpose:
The purpose of this assignment was the develop a webpage that showcased a table filled with data about UFO sightings. Likewise, this table had to have multiple filters for the data such as state and country where the UFO sighting took place. This webpage was created with HTML and styled with CSS and Bootstrap, and Javascript was used to make the webpage hold the data and be interactive.
---
## Results:
![Table](https://github.com/mbroad1/Module-11-UFOs/blob/main/Analysis_Images/Filtered_Table.png)
**The Advantages of Having Multiple Filters**
Adding more filters to the data table displayed on the webpage makes the table more dynamic in the sense that more specific data can be pulled from the data table unlike before when there was only one filter for datetime.

As seen in the image above, the data table can not only be filtered on a specific date, but also can be filtered on a specific city, state, country, and shape (of the UFO).

Therefore, the main advantage of having more filters for the data table is that users can pull as specific as they want data from the table.

**The Disadvantage of Having Multiple Filters**
The only issue that the user needs to keep in mind when entering multiple filters such as entering a state and country is to make sure that the state is in the country; otherwise, no data will be shown on the table because there is no data that would match those two criteria.

---
## Summary:
The one drawback of this updated webpage is that the filter button was taken away from the page (the HTML code for the filter button in the index.html was removed and the D3 code specific to the filter button was also changed), so the user is actually unable to filter the data from the webpage.

For further development, I recommend re-adding the filter button to the webpage so that users are able to use the multiple filters that were added. Also, I recommend adding a console.log() statement to the if-else code in the updateFilters function that reads "Results do not exist" if the user inputs a combination of filters (e.g. a state that is not in a country) that no data corresponds with and thus no data would be shown in the table.
