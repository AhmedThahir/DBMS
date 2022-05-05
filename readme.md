---
title: Resume Management System
author: Anmol, Anurag, Bharathwaj, Ishan, Thahir
display: none
---

# Summary

|      ID       |         Name          |      Contribution       |
| :-----------: | :-------------------: | :---------------------: |
| 2020A7PS0080U |     Bharathwaj M      |         Queries         |
| 2020A7PS0107U | Ishan Anthony Menezes |     Queries, RA, RC     |
| 2020A7PS0128U |   Anurag Kumar Jha    |   Application Backend   |
| 2020A7PS0198U |     Ahmed Thahir      | Diagrams, Documentation |
| 2020A7PS0221U |  Anmol Deepak Kumar   |  Normalization, Report  |

## Title

Resume Management System

## Repository

The code and the documentation for this project is available on this [Github Repo](https://github.com/AhmedThahir/DBMS/).

## Concepts Used

- [x] ER Model
- [x] ER Diagram
- [x] Relational Model
- [x] Schema Diagram
- [x] Tuple Relational Calculus
- [x] Domain Relational Calculus
- [x] Normalization (1NF, 2NF, 3NF)
- [x] mySQL
- [x] GUI implementation

# Acknowledgement

Firstly, we would like to thank our family and friends for their constant support.

Secondly, we would like to express my sincere gratitude to all Department of Computer Science Professors for allowing us to apply my expertise in this assignment.

Our humble and noteworthy appreciation is due to Dr. Sapna Sadhwani, Dr. Tamizharasan Periyaswamy and Dr. Pramod Gaur for their guidance and assistance in the completion of this assignment.

We are also grateful to all the Department of Computer Science faculty for giving us the required knowledge to program using the mySQL querying language to implement our ideas for this project.

[toc]

# Introduction

## Historical Background

The job industry is booming with millions of job seakers each years. One of the most crucial elements which the job industry depends upon is the Database Management System, which is used to store, organize and retrieve the details of applicants. This requires a robust and efficient design of the Database to manage the data so that it can be accessed, modified, and stored quickly, with minimal storage space.

## Theory

The following is the theory relevant to this project.

### Database

A database is a collection of data.

### Relational Database

A database is a collection of data, in the form of rows and columns.

### Transaction

A transaction is an atomic unit of a database operation. Hundreds of transactions may take place concurrently at any instant. A transaction may be one of the CRUD operations

- Create
- Read
- Update (or Insert)
- Delete

### DBMS

A ‘DataBase Management System’ is a system for handling large amounts of data stored in one or more databases. It is also called as a ‘Transaction Processing System’.

### Querying Language

A querying language is a set of commands that facilitates database operations.

### Database Design

There are various ways of designing the structure(schema) of a database. The database must be designed well before inserting values, to ensure inconsistencies.

The logical schema depicts the structure of the database, showing the tables, columns, and relationships with other tables in the database, and is a direct mapping of the Entity-Relationship diagram. The physical schema is created by actually generating the tables, columns, and relationships in the DBMS, using a querying language.

Relational databases are ACID-compliant, but NoSQL aren’t

- Atomicity
  If any sub-steps of a transaction fails, the whole transaction must fail and the database must be in the same state as the original.
- Consistency
  Correct data is ensured through constraints
- Isolation
  Concurrent-Execution Safe
  Simultaneous transactions must be considered as multiple sequential transactions.
- Durability
  Committed transactions must be stored to a non-volatile memory, to prevent loss of data.

### ER Model

A database is modelled as

- entity set
- relationship sets

| Term                       | Meaning                                                  | Example                                         |
| -------------------------- | -------------------------------------------------------- | ----------------------------------------------- |
| Entity                     | unique object                                            | specific person, company                        |
| Entity Set                 | set of entities                                          |                                                 |
| Attributes                 | properties/features of an entity/relationship            | name, age                                       |
| Composite Attributes       | sub-attributes                                           | first name, last name                           |
| Relationship               | association among several entites                        |                                                 |
| Relationship Sets          | set of relationships                                     |                                                 |
| Degree of Relationship Set | no of entity sets that participate in a relationship set |                                                 |
| Mapping Cardinalities      | Type of mapping                                          | One-One<br/>One-Many<br/>Many-One<br/>Many-Many |

### ER Diagram

A diagrammatic representation of the entities and relations used.

| Shape            | Meaning                                                      |
| ---------------- | ------------------------------------------------------------ |
| Rectangle        | Entity Set                                                   |
| Double Rectangle | Weak Entity Set<br />entity without a primary key            |
| Diamond          | Relationship Set                                             |
| Double Diamond   | Weak Relationship Set<br />relation connecting a weak entity with something else |
| Ellipse          | Attribute                                                    |
| Dashed ellipse   | Derived attribute                                            |
| Double ellipse   | Multi-valued attribute                                       |
| Underline        | Primary Key Attribute                                        |
| Triangle         | ‘is-a’ relation                                              |
| Lines            | - Link attribute **to** entity set<br />- Link entity set **to** relationship set |
| $\to$            | **to** one                                                   |
| $-$              | **to** many                                                  |

### Relational Model

A database is a collection of relations, where each relations is a table.

### Schema Diagram

A diagrammatic representation of the relations used.

### Normalization

It is the process of structuring a database, usually a relational database, in accordance with a series of so-called normal forms in order to reduce data redundancy and improve data integrity.

|                               | 1NF  | 2NF  | 3NF  | BCNF | 4NF  | 5NF  |
| ----------------------------- | :--: | :--: | :--: | :--: | :--: | :--: |
| No Multi-Valued Attributes    |  ✅   |  ✅   |  ✅   |  ✅   |  ✅   |  ✅   |
| No Partial Dependency         |      |  ✅   |  ✅   |  ✅   |  ✅   |  ✅   |
| No Transitive Dependency      |      |      |  ✅   |  ✅   |  ✅   |  ✅   |
| LHS = Candidate/Super Key     |      |      |      |  ✅   |  ✅   |  ✅   |
| No Multi-Attribute Dependency |      |      |      |      |  ✅   |  ✅   |
| Lossless Decomposition        |      |      |      |      |      |  ✅   |

## Tools

| Tool      | Full Form                                   | Use                                                          |
| --------- | ------------------------------------------- | ------------------------------------------------------------ |
| HTML      | HyperText Markup Language                   | Layout of web pages                                          |
| CSS       | Cascading Style Sheets                      | Design of web pages                                          |
| Bootstrap |                                             | CSS framework for developing responsive web pages            |
| Php       | Hypertext Preprocessor                      | Backend<br />- Calling SQL<br />- Serving dynamic content to user |
| mySQL     | My Structured Query Language                | Structured Relational Database Querying Language             |
| Xampp     | cross-platform, Apache, MySQL, PHP and Perl | - Database manipulation<br />- Locally hosting the website   |

# Limitations

1. Dynamic Sites are not as performant as static sites
2. Filters are not dynamic currently (it is hard-coded)
3. There are a few hyperlinks which don’t work properly.
   For example, report button down as the site is not hosted on any server
4. The webpage is hosted locally at the moment. Needs to be run on the server
4. Relational database paradigm is not the most efficient to deal with a networking model, with unstructured data. A NoSQL paradigm could be used in the future to deal with large loads.

# ER Diagram

![](assets/er.svg)

# Normalization

In this project, we have only reached till 3NF. This is because BCNF and onwards may lead to lossy decomposition, with respect to the functional dependencies.

## Functional Dependencies

```
admin → id_admin, username, password
```

```
apply_job_post → id_apply, id_jobpost, id_company, id_user, status
```

```
cities → id,name,state_id
```

```
company → id_company, name, companyname, country, state, city, contactno, website, email, password, aboutme, logo, createdAt, active
```

```
countries → id, country_code, name, phonecode
```

```
job_post → id_jobpost, id_company, jobtitle, description, minimumsalary, maximumsalary, experience, qualification, createdat
```

```
mailbox → id_mailbox, id_fromuser, fromuser, id_touser, subject, message, createdAt
```

```
reply_mailbox → id_reply, id_mailbox, id_user, usertype, message, createdAt
```

```
states → id, name, country_id
```

```
users → id_user, firstname, lastname, email, password, address, city, state, contactno, qualification, stream, passingyear, dob, age, designation, resume, hash, active, aboutme, skills
```

## 1NF

```
R(id_admin, username, password, id_apply, id_jobpost, id_company, id_user, status, id, name, state_id, id_company, name, companyname, country, state, city, contactno, website, email, password, aboutme, logo, createdat, active, id, country_code, name, phonecode, id_jobpost, id_company, jobtitle, description, minimumsalary, maximumsalary, experience, qualification, createdat, id_mailbox, id_fromuser, fromuser, id_touser, subject, message, createdAt, id_reply, id_mailbox, id_user, usertype, message, createdAt, id, name, country_id, id_user, firstname, lastname, email, password, address, city, state, contactno, qualification, stream, passingyear, dob, age, designation, resume, hash, active, aboutme, skills)
```

## 3NF

```
R1(id_admin, username, password)
```

```
R2(id_apply, id_jobpost, id_company, id_user,status)
```

```
R3(id, name, state_id)
```

```
R4(id_company, name, companyname, country, state, city, contactno, website, email, password, aboutme, logo, createdat, active)
```

```
R5(id, country_code, name, phonecode)
```

```
R6(id_jobpost, id_company, jobtitle, description, minimumsalary, maximumsalary, experience, qualification, createdat)
```

```
R7(id_mailbox, id_fromuser, fromuser, id_touser, subject, message, createdat)
```

```
R8(id_reply, id _mailbox, id_user, usertype, message, createdAt)
```

```
R9(id, name, country_id)
```

```
R10(id_user, firstname, lastname, email, password, address, city, state, contactno, qualification, stream, passingyear, dob, age, designation, resume, hash, active, aboutme, skills)
```

# Schema Diagram

![](assets/schema.svg)

# Design

|                Table                | Details                                                      |
| :---------------------------------: | ------------------------------------------------------------ |
|               `admin`               | - admin username<br />- admin password<br />- Holds details about the active companies registered, candidates registered, total job posts and total applications.<br />- Permissions to remove any user or candidate<br />- Any company before being able to recruit and post jobs must be verified by the admin. |
|          `apply_job_post`           | Id_apply: acts as primary key with auto increment on<br/>Id_job_post: acts as the id for the GET method of php for opening the specific webpage having job<br/>decription<br/>Id company/user : id of user or the company<br/>Status: status of the job post depending on the admin. A job post is published only after validation by the admin. |
| `City`<br />`state`<br /> `country` | - Large database of the cities, states and tables connected together by id of state and<br/>countries.<br />- Created separately since while creating forms the option to select country comes first, then the state and then the city.<br />- None of these are compulsory so the 3 tables are kept separately so that if a user only provides country or country-state it works as well. |
|              `Company`              | - Consists of all the details of the country. The logo is stored as image format in the uploads folder.<br />- Any company before being to operate must be able to be verified from the admin when their active column changes from 2 to 1. |
|               `Users`               | - Similar to the companies these include all the users looking for jobs.<br />- The resume is stored as pdf(size smaller than 5 mb) and is stored in the uploads folder.<br />- The passwords are stored after applying decoding so that even the admin or the superuser can’t access the password. |
|       `Mailbox`<br />`Reply`        | - Inbuilt mailing technique b/w the users and the companies, the user can have converstion with the employee who have interest in their application.<br />- The design is similar to Gmail<br />- all the information is stored in the sql file i.e. the message, from, to and the date. |
# Implementation

## Connections

Let’s see how a connection with mysql is made.

In all the php pages which require access to database we include the db.php. db.php is a php which is used for establishing the sql connection. Rather than writing all of that separately in all the php files, we have created one db file and included this in all which we require.

For running any SQL query we just write the query similar to that in SQL and then run it using the
connection established.

```php
$result = $conn->query($sql);
```

## PHP File Roles

|                      PHP File                       | Role                                                         |
| :-------------------------------------------------: | ------------------------------------------------------------ |
|                       `index`                       | The main php file that opens up at the start. Contains link to other pages like login and register and also the admin login. Shows 4(using sql limit) recently available job offers at the centre. |
|                       `jobs`                        | Contains the job offers 4 per page(again by using limit 4, for this code is written in `jobpagination.php`).<br />The filters applied are using the help of search.php which applies the filters of city and experience.<br />Currently the cities are navi-mumbai and Bengaluru but more can be added as required.<br />Clicking on any of these open the `view-job-post.php` |
|                   `view-job-post`                   | - also has an id at the end of url required to identified which job post page to open as all have the same format.<br />- This id is sent using the GET method of php. |
|        `login`<br />`signup`<br />`register`        | - These are the pages which open the login and signup pages.<br />- The details of username and password are checked using the `checklogin.php` and `checkcompanylogin.php`.<br />- All the login and register pages have the standard php code for validation of phone number, email id, pdf size etc.<br />- These can be seen at W3Schools itself. |
| Folders of<br /> `user`<br />`company`<br />`admin` | - These contain the php pages to be loaded when the corresponding people are logged in.<br />- This is known by using the session global variable of php to know which of these is set.<br />- The php files within are pretty simple to those mentioned above with the exception that these are a little more specified for the particular kind of user. |

## Queries

### `addcompany.php`

Check if the email already exists so that every new company created has a new email.

```php
$sql = "SELECT email FROM company WHERE email='$email'";
```

Inserting new data retrieved from the form into the company table

```php
$sql = "INSERT INTO company(name, companyname, country, state, city,
contactno, website, email, password, aboutme, logo) VALUES ('$name',
'$companyname', '$country', '$state', '$city', '$contactno', '$website',
'$email', '$password', '$aboutme', '$file')";
```

### `adduser.php`

Similar to the above to check if the file already exists.

```mysql
$sql = "SELECT email FROM users WHERE email='$email'";
```

Inserting data into the user table

```php
$sql = "INSERT INTO users(firstname, lastname, email, password, address, city, state, contactno, qualification, stream, passingyear, dob, age, designation, resume, hash, aboutme, skills) VALUES ('$firstname', '$lastname', '$email', '$password', '$address', '$city', '$state', '$contactno', '$qualification', '$stream', '$passingyear', '$dob', '$age', '$designation', '$file', '$hash', '$aboutme', '$skills')";
```

### `apply.php`

This is not a file directly associated with the front end but called for processing of another file.

Retrieve all the data from the job_post table where id is taken from the GET function of php.

```php
$sql = "SELECT * FROM job_post WHERE id_jobpost='$_GET[id]'";
```

Check if the user has applied to the job post or not.

```php
$sql1 = "SELECT * FROM apply_job_post WHERE id_user='$_SESSION[id_user]' AND
id_jobpost='$row[id_jobpost]'";
```

Whenever a user applies for a job the details need to be added to the apply_job_post table.

```php
$sql = "INSERT INTO apply_job_post(id_jobpost, id_company, id_user) VALUES ('$_GET[id]', '$id_company', '$_SESSION[id_user]')";
```

### `checkcompanylogin.php`

Check if the login is correct or not.

```php
$sql = "SELECT id_company, companyname, email, active FROM company WHERE email='$email' AND password='$password'";
```

### `checklogin.php`

Check if the login is correct or not.

```php
$sql = "SELECT id_company, companyname, email, active FROM company WHERE email='$email' AND password='$password'";
```

### `city.php`

Select the cities from states. Similar is with the case in `state.php` in a layer by layer like fashion.

```php
$sql = "SELECT * FROM cities WHERE state_id='$_POST[id]'";
```

### `index.php`

Select 4 most recent job offers to display at the main screen.

```php
$sql = "SELECT * FROM job_post Order By createdat Limit 4";
```

Other sql commands are the simple select commands to get the count of various elements.

### `jobpagination.php`

Choosing 4 job posts at a time.

```php
$sql = "SELECT * FROM job_post LIMIT $start_from, $limit";
```

### `search.php`

Search specific company on the basis of inputted name.

```php
$sql = "SELECT * FROM job_post WHERE jobtitle LIKE '%$search%' LIMIT $start_from, $limit";
```

### `view-job-post.php`

Select details of the specific company on on the page on the basis of id sent by GET method of php.

```php
$sql = "SELECT * FROM job_post INNER JOIN company ON job_post.id_company=company.id_company WHERE id_jobpost='$_GET[id]'";
```

Similar queries in the user, company and admin php files for the specific user types.

# Screenshots

![1_Index_Page](assets/Screenshots/1_Index_Page.png)

![2_Index_Page](assets/Screenshots/2_Index_Page.png)

![3_Login_Page_Users_Companies](assets/Screenshots/3_Login_Page_Users_Companies.png)

![4_Signin_page](assets/Screenshots/4_Signin_page.png)

![5_Users_Index_Page](assets/Screenshots/5_Users_Index_Page.png)

![6_Mail_Box_Page](assets/Screenshots/6_Mail_Box_Page.png)

![7_User_Registration_Page](assets/Screenshots/7_User_Registration_Page.png)

![8_Company_Register_Page](assets/Screenshots/8_Company_Register_Page.png)

![9_Company_Dashboard](assets/Screenshots/9_Company_Dashboard.png)

![10_Createing_Jobpost_page](assets/Screenshots/10_Createing_Jobpost_page.png)

![11_Resume_of_applicants_page](assets/Screenshots/11_Resume_of_applicants_page.png)

![12_Admin_dashboard](assets/Screenshots/12_Admin_dashboard.png)

![13_Active_Jobs_admin_panel](assets/Screenshots/13_Active_Jobs_admin_panel.png)

![14_Company_List_Admin_Panel](assets/Screenshots/14_Company_List_Admin_Panel.png)

# Usage

The following are the steps to run this project yourself

1. Clone the [Github Repo](https://github.com/AhmedThahir/DBMS/)

2. Import the `git_repos_jobportal.sql` in the xampp mysql database

3. Paste the `Job_Portal` folder into `htdocs` folder. (found in WAMPP, XAMMP, MAMPP installation folder)

4. Start the Apache and Mysql services from the MAMPP server (mac), XAMPP server (windows).

5. Run the following commands in the terminal

   ```bash
   cd Job-Portal
   open db.php
   ```

6. Check that credentials for username and password are matching according to your system.

7. Go to `localhost` and job posts will now be visible.

8. Login with any of the below default accounts

|   Type    | Username | Password |
| :-------: | :------: | :------: |
|   Admin   |  admin   |  12345   |
| Candidate | m@m.com  |    m     |
|  Company  | m@m.com  |    m     |

