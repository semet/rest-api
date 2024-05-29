# Backend REST API

Boiler Plate for Nodejs Expressjs REST API

## Table of Contents

- [Technologies](#technologies)
- [Installation](#installation)
- [ESLint Config](#ESLint)
- [Contributing](#contributing)
- [License](#license)

## Technologies

This repo use the following main packages:

- **[pnpm](https://pnpm.io/)**
- **[Express.js](https://expressjs.com/)**
- **[Nodemon](https://nodemon.io/)**
- **[Cors](https://github.com/expressjs/cors)**
- **[Dotenv](https://github.com/motdotla/dotenv)**
- **[http-status-codes](https://github.com/prettymuchbryce/node-http-status)**
- **[Jsonwebtoken](https://github.com/auth0/node-jsonwebtoken)**
- **[Morgan](https://github.com/expressjs/morgan)**
- **[ESLint](https://eslint.org/)**
- **[TypeScript](https://www.typescriptlang.org/)**
- **[Prettier](https://prettier.io/)**
- **[Zod](https://github.com/colinhacks/zod)**

## ESLint

- **[@typescript-eslint/eslint-plugin](https://github.com/typescript-eslint/typescript-eslint/tree/main/packages/eslint-plugin)**
- **[@typescript-eslint/parser](https://github.com/typescript-eslint/typescript-eslint/tree/main/packages/parser)**
- **[eslint-config-prettier](https://github.com/prettier/eslint-config-prettier)**
- **[eslint-plugin-import](https://github.com/import-js/eslint-plugin-import)**
- **[eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier)**
- **[eslint-plugin-unicorn](https://github.com/sindresorhus/eslint-plugin-unicorn)**
- **[eslint-plugin-unused-imports](https://github.com/sweepline/eslint-plugin-unused-imports)**

## Installation

- clone this repo `https://github.com/semet/rest-api.git`
- Install the package by running `pnpm install`
- Create `env` file by running `cp .env.example .env`
- Adjust the database connection details in `.env` file
- configure `Prisma` by runnning `npxnpx prisma migrate dev --name init`. For more details about Prisma, checkout the **[documentation](https://www.prisma.io/docs/getting-started/setup-prisma/start-from-scratch/relational-databases/using-prisma-migrate-typescript-postgresql)**
- finally, run `pnpm run dev`. List available command can be found in `package.json` file.

## Contributing

Just submit your PR abnd I'll happily check it..

## License

MIT License.
