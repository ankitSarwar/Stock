<h1 align="center"> Stock </h1>

-   The Stock Controller is a part of the Doctor App project, implemented using the Spring Boot framework. It provides various endpoints to manage stocks and perform CRUD operations. 

> ### [](https://github.com/Rushi-29/REstaurantManageamentSystem#prerequisites)[](https://github.com/Rushi-29/E-commerce#prerequisites)Prerequisites

-   [![MySql](https://camo.githubusercontent.com/ba7cdc426003905af438f0938e0890b3437e590d2c249d671115d19ca32b5df6/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f44424d532d4d5953514c253230352e372532306f722532304869676865722d726564)](https://camo.githubusercontent.com/ba7cdc426003905af438f0938e0890b3437e590d2c249d671115d19ca32b5df6/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f44424d532d4d5953514c253230352e372532306f722532304869676865722d726564)

-   [![SpringBoot](https://camo.githubusercontent.com/a6677a4ec12bd03f835c62db09a8db96a6d726afe3985c8fbf5c43db9b6cb8ad/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4672616d65776f726b2d537072696e67426f6f742d677265656e)](https://camo.githubusercontent.com/a6677a4ec12bd03f835c62db09a8db96a6d726afe3985c8fbf5c43db9b6cb8ad/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4672616d65776f726b2d537072696e67426f6f742d677265656e)

-   [![Java](https://camo.githubusercontent.com/be815b7d90eac640a950b5ef6e2bd93f30cab6ac1cd9ace277bc560e3e6fc11c/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c616e67756167652d4a617661253230382532306f722532306869676865722d79656c6c6f77)](https://camo.githubusercontent.com/be815b7d90eac640a950b5ef6e2bd93f30cab6ac1cd9ace277bc560e3e6fc11c/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c616e67756167652d4a617661253230382532306f722532306869676865722d79656c6c6f77)

> [](https://github.com/Rushi-29/REstaurantManageamentSystem#data-flow)[](https://github.com/Rushi-29/E-commerce#data-flow)Data flow
> ----------------------------------------------------------------------------------------------------------------------------------

>### In this project, we have four layers-

-   Controller - The controller layer handles the HTTP requests, translates the JSON parameter to object, and authenticates the request and transfer it to the business (service) layer. In short, it consists of views i.e., frontend part.
-   Service -The business layer handles all the business logic. It consists of service classes and uses services provided by data access layers.
-   Repository - This layer mainatains the mySQl-database thing on which CRUD operations are performed
-   Model - This layer consists basically the class level things- the various classes required for the project and these classes consists the attributes to be stored.


>### Endpoints

- GET /stock/type/{stockType} : Get stocks based on the specified stock type.
- GET /stock/abovePrice/price/{price}/lowerData/date/{date} : Get stocks above the specified price and lower than the specified date.
- GET /stock/cap/{capPercentage} : Get all stocks above the specified market cap percentage.
- POST /stock/ : Insert stocks into the system.
- PUT /stock/marketCap/{marketCap}/id/{id} : Update the market cap of a stock based on the specified ID.
- PUT /stock/type/id : Update the type of a stock based on the specified ID using a custom query.
- PUT /stock/{id} : Update a stock based on the specified ID.
- DELETE /stock/ownerCount/{count} : Remove stocks based on the specified owner count.






> [](https://github.com/Rushi-29/REstaurantManageamentSystem#project-summary)[](https://github.com/Rushi-29/E-commerce#project-summary)Project Summary
> ----------------------------------------------------------------------------------------------------------------------------------------------------

This Spring Boot project, known as the StockApp, focuses on managing stocks. It provides a RESTful API for various operations such as retrieving stocks based on type, filtering stocks by price and date, querying stocks above a market cap, inserting new stocks, updating stock properties, and deleting stocks based on owner count. The project utilizes the Spring Boot framework, allowing for efficient development and deployment of the application. It aims to simplify stock management and enhance productivity in the context of the StockApp.
