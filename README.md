

# Excel: Road-Safety from 2019-2020
### Brief: 
Asked to observe the road safety datasets from the UK government website and find and present some insights. I decided to focus on casualties in 2019 pre-pandemic and 2020 where the pandemic was at its peak. 

### Areas of focus: 
#### 1)Quantity of casualties across Urban, Small Towns and Rural Areas
#### 2)Casualty Severity within the area type
#### 3)Speed Limits 

### Data Cleaning: 
The answers to my questions didn't require much cleaning but when it was necessary i used to the following techniques:
-XLOOKUP()
-VLOOKUP()
-Pivot Tables 

### XLookup/Vlookup:
As the focus was casualties, the speed limits were organised in a field/column and this was not present in the casualty data but it was present in the accident data. As both sets of data had an accident reference, a V and X lookups were sufficient to append merge the data into a master dataset. Some other bits of data like Urban, Small Towns and rural areas were coded numerically but had another table that acted as key values. Vlookups and Xlookups were used to generate new columns with the value of the key. See images below: 

Use of Xlookup() to get the speed limit records: 

![Xlookup output and command](https://user-images.githubusercontent.com/116355407/230797712-22f045f2-4865-4c05-9214-e72b970399c2.png)

Vlookup() command to get the casualty class (Driver/rider, Passenger etc.):

![Vlookup command](https://user-images.githubusercontent.com/116355407/230798613-bba07a16-6c0f-4289-bca6-5f1f0163a204.png)

Vlookup() output:

![Vlookup output](https://user-images.githubusercontent.com/116355407/230798626-0c25c136-10bd-4ef7-b4a8-88c9c233e637.png)

### Visualisations 
Below is a few examples of visualisations that were generated in excel

Casualties in 2019: 

![Recorded Casualties from 2019](https://user-images.githubusercontent.com/116355407/230801108-1ff04c57-13a9-48ef-9845-6fc750bacd05.png)

Casualties in 2020: 

![Recorded Casualties from 2020](https://user-images.githubusercontent.com/116355407/230801140-8bd9eaea-42e5-4482-b1ae-f10dc5fdf0e9.png)

2019 and 2020 key:
![2019 and 2020 key](https://user-images.githubusercontent.com/116355407/230801157-ef629fff-5f6e-4c83-a6c5-f0fecb56de05.png)

Fatalities in Rural Areas: 

![Fatal Casualties in Rural Areas](https://user-images.githubusercontent.com/116355407/230801172-ba68af6d-6669-43e5-8b14-b18e5d4e1eba.png)

Fatalities in Urban Areas:

![Fatal Casualties in Urban Areas](https://user-images.githubusercontent.com/116355407/230801187-b7fca656-b2fb-45e0-a917-84986ea7bc3d.png)


## Conclusions:

In 2020 there were considerably less casualties which was heavily due to covid-19 affecting road traffic due to a lot of businesses being in lockdown and as a result - reducing the need for cars to commute. Despite this, it is still common occurence, the majority of casualties are still occuring in Urban areas thus confirming that despite a lockdown, high volume oncoming traffic is still a persistent problem. 

In terms of fatalities, there were still very similar trends compared to 2019 where covid-19 was unheard of. 30mph speed limits make up the largest portion for fatalities in urban areas despite a significant reduction in traffic whereas in rural areas, 60mph makes up the largest portion of fatalities compared to others. Rural roads are typically branded as a 60mph speed limit and due to the unstable terrain that rural roads posess, they carry the greater risk of fatal accidents should lack of concentration, poor driving habits and even natural occurences such as falling rocks, be a contributing factor to casualties. 

Overall, we can attribute that less casaulties occured due to less traffic during covid times and we can further conclude that despite this that humans will still face the same problems that cause accidents. More information can be found in the attached powerpoint....

## Reflection:

I was pleased with how this project went and I picked up the data cleaning techniques and applied them well. Next project with excel, I will use data that had more consecutive years to conduct further year-on-year analysis and use more advanced excel techniques such as power query for merging tables. This will be entirely dependent on project necessities. 










