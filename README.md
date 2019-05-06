# Freshiez Backend

This application is written with Node JS and Express 4.16.

## Run and Deployment

1. Run `npm install`.
2. Rename `config.json.exampele` to `config.json` and replace fields with your DB information.
<!-- 3. Rename `privatekeys.js.example` to `privatekeys.js` and replace fields with a ramdon string for JWT secret and your sms panel API key. -->
4. Execute `npm run apidoc` to create API documents. (You can access API documents on `http://localhost:3000/apidoc`)
5. Execute `npm run migrate` to create database tables and relations.
6. Execute `npm run seeders` to insert initial data into DB.
    <!-- * After execution of this command an Admin user creates with `phoneNumber: 09121234567` and `password: 123456`,
    you can use this admin to create other admins.
    * <span style="color: red;">NOTE THAT AS SOON AS POSSIBLE CHANGE THE PHONENUMBER AND PASSWORD OF GENERATED ADMIN</span> -->

7. Run `npm start` and your RESTful APIs is ready.
