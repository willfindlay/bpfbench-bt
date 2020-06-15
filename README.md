# bpfbench-bt

A bpftrace implemenation of my bpfbench software.

Use this to benchmark system call runtime.

## Requirements

- bpftrace (https://github.com/iovisor/bpftrace)
- bcc (https://github.com/iovisor/bcc)
- libbpf (https://github.com/libbpf/libbpf)
- Linux >= 4.8
- (helpful but not required) BTF support in kernel

## Usage

- To run: `sudo ./bpfbench.bt`
- Press `ctrl-c` when finished.
