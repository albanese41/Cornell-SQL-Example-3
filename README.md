CREATE TABLE Guitars (

guitar_id INT NOT NULL,

model_name varchar(100) NOT NULL

CONSTRAINT PK_Guitars

PRIMARY KEY (guitar_id),

CONSTRAINT FK_Guitars_Models

FOREIGN KEY (model_name)

REFERENCES Models (model_name));
