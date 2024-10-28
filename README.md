# About The Project

CampMap is a website where users can create and review campgrounds. In order to review or create a campground, you must have an account. 


![CampMap](https://github.com/user-attachments/assets/5f75e509-011c-44ea-8377-0d068c1d7679)


This project was created using NodeJS, ExpressJS, MongoDB, Bootstrap, Passport.js, EJS, MapBox, and Cloudinary

Deployed on Heroku: https://agile-dawn-96924-c9a3d9b774a5.herokuapp.com/



<h1>Features</h1>
<ul>
  <li>Users can create user profile</li>
  <li>Users can create, edit, and remove campgrounds</li>
  <li>User can review campgrounds once, and edit or remove their review </li>

</ul>




<h1>Run it locally</h1>
<ol>
  <li>Install mongodb</li>
  <li>Create a cloudinary account to get an API key and secret code</li>

</ol>

```
git clone https://github.com/eulicescahuantzi/campmap.git
cd campmap
npm install
 ```
Create a .env file (or just export manually in the terminal) in the root of the project and add the following:

```
  CLOUDINARY_CLOUD_NAME=YOUR_CLOUD_NAME
  CLOUDINARY_API_KEY=YOUR_CLOUDINARY_API_KEY
  CLOUDINARY_SECRET=YOUR_CLOUDINARY_SECRET
  MAPBOX_TOKEN=YOUR_MAPBOX_TOKEN
  API_ENDPOINT=YOUR_API_ENDPOINT
  SESSION_SECRET=YOUR_SESSION_SECRET
  STORE_SECRET=YOUR_STORE_SECRET
  ```

  
  
Run `mongod` in another terminal and `node app.js` in the terminal with the project.

Then go to `localhost:3000`
