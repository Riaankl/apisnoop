# apisnoop.cncf.io

This is the APISnoop web app, displayed at [apisnoop.cncf.io](https://apisnoop.cncf.io)

It pulls in json generated by our [Snoop Postgres DB](https://github.com/ii/snoop) to display the testing coverage for kubernetes.

The app is written in [Svelte](https://svelte.dev), using [Sapper](https://sapper.svelte.dev) to help build the routes.

## Installing for local development

Clone down and enter the repo:

```shell
git clone https://github.com/zachmandeville/snoopApp.git
cd snoopApp
```

install dependencies and start up dev server

```shell
npm install
npm run dev
```

The site will abe visitable at localhost:3000

