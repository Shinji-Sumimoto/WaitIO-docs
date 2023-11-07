WaitIO Basic API
===

.. autosummary::
   :toctree: generated

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
| |waitio_create_group_wank| | with selection function or arrays  |
|                            |  of MPI rank lists                 |
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



   
