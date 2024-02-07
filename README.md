# Java-Angular_Vendor-Ecommerce

Problem statement 
XYZ company provides the E-comm platform to local vendors to take their business online. 
Local Vendor

Local vendor can login with vendor id, choose its category of business, upload products with price, check orders based on order locations, apply discounts during festival season, view its products and check sales report.

Home screen should show products of multiple vendors.

Customer
• Login
• Buy view and buy products
Please make reasonable assumptions wherever required and state them clearly in a separate text file (if any).

2 Applications are to be developed

First application (REST API – No UI, only backend):

User authentication API 
Build a Rest API to support successful/unsuccessful user authentication validation.

User registration API 
Build a Rest API to register new users.

Upload products
Build Rest API to upload products with complete details (name, category, image, price, Brand etc)

Buy product
Build Rest API to buy product (no need to add any payment options)

Sales Report
Build Rest API to generate total sales report that can be filtered on following criteria 
• Product type
• Product brand
• date

Update discount on product
Build Rest API to update discount on selected product

Product Details API 
Build a Rest API to get other details such as description for product




Second Application (Angular)


Homepage 
Landing page should have links for Registration and Login.

Login Page 
The application should have a login page. User should be able to login. Proper error messages should be handled in case of invalid authentication. Login page should provide the option to login as admin or customer.

Registration Page 
The application should have a registration page. User should be able to register. Validation for email address, password policy, mandatory fields such as name etc. should be performed.

Customer login view
Once customer is login, customer should see the product, price, discount, and buy option.

![image](https://github.com/YashKeshari/Java-Angular_Vendor-Ecommerce/assets/79370070/36635b04-bbc9-471a-891d-6fc39dbec830)

Vendor view
Once login, vendor can view its uploaded products, admin can also filter products based on bands and category.
This view also provides an option to go to add product and view reports

![image](https://github.com/YashKeshari/Java-Angular_Vendor-Ecommerce/assets/79370070/3badec55-2cf4-4412-87c4-888fd29fea44)

Add Product
Vendor can add new product with all product details

![image](https://github.com/YashKeshari/Java-Angular_Vendor-Ecommerce/assets/79370070/1e52cdaf-1fc5-4462-b3be-436bd3580244)

View sales report
Vendor can also view sales reports based on date, product brand and category

![image](https://github.com/YashKeshari/Java-Angular_Vendor-Ecommerce/assets/79370070/32ad00df-2f5a-4a7d-8d0b-19f305f24bc9)

Every page should give the option to logout
