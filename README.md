# postgresql-learning

### Installation

* Operate system: mac os x
* step 1:

  brew install postgres
  
* step 2:
  
  brew services start postgresql
 
* step 3:

  install [pgadmin client](https://www.postgresql.org/ftp/pgadmin/pgadmin3/v1.22.2/osx/) to manage db
  
### Mauals

https://www.postgresql.org/docs/9.6/static/index.html


### SQL syntax

* psql 
* createdb <db_name> -O <user_name>
* drop database <db_name>
* select * from pg_database;
* \du (query all the users database have)
* create user admin superuser password'123456';


  
