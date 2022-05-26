## Global Mongo Database

This repo is a little project that create and start a `MongoDB` docker instance and also a `MongoExpress` globally on your machine. So, you don't need to create a new service for every project, you must only download this repo, start and be happy.


### Requirements 🧰 
- Docker
- Docker Compose

### How to start 🚀 

- Copy the files `.env.example`, paste on the same folder but remove the `.example`.
- Run the command `docker-compose up -d` and done!
  - This command will make these instances run on your machine forever. But you can turn it down running `docker-compose down` inside this folder.
  - If you want to see the logs in real time you can run `docker-compose up` without `-d`, this will make the instances but you will see the logs in real time in the console.

### How to connect

After making it start, the `MongoDB` should be available at `localhost:27017` and the `MongoExpress` at `localhost:8081`