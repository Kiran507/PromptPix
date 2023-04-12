# PromptPix
This project uses the DALL-E AI model to create images in real-time based on user prompts. The frontend is built with React, providing an easy-to-use interface, while the backend, powered by Node.JS, seamlessly integrates with the DALL-E model through the OpenAI API.

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