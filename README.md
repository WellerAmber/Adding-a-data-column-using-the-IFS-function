# Adding-a-data-column-using-the-IFS-function
Here is an example of how I add a data column using IFS function

The worksheet needs the following additional information for Contoso Bikes:

1.Delivery charges: When working with Excel the proper input to get this information is =IFS(J7="A", 
D
 2,J7="B", 
D
 3,J7="C", 
D
 4,TRUE,0) This input is telling Excel to take the delivery location letter and match it with the delivery price for each number A=50, B=75, and C=100.

2.Discount rates: When working with Excel the proper input to get this information is =IF(G7>10000,0.1,0) This input is telling Excel to look at the number in each cell of the subtotal column telling it to give a 10% discount if the subtotal number is larger then 10,000. If it is not larger then 10000 then it gives a 0 or 0% discount.

3.And regional totals: When working with Excel the proper input to get this information is =K7+L7 This is a simple input that is just adding together the total and the delivery amount.
