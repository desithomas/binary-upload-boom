

# Binary Upload Boom

A social media app where people create an account, post photos with a title and a caption, and scroll a shared feed of everyone's posts. You can open any post to like it or leave a comment, and your profile page will collect everything you have posted. 

## Tech Stack 
* **Node.js:** Runs the server.
* **Express:** Handles the routes and requests.
* **EJS:** Builds the pages. Templates that turn data from the database into the HTML that you can see.
* **MongoDB w/ Mongoose:** The database that stores users, posts, and comments.
* **Passport:** Handles signup and login, and keeps each visitor signed in as they move between pages.
* **Multer:** Receives the photo file when a post is created.
* **Cloudinary:** Stores the uploaded photos online, so the database only has to keep each photo's address.

<img width="2269" height="925" alt="Screenshot 2026-11-16 at 12 38 26 AM" src="https://github.com/user-attachments/assets/35ac0f7e-b3a3-4574-bddb-1d26b976fce2" />

## View on website: 

 https://binaryuploadboom-xc8j.onrender.com

 ## Try it with a demo account: 
* **Email:** xqdrcxtngqkuefeohw@gonrr.net
* **Password:** password123

 ## How to Run Locally:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/desithomas/binary-upload-boom.git
    cd binary-upload-boom
    
2. **Install the dependencies:**
   ```bash
   npm install
   
3. **Create your .env file:**
   * Create a .env file inside of the config folder with these five keys. Please note that you will have to supply your own credentials when running locally. You will need a MongoDB connection string and a free Cloudinary account.
  ```bash
  - PORT = 9000 (the port being used for this application)
  - DB_STRING = `your database URI`
  - CLOUD_NAME = `your cloudinary cloud name`
  - API_KEY = `your cloudinary api key`
  - API_SECRET = `your cloudinary api secret`

```
4. **Start the application:**
   ```bash
   npm start
  
5. **Local browser view:**
* Go to http://localhost:9000 in your browser.

Viola! Join in and share your nails!
