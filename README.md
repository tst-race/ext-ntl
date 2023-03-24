# NTL for RACE

This repo provides scripts to custom-build the
[NTL library](https://libntl.org) for RACE.

## License

The NTL library is licensed under LGPL v2.1+.

Only the build scripts in this repo are licensed under Apache 2.0.

## Dependencies

NTL has no dependencies on any custom-built libraries.

## How To Build

The [ext-builder](https://github.com/tst-race/ext-builder) image is used to
build NTL.

```
git clone https://github.com/tst-race/ext-builder.git
git clone https://github.com/tst-race/ext-ntl.git
./ext-builder/build.py \
    --target linux-x86_64 \
    ./ext-ntl
```

## Platforms

NTL is built for the following platforms:

* `linux-x86_64`
* `linux-arm64-v8a`

## How It Is Used

NTL is used by the <TO-BE-NAMED> plugin.
