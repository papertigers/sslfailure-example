# Example of pkgsrc rust not using libssl in /opt/local/lib

```
root - rustdev ~/src/sslfailure-example (git:HEAD) # cargo run
   Compiling sslfailure-example v0.1.0 (/root/src/sslfailure-example)
    Finished dev [unoptimized + debuginfo] target(s) in 3.15s
     Running `target/debug/sslfailure-example`
ld.so.1: sslfailure-example: fatal: libssl.so.1.0.0: open failed: No such file or directory
Killed
```
