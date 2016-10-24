### Before you begin

* Download the latest version of [Docker][1]

### Start app server

```
bin/start
```

Visit [http://localhost:3000][2]

### Start app server with HTTPS

```
HTTPS=true bin/start
```

Visit [https://localhost:3000][3]

### Run test runner and watch for changes

```
bin/test
```

### Run test runner once and quit

```
CI=true bin/test
```

### Make a production build

```
bin/build
```

[1]: https://www.docker.com/products/overview
[2]: http://localhost:3000
[3]: https://localhost:3000
