

# Excel: - Road-Safety from 2019-2020
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








