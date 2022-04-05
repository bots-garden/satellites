# satellites

## Prerequisites

- Install Subo: `./install-subo-amd64.sh`
- Install Sat: `./build-sat-amd64.sh`

## WAPM

Create an account on https://wapm.io/

### Install Wasmer and Wapm

```bash
sudo apt install libncurses5 libxkbcommon0 libtinfo5 libnss3-tools -y
curl https://get.wasmer.io -sSfL | sh 
source /home/gitpod/.wasmer/wasmer.sh
```

### Publish a package

> You need a token

```bash
wapm login ${WAPM_REGISTRY_TOKEN}
cd hello-world
wapm init
# ...

```
