# webasm-hello
Hello World in WebAssembly

## Requirements
Install [Homebrew](https://brew.sh), then from the repository directory:
```shell
brew bundle --no-lock install
```

## Building
```shell
emcc hello.c -o hello.html
```

## Running
```shell
python -m http.server
```
Open [http://localhost:8000/hello.html](http://localhost:8000/hello.html)
