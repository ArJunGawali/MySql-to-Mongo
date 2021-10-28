#### A Simple python Script to migrate data from MySQL to MongoDB

---

            Author: ArJun Gawali (arjungawali111@gmail.com)
            Date: 27 Oct, 2021
            Version: 1.0.1
            Purpose: Migrate Data from MySQL to Mongo

---

You can find the module [here](https://pypi.org/project/mysql-to-mongo/1.0.2/)
You can install it with following command :

<<<<<<< HEAD
<<<<<<< HEAD
> pip install mysql-to-mongo==1.0.2
=======
> pip install mysql-to-mongo==1.0.1
>>>>>>> 3c80abfce0d1d321ab2b7b1932f823ab0c215226
=======
> pip install mysql-to-mongo==1.0.2
>>>>>>> 973cdc313c0e67c63e979cd892ab14c655ca7111

## Functions :

1.  **migrate_all** : Migrate all tables from mysql to mongodb

    - **Parameters** :

      - **mysqldb_dict** : A Python dictionary of your mysql database details

                      Ex :
                          mysqldb_dict = {
                              "mysql_host" :"localhost",
                              "mysql_database" : "sample_database",
                              "mysql_user" : "root",
                              "mysql_password" : "*******",
                          }

      - **mongodb_host** : Your MongoDb hostname/Url
      - **mongodb_dbname** : Choose the name of Database in which the data has to migrate.

2.  **migrate_single** : Migrate specified table

    - **Parameters** :

      - **mysqldb_dict** : A Python dictionary of your mysql database details

                      Ex :
                          mysqldb_dict = {
                              "mysql_host" :"localhost",
                              "mysql_database" : "sample_database",
                              "mysql_user" : "root",
                              "mysql_password" : "*******",
                          }

      - **mongodb_host** : Your MongoDb hostname/Url
      - **mongodb_dbname** : Choose the name of Database in which the data has to migrate.
      - **table** : Specific table which has to migrate
