![](images/cover-photo-6.jpg)

### ABOUT PROJECT:

The aim of this project is to illustrate the use of **SQL** to answer some hypothetical questions about a DVD rental store named **Sakila**. The database is queried to acquire a better understanding of the customer base, rental time, payment revenue and comparisons of stores in terms of performance.

<br>

### DATASET OVERVIEW:

For the project, I have used [**Sakila**](https://dev.mysql.com/doc/sakila/en/) database, which was initially developed by Mike Hillyer, a former member of the MySQL AB documentation team. The database is an open source under the [**New BSD license**](*https://opensource.org/license/bsd-2-clause/).

The database presents a nicely normalised schema modelling a DVD rental store, featuring information such as films, actors, film-actor relationships, and a central inventory table that connects film, stores, and rentals.

The following diagram provides an overview of the database structure.

<figure>
    <img src="images/sakila ERD.png" alt="Entity Relationship Diagram">
    <figcaption>Entity Relationship Diagram</figcaption>    
</figure>

<br>

### DATA CHARACTERIZATION:

The database **Sakila** has 16 tables. Below are the table’s names with a brief description of them.

**actor:** contains actors data including first name and last name.

**address:** stores address data for staff and customers.

**category:** contains film’s categories data.

**city:** stores the city names.

**country:** stores the country names.

**customer:** stores customer’s data.

**film:** contains films data such as title, release year, length, rating, etc.

**film_actor:** contains the relationships between films and actors.

**film_category:** containing the relationships between films and categories.

**film_text:** contains film names and their description.

**inventory:** stores inventory data.

**language:** stores possible language values for films.

**payment:** stores customer’s payments.   

**rental:** stores rental data.

**staff:** stores staff data. 

**store:** contains the store data including manager staff and address. 

<br>

### DATA ANALYSIS:

Below is the working that I have done to answer each of the questions by running queries against **Sakila database** in **MySQL Workbench**.

<style type="text/css">
  .gist {width:100% !important;}
  .gist-file
  .gist-data {max-height: 500px;max-width: 100%;}
</style>

<script src="https://gist.github.com/nlaeeq/1fe3924373eb8c2cbb4a250e5a8f779b.js"></script>

<br>
