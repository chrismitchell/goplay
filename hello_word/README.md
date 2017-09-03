Go by Example: Hello World

Our first program will print the classic “hello world” message. Here’s the full source code.

To run the program, put the code in hello-world.go and use go run.

```shell
$ go run hello-world.go
hello world
```

Sometimes we’ll want to build our programs into binaries. We can do this using go build.

```shell
$ go build hello-world.go
$ ls
hello-world	hello-world.go
```

We can then execute the built binary directly.

```shell
$ ./hello-world
hello world
```
