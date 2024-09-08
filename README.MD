# Playlist Transferer

## Description
Hobby project to transfer playlists between different music streaming services. 

The project is built using [NestJS](https://nestjs.com) for the backend and [React](https://reactjs.org) for the frontend. The project uses [Vite](https://vitejs.dev) as the frontend build tool.

## Requirements

| Node Version | NPM Version |
|--------------|-------------|
| 18.20.3      | 10.8.1      |


## Project Structure
The project is structured as follows:
```
project
│  README.md
|  package.json    
└───middleware
|   |   README.md
│   │   package.json
│   │   tsconfig.json
|   |   nest-cli.json
|   |   ...
│   └───src
|   |   |   main.ts
|   |   |   ...
|   └───tests
|       |   app.e2e-spec.ts
|       |   ...
└───ui
|   |   README.md
|   |   package.json
|   |   tsconfig.json
|   |   next.config.mjs
|   |   ...
|   └───src
|   |   └───app
|   |   |   |   page.tsx
|   |   |   |   layout.tsx
|   |   |   |   ...
|   |   |   ...
|   └───public
|       |   ...
└───...
```


## Usage
To use this project, follow these steps:

1. Clone the repository:
```bash
$ git clone https://github.com/your-username/playlist-transferer.git
```

2. Install dependencies:
```bash
$ cd playlist-transferer
$ npm install
```

3. Start the backend server:
```bash
$ npm run dev:mw
```

4. Start the frontend development server:
```bash
$ npm run dev:ui
```

5. Open your browser and navigate to `http://localhost:3000` to access the application.

## Building the Project
To build the project, run the following commands:

- Build both the middleware and the UI in a single command:
```bash
$ npm run build:all
```

- Build only the middleware:
```bash
$ npm run build:mw
```

- Build only the UI:
```bash
$ npm run build:ui
```

## Unit tests
```bash
$ npm run test
```

## Linting
```bash
$ npm run lint
```

## Resources
Here are some additional resources that may be helpful:

- [NestJS Documentation](https://docs.nestjs.com) - Official documentation for NestJS.
- [NestJS Discord Channel](https://discord.com/invite/G7Qnnhy) - Join the NestJS community on Discord for questions and support.
- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [React Documentation](https://reactjs.org/) - Official documentation for React.

## Support
Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).
