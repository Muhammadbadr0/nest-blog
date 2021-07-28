### To run the project locally

1. clone the Repo
2. install dependencies
  ```sh
  npm i 
  ```
3. add .env with the following content:
```
HOST=localhost
PORT=5432
USERNAME=YOUR_DATABASE_USER_NAME
PASSWORD=YOUR_DATABASE_PASSWORD
DATABASE=YOUR_DATABASE_NAME
```
4. You are now able to run the project
  ```bash
  npm run start:dev
  ```