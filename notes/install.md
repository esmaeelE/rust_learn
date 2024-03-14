# Install and Run first program

On Debian 12

## Install required applications
```
sudo apt install rust-all
```

Check
```
$ cargo --version 
cargo 1.73.0 (9c4383fb5 2023-08-26)
$ rustc --version
rustc 1.73.0 (cc66ad468 2023-10-03)
```

## Create first hello world

```
cargo new hello
```
## Run hello
```
cd hello
cargo run 
```

### Compile and run
```
cd src
rustc main.rs
./main
```


