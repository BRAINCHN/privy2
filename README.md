# Privy Auth `create-next-app` Starter

This is a template for integrating [**Privy Auth**](https://www.privy.io/) into a [NextJS](https://nextjs.org/) project. Check out the deployed app [here](https://create-next-app.privy.io/)!

This demo uses NextJS's [Pages Router](). If you'd like to see an example using the [App Router](https://nextjs.org/docs/app), just change the branch of this repository to [`app-router`](https://github.com/privy-io/create-next-app/tree/app-router). 

## Setup


```sh
git clone https://github.com/BRAINCHN/privy2
```
```sh
npm i 
```
```sh
npm install @privy-io/react-auth@latest
```
enable localhost:3000 in the domain allow list
```sh
npm run dev
```
```sh
cp .env.example .env.local


```.env
# Add Privy App ID to .env.local
NEXT_PUBLIC_PRIVY_APP_ID=yourprivyappIDgoeshere
PRIVY_APP_SECRET=yourprivyappsecretkeygoeshere
```

```sh
npm run dev
```

<a href="http://localhost:3000">yourPRIVYapplocalhost</a>


## Check out:
- `pages/_app.tsx` for how to use the `PrivyProvider` and initialize it with your Privy App ID
- `pages/index.tsx` for how to use the `usePrivy` hook and implement a simple `login` button
- `pages/dashboard.tsx` for how to use the `usePrivy` hook, fields like `ready`, `authenticated`, and `user`, and methods like `linkWallet` and `logout`


**Check out [our docs](https://docs.privy.io/) for more guidance around using Privy in your app!**
