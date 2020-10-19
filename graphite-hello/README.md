# MPI "Hello world" codes on graphite

The [Graphite CPU cluster](ihttps://it.coecis.cornell.edu/researchit/graphitegpu/graphitecpu/) is the current home of the nodes that formerly made up the Totient cluster (used for the past couple iterations of CS5220), along with a number of GPU-accelerated machines used by various research groups in CS.  We have a priority access partition `cs5220` to the Totient nodes, as well as a `cs5220-gpu` partition for running on the GPU nodes.  This directory illustrates some simple MPI "hello world" codes on Graphite.  Note that you will need to load the Open MPI module (`module load openmpi-4.0.0`) before you can build the `mpi-hello.x` executable.