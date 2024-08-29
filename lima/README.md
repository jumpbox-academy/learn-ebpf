## How to use roughly command
```bash
limactl start --name=<name> ./<path>/<lima-config>.yaml 
#e.g. limactl start --name=ebpf-lima-vm ./ubuntu-lts-ebpf.yaml
limactl shell <name> 
#e.g. limactl shell ebpf-lima-vm
limactl list
```