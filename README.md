# Splash Images 

This is a photo gallary web app built with:

- docker 
- expressjs
- nunjucks template engine
- mongodb

### Run web app with docker 

Build the image and run it

`
$ docker-compose up
`

view website on `http://localhost`

### Run web app without docker 

Change the DATABASE_URL in `config/.env/` from `mongodb://db:27017/splash_images` to `mongodb://localhost/splash_images`  

Install all packages

`$ yarn install` 

Run the development server

`$ yarn dev` 