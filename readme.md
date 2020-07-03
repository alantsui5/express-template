
# Express JWT Template

## Origin
It is a express template forked from [jwt-express-typeorm](https://github.com/andregardi/jwt-express-typeorm) with medium article [TypeScript Rest API with Express.js, JWT, Authorization Roles and TypeORM](https://medium.com/javascript-in-plain-english/creating-a-rest-api-with-jwt-authentication-and-role-based-authorization-using-typescript-fbfa3cab22a4)

## Fixes and Enhancement
However, it fixed some bug that occur in that repository includes
* Fixed JWT Authentication Error by changing the middleware to respond to `authorization: Bearer <token>`
* Fixed TypeORM and TypeScript Version mismatch by adding `^` in front of version number and `npm upgrade`
It also add some functionalities for better portability
* Add postgreSQL configurations by `ormconfig.ts` 
* Change the ormconfig by detecting deployment environment
* Add dotenv
* Deployed to heroku

## API Documentations