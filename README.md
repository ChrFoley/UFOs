# UFOs

# Challenge

## Purpose
Adding additional depth to the filter function increases the efficiency of the end users search. By adding this function to the UFOs web search app it becomes more robust as well as user freindly. Allowing the end users to search multiple filters increase usability and ease throught the search function. In addition to the Date search, users can now search by these additional filters:
 - Date
 - City
 - State
 - Country
 - Shape
 
### Method
To add additional seach capability, the following was completed:
 1. update app.js
    -replace the handleClick function with a loop to track all filters and store the data
    -write the data to the filtered table
 2. Update the inde.html
    - create new filter boxes for each new category.

### Output
Data outputs are based on data being in the table, and is diplayed in print order.

### additional refinement
1. Create a dynamic reset on the webapp that will clear the search and return the user to the original data set.
2. Alert user if there is no data matching the query, this will alleviate any confusion of the web app stalling.
