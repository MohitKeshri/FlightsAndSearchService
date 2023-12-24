# Welcome to Flights Service 

## Project Setup
- clone the project on your local
- Execute `npm install ` on the same path of your root dir of the downloaded project 
- Create a `.env` file in the root directory and add the following environment variable
- `PORT=3000`
- Inside the `src/config` folder create a new file `cconfig.json` and then add the following piece of json
```
{
    "development": {
    "username": <YOUR_DB_LOGIN_NAME>,
    "password": <YOUR_DB_PASSWORD>,
    "database": "Flights_Search_DB_DEV",
    "host": "127.0.0.1",
    "dialect": "mysql"
  }
}
<<<<<<< HEAD

```
- Once you've added your db config as listed above, go to the src folder from your terminal and execute `npx sequelize db:create`
=======
>>>>>>> c2b74cd6d7e80658626503a8f7700bd6401cfa0d
