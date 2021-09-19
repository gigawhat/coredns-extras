# coredns-extras

Coredns container image with the following external plugins added:
* [alternate](https://coredns.io/explugins/alternate/)
* [k8s_gateway](https://coredns.io/explugins/k8s_gateway/)

## Using the container image

The container image tag is the coredns git tag (version) used during the build and the build iteration.  
For example `ghcr.io/gigawhat/coredns-extras:v1.8.4-16` is coredns version `v1.8.4` and the `16`<sup>th</sup> build of that version.

```bash
$ docker pull ghcr.io/gigawhat/coredns-extras:v1.8.4-16 
$ docker run --rm ghcr.io/gigawhat/coredns-extras:v1.8.4-16 -version
CoreDNS-1.8.4
linux/amd64, go1.17.1, 053c4d5c-dirty
```
