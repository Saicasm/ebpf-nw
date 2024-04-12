# ebpf-nw
Tracing Network Calls with Go and eBPF

## Setup 
if you are using MacOS, we can use Lima to emulate Linux VM in Mac

### Install Lima 
``
brew install lima
``
We can use the ebpf-vm.yaml file which has the default configuration needed for running ebpf programs

Run the VM 

``limactl start ebpf-vm.yaml
``
`limactl shell ebpf-vm
`