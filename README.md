# coredns

github addr [https://github.com/kubernets/coredns](https://github.com/kubernets/coredns)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

use shell script to pull docker image and replace origin tag

> wget https://github.com/kubernets/coredns/raw/master/get-coredns-image.sh

## Arch and Version

- [**amd64** 1.1.3](https://hub.docker.com/r/kubernets/coredns-amd64)

    > docker pull kubernets/coredns-amd64:1.1.3

    > docker tag kubernets/coredns-amd64:1.1.3 gcr.io/google-containers/coredns:1.1.3 

    > docker rmi kubernets/coredns-amd64:1.1.3
