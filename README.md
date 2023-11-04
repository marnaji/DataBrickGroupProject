# DataBrickGroupProject
## Background 
In our collaborative project, we conducted data analysis utilizing a database associated with an imaginary company known as Northwind. The process involved the following steps:

1. Importing data from various sources.
2. Examining and interpreting the data.
3. Creating visual representations of the data.
4. Communicating the insights derived from the data.
All queries were executed using SQL, and PySpark was not utilized for this purpose.

# Report
* Northwind is a company that interacts with a total of **91** companies/customers across **21** distinct countries.
* Total orders are 830 from *1996* to *1998*.
* Germany and USA have the highest orders of **122** each.

![Orders](/images/CountriesOrders.png)

* Austria has the heaviest shipment in terms of weight *184.78* and Ireland has the second highest shipment weight of *145.01*, third being USA with sjipment weight of *112.87*, Germany being fourth with shipment weight of *92.48* and Sweden being fifth with weight of *87.50*.

![HighestWeight](/images/HighWeight.png)

* There are **77** products that are sold and most of them are groceries
* Top **5** companies with highest orders are **Save-a-lot Markets** with *31*, **Ernst Handel** with *30*, **QUICK-Stop** with *28*,**Hungry Owl All-Night Grocers** with *19*, **Folk och fa HB** with *19* and so on.
* Companies that spent the most on orders are Quick-Stop with *$117483.39*, Save-a-lot Markets with *$115673.39*, Ernst Handel with *$113236.68* , Hungry Owl All-Night Grocers with *$57317.39* and Rattlesnake Canyon * Grocery with *$52245.9* amount spent respectively.
* There are a total 9 employees in the company
* EmployeesID 4(Margaret Peacock) has the highest orders sold at **156**, employeeID 3(Janet Leverling) sold **127** orders, employeeID 1(Nancy Davolio) sold **123** orders, employeeID 8(Laura Callahan) sold **104** and employeeID 2(Andrew Fuller) sold **96** orders respectively.
* There are no customers that haven't placed an order
* Some of the products that have the highest discount are wine (Côte de Blaye) from **$52.7** to **$42.16** discount and German sausage (Thüringer Rostbratwurst) with *$30.94* discount 
* Three employees were enough to fulfil almost half the orders out of **830** total orders.
* The three most sold products were two types of cheese and soda. 
### Recommendation 
1. They can reduce the number of employees because 3 employees were enough to fullfill the half of the total order **830**. The first three employees sell 406 total orders.Find encouraging ways to motivate employees to sell more orders.

![Employees](/images/Employees3.png)

2. Increase the products that has been offered to attract more Customers, and increase the orders by countries that order less. 

![ItemSold](/images/itemSold.png)

3. Advertise the products that has been sold the most and add some promotions for less sold items. 

![highSold](/images/HighSoldItem.png)

![lessSold](/images/lessSold.png)
