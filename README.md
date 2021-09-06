# Inventory-Management-System
IMS is the project based on the operations of a shop i.e, enlisting the products on a remote system, selling , updating etc<br/>
## Description about the project functionalities:
### This project contains 2 jupyter notebook files:<br/>
1. inventory_jsonfile_creation: to create record.json file containing all the details about the product present in the store and also creates employee records.
2. IMS operations: this notebook contains the execution of the operations related to a inventory.<br/>
### It also contains 3 .json files:
1. records.json: contains the details of all the product present in a inventory
2. sales.json: contains the details about the all the transactions(purchase related) happened in the inventory
3. employee.json: contains the details about the employees work at the inventory<br/>
## Functionalities in the Project:
In the project there are two types of functionalities are present:<br/>
### 1.Customer specific functionalities: A customer can access these functionalities<br/>
![](https://github.com/captainra1/images/blob/master/git_img.png)
1. a customer can check all the products present in inventory<br/>
![](https://github.com/captainra1/images/blob/master/git_img5.png)
![](https://github.com/captainra1/images/blob/master/git_img6.png)<br/>
2.when a product goes out of stock it will remove the product from records.json<br/>
3.for purchasing a product: this function consists of several other functionality:<br/>
                           (i)slip generation<br/>
                           (ii)sales history generation(sales.json file generation and updation)<br/>
                           (iii)updating the records.json after purchasing the product.<br/>
   4. we can check the most purchased product.
### 2.employees specific functionalities: A customer can access these functionalities<br/> 
first it checks for employee id if it is correct than a employee can access employee related functions.<br/>
![](https://github.com/captainra1/images/blob/master/git_img2.png)<br/>
1. If there is a new product a employee can add the product in the inventory
2. If there is a product which is to be removed for some reason can be removed by this
3. same as in customer functionalities
4. same as in customer functionalities
5. If there is a change in the existing product i.e, in price or quantity
6. A employee can access all the sales history<br/>
![](https://github.com/captainra1/images/blob/master/git_img3.png)<br/>
7. A employee can also update employee record
