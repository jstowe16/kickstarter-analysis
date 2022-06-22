# **Analysis of Theater Kick-Starter Campaigns**
## **Overview**
The client, Louise, is interested in Kickstarter campaigns similar to those of the play _Fever_. The client is interested in visualizing the performance of both general theater campaings in relation to the campaign launch month and the subcategory of plays based on the range of fundraising goals. 

The analysis is based on the data provided in "StarterBook.xlsx". 

## **Analysis and Challenges**
### _Theater Outcomes Based on launch_
The primary challenge to determine the month of launch using Excel Pivot Tabes is the removal of the default fields that populate the Row when the Date Created Converstion field is selected. To isolate the months, the default Year and Quarter fields must be removed, even though the Month field is not auto-populated. The auto-populated fields are circled in red in the image below. 

![image](https://user-images.githubusercontent.com/106441473/174940090-a070cbdd-4209-4b4f-a7d3-23c5e6fdac18.png)

### _Play Outcomes Based on Goals Range_
The Excel function "COUNTIFS" primary challenge is the concatenation of the logical criteria statements. It was initially unclear that "COUNTIFS" logic statements were not the same syntax as the "IF" function. The challenge was overcome by utilizing the Excel help found in the function window. 

## **Results**
### _Theater Outcomes Based on Launch_
Theater outcomes based on Launch are provided in the image "Theater_Outcomes_vs_Launch.png". As shown in the plot, the peak successul theater campaigns launched in May. Also, the ratio of successful to failed campaigns reduces consistently in the last three months of the calendar year, the lowest ratio being campaigns that launch in December.

### _Play Outcomes Based on Goals Range_
The specific theater subcategory "Plays" campaign outcomes as a percentage of the total per funding goal range is provided in the image "Outcomes_vs_Goals.png". Plays campaigns with a greater than 70% successful rate have funding goals of less than $5,000.

### _Limitations_
The data provided in the source file are limited to the years 2011 to 2017. The client's campaign is more recent, 2022, and may not be representative of the current fundraising climate. Additional analysis showing year to year trends of theater and play campaign success rates may show whether there is a trend over time to be aware of when considering the client comparison. 
