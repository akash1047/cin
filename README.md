# cin

A C interpreter.

## dependencies

- zig compiler (currently version 0.11.0 is used)

You can download zig compiler from zig's official [download page](https://ziglang.org/download/).

- zls (optional)

zls is zig's language server

You can download zls from github [release page](https://github.com/zigtools/zls/releases).

⚠️ the zig compiler version and zls supported zig version should be same

## build

```
git clone https://github.com/akash1047/cin.git
cd cin
zig build
```

It will create cin executable in _zig-out/bin/cin_.

```
zig build run
```
It will build and run.
