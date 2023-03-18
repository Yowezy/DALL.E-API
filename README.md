# DALL.E-API - OpenAI image generation 🌁

### Getting Started:
* Open the Terminal.
* Create package.json file `npm init -y`
* Install packages `npm i express openai dotenv`
* Install  dev dependencie `npm i -D nodemon`
* Make this changes on package.json file
```bash 

"scripts": {
    "start": "node index",
    "dev": "nodemon index"
  },
```

* Create `.env` File

```bash 

PORT=5000 
OPENAI_API_KEY='PUT YOUR API KEY'
```
* Run `npm run dev` or `npm run start`.
