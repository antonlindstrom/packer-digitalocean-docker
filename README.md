# Docker on Digitalocean

We're running Ubuntu 13.04 (Digitalocean image id 350076) due to the 3.8 kernel.

This is an example for running Docker on Digitalocean.

Supply your digitalocean API id and key with the following variables:

    export DIGITALOCEAN_API_KEY=key
    export DIGITALOCEAN_CLIENT_ID=client_id

Then run the following command:

    packer build docker.json
