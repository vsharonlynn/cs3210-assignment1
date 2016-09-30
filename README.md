Navigate into the directory which contains mm-cuda.cu file.

Compile mm-cuda.cu.
```shell
$ nvcc –arch=sm_32 mm-cuda.cu –o mm-cuda –lcuda -lcudart
```

To run matrix of size 512 x 512.
```shell
$ ./mm-cuda 512
```

To run matrix of size 1024 x 1024.
```shell
$ ./mm-cuda 1024
```
