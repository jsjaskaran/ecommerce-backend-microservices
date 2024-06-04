# ecommerce-backend-microservices
Node.js based ecommerce backend using microservices.

## How to run on local
1. Create a .env file following the format specified in the `/auth/env.example`, `order/env.example` and `product/env.example` directories, following the format specified in each microservice directory
2. Run `npm install` in the `/auth`, `/product`, `/order` and `/api-gateway` directories
3. Run `npm start` on all four directories mentioned in the step above. Now you can test the APIs from localhost:3003