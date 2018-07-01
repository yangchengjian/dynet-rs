# dynet-rs: DyNet Rust Binding

* [DyNet website](http://dynet.io/)
* [DyNet GitHub page](https://github.com/clab/dynet/)
* [DyNet Documentation](http://dynet.readthedocs.io/)

# install

[DyNet build](http://dynet.readthedocs.io/en/latest/install.html#building)

```shell
export DYNET_INCLUDE_DIR=/path/to/dynet/build/dynet/libdynet.so(.dylib) 
export DYNET_LIBRARY_DIR=/path/to/dynet/ 
``` 
or 
```shell
cp -rf /path/to/dynet/build/dynet/libdynet.so(.dylib) /usr/local/lib 
cp -rf /path/to/dynet/dynet /usr/local/include/dynet
```

```shell
cargo build

```