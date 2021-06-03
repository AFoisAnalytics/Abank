# Abank

## PowerBI Reports

Measures created in DAX:

	- Blue Collar = CALCULATE([Total Balance],AmericaBankNew[Job Classification] = "Blue Collar")
	- Female Balance = CALCULATE([Total Balance],AmericaBankNew[Gender] = "Female")
	- House Owner Balance = CALCULATE([Total Balance],AmericaBankNew[HouseLoan] = "Yes")
	- Male Balance = CALCULATE([Total Balance],AmericaBankNew[Gender] = "Male")
	- Renters Balance = CALCULATE([Total Balance],AmericaBankNew[HouseLoan] = "No")
	- Total Balance = SUM(AmericaBankNew[Balance])
	- White Collar = CALCULATE([Total Balance],AmericaBankNew[Job Classification] = "White Collar")

### Balance per Customer Demographics
![alt_text](https://github.com/AFoisAnalytics/Abank/blob/main/Imagines/Abank%20Report%20-%20Balance%20per%20Customer%20Demographics.png)

### Age Groups and Balance Groups
![alt_text](https://github.com/AFoisAnalytics/Abank/blob/main/Imagines/Abank%20Report%20-%20Age%20Groups%20and%20Balance%20Groups.png)

### Loan Default per Customer Demographics
![alt_text](https://github.com/AFoisAnalytics/Abank/blob/main/Imagines/Abank%20Report%20-%20Loan%20Default%20per%20Customer%20Demographics.png)

### Data Model
![alt_text](https://github.com/AFoisAnalytics/Abank/blob/main/Imagines/Abank%20Report%20-%20Data%20Model.png)
