# ldd_jail
Create chroot jail using ldd.

```
$ ./ldd_jail 
ldd_jail JAIL SRC [SRC1 SRC2 ...]
```

Copy all the `SRC` files/directories and their dependencies detected by ldd in `JAIL`.
If no `/` in `JAIL`, destiantion is `/tmp/JAIL`.

