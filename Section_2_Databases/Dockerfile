CREATE DATABASE car_selling;

\c car_selling;

CREATE TABLE car(
	Serial_Number varchar(50) PRIMARY KEY,
	Manufacturer varchar(50) NOT NULL,
	Model_Name varchar(50) NOT NULL,
	Weight int NOT NULL,
	Price NUMERIC(18,2) NOT NULL
);
CREATE TABLE car_transaction (
	id serial PRIMARY KEY,
	Serial_Number varchar(50) UNIQUE references car(Serial_Number),
	Customer_Name varchar(50) NOT NULL,
	Customer_Phone varchar(20) NOT NULL,
	Salesperson varchar(50) NOT NULL,
	Date_Time timestamp NOT NULL
)




