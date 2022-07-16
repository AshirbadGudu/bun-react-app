# React with Bun runtime

## Want to use bun for your next react projects?

---

### Install `bun`

First run the following command to check `bun` is installed or not

```sh
bun -v
```

If you don't have `bun` installed then run the following command to install `bun`

```sh
curl https://bun.sh/install | bash
```

### Create a react app

Now run the following command to create a react app

```sh
bun create react [your-app-name]
```

It will create a new directory with the name of your app. To start the app run the following command

```sh
cd your-app-name
bun dev
```

### Build production bundle for react app

By default `bun` does not ship with `react-scripts` so you need to install it first.

```sh
bun a react-scripts -d
```

Here we install it as a dev dependency.

Then run the following command to build the production bundle

```sh
bun react-scripts build
```

When you run the command above it will build the production bundle and it will be stored in the `build` directory.

### Adding `scripts` to your package.json

We can add the following scripts to our package.json file

```json
{
  "scripts": {
    "start": "bun dev",
    "build": "react-scripts build"
  }
}
```

Now we can run the following command to start the app

```sh
bun start
```

And we can run the following command to build the production bundle

```sh
bun run build
```

### Bonus:

> By default `bun` creates react app with javascript but we can easily use typescript by changing the file extension from `.jsx` to `.tsx`
