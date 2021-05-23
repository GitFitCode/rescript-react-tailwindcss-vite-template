# rescript-react-tailwindcss-vite-template
A starter template for ReScript, React, TailwindCSS and Vite.

## Run Project

```sh
pnpm install
pnpm start
# in another tab
pnpm serve
```

When both processes are running, open a browser at http://localhost:3000.

## Build for Production

```sh
pnpm clean
pnpm build
pnpm build:production
```

## Replace template placeholders in
1. `bsconfig.json`, name
2. `index.html`, title
3. `package.json`, name
4. `README.md`


**NOTES**: 
1. This template uses `pnpm`; more info [here](https://pnpm.io/). It can be replaced by `npm` or `yarn`; make sure to delete the `pnpm-lock.yaml` file.
2. [commitlint/config-conventional](https://github.com/conventional-changelog/commitlint/tree/master/@commitlint/config-conventional) is being used for linting commit messages.