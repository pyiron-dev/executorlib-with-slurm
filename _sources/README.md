# executorlib with SLURM 
A number of examples for applying [executorlib](https://executorlib.readthedocs.io/) on [CMTI](https://docs.mpcdf.mpg.de/doc/computing/clusters/systems/Sustainable_Materials.html).

## Table of Contents
* [Getting Started](https://pyiron-dev.github.io/executorlib-with-slurm/slurm_demo_v1.html) - submit a serial function, an MPI-parallel function, and nested executors via SLURM
* [Submission Errors](https://pyiron-dev.github.io/executorlib-with-slurm/slurm_error_v1.html) - inspect `sbatch` submission failures raised through a `Future`
* [SLURM with Flux](https://pyiron-dev.github.io/executorlib-with-slurm/slurm_with_flux_v1.html) - run a nested [Flux](https://flux-framework.org) instance inside a SLURM allocation
* [SLURM with LAMMPS](https://pyiron-dev.github.io/executorlib-with-slurm/slurm_with_lammps_v1.html) - couple executorlib with [pylammpsmpi](https://pylammpsmpi.readthedocs.io) for interactive MPI-parallel LAMMPS
* [Nested SLURM Jobs](https://pyiron-dev.github.io/executorlib-with-slurm/slurm_with_nested_executor.html) - fan out many short tasks as job steps inside one SLURM allocation
