# h2-table1
CREATE TABLE Product
(
P_Id int NOT NULL PRIMARY KEY,
Name varchar(255) NOT NULL,
Category varchar(255),
Supplier varchar(255),
Price int,
stock int
)

#h2-table2
CREATE TABLE Category
(
C_Id int NOT NULL PRIMARY KEY,
Name varchar(255) NOT NULL,
Description varchar(255)
)

#h2-table3
CREATE TABLE Supplier
(
S_Id int NOT NULL PRIMARY KEY,
Name varchar(255) NOT NULL,
Address varchar(255)
)
