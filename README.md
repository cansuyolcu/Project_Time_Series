# Project_Time_Series
 In this project I'll be developing time series forecasting models to predict future product prices using Facebook Prophet.
 
 Some information about the dataset are:
- almost a million observation 
- 1115 unique stores 
- Note that sales is the target variable (that's what we are trying to predict) 
- Id: transaction ID (combination of Store and date) 
- Store: unique store Id
- Sales: sales/day, this is the target variable 
- Customers: number of customers on a given day
- Open: Boolean to say whether a store is open or closed (0 = closed, 1 = open)
- Promo: describes if store is running a promo on that day or not
- StateHoliday: indicate which state holiday (a = public holiday, b = Easter holiday, c = Christmas, 0 = None)
- SchoolHoliday: indicates if the (Store, Date) was affected by the closure of public schools

The dataset is from [Kaggle]((https://www.kaggle.com/c/rossmann-store-sales/data)).

