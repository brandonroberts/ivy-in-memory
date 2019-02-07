# Tour of Heroes

This repros a bug with Ivy/ngcc when using angular-in-memory-web-api with V7 vs V8.

### Instructions

Clone this repo

Install dependencies

```sh
yarn
```

Start app

```sh
yarn start
```

Note that app does not compile successfully.

Switch to v7 branch

```
git checkout v7
```

Install dependencies

```sh
yarn
```

Start app

```sh
yarn start
```

Browse to http://localhost:4200 and note that app runs successfully.
