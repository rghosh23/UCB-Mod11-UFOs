# UFO Sightings
## Overview of the Project
The goal of this project is to help Dana build a dynamic website using JavaScript. The data of UFO sightings around the world is displayed in tables on an HTML web page. We will also add filters to the data so that users can hone in on the exact data they might need.
### Purpose
The purpose of this analyses is to use functions and for-loops to filter the data for multiple criterias. This way the user can filter on multiple different criterias.
## Results
![Screen Shot 2022-06-23 at 2 25 34 PM](https://user-images.githubusercontent.com/102441140/175405125-fedba1b0-6bc3-475f-a84d-fc6b00a7a968.png)
***Figure 1: Overall unfiltered data***

The figure above shows the unfiltered data. There are multiple search bars to the left hand side. Each search bar has words or dates pre-filled in already to the user can easily identify how to put in key words to perform the search. 

![Screen Shot 2022-06-23 at 2 31 13 PM](https://user-images.githubusercontent.com/102441140/175405873-52c4fd67-1090-4304-a411-a0d3d54be845.png)
***Figure 2: Filtered data using the date search bar***

The figure above shows the data filtered by the date. With the applied filter we see 11 rows. The filters make it really easy to look at the exact data the user needs. The HTML website displayes the data in a viually appealing way, which is much nicer than Dana's original JSON file.

**Steps to perform the search:**

1. Type in the item of search in the exact manner it is on the dataset into the respective search bar. The JavaScript is not smart enough to filter properly through autocorrect.
2. When the filters have been properly typed in, click on the filter bar in order to execute the filter.
3. The website presents the exact dataset of interest to the user
4. To remove a filter, simply delete the keyword in the filter search bar and click on said filter search bar to refresh the page. 

## Summary

*Drawbacks*

While the filter works and displays the correct dataset, it is very sensitive as to how the keywords are inputted. The user has to inout the data exactly as it is represented on the dataset. This makes is complicated as the user accessing the website would not know that the search bar is sensitive to how we input the key. The user also would not know to click on the search bar to activate the search. 

*Recommendations*

While Dana's website is really great, there is scope for some improvement to the user experience. Here are some recommendations below:
- The search bar function should be modified to ignore any spaces the user might add such as, "1/14/2010 " instead of "1/14/2010"
- The date search bar should also be modified to include any variations to the date and also to not be case-sensitive
- Dana should also think about changing the way the search is executed. Maybe add a button labeled "search" or "run" that the user can click instead to execute the search
