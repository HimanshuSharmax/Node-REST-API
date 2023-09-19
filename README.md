# Node-REST-API
Creating a REST API using Node.js involves building a web server that can handle HTTP requests and respond with the appropriate data or actions based on those requests.

<h2> To Run this Project via NPM follow below: </h2>
Follow these instructions to set up and run the API locally.

<b>Prerequisites</b>
- Node.js and npm installed on your machine.
- A database system like MongoDB to store user data.

<b>Installation</b>
1. Clone the repository:

```
git clone https://github.com/HimanshuSharmax/Node-REST-API.git
```

2. Install dependencies:

```
npm install
```

3. Set up your environment variables. Create a .env file in the project root and provide the following variables:

```
PORT = 8000
DATABASE_URL = "mongodb://127.0.0.1:27017"
JWT_SECRET_KEY = "dhsjf3423jhsdf3423df"
```

4. Start the server:

```
npm run dev
```

<br>

There is a File "PostmanEndpoints" which has a Postman Collection File You can import this file in your Postman to test this API
