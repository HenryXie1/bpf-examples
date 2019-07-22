# bpf-examples
This repo is to learn and practise bpf related programs
# What is BPF
BPF is a mini-VM residing in the Linux kernel that runs BPF programs. Before running, BPF programs are loaded with the bpf() syscall and are validated for safety: checking for loops, code size, etc. BPF programs are attached to kernel objects and executed when events happen on those objects—for example, when a network interface emits a packet.

Further information on what BPF provides can be found through the following links:
- [A thorough introduction to eBPF](https://lwn.net/Articles/740157/)
- [How to Make Linux Microservice-Aware with Cilium and eBPF](https://www.infoq.com/presentations/linux-cilium-ebpf)
- [Dive into BPF: a list of reading materials](https://qmonnet.github.io/whirl-offload/2016/09/01/dive-into-bpf/)
- [BPF and XDP Reference Guide](https://docs.cilium.io/en/stable/bpf/)
