# bike-stores-sqlite

A SQLite sample database of bike stores taken from [SQLServer Tutorial](https://www.sqlservertutorial.net/sql-server-sample-database/).

## How to run?

### Requirements

- SQLite3
- Cat

### Steps

1. Clone this repository

```bash
git clone https://github.com/asynched/bike-stores-sqlite.git
```

2. Run the script

```bash
cat sql/create.sql | sqlite3 bike-stores.db
cat sql/insert.sql | sqlite3 bike-stores.db
```

3. Enjoy!

## Schema

![Schema](https://www.sqlservertutorial.net/wp-content/uploads/SQL-Server-Sample-Database.png)