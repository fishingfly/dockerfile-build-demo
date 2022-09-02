# Build From Tar
compressed dir directory
```
$ tree dir
dir/
├── Dockerfile
└── test
0 directories, 2 files
$ tar  zvcf test.tar.gz dir/
dir/
dir/Dockerfile
dir/test
```
build from tar as follows:
```
docker build -t fishingfly/test https://github.com/fishingfly/dockerfile-build-demo/build-context/build-from-tar/test.tar.gz
```
