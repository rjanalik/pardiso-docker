# pardiso-docker

Docker images used to build PARDISO on systems (with old glibc).

## Examples
```bash
docker build -f Dockerfile-pardiso-centos-7-gcc6.3-icc2023.0 -t rjanalik/pardiso-centos:7-gcc6.3-icc2023.0 .
docker push rjanalik/pardiso-centos:7-gcc6.3-icc2023.0
```
