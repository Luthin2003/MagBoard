# Magazine Web Application

## Overview
This project is a magazine web application built using Node.js, Express.js, and MongoDB. It provides a platform for users to create, read, update, and delete articles. Each article consists of a title, summary, content, and cover image. Users can register, log in, and manage their articles, making it suitable for magazine-style websites or blogs. The application also includes features such as user authentication, authorization, and file uploads for article cover images.

## Features
- User registration and authentication using JSON Web Tokens (JWT)
- CRUD operations for articles (Create, Read, Update, Delete)
- File uploads for article cover images
- User authorization to ensure only the article's author can edit or delete it
- Secure password hashing using bcrypt.js
- CORS (Cross-Origin Resource Sharing) support for handling cross-origin requests
- Error handling and logging for better debugging

## Installation

1. Clone the repository to your local machine:


```bash
git clone https://github.com/Luthin2003/chatapp.git

```
2. Install dependencies
```bash
cd api
npm i

cd client
npm i
```

3. Run

inside backend folder :
```bash
npm run dev
```

inside client folder : 

```bash
npm start
```

## Usage
- Register a new user using the `/register` endpoint
- Log in with your credentials using the `/login` endpoint to obtain an access token
- Use the access token for authenticated requests by including it in the `Authorization` header as a Bearer token
- Create, read, update, and delete articles using the corresponding endpoints
- Log out using the `/logout` endpoint to invalidate the access token
- Access the application frontend to interact with the API endpoints

## API Endpoints
- `POST /register`: Register a new user
- `POST /login`: Log in and obtain an access token
- `POST /logout`: Log out and invalidate the access token
- `POST /post`: Create a new article
- `GET /post`: Get all articles
- `GET /post/:id`: Get a specific article by ID
- `PUT /post/:id`: Update an existing article
- `DELETE /post/:id`: Delete an article by ID

## Contributing
Contributions are welcome! Feel free to open issues or pull requests for any improvements or additional features.

## Screenshots
![Screenshot 2024-02-16 161910](https://github.com/Luthin2003/MagBoard/assets/101446790/f05a38cf-fbbb-46a6-bd6e-a70a2712b87f)

![Screenshot 2024-02-16 162333](https://github.com/Luthin2003/MagBoard/assets/101446790/37a80ca8-0bf6-4436-be2f-c44bf7d4ac1e)

![Screenshot 2024-02-16 161516](https://github.com/Luthin2003/MagBoard/assets/101446790/339f0abd-405f-421c-8558-ccffb3c1a3c2)
