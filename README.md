<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Run in development mode

1. Clone the repository
2. Run `yarn install`
3. Install NestJS CLI globally `yarn global add @nestjs/cli`
4. Run Database `docker-compose up -d`
5. Clone the **.env.template** file and rename it to **.env**
6. Fill the **.env** file with the correct values
7. Run the application `yarn start:dev`
8. Rebuild the Database with the seed `http://localhost:3000/api/v2/seed`

# Production build

1. Create a **.env.prod** file with the correct values
2. Run the new docker image `yarn docker:build`

## Stack

- NestJS
- MongoDB
- Docker
