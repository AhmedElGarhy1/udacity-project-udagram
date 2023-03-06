# Udagram app

Udagram app is a social media platform that you can:

- [x] Login
- [x] Register
- [x] Add posts

## Project setup

now lets see how can we setup this app to see it live

1. Clone this repo with command

```sh
git clone https://github.com/AhmedElGarhy1/udacity-project-udagram.git
cd udacity-project-udagram
```

2. Install Dependency, You will find Udagram folder this folder contains the frontend and backend code so

   - Go to udagram-api folder and run `npm install`
   - Go to udagram-frontend folder and run `npm install`

3. Add Environment Variables for udagram-api(backend) by going to udagram-api and create .env file and add the following

```sh
POSTGRES_HOST=
POSTGRES_USERNAME=
POSTGRES_DB=
POSTGRES_PASSWORD=
PORT=4000
AWS_REGION=
AWS_PROFILE=
AWS_BUCKET=
URL=
JWT_SECRET=
```

4. Run the app, now we will run the app by

   - Going to udagram-api folder and run `npm run tsc && npm run start`
   - Going to udagram-frontend folder and run `npm run start`

5. Open the app, go to `http://localhost:4200` Now it's running

## Exist application

[Udagram](http://udagram-frontend-site-995595.s3-website-us-east-1.amazonaws.com)
