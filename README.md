
## RcppHwloc: Binding for the Portable Hardware Locality package

### What is hwloc?

The [hwloc](https://www.open-mpi.org/projects/hwloc/) grew out of [Open
MPI](https://www.open-mpi.org/) and has a strong affinity (bad pun!) for high-performance computing
systems. It is described as

> The Portable Hardware Locality (hwloc) software package provides a portable
> abstraction (across OS, versions, architectures, ...) of the hierarchical
> topology of modern architectures, including NUMA memory nodes, sockets,
> shared caches, cores and simultaneous multithreading. It also gathers
> various system attributes such as cache and memory information as well as
> the locality of I/O devices such as network interfaces, InfiniBand HCAs or
> GPUs.

### What is this then?

A (currently very minimal) package which builds and lets us access `hwloc`
from R. Right now it is so 'alpha' that no data is returned: we currently
just run the `helloHwloc()` example as `hwlocExample()`.

### Installation

For now from source, on Unix only, and with [hwloc](https://www.open-mpi.org/projects/hwloc/)
present. The build relies on `pkg-config` to provide
[hwloc](https://www.open-mpi.org/projects/hwloc/) installation details.

### Author

[hwloc](https://www.open-mpi.org/projects/hwloc/) has grown out of libtopology and the [Portable
Linux Processor Affinity (PLPA)](https://www.open-mpi.org/projects/plpa/) project. 

This package was put together by Dirk Eddelbuettel

### License 

[hwloc](https://www.open-mpi.org/projects/hwloc/) is released under the [3-clause
BSD](https://opensource.org/licenses/BSD-3-Clause) like the rest of [Open
MPI](https://www.open-mpi.org/).

This package is released under the GPL (>= 2) like R itself and most of my packages.
