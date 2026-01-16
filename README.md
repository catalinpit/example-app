# example-app

This application uses a client - server architecture.

The client stack is:

- Vite
- React
- Tanstack Router
- Better-Auth
- Tanstack Query (upcoming)
- TailwindCSS (upcoming)
- Shadcn UI (upcoming)

The server stack is:

- Bun
- Hono
- PostgreSQL
- Prisma
- Better-Auth
- Zod (upcoming)

## How to run the application

### Run the server

1. Navigate to the server directory and run `bun install` to install the dependencies.
2. Create the `.env` file and add the environment variables from the `.env.example` file.

```
BETTER_AUTH_SECRET=
BETTER_AUTH_URL=

GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

DATABASE_URL=
```

3. Run `bun run dev` to start the development server.

### Run the client

1. Navigate to the client directory and run `bun install` to install the dependencies.
2. Run `bun run dev` to start the development server.
