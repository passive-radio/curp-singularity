# curp-singularity
The singularity definition file of curp container and the workflow to build and upload sif file to GHCR.

## How to pull and use pre-built image
```bash
singularity pull curp_singularity.sif oras://ghcr.io/passive-radio/curp-singularity:latest
singularity test curp_singularity.sif
```
