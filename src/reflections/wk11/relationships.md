# Relationships

## What is the difference between a primary key and a foreign key

Primary Keys are used as unique information to differentiate between data on a table.
Foreign Keys are used to reference other keys on different tables.

## What is an Alias?

An alias is used to abbreviate table names.

## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctor_patients (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)

SELECT * FROM doctor_patients dp
JOIN doctors d ON d.id = dp.doctorId
JOIN patients p ON p.id = dp.patientId

https://github.com/Jeremy-Fowler/Contractr