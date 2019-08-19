# Groups


## Main
### DB
| CMD                                        | DESC                      |
| :----------------------------------------- | :------------------------ |
| $ `psql -h localhost -p8763 -U jimzy  db5` | log into db5 at port 8763 |
| `\l`                                       | list databases            |
| `\c dbName`                                | change db to dbName       |
## _Docker_
| Command                                          | Description                          |
| :----------------------------------------------- | :----------------------------------- |
| $ `docker-compose up`                            | run container                        |
| $ `docker-compose down (-v)`                     | shut down container                  |
| $ `docker ps`                                    |                                      |
| $ `docker images`                                |
| $ `docker system prune -a`                       |
| gets rid of all images/containers not being used |
| $ `lsof -t -i:5432`                              | list open files on port 5432         |
| $ `lisof -P`                                     | list open files: ports               |
| $ `kill $(lsof -t -i:5432)`                      | ... kill the process using port 5432 |
| $ `curl localhost:8080/api/users`                | grab the data                        |
### Virtual Environment
### Python
  Make file executable
  code to help file know what version of Python

### Installs
 - postgress
   - $ brew install postgresql
 -