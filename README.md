# Medicare Hospital Patient Admission System

## Project Overview

The Medicare Hospital Patient Admission System is a Java console application developed to manage hospital patients and ward beds.

The system allows users to register, search, update and delete patients, as well as allocate and release hospital beds.

## Features

* Register patients
* Search for patients
* Update patient information
* Delete patients
* Allocate and release beds
* Display available and occupied beds
* Generate ward reports
* Sort patients by surname or Patient ID
* JUnit testing

## Technologies Used

* Java
* Maven
* JUnit 5
* NetBeans
* GitHub

## Project Structure

```text
HospitalSystem/
├── pom.xml
├── README.md
├── src/
│   ├── main/
│   │   └── java/
│   │       ├── HospitalSystem.java
│   │       ├── Patient.java
│   │       ├── Inpatient.java
│   │       ├── Bed.java
│   │       └── PatientCategory.java
│   └── test/
│       └── HospitalSystemTest.java
```

## Patient Categories

* Inpatient
* Outpatient
* Emergency

The ward contains 20 beds, numbered B01 to B20.

## How to Run

Open the project in NetBeans and run `HospitalSystem.java`.

To run the tests using Maven:

```bash
mvn test
```

## Student

**Student Number:** ST10485209

**Project:** Medicare Hospital Patient Admission System
