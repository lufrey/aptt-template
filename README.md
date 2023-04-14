# Minimal Template for Astro, Prisma, Tailwind and TypeScript

## 🧑‍💻 Requirements

- [Node.js](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/)
- [sqlite](https://www.sqlite.org/index.html)
- [Docker](https://www.docker.com/)

## 🚀 Getting Started

1. Clone/Download repo

2. Install dependencies

```bash
npm install
```

3. Copy `.env.example` to `.env` and update the values (if required)

4. Start Dockered Postgres and wait for it to start

```bash
docker-compose up
# use "docker-compose up -d" to run in background
```

5. Push prisma schema to db

```bash
npx prisma db push
```

6. Start the dev server

```bash
npm run dev
```

## 🧙‍♂️ Tips

- use vscode to run eslint on save and disable normal formatting

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:3000`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm start`               | Serve your production build locally              |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npx prisma db push`      | Push prisma schema to db                         |
| `npx prisma studio`       | Open prisma studio  (web db viewer)              |
| `npx prisma migrate dev`  | Run prisma migrations (probably not neccessary)  |
| `npx prisma generate`     | Generate prisma client                           |
| `docker-compose up`       | Start Dockered Postgres and wait for it to start |
| `docker-compose down`     | Stop Dockered Postgres                           |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help`    | Get help using the Astro CLI                     |

