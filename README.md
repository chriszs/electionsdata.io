# 🗳️🌐 electionsdata.io

This is a full-stack React application built with Next.js, Prisma, and tRPC with WebSocket support.

## Features

- 🧙‍♂️ E2E type safety with [tRPC](https://trpc.io)
- ⚡ Full-stack React with Next.js
- ⚡ WebSockets / Subscription support
- ⚡ Database with Prisma
- 🔐 Authorization using [next-auth](https://next-auth.js.org/)
- ⚙️ VSCode extensions
- 🎨 ESLint + Prettier
- 💚 CI setup using GitHub Actions:
  - ✅ E2E testing with [Playwright](https://playwright.dev/)
  - ✅ Linting

## Getting Started

First, install the dependencies:

```sh
pnpm install
```

Then, start the development server:

```sh
pnpm dev
```

Open http://localhost:3000 with your browser to see the result.

## Scripts

```sh
pnpm build #Runs prisma generate, prisma migrate, and next build
pnpm db-nuke #Resets the local database
pnpm dev #Starts the Next.js and WebSocket server
pnpm dx #Starts the PostgreSQL database, runs migrations, seeds the database, and starts the Next.js server
pnpm test-dev #Runs end-to-end tests on the development server
pnpm test-start #Runs end-to-end tests on next start - build required before
pnpm test:unit #Runs normal Vitest unit tests
pnpm test:e2e #Runs end-to-end tests
```

## Deployment

(Optional) The project contains a `render.yaml` ["Blueprint"](https://render.com/docs/blueprint-spec) which makes the project deployable on [Render](https://render.com/).

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the terms of the GNU Affero General Public License.

Contact
