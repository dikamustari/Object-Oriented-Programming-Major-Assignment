# ReAndKhay Taylor – Tailoring Service Ordering System

A Java-based desktop application developed to fulfill the Final Project for the **Object-Oriented Programming (OOP)** course.

**ReAndKhay Taylor** is a simple application designed to manage tailoring service orders by connecting customers with tailors. The application provides features for managing orders, customer information, order progress status, and payment status.

## Main Features

### Customers
- Account registration and login.
- View profile information.
- Place tailoring service orders.
- View order lists and order statuses.
- View total prices and payment statuses.

### Tailors
- Log in as a tailor.
- View customer information and order lists.
- Modify order details and total prices.
- Update order progress statuses.
- Update payment statuses.
- Delete orders.

## Technologies Used

- **Java** – Main programming language.
- **Java Swing** – Application user interface development.
- **MySQL** – Database management and storage.
- **JDBC** – Connects the Java application to the MySQL database.
- **NetBeans IDE** – Application development environment.

## Project Structure

```text
Tugas-Besar-Pemrograman-Berorientasi-Objek/
│
├── Gambar/
│   ├── Logo.png
│   └── Project Documentation
│
├── src/
│   ├── InterfacePelanggan.java
│   ├── InterfacePenjahit.java
│   ├── Koneksi.java
│   ├── Login.java
│   ├── Pelanggan.java
│   ├── Penjahit.java
│   ├── Pengguna.java
│   ├── ModelPelanggan.java
│   ├── ModelPenjahit.java
│   └── ModelPesanan.java
│
└── README.md
```

## Object-Oriented Programming Concepts

During the development of this application, several fundamental Object-Oriented Programming (OOP) concepts were implemented, including:

- **Encapsulation:** Using `private` attributes and getter/setter methods in model classes.
- **Inheritance:** The `ModelPelanggan` and `ModelPenjahit` classes inherit from the abstract `Pengguna` class.
- **Abstraction:** Using the abstract `Pengguna` class and interfaces to define user behaviors.
- **Polymorphism:** Implementing the `getRole()` method in subclasses and implementing interfaces according to each user's specific requirements.

## Group 5 Members

| Name | Student ID |
|---|---|
| Muhammad Khayru Rizki | 11251033 |
| Andika Jusuf Jeremy Mustari | 11251063 |
| Remarsya Fredericha | 11281078 |

## Documentation

Project documentation and presentation materials can be accessed through the following Google Drive link:

[Google Drive – Final Project Documentation](https://drive.google.com/drive/folders/1mqX3H9HxpzuWcLoqZVszOkA9ThKgbXHw?usp=sharing)

---

*Object-Oriented Programming Final Project – Group 5.*
