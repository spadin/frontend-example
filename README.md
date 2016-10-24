### Before you begin

* Download the latest version of [Docker][1]

### Start app server

```
bin/start
```

### Start app server with HTTPS

```
HTTPS=true bin/start
```

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
