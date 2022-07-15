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

### Bonus:

> By default `bun` creates react app with javascript but we can easily use typescript by changing the file extension from `.jsx` to `.tsx`
