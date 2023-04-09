# idea9101_A1

###### New user

As a new user, you can run everything (installing packages and run servers) by doing following the steps below:
```
// requires: 'concurrently' to run.
npm run install // Or run `npm install concurrently` or npm install -g concurrently`
npm run new-user
```

`npm run new-user` will do three things:
1. It will first run `npm run install-all` which will install all node packages dependencies within desktop and mqtt
2. Then it will run `npm run mqtt-all` which will connect phone (localhost:3000) and desktop (localhost:3300)

> However to run any of the following scripts: `npm run new-user`, `npm run install-all`, and `npm run mqtt-all` it requires the package `concurrently` to be installed either globally or within this repository 

---

### To run it manually or individually, you can open two terminal windows:

```console
npm install
npm start
```

open browser in `localhost:3000`
open browser in `localhost:3300`


---

### To run it manually or individually, you can open two terminal windows:

##### Terminal 1:
```console
cd phone_mqtt_sender
npm install
npm start
```

open browser in `localhost:3300`

enjoy :)
