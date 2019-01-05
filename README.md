[![Licence](https://img.shields.io/hexpm/l/plug.svg)](https://github.com/gsharma/supervisor/blob/master/LICENSE)

# Supervisor

## Background Motivation
The idea behind this is to create a supervisor that can manage a heirarchical supervision tree of child processes that each expose some basic lifecycle hooks to:
1. start the process
2. gracefully shutdown the process (via for example, handling the SIGTERM signal)

The dependency tree between processes is best expressed declaratively as a DAG with the Supervisor orchestrating the process creation and destruction as well as monitoring for their liveness.


<this is a work in progress>
