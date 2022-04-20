# nodejs-express-mysql-crud
***nodejs-express-mysql CRUD API***

- Use *mysql* PHP Myadmin XAMPP create table books.
```
CREATE TABLE books(
    id int(11) NOT NULL PRIMARY KEY AUTO_INCREMENT,
    name varchar(100) NOT NULL,
    author varchar(100) NOT NULL,
    create_at timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
    update_at timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP
   ) ENGINE=INNODB DEFAULT CHARSET=utf8;
```
- Use *nodemon* for watching changing of project.
- Use *body-parser* for convert to json
- Use *express* for http request and call request and response
- Use test api by *postman* 
- This project create on *microsoft surface go 3*


<img width="846" alt="image" src="https://user-images.githubusercontent.com/89307294/164274178-38a9035e-03ff-4e13-89a4-dc2b7e0afc7c.png">

