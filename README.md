# columnfamily
HBase is most effectively used to store non-relational data, accessed via the HBase API. Apache Phoenix is commonly used as a SQL layer on top of HBase allowing you to use familiar SQL syntax to insert, delete, and query data stored in HBase.

Advantage:
This type of distributed and non-relational databases presents a large storage capacity. A table within HBase can consist of hundreds of millions of rows and millions of columns. HBase allows professionals to search for different versions, as well as historical data.

                            NEVER LAUGHING TOO LOUDLY IN A RESTAURANT NO MATTER HOW GOOD THE JOKE
                            
n this family table there are three columns named Restaurant,Menu containing three rows basically

![WhatsApp Image 2023-03-18 at 10 04 29 PM](https://user-images.githubusercontent.com/123790535/226156094-aaa6f1d8-f9fc-4f95-8d6d-bf8e62849cb0.jpeg)


I inserted the values of row no 02 by changing their branch details of restaurant.In the second row I deleted the session of menu details column using delete keyword, Then I updated the values of row no 03 by changing their timing details. finally I inserted the discount of menu details by using the put keyword

![WhatsApp Image 2023-03-18 at 10 04 24 PM](https://user-images.githubusercontent.com/123790535/226156123-0f4077b9-3610-418f-b07d-d0ff0d0316cc.jpeg)


To make the above operation I used the following keywords: 
                  put- put keyword is used to insert and update the values of the restaurant in the table
                  scan- scan keyword is used to display the entities of the table we have created 
                  get- get keyword is used to read the values of the table 
                  delete- delete keyword is used to delete the value as well as the table

                 Pictorial representation of CRUD operation in restaurant database are attached in the Issues file(3 files) 
                 In conclusion, column-family databases are a powerful tool in the world of data management, and their popularity is only expected to grow as organizations continue to generate and collect more and more data.
