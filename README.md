# Turborepo starter

This is an official starter Turborepo.

## Using this example

Run the following command:

```sh
npx create-turbo@latest
```

## What's inside?

This Turborepo includes the following packages/apps:

### Apps and Packages

- `docs`: a [Next.js](https://nextjs.org/) app
- `web`: another [Next.js](https://nextjs.org/) app
- `@repo/ui`: a stub React component library shared by both `web` and `docs` applications
- `@repo/eslint-config`: `eslint` configurations (includes `eslint-config-next` and `eslint-config-prettier`)
- `@repo/typescript-config`: `tsconfig.json`s used throughout the monorepo

Each package/app is 100% [TypeScript](https://www.typescriptlang.org/).

### Utilities

This Turborepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting

### Build

To build all apps and packages, run the following command:

```
cd my-turborepo
pnpm build
```

### Develop

To develop all apps and packages, run the following command:

```
cd my-turborepo
pnpm dev
```

### Remote Caching

Turborepo can use a technique known as [Remote Caching](https://turbo.build/repo/docs/core-concepts/remote-caching) to share cache artifacts across machines, enabling you to share build caches with your team and CI/CD pipelines.

By default, Turborepo will cache locally. To enable Remote Caching you will need an account with Vercel. If you don't have an account you can [create one](https://vercel.com/signup), then enter the following commands:

```
cd my-turborepo
npx turbo login
```

This will authenticate the Turborepo CLI with your [Vercel account](https://vercel.com/docs/concepts/personal-accounts/overview).

Next, you can link your Turborepo to your Remote Cache by running the following command from the root of your Turborepo:

```
npx turbo link
```

## Useful Links

Learn more about the power of Turborepo:

- [Tasks](https://turbo.build/repo/docs/core-concepts/monorepos/running-tasks)
- [Caching](https://turbo.build/repo/docs/core-concepts/caching)
- [Remote Caching](https://turbo.build/repo/docs/core-concepts/remote-caching)
- [Filtering](https://turbo.build/repo/docs/core-concepts/monorepos/filtering)
- [Configuration Options](https://turbo.build/repo/docs/reference/configuration)
- [CLI Usage](https://turbo.build/repo/docs/reference/command-line-reference)

## Como rodar o projeto na sua máquina

- Instale e configure o postgreSQL
- Volte a pasta raiz e rode o comando npm i no terminal
- Quando estiver o postgreSQL aberto e conectado ao banco rode os comandos abaixo estando na pasta backend

```
 npx prsima migrate dev no terminal
 npx prisma db seed no terminal
```

- Volte para a pasta raiz e rode o comando npm run dev no terminal

## Print WEB
![web](https://github.com/user-attachments/assets/9cde5244-6bce-40d8-9537-290d70366438)

## Print Mobile
![home_page_mobile](https://github.com/user-attachments/assets/5acce56a-2211-4177-8899-58a645dcecc4)

![agendamento_mobile_01](https://github.com/user-attachments/assets/3e574a3a-ae16-4b74-a740-61e87894dc1e)

![agendamento_mobile_02](https://github.com/user-attachments/assets/f348a3ef-3750-4a3d-89c0-96d3ed445c17)

![agendamento_mobile_03](https://github.com/user-attachments/assets/a94b30e2-8ef4-4783-8000-df3bf2787a69)
