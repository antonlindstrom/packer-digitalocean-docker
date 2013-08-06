# Docker on Digitalocean

We're running Ubuntu 13.04 (Digitalocean image id 350076) due to the 3.8 kernel.

This is an example for running Docker on Digitalocean.

Supply your digitalocean API id and key in `packer.json` and run:

    packer build docker.json
