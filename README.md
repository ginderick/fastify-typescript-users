# fastify-typescript-users

This repository uses Fastify to create a CRUD application with Typescript for type safety.
The application includes user-related functionalities such as registration and authentication.

## Getting Started

1. Clone this repository to your local machine

```
https://github.com/ginderick/fastify-typescript-users.git
```

2. Navigate to directory

```
cd fastify-typescript-users
```

### Running Locally

1. Install the dependencies:

```
npm install
```

2. To build the project, run:

```
npm run build
```

3. Start the development server:

```
npm run start:dev
```

### Running Docker

To run the application with Docker, follow these steps:

1. To build the project, run:

```
docker build -t fastify-typescript-users .
```

2. Run the Docker container:

```
docker run -d -p 3002:3002 fastify-typescript-users
```

## License

This software is licensed under the [Apache 2 license](./LICENSE).

