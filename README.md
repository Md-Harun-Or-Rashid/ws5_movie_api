# Movie API

The purpose of this project was to create a simple movie API application with Node.js using Express for server, Mongoose for MongoDB interaction, CORS for cross-origin requests. 


## Learning outcomes

- Creating Express server and connecting it to MongoDB
- Creating schema and model
- REST routes for movies for implementing CRUD operations. 


## 🛠️ Tools and Technologies Used 

- [Node.js](https://nodejs.org/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [MongoDB](https://www.mongodb.com/products/platform/atlas-database)
- [Postman](https://www.postman.com/downloads/) 
- Git (for cloning the repository)


##  How to run it locally

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [Visual Studio Code](https://code.visualstudio.com/)
- Git (for cloning the repository)

## MongoDB

- You need a MongoBD Atlas account and create a free cluster. Connection string (URI) is required and you need to use real connection string ( please check server.js file, line 6 and 7 for more details) to run this project successfully. 

## 🚀 Setup Instructions (Windows)

Open PowerShell or CMD and run the following commands:

```
# Navigate to your projects folder
cd ~/Documents/Projects
# Clone the repository
git clone https://github.com/Md-Harun-Or-Rashid/ws5_movie_api.git
# Change into the project directory
cd ws5_movie_api
# Install dependencies
npm install
# Start the server
npm start
```

## Run and test with Postman

- Make sure URL in the active tab http://localhost:3000/api/movies

```
Method: POST http://localhost:3000/api/movies 
Header: Content-Type: application/json
Body:{"title":"Test Movie","year":2024} 

# Click Send

```
