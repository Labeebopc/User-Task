

# Steps used to create the App
    1. Created a client side & server side folders to differentiate frontend and backend
    
    2. In server side (backend)-> 
                * Initialized a empty package.json file
                * Defined a PORT and connected with mongodb 27017
                * Installed packages like express, body-parser,cors, mongoose etc...
                * Created a userSchema, productSchema in Models folder
                * Defined functions for Signup, Login, Get user etc.. in controllers folder
                * Created userRoutes in routes folder
                * Implemented "bcrypt" for hashing user password
                * Created "jwt-web-token" for user
                * Checked Signup, Login, getUser by Id etc.. with postman
                
     3. In client side (frontend)->
                * Created a app using the command "npx-create-react-app ./"
                * Installed npm packages like axios, react-router-dom@6, bootstrap etc...
                * Created & designed components for Signup from, Login form using bootstrap
                * Created and designed Dashboard page, Error page 
                * Navigated using react-router
                * Signup and Login process completed (user can signup, then login to dashboard with credentials)

# Steps open/test the app
     1. Clone the repo.
     2. Make sure that you have installed node.
     3. within the server directory, run: npm i && npm start
     4. Navigate to the client directory and run: npm i && npm start
     5. Make sure both client and server are running.
     6. You can go to localhost:3000 from your browser and test the app.
                