# PromptPix
This project uses the DALL-E AI model to create images in real-time based on user prompts. The frontend is built with React, providing an easy-to-use interface, while the backend, powered by Node.JS, seamlessly integrates with the DALL-E model through the OpenAI API.

## Features

- **Real-time Image Generation:** Users can input prompts, and the application will generate unique images using the DALL-E model in real-time.
- **User-Friendly Interface:** The React-based frontend provides an intuitive and user-friendly interface for interacting with the image generation functionality.

## Technologies Used

- **React:** A JavaScript library for building user interfaces.
- **Node.js:** A JavaScript runtime for server-side development.
- **Express.js:** A web application framework for Node.js that simplifies the development of web applications.
- **OpenAI API:** The DALL-E model is integrated into the application using the OpenAI API.

## Installation Guide
### Client
In the client directory, you can run:
#### Install dependencies: 
```
npm install
```

#### To Start Server:
```
npm run dev
``` 

#### To Visit App:
```
localhost:5173
```

### Server
In the Server directory, you can run:
#### Install dependencies: 
```
npm install
```

#### To Start developement  Server:
```
npm run dev
``` 

## Using your credentials
You can use your own credentials by get the api in to the [OPENAI API DOCS](https://beta.openai.com/account/api-keys) setting the OPENAI_API_KEY` environment variables before running the server. For example, you could supply your own credentials by running the server like so:

```
OPENAI_API_KEY = my_api_key
```