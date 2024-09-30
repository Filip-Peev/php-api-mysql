<br>

## Simple API responder with PHP and MySQL

<br><br>

Query for creating the database and add two entries:

```sh
CREATE DATABASE api_example;

USE api_example;

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    email VARCHAR(100)
);

INSERT INTO users (name, email) VALUES ('John Doe', 'john@example.com');
INSERT INTO users (name, email) VALUES ('Jane Smith', 'jane@example.com');
```

Rename config.sample.php to config.php and edit it with your data.
