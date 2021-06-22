### NodeJS API Users CRUD

Tris is a sample of Users CRUD API build in NodeJS, MongoDB and Docker...

### API start

The application is built with Node.js and MongoDB as database with docker. To start the application you need `docker` and `docker-compose`.

The application will be avaible on *PORT 3000* by default.

Note: you should create `.env` file with the enviroment variables, our `docker-compose` file already has the `NODE_ENV` variable, on .env file you just have to create a `APP_NAME=crud_users` variable or copy `.env_copy` to `.env`

### Running the application in development mode

If you want to run in development mode, use this command

```shell
docker-compose -f docker-compose.yml up --build
```



### Running the tests

To run the tests using docker, use this command:

```shell
docker-compose -f docker-compose-test.yml up --build
```



### Running the application in production mode

If you want to run in production mode, use this command

```shell
docker-compose -f docker-compose-prod.yml up --build
```


And then you will see something like this on your terminal


```shell
Starting ukcrudusers__1 ...
Starting ukcrudusers__1 ... done
Starting ukcrudusers_app_1 ...
Starting ukcrudusers_app_1 ... done
```


## Contributing

Feel free to join us on the API



## Authors

* **Cicero Oliveira** -  [Galter](https://github.com/galter)
