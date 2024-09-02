# Playlist Transferer

This project consists of two subfolders: `middleware` and `UI`.

## Middleware
The `middleware` folder contains the backend code for the Playlist Transferer application. It is built using NestJS and TypeScript.

## UI
The `UI` folder contains the frontend code for the Playlist Transferer application. It is built using React and TypeScript.

## Project setup
```bash
$ npm install
```

## Compile and run the project
Development mode should be run in **separate** terminals.
```bash
# development
$ npm run dev:mw
$ npm run dev:ui
```

Build the project. This will build both the middleware and the UI in a single command.
```bash
# Build
$ npm run build:all

# Build individual parts
## Middleware
$ npm run build:mw
## UI
$ npm run build:ui
```

Unit tests
```bash
# unit tests
$ npm run test
```

Linting
```bash
# Lint
$ npm run lint
```

## Resources
### NestJS
Check out a few resources that may come in handy when working with NestJS:
- Visit the [NestJS Documentation](https://docs.nestjs.com) to learn more about the framework.
- For questions and support, please visit [NestJS Discord channel](https://discord.com/invite/G7Qnnhy).

### React + Vite
Boostrapped using the React + TypeScript + Vite template.
This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.
Official documentation for the template can be found here:
- [Vite](https://v4.vitejs.dev/guide/) 
- [React](https://reactjs.org/)

## Support
Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).
