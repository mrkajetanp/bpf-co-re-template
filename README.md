# bpf-co-re-template

Template for a new BPF program.

Taken from: https://github.com/qais-yousef/bpf-hello-world

# Compile

```
make
```

### clean

```
make clean
```

# Run

From one terminal window:

```
sudo ./hello_world
```

From another terminal window:

```
sudo cat /sys/kernel/tracing/trace_pipe
```

`CTRL+c` to interrupt and exit program.
