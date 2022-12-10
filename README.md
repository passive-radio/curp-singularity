# curp-singularity
The singularity definition file of curp container and the workflow to build and upload sif file to GHCR.

## How to use pre-built image
```bash
singularity pull curp-singularity.sif oras://ghcr.io/singularityhub/curp-singularity:latest
singularity run curp-singulrity.sif
```