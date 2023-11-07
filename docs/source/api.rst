API
====

.. autosummary::
   :toctree: generated

WaitIO Basic API	     
----------------

+----------------------------+------------------------------------+
| Functions                  | Description                        |
+----------------------------+------------------------------------+
| |waitio_isend|             | Non-Blocking Send                  |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_irecv|             | Non-Blocking Receive               |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_wait|              | Termination of WaitIO isend/irecv  |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_init|              | Initialization of WaitIO           |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_create_group|      | Create WaitIO communication group  |
|                            | Using selection function           |
+----------------------------+------------------------------------+
| |waitio_create_group_wank| | Create WaitIO communication group  |
|                            | Using arrays of MPI rank lists     |
+----------------------------+------------------------------------+
| |waitio_group_rank|        | Get WaitIO rank ID in the Group    |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_group_size|        | Get size of the WaitIO Group       |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_pb_rank|           | Get PB ID of the WaitIO Instance   |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_pb_size|           | Get PB size of the WaitIO Instance |
|                            |                                    |
+----------------------------+------------------------------------+

   
WaitIO MPI Conversion Library API	     
----------------------------------


+----------------------------+------------------------------------+
| Functions                  | Description                        |
+----------------------------+------------------------------------+
| |waitio_mpi_isend|         | WaitIO version:Non-Blocking Send   |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_mpi_irecv|         | WaitIO version:Non-Blocking receive|
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_mpi_bcast|         | WaitIO version: MPI_Bcast          |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_mpi_barrier|       | WaitIO version: MPI_Barrier        |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_mpi_reduce|        | WaitIO version: MPI_Reduce         |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_mpi_allredice|     | WaitIO version: MPI_Allreduce      |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_mpi_waitall|       | WaitIO version: MPI_Waitall        |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_create_universe|   | Create WaitIO version of COMM_WORLD|
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_mpi_gather|        | WaitIO version: MPI_Gather         |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_mpi_gatherv|       | WaitIO version: MPI_Gatherv        |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_mpi_algather|      | WaitIO version: MPI_Allgather      |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_mpi_scatter|       | WaitIO version: MPI_Scatter        |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_mpi_scatterv|      | WaitIO version: MPI_Scatterv       |
|                            |                                    |
+----------------------------+------------------------------------+
| |waitio_mpi_type_size|     | WaitIO version: MPI_Type_size      |
|                            |                                    |
+----------------------------+------------------------------------+
