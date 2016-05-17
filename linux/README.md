## CH340G Driver for Linux

#### ChangeLog

1.0 - 1.1   modified to solve transmition between ch341 and ch341
1.1 - 1.2   Support high Linux kernel

#### Instructions

- Please run followed executable programs as root privilege
- Current Driver support versions of linux kernel range from 2.6.25 to 3.13.x
- Current Driver support 32bits and 64bits linux systems

###### Usage:

```

cd drivers-CH34G/linux

# Compile
make

# Load ch34x chips driver
make load

# unload ch34x chips driver
make unload
```
