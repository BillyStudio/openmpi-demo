# Open MPI Demos
Tested on Raspberry Pi cluster.

## Prerequisites
openmpi

mpi4py

### 说明
helloworld.cc   每个进程输出 helloworld

bcast.cc        由主进程接收控制台输入并广播给各子进程

ring.cc         由主进程接收输入，然后根据进程序号依次传播

find_pi.cc      指定进程个数为 n，计算pi

## Testing table

Slice = 1000000
| Node number | Elapsed time | error
| Cluster nodes = 2 | 161 | 2e-8
| Cluster nodes = 3 | 138 | 2e-8