# ASP .NET Core BestBuy Website Using MVC Modeling

This web app was built in C# on the .NET Core framework.
This project was built to represent a list of products that may be found on Best Buy's website. An example of a product on the database is found below:

public class Product
    {
        public int ProductID { get; set; }
        public string Name { get; set; }
        public double Price { get; set; }
        public int CategoryID { get; set; }
        public int OnSale { get; set; }
        public int StockLevel { get; set; }
        public IEnumerable<Category> Categories { get; set; }
    }
   
Features of the Web App
========================
* The database of the website is built through a connection to MySQL with a transient registered repository.
* Utilizes Dapper to interface with MySQL and uses Razor to connect Models and Views on the backend.
* Allows a user to perform all CRUD operations on examples of Best Buy products.


