jQuery was used for ease of appending dynamically generated data to a table (jQuery 3.3.1 min)

You can hover over Date, Tango, and India cells to see full value

I used the tablesorter jQuery plugin because a table of this size needs to be sortable* 
(link to the plugin is found in main.html where it is initialized)

***Please note that sorting the Date column does not work properly*** 
There is a way to get tablesorter to sort by a hidden value but
For this demo I didn't want to spend more time to learn how to implement this feature.
(In a real world setting this would be fixed and working)
Instead I included a column "num" which is the order that the data is generated in which is also date order

Thanks!