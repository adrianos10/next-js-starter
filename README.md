This is a [Next.js](https://nextjs.org/) project starter bootstrapped using [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with pre-installed linters using my preferred and opinionated configuration, which helps to write consistent and clean code in the project.

## Features

- [`Prettier`](https://prettier.io/)
- [`ESlint`]('https://eslint.org/')
- [`husky`]('https://github.com/typicode/husky')
- [`lint-staged`]('https://github.com/okonet/lint-staged')
- `pnpm` as a package manager
- `TypeScript`
- initial project structure
- import inside `src` using `@/*` as well as items from `public` using `public/*`

### Additional scripts

- `pnpm run format` - run `Prettier` formatter on all files
- `pnpm run check-types` - run `TypeScript` compiler on all files to validate them
- `pnpm run lint` - run `ESlint` on all files with `TypeScript` compiler

## Getting Started

First, run the development server:

```bash
pnpm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
