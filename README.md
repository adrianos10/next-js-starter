This is a [Next.js](https://nextjs.org/) project starter bootstrapped using [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [`Prettier`](https://prettier.io/), [`ESlint`]('https://eslint.org/'), [`husky`]('https://github.com/typicode/husky') and [`lint-staged`]('https://github.com/okonet/lint-staged') pre-installed with my preferred and opinionated configurations, which helps to write consistent and clean code in the project. This project is also using `pnpm` as a package manager and `TypeScript`. I've also provided some basic project structure in `src`.

## Getting Started

First, run the development server:

```bash
pnpm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Additional scripts

- `pnpm run format` - run `Prettier` formatter on all files,
- `pnpm run check-types` - run `TypeScript` compiler on all files to validate them,
- `pnpm run lint` - run `ESlint` on all files with `TypeScript` compiler.
