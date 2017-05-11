# MRuby Workshop

This repository contains a Docker image and an helper script to get quickly
started with the mruby exploitation workshop. To get started, simply run:

```
$ bin/mruby hello.rb
```

and you should see: `Hello world!` printed back. Congratulation, you just ran
the vulnerable mruby engine!

You can also use the `-v` flag to log every allocation made in the mruby heap.

The `gdb` command is available to start mruby through gdb:
`bin/mruby gdb hello.rb`.

Finally, the `mirb` command is available to spawn an interractive REPL within
mruby.
