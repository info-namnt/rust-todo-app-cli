# rust-todo-app-cli

```shell
cargo run
cargo run add "do sth"
```

## cross_compiling

```
rustup target add x86_64-pc-windows-gnu
```

Add the file config into new folder .cargo 
```
[target.i686-pc-windows-gnu]
linker = "i686-w64-mingw32-gcc"

[target.x86_64-pc-windows-gnu]
linker = "x86_64-w64-mingw32-gcc"
```

install the package `mingw-w64`