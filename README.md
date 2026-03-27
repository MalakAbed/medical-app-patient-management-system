# Medical App - Patient Management System

A web-based hospital patient management system developed as a university project.  
The application simulates a real-world workflow between **Doctors**, **Patients**, and **Pharmacists**.

## Project Overview

This system was built to help manage patient records and drug assignments inside a hospital environment.  
It provides different roles with different permissions:

- **Doctor**
  - Add patients
  - Update patient information
  - Delete patients
  - Assign drugs to patients
  - Remove assigned drugs
  - View all patients

- **Patient**
  - Log in
  - View assigned drugs
  - Update personal information
  - Log out

- **Pharmacist**
  - Add new drugs
  - Update drug information
  - Delete drugs
  - Log out

## Main Features

### Authentication
- Register doctors and pharmacists
- Secure login system
- Logout functionality
- Passwords stored with encryption
- Sessions and cookies support

### Patient Management
- Add patient
- Update patient data
- Delete patient
- View all patients assigned to the doctor

### Drug Management
- Add new drug
- Update drug details
- Delete drug
- Assign drug to patient
- Show assigned drugs
- Remove assigned drug from patient

## Technologies Used

- **PHP**
- **MySQL**
- **HTML**
- **CSS**
- **JavaScript**
- **Bootstrap**

## Database

- Database name: **hospital**

The database includes tables for:
- Doctors
- Patients
- Pharmacists
- Drugs
- Drug assignments

It also uses:
- Primary Keys
- Foreign Keys
- Unique Constraints

## Default Test Accounts

### Doctor
- Email: `doctor@gmail.com`
- Password: `123456`

### Patient
- Email: `patient@gmail.com`
- Password: `123456`

### Pharmacist
- Email: `pharm@gmail.com`
- Password: `123456`

## Folder Structure

```bash
FinalProject2/
│── asset/          # Images and static assets
│── css/            # Stylesheets
│── DB/             # Database connection/config files
│── html/           # HTML pages
│── php/            # Backend PHP logic (CRUD, authentication, etc.)
│── hospital.sql    # Database file
│── README.md       # Project documentation

```
## Installation Guide

1. Move the project folder into `htdocs` if you are using XAMPP.
2. Start **Apache** and **MySQL** from XAMPP.
3. Create a database named `hospital`.
4. Import the SQL database file into phpMyAdmin.
5. Update the database connection settings if needed.
6. Open the project in your browser using:

```bash
http://localhost/medical-app
