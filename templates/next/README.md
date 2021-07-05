# How to use this template

```sh
npx copy-github-directory https://github.com/terra-money/wallet-provider/tree/main/templates/next your-app-name
cd your-app-name
yarn install
yarn run dev
```

Or if you want to start development based on yarn (2.0) workspaces,

```sh
npx copy-github-directory workspace your-workspace-name
cd your-workspace-name
npx copy-github-directory https://github.com/terra-money/wallet-provider/tree/main/templates/next your-app-name
yarn install
cd your-app-name
yarn run dev
```