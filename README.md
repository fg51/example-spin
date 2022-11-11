# example-spin
example spin

## setup
```sh
$ rustup target install wasm32-wasi
```

## build
```sh
$ spin new http-rust hello-rust
$ spin build
```

# run local
```sh
$ spin up  # run localhost
$ curl -i http://localhost:3000/hello
```

# with Fermyon
```sh
$ spin login
$ spin deploy
```
