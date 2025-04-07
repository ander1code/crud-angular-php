# CRUD-Angular-PHP  

![Programming Language](https://img.shields.io/badge/PHP-lavender?style=flat&logo=php&logoColor=white) ![Programming Language](https://img.shields.io/badge/JavaScript-yellow?style=flat&logo=javascript&logoColor=white)  
![Framework](https://img.shields.io/badge/Angular-darkred?style=flat&logo=angular&logoColor=white) ![Framework](https://img.shields.io/badge/Express-gray?style=flat&logo=express&logoColor=white)  
![Database](https://img.shields.io/badge/SQLite-blue?logo=sqlite&logoColor=white) ![Database](https://img.shields.io/badge/PostgreSQL-blue?logo=postgresql&logoColor=white) ![PDO](https://img.shields.io/badge/PDO-777BB4?logo=php&logoColor=white)   
![Platform: Web](https://img.shields.io/badge/Platform-Web-blue?logo=google-chrome)
![Last Commit](https://img.shields.io/github/last-commit/ander1code/crud-angular-php?color=yellow&logo=github) ![Size](https://img.shields.io/github/repo-size/ander1code/crud-angular-php?color=blue&logo=files) ![License](https://img.shields.io/github/license/ander1code/crud-angular-php?color=black&logo=open-source-initiative)

## 1. Description
A **web-based CRUD application** developed with **Angular 7** on the client side and **PHP (API)** with an **SQLite3 database** on the server side, incorporating robust security features.

## 2. Client Side (crud-angular-php)

### 2.1. Overview
The **client-side application** is built using Angular, designed to consume the PHP-based API efficiently.

### 2.2. Tools and Dependencies
#### Additional dependencies specified in `package.json`:
- **@angular/cli:** ^7.3.7
- **ngx-pagination:** ^3.2.1
- **ngx-bootstrap:** ^3.2.0
- **http-proxy-middleware:** ^0.19.1
- **express:** ^4.16.4

## 3. Server Side (php-crud-api)

### 3.1. Overview
The **server-side API** is developed using PHP. It facilitates database operations such as connection, creation, editing, and searching of records.

### 3.2. CRUD Features
- **Login System:** Implemented with sessions secured using MD5 encryption.
- **Token-Based Security:** Token generation and validation using SHA512.
- **Search Functionality:** Search by name and code.

### 3.3. Security Features
The application implements the following security measures:
- **SQL Injection Protection**
- **PHP Injection Protection**
- **Cross-Site Scripting (XSS) Protection**
- **CSRF Protection**

### 3.4. Tools and Technologies
- **Programming Language:** PHP 7.3.3
- **Database Options:** SQLite3 and PostgreSQL
- **Database Connection:** PDO (PHP Data Objects)

---

