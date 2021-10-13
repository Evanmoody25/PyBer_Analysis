# PyBer_Analysis

## Background

V. Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.


## Requierments

1) The total number of rides for each city type is retrieved.

2) The total number of drivers for each city type is retrieved.

3) The sum of the fares for each city type is retrieved.

4) The average fare per ride for each city type is calculated.

5) The average fare per driver for each city type is calculated.

6) A PyBer summary DataFrame is created.

7) The PyBer summary DataFrame is formatted as shown in the example.

## Deliverable 1

1) The total number of rides for each city type is retrieved.

![Capture](https://user-images.githubusercontent.com/89880015/137067318-026c193e-cc42-43b4-b21c-3c892303fd7c.PNG)

2) The total number of drivers for each city type is retrieved.

![Capture](https://user-images.githubusercontent.com/89880015/137067560-5c3aa259-b727-4bda-98d3-6af5d9d4f6d1.PNG)

3) The sum of the fares for each city type is retrieved.

![Capture](https://user-images.githubusercontent.com/89880015/137067800-405e84b9-6b46-4585-b41c-45345397c435.PNG)

4) The average fare per ride for each city type is calculated.

![Capture](https://user-images.githubusercontent.com/89880015/137067932-2c433b06-5045-42ab-b958-e4908495ad80.PNG)

5) The average fare per driver for each city type is calculated.

![Capture](https://user-images.githubusercontent.com/89880015/137068089-2d213ef2-d6b4-483c-a286-d23e7fef8857.PNG)

6) A PyBer summary DataFrame is created.

![Capture](https://user-images.githubusercontent.com/89880015/137068322-3c065fc3-018e-40ef-9e45-160cd5a5c0dc.PNG)

7) The PyBer summary DataFrame is formatted as shown in the example.

example: 

![Capture](https://user-images.githubusercontent.com/89880015/137068486-0cd57027-a0e1-441f-9dee-54a92694e73d.PNG)

my work: 

![Capture](https://user-images.githubusercontent.com/89880015/137068632-f2688da4-39fb-486b-9694-189d3a7fd7f5.PNG)

## Deliverable 2 requierments

1) A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time.

2) A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare."

3) A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-28.

4) A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week.

5) An annotated chart showing the total fares by city type is created and saved to the "analysis" folder.

## Deliverable 2

1) A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time.

![Capture](https://user-images.githubusercontent.com/89880015/137147577-fa3f915e-7be7-4f7f-85d8-050f81cd193d.PNG)


![Capture](https://user-images.githubusercontent.com/89880015/137147905-a177e509-5782-4775-9b68-83d9138a14f1.PNG)


2) A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare."

![Capture](https://user-images.githubusercontent.com/89880015/137148623-57152514-d136-4356-b723-c9793cb5dc99.PNG)

![Capture](https://user-images.githubusercontent.com/89880015/137148987-3f66cc4b-4b4f-4b73-aa4b-3958b3668813.PNG)



3) A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-28.

![Capture](https://user-images.githubusercontent.com/89880015/137149299-8c69dcdc-afdf-49f2-9726-8b5ea7900dfd.PNG)



4) A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week.

![Capture](https://user-images.githubusercontent.com/89880015/137149607-c808decd-5feb-4a2a-9df5-9247c9f3afc4.PNG)


5) An annotated chart showing the total fares by city type is created and saved to the "analysis" folder.

![Capture](https://user-images.githubusercontent.com/89880015/137149975-945a1fba-9d43-4541-a08b-5734cc37737b.PNG)


![Capture](https://user-images.githubusercontent.com/89880015/137150085-56dd4106-f5a1-4439-b34e-d20389e4ff72.PNG)

##  Deliverable 3

Purpose: To create a summary of company data for the company, PyBer. Academicaly, it can be said that the purpose of this challenge was to put into practice Python and Pandas to 
create statistical models which give displays of what is going on with the data. Finding summary statistics is also relevant to this project. In a practical, real world sense, 
we are trying to find trends within the data that may be keys to how PyBer as a company can be run more efficiently. 

results: Rural fares are very low but relatively steady throughout the year when compared to urban and suburban fares. Their low fare numbers could likely be attributable
to rural having a less densly populated area. Suburban is the same with higher fare numbers and so is urban. One area of interest is that fares for all categories drop off in 
march and april. 

Summary
1) Further research must be done to see if buisness can be expanded into rural cities or if the low fares are just an part of the low population densities of these areas. 
Some may want to jump at this opportunity but I feel that one reason rural is so low is outside of cities, areas are often far apart, sparsley populated, and the population
has a dependence on their own cars which may mean that throwing more drivers into these areas may just mean sinking funds. 

2) This may be why urban is high and consistently high. Having that population density is important but urban areas also means it is tricky for people to have their own cars
as parking is hard to find and often expensive. Some people get enxiety when driving in congested urban environments. If there is somrhing that the company can change to reverse the drop in fares for march and april, i highly advise becoming a more prominent service in big cities. 

3) in plain summary, rural had the lowest fares, suburban secong lowest, and urban highest. There is a drop off in march and april that needs to be looked into and I am 
curious about expanding services into urban areas even more rather than investing in areas where personally owned cares become a viable alternative to PyBer. I must conclude, however, by saying that more research must be done to etablish a true cause and effect relationship in the data. This is mearly a glimpse at company data. 








