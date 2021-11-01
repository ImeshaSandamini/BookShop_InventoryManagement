# BookShop_InventoryManagement
Spring Boot CRUD application for manage inventories

In this book shop inventory management system I have add books as inventories. First User can Register to the system by adding their details. Then user can login to the system by adding their user name and password. I have got the email as User Name.
Then user can add categories. We can add books by according to these categories. Also when adding books we can add book details separately. We can add suppliers according to the category. Also there are pages to show the list of Categories, books and suppliers. Then we can Update and Delete the books.

Technologies: STS IDE, java 8, HTML 5, Maven, MySQL database and Spring security

User can add books according to the category. There for one category can have more than one books, but one book belong to only one category (one to many relationship).
Also I save book details on a separate folder in the database. Then one book can have multiple details (one to many relationship).

Suppliers can added according to the category. One category can have many suppliers and one supplier can supply many categories of books (many to many relationship).


